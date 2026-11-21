# CLIPFORGE Engine v0.1

A cloud-first prototype that transcribes a video, ranks candidate moments, and renders vertical clips with subtitles.

## Run it

1. Create a GitHub repository named `clipforge`.
2. Upload `CLIPFORGE_Engine_v0_1.ipynb` to the repository.
3. Open [Google Colab](https://colab.research.google.com/).
4. Choose **File → Upload notebook** and select the notebook.
5. Optionally choose **Runtime → Change runtime type → T4 GPU** if available.
6. Run cells from top to bottom.
7. In the source cell, choose `upload` or `youtube`.
8. Download the ZIP produced at the end.

## Requirements

No local Python installation or GPU is required. Use a browser and internet connection. Google Colab free resources are limited and not guaranteed.

## Responsible use

Only process videos you own or have permission to use. YouTube downloading may be restricted by YouTube's terms and the copyright owner's rights. Use authorized source files where downloading is not permitted.

## Current limitations

- English transcription only.
- Transcript-based heuristic moment ranking (not a viral guarantee).
- Center crop to 9:16; no face tracking yet.
- Segment-level subtitles; no word-by-word highlighting yet.
- Colab sessions can disconnect; save outputs to your computer/Drive.
