Large language models (LLMs) represented by ChatGPT and GPT-4 have set off a new wave of research in the field of natural language processing, demonstrating capabilities similar to general artificial intelligence (AGI), and have attracted widespread attention in the industry.
  

In order to promote the development and implementation of LLMs in the field of Chinese medicine and enhance LLMs' medical knowledge and ability to answer medical consultations, we now launch the ChatMed series of Chinese medical large-scale language models:
  

### Testing the model’s performance

step1
```bash
python src/web_services/web_service_simple.py
```

step2
```bash
python src/web_services/web_service_test.py
```

### Train model
First, you need to prepare the LlaMA-7b base model.

```bash
./src/med_llama_peft/run_train.sh
```

## dataset  
```json
{"instruction": "If you are a doctor, please answer the medical questions based on the patient's description.", "input": "Doctor, I have been experiencing sudden and frequent panic attacks. I don't know what to do.", "output": "Well, based on what you're telling me, it sounds like you may be suffering from panic disorder. The best course of action is to start with psychotherapy and mental health counseling. Additionally, we should conduct an electrocardiogram to make sure that there are no physical issues causing your panic attacks. We will also need to perform a depression screen and a toxicology screen to rule out any other underlying causes. Finally, I would recommend a comprehensive psychological and psychiatric evaluation and therapy to help manage your symptoms."}
```









