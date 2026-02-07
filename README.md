# atvd_andar

For:
for andar in range(20, 0, -1):
    if andar == 13:
        continue
    print(andar)

While:
andar = 20

while andar >= 1:
    if andar != 13:
        print(andar)
    andar -= 1

Simulando do while:
andar = 20

while True:
    if andar != 13:
        print(andar)
    andar -= 1
    if andar < 1:
        break
