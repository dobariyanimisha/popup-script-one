# popup-script-one
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sales Popup Test Page</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        
        h1 {
            text-align: center;
            margin-bottom: 30px;
        }
        
        .product {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 20px;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
        }
        
        .product-image {
            width: 100px;
            height: 100px;
            background-color: #f0f0f0;
            margin-right: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .product-details {
            flex: 1;
        }
        
        .product-title {
            font-size: 18px;
            font-weight: bold;
            margin-bottom: 5px;
        }
        
        .product-price {
            font-size: 16px;
            color: #333;
        }
        
        .buy-button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 4px;
            cursor: pointer;
            font-size: 14px;
        }
        
        .buy-button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h1>Demo Store</h1>
    
   
    <!-- Include the sales popup script -->
    <!-- Replace "your-website-id" with an actual website ID -->
    <script 
    src="http://github.com/dobariyanimisha/popup-script/main/popup.js"
    data-website-id="686b50497ef71ce228e90d30"
    async
    defer
  ></script>
</html> 
