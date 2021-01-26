# Static website for audio demos
This is a simple static website for demoing audio samples in the browser. This will be mainly used for the project found [here](https://github.com/atliSig/Real-Time-Voice-Cloning).

## Adding a new page
It's simple to add a new page.
1. Simply copy the `template` directory under `pages` and rename.
2. Then link to that page on the main `index.html` to make it visible on the index.
3. Put all audio to be included under the `audio` directory in your new page directory.
4. To include it on the page use the following HTML `<audio controls=""><source src="audio/path_to_your_file.wav"></audio>`
5. Commit and push the code. Your new page should now be visible at [this domain](https://atlisig.github.io/cloning_samples/).