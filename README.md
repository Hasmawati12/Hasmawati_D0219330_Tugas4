class Warung():
  def__init__(self,nama,menu,alamat,):
    self.nama = nama
    self.menu = menu
    self.alamat = alamat
  def cek_id_warung(self):
    print("nama:",self.nama, '\nmenu:',self.menu, '\nalamat:',self.alamat)
    
class Warungped(Warung):
  def cek_id_warung(self):
    print('cek aja warungped')
    
warung1 = Warung('Maros','Roti','Pare-pare')
warung2 = Warungped('Makassar','ikan bakar','pinrang')
    
warung1.cek_id_toko()
warung2.cek_id_toko()
