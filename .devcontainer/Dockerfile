FROM mcr.microsoft.com/devcontainers/python:1-3.12-bullseye

RUN pip install torch torchvision torchaudio --index https://download.pytorch.org/whl/cu118

RUN pip install packaging \
    ipykernel \
    accelerate
