

# Customer Churn Prediction – Διπλωματική εργασία

Πρόβλεψη churn πελατών e-commerce με μεθόδους machine learning.

| Αρχείο | Περιγραφή |
|---|---|
| Word | Το κείμενο της διπλωματικής |
| Notebook (.ipynb) | Ο κώδικας της ανάλυσης |
| `data_dict.csv` | Λεξικό μεταβλητών |

## Δεδομένα

**Πηγή:** Η εργασία χρησιμοποιεί το [E-commerce churn dataset – REES46](https://www.kaggle.com/datasets/fridrichmrtn/e-commerce-churn-dataset-rees46) (Kaggle, δημιουργός: fridrichmrtn). Το dataset βασίζεται στην πλήρη έκδοση του [eCommerce behavior data from multi category store](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store) της REES46, που περιέχει δεδομένα συμπεριφοράς χρηστών από μεγάλο ηλεκτρονικό κατάστημα πολλών κατηγοριών για την περίοδο Οκτώβριος 2019 – Απρίλιος 2020. Τα αρχικά δεδομένα έχουν συλλεχθεί από το έργο Open CDP και ανήκουν στους αρχικούς δημιουργούς (© Original Authors).

**Περιεχόμενο:** Το αρχείο `customer_model.csv` περιέχει περίπου 112.000 εγγραφές με μεταβλητές συμπεριφοράς πελατών, όπως recency (χρόνος από την τελευταία συνεδρία ή αγορά) και frequency (αριθμός συνεδριών και αγορών). Η μεταβλητή-στόχος είναι το `target_event`, που δείχνει αν ο πελάτης έκανε churn (καμία συναλλαγή στην επόμενη περίοδο). Η πλήρης περιγραφή των μεταβλητών βρίσκεται στο `data_dict.csv`.

**Διαθεσιμότητα:** Το `customer_model.csv` (~262 MB) δεν περιλαμβάνεται στο repository λόγω μεγέθους.
