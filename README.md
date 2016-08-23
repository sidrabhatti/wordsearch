# wordsearch

A fun rails application that uses a word search game with Phaser.io 

/app/views/home/index.html.erb contains the phaser game js.

All other JS files can be found under /vendor/assets/javascripts. The main files are main.js, gameover.js, and gametitle.js.  The titles and gameboard are all being created in main.js.  The dicitonary that is referenced in the main.js file can be found under app/assets/javascripts/dictionary.txt.

This game can be played on both desktop and mobile, however for it is optimizes for desktop.  A swipe can be done in any direction as long as it consist of a consecutive touch event.  

Use foreman start to start the application and then visit localhost:5000 in your browser to get started.  
