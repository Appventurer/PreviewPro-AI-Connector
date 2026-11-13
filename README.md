# PreviewPro AI Connector

Connect PreviewPro for Mac to your installed Codex CLI or Claude Code using your own account.

## Download

**[Download PreviewPro AI Connector for Mac](https://github.com/Appventurer/PreviewPro-AI-Connector/raw/refs/heads/main/Downloads/PreviewProAIConnector-13.1.zip)**

Version 13.1 (1124) · macOS 15 or later · Apple Silicon and Intel

Signed with Developer ID and notarized by Apple. [SHA-256 checksum](Downloads/SHA256SUMS).

## Set up

1. Download and unzip the file. Move **PreviewPro AI Connector.app** to **Applications**, then open it.
2. Install [Codex CLI](https://developers.openai.com/codex/cli) or [Claude Code](https://code.claude.com/docs/en/setup), following the provider’s official guide.
3. Sign in through the tool in Terminal: `codex login` or `claude auth login`.
4. In the connector, choose **Copy pairing code**. In PreviewPro’s AI setup, paste it and choose **Pair and check connection**.
5. Leave the connector running while using AI in PreviewPro. Close its window to quit and stop active requests.

If PreviewPro cannot find the connector, choose **Choose connector…** in its setup and select the app. If a provider tool is installed in a custom location, use **Choose Codex…** or **Choose Claude Code…** inside the connector.

The connector is free. It accepts paired requests only on this Mac and uses the unmodified provider tool; PreviewPro does not read provider passwords or session tokens. Prompts, selected images and layouts are sent by that tool to its provider. Your provider’s subscription eligibility, billing, and usage limits apply; there are no PreviewPro AI credits. Requests already sent may count toward provider usage even if canceled. PreviewPro is independent of OpenAI and Anthropic.
