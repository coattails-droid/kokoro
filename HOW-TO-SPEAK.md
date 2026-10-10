# How to make Kokoro talk (no computer setup needed)

GitHub runs Kokoro for you on its own free computers. You just type text and download the audio.

1. Open this repository on github.com and click the **Actions** tab at the top.
2. On the left, click **speak**.
3. On the right, click the **Run workflow** button.
4. Type what you want it to say in the **Text to speak** box.
   - Optional: change the **Voice** (for example `af_heart`, `af_bella`, `am_michael`, `bf_emma`, `bm_george`) and the **Speed** (1.0 is normal).
5. Click the green **Run workflow** button.
6. Wait a few minutes. Refresh the page; when the run shows a green check mark, click on it.
7. Scroll down to **Artifacts** and click **speech**. It downloads a zip file.
8. Open the zip. Inside are `speech.mp3` and `speech.wav`. Double-click either one to listen.

Tips:
- The first run of a new voice is slower because it downloads that voice. Later runs are faster.
- Each run uses a few of your free GitHub Actions minutes (private repos get 2,000 free minutes a month).
- The audio file is kept on GitHub for 7 days, so download it soon after it finishes.
- Voice names start with a letter for the language: `a` = US English, `b` = UK English, `e` = Spanish,
  `f` = French, `h` = Hindi, `i` = Italian, `p` = Portuguese, `j` = Japanese, `z` = Chinese.
  The second letter is `f` for a female voice or `m` for a male voice.
