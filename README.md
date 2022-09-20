antenas = int(input("Quantas antenas o alienígena tinha? "))
olhos = int(input("Quantos olhos o alienígena tinha? "))

if antenas >= 3 and olhos <= 4:
  print("Marciano")
if antenas <= 6 and olhos >= 2:
  print("Saturniano")
if antenas <= 2 and olhos <= 3:
  print("Mercuriano")
