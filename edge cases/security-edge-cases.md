# Security Edge Cases

| ID | Edge Case | Test Data | Expected Results | 

| EC-01 | XSS Payload in Login | Enter <script>alert(1)</script> in input fields | Script should not execute and login should fail or sanitize input

| EC-02 | Brute Force Login Attempts | Perform multiple rapid login attempts with incorrect passwordss | System should throttle requests, lock account or trigger protection|
