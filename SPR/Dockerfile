FROM debian

LABEL version="2.0.3"
LABEL author="Eric Gebhart"

RUN DEBIAN_FRONTEND="noninteractive" apt update && apt install -y python3 \
	python3-pip \
	libgl1-mesa-dev \
	libglib2.0-0 \
	libzbar-dev \
	dialog

RUN pip3 install Simple_Process_REPL

RUN SPR -r