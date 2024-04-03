
#ChatGLM微调

CUDA_VISIBLE_DEVICES=0 python  finetune_hf.py data/AdvertiseGen_fix /home/chendz/llm/model/chatglm3-6b configs/lora.yaml 

CUDA_VISIBLE_DEVICES=0 python  inference.py output/checkpoint-1000/ --prompt 类型#群*群长#半身裙 
