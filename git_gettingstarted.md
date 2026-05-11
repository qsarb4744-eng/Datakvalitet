1. Skapa ett nytt repository på GitHub. 
    Dokumentation om du behöver det: https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository
    Gör repot Privat och lägg till en ReadMe fil.

2. Öppna en terminal och gå till den folder du vill lägga ditt nya repo i
`cd <path/to/repos>`

4. På GitHub kopierar du url:en till dit nya repo: "Code" och sen HTTPS

3. Dubbelkolla att du har git installerat:
`git --version`

5. I terminalen kör du sedan:
`git clone <copied-url>`

6. Öppna ditt repo i Vs Code. Antingen från VS Code eller genom att öppna från terminalen:
`cd <name-of-repo>`
`code .`

7. Lägg den här filen och secrets.txt filen i repot

8. Secrets-filen verkar innehålla känslig information som vi inte vill skicka upp till GitHub:
    Skapa en fil som heter `.gitignore`. I den filen skriver du `secrets.txt` på första raden.

9. I filen README.md ändra något i texten som finns. Lägg också till en ny rad med en kort text.

9. På vänstra sidan i VS Code ser du en symbol för "Source Control". Öppna den och undersök vilka filer som finns här. Vad betyder U/M? Finns secrets.txt med i listan?

10. Tryck på README och undersök hur det ser ut när saker ändrats i en fil.

11. Lägg till .gitignore, gettingstarted och README genom att trycka på pluset vid sidan av filerna (terminal: samma sak som git add <filename>)

12. Skriv en kort text över vilka ändringar du gjort i "Message" och tryck sedan på "Commit": (terminal: samma som git commit -m "beskrivande text")

13. Tryck på "Push", finns. som val om du trycker på de tre punkterna bredvid "CHANGES" (terminal: git push)

14. Öppna GitHub igen och notera att de nya filerna nu finns där.

15. Notera att det står "main" längst ned i VS Code, alltså namnet på huvudbranchen. I VS Code, tryck på Branch > Create Branch, och ge den ett namn. Observera att det nya namnet nu står längst ned i VS Code (terminal: git checkout -b new-branch).

16. Gör en ändring, commita och pusha från den nya branchen.

17. Testa att göra en PR på GitHub för att se hur det ser ut.

Om du vill använda git från VS Code UI hittar du dokumentation här: https://code.visualstudio.com/docs/sourcecontrol/overview
Om du vill använda git kommandon från terminalen hittar du ett cheat-sheet här: https://git-scm.com/cheat-sheet



