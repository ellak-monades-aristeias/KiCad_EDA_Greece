# Περιγραφή έργου KiCad_EDA_Greece
Αυτό το repository [https://github.com/ellak-monades-aristeias/KiCad_EDA_Greece](https://github.com/ellak-monades-aristeias/KiCad_EDA_Greece) δεν είναι ένα τυπικό λογισμικό, αλλά ένα έργο που έχει ως σκοπό την προώθηση του λογισμικού [Kicad](http://kicad-pcb.org/) στους Έλληνες χρήστες. Αυτό γίνεται υλοποιώντας τρεις ενέργειες.

* Πλήρης εξελληνισμός του περιβάλλοντος του KiCad
* Ανάπτυξη μίας απλής ηλεκτρονικής συσκευής ανοιχτού υλικού με το KiCad ([περισσότερες πληροφορίες](work/pcb/usb2uart/README.md))
* Συγγραφή ενός οδηγού εκμάθησης (tutorial) χρήσης του KiCad στα Ελληνικά

Τα αρχεία και για τις τρεις ενέργειες αποτελούν τα αρχεία αυτού του repository.

# Συνεισφορά στο έργο - Εξελληνισμένο περιβάλλον KiCad
Για να συνεισφέρετε στη μετάφραση για το Ελληνικό περιβάλλον του KiCad, μπορείτε να μεταφράσετε το σχετικό αρχείο kicad.po και να το ανεβάσετε σε αυτό το repository ή να να το ανεβάσετε απευθείας στο  [επίσημο github repository μεταφράσεων του KiCad](https://github.com/KiCad/kicad-i18n). 
Πιο αναλυτικά, η πορεία που προτείνεται είναι η παρακάτω
* Κατεβάστε σε έναν φάκελο του υπολογιστή σας την πιο πρόσφατη έκδοση των πηγαίων αρχείων κώδικα του KiCad. Αυτό μπορεί να γίνει από το [bazaar KiCad repository στο launchpad](https://launchpad.net/kicad) ή από το [git KiCad mirror repository στο Github](https://github.com/KiCad/). Για περισσότερες πληροφορίες ως προς το πως θα κατεβάσετε την πρόσφατη έκδοση των πηγαίων αρχείων κώδικα του KiCad επισκεφθείτε τη σελίδα του KiCad για τους developers [Developers | KiCad EDA](http://kicad-pcb.org/contribute/developers/#_fetching_the_source_code).
* Κατεβάστε το [ελληνικό αρχείο kicad.po](https://github.com/ellak-monades-aristeias/KiCad_EDA_Greece/blob/master/work/translation/kicad.po) από αυτό το repository.
* Ανοίξτε το ελληνικό αρχείο kicad.po με κάποιο πρόγραμμα επεξεργασίας gettext, όπως το [poedit](https://poedit.net/). 
* Χρησιμοποιώντας το πρόγραμμα αυτό, ανανεώστε το ελληνικό αρχείο kicad.po με βάση  πιο πρόσφατη έκδοση των πηγαίων αρχείων κώδικα του KiCad.
* Αν η ανανέωση παράξει αμετάφραστα κείμενα στο ελληνικό αρχείο kicad.po, μεταφράστε τα κειμενα αυτά στα Ελληνικά, κατά προτίμηση ακολουθώντας την ορολογία που έχει ήδη χρησιμοποιηθεί στον [εξελληνισμό του περιβάλλοντος του KiCad]  (https://github.com/ellak-monades-aristeias/KiCad_EDA_Greece/wiki/%CE%A5%CF%80%CE%BF%CE%AD%CF%81%CE%B3%CE%BF-1:-%CE%A0%CE%BB%CE%AE%CF%81%CE%B7%CF%82-%CE%B5%CE%BE%CE%B5%CE%BB%CE%BB%CE%B7%CE%BD%CE%B9%CF%83%CE%BC%CF%8C%CF%82-%CF%84%CE%BF%CF%85-%CF%80%CE%B5%CF%81%CE%B9%CE%B2%CE%AC%CE%BB%CE%BB%CE%BF%CE%BD%CF%84%CE%BF%CF%82-%CF%84%CE%BF%CF%85-KiCad).
* Ανεβάστε τo ανανεωμένο ελληνικό αρχείο kicad.po σε αυτό το repository ή στο [επίσημο github repository μεταφράσεων του KiCad](https://github.com/KiCad/kicad-i18n).

# Συνεισφορά στο έργο - Ηλεκτρονική συσκευή ανοιχτού υλικού
Για να συνεισφέρετε στην εξέλιξη του σχεδιασμού της συσκευής ανοιχτού υλικού πρέπει να κατεβάσετε τα αρχεία της συσκευής από αυτό το repository, να τα επεξεργαστείτε, και να δημιουργήσετε ένα pull request για το έργο.

# Συνεισφορά στο έργο - Ηλεκτρονική συσκευή ανοιχτού υλικού - Οδηγός εκμάθησης (tutorial) χρήσης του KiCad
Για να συνεισφέρετε στην εξέλιξη του οδηγού εκμάθησης πρέπει να κατεβάσετε το αρχείο .tex του tutorial, να τα επεξεργαστείτε, και να δημιουργήσετε ένα pull request για το έργο. 

Bελτιώσεις, δυσλειτουργίες, feature requests κλπ και για τα τρία μέρη του έργου, προτείνεται να καταχωρούνται ως [issues στο repository](https://github.com/ellak-monades-aristeias/KiCad_EDA_Greece/issues).

# Άδεια χρήσης και πνευματικά δικαιώματα

Το περιεχόμενο αυτού του έργου κυκλοφορεί κάτω από άδειες EUPL v1.1 και CC-BY-SA 4.0.

**Για να δείτε το περιεχόμενο αυτών των αδειών επισκεφθείτε τα  http://creativecommons.org/licenses/by-sa/4.0/deed.el και http://ec.europa.eu/idabc/eupl.html**
