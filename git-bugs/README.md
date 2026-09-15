# Bug Tracker Export

این پوشه از فایل تست اکسل به یک ساختار مناسب نگهداری در Git تبدیل شده است.

## Summary

| Module | Total | Open | Partially Fixed | Closed |
|---|---:|---:|---:|---:|
| قراردادها | 117 | 52 | 3 | 62 |
| نمایندگان | 166 | 147 | 0 | 19 |
| مدیریت سفارشات | 40 | 40 | 0 | 0 |
| **Total** | **323** | **239** | **3** | **81** |

## Files

- `contracts.md` — باگ‌های قراردادها
- `agents.md` — باگ‌های نمایندگان
- `order-management.md` — باگ‌های مدیریت سفارشات
- `issue-template.md` — قالب پیشنهادی برای ثبت باگ‌های جدید

## ID Convention

- `CON-xxx` → قراردادها
- `AGT-xxx` → نمایندگان
- `OMS-xxx` → مدیریت سفارشات

## Status Mapping

- `fixed (pass)` → `Closed`
- `partially fixed` → `Partially Fixed`
- سایر موارد → `Open`

## Suggested Git Labels

`bug`  
`module:قراردادها`  
`module:نمایندگان`  
`module:مدیریت سفارشات`  
`priority:major` / `priority:medium` / `priority:minor`  
`status:open` / `status:closed` / `status:partially-fixed`

> نکته: چون در فایل مبدا برای بسیاری از موارد Priority ثبت نشده، مقدار آن‌ها `unspecified` نگه داشته شده و چیزی حدس زده نشده است.
