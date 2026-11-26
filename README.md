# AI Spirit – connector for Claude, ChatGPT and Gemini CLI

AI Spirit is a personal assistant that runs on your own Windows PC. This repository only contains the small connection files that let an AI app talk to **your own** Spirit through the AI Spirit connector at `https://relay.get-ai-spirit.com/mcp`. It contains no Spirit software and no data.

**What the AI can do:** search the notes and files you shared with Spirit, read a note, explore connections in your notes (knowledge map) and save a new draft in your Spirit work folder.

**What it can't do – by design:** delete anything, spend money, buy things, control your PC or phone, open programs or websites, or generate images, video or audio.

## How to connect
1. Install AI Spirit on your Windows PC (https://get-ai-spirit.com) and pair the AI Spirit app.
2. In the app open **Account & Connections → Connect with Claude or ChatGPT** to get a one-time code (valid 10 minutes).
3. Add this connector in your AI app and enter the code on the AI Spirit sign-in page.
   - Gemini CLI: `gemini extensions install https://github.com/facesaft-sudo/ai-spirit`
   - Claude / ChatGPT: add the connector address `https://relay.get-ai-spirit.com/mcp`

Disconnect at any time under **My devices** in Spirit. Your PC must be on and Spirit running.

- Privacy: https://relay.get-ai-spirit.com/privacy
- Terms: https://relay.get-ai-spirit.com/terms
- Help: https://relay.get-ai-spirit.com/support · support@get-ai-spirit.com
