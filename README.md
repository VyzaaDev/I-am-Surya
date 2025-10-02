<img width="3264" height="1018" alt="1000022250" src="https://github.com/user-attachments/assets/5cd55c85-e25d-43bc-b56f-f19502b9501b" />
impor  urllib2
UKURAN_PENYANGGA  =  256 * 1024
url  =  'http://downloads.sourceforge.net/project/pydev/pydev/PyDev%202.5.0/PyDev%202.5.0.zip?r=http%3A%2F%2Fsourceforge.net%2Fprojects%2Fpydev%2Ffiles%2F&ts=1338118912&use_mirror=nchc'
res  =  urllib2 . buka url ( url )
dengan  terbuka ( 'PyDev.zip' , 'wb' ) sebagai  f :
	sementara  Benar :
		potongan  =  res.baca ( UKURAN_BUFFER )​​
		jika ( bukan  potongan ):
			merusak		
		f . tulis ( potongan )
		cetak  len ( potongan )
