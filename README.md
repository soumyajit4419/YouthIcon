# YouthIcon

![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)
[![Slack Status](https://img.shields.io/badge/slack-join_chat-white.svg?logo=slack&style=social)](https://join.slack.com/t/osdfs/shared_invite/zt-eecws9vb-zvmzBeSPgBZrE9RWVj43Sw)
[![85e92ee9](https://user-images.githubusercontent.com/41269164/84294764-440e7200-ab67-11ea-8732-fa5973d2b09a.png )](https://scodein.tech/)

<div align="center">
<img src="asset/youthicon.png" >
</div>

- Let's put **Asia** on NLP map. A living collection of NLP projects for Asians, by Asians. I am modelling this after [Masakhane](https://masakhane.io/).

**YouthIcon** is an research effort for NLP for Asian languages that is OPEN SOURCE, CONTINENT-WIDE, DISTRIBUTED and ONLINE. The **YouthIcon** will contain the data, code, results and research for building open baseline NLP results for Asian languages.

## Goals
- **For Asia**: We are looking for NLP enthusiast to build and facilitate a community of NLP researchers, connect and grow it, spurring and sharing further research, build helpful tools for applications in government, medicine, science and education, to enable language preservation and increase its global visibility and relevance. We want to build model for different Asian Languages. 

- **For NLP Research**: To build data sets and tools to facilitate NLP research on Asian languages, and to pose new research problems to enrich the NLP research landscape.

- **For the global researchers community**: To discover best practices for distributed research, to be applied by other emerging research communities.

## How can I contribute?

There are many ways to contribute to **YouthIcons**.

1. **TRAIN A MODEL** - Contribute a trained model and related code for your language
2. **ANALYSIS** - Contribute analysis of data/models for any languages. You do not need any technical experience for this! If you're a linguist, we can pair you up with a machine translation practitioner and you can help contribute analysis
3. **DATA** - Help build or find datasets for your language
4. **DOCUMENTATION** - Help document our discussions, progress. This is VERY much needed. Or contribute to documentation of the base "notebook" that will improve the experience of others
5. **MENTORSHIP** - We are also looking for mentors to provide advice or help tune models for their languages and datasets, or help people get started
6. **ADMIN** - Working with so many researchers can be quite a challenge! Help out with administrative tasks
7. **COMPUTE** - Help with infrastructure and compute! Do you have spare compute to donate? Let us know! We're always looking for more.
9. **STORY-TELLING** - Tell our stories to the world by doing talks about the community, or engaging with media outlets
10. **MLOps & ML Engineering** - Do you enjoy delving into the MLOps side of machine learning? Are you a software developer looking to hone-in on your ML engineer abilities? Join us to help build tools to support out reproducability, data gathering, and model sharing!

Want more details? Check out our [current initiatives](https://github.com/osDFS/YouthIcon/blob/master/initiatives.md)

## How do I join?

1. Join our [Slack](https://join.slack.com/t/youthiconworkspace/shared_invite/zt-e102vcid-l9LyldQJ303mePF9rxGWDQ)
2. This is so we can feature you on our webpage [osDFS](https://www.osdfs.in). Please email the following to codegirls.opensource@gmail.com:
    - Your Full Name
    - A preferred social media link
    - You GitHub profile
    - The language(s) you'll be working on (or your general relevant specialty - if you're an expert at machine translation and - would like to boost the community through that)
    - A picture
    - Your affiliation and role.

#### Structure of your PR:

Also see this as an example for the structure of your contribution

Structure:
 ```
/benchmarks
  /<src-lang>-<tgt-lang>
    /<technique> -- this could be "jw300-baseline" or "fine-tuned-baseline" or "nig-newspaper-dataset"
      - notebook.ipynb
      - README.md
      - test.src
      - test.tgt
      - results.txt
      - src_vocab.txt
      - trg_vocab.txt
      - src.bpe
      - [trg.bpe if the bpe model is not joint with src]
      - config.yaml
      - any other files, if you have any
```


**Feeling nervous about contributing your first pull request or unsure how to proceed? Please don't feel discouraged! Drop us an email or a slack message and we will work together to get your contribution in ship shape!**

# Code of Conduct

See [Code of Conduct](https://github.com/osDFS/Code-of-Conduct/blob/master/code-of-conduct.md)


