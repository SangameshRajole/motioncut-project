<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0,0" />
    <title>Search Bar with Dropdown</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url(pic.jpg);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .search-bar {
            display: flex;
            align-items: center;
            width: 600px;
            border-radius: 28px;
            background: #f6f6f6;
            color: #8e4496;
        }
        .search-bar::placeholder,
        .search-bar {
            color: #8e4496;
        }
        .search-bar input {
            outline: none;
            border: none;
            background: transparent;
            align-items: center;
            width: 600px;
        }
        .search-bar select {
            padding: 10px;
            border-radius: 28px;
            background-color: #8e4496;
            color: #f6f6f6;
        }
    </style>
</head>
<body>
    <div class="search-bar">
        <select>
            <option value="Everything">Everything</option>
            <option value="Software development">Software development</option>
            <option value="Web development">Web development</option>
            <option value="Data Analyst">Data Analyst</option>
            <option value="IT Consultant">IT Consultant</option>
            <option value="Network administrator">Network administrator</option>
        </select>
            <input placeholder=" Search Anything"  type="text" ><span class="material-symbols-outlined">search</span>
            
    </div>
</body>
</html>
