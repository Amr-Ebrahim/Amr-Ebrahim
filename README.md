<p align="center">
  <img src="./banner.svg" width="100%" alt="Amr Ebrahim — AI / Machine Learning Engineer. Computer vision, LLM systems and AI automation." />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/amr-ebrahim-el-sayed">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="mailto:amr433606@gmail.com">Email</a>
  &nbsp;·&nbsp;
  <a href="https://ieeexplore.ieee.org/document/11417605/">IEEE paper</a>
  &nbsp;·&nbsp;
  Alexandria, Egypt
</p>

<br />

I build AI systems end to end — from messy input data to a model that runs inside a working pipeline.
The problems I like most sit between research and product: taking something that works in a notebook and turning it into a tool people can actually use.

- **Medical imaging research** — co-authored a peer-reviewed paper (JAC-ECC 2025, IEEE Xplore) on how super-resolution changes the diagnostic accuracy of chest X-ray models.
- **LLMs that run locally** — built Otto, a voice assistant that listens, thinks and answers in Arabic and English, fully offline.
- **Automation & data** — build no-code AI workflows with Make and n8n; SQL, dashboards and exploratory analysis from my data analytics work.
- **Teaching** — design and teach AI and robotics courses, from Arduino programming to AI tools for non-technical students.

<sub>B.Sc. Computer Science & Engineering · Egypt-Japan University of Science and Technology (E-JUST), 2021–2026 · Arabic (native) · English (fluent)</sub>

<br />

## Featured work

### MedFlow — from a blurry X-ray to an explained diagnosis

<img src="./medflow-pipeline.svg" width="100%" alt="MedFlow pipeline: low-quality chest X-ray, enhanced with SRGAN, classified with EfficientNetV2-M and Swin Transformer, reasoned over by MedGemma, and turned into readable clinical insight." />

Low-quality scans hide diagnostic detail, and raw model scores are hard for clinicians to interpret.
MedFlow is a modular pipeline that first restores the image, then detects pneumonia, then uses a medical vision-language model to explain the result in plain language.

| Stage | Metric | Result |
| :-- | :-- | :-- |
| Super-resolution (SRGAN) | PSNR / SSIM | **49.37 dB** / **0.996** |
| Pneumonia detection | Accuracy / F1 | **93.11%** / **0.9374** |
| Effect of super-resolution (paper) | AUC | up to **+19%** |

**My part:** built the AI research pipeline — the super-resolution and classification models (CNN, EfficientNetV2-M, Swin Transformer) and their benchmarks — and integrated Google's MedGemma for clinical reasoning. Co-authored the resulting paper.

`Python` `PyTorch` `SRGAN` `EfficientNetV2-M` `Swin Transformer` `MedGemma`

[Paper on IEEE Xplore](https://ieeexplore.ieee.org/document/11417605/) &nbsp;·&nbsp; [Team repository](https://github.com/Assem-ElQersh/MedFlow-V2)

<br />

### Otto — an offline voice assistant that speaks Arabic and English

<img src="./otto-pipeline.svg" width="100%" alt="Otto pipeline: microphone input, wake word detection with openWakeWord, speech-to-text with whisper.cpp, a local LLM served by llama.cpp, and speech output with Piper TTS." />

Most voice assistants send your voice to the cloud. Otto runs the whole loop on your own Windows PC: say *"Hey Otto"*, ask in Arabic or English, and it answers out loud — with no cloud requests and no telemetry.

**How it works:** wake-word detection (openWakeWord) → speech-to-text (whisper.cpp) → a local LLM served by llama.cpp → neural text-to-speech (Piper, with English and Arabic voices).

**My part:** designed and built the full pipeline.

`Python` `openWakeWord` `whisper.cpp` `llama.cpp` `Piper TTS` `Local LLMs`

[Repository](https://github.com/Amr-Ebrahim/Otto-Assistant)

<br />

## Toolkit

<table>
  <tr>
    <td width="190"><b>AI &amp; deep learning</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv" height="36" alt="PyTorch, TensorFlow, scikit-learn, OpenCV" /><br />
      <code>Hugging Face Transformers</code> <code>CNNs</code> <code>Vision Transformers</code> <code>GANs</code> <code>Super-resolution</code> <code>YOLO</code>
    </td>
  </tr>
  <tr>
    <td><b>LLMs &amp; speech</b></td>
    <td>
      <code>MedGemma</code> <code>llama.cpp</code> <code>whisper.cpp</code> <code>Piper TTS</code> <code>openWakeWord</code> <code>Prompt engineering</code>
    </td>
  </tr>
  <tr>
    <td><b>Languages</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=py,r,cpp,c,bash" height="36" alt="Python, R, C++, C, Bash" /><br />
      <code>SQL</code> <code>Embedded C</code>
    </td>
  </tr>
  <tr>
    <td><b>Data &amp; analytics</b></td>
    <td>
      <code>Pandas</code> <code>NumPy</code> <code>Seaborn</code> <code>Tableau</code> <code>Power BI</code> <code>Excel</code> <code>EDA</code> <code>Clustering</code>
    </td>
  </tr>
  <tr>
    <td><b>Automation &amp; backend</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=docker,fastapi,flask" height="36" alt="Docker, FastAPI, Flask" /><br />
      <code>Make</code> <code>n8n</code>
    </td>
  </tr>
  <tr>
    <td><b>Hardware &amp; tools</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=arduino,git,github,linux" height="36" alt="Arduino, Git, GitHub, Linux" /><br />
      <code>Microcontrollers</code> <code>Embedded systems</code> <code>Jupyter</code>
    </td>
  </tr>
</table>

<br />

## Publication

**A Systematic Framework for Evaluating the Diagnostic Impact of Super-Resolution Models in Medical Imaging** — JAC-ECC 2025 · [IEEE Xplore](https://ieeexplore.ieee.org/document/11417605/)

Benchmarks CNN-, GAN- and Transformer-based super-resolution models under domain shift, shows up to a 19% AUC improvement in pneumonia detection, and proposes guidelines for using super-resolution safely in clinical imaging.

<p align="center">
  Open to <b>AI / ML Engineer</b> roles, as well as AI automation and data roles.<br />
  <a href="https://www.linkedin.com/in/amr-ebrahim-el-sayed">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="mailto:amr433606@gmail.com">amr433606@gmail.com</a>
</p>
