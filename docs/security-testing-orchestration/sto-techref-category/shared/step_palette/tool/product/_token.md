The access token used to log in to a specific product in the scanner. This is required for some scans. In most cases this is a password or an API key. 
You should create a Harness text secret with your encrypted token and reference the secret using the format `<+secrets.getValue("container-access-id")>`. For more information, go to [Add and Reference Text Secrets](/docs/platform/secrets/add-use-text-secrets).

