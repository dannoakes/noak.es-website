# Setup and Usage Instructions for the Static Short URL Service

## Web UI
1. Navigate to the web UI by visiting `http://yourdomain.com/ui`.
2. Log in with your credentials.
3. Use the interface to create and manage your short URLs.

## Generating Static Redirect Pages
To generate static redirect pages:
1. Create a new entry in the dashboard.
2. Specify the target URL and the desired short URL.
3. Save the changes and the static redirect page will be generated.

## Authenticating with GitHub Personal Access Token
1. Go to your GitHub account settings.
2. Navigate to Developer settings > Personal access tokens.
3. Click on "Generate new token" and select the necessary scopes (e.g., repo).
4. Copy the generated token and use it in your application configuration.

5. Set the token in your environment variables:
   ```bash
   export GITHUB_TOKEN=your_token_here
   ```
6. Now, your application will be able to authenticate with GitHub using the token.