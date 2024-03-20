# Ueberschriftengenerator_LEOLM
My fine tuned german language model with training parameters, code and some training information

Access the model to fine tune it for your own purpose: 

from transformers import AutoTokenizer, AutoModelForCausalLM

tokenizer = AutoTokenizer.from_pretrained("Kamilatr/Ueberschriftengenerator_LEOLM", trust_remote_code=True) model = AutoModelForCausalLM.from_pretrained("Kamilatr/Ueberschriftengenerator_LEOLM", trust_remote_code=True)

View additional information about the fine tuned model on my hugging face hub repo: https://huggingface.co/Kamilatr/Ueberschriftengenerator_LEOLM

You can find the entire code in newrepo.py


The .png file contains a picture with the training loss
