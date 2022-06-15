from codecs import namereplace_errors
from shutil import register_unpack_format


print ("===============================")
print ("                    ")

data = input (" masukan nama: ")
data = input (" masukan nomer mahasiswa: ")
data = input (" masukan alamat rumah: ")
print (" nama  = ",data,)
print (" nomer mahasiswa = ",data,)
print (" alamat runah = ",data,) 


print("===========================")
print("nilai uts")
nilai = 75

if 80 <= nilai <= 100:
    print (" nilai anda adalah A")
elif  51 <= nilai < 80:
    print (" nilai anda adalah B")
elif  31 <= nilai < 50:
    print (" nilai anda adalah C")
elif  10 <= nilai < 30:
    print (" nilai anda adalah D")
else:
    print (" maaf anda tidak lulus mata kuliah ini ")

print("===========================")

class dosen():

    def nama_dosen(self):
        nama = " pak agung "
        return nama
    
    def nilai_dosen(self):
        nilai = "75"
        return nilai

    def cetak(self):
        print (" nama dosen \t:", self.nama_dosen())
        print (" nilai dosen \t:", self.nilai_dosen())


ftr = dosen ()
ftr. cetak()
