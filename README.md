using this curl for test
```
curl -i -X POST \
   -H "Content-Type:application/json" \
   -d \
'{
  "fromEmail": "noreply@[YOUR_COMPANY]",
  "toEmail": "test@[YOUR CUSTOMER]",
  "subject": "test email",
  "body": "Hi, This is a test email."
}' \
 'http://localhost:8080/sendEmail'
```