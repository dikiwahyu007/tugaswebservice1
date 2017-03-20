# tugaswebservice1
DTD di atas ditafsirkan seperti ini:
!DOCTYPE note mendefinisikan bahwa elemen root dari dokumen ini adalah catatan
!ELEMEN note  mendefinisikan bahwa elemen catatan berisi empat unsur: "ke, dari, judul, tubuh"
!ELEMEN to mendefinisikan untuk elemen untuk menjadi tipe "# PCDATA"
!ELEMEN from mendefinisikan dari unsur untuk menjadi tipe "# PCDATA"
!ELEMEN heading mendefinisikan elemen menuju dari tipe "# PCDATA"
!ELEMEN body mendefinisikan elemen body untuk menjadi tipe "# PCDATA"

Kosong elemen dideklarasikan dengan kata kunci kategori KOSONG:
<!ELEMENT element-name EMPTY>

Example:

<!ELEMENT br EMPTY>

XML example:

<br />
