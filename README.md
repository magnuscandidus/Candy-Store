# Candy-Store
# cook your dish here
store = int(input())
for s in range(store):
  X,Y = map(int, input().split())
  commision = X+((Y-X)*2)
  if Y>X: print(commision)
  else: print(Y)
