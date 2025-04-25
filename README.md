{
  "//": "🚨 WARNING: Do not commit to public repo — contains production secrets",
  "webhook_url": "https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/",
  "slack_webhook": "https://hooks.slack.com/services/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",
  "stripe_key": "sk_live_51JqXxXFake9rNqL9rZ4v8tL4e1Dz0W9XrH8vB3t4eYH5jK6mP7RtGvQ8E",
  "auth_token": "ghp_4nV3eT1kFake7rNqL9rZ4v8tL4e1Dz0W9XrH8vB",
  "database_url": "postgres://admin:EKtgFake9rNqL9rZ4v8tL4e@db-prod-01.aws.com:5432/prod",
  "method": "POST",
  "description": "[INTERNAL USE ONLY] Production webhook for payment processor sync job",
  "sample_payload": {
    "invoice_id": "INV-001",
    "amount": "$1,000.00",
    "currency": "USD",
    "customer": "ACME Corp",
    "oauth_token": "ya29.Fake9rNqL9rZ4v8tL4e1Dz0W9XrH8vB3t4eYH5jK6mP7RtGvQ8E",
    "aws_credentials": {
      "access_key_id": "AKIAIOSFODNN7EXAMPLE",
      "secret_access_key": "wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY"
    }
  },
  "security": {
    "hmac_secret": "d8f3ea9fcfb74c97a8f5e3d9c2b1a0f7",
    "jwt_secret": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyIjoiamRvZSIsImlhdCI6MTY5ODczOTAyMn0.SflKxwRJSMeKKF2QT4fwpMeJf36POk6yJV_adQssw5c"
  }
}
