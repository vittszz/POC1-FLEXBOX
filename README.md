# POC1-FLEXBOX
POC 1 - FlexBox
  html:
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PoC Flexbox</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="item">Item 1</div>
        <div class="item">Item 2</div>
        <div class="item">Item 3</div>
    </div>
</body>
</html>

CSS;

.container {
    display: flex;
    flex-direction: row; 
    justify-content: space-around; /
    align-items: center; 
    height: 100vh; 
    background-color: #f0f0f0;
}

.item {
    background-color: #007bff;
    color: white;
    padding: 20px;
    border-radius: 8px;
    text-align: center;
    font-size: 1.2em;
}
