# Prozin SASS

Wil je de styling genereren dan volstaat het commando:

```bash
mvn clean install
```

Mis je de patterns git submodule dan kun je deze aanmaken:

```bash
git submodule add https://github.com/Patternslib/patterns-sass.git patterns
git -C patterns checkout e4a182f4af4bc726e9f939fdc6788dffe94638aa
git add .gitmodules patterns
git commit -m "Add patterns-sass as submodule"
```