<!doctype html public "-//W3C//DTD HTML 4.0 Transitional//EN">
<font color="blue"><script type="text/javascript">
now = new Date();
if (now.getTimezoneOffset() == 0) (a=now.getTime() + ( 7 *60*60*1000))
else (a=now.getTime());
now.setTime(a);
var tahun= now.getFullYear ()
var hari= now.getDay ()
var bulan= now.getMonth ()
var tanggal= now.getDate ()
var hariarray=new Array("Minggu,","Senin,",
"Selasa,","Rabu,","Kamis,","Jum'at,","Sabtu,")
var bulanarray=new Array("Januari","Februari","Maret","April","Mei","Juni","Juli","Agustus","September","Oktober","Nopember","/ 12 /")
document.write(hariarray[hari]+" "+tanggal+" "+bulanarray[bulan]+" "+tahun)
</script>
<script type="text/javascript">
now = new Date();
if (now.getTimezoneOffset() == 0) (a=now.getTime() + ( 7 *60*60*1000))
else (a=now.getTime());
now.setTime(a);
document.write(" Jam " + ((now.getHours() < 10) ? "0" : "") + now.getHours() + ":" + ((now.getMinutes() < 10)? "0" : "") + now.getMinutes() + (" W.I.B "))
</script>
</font>
</!doctype>
