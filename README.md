<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Moja GitHub Page</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
* {
margin: 0;
padding: 0;
box-sizing: border-box;
}


body {
font-family: 'Inter', sans-serif;
background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
color: #eaeaea;
min-height: 100vh;
display: flex;
align-items: center;
justify-content: center;
}


.container {
max-width: 900px;
width: 90%;
background: rgba(255, 255, 255, 0.05);
backdrop-filter: blur(12px);
border-radius: 24px;
padding: 3rem;
box-shadow: 0 20px 50px rgba(0, 0, 0, 0.4);
}


header {
display: flex;
flex-direction: column;
gap: 1rem;
margin-bottom: 3rem;
}


header h1 {
font-size: 3rem;
font-weight: 700;
letter-spacing: -1px;
}


header p {
font-size: 1.2rem;
color: #b8c6db;
max-width: 600px;
}


section {
margin-bottom: 2.5rem;
}


section h2 {
font-size: 1.8rem;
margin-bottom: 1rem;
font-weight: 600;
}


.cards {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
gap: 1.5rem;
}


.card {
background: rgba(255, 255, 255, 0.08);
border-radius: 18px;
padding: 1.5rem;
transition: transform 0.3s ease, box-shadow 0.3s ease;
}
