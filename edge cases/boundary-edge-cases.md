## Boundary Edge Cases

| ID | Edge Case | Test Data | Expected Results |

| EC-01 | Email with 254 characters | Enter the maximum valid email length | System should accept valid length and process normally |

| EC-02 | Password with 1000 characters | Attempt login with an extremely long password | System shouldmhandle input safely without crashing |

| EC-03| Email without domain | Use email like user@ or user | Validation should reject invalid email format |
