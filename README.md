//---------------------------------------------------------------------------//
// Application console Manage Library
// Compiler: GNU C++, MSVS C++
//---------------------------------------------------------------------------//

# Manage Library

# Use Commands

- Build:    
~$ make
or
~$ make build

- Build Debug:
~$ make debug

- Run:
~$ ./main

- Remove files objects *.0 and excute file:
~# make clean

- Remove data file:
~# make clean-data

===============================================================================

1. Information list of books was storage in Books.bin file
2. Information list of borrows was storage in Borrows.bin file
3. Books.bin and Borrows.bin was storage in folder Data
4. Books.bin file has data template as below:

Note:
Data template was created depend on compiler GNU c++.
Data template will not display correctly when build with MSVS compiler on Windows.
So, If want build with MSVS (on Windows), 
need run command "make clean-data" to remove data template.

 DANH SACH THONG TIN SACH

 ===============================================================================================================================
 | STT | Ma sach | Ten sach                     | Nam XB | Nha xuat ban           | Tac gia                | The loai     | SL |
 -------------------------------------------------------------------------------------------------------------------------------
  1     123406    Tu duy nhanh va cham           2017     The gioi                 Daniel Kahneman          Kinh te        7    
  2     123405    Lap trinh C++                  2016     Minh Khai                Nhieu tac gia            Lap trinh      15   
  3     123404    Luoc su loai nguoi             2017     Tri thuc                 Harari                   Lich su        20   
  4     123403    Ky thuat lap trinh C           2018     Bach khoa Ha Noi         Nhieu tac gia            Lap trinh      15   
  5     123402    Nha gia kim                    2013     Van hoc                  Paulo Coelho             Van hoc        19   
  6     123401    Lap trinh C                    2010     Minh Khai                Pham Van Uat             Lap trinh      10   
 ===============================================================================================================================

===============================================================================
    Tong quan giao dien nhap xuat
===============================================================================

=====MENU CHINH================================================================

 CHUONG TRINH QUAN LY THU VIEN

 ============================================

 Moi ban chon

 1. Nhap thong tin sach.

 2. Danh sach thong tin sach.

 3. Muon sach.

 4. Tra sach.

 5. Danh sach phieu muon sach.

 6. Tim kiem.

 0. Thoat.

 ============================================

 Nhap lua chon cua ban: 

=====1 - PHAN NHAP THONG TIN SACH==============================================

 NHAP THONG TIN SACH

 Ma sach (6 so): 
 Ten sach: Ten 
 Nam xuat ban: 
 Nha xuat ban: 
 Ten tac gia: 
 The loai sach: 
 So luong: 

 Luu thong tin thanh cong!

=====2 - MENU DANH SACH SACH===================================================

 DANH SACH THONG TIN SACH

 1. Sap xep theo tieu de sach
 2. Sap xep theo nam xuat ban
 3. Sap xep theo nha xuat ban
 4. Sap xep theo tac gia
 5. Sap xep theo sach moi nhat
 0. Tro ve

 Nhap lua chon cua ban: 

=====2.5 - HIEN THI DANH SACH SACH=============================================

 DANH SACH THONG TIN SACH

 ===============================================================================================================================
 | STT | Ma sach | Ten sach                     | Nam XB | Nha xuat ban           | Tac gia                | The loai     | SL |
 -------------------------------------------------------------------------------------------------------------------------------
  1     123406    Tu duy nhanh va cham           2017     The gioi                 Daniel Kahneman          Kinh te        7    
  2     123405    Lap trinh C++                  2016     Minh Khai                Nhieu tac gia            Lap trinh      15   
  3     123404    Luoc su loai nguoi             2017     Tri thuc                 Harari                   Lich su        20   
  4     123403    Ky thuat lap trinh C           2018     Bach khoa Ha Noi         Nhieu tac gia            Lap trinh      15   
  5     123402    Nha gia kim                    2013     Van hoc                  Paulo Coelho             Van hoc        19   
  6     123401    Lap trinh C                    2010     Minh Khai                Pham Van Uat             Lap trinh      10   
 ===============================================================================================================================

=====3 - PHAN NHAP THONG TIN PHIEU MUON========================================

 NHAP THONG TIN PHIEU MUON SACH

 Ma phieu (6 so): 
 Ma nguoi muon (6 so): 
 Ten nguoi muon: 
 Ma sach (6 so): 
 Ma sach (6 so): 
 Ngay muon (dd/mm/yyyy): 
 Ngay muon (dd/mm/yyyy): 
 Ngay muon (dd/mm/yyyy): 

 Chon tinh trang sach:
 1: Tot
 2: Binh thuong
 3: Cu
 Tinh trang sach: 

 Nhap thong tin thanh cong!

======4 - PHAN NHAP THONG TIN TRA SACH=========================================

 NHAP THONG TIN TRA SACH

 Ma phieu (6 so): 
 Nhap ngay tra: 

 Chon tinh trang sach:
 1: Tot
 2: Binh thuong
 3: Cu
 Tinh trang sach: 

 Nhap thong tin thanh cong!

=====5 - MENU DANH SACH PHIEU MUON=============================================

 DANH SACH PHIEU MUON

 1. Danh sach phieu dang muon
 2. Danh sach phieu muon da tra
 3. Tat ca danh sach
 0. Tro ve

 Nhap lua chon cua ban: 
 
=====5.1 - MENU DANH SAP XEP PHIEU MUON==================================================

 DANH SACH PHIEU DANG MUON

 1. Sap xep theo ngay muon
 2. Sap xep theo ten nguoi muon
 0. Tro ve menu chinh

 Nhap lua chon cua ban:

=====5.2 - MENU DANH SAP XEP PHIEU MUON==================================================

 DANH SACH PHIEU DA TRA

 1. Sap xep theo ngay muon
 2. Sap xep theo ten nguoi muon
 3. Sap xep theo ngay tra
 0. Tro ve menu chinh

 Nhap lua chon cua ban:

======5.3 - HIEN THI DANH SACH PHIEU MUON==============================

 DANH SACH PHIEU DANG MUON

 ============================================================================================================================================
 | STT | Ma phieu | Ma nguoi muon | Ten nguoi muon         | Ma sach | Ten sach                     | Ngay muon | TT sach muon | Trang thai |
 --------------------------------------------------------------------------------------------------------------------------------------------
 ============================================================================================================================================


 DANH SACH PHIEU DA TRA

 =======================================================================================================================================================================
 | STT | Ma phieu | Ma nguoi muon | Ten nguoi muon         | Ma sach | Ten sach                     | Ngay muon | Ngay tra  | TT sach muon | TT sach tra  | Trang thai |
 -----------------------------------------------------------------------------------------------------------------------------------------------------------------------
 =======================================================================================================================================================================

