# Text_processors
1. tail -n 40 1.txt | cat > 2.txt
2. head -n 10 2.txt | cat > 3.txt
3. sed -r 's/koko/kuku/g' 2.txt | grep 'kuku' | head -n 3 | cat >> 3.txt
4. sort 3.txt | uniq -c
