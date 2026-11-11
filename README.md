# Mustafa Yusuf Aksoy

Software developer in Istanbul. I build the ERP of a textile manufacturer (Node.js, MSSQL, Oracle) and the AI pipelines behind [Codewander](https://www.instagram.com/codewander), my content project. When something breaks in real work I measure it, fix it, and open-source the part others can use.

[X](https://x.com/codewandertech) · [Instagram](https://www.instagram.com/codewander) · [LinkedIn](https://www.linkedin.com/in/mustafayusufaksoy) · [Medium](https://medium.com/@mustafayusufaksoy) · [Portfolio](https://mustafayusufaksoyportfolio.vercel.app)

## Open source

| Project | What it is | Stars |
|---|---|---|
| **[colab-nb-runner](https://github.com/mustafayusufaksoy/colab-nb-runner)** | Run a Jupyter notebook cell by cell in a Google Colab session from your terminal. Survives dropped connections, never starts a cell twice, shows output live. `pip install colab-nb-runner` | [![stars](https://img.shields.io/github/stars/mustafayusufaksoy/colab-nb-runner?style=flat-square&label=%E2%98%85&color=8da2fb)](https://github.com/mustafayusufaksoy/colab-nb-runner) |
| **[turkce-asr-ozel-isim](https://github.com/mustafayusufaksoy/turkce-asr-ozel-isim)** | Fixes misheard Turkish people and company names in Whisper and WhisperX transcripts. The model only picks a candidate number, so it cannot invent a name. `pip install turkce-asr-ozel-isim` | [![stars](https://img.shields.io/github/stars/mustafayusufaksoy/turkce-asr-ozel-isim?style=flat-square&label=%E2%98%85&color=8da2fb)](https://github.com/mustafayusufaksoy/turkce-asr-ozel-isim) |
| **[claude-pet-overlay](https://github.com/mustafayusufaksoy/claude-pet-overlay)** | A transparent desktop companion that reacts to Claude Code activity. Tauri 2, no account, nothing leaves your machine. | [![stars](https://img.shields.io/github/stars/mustafayusufaksoy/claude-pet-overlay?style=flat-square&label=%E2%98%85&color=8da2fb)](https://github.com/mustafayusufaksoy/claude-pet-overlay) |

## How these came about

- **colab-nb-runner** started as a script in a podcast clipping pipeline. Long GPU cells kept dying with the connection, and a failed notebook could exit with code 0.
- **turkce-asr-ozel-isim** came from the same pipeline: Whisper wrote "ikaz" for the company ikas and "Ulan Moğlu" for Namoğlu, and asking an LLM to fix names it did not know only made new ones up.
