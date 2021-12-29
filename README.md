# Arch-3
3rd lab for Computer Arch

1 Έτρεξαν διαφορα πειράματα και σύγκριναν την έξοδο του McPAT με published data για τους επεξεργαστες:
* Niagara 90mm at 1.2Ghz
* Niagara2 65mm at 1.4Ghz
* Xeon 65nm at 3.4Ghz
* Alpha 180nm at 1.2Ghz

Θεώρησαν ότι αυτοί οι επεξεργαστές εξαιτίας των διαφορών στην αρχιτεκτονική τους θα επιβεβαίωναν πλήρως την λειτουργικότητα του McPAT.  

2 Υποθέτω οτι θα επηρεαστεί αναλογα με το πόσο CPU time χρειάζεται κάθε πρόγραμμα - πόσα access στην μνήμη έχει κοκ.  
Ανάλογα με το leakage power κάθε επεξεργάστη προς το total power μπορεί να είναι περισσότερο ή λιγότερο efficient.  


ΑRM peak power 1.74 Watt - Xeon peak power 134.938 Watt
ARM total leakage 0.1 Watt - Xeon total leakage 36.83 Watt

We use sim seconds as the delay  
