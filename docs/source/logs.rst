Latest Logs From Latest Build
==============================

Generated On: 2026-03-15 18:10:22 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/makaeron/raspberrypitss/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2026-03-15_18:08:05] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2026-03-15_18:08:11] STEP 2: Create topics started

  [INFO 2026-03-15_18:08:31] STEP 2: Completed

  [INFO 2026-03-15_18:08:44] STEP 3: producing data started

  [INFO 2026-03-15_18:08:51] STEP 3: reading local file..successfully

  [INFO 2026-03-15_18:08:52] STEP 4: Preprocessing started

  [INFO 2026-03-15_18:08:54] STEP 4: Preprocessing started

  [INFO 2026-03-15_18:09:01] STEP 5: Machine learning started

  [INFO 2026-03-15_18:09:08] STEP 6: Predictions started

  [INFO 2026-03-15_18:09:11] STEP 7: Visualization started

  [INFO 2026-03-15_18:09:17] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2026-03-15_18:09:26] STEP 9b: Starting ollama server

  [INFO 2026-03-15_18:09:37] STEP 9b: Ollama container.  Here is the run command: docker run -d -p 11434:11434 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z -v /mnt/c/maads/tml-airflow/rawdata/ollama:/root/.ollama:z --env OLLAMA_LOAD_TIMEOUT=30m0s --env PORT=11434 --env TSS=1 --env GPU=1 --env COLLECTION=tml-llm-model-v2 --env WEB_CONCURRENCY=2 --env CUDA_VISIBLE_DEVICES=0 --env TOKENIZERS_PARALLELISM=false --env temperature=0.1 --env LLAMAMODEL="phi3:3.8b && phi3:3.8b && llama3.2:3b" --env mainembedding="nomic-embed-text" --env OLLAMASERVERPORT="http://127.0.0.1:11434" maadsdocker/tml-privategpt-with-gpu-nvidia-amd64-llama3-tools, v=125

  [INFO 2026-03-15_18:09:37] STEP 9b: Success starting Agentic AI.  Here is the run command: docker run -d -p 11434:11434 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z -v /mnt/c/maads/tml-airflow/rawdata/ollama:/root/.ollama:z --env OLLAMA_LOAD_TIMEOUT=30m0s --env PORT=11434 --env TSS=1 --env GPU=1 --env COLLECTION=tml-llm-model-v2 --env WEB_CONCURRENCY=2 --env CUDA_VISIBLE_DEVICES=0 --env TOKENIZERS_PARALLELISM=false --env temperature=0.1 --env LLAMAMODEL="phi3:3.8b && phi3:3.8b && llama3.2:3b" --env mainembedding="nomic-embed-text" --env OLLAMASERVERPORT="http://127.0.0.1:11434" maadsdocker/tml-privategpt-with-gpu-nvidia-amd64-llama3-tools

  [INFO 2026-03-15_18:09:44] STEP 8: Starting docker push for: makaeron20@gmail.com/tml-multi-agenticai-iot-3f10-ml_agenticai-c8df-amd64

  [INFO 2026-03-15_18:09:53] STEP 8: Docker Container created and optimized.  Will push it now.  Here is the commit command: docker commit 845a9ca6b6a3 makaeron20@gmail.com/tml-multi-agenticai-iot-3f10-ml_agenticai-c8df-amd64 - message=1

  [INFO 2026-03-15_18:10:21] STEP 10: Started to build the documentation

  [INFO 2026-03-15_18:10:22] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


