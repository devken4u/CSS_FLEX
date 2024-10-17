# Flex Box
    The flexible box layout module (usually referred to as flexbox) is a one-dimensional layout\
    model for distributing space between items and includes numerous alignment capabilities.
    This article gives an outline of the main features of flexbox, which we will explore in more detail in the rest of these guides.

    The flex container properties are:
    flex-direction
    flex-wrap
    flex-flow
    justify-content
    align-items
    align-content

    Visit https://www.w3schools.com/css/css3_flexbox.asp for more information.

# Example code
style.css

    .flex-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
    }
    
    .flex-child {
      border: 2px solid black;
    }
    
    .profile {
      width: 300px;
    }
    
    .profile img {
      width: 100%;
    }
