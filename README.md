# Repo


from kitchen import Mug,Coffee

mug = Mug()
while True:
      if mug.status == “empty”:
            mug.refill(Coffee)
      else:
            mug.drink()
