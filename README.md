# Modal Window using CSS, HTML and JavaScript (course "The Complete JavaScript Course 2023: From Zero to Expert!" by Jonas Schmedtmann)

JavaScript code sets up a modal window with open and close functionality using strict mode:
   
1. It begins by selecting the necessary HTML elements:
   
**'modal'**: Represents the modal dialog box.  
**'overlay'**: Represents the overlay background behind the modal.  
**'btnCloseModal'**: Represents the close button within the modal.  
**'btnOpenModal'**: Represents an array of buttons that trigger the modal to open.  
   
2. Two functions, **'openModal'** and **'closeModal'**, are defined:  
**'openModal'**: Removes the 'hidden' class from both the modal and overlay elements to display the modal.  
**'closeModal'**: Adds the 'hidden' class to both the modal and overlay elements to hide the modal.  
   
4. A **'for'** loop iterates through each button in **'btnOpenModal'** and attaches an event listener to open the modal when any of these buttons are clicked. It calls the **'openModal'** function.  
   
5. An event listener is added to the **'btnCloseModal'** element to close the modal when the close button is clicked. It calls the **'closeModal'** function.  
Another event listener is added to the **'overlay'** element to close the modal when the overlay background is clicked. It also calls the **'closeModal'** function.  
   
6. Finally, a global event listener is set up for the 'keydown' event. If the 'Escape' key is pressed and the **'modal'** element does not have the 'hidden' class, it calls the closeModal function, effectively closing the modal.  
    
This code creates a basic modal window that can be opened and closed using buttons or the 'Escape' key, all while adhering to strict JavaScript mode for enhanced code quality.  
