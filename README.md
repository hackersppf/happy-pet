# happy-pet
Ένα σύστημα για την αυτόνομη και προσωποποιημένη παροχή τροφής και νερού στα κατοικίδια μας!
# Πως επιλέξαμε το θέμα
- Αρχικά μέσα από μια δίωρη ιδεοθύελλα (brainstorming) δημιουργήσαμε τον [εννοιολογικό χάρτη](http://ppf.edu.gr/hackers/archives/153 "εννοιολογικό χάρτη") με τα γενικά θέματα τα οποία μας απασχολούν.
- Στην [επόμενη συνάντηση μας](http://ppf.edu.gr/hackers/archives/247 "επόμενη συνάντηση μας"), αφού μελετήσαμε τον εννοιολογικό χάρτη και τις πληροφορίες που είχαμε συλλέξει για τα θέματα που είχαν αποτυπωθεί σε αυτόν, ξεκινήσαμε να γράφουμε [ιδέες και προτάσεις](http://ppf.edu.gr/hackers/archives/category/%CE%B9%CE%B4%CE%AD%CE%B5%CF%82-%CE%B3%CE%B9%CE%B1-%CE%BA%CE%B1%CF%84%CE%B1%CF%83%CE%BA%CE%B5%CF%85%CE%AD%CF%82 "ιδέες και προτάσεις").
- Η συγγραφή και ο σχολιασμός ιδεών και προτάσεων διήρκησε τρεις εβδομάδες. Μια από τις πιο δημοφιλείς ιδέες ήταν το[ αυτόματο σημείο σίτισης για αδέσποτα ζώα](http://ppf.edu.gr/hackers/archives/326 " αυτόματο σημείο σίτισης για αδέσποτα ζώα").
- Ύστερα από συζητήσεις που έγιναν είτε στην τάξη, είτε διαδικτυακά μέσα από τα σχόλια στον δικτυακό τόπο του Ομίλου μας, καταλήξαμε στην ιδέα να κατασκευάσουμε ένα έξυπνο μηχάνημα σίτισης για κατοικίδια, το οποίο να αναγνωρίζει το ζωάκι που έρχεται κοντά και να συμπεριφέρεται ανάλογα. Η ίδια συσκευή μπορεί να αξιοποιηθεί με διαφοροποιήσεις και για την σίτιση των αδέσποτων ζώων.
# Αναλυτική περιγραφή
## Τι θέλουμε να πετύχουμε
Αρκετά από τα παιδιά του ομίλου μας έχουν στα σπίτια τους κατοικίδια, τα οποία αγαπούν και φροντίζουν. Μια βασική τους έγνοια είναι να προσφέρουν στα ζωάκια τους τροφή και νερό, ακόμα και όταν λείπουν όλα τα μέλη της οικογένειας από το σπίτι. Επίσης θεωρούν σημαντικό να υπάρχει παρόμοια πρόνοια για τα αδέσποτα ζωάκια της πόλης, τα οποία δεν έχουν οικογένεια να τα φροντίσει. Για αυτούς τους λόγους θέλουμε να κατασκευάσουμε ένα έξυπνο σύστημα που θα αναγνωρίζει ποιο ζωάκι έρχεται κοντά του και θα παρέχει κατάλληλη τροφή και νερό.
## Οι βασικές λειτουργίες που θέλουμε να έχει το σύστημα μας είναι οι εξής:
- Να μπορεί να αναγνωρίζει ποιο από τα ζωάκια μας έρχεται κοντά στην συσκευή τροφοδοσίας και να του δίνει την κατάλληλη τροφή. Αν για παράδειγμα έχουμε μια γάτα και έναν σκύλο, θα πρέπει να έχουμε δυο δοχεία αποθήκευσης τροφής και ανάλογα με το ζωάκι που πλησιάζει να ρίχνει την κατάλληλη τροφή στο πιάτο.
- Να κρατάει στη μνήμη του πότε έδωσε τροφή τελευταία φορά για όλα τα ζωάκια, ώστε η επόμενη τροφοδοσία τους να γίνει μετά από ορισμένο χρονικό διάστημα.
- Κάθε φορά που πλησιάζει κάποιο ζωάκι, να ελέγχει αν υπάρχει νερό στο πιατάκι και να συμπληρώνει όσο χρειάζεται από το δοχείο αποθήκευσης νερού.
- Να μας ειδοποιεί στο κινητό μας τηλέφωνο κάθε φορά που καταγράφεται κάποια ενέργεια, δημιουργώντας έτσι ένα ημερολόγιο με την τροφοδοσία των κατοικίδιων μας. 
- Να μας ειδοποιεί αν κάποιο ζωάκι δεν έχει πάει να φάει για αρκετό χρονικό διάστημα ώστε να φροντίσουμε κατάλληλα.
## Πως σκοπεύουμε να υλοποιήσουμε το σύστημα μας
- Για να αναγνωρίζει η συσκευή μας ότι κάποιο ζωάκι πλησιάζει, θα χρησιμοποιήσουμε οικονομικούς αισθητήρες κίνησης υπέρυθρων (PIR sensors). Με αυτόν τον τρόπο μπορούμε να «ξυπνάμε» το σύστημα μας ώστε να προχωρήσει στο επόμενο βήμα αναγνώρισης.
- Για να αναγνωρίζει ποιο ζωάκι πλησιάζει στο πιατάκι, θα χρησιμοποιήσουμε άλλη μια οικονομική λύση που θα βασίζεται στις ετικέτες RFID. Κάθε ζωάκι θα έχει στο κολάρο του ένα αυτοκόλλητο ή μια ετικέτα RFID που θα το χαρακτηρίζει μοναδικά σε σχέση με τα υπόλοιπα. Στην συσκευή μας θα υπάρχει ένας RFID reader ο οποίος θα διαβάζει την ετικέτα από το ζωάκι που έρχεται κοντά και έτσι θα το αναγνωρίζει. Θέλουμε να πειραματιστούμε με RFID readers κοντινής και μέσης απόστασης, οι οποίοι θα ενσωματωθούν στο πιατάκι τροφής.
- Για να μεταφέρουμε την τροφή από τα αποθηκευτικά δοχεία στο πιατάκι, θα χρησιμοποιήσουμε ένα σύστημα μεταφοράς με οικονομικούς βηματικούς κινητήρες και με κοχλίες, τους οποίους θα κατασκευάσουμε με τον τρισδιάστατο εκτυπωτή που διαθέτουμε στον Όμιλο. 
- Για να γεμίζουμε το πιατάκι του νερού από το αποθηκευτικό δοχείο, θα χρησιμοποιήσουμε αισθητήρες στάθμης νερού και θα πειραματιστούμε με ηλεκτροβάνες (Plastic Water Solenoid Valves) καθώς και αντλίες που θα κατασκευάσουμε από παλιούς dc κινητήρες που έχουμε στο σχολείο και τους έχουμε ανακτήσει από εκτυπωτές και άλλες συσκευές. Τα πλαστικά μέρη από τις αντλίες, θα τις εκτυπώσουμε στον τρισδιάστατο εκτυπωτή του Ομίλου.
- Η επικοινωνία του συστήματος μας με το κινητό μας τηλέφωνο θα γίνεται μέσω διαδικτύου και μιας απλής εφαρμογής, που θα αναπτύξουμε χρησιμοποιώντας το AppInventor. Το σύστημα θα συνδέεται ασύρματα στο τοπικό δίκτυο του σπιτιού (wifi) και θα στέλνει τα δεδομένα στο κινητό μας τηλέφωνο, χρησιμοποιώντας είτε την εφαρμογή Blynk είτε την υπηρεσία TinyWebDB που υπάρχει στο AppInventor. 
## Λίστα βασικού εξοπλισμού
- 1 x ESP32S (Έχει αρκετά GPIO pins για όλα τα περιφερειακά μας και ενσωματωμένο wifi)
- 2 x PIR sensors 
- 3 x mid range RFID reader
- 3 x small range RFID reader 
- 10 x RFID stickers
- 10 x RFID keychains
- 2 x 28-BYJ48 Stepper motors with ULN2003 driver
- 1 x Normally Closed Type Solenoid Valve
- 1 x 12V 1-Channel Relay Module Board with Optocoupler (Για τον έλεγχο της ηλεκτροβάνας)
- 1 x Real Time Clock Module
- 1 x PLA filament
## Πρόχειρο σχέδιο κατασκευής
![](https://github.com/hackersppf/happy-pet/blob/master/happy%20pet%20%CF%80%CF%81%CE%BF%CF%83%CF%87%CE%AD%CE%B4%CE%B9%CE%BF.png)
