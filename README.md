# IQ Voice for Windows

IQ Voice turns speech into text and pastes it into the app you’re typing in.

## Install

1. Download and run the IQ Voice Windows x64 installer from the Releases page. It requires 64-bit Windows 10 or later and a graphics driver with Vulkan support.
2. Open **IQ Voice** from the Start menu. Follow setup, allow microphone access and wait for the speech model to finish downloading.
3. Open a text field and try a short dictation.

## Dictate

- **Ctrl+Space** by default. Hold it while you speak, then release to paste. If you prefer to tap once to start and again to stop, change **Shortcut mode** in **General**.
- **Escape** discards the recording while you’re still speaking.
- **Ctrl+Alt+V** pastes the last dictation again.

Open IQ Voice from the notification area to change your shortcut or microphone, or to view recent dictations in **History**.

## Optional rewriting

Ordinary dictation transcribes audio on your PC. If you have an OpenRouter account, set your own `OPENROUTER_API_KEY` as a Windows user environment variable. Quit IQ Voice from its notification-area menu and open it again. Enable **Polish dictation shortcut** in **Labs**, then use **Ctrl+Shift+Space** with the same hold or tap behaviour as your main shortcut.

The optional shortcut sends the transcript and rewrite instructions to OpenRouter. Your provider may charge for the request. If rewriting fails, IQ Voice pastes the transcription.

[Troubleshooting](TROUBLESHOOTING.md)

IQ Voice is based on [Hex](https://github.com/anomalyco/hex). The installer includes the Hex licence and third-party notices.
