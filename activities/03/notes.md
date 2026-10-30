# Lecture 03 Activity: Notes
Name: Karol Maeve L. Tacang · Student ID: 2023-0107

## My photos (Parts 0 to 6)
How many photos, and what each shows (one line each):

There are 5 photos in total:
1. Battery
2. Back of a certiificate holder 
3. Nail Cutter
4. Spoon
5. Wooden panel

## My dataset (Part 7)
Categories: Tumbler vs. Axe Spray
Photos per category: 21 and 21
How I took them (places, backgrounds, lighting, angles): I placed the objects in various locations inside the house like in the living room table, on top of a chair, on the floor, in the dining room table, and on the kitchen counter. I also tried t take the pictures from multiple angles and lightings. 
Final validation accuracy: transfer transfer 1.00 (100%) · from scratch 0.40 (40%)

## My kernel (Part 2c)
The numbers, and what it detects:

**Numbers:**
[ 0,  1,  2], 
[-1,  0,  1], 
[-2, -1,  0]

**What is detects:**
This kernel detects diagonal edges (specifically, edges that run from top-left to bottom-right). It works by comparing the top-right corner (positive weights) to the bottom-left corner (negative weights). If there is a bright line on the top-right and a dark line on the bottom-left, it outputs a strong positive response. Because the sum of the weights is 0, flat areas cancel out to zero, leaving only the diagonal edges visible.


## AI and outside help
List any AI tools, websites or classmates you used, and for what. Write "None" if none.

**AI Tools:**
  - Gemini: To help debug inline error
  - Deepseek: To help further understand concepts

**Classmates:** 
  - Kim Gabriel Nasayao: Helped me verify a few concepts