# ChatRWKV

ChatRWKV is an advanced language model that is similar to ChatGPT. It is powered by the RWKV (100% RNN) language model, which is the only RNN that can match transformers in quality and scaling, while being faster and saves VRAM.

## Getting Started

To get started with ChatRWKV, you should upgrade to the latest code to ensure that you have the most stable version. You can download the RWKV-4 weights from https://huggingface.co/BlinkDL. Note that you should use RWKV-4 models and not RWKV-4a and RWKV-4b models.

The RWKV LM project on GitHub (https://github.com/BlinkDL/RWKV-LM) provides more information about the model, including how to fine-tune and train it. You can also join the RWKV Discord community (https://discord.gg/bDSBUMeFpc) to connect with other developers and build together.

Some great community projects include:

- [rwkvstic](https://pypi.org/project/rwkvstic/): an easy pip package with 8bit & offload for low VRAM GPUs
- [WebChatRWKVstic](https://github.com/hizkifw/WebChatRWKVstic): a WebUI (WIP)
- [rwkv_gradio](https://github.com/gururise/rwkv_gradio): RWKV Gradio

## Usage

The model is not yet fine-tuned for conversation, so don't directly ask it to do things unless it's a simple question. For Instruct-test1 RWKV-4 models, you can use the `+gen` command followed by a prompt. For all RWKV-4 models, there are some great Q&A prompts that you can use. 

### Examples

Some examples of prompts include:

```sql
+gen \nExpert Questions & Helpful Answers\nAsk Research Experts\nQuestion:\nCan penguins fly?\n\nFull Answer:\n
+gen \nAsk Expert\n\nQuestion:\nWhat are some good plans to kill all mosquitoes?\n\nExpert Full Answer:\n
+gen \nQ & A\n\nQuestion:\nHow's the weather of Mars?\n\nDetailed Expert Answer:\n
```

## Chinese Model

The readme also includes information about the Chinese model, including download links for the big, medium, and small models. If you don't have a GPU, you can use the CPU mode, but it will be slower. The readme also provides examples of "magic spells" or prompts you can use with the Chinese model.

### Examples

Some examples of Chinese magic spells or prompts include:

```sql
+gen 这是一颗
+gen 下面是科幻史诗长篇巨著，描写细致，有数百位英雄人物和宏大的星际文明战争，情节曲折离奇。\n第一章
+gen 这是一个修真世界，详细世界设定如下：\n1.
```

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=BlinkDL/ChatRWKV&type=Date)](https://star-history.com/#BlinkDL/ChatRWKV&Date)

## Links

- RWKV LM: https://github.com/BlinkDL/RWKV-LM (explanation, fine-tuning, training, etc.)
- RWKV Discord: https://discord.gg/bDSBUMeFpc
