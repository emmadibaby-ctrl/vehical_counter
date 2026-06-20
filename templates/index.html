<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>AI Vehicle Counter</title>
    <style>
        body { 
            margin: 0; overflow: hidden; 
            background: linear-gradient(to bottom, #bae6fd, #e0f2fe); 
            font-family: 'Inter', sans-serif;
            height: 100vh; display: flex; justify-content: center; align-items: center;
        }

        /* Road Surface */
        .road {
            position: absolute; bottom: 0; width: 100%; height: 160px;
            background: #334155; border-top: 5px solid #475569;
        }
        .line {
            position: absolute; width: 100%; height: 10px;
            border-top: 5px dashed #ffffff; top: 70px;
        }

        /* Large Animated Vehicles */
        @keyframes drive {
            from { left: 110%; }
            to { left: -150px; }
        }
        .vehicle { 
            position: absolute; font-size: 60px; /* Increased size */
            animation: drive linear infinite; z-index: 5;
        }

        .container { 
            position: relative; z-index: 10;
            background: white; padding: 40px; border-radius: 24px; 
            box-shadow: 0 20px 50px rgba(0,0,0,0.15);
            text-align: center; width: 400px;
        }

        #preview { 
            width: 100%; height: 180px; border-radius: 12px; 
            margin-bottom: 20px; object-fit: cover; display: none;
            border: 2px solid #e2e8f0;
        }

        button { 
            background: #2563eb; color: white; border: none; 
            padding: 14px 25px; border-radius: 12px; width: 100%; 
            cursor: pointer; font-weight: 600; font-size: 16px;
        }
        #result { margin-top: 20px; font-weight: 700; color: #1e293b; }
    </style>
</head>
<body>

    <div class="road"><div class="line"></div></div>

    <div class="vehicle" style="bottom: 70px; animation-duration: 9s;">🚗</div>
    <div class="vehicle" style="bottom: 20px; animation-duration: 13s;">🚚</div>
    <div class="vehicle" style="bottom: 80px; animation-duration: 7s;">🏎️</div>
    <div class="vehicle" style="bottom: 30px; animation-duration: 11s;">🚌</div>

    <div class="container">
        <h1>Vehicle Counter</h1>
        <img id="preview" alt="Preview">
        <input type="file" id="imageInput" accept="image/*" onchange="previewImage(event)">
        <button onclick="uploadImage()">Analyze Image</button>
        <div id="result"></div>
    </div>

    <script>
        function previewImage(event) {
            const preview = document.getElementById('preview');
            preview.src = URL.createObjectURL(event.target.files[0]);
            preview.style.display = 'block';
        }

        async function uploadImage() {
            const fileInput = document.getElementById('imageInput');
            if (!fileInput.files[0]) return alert("Select an image!");
            
            document.getElementById('result').innerText = "Analyzing...";
            const formData = new FormData();
            formData.append('file', fileInput.files[0]);

            const response = await fetch('/predict', { method: 'POST', body: formData });
            const data = await response.json();
            document.getElementById('result').innerText = 'Vehicles Detected: ' + data.count;
        }
    </script>
</body>
</html>
