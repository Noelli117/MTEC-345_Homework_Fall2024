# MTEC-345_Homework_Spring2024




  

  

  

# Song One Mantra  by DJSwami 

- drone which was used to generate ambient drones. *AI Test Kitchen MusicFX*
- Women Vx  was then layered and enhanced using *Kits.AI's voice cloning technology*.This tool allowed us to create different vocal textures by blending her voice with AI-generated vocals, enriching the auditory experience with diverse and harmonious layers
- others has some human performance 
# **AI-Assisted Computer Programming**
- Cursor:  
        - Have a trouble to combine Cursor with xcode/ VS studio. 
        - How to solve: 
                

- Use Obsidian to create a markdown file.
  

### Data Preprocessing:

-  Access MIDI Files: Collect MIDI files from classical compositions.

-  Convert MIDI Files to Images: Use music21 to transform MIDI data into images representing note sequences. Images are resized to a uniform shape (106x106) for easier processing.

### Construct Dataset:

-  Extract Image Data: Convert images into numerical arrays and prepare them for model training.

-  Split Sequences: Create input-output pairs where inputs consist of sequences of notes and outputs are the following notes.

### Build the ConvLSTM Model:

-  The architecture includes TimeDistributed layers with Conv1D, MaxPooling1D, LSTM layers, and a final Dense layer. The model is trained with MSE (Mean Squared Error) loss function.

### Some idea about draft idea for project: 

**Idea 1: Application to Learn CC11 and CC1 from User Behavior**  
This application will capture and learn how I use MIDI data, focusing on CC11 (Expression) and CC1 (Modulation) in my playing style. For example, I’ll use a sample library to create MIDI data, and practice with a VST instrument that fits my musical preferences. The application will track my input and learn my unique patterns. The goal is to use this data to improve future MIDI creation by adapting to my playing style. It will follow a similar approach to generating custom MIDI data tailored to my performance style.

**Idea 2: Creating a MIDI Collection**  
This concept involves building a comprehensive MIDI collection, featuring various pre-made sequences, patterns, and loops. The collection could cover multiple genres, instruments, and styles, allowing users to easily access and incorporate these MIDI files into their projects. This resource would save time and spark creativity by offering a versatile library that caters to different musical preferences. It could also include customizable elements, enabling users to adjust and personalize the MIDI data to fit their compositions.(ChatGPT reorganized words)

**Idea 3: Creating Variations in Film Scoring Using One Motion**  
This idea focuses on creating multiple variations of a single musical motion (or motif) by altering tempo and time signatures. The goal is to apply one musical idea to different scenes in a film by adjusting the tempo (speeding up or slowing down) and changing the measure (e.g., from 4/4 to 3/4). This approach would give the same musical motion a unique feel and emotional impact in different contexts, making it a versatile tool for film scoring.



