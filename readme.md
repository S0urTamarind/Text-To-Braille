# TEXT TO BRAILLE CONVERTER
## Team Members:  
  1\. Alen Basil Thelappilly, 221CS206, alenbasilthelappilly.221cs206@nitk.edu.in
  
  2\. Hemanth Kumar P L, 221CS225, hemanthkumarpl.221cs225@nitk.edu.in
  
  3\. Rathod Smit Amitkumar, 221CS238, smit.221cs238@nitk.edu.in
  
## Abstract:
  This project aims to create a Text to Braille Converter using logic
  gates, integrated circuits (ICs), and advanced design techniques,
  emphasizing creating a foundational component for various Braille
  equipment. While the primary motivation for this project is to improve
  accessibility for the visually impaired by enabling text-to-Braille
  conversion, we see this component as a versatile building block for
  various Braille devices and systems, such as notetakers, refreshable
  Braille displays, and embossers.

  **Background**
  
  When accessing printed information, visually impaired people frequently
  face formidable obstacles, and Braille, with its raised-dot tactile
  system, provides an essential means of communication.
  
  **Our unique contribution**
  
  Existing assistive technologies have primarily addressed converting
  Binary-Coded Decimal (BCD) numbers to Braille using logic gates and ICs,
  leaving a significant gap in text conversion. We plan to fill this void
  by creating a Text to Braille Converter that uses logic gates,
  integrated circuits, and advanced design techniques.
  
  **Motivation**
  
  The primary goal of our project is to create a robust and adaptable
  component capable of efficiently converting textual content into Braille
  patterns so that visually impaired people have more access to written
  text.
  
  **Summary**
  
  Our project is developing a Text to Braille Converter using logic gates,
  integrated circuits, and advanced design techniques to create a
  versatile foundation for diverse Braille equipment. By focusing on this
  fundamental component, we hope to improve accessibility, independence,
  and inclusivity for people with visual impairments in the future, paving
  the way for many innovative Braille solutions.

## Working description :
  **Introduction:**
  
  In our ever-evolving world, technology continues to be a powerful force
  in bridging gaps and fostering inclusivity. In line with this ethos, we
  present a project that can potentially transform the lives of
  individuals with visual impairments by providing them with a more
  accessible means of understanding and interacting with the written word.
  The English-to-Braille conversion system, fueled by integrated circuits
  (ICs), embodies innovation with a purpose - to make information
  available to all.
  
  **Key Components:**
  
  1\. Keyboard Input Interface:
  
  The foundation of our project rests on a user-friendly keyboard input
  interface. We recognize the importance of simplifying the process for
  individuals with visual impairments to input English characters for
  conversion into Braille. This interface stands as a beacon of
  accessibility, ensuring that they can easily communicate their thoughts
  and needs. To make the keyboard, we make use of tactile push button
  switches. Each button represents a character on the keyboard.
  
  2\. Encoder:
  
  At the heart of our system lies the encoder, a crucial element that
  bridges English and Braille. It is designed to perform the intricate
  task of translating the entered English characters into a compact 5-bit
  representation. This encoding scheme is carefully crafted to ensure that
  it effectively captures the essence of the English alphabet, numbers,
  and various symbols in a format that can be readily transformed into
  Braille. To make this, we use 5 OR gates.
  
  3\. Converter to Braille Output:
  
  Following the encoding process, the converter stage takes the 5-bit
  representation and performs a remarkable transformation, rendering the
  information in 6-bit Braille output. This stage is where the magic
  happens, as it translates the encoded data into tactile patterns that
  correspond to Braille characters. The converter thus empowers
  individuals with visual impairments by giving them access to a form of
  communication that is both efficient and universally recognized. The
  converter uses a combination of AND, OR, and NOT gates.
  
  **Purpose:**
  
  Our project has a profound and noble purpose: to empower individuals
  with visual impairments, granting them the independence to access and
  comprehend written information in Braille. This endeavor aligns
  seamlessly with the broader mission of making technology more inclusive
  and accessible, emphasizing equal opportunities for all. It is a
  testament to our commitment to fostering a more equitable and just
  society where everyone can engage with the world around them, regardless
  of their abilities.
  
  **Conclusion:**
  
  In conclusion, the English-to-Braille converter using integrated
  circuits is not just a technological advancement but a significant
  endeavor with a noble purpose. As technology advances, we should never
  forget that its true power lies in its capacity to make the world a
  better place for everyone, irrespective of their abilities or
  disabilities.

  ## Working:
  
  |Alphabets/Numerals|Input Format|Encoded|<p>Braille</p><p>○ = 0</p><p>● = 1</p>|
  | :-: | :-: | :-: | :-: |
  |A|0000000000000000000000000**1**|00001|<p>●○</p><p>○○</p><p>○○</p>|
  |B|000000000000000000000000**1**0|00010|<p>●○</p><p>●○</p><p>○○</p>|
  |C|00000000000000000000000**1**00|00011|<p>●●</p><p>○○</p><p>○○</p>|
  |D|0000000000000000000000**1**000|00100|<p>●●</p><p>○●</p><p>○○</p>|
  |E|000000000000000000000**1**0000|00101|<p>●○</p><p>○●</p><p>○○</p>|
  |F|00000000000000000000**1**00000|00110|<p>●●</p><p>●○</p><p>○○</p>|
  |G|0000000000000000000**1**000000|00111|<p>●●</p><p>●●</p><p>○○</p>|
  |H|000000000000000000**1**0000000|01000|<p>●○</p><p>●●</p><p>○○</p>|
  |I|00000000000000000**1**00000000|01001|<p>○●</p><p>●○</p><p>○○</p>|
  |J|0000000000000000**1**000000000|01010|<p>○●</p><p>●●</p><p>○○</p>|
  |K|000000000000000**1**0000000000|01011|<p>●○</p><p>○○</p><p>●○</p>|
  |L|00000000000000**1**00000000000|01100|<p>●○</p><p>●○</p><p>●○</p>|
  |M|0000000000000**1**000000000000|01101|<p>●●</p><p>○○</p><p>●○</p>|
  |N|000000000000**1**0000000000000|01110|<p>●●</p><p>○●</p><p>●○</p>|
  |O|00000000000**1**00000000000000|01111|<p>●○</p><p>○●</p><p>●○</p>|
  |P|0000000000**1**000000000000000|10000|<p>●●</p><p>●○</p><p>●○</p>|
  |Q|000000000**1**0000000000000000|10001|<p>●●</p><p>●●</p><p>●○</p>|
  |R|00000000**1**00000000000000000|10010|<p>●○</p><p>●●</p><p>●○</p>|
  |S|0000000**1**000000000000000000|10011|<p>○●</p><p>●○</p><p>●○</p>|
  |T|000000**1**0000000000000000000|10100|<p>○●</p><p>●●</p><p>●○</p>|
  |U|00000**1**00000000000000000000|10101|<p>●○</p><p>○○</p><p>●●</p>|
  |V|0000**1**000000000000000000000|10110|<p>●○</p><p>●○</p><p>●●</p>|
  |W|000**1**0000000000000000000000|10111|<p>○●</p><p>●●</p><p>○●</p>|
  |X|00**1**00000000000000000000000|11000|<p>●●</p><p>○○</p><p>●●</p>|
  |Y|0**1**000000000000000000000000|11001|<p>●●</p><p>○●</p><p>●●</p>|
  |Z|**1**0000000000000000000000000|11010|<p>●○</p><p>○●</p><p>●●</p>|

  Flowchart
  --
  
  ![[flowchart](https://github.com/S2-team11/Text-To-Braille-S2T11/assets/148744908/87d28f7b-7096-4aba-a7af-e4625fc169d0)](https://github.com/S2-team11/Text-To-Braille-S2T11/blob/8f1c00fd382b7f3820590041626200436f521478/Snapshots/Flowchart.png)

## Logisim Circuit Diagram :
  Main :
  --
  
   ![Snapshots/main.png](https://github.com/S2-team11/Text-To-Braille-S2T11/blob/4249933660e01bb4933c287331a4871fd2fc09d4/Snapshots/main.png)
  --
  Converter :
  --
  
   ![[converter](https://github.com/S2-team11/Text-To-Braille-S2T11/assets/148744908/3f30b9a4-47b5-428b-9b32-d162b0f49f63)](https://github.com/S2-team11/Text-To-Braille-S2T11/blob/c1ac70bd42d6ea3be6482357a4dc9b9b22fbea84/Snapshots/converter.png)
  --
  Delay : 
  --
  
   ![[Delay](https://github.com/S2-team11/Text-To-Braille-S2T11/assets/148744908/d4a14560-51ea-4d43-9fcf-647acb2f6e42)](https://github.com/S2-team11/Text-To-Braille-S2T11/blob/c1ac70bd42d6ea3be6482357a4dc9b9b22fbea84/Snapshots/Delay.png)
  --
  Counter :
  --
  
  ![[Counter](https://github.com/S2-team11/Text-To-Braille-S2T11/assets/148744908/9daff273-9097-47ee-bd4a-92cb4e5fafc1)](https://github.com/S2-team11/Text-To-Braille-S2T11/blob/5ebc70704a74ea2de9dc192780c60da77a2ec8cd/Snapshots/Counter.png)
  --
