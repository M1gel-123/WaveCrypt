# WaveCrypt
WaveCrypt Terminal v8.0
WaveCrypt Terminal is a high-performance desktop application designed for multimedia steganography. It enables the secure embedding of image and video data into high-fidelity audio containers using advanced signal mapping techniques.

🚀 Deployment & Installation
For Standard Users (Windows .EXE)
The application is distributed as a standalone portable executable. You do not need to install Python or any additional libraries.

All-in-One: All dependencies (NumPy, OpenCV, Mutagen) are bundled within the binary.

Portable: Simply place codecfinal.exe, colorswap.exe, click.wav, ffmpeg.exe, shutdown.wav, typing.wav in one folder and run.

Requirements: Windows 10/11 (x64).

🛠 Technical Specs
Core Engine: Python-based signal processing.

Media Handling: Optimized FFMPEG integration for high-speed encoding and decoding.

Audio Mapping: Utilizes 7.1 channel audio layouts to isolate data from the primary audio playback.

Data Integrity: Automated color-space reconstruction via a dedicated post-processing module.

📖 Operational Manual
Data Encoding Sequence

Select Target: Choose the image or video file you wish to encrypt.

Select Carrier: Select a high-quality FLAC or WAV file to serve as the host.

Execute: Click ENCODE_SEQUENCE. The system will generate a protected *_CRYPT.flac file.

Data Extraction Sequence
Load Protected File: Select the encrypted .flac file.

Execute: Click DECODE_SEQUENCE.

Finalization: The system extracts the raw signal and automatically triggers the colorswap utility to finalize visual reconstruction.

⚠️ IMPORTANT: PRE-ENCODING NOTICE
[!IMPORTANT] To ensure optimal performance and prevent excessive file sizes, all media MUST be pre-encoded before the encryption sequence.

Video Format: It is highly recommended to encode your videos using the H.264 (MPEG-4 AVC) codec.

Efficiency: Using H.264 can reduce the required storage space within the audio carrier by up to 10x – 50x compared to raw formats.

Stability: Smaller data streams significantly improve signal stability and reduce the risk of corruption during the recovery process.

Image Optimization: For photos, ensure they are optimized (PNG or JPG) to keep the bit-depth manageable for audio injection.

⚖️ License and Copyright
PROPRIETARY SOFTWARE - ALL RIGHTS RESERVED

Copyright (c) 2026 WaveCrypt Systems.

This software is the exclusive property of WaveCrypt Systems. Any unauthorized use, reproduction, or distribution is strictly prohibited.

Reverse Engineering: Disassembly or decompilation of binary files is strictly forbidden.

Commercial Use: Unauthorized commercial exploitation is subject to legal action.

Full Terms: Detailed licensing terms can be found in the LICENSE file.

📧 Contact
For technical support, security reports, or licensing inquiries, please contact the lead developer through this GitHub repository.
