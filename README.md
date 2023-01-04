# waifu-v1-4使ってみたメモ.

## 最低限推論環境ライブラリ
```
pip install git+https://github.com/huggingface/diffusers 
pip install torch==1.13.0 torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu116
pip install transformers
pip install accelerate
```

推論
```
python waifu1-4.py
```

![hoge](000.png)

## 参考ページ

### 推論時のメモリ節約方法.
https://huggingface.co/docs/diffusers/optimization/fp16
https://baskmedia.jp/novelai-code-of-the-elements1/

### diffuserの解説
https://huggingface.co/blog/stable_diffusion