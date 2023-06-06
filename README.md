# OOP-excercise
class Cat:
  species = 'mammal'
  def __init__(self, name, age):
    self.name = name
    self.age = age



cat1 = Cat ('Charly', 3)
cat2 = Cat ('Tom', 7)
cat3 = Cat ('Baghira', 6)



def get_oldest_cat(*args):
    return max(args)


print(f'The oldest cat is {get_oldest_cat(cat1.age, cat2.age, cat3.age)} years old, and the cats name is {cat2.name}')


