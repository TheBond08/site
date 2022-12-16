Η Python είναι μια δυναμική γλώσσα προγραμματισμού, πολύ υψηλού
επιπέδου. Κύριος στόχος της είναι η αυξημένη παραγωγικότητα του
προγραμματιστή και η αναγνωσιμότητα του κώδικα. Έχει ενσωματωμένες δομές
δεδομένων όπως λίστες και πίνακες κατακερματισμού (που αποκαλεί dictionaries)
και μια αρκετά μεγάλη βιβλιοθήκη, ακολουθώντας τη φιλοσοφία batteries included.
Δανείζεται στοιχεία από τον προστακτικό, αντικειμενοστρεφή αλλά και συναρτησιακό
προγραμματισμό, χωρίς να επιβάλλει κάποιο συγκεκριμένο τρόπο
προγραμματισμού (σε αντίθεση π.χ. με τη Java).
Τα χαρακτηριστικά της την καθιστούν καλή επιλογή για prototyping, αλλά και για
πληθώρα εφαρμογών στις οποίες η απόδοση δεν είναι τόσο σημαντικός παράγοντας.
Η Python είναι εύκολη στην εκμάθηση και ταυτόχρονα ισχυρή γλώσσα
προγραμματισμού. Έχει αποδοτικές δομές δεδομένων υψηλού επιπέδου και μια
απλή αλλά αποτελεσματική προσέγγιση στον αντικειμενοστρεφή προγραμματισμό.[^1]

Η Python είναι μια διερμηνευόμενη (interpreted), αλληλεπιδραστική (interactive) και
προσανατολισμένη σε αντικείμενα (object-oriented) γλώσσα προγραμματισμού, που
αναπτύχθηκε από τον Ολλανδό Guido van Rossum, το 1990. Το όνομά της
προέρχεται από ένα από τα αγαπημένα τηλεοπτικά θεάματα του van Rossum, το
ιπτάμενο τσίρκο των Monty Python's. Η Python είναι μια γλώσσα που συνδυάζει σημαντική ισχύ με πολύ σαφή σύνταξη.
Χρησιμοποιεί ενότητες (modules), τάξεις (classes), εξαιρέσεις (exceptions) καθώς
και πολύ υψηλού επιπέδου δυναμικούς τύπους δεδομένων.

Οι διερμηνευτές (interpreters) της Python είναι διαθέσιμοι για τα περισσότερα λειτουργικά
συστήματα και ο πηγαίος κώδικας (source code) της Python διατίθεται δωρεάν. Η επίσημη 
ιστοσελίδα της γλώσσας είναι η http://www.python.org. Η ανάπτυξη της Python ξεκίνησε το 1990
στο CWI του Άμστερνταμ και συνεχίζεται στο CNRI του Reston. Η γλώσσα διαθέτει μια κομψή αν και
όχι πολύ απλοποιημένη σύνταξη και έναν μικρό αριθμό από ισχυρούς και υψηλού επιπέδου τύπους δεδομένων.

{% include figure image_path="/images/python-logo.jpg" caption="Figure 1: To λογότυπο της Python" %}

{% include figure image_path="/images/guido-headshot.jpg" caption="Figure 2: Ο Δημιουργός της: Guido Van Rossum" %}

Η Python μπορεί να επεκταθεί προσθέτοντάς της καινούργια modules που να είναι γραμμένα σε μια
γλώσσα που μεταγλωττίζεται, όπως είναι η C ή η C++. Αυτά τα modules επέκτασης μπορούν να 
ορίσουν νέες συναρτήσεις (functions) και μεταβλητές (variables) καθώς επίσης και καινούργιους
τύπους δεδομένων (object types). Η Python συγκρίνεται συχνά μ’ άλλες διερμηνευόμενες γλώσσες
προγραμματισμού, όπως είναι οι Java, JavaScript, Perl, Tcl και η Smalltalk, αλλά συγκρίσεις
μπορούν να γίνουν και με τις C++, Common Lisp και Scheme.
Ο κύριος στόχος της είναι η αναγνωσιμότητα του κώδικά της και η ευκολία χρήσης
της. Διακρίνεται λόγω του ότι έχει πολλές βιβλιοθήκες που διευκολύνουν ιδιαίτερα
αρκετές συνηθισμένες εργασίες και για την ταχύτητα εκμάθησης της.
Η Python αναπτύσσεται ως ανοιχτό λογισμικό (open source) και η διαχείρισή της
γίνεται από τον μη κερδοσκοπικό οργανισμό Python Software Foundation. Ο
κώδικας διανέμεται με την άδεια Python Software Foundation License η οποία είναι
συμβατή με την GPL. Το όνομα της γλώσσας προέρχεται από την ομάδα άγγλων
κωμικών Μόντυ Πάιθον.

Eπομένως, καταλήγουμε στο συμπέρασμα πως οι υπολογιστές τσέπης φέρειπειν: raspberry pi, odroid-c4,
odroid-n2l, odroid-h3/h3+ κα. μπορούν με ευκολία να υποστηρίξουν την γλώσσα υψηλού επιπέδου Python
κατεβάζοντας τον πηγαίο κώδικά της στον αντίστοιχο υπολογιστή και τρέχοντας το script με κατάληξη .sh
μπορεί να γίνει compiled και να υποστηριχτεί από τον υπολογιστή. Πέραν αυτού, η Python σύμφωνα με τα
στατιστικά στοιχεία του ιδρύματος TIOBE, προκύπτει πως βρίσκεται στην πρώτη θέση της κατάταξης
με στατιστικά μέτρα από τον Νοέμβριο του 2022 με ποσοστό χρήσης: 17,18% από όλον τον κόσμο. 

{% include figure image_path="/images/python-statistics-2022.jpg" caption="Figure 3: Τα στατιστικά στοιχεία από την ιστοσελίδα TIOBE. Πηγή: TIOBE: https://www.tiobe.com/tiobe-index/python/" %}

Τέλος, προκύπτει ο παρακάτω πίνακας με τα στοιχεία κατάταξης των γλωσσών προγραμματισμών που 
χρησιμοποιούνται από όλον τον κόσμο, κατατάσσοντας την Python στην πρώτη θέση, στην δεύτερη την
C, στην τρίτη την Java, στην τέταρτη την C++ και στην πέμπτη την C#

{% include figure image_path="/images/programming-languages-statistics-2022.jpg" caption="Figure 4: Τα στατιστικά στοιχεία από την παγκόσμια κατάταξη των γλωσσών προγραμματισμού από την ιστοσελίδα TIOBE. Πηγή: TIOBE: https://www.tiobe.com/tiobe-index/" %}

[^1]: fig: python-language