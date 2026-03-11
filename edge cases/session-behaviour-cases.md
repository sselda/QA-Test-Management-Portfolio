## Session Behaviour Cases

| ID | Edge Case | Test Data | Expected Results |

| EC-01| Login then refresh page | Login succesfully and refresh the browser | User should remain logged in and session should persist

| EC-02| Login then Open new tab | Login and open the application in a new tab | User should still be authenticated |

| EC-03 | Login then use browser back button | Login, navigate forward, then press browser back | User should not see cached login page or be logged  out incorrectly | 

