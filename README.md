# IQ Voice for Windows

IQ Voice turns speech into text and pastes it into the app you’re typing in.

[Download IQ Voice for Windows](https://github.com/N9ALV/iq-voice-downloads/releases/latest)

## Install

To get help with installation, paste the download link into IQ Wealth with this request.

> Please download and install IQ Voice for me from this link. Help me finish setup and try a short dictation in this chat.

IQ Wealth can download and run the installer when it has permission to run commands on your PC. Follow any prompts that need your approval.

To install it yourself, download the Windows x64 `.exe` under **Assets** and run it. IQ Voice requires 64-bit Windows 10 or later and a graphics driver with Vulkan support. The installer is unsigned.

Open **IQ Voice** from the Start menu, allow microphone access when prompted and wait for the speech model to finish downloading.

## Use IQ Voice in IQ Wealth

1. Open an IQ Wealth chat and click the message box.
2. Hold **Ctrl+Space** while you speak, then release it. Keep the cursor in the message box while IQ Voice pastes the text.
3. Review the text and send it when you’re ready. For a first try, say “Please summarise the main points of this chat.”

For help choosing a shortcut or getting the transcript to paste, ask IQ Wealth “Help me check my IQ Voice settings and try another dictation.”

## Dictate

- To dictate in another app, click the text field where you want the words to go.
- **Ctrl+Space** by default. Hold it while you speak, then release to paste. If you prefer to tap once to start and again to stop, change **Shortcut mode** in **General**.
- **Escape** discards the recording while you’re still speaking.
- **Ctrl+Alt+V** pastes the last dictation again.

Open IQ Voice from the notification area to change your shortcut or microphone, or to view recent dictations in **History**.

## Optional rewriting

Ordinary dictation transcribes audio on your PC. If you have an OpenRouter account, set your own `OPENROUTER_API_KEY` as a Windows user environment variable. Quit IQ Voice from its notification-area menu and open it again. Enable **Polish dictation shortcut** in **Labs**, then use **Ctrl+Shift+Space** with the same hold or tap behaviour as your main shortcut.

The optional shortcut sends the transcript and rewrite instructions to OpenRouter. Your provider may charge for the request. If rewriting fails, IQ Voice pastes the transcription.

[Troubleshooting](TROUBLESHOOTING.md)

IQ Voice is based on [Hex](https://github.com/anomalyco/hex). The installer includes the Hex licence and third-party notices.
