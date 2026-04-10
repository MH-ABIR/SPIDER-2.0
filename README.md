#Run tools

cd

rm -rf SPIDER-2.0

git clone --depth=1 https://github.com/MH-ABIR/SPIDER-2.0

cd SPIDER-2.0

git pull

python SPIDER.py
