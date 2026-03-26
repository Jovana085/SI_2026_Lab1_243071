1. git checkout -b feature-search-books   # креирање гранка и префрлување
2. git add SI2026Lab1Main.java            # додавање промени
3. git commit -m "Implement book search and other library methods"  # commit
4. git push -u origin feature-search-books  # push на remote
5. git checkout master                     # префрлување на master
6. git merge feature-search-books          # merge на feature гранка во master
7. git push                                # пуш на master
8. git log --oneline --graph --all         # преглед на лог

Излез: \* 0a0acc8 (HEAD -> master, origin/master, origin/feature-search-books, feature-search-books) Add starter code

\* adc1c88 Initial commit

Merge тип: Fast-forward merge, бидејќи master немаше свои промени и едноставно се придвижи до последниот commit од feature-search-books.



