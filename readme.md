![Laravel](https://laravel.com/assets/img/components/logo-laravel.svg)

<h1 align="center">Genealogy Application</h1>

## About
Genealogy (Silsilah) application to record our family members.

## Features
This application uses Bahasa Indonesia and English based on `config.locale`.

### Logic Concept
1. A person can have one father
2. A person can have one mother
3. A person can have one parent (couple of mother and father)
4. A person can have 0 to many children
5. A person can have 0 to many spouses (husbands or wife)
6. A couple can have 0 to many children (based on parent_id)

### Family Member Entry
1. Enter Name and Gender
2. Set Father
3. Set Mother
4. Add Spouse
5. Add Child

### Person Attribute
1. Nickname
2. Gender
3. Fullname
4. Date of birth
5. Date of death (or at least year of death)
6. Address
7. Phone Number
8. Email

### Couple Attribute (TODO)
1. Husband
2. Wife
3. Marriage Date
4. Divorce Date
5. Address
