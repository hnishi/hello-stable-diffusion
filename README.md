# hello-stable-diffusion

https://huggingface.co/stabilityai/stable-diffusion-2-1

```shell
pipenv install diffusers transformers accelerate scipy safetensors
```

```shell
pipenv run python main.py
```

GPT のみ対応。

> RuntimeError: "LayerNormKernelImpl" not implemented for 'Half'

https://github.com/huggingface/transformers/issues/21989#issuecomment-1458129116
