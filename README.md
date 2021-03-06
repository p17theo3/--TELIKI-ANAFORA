# Μάθημα: Πολυμέσα - Τελική Αναφορά
# Όνομα: Xαράλαμπος
# Επίθετο: Θεοδούλου
# Α.Μ.: Π2017151
# Προφίλ Github: [Προφίλ](https://github.com/p17theo3)
# Κλαδί του κώδικα: [link](https://github.com/p17theo3/mm/tree/P2017151)
# Αποθετήριο του κώδικα: [link](https://github.com/p17theo3/mm/tree/master)

### Σύνοψη:
 Για το μάθημα πολυμέσα είχα 5 παραδοτέα και τα έστειλα στις ημερεμένες μας έδωσε ο καθηγητής. Για το πρώτο παραδοτέο έπρεπε να κατεβάστε και παίξω μέσο του τέρμινα το αγαπημένο μου τραγούδι του μήνα. Στο δεύτερο παραδοτέο έπρεπε να Κατεβάστε torrent μέσω του terminal. Στο τρίτο παραδοτέο να κάνω youtube video streaming και στο τέταρτο παραδοτέο να κάνουμε επίδειξη διαχεισηρης ενός μουσικού άλμπουμ με τραγούδια mp3. Για το 5ο παραδοτέο έπρεπε να διαχειριστούμε την μουσική βιβλιοθήκη μας , να βάζουμε και να μπορούμε να διαγράψουμε τραγούδια.

### Σύντομη Εισαγωγή:
Στο πρώτο παραδοτέο με την χρήση του youtube-dl κατέβασα το τραγούδι σε mp3 μορφή και με την MPV εντολή έγινε η εκτέλεση του. Για το δεύτερο παραδοτέο χρησιμοποίησα την εφαρμογή rtorrent με την οποία κατεβάζεις τερέν από το τέρμινα. Στο Τρίτο παραδοτέο έγινε η χρήση του youtube-viewer οπού μπορείς μπορείς να αναζητήσεις και να δεις βίντεο από το τέρμινα. Για το τέταρτο παραδοτέο εγκατάστησα το cmus οπού είναι κατάλληλο για την διαχείριση μουσικών άλμπουμ. Τέλος στο πέμπτο παραδοτέο έγινε η χρήση του beet με το οποίο μπορείς να διαχειριστείς  μια μουσική βιβλιοθήκη εντός linux. 


### Σύντομη Ανάλυση σχετικών Έργων και Εργαλείων:

Για την ολοκλήρωση των πιο πάνω παραδοτέων έγινε η χρήση του linux. Έγινε λήψη του ubuntu το οποίο μπορούσα να το εκκίνηση μέσω του VirtualBox. Έχω αλλάξει το HostName το οποίο εμφανίζεται στο τέρμινα όπως ζητούσε η εργασία με την εντολή sudo gedit ~/.bashrc. Για την καταγραφή των βίντεο έγινε η χρήση του asciinema στο οποίο έπρεπε να δημιουργήσω λογαριασμό για να μην γίνονται archived τα βίντεο  Επίσης έχω κανί εγκατάσταση του FFmpeg άλλα και του python.

### Μέθοδος και Τεχνικές Ανάπτυξης:
Για το πρώτο παραδοτέο έγινε η εγκατάσταση FFMPEG και του MPV με τις  εντολές  sudo apt install ffmpeg  και sudo add-apt-repository ppa:mc3man/mpv-tests , sudo apt-get install mpv. για την λήψη του τραγουδιού έγινε η χρήση του youtube dl. Xρησιμοποιήθηκε η παρακάτω εντολή για την εκτέλεση του τραγουδιού μέσα στο τέρμινα mpv onemoreligh.mp3. 

Στο Δεύτερο παραδοτέο για την λήψη τορρεντ μέσω του τέρμινα εχει χρησιμοποιηθεί το rTorrent,  sudo apt-get install rtorrent. είναι ένας σχετικά εύκολος τρόπος όπου μπορείς να χρησιμοποιήσεις λινκ τορρεντ η directory path. τα τορρεντ που κατεβαίνουν μέσω του rTorrent αποθηκεύονται στο /home/username. Κάποια keys για το τορρεντ είναι ctrl+S = εκινηση τορεντ ctrl+D = τερματισμός τορεντ ctrl+DD = διαγραφή τορεντ.

Στο τρίτο παραδοτέο έκανα χρήση του youtube-viewer sudo apt install youtube-viewer . Όταν ανοίξεις το youtube-viewer ψάχνεις το βίντεο που θες και πατάς enter. στη συνεχεία σου βγάζει μια λίστα με βίντεο που έχουν βρεθεί επιλέγεις τον αριθμό του βίντεο που θες να δεις και πατάς enter. χρησιμοποιήθηκε το παρακάτω gif (https://gfycat.com/leafyyearlyatlanticsharpnosepuffer)

Στο τέταρτο παραδοτέο επερε να κάνω επίδειξη διαχεισηρης ενός μουσικού άλμπουμ με τραγούδια mp3. εγινε  χρήση του cmus sudo apt-get install cmus. Το cmus είναι ένα Music Player για τα Linux οπού μπορεί αναπαράγει μουσικά αρχεία αμέσως, ακόμη και αν υπάρχουν χιλιάδες αρχεία ήχου. Επίσης υποστηρίζει σχεδόν όλες τις μορφές. MP3, FLAC, Opus, Musepack, WavPack, WAV, AAC, MP4. Εκινουμε το cmus με την εντολή cmus start up και εισάγουμε μουσική απο το σύστημα  add ~Music/music2. Μπορούμε να χρησιμοποιήσoυμε τα πάνω και κάτω βελάκι για να επιλέξουμε ένα κομμάτι που θέλουμε να ακούσουμε. πατάμε το Enter για να το παίξει. επίσης πατάμε το C για pause η resume.

Στο Πέμπτο παραδοτέο έπρεπε να διαχειριστούμε την μουσική βιβλιοθήκη μας , να βάζουμε άλλα και να να διαγραφούμε τραγούδια. χρησιμοποιήθηκε το beet sudo apt-get install -y beets οπού είναι μια μουσική βιβλιοθήκη για το linux. κάποιες εντολές είναι beet ls -a για προβολή όλων των άλμπουμ , beet rm  of name> για διαγραφή τραγουδιού από την λίστα και beet rm -a  of name> για διαγραφή κάποιου άλμπουμ από την λίστα 

### Αποτελέσματα:
Με την χρήση του asciinema έγιναν οι παρακάτω καταγραφές οι οποίες είναι τα αποτελέσματα του κάθε παραδοτέου:
### 1η άσκηση.
## Asciinema URL: [1η ασκηση](http://asciinema.org/a/qxybfXGWa4Pyo4zbJNCgJM01m)
### 2η άσκηση.
## Asciinema URL: [2η άσκηση](https://asciinema.org/a/277311)
### 3η άσκηση.
## Asciinema URL: [3η άσκηση](https://asciinema.org/a/277778)
### 4η άσκηση.
## Asciinema URL: [4η άσκηση](https://asciinema.org/a/278649)
### 5η άσκηση.
## Asciinema URL: [5η άσκηση](https://asciinema.org/a/277347)

### Συμπεράσματα:
Συμπεράσματα είναι πως το linux είναι ένα δωρεάν λειτουργικό σύστημα το οποίο παρέχει πολλές δυνατότητες στους προγραμματιστές. Μέσω του linux μπορείς να δεις βίντεο , να ακούσεις μουσική να κατεβάσεις τορεντ με ευκολία. Επίσης το asciinema είναι μια πάρα πολύ ευκολόχρηστη  εφαρμογή καταγραφής της οθόνης.

### Βιβλιογραφία:
Google, Youtube, Github

# Α.Συμμετοχικό εκπαιδευτικό υλικο:
##  [Twitter](https://twitter.com/p17theo3)

### [Xerox](https://twitter.com/p17theo3/status/1193280196171964416)
### [Uber](https://twitter.com/p17theo3/status/1193280727535771653)
### [Windows10](https://twitter.com/p17theo3/status/1193282212520747008)
### [Minecraft](https://twitter.com/p17theo3/status/1193285053197029377)
### [Scratch](https://twitter.com/p17theo3/status/1193285905903214594)
### [Visual Basic](https://twitter.com/p17theo3/status/1193286574387150849)
### [Mobile](https://twitter.com/p17theo3/status/1193287740625997824)
### [Mobile](https://twitter.com/p17theo3/status/1193289442963968000)
### [Micro-Controller](https://twitter.com/p17theo3/status/1193290234542333953)
### [Vr Solder Training](https://twitter.com/p17theo3/status/1193292729511489536)


# Β.Συμμετοχικό εκπαιδευτικό υλικο:
## Λίνκ αποθετηρίου: [link](https://github.com/p17theo3/gr)

