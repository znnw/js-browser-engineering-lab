# Security Policy / 安全说明

## Supported Versions

Security fixes are applied to the latest state of the `main` branch.

安全修复仅针对 `main` 分支的最新内容。

## Reporting a Vulnerability

This is a static educational project and does not include a backend, database, or real authentication service. If you discover exposed credentials, unsafe HTML injection that could mislead users, a malicious dependency reference, or another security issue, please report it privately through GitHub Security Advisories for this repository.

Please do not publish exploitable details in a public issue before the report has been reviewed.

本仓库是静态教学项目，不包含后端、数据库或真实认证服务。如发现凭据泄露、可能误导用户的不安全 HTML 注入、恶意依赖引用或其他安全问题，请优先通过 GitHub Security Advisories 私密报告，不要在修复前公开可利用细节。

## Scope Notes

- Demo form validation is client-side only and must not be treated as a security boundary.
- `localStorage` data is intended for local demonstration and must not contain sensitive information.
- Third-party CDN resources and remote media are outside this repository's control.
