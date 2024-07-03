# Stable-Diffusion_Using_PyTorch
Stable Diffusion From Scratch Using PyTorch

How to use: 
Clone the repo on your machine
"https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main"
Download following files from above link:
1. merges.txt and vocab.json from tokenizer folder
2. v1-5-pruned-emaonly.ckpt
3. put these file in the "data" folder
4. Add your prompt to the prompt variable in the demo.ipynb file (for text-to-image)
5. Add negative prompts to the uncond_prompt variable
6. Add your reference image path to the image_path variable
7. RUN the cell and Voila!
