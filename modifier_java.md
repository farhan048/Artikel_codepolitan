# Modifier pada Java

## Apa Itu Modifier?
Modifier sebenarnya adalah Java keyword yang digunakan untuk memberikan "Sesuatu yang berbeda" pada kelas, method, ataupun property yang menggunakan modifier tersebut.

## Macam-Macam Modifier
Ada beberapa jenis modifier di Java, yaitu:
   - **public access modifier**
      - Sebuah kelas, method, ataupun property yang mempunyai akses modifier public artinya bahwa kelas, method, ataupun property tersebut dapat diakses oleh kelas manapun.

        Untuk memberikan akses modifier public di kelas, method, maupun property, Anda dapat memberikan kata kunci (keyword) public pada kelas, method, dan property tersebut.

        public class Studnet{

	    public String name;

	    public String getName(){

		return name;

	        }

        }

   - protected access modifier
      - Sebuah method, ataupun property yang mempunyai akses modifier protected artinya bahwa method, ataupun property tersebut dapat diakses hanya oleh kelas turunannya (subclass) dan hanya dapat diakses oleh kelas yang satu package,

        Anda tidak boleh memberikan akses protected pada kelas, dan interface. Anda juga tidak boleh memberikan akses protected pada method dan property pada interface.

        Anda dapat memberikan keyword protected untuk memberikan akses protected pada method, dan property yang akan di berikan akses protected.

        public class Studnet{

	    protected String name;

	    protected String getName(){

		return name;

	        }

        }
   - private access modifier
     - Access modifier private bersifat tertutup. Sesuai dengan konsep OOP Encapsulation, maka setiap variabel wajib untuk dilindungi hak aksesnya secara langsung dari luar. Oleh karena itu, variabel diberikan hak akses private dan untuk melakukan pengaksesan/perubahan data digunakan setter getter.
  
         public class Studnet{

	    private String name;

	    private String getName(){

		return name;

	        }

        }
   - no access modifier
     - Sesuai namanya, hak akses yang satu ini tidak perlu dituliskan di method/variabelnya. Dengan hak akses ini, variabel/method dapat diakses dari class lain asalkan masih dalam satu package yang sama.
      
      public class Kendaraan {

	   int jumlahRoda;

	   String warna;

      }
