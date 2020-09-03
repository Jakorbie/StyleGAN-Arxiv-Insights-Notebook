# StyleGAN-Arxiv-Insights-Notebook
These are the notebooks I forked from this [youtube video](https://www.youtube.com/watch?v=dCKbRCUyop8&amp;t=1363s)

# Debugging Notes


1. [tqdm Error while running encode_images.py](https://github.com/pbaylies/stylegan-encoder/issues/41#issuecomment-568890957)

The problem occurs because of the incorrect tqdm version pre-installed in google colab. \
Downgrade it to tqdm==4.24.0 \
`!pip install --force tqdm==4.24.0`

2. [OSError: Google Drive quota exceeded](https://github.com/pbaylies/stylegan-encoder/issues/41#issuecomment-568738429)

Remember to only change the ID hash in the url. Do not directly use the shareable link of the google file.

 
