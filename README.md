<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="javascript_library.js" defer></script>
    <link rel="stylesheet" href="styles_library.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Ubuntu+Condensed&display=swap" rel="stylesheet">
    <title>Library Project</title>
</head>
<body>
    <!--page header-->
    <div class="header">
        <div class="title">
            <h1>Book Library</h1>
        </div>
        <div class="loginBtn">
            <button class="btn login">login</button>
        </div>
    </div>
    
    <div class="bookInputContainer"> 
        <div class="book_info">
        <div class="book_title">
            <label for="title">Book Title:</label>
            <input class="bookInput" id="bookTitle"></input>
        </div>
        <div class="book_author">
            <label for="author">Book Author:</label>
            <input class="author bookInput" id="bookAuthor"></input>
        </div>
        <div class="book_pages">
            <label for="pages">Book Pages:</label>
            <input class="pages bookInput" id="bookPages" type="number" min="1" max="100000"></input>
        </div>
        <div class="read_notread">
            <label for="readStatus">Status:</label>
            <select name="readStatus" placeholder="" class="bookInput" id="readStatus">
                <option value="Read">Read</option>
                <option value="Not Read">Did not read</option>
            </select>
        </div> 
        </div>
        <div class="main_buttons">
            <div class="submit">
                <button class="submitbtn" type="submit">+submit</button>
            </div>
            <div class="clear">
                <button class="clearbtn" type="submit">-clear</button>
            </div>
        </div>
        
    </div>
    
<!--main book display-->
    <main class="main_display">    
         <div class="book_display">

        </div>


    </main>


    
   
</body>
</html>
