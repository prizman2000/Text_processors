# Text_processors
1. tail -n 40 1.txt > 2.txt
2. head -n 10 2.txt > 3.txt
3. sed -r 's/koko/kuku/g' 2.txt | grep 'kuku' | head -n 3 >> 3.txt
4. sort 3.txt | uniq -c
