# 公开测试计划

这里存放可以公开分享的测试计划，方便一起查看和更新。

## 这个仓库是做什么的

把对外可分享的测试计划集中放在这个仓库里。每份计划是一个 Markdown 文件，写清要测什么、在什么环境测、怎样算通过。

## 建议的目录

```text
test-plans/     每份计划一个 Markdown 文件
templates/      可选，放计划模板
```

## 文件怎么命名

用小写英文和连字符，让文件名能看出主题。需要按时间排序时，可以在前面加上日期：

- `test-plans/login-smoke.md`
- `test-plans/2026-10-16-checkout.md`

## 一份计划里写什么

- **范围**：测什么，不测什么
- **环境**：系统、版本，以及需要的账号或数据
- **测试用例**：具体步骤，别人可以照着做
- **预期结果**：通过时长什么样
- **状态**：草稿、进行中或已完成

## 不要提交机密

仓库是公开的。密码、密钥、内网地址、客户数据和其他不能公开的内容，都不要放进来。

---

# Public Test Plans

A small home for test plans that are fine to share in public.

## What this repo is for

Keep publicly shareable test plans here. Each plan is one Markdown file: what to test, where to run it, and how to tell that it passed.

## Suggested layout

```text
test-plans/     one Markdown file per plan
templates/      optional folder for plan templates
```

## Naming

Use lowercase words and hyphens so the filename shows the topic. Add a date at the front when you want plans to sort by time:

- `test-plans/login-smoke.md`
- `test-plans/2026-10-16-checkout.md`

## What a test plan should contain

- **Scope**: what is covered, and what is left out
- **Environment**: system, version, and any accounts or data you need
- **Test cases**: concrete steps someone else can follow
- **Expected results**: what a pass looks like
- **Status**: draft, in progress, or done

## Nothing confidential

This repository is public. Do not commit passwords, keys, internal addresses, customer data, or anything else that should stay private.
