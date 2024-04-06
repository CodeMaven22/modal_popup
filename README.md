# modal_popup
<body class="grid place-items-center h-screen">
    Begins the <body> section of the HTML document and applies several classes to it. These classes likely come from a CSS framework called 
    Tailwind CSS. They set the body to display as a grid, center its items both horizontally and vertically, and set its height to match the 
    screen height.
      
  <button id="open-modal-btn" class="px-4 py-2 bg-blue-500 text-white rounded">Open Modal</button>
     Creates a button element with the id "open-modal-btn" and some classes that style it using Tailwind CSS. This button will display the 
     text "Open Modal" and has a blue background, white text, rounded corners, and some padding.

   <div id="modal-wrapper" class="fixed z-10 inset-0 hidden">
     Creates a <div> element with the id "modal-wrapper" and applies several classes to it. This div will serve as a wrapper for the modal   
     content. It is initially hidden (hidden class), positioned as a fixed element (fixed class), with a z-index of 10 (z-10 class), and 
     spans the entire viewport (inset-0 class).

  <div class="flex items-center justify-center min-h-screen bg-gray-500 bg-opacity-75 transition-all">
     Within the modal wrapper div, this line creates another <div> element and applies several Tailwind CSS classes to it. This div will 
     serve as the backdrop for the modal. It is styled to display as a flex container with its items centered both horizontally and 
     vertically (flex items-center justify-center), has a minimum height of the screen (min-h-screen), has a semi-transparent gray 
     background (bg-gray-500 bg-opacity-75), and its appearance will transition smoothly (transition-all).

  <div class="flex flex-col items-center justify-between bg-white p-10 rounded w-2/3">
    Within the modal backdrop div, this line creates another <div> element that will serve as the actual modal box. It applies Tailwind 
    CSS classes to style it as a flex container with its items arranged in a column (flex flex-col), with its items centered both 
    horizontally and vertically (items-center justify-between), has a white background (bg-white), some padding (p-10), rounded corners 
    (rounded), and is set to occupy two-thirds of the width of its container (w-2/3).

