import streamlit as st;

class Rectangle:
    def _init_(self, width, height):
        self.width = width
        self.height = height

    def area(self):
        return self.width * self.
def main():
   
    rect = Rectangle(3, 4)


    st.write("Width:", rect.width)
    st.write("Height:", rect.height)


    st.write("Area:", rect.area())

if _name_ == '_main_':
    main()
