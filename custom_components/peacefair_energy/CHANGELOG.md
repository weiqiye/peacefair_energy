# Changelog 更新日志

## v3.11.2 (2026-10-10)

- 修复：实体 ID 域名错误。实体 ID 由 `peacefair_energy.*` 改为 `sensor.*`，消除 Home Assistant 2026.10 的警告，避免 HA 2027.5.0 后失效。`unique_id` 保持不变，现有实体注册信息和自动化不受影响。
- Fix: entity ID domain mismatch. Entity IDs changed from `peacefair_energy.*` to `sensor.*`, removing the warning on HA 2026.10 and breakage expected in HA 2027.5.0. `unique_id` values are unchanged, so existing entity registry entries and automations are not affected.

## v3.11.1

- 历史版本 / Prior release.
