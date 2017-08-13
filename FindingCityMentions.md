    1  git remote add origin https://github.com/BETHANYPEHORA/MODULE_4.git
    2  git config remote.origin.url https://github.com/BETHANYPEHORA/MODULE_4.git
    3  git pull -u origin master
    4  grep '\bChapeau\b' June4-1931.txt
    5  grep '\bPontiac\b' June4-1931.txt
    6  grep '\bLitchfield\b' June4-1931.txt
    7  sed -r -i.bak 's/(.+\bLitchfield\b.+)/~\1/g'
    8  sed -r -i.bak 's/(.+\bLitchfield\b.+)/~\1/g' June4-1931.txt
    9  grep '\bGrand-Calumet\b' June4-1931.txt
   10  grep '\bBryson\b' June4-1931.txt
   11  sed -r -i.bak 's/(.+\bBryson\b.+)/~\1/g' June4-1931.txt
   12  grep '~' June4-1931.txt > CityMentions.txt
   13  nano CityMentions.txt
   14  history > FindingCityMentions.md
