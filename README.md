# GitHub-Commit-Monitor_API-call-example-in-Python
## Project's overview
This project was made as a **self-assignment/learning tool**, and consists of an **example** of **REST API call** written in **Python**, accompanied by an introduction to some of the concepts surrounding the topic. 

In particular the code presented in this notebook consists of a call to the **GitHub REST API** (https://docs.github.com/en/rest?apiVersion=2022-11-28), which we here use to scrape some of our **GitHub's account information**, namely:
- API Key expiration date
- Last commit informations for the last five (different) projects receiving a commit

One might imagine to find themselves in need of retrieving this kind of info about their profile if they host different projects receiving commits by one or more other people. This monitoring script save the user some time in getting to their profile and check each and every project receiving commits.

Anyhow, I tried keeping the code simple choosing just these two outputs as others would have had a similar implementation to eithern one or the other of the two I've chosen. A more robust code would probably implement more info retrieval or use them as input to other functions, not just listing them as done here.

Below I wrote an essencial **glossary** of the concepts introduced with this lesson.

In the last part of the note-book there will be a **completely commented** version of the **code**, which can be copied by anyone, better if quoting this github project as a reference (https://github.com/RAGilardi/GitHub-Commit-Monitor_API-call-example-in-Python).

An interesting **excercise**, for someone reading this document who wants to learn about implementing API Calls, would be to use this code as a starting point and add more information to its output, using one of the many other parameters which the GitHub REST API gives access to (to do this I strongly suggest to try and read the documentation linked above, before asking ChatGPT to write for us a mockup which we don't completely undestand).
