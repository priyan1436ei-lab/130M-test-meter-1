# Run your project

1. Extract the ZIP completely.
2. Open PowerShell in the `llm-130m` folder.
3. Follow the README installation steps (Python environment, CUDA PyTorch, requirements).
4. Start the included tiny demonstration:

```powershell
.\.venv\Scripts\python.exe start_demo.py
```

Open http://127.0.0.1:8000/docs in your browser. Expand POST /generate, click Try it out, enter a prompt, and Execute. This is the API's interactive documentation, not a chat frontend. The included checkpoint is a tiny model trained briefly on synthetic text; expect poor output.

To build and train the 130M model, follow README sections 2 and 3 using your own suitable corpus. The code and training machinery are implemented. A useful pretrained 130M checkpoint is not included. Your NVIDIA laptop's GPU memory fit still needs local verification.
