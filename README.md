The Markdown Resume
===================

### Instructions

* Edit `markdown/resume.md` file.

* Build resume and add it to git
```bash
nix build

cp ./result/resume.pdf .

git add markdown/resume.md resume.pdf
git commit -m "Resume update"
```
