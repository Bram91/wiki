### Using Jagex Accounts

If you have converted your account to a Jagex Account and can no longer login directly to RuneLite, but want to do RuneLite development, follow this guide:

1. Make sure your *RuneLite launcher* is version 2.6.3 or newer
2. Run `RuneLite (configure)` from the start menu. If you don't use Windows, pass `--configure` to the launcher.
3. In the `Client arguments` input box add `--insecure-write-credentials`
4. Click Save
5. Launch RuneLite via the Jagex launcher. RuneLite will write your launcher credentials to `.runelite/credentials.properties`. **Do not share this file with anyone.**
6. Launch RuneLite client (eg. via the IDE) and it will use the saved credentials.