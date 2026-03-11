# Authentication Edge Cases

| ID | Edge Cases | Test Data | Expected Result |

| EC-01 | Email with leading spaces | “     user@test.com“ | Spaces trimmed or validation error |

| EC-O2 | Email with trailing spaces | “user@test.com     “ | Login should still work or show validation |

| EC-03 | Email with uppercase characters | USER@TEST.COM | System should treat email as case-intensive | 

| EC-O4 | Password with unicode characters | pässwørd123 | System should handle unicode characters |

| EC-05 | Extremely long password | 500 characters | Validation error or max length enforced |

| EC-06 | SQL injection attempt | ‘ OR 1=1 -- | Login should fail and sanitize input |

| EC-07 | Multiple rapid login attempts | 20 attempts in 10 sec | Account lock or rate limit |

| EC-08 | Empty email field | "" | Validation message displayed | 

| EC-09 | Empty password field | "" | Validation message displayed |

| EC-10 | Both fields empty | "" "" | Form validation error | 

