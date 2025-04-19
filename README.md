# Using-Stable-Diffusion-in-Colab-for-free
Using Stable Diffusion in Colab for free including NSFW content.  
Since can't use WebUI or ComfyUI without Colab Pro.  
It's the only way that can use for free.  
## Step 1.   
Create a folder name lora in Google drive.  
Upload your LoRA to the folder.  
Make sure your LoRA support the base model.  
If don't use LoRA, skip this step.  
## Step 2.  
Open stablediffusion.ipynb in Google Colab.  
Change runtime type to GPU.  
## Step 3.  
In https://huggingface.co/models?library=diffusers&sort=trending find the base model you want to use.  
Copy the model name in the website.  
Replace the model name in block 3.  
## Step 4.  
Change the LoRA name in block 5.  
You can also use multiple LoRA by uncommenting.  
## Step 5.  
Edit the prompt, negative prompt and other parameters in block 6.
## Step 6.  
Run all the block.  
If don't use LoRA, skip block 4 and 5.  
## Reference  
https://www.youtube.com/watch?v=8_V8CO_Dbdw&t=2s
