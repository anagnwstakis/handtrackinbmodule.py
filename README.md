# handtrackinbmodule.py
Overview

Το handtrackingmodule.py είναι μια εφαρμογή Python που χρησιμοποιεί Computer Vision και Hand Tracking για τον έλεγχο της έντασης ήχου του συστήματος μέσω χειρονομιών.

Η εφαρμογή ανιχνεύει το χέρι του χρήστη μέσω κάμερας και υπολογίζει την απόσταση μεταξύ του αντίχειρα και του δείκτη. Η απόσταση αυτή μετατρέπεται σε επίπεδο έντασης ήχου των Windows σε πραγματικό χρόνο.

Features
Real-time hand tracking με MediaPipe.
Ανίχνευση έως ενός χεριού.
Υπολογισμός απόστασης μεταξύ landmarks.
Έλεγχος έντασης ήχου μέσω χειρονομιών.
Οπτική ένδειξη ποσοστού έντασης.
Εμφάνιση volume bar στην οθόνη.
Mirror camera view για φυσικό χειρισμό.
Requirements
Python Version
Python 3.8 ή νεότερη
Dependencies

Εγκαταστήστε τις απαραίτητες βιβλιοθήκες:

pip install opencv-python mediapipe numpy pycaw comtypes
Project Structure
handtrackingmodule.py






Το αρχείο περιέχει:

Την κλάση HandDetector
Τη λογική ανίχνευσης χεριού
Τον έλεγχο έντασης ήχου
Την κύρια συνάρτηση εκτέλεσης (main())
Class: HandDetector




<img width="794" height="595" alt="Screenshot_1" src="https://github.com/user-attachments/assets/60702d21-8c86-4bb8-bafd-fc0fa6e2393c" />

