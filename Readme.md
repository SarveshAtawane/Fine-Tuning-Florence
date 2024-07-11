# For the davit error

### Keep this as it as and copy the rest part from the config.json
```bash
{
  "_name_or_path": "model_checkpoints/epoch_2",
  "architectures": [
    "Florence2ForConditionalGeneration"
  ],
  "auto_map": {
    "AutoConfig": "configuration_florence2.Florence2Config",
    "AutoModelForCausalLM": "modeling_florence2.Florence2ForConditionalGeneration"
  },
 ``` 