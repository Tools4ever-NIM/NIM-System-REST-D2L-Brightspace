# NIM-System-REST-D2L-Brightspace
D2L Brightspace

![image](https://github.com/Tools4ever-NIM/NIM-System-REST-D2L-Brightspace/assets/24281600/8cfcd29f-52bd-4c3c-9fb3-7400e2714905)


# Setup Authorization
- Login to the Brightspace portal as admin
- Go to Settings > Manage Extensibility
- Click "OAuth 2.0"
- Click "Register an App"
- Configure App
    - Name: "Tools4ever NIM"
    - Redirect URI: <Copy from NIM System configuration screen>
    - Scope: "attributes:*:* core:*:* role:*:* sessions:*:* users:*:*"
    - Access Token Lifetime (seconds): 72000
    - Prompt for user consent: Unchecked
    - Enable refresh tokens: Checked
- Add Client ID and Secret to NIM System configuration screen and click "Retrieve Token"
