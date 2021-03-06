# Installation

```bash
## Commands used for installing the software
wget https://www.cog-genomics.org/static/bin/plink181012/plink_linux_x86_64.zip
unzip plink_linux_x86_64.zip

## Ignore all downloaded/installed files
echo "plink*" > .gitignore
echo "LICENSE" >> .gitignore
echo "prettify" >> .gitignore
echo "toy*" >> .gitignore

## Version control files
git add .gitignore
git add README.md
```

# Reproducibility

```bash
## Evaluate the following commands
module list
date
echo "User: ${USER}"
echo "Hostname: ${HOSTNAME}"
```

```bash
## copy paste the output from the previous commands
$ module list

Currently Loaded Modules:
  1) JHPCE_DEFAULT_ENV   4) JHPCE_tools/1.0         7) conda_R/3.5
  2) matlab/R2017b       5) COMMUNITY_DEFAULT_ENV   8) gcc/4.4.7
  3) stata/15            6) sge/2011.11p1           9) git/2.17.0



$ date
Fri Nov 16 15:40:25 EST 2018
$ echo "User: ${USER}"
User: lcollado
$ echo "Hostname: ${HOSTNAME}"
Hostname: compute-116
```
