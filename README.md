# Repo

https://cdn.keepo.me/images/post/lists/2020/04/17/main-list-image-d422140d-dbf2-4956-8666-6fb36217a876-3.jpg


from kitchen import Mug,Coffee

mug = Mug()
while True:
      if mug.status == “empty”:
            mug.refill(Coffee)
      else:
            mug.drink()
