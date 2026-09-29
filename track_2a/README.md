# Academia Challenges

Submissions must use the Apertus model family.
For Track 2 this to means that submitted solutions must be built with Apertus. Other open-weights models can be used to support development, e.g as automatic judges during evaluation. Their role must be clearly described in the submission report.

💬 In case you have questions, join the conversation on Discord or send an email to “hello@hackapertus.ch”

## How it works
Pick from 5 academia challenges provided by Swiss institutions:

- **FHGR:** AI-Powered Job Interview Coach
- **OpenParlData:** Extracting Parliamentary Affairs from PDFs into One Common Structure
- **OST:** Multilingual Natural Language Inference over Swiss Official Voting Booklets
- **UZH:** Detecting Cross-Lingual Semantic Differences in Swiss Government Websites
- **ZHAW:** See It, Say It, Pick It: Vision-Language Grounding for a Real Robot Arm

The challenges incl. submission and judging criteria are described in our **Getting Started guide**:
https://hackapertus.notion.site/getting-started-guide-onlinehack

## Run it

Keep `track_2a/` as it is: don't rename it or move its files, just delete the
other track directories.

From the root of the project:

```bash
make run
```

Fill in the [Makefile](Makefile) so that works on a clean checkout.

Requirements: `runtime, hardware, API keys, model weights`

## Data

Store your data in `data/` and commit it with your project. If it is too big
for git (GitHub rejects files over 100 MB), upload it to
[Hugging Face](https://huggingface.co/) instead and link it from
`technical_report.md`, together with where the data came from.

## 📦 Submission Requirements & Deliverables
❗️ Submissions are not handled on Devpost but via our website only:
http://hackapertus.ch/online-hack/submissions

## ⚖️ Judging Criteria
The judging criteria per challenge are listed in the respective challenge description.

## Support

**Licensing requirements**
Please check our Terms & Conditions (6. What you build is open source):
https://hackapertus.ch/terms-and-conditions

## FAQ
💡 https://hackapertus.ch/faq

## Contact
💬 In case you have questions, join the conversation on Discord or send an email to “hello@hackapertus.ch”
