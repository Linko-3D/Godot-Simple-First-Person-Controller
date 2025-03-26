# Simple First Person Controller  

A simple **Godot First-Person Controller** with movement, jumping, walking, crouching, footstep sounds and smooth animations.  

### **Input Setup:**  
Configure these inputs in the **Input Map**:  
- **forward** (*W recommended*)  
- **backward** (*S recommended*)  
- **left** (*A recommended*)  
- **right** (*D recommended*)  
- **jump** (*Space recommended*)  
- **walk** (*Shift recommended*)  
- **crouch** (*Ctrl recommended*)  

### **Features:**  
- **Ceiling Detection:** Uses a **raycast** to prevent uncrouching if there’s not enough space.  
- **Landing Animation:** Smooth transition when hitting the ground after a fall or jump.  