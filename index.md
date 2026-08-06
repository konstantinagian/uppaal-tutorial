# UPPAAL

## Εισαγωγή

Το UPPAAL είναι ένα εργαλείο μοντελοποίησης, προσομοίωσης και επαλήθευσης συστημάτων πραγματικού χρόνου. Υποστηρίζει τόσο την τυπική επαλήθευση (formal verification) όσο και το Statistical Model Checking, επιτρέποντας την ανάλυση της συμπεριφοράς ενός συστήματος μέσω εξαντλητικής εξερεύνησης ή στατιστικών προσομοιώσεων, ανάλογα με το είδος του προβλήματος. Τα συστήματα μοντελοποιούνται ως δίκτυα αυτομάτων (automata).

## Γενικά παραδείγματα

Ακολουθούν κάποια παραδείγματα που παρουσιάζουν τις βασικές λειτουργίες του εργαλείου.

- [Λάμπα με χρονοδιακόπτη](lamp.md)
- [Φανάρια - Statistical Model Checking](traffic_lights.md)
- [Φανάρια - Stratego](traffic_lights_stratego.md)

Παρακάτω βρίσκονται τα πλήρη UPPAAL μοντέλα για το κάθε παράδειγμα (μαζί με τα queries) και μπορείτε να τα ανοίξετε με το UPPAAL κατεβάζοντάς το από [εδώ](https://uppaal.org/downloads/).

- [lamp.xml](models/lamp.xml)
- [traffic_lights.xml](models/traffic_lights.xml)
- [traffic_lights_stratego.xml](models/traffic_lights_stratego.xml)

## Μοντελοποίηση ενός IoT συστήματος με το UPPAAL

Θα αναπτύξουμε βήμα προς βήμα ένα μοντέλο ενός απλού συστήματος Internet of Things (IoT) στο UPPAAL. Συνεχίζουμε παράλληλα να παρουσιάζουμε διάφορες λειτουργίες του εργαλείου.

- [Μέρος 1ο - Απλή υλοποίηση](IoTSystemV1.md) ([v1.xml](models/IoTSystemV1.xml))
- [Μέρος 2ο - Προσθήκη ουράς](IoTSystemV2.md) ([v2.xml](models/IoTSystemV2.xml))
- [Μέρος 3ο - Κάνοντας τις συσκευές non-blocking](IoTSystemV3.md) ([v3.xml](models/IoTSystemV3.xml))
- [Μέρος 4ο - Statistical Model Checking](IoTSystemV4.md) ([v4.xml](models/IoTSystemV4.xml))
- [Μέρος 5ο - Προσθήκη ενδιάμεσων Gateways](IoTSystemV5.md) ([v5.xml](models/IoTSystemV5.xml))
