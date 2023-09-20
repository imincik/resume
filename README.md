The Markdown Resume
===================

### Instructions

* Edit `markdown/resume.md` file.

* Build resume and add it to git
```bash
nix build

cp ./result/resume.pdf .
cp ./result/resume.html .

git add markdown/resume.md resume.pdf resume.html
git commit -m "Resume update"
```
