# Agnes media

Media files for the Agnes landing page and docs. Each demo video comes with a WebM and an MP4 encode, an English `.vtt` caption file and a `.png` poster. The subtitles are also burned into the video, below the frame.

| File | Shows |
|------|-------|
| `demo/01-ask-from-anywhere-en` | A request typed into a web session. Claude Code runs it and replies. |
| `demo/02-understands-code-en` | The code views: flow, states, impact and skyline. |
| `demo/03-connect-one-command-en` | Connecting a computer with one command. |
| `demo/04-plans-en` | The plans and the 14-day trial. |
| `demo/05-orca-live-terminal-en` | A chat request opens a live Claude Code terminal in Orca. |

Every video is 1280x840 with no audio. The scripts that record them live in the main Agnes repo, under `docs/demo-videos/scripts/`.

```html
<video autoplay muted loop playsinline width="1280" height="840" poster="demo/01-ask-from-anywhere-en.png">
  <source src="demo/01-ask-from-anywhere-en.webm" type="video/webm">
  <source src="demo/01-ask-from-anywhere-en.mp4" type="video/mp4">
  <track kind="captions" srclang="en" label="English" src="demo/01-ask-from-anywhere-en.vtt">
</video>
```
