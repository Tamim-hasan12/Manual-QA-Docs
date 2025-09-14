#  Login Module – Manual Test Cases

| Test Case ID | Description                     | Steps to Execute                        | Expected Result             | Status |
|--------------|----------------------------------|------------------------------------------|-----------------------------|--------|
| TC001        | Valid login                     | Enter valid email and password           | Redirect to dashboard       | Pass   |
| TC002        | Invalid password                | Enter valid email and wrong password     | Show error message          | Pass   |
| TC003        | Empty fields                    | Leave email and password blank           | Show validation errors      | Pass   |
| TC004        | SQL injection attempt           | Enter `' OR '1'='1` in email field       | Show error / block request  | Pass   |

