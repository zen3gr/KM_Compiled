# KAEK Maker

Το πρόγραμμα KAEK Maker επιτρέπτει το σχεδιασμό polylines που περιγράφουν ΚΑΕΚ όπως αυτά υπάρχουν αναρτημένα στο maps.gov.gr  
Το πρόγραμμα διαβάζει την λίστα των ΚΑΕΚ που επιθυμούμε και τα σχεδιάζει εξαρτημένα στο .dwg αρχείο που είναι ανοικτό [σε περίπτωση που για την περιοχή υπάρχουν 2 polylines, για παράδειγμα ανάρτησης και προανάρτησης, το πρόγραμμα τα σχεδιάζει με διαφορετικό χρώμα].

## Προϋποθέσεις - Τρόπος λειτουργίας

HTTP request για ΚΑΕΚ συντεταγμένες & άδεια-trial  
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
Powershell v5 ή μεταγενέστερο
AutoCAD 2007 ή μεταγενέστερο
```

## Usage

```python
Τραβάμε το αρχείο __kaek_maker.VLX__ μέσα στο παράθυρο του σχεδίου και πληκτρολογούμε km  
Στο κουτάκι που εμφανίζεται γράφουμε το ΚΑΕΚ ή τα ΚΑΕΚ που θέλουμε, στη δεύτερη περίπτωση χωρισμένα μεταξύ τους κόμμα (,)

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)