# create a new repository on the command line
echo "# Test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M 'main'
git remote add origin git@github.com:JerryCatLeung/Test.git
git push -u origin 'main'

Avazu Click-Through rate prediction

The introduction of our approach could be found in doc.pdf.

System Requirement
------------------
- 64-bit Unix-like os
- Python 2.7
- g++
- pypy
- sklearn
- at least 20GB memory and 50GB disk space

To reproduce our submission:
-------------------
- Download tha data("train" and "test") to this folder.
- Change directory to script:
	cd script
- Run the code:
	./run.sh
