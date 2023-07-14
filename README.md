import random

def signature():
  """Generates a fancy signature for Surinder Singh."""
  name = "Surinder Singh"
  initials = "S.S."
  random_char = random.choice("!@#$%^&*()_-")
  return f"""
    {name} {initials} {random_char}
    \n
    [![Github](https://img.shields.io/badge/github-%23121212.svg?style=flat-square)](https://github.com/surindersingh)
    [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=flat-square)](https://www.linkedin.com/in/surindersingh/)
    [![Twitter](https://img.shields.io/badge/twitter-%231DA1F2.svg?style=flat-square)](https://twitter.com/surindersingh)
  """

if __name__ == "__main__":
  print(signature())
