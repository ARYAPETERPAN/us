impor  jawa . menggunakan . Pemindai ;

public  class  TugasArray1 {
    public  static  void  main ( String [] args ) {
        Sistem . keluar . println ( "Nomor 1" );
         Masukan pemindai = Pemindai baru  ( System.in ) ; _

        Sistem . keluar . print ( "Masukkan jumlah data: " );
        int  jumlahData = masukan . nextInt ();

        ganda  totalNilai = 0 ;

        Sistem . keluar . println ( "________________________________" );

        for ( int  i = 1 ; i <= jumlahData ; i ++) {
            Sistem . keluar . println ( "Mahasiswa Ke : " + i );

            Sistem . keluar . print ( "Nama: " );
            String  nama = masukan . berikutnya ();

            Sistem . keluar . print ( "Nila: " );
            int  nilai = masukan . nextInt ();

            jumlahNilai += nilai ;

            Sistem . keluar . println ( "________________________________" );
        }

        Sistem . keluar . println ( "DAFTAR NILAI MAHASISWA" );
        Sistem . keluar . println ( "================================" );
        Sistem . keluar . println ( "No\tNama\tNilai\tStatus" );

        double  rataRata = totalNilai / jumlahData ;
        int  nomor = 1 ;

        for ( int  i = 1 ; i <= jumlahData ; i ++) {
            Sistem . keluar . cetak ( nomor + "\t" );
            nomor ++;

            String  nama = masukan . berikutnya ();
            Sistem . keluar . print ( nama + "\t" );

            int  nilai = masukan . nextInt ();
            Sistem . keluar . print ( nilai + "\t" );

            if ( nilai >= rataRata ) {
                Sistem . keluar . println ( "Lulus" );
            } lain {
                Sistem . keluar . println ( "Tidak Lulus" );
            }
        }

        Sistem . keluar . println ( "================================" );
        Sistem . keluar . println ( "Jumlah: " + jumlahNilai );
        Sistem . keluar . println ( "Nilai Rata-rata: " + rataRata );
    }
}
