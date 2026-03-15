## School-Ontology
A basic school ontology built using Protege.

## Classes in the Ontology:
- owl:Thing
  - Person
    - Lecturer
    - Student
    - Course

## Object Properties:
- teaches (Lecturer -> Student)
- learnsFrom (Student -> Lecturer)
- offers (Student -> Course)
- isOfferedBy (Course -> Student)
- handles (Lecturer -> Course)
- isHandledBy (Course -> Lecturer)

## Data Properties:
- CourseName (Course -> xsd:string)
- lectName (Lecturer -> xsd:string)
- lectAge (Lecturer -> xsd:integer)
- lectPosition (Lecturer -> xsd:string)
- stdAge (Student -> xsd:integer)
- stdName (Student -> xsd:string)
- stdRegNumber (Student -> xsd:string)


## Sample DL Queries to retrieve data:
- > Lecturer and teaches some Student and handles some Course
- > Student and offers some Course and learnsFrom some Lecturer


# Graphical view (OntoGraf):
<img width="939" height="456" alt="image" src="https://github.com/user-attachments/assets/3bde9d46-79cf-4229-a085-d05a6407713f" />

# OwlViz:
<img width="298" height="125" alt="image" src="https://github.com/user-attachments/assets/2bacb004-6fa6-41ef-9983-09768de8adbb" />
