# Bruce's Quiz Library

Quizzes for [Bruce's Quiz Party](https://github.com/bruceskingle/bruce-quiz-party), to download on its Quizzes page
with Get Quizzes from a Library.

Each quiz is a folder with its `quiz.md` and its images, in the [quiz format](https://github.com/bruceskingle/bruce-quiz-party/blob/main/docs/QuizFormat.md).
`library.json` lists them, with their files, for the app to download; it is written by the app's Add to Library…, or by
hand.

## Adding a quiz

On the app's Quizzes page, choose the quiz, review it, then press Add to Library…, choose this repository's local
checkout, and tick Commit and push (in the Mac App Store's build, commit and push it yourself).

## Your own library

Any folder of quizzes with a `library.json`, on the web or on disk, is a library: make a repository like this one,
and give the controller the address of its raw files, e.g.
`https://raw.githubusercontent.com/<you>/<repository>/main`.

## Licence

Each quiz is under the licence its `quiz.md` names, crediting the articles and images it draws on. Quizzes drawn from
Wikipedia are under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), whose legal code is in
[LICENSE](LICENSE), and use only freely licensed images from Wikimedia Commons, each under its own licence, which its
quiz's `quiz.md` names with its author.
