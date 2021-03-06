# GIT TUTORIAL

1.
```sudo apt install git-all```

```git --version```

```git config --global user.email "nhien@gmail.com```

```git config --global user.name "nhienduyvu```

๐ฐ๐ผ๐ป๐ณ๐ถ๐ด: cแบฅu hรฌnh 

2.
```git init```

๐ถ๐ป๐ถ๐๐ถ๐ฎ๐น๐ถ๐๐ฒ๐ฑ: khแปi tแบกo

```git status```

๐๐ป๐๐ฟ๐ฎ๐ฐ๐ธ๐ฒ๐ฑ ๐ณ๐ถ๐น๐ฒ๐: tแปp khรดng theo dรตi

๐ฐ๐ผ๐บ๐บ๐ถ๐: thao tรกc ghi lแบกi viแปc thรชm/ thay ฤแปi file hay thฦฐ mแปฅc vร o repository / cam kแบฟt (ggdich)

๐ฟ๐ฒ๐๐ฝ๐ผ๐ป๐๐ถ๐๐ผ๐ฟ๐: kho

```git add <file>``` 

```git add . : thรชm tแบฅt cแบฃ cรกc file``` 

```git commit -m " " ``` 

๐ถ๐ป๐๐ฒ๐ฟ๐๐ถ๐ผ๐ป: sแปฑ chรจn (ggdich) / Nhiรชn hiแปu: sแปฑ thรชm mแปi

๐๐ผ๐ฟ๐ธ๐ถ๐ป๐ด ๐๐ฟ๐ฒ๐ฒ: cรขy thฦฐ mแปฅc hiแปn hร nh

```git log```

```๐๐๐๐๐๐ก XXXXXXXXXXXXXX
๐ด๐ข๐กโ๐๐: ๐โ๐๐๐๐๐ข๐ฆ๐ฃ๐ข <๐โ๐๐๐@๐๐๐๐๐.๐๐๐>
๐ท๐๐ก๐:   Time  +0700
    ๐๐ข๐๐๐ฆ๐๐ข
```

```git show XXXXXXXXXXXXXX```

๐ฎ๐ข๐ถ ๐น๐ข๐ฏ๐ฉ ๐ญ๐ข ๐ฏ๐ฐ๐ช ๐ฅ๐ถ๐ฏ๐จ ๐ฎ๐ฐ๐ช ๐ฅ๐ถ๐ฐ๐ค ๐ต๐ฉ๐ฆ๐ฎ ๐ท๐ข๐ฐ

```git diff``` (diff viแบฟt tแบฏt cแปงa different) xem thay ฤแปi

3.
๐๐ผ๐ฟ๐ธ๐ถ๐ป๐ด ๐ฑ๐ถ๐ฟ๐ฒ๐ฐ๐๐ผ๐ฟ๐: <file_maudo> thฦฐ mแปฅc lร m viแปc 

๐๐๐ฎ๐ด๐ถ๐ป๐ด ๐ฎ๐ฟ๐ฒ๐ฎ: <file_mauxanh> khi commit chแป file trong staging are mแปi ฤฦฐแปฃc commit 

๐ด๐ถ๐ ๐ฟ๐ฒ๐๐ฝ๐ผ๐ป๐๐ถ๐๐ผ๐ฟ๐: lฦฐu nhแปฏng thay ฤแปi cแปงa nhแปฏng commit (xem dรนng git log)

```gitk```

๐๐จ๐(๐ด๐ฟ๐ฎ๐ฝ๐ต๐ถ๐ฐ ๐๐๐ฒ๐ฟ ๐ถ๐ป๐๐ฒ๐ฟ๐ณ๐ฎ๐ฐ๐ฒ): giao diแปn ngฦฐแปi dรนng

4.
```git checkout -- <file_name>``` xรณa bแป file chฦฐa lรชn staging area 

๐ฐ๐ต๐ฒ๐ฐ๐ธ๐ผ๐๐: thแปง tแปฅc thanh toรกn (ggdich)

```git reset HEAD <file_name>```: xรณa nhแปฏng thay ฤแปi hiแปn tแบกi แป working directory

5.
```git checkout -b <branch_name>``` tแบกo mแปt branch vร  chuyแปn qua branch ฤรณ lร m viแปc

```git branch``` xem ฤang cรณ nhรกnh nร o

```git checkout <branch_name>``` chuyแปn qua <barnch_name>

```git merge <branch_name>``` hแปฃp nhแบฅt <branch_name> vร o master (lฦฐu รฝ: nhแป |git checkout master trฦฐแปc lแปnh git merge <branch_name>

```git branch -D <branch_name>``` xรณa <branch_name>

๐ฏ๐ฟ๐ฎ๐ป๐ฐ๐ต: nhรกnh

๐บ๐ฒ๐ฟ๐ด๐ฒ: hแปฃp nhแบฅt

6.
(dรนng git log ฤแป lแบฅy XXXXXXXX)

```git reset --soft XXXXXXXXX```

```git reset --mixed XXXXXXXX```

```git reset --hard XXXXXXXXX```

7.
```git revert XXXXXXXXXXX``` khรกc vแปi reset lร  khi Nhiรชn thแบฅy mแปt commit Nhiรชn ghรฉt nรณ, cรกch ฤรขy vร i commit rแปi vร  muแปn bแป nรณ ฤi thรฌ dรนng git revert / lร  mแปt lแปnh trong git cรณ tรกc dแปฅng hoร n nguyรชn lแบกi mแปt sแป commit nร o ฤรณ ฤรฃ tแปn tแบก

๐ฟ๐ฒ๐๐ฒ๐ฟ๐: hoร n nguyรชn

8.

**gitignore**: liแปt kรช nhแปฏng file mร  Nhiรชn khรดng mong muแปn cho vร o git hoแบทc hiแปu nรดm na lร  Git sแบฝ bแป qua nhแปฏng file ฤรณ ฤi.
tแบกo 1 file .gitignore/liแปt kรช cรกc file khรดng muแปn commit

๐ถ๐ด๐ป๐ผ๐ฟ๐ฒ: lร m lฦก (ggdich)

9.
```git remote add orgin <link>```

```git remote -v``` danh sรกch cรกc remote repo

```git push -u oringin master```

```git push```

๐ผ๐ฟ๐ถ๐ด๐ถ๐ป: gแปc

10. 
```git config --global credential.helper store```

```git config --global credential.helper "cache --timeout=18000"```

```git ssh / gnome-keyring```

11.
```git clone <link>```

```git pull``` merge tแบฅt cแบฃ cรกc thay ฤแปi trรชn remote repository tแปi thฦฐ mแปฅc ฤang chแบกy trรชn local, pull command cแบงn ฤฦฐแปฃc dรนg

๐ฝ๐๐น๐น: kรฉo

12.
push a branch

push request

rebase
....
๐๐๐ ๐โ๐๐ก ๐ ๐๐ข....
