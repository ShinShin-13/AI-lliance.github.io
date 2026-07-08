# Ai-lliance.github.io
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SLA Mission Control</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Segoe UI, Arial, sans-serif;
}

body{
    background:#eef4f8;
    color:#333;
}

/* Hero */
.hero{
    height:420px;
    background:url("https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=1600&q=80") center/cover;
    position:relative;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
}

.hero::before{
    content:"";
    position:absolute;
    inset:0;
    background:rgba(0,0,0,.55);
}

.hero-content{
    position:relative;
    z-index:1;
}

.hero h1{
    font-size:48px;
}

.hero p{
    margin-top:15px;
    font-size:20px;
}

/* Dashboard */

.container{
    width:90%;
    margin:auto;
    margin-top:-60px;
    position:relative;
    z-index:2;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.card{
    background:white;
    border-radius:15px;
    padding:25px;
    text-align:center;
    box-shadow:0 10px 25px rgba(0,0,0,.1);
    transition:.3s;
}

.card:hover{
    transform:translateY(-6px);
}

.card h2{
    font-size:40px;
    margin-bottom:10px;
}

.green{
    color:#28a745;
}

.orange{
    color:#ff9800;
}

.red{
    color:#dc3545;
}

/* Sections */

.section{
    margin-top:40px;
    background:white;
    border-radius:15px;
    padding:25px;
    box-shadow:0 10px 25px rgba(0,0,0,.08);
}

.section h2{
    margin-bottom:20px;
    color:#0066cc;
}

.performance{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
    gap:20px;
}

.box{
    background:#f7f9fb;
    border-radius:12px;
    padding:20px;
    text-align:center;
}

.box h3{
    color:#0066cc;
}

.hero-team{
    display:flex;
    gap:20px;
    flex-wrap:wrap;
}

.member{
    flex:1;
    min-width:220px;
    text-align:center;
}

.member img{
    width:100%;
    border-radius:15px;
}

.member h3{
    margin-top:10px;
}

.network{
    width:100%;
    border-radius:15px;
    margin-top:20px;
}

.attention ul{
    margin-left:20px;
    line-height:2;
}

footer{
    margin-top:40px;
    padding:20px;
    background:#003366;
    color:white;
    text-align:center;
}
</style>

</head>

<body>

<div class="hero">
    <div class="hero-content">
        <h1>🚀 SLA Mission Control</h1>
        <p>Keeping Every Customer Connected</p>
    </div>
</div>

<div class="container">

<div class="cards">

<div class="card">
<h2 class="green">96%</h2>
<p>Within SLA</p>
</div>

<div class="card">
<h2 class="orange">14</h2>
<p>Due Soon</p>
</div>

<div class="card">
<h2 class="red">2</h2>
<p>Breached</p>
</div>

</div>

<div class="section">

<h2>📊 Today's Performance</h2>

<div class="performance">

<div class="box">
<h3>🔥 Tickets</h3>
<h1>268</h1>
</div>

<div class="box">
<h3>⚡ Avg Response</h3>
<h1>12 mins</h1>
</div>

<div class="box">
<h3>😊 CSAT</h3>
<h1>94%</h1>
</div>

<div class="box">
<h3>⭐ FCR</h3>
<h1>91%</h1>
</div>

</div>

</div>

<div class="section">

<h2>👨‍💻 Today's Heroes</h2>

<div class="hero-team">

<div class="member">
<img src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?auto=format&fit=crop&w=500&q=80">
<h3>Alex</h3>
<p>36 Tickets Resolved</p>
</div>

<div class="member">
<img src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?auto=format&fit=crop&w=500&q=80">
<h3>Sarah</h3>
<p>100% SLA</p>
</div>

<div class="member">
<img src="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?auto=format&fit=crop&w=500&q=80">
<h3>Mike</h3>
<p>Fastest Resolution</p>
</div>

</div>

</div>

<div class="section">

<h2>📡 Network Status</h2>

<img class="network"
src="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=80">

<h3 style="margin-top:20px;">Overall Network Health</h3>

<progress value="96" max="100" style="width:100%;height:25px;"></progress>

<p style="margin-top:10px;">96% Healthy</p>

</div>

<div class="section attention">

<h2>⚠️ Attention Board</h2>

<ul>
<li>🔴 2 Critical Cases</li>
<li>🟡 5 Waiting for NLT</li>
<li>🟠 3 Pending Customer Reply</li>
<li>🟢 18 Ready to Close</li>
</ul>

</div>

</div>

<footer>

<h3>Made with ❤️ by Support Team</h3>

</footer>

</body><elevenlabs-convai agent-id="agent_5101kwbqaggxfnwbkyqbj9z5wy1f"></elevenlabs-convai><script src="https://unpkg.com/@elevenlabs/convai-widget-embed" async type="text/javascript"></script>
</html>
