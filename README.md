# Clase-Python

Class Fraction:
   #atributos#
   numerator=0
   denominator=1
   
   #fin secion atribtos#

   def_init_(self,numerador,denominador):
      self.numerator=numerador
      self.denominator=denominador
      print("mi numerador es", numerador")
      print("mi denominador es", denominador")
      
   def print(self)
   # imprimir numerador y denominador con un slash
   print(self.numerator,"/",self.denominator)
   
   def multiplication(self,b):
         numerator = self.numerator*b.numerator
         denominator = self.denominator*b.denominator
         r = fraction(numerator,denominator)
         r.print()
         

a=fraction(3,2)
b=fraction(6,5)
a.print()
b.print()
