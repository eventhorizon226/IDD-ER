# IDDx Annotator Tool

This tool helps you annotate the IDDx dataset videos for research and analysis. Most users should use the deployed version:

👉 **[Use the Annotator Tool Online](https://iddx-annotator.frii.site/annotate)**

---

## How to Use the Annotator Tool

1. **Prepare Your Videos**
   - The annotator only supports videos in `.mp4` format with the H.264 (x264) codec.
   - IDDx dataset videos must be batch converted before uploading.
   - Use [HandBrake](https://handbrake.fr/) or a similar tool:
     - Add your videos to HandBrake.
     - In the **Video** tab, set the **Video Codec** to `H.264 (x264)`.
     - Export as `.mp4` files.

2. **Open the Annotator**
   - Go to [https://iddx-annotator.frii.site/annotate](https://iddx-annotator.frii.site/annotate)

3. **Upload Your Videos**
   - Click the upload area and select your prepared `.mp4` videos.
   - Wait for the videos to load in the interface.

4. **Annotate**
   - Use the provided controls to play, pause, and navigate frames.
   - Select or draw labels as required for your annotation task.
   - Save your annotations as instructed in the interface.

5. **Download/Export**
   - After annotating, download your results for further use.

---

## FAQ

**Q: Why can't I upload my IDDx videos directly?**
A: The tool only supports `.mp4` files with H.264 codec. Convert your videos using HandBrake or a similar tool before uploading.

**Q: Can I run this tool locally?**
A: Yes, but most users should use the online version. To run locally:

```bash
pnpm install
pnpm dev
# Then open http://localhost:3000 in your browser
```

---

For issues or suggestions, please open an issue on this repository.
