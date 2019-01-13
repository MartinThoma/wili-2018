# WiLI-2018 Errata

If you want to get to the data, go to [zenodo.org](https://zenodo.org/record/841984).
If you want to get to the publication, go to [archive.org](https://arxiv.org/pdf/1801.07779.pdf).
If you want to give feedback or a comment, go to [martin-thoma.com](http://martin-thoma.com/wili).

If you want to add to the errata, you have a couple of options:

* Send me an e-mail (info@martin-thoma.de) - if I don't respond within 3 days,
  just ping me again. I get a lot of messages and if I read it during work I might
  not answer right away. I'm sorry if that happens.
* Add an issue here on GitHub
* Make a Pull Request on Github - that is best, because it makes sure that you
  get credit for your work as well!

## errata.csv

The following format is used:

```
file;line;wrong label;correct label;comment;contributor
```

where:

* `file`: either `y_test.txt` or `y_train.txt`
* `line`: Zero-based - your editor might show something different!
* `wrong label`: what is in `y_test.txt` / `y_train.txt`
* `correct label`: what should be in `y_test.txt` / `y_train.txt`
* `comment`: How you found it
* `contributor`: Your name / e-mail address / pseudonym - whatever you want, as long as it is not insulting or otherwise improper such as advertisement
