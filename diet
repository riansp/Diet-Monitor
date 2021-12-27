from time import gmtime
from time import strftime

print('Hei Sophi')
print('Selamat datang di program diet, kami akan membatasi kalori yang ada dalam tubuh anda')
print('Jika asupan kalori harian melebihi batas maksimal yaitu sebanyak 1500, maka kami akan memberikan tips untuk mengurangi kalori tersebut, dengan memberikan beberapa tips untuk olahraga dan berapa lama untuk melakukanya')
print('='*127)

diet = float(input('Masukan Jumlah Kalori Anda: '))
tips = diet - 1500
#print ('Kelebihan atau kekurangan kalori hari ini: ',tips)

time = tips/10*60
waktu = strftime("%H:%M:%S", gmtime(time))

if tips == 0:
    print('Kalori hari ini sangat bagus dan terus pertahankan')
elif (tips >=1) and (tips<450) :
    print('Anda kelebihan kalori hari ini sebesar:', tips,)
    print('maka anda harus melalukan olahraga dengan BERENANG selama:', waktu,'[Jam/Menit/Detik]')
elif (tips >=450) and (tips<800) :
    print('Anda kelebihan kalori hari ini sebesar: ', tips,)
    print('maka anda harus melalukan olahraga dengan BERSEPEDA selama:', waktu, '[Jam/Menit/Detik]')
elif tips >= 800 :
    print('Anda kelebihan kalori hari ini sebesar: ', tips,) 
    print('maka anda harus melalukan olahraga dengan BERLARI selama: ', waktu, '[Jam/Menit/Detik]')
else :
    print('anda kekurangan kalori sebanyak:', tips, 'sehingga harus perbanyak makan')

print('='*127)

print('Semoga Bermanfaat')
