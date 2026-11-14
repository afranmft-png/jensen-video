# Your Life as MrBeast

Full-quality 1080p master (9:30, H.264, AAC 320 kbps, −14 LUFS), split into 11 parts so each file stays under GitHub's 100 MB limit.
Each part plays on its own.

## Join the parts back into one file

Download all 11 `mrbeast-full_partNNof11.mp4` files and `parts.txt` into one folder, then run (needs ffmpeg):

```bash
ffmpeg -f concat -safe 0 -i parts.txt -c copy mrbeast-full.mp4
```

This is a lossless join (no re-encoding): you get back the original 17,098-frame master.

Also here: `thumbnail.png` (1280×720), `CREDITS.md`, and `description_credits.txt` (paste into the YouTube description).
