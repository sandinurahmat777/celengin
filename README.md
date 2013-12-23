List Dasar
======================
Base view
        Menyiapkan Page
Base model
        Menyiapkan Integritas Sesama Model
Base Controler
        Membangun Route
        Menyiapkan model yang akan di oper ke model
----------------------

Model

==> User
    email
    password
    photo_id => polimorphis
    alamat
    saldo balance

==> History
    User_id
    TaskTarget_id
    Amount
    Debit, integer, default = 0
    Credit, integer, default = 0
    Date
    
==> TargetSaving
    Name
    Description
    Url
    photo_id => polimorphis

==> photo
    ini polimorphis


Target maksimal
=========================================================
Social Media

huhuhuhuhuhuhuhu...........
