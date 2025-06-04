## What I did

1. Forked from the [Modal examples](https://github.com/modal-labs/modal-examples) repository.
2. Run the following commands to set up uv:
    ```bash
    uv init
    uv add modal
    ```

## Running the examples

Run on Modal:

```bash
uv run modal run 06_gpu_and_ml/llm-serving/trtllm_latency.py
```

Deploy to Modal:

```bash
uv run modal deploy 06_gpu_and_ml/llm-serving/trtllm_latency.py
```

Start a local interactive chat client that connects to the deployed Modal LLM serving endpoint:

```bash
uv run 06_gpu_and_ml/llm-serving/trtllm_latency.py
```
