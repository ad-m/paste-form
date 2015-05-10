# paste-form

Idea jest prosta. Chcemy zbudować aplikacje do prostego budowania formularzy generujących różne rodzaju pisma w kilku prostych krokach. Ma to być pastebin dla wzorów dokumentów.

Posiadamy użytkownika wytwarzającego formularze (redaktor) i użytkownika, który wykorzystuje pisma (ZU).

Redaktor umieszcza treść dokumentu, który chce stworzyć (publicznie lub prywatnie). Z wykorzystaniem HTML go scyluje. Następnie wykorzystuje kreator formularzy, aby jakie pola ulegają zmianie. W ostatnim kroku z wykorzystaniem silnika _.js.template opisuje sposób przyporządkowania pól formularza do elementów formularza. 

ZU trafia na formularz, wypełnia pola, klika generuj i otrzymuje dokument przetworzony z wykorzystaniem systemu skórek. Wygląd dokumentu poznaje dopiero po wypełnieniu formularza. Wcześniej o tym nie myśli. 
