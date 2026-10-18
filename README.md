# FLUX-3-KLEIN-vs-FLUX-2-KLEIN-9B-workflow
I have built 2 workflows to benchmark FLUX 3 KLEIN and FLUX 2 KLEIN 9B.

FLUX 3 KLEIN: int8.convrot
FLUX 2 KLEIN 9B: FP8
LLM with vision: QWEN 3.5

Performance (1024x1024) Text-to-Image: About 28 sec with a 5070ti, 56 sec with a 5060ti (2nd gen/warm)
Performance (1024x1024) Image-to-Image: About 35 sec with a 5070ti, 70 sec with a 5060ti (2nd gen/warm)

The 2 workflows generate a big image with the 2 images and the model's name on it. So you can easily share your results on social networks.

More images with prompts: https://h2logs.substack.com/p/flux-3-klein-vs-flux-2-klein-9b
