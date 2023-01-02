# Fine-Tuning-Whisper
Fine tuned Whisper ASR by using Open CV Hindi Dataset

### Framework versions

<ol>
<li>Transformers 4.26.0.dev0</li>
<li>Pytorch 1.13.0+cu116</li>
<li>Datasets 2.8.0</li>
<li>Tokenizers 0.13.2</li>
</ol>

Deployment of the above setup can be found here at Huggingface: https://huggingface.co/spaces/Ranjit/Ranjit-whisper-small-hi

The model prepared here is a fine-tuned version of <a href="https://huggingface.co/openai/whisper-small">openai/whisper-small</a> model on the <a href="https://huggingface.co/datasets/mozilla-foundation/common_voice_11_0/viewer/hi/train">Common Voice 11.0 dataset</a>. It achieves the following results on the evaluation set:

Loss: 0.4292
</br>
Wer: 32.0452

More details about the model can be found <a href="https://huggingface.co/Ranjit/whisper-small-hi">here</a>. 
