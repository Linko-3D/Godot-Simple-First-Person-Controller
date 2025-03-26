# Simple First Person Controller  

A simple **Godot First-Person Controller** with movement, jumping, walking, crouching, and smooth animations.  

### **Input Setup:**  
Configure these inputs in the **Input Map**:  
- **Forward** (*W recommended*)  
- **Backward** (*S recommended*)  
- **Left** (*A recommended*)  
- **Right** (*D recommended*)  
- **Jump** (*Space recommended*)  
- **Walk** (*Shift recommended*)  
- **Crouch** (*Ctrl recommended*)  

### **Features:**  
- **Ceiling Detection:** Uses a **raycast** to prevent uncrouching if there’s not enough space.  
- **Landing Animation:** Smooth transition when hitting the ground after a fall or jump.  