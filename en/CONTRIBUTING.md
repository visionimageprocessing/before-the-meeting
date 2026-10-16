# How to Contribute

[日本語](../ja/CONTRIBUTING.md) | [简体中文](../cn/CONTRIBUTING.md) | [Top](../README.md)

You can add a version for your own lab. All you need to send is **one md file**. Other things, such as updating the list in the README, are handled by the maintainer.

You cannot write to this repository directly, so add the file to your own copy (a **fork**) and send it as a **pull request**. You need a GitHub account, but you do not need the command line. You can do everything in the browser.

## Steps

1. Open this repository and click **Fork** to make your own copy.
2. In your fork, open a language folder (`ja/`, `en/`, `cn/`). Click **Add file** → **Create new file** (or **Upload files**) and add `before-<id>.md`.
3. Save (commit). Then, on your fork's page, click **Contribute** → **Open pull request**.
4. In the pull request message, write the following three lines. Write your name in the Latin alphabet so that it can be used in any language.
   ```
   Contributor name: Given-name Family-name
   URL: https://your-personal-page
   Original language: en
   ```
   `URL` is your personal web page (if you do not have one, your lab or university page). `Original language` is the language in which you first wrote the instructions.
5. The maintainer will review and merge it, and will also add the attribution and the entry in the list.

If you use the command line, the flow is the same (fork, clone, create a branch, commit, push, pull request).

## Issues (questions and reports)

For anything other than adding a new file, please write an Issue.

- Mistakes or problems in the instructions (please say which file, e.g., `en/before-mtanaka.md`)
- Translation mistakes
- Requests to add a new language
- Questions about how to use the instructions

Please also write what happened and which AI (Claude or ChatGPT) you used. Do not include unpublished data, personal information, or students' names.

## Rules

- **File name:** `before-<id>.md`. `<id>` is the first initial of your given name followed by your family name, in lowercase (e.g., `before-mtanaka.md`).
- **One file is enough:** One language is fine. If your language does not have a folder yet, put the file in a new folder with a short code (e.g., `ko`, `fr`) and say so in the pull request. The maintainer will do the rest of the setup.
- **Keep the purpose:** The student explains in their own words; the AI asks only one question at a time; the goal is understanding, not evaluation. Everything else can be adapted to your lab.
- **No confidential information:** Do not include unpublished data, personal information, or students' names.
- **Existing files:** Only the author of a file may modify it. If you find a problem in someone else's file, report it in an Issue.
- **If you do not have a GitHub account:** Send the file, your name (in the Latin alphabet), your URL, and the original language to the maintainer (see the top-level `README.md`).
