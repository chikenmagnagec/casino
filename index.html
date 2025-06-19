<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Neon Casino IP Tracker</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Orbitron', 'Arial', sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0c0e1d, #161a33);
            color: #fff;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
            position: relative;
        }
        
        body::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle at 20% 30%, rgba(106, 27, 154, 0.2) 0%, transparent 40%),
                        radial-gradient(circle at 80% 70%, rgba(33, 150, 243, 0.2) 0%, transparent 40%);
            z-index: 1;
        }
        
        .container {
            position: relative;
            width: 95%;
            max-width: 1200px;
            background: rgba(15, 20, 40, 0.85);
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.5);
            border: 1px solid rgba(100, 100, 255, 0.2);
            overflow: hidden;
            z-index: 2;
            backdrop-filter: blur(10px);
        }
        
        .header {
            text-align: center;
            padding: 30px;
            background: rgba(0, 0, 0, 0.4);
            border-bottom: 2px solid #6a1b9a;
        }
        
        h1 {
            font-size: 3.5rem;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #ff4081, #7c4dff, #00bcd4);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 20px rgba(124, 77, 255, 0.5);
            letter-spacing: 2px;
            animation: titleGlow 3s infinite alternate;
        }
        
        @keyframes titleGlow {
            0% { text-shadow: 0 0 10px rgba(124, 77, 255, 0.5); }
            100% { text-shadow: 0 0 30px rgba(124, 77, 255, 0.8), 0 0 60px rgba(0, 188, 212, 0.6); }
        }
        
        .subtitle {
            font-size: 1.2rem;
            color: #bb86fc;
            margin-bottom: 20px;
        }
        
        .content {
            display: flex;
            padding: 30px;
            gap: 30px;
        }
        
        .ip-display {
            flex: 1;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 15px;
            padding: 30px;
            border: 1px solid rgba(124, 77, 255, 0.3);
            box-shadow: 0 0 20px rgba(124, 77, 255, 0.2);
            position: relative;
            overflow: hidden;
        }
        
        .ip-display::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(45deg, transparent, rgba(124, 77, 255, 0.1), transparent);
            transform: rotate(45deg);
            animation: scan 8s infinite linear;
        }
        
        @keyframes scan {
            0% { transform: rotate(45deg) translate(-50%, -50%); }
            100% { transform: rotate(45deg) translate(50%, 50%); }
        }
        
        .ip-display h2 {
            color: #bb86fc;
            font-size: 1.8rem;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .ip-address {
            font-size: 2.5rem;
            font-weight: bold;
            background: linear-gradient(90deg, #00bcd4, #7c4dff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin: 20px 0;
            text-align: center;
            letter-spacing: 2px;
            text-shadow: 0 0 10px rgba(124, 77, 255, 0.5);
            animation: pulse 2s infinite alternate;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            100% { transform: scale(1.05); }
        }
        
        .location-info {
            background: rgba(0, 0, 0, 0.2);
            border-radius: 10px;
            padding: 20px;
            margin-top: 30px;
        }
        
        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .info-card {
            background: rgba(30, 30, 60, 0.5);
            border-radius: 10px;
            padding: 15px;
            border-left: 3px solid #7c4dff;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .info-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(124, 77, 255, 0.4);
        }
        
        .info-card h3 {
            color: #bb86fc;
            margin-bottom: 10px;
            font-size: 1.1rem;
        }
        
        .info-card p {
            font-size: 1.3rem;
            font-weight: bold;
        }
        
        .casino-section {
            flex: 1;
            display: flex;
            flex-direction: column;
            gap: 30px;
        }
        
        .slot-machine {
            background: linear-gradient(to bottom, #8b0000, #6b0000);
            border: 5px solid #d4af37;
            border-radius: 15px;
            padding: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.7);
            position: relative;
            overflow: hidden;
        }
        
        .slot-machine::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, 
                transparent 48%, rgba(255, 215, 0, 0.1) 50%, 
                transparent 52%);
            background-size: 300% 300%;
            animation: shine 3s infinite linear;
        }
        
        @keyframes shine {
            0% { background-position: 100% 100%; }
            100% { background-position: 0% 0%; }
        }
        
        .reels-container {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin: 20px 0;
        }
        
        .reel {
            width: 100px;
            height: 150px;
            background: #0d1b2a;
            border: 3px solid #d4af37;
            border-radius: 8px;
            overflow: hidden;
            position: relative;
            box-shadow: inset 0 0 20px rgba(0, 0, 0, 0.8);
        }
        
        .reel-inner {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            transition: transform 0.1s;
        }
        
        .reel-item {
            height: 150px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 50px;
            color: white;
            text-shadow: 0 0 10px rgba(255, 255, 255, 0.7);
        }
        
        .controls {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        
        .spin-btn {
            background: linear-gradient(to bottom, #00cc00, #009900);
            border: none;
            border-radius: 50px;
            padding: 15px 40px;
            color: white;
            font-size: 1.2rem;
            font-weight: bold;
            cursor: pointer;
            display: flex;
            align-items: center;
            gap: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
            transition: all 0.3s;
            position: relative;
            overflow: hidden;
        }
        
        .spin-btn::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(rgba(255, 255, 255, 0.1), transparent);
            transform: rotate(45deg);
        }
        
        .spin-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(0, 255, 0, 0.6);
        }
        
        .spin-btn:active {
            transform: translateY(1px);
        }
        
        .particles {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            pointer-events: none;
            z-index: 3;
        }
        
        .particle {
            position: absolute;
            width: 4px;
            height: 4px;
            background: #7c4dff;
            border-radius: 50%;
            box-shadow: 0 0 10px #7c4dff, 0 0 20px #7c4dff;
            animation: float 6s infinite linear;
        }
        
        @keyframes float {
            0% { transform: translateY(100vh) translateX(0); opacity: 0; }
            10% { opacity: 1; }
            90% { opacity: 1; }
            100% { transform: translateY(-100px) translateX(100px); opacity: 0; }
        }
        
        .win-message {
            height: 60px;
            margin: 15px 0;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 1.5rem;
            font-weight: bold;
            color: #ffd700;
            text-shadow: 0 0 10px rgba(255, 215, 0, 0.7);
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        
        .win-animation {
            animation: winPulse 0.5s infinite alternate;
        }
        
        @keyframes winPulse {
            from { transform: scale(1); text-shadow: 0 0 10px rgba(255, 215, 0, 0.7); }
            to { transform: scale(1.1); text-shadow: 0 0 30px rgba(255, 215, 0, 1); }
        }
        
        .connection-details {
            background: rgba(0, 0, 0, 0.3);
            border-radius: 15px;
            padding: 20px;
            border: 1px solid rgba(0, 188, 212, 0.3);
            box-shadow: 0 0 20px rgba(0, 188, 212, 0.2);
        }
        
        .connection-details h2 {
            color: #00bcd4;
            font-size: 1.8rem;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .details-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
        }
        
        .detail-item {
            background: rgba(0, 40, 60, 0.4);
            padding: 15px;
            border-radius: 10px;
            border-left: 3px solid #00bcd4;
        }
        
        .detail-item h3 {
            color: #00bcd4;
            margin-bottom: 5px;
            font-size: 1rem;
        }
        
        .detail-item p {
            font-size: 1.2rem;
            font-weight: bold;
        }
        
        .footer {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.4);
            border-top: 1px solid rgba(100, 100, 255, 0.2);
            font-size: 0.9rem;
            color: #bb86fc;
        }
        
        @media (max-width: 900px) {
            .content {
                flex-direction: column;
            }
            
            h1 {
                font-size: 2.5rem;
            }
            
            .ip-address {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1><i class="fas fa-dice"></i> NEON CASINO IP TRACKER <i class="fas fa-network-wired"></i></h1>
            <p class="subtitle">Roll the dice to reveal your connection information in style</p>
        </div>
        
        <div class="content">
            <div class="ip-display">
                <h2><i class="fas fa-location-dot"></i> YOUR IP ADDRESS</h2>
                <div class="ip-address" id="ipDisplay">192.168.1.1</div>
                
                <div class="location-info">
                    <h2><i class="fas fa-map"></i> LOCATION INFORMATION</h2>
                    <div class="info-grid">
                        <div class="info-card">
                            <h3>COUNTRY</h3>
                            <p id="country">United States</p>
                        </div>
                        <div class="info-card">
                            <h3>REGION</h3>
                            <p id="region">California</p>
                        </div>
                        <div class="info-card">
                            <h3>CITY</h3>
                            <p id="city">Los Angeles</p>
                        </div>
                        <div class="info-card">
                            <h3>POSTAL CODE</h3>
                            <p id="postal">90001</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="casino-section">
                <div class="slot-machine">
                    <div class="win-message" id="winMessage">Roll to reveal your connection!</div>
                    
                    <div class="reels-container">
                        <div class="reel">
                            <div class="reel-inner" id="reel1">
                                <div class="reel-item">🌐</div>
                                <div class="reel-item">📡</div>
                                <div class="reel-item">🔒</div>
                                <div class="reel-item">💻</div>
                                <div class="reel-item">📱</div>
                            </div>
                        </div>
                        
                        <div class="reel">
                            <div class="reel-inner" id="reel2">
                                <div class="reel-item">🌍</div>
                                <div class="reel-item">📍</div>
                                <div class="reel-item">🗺️</div>
                                <div class="reel-item">🏙️</div>
                                <div class="reel-item">🏢</div>
                            </div>
                        </div>
                        
                        <div class="reel">
                            <div class="reel-inner" id="reel3">
                                <div class="reel-item">⚡</div>
                                <div class="reel-item">🔌</div>
                                <div class="reel-item">📶</div>
                                <div class="reel-item">🛡️</div>
                                <div class="reel-item">🔑</div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="controls">
                        <button class="spin-btn" id="spinBtn">
                            <i class="fas fa-dice"></i> ROLL FOR DETAILS
                        </button>
                    </div>
                </div>
                
                <div class="connection-details">
                    <h2><i class="fas fa-wifi"></i> CONNECTION DETAILS</h2>
                    <div class="details-grid">
                        <div class="detail-item">
                            <h3>ISP PROVIDER</h3>
                            <p id="isp">Comcast Cable</p>
                        </div>
                        <div class="detail-item">
                            <h3>CONNECTION TYPE</h3>
                            <p id="connection">Cable</p>
                        </div>
                        <div class="detail-item">
                            <h3>BROWSER</h3>
                            <p id="browser">Chrome 115</p>
                        </div>
                        <div class="detail-item">
                            <h3>PLATFORM</h3>
                            <p id="platform">Windows 10</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="footer">
            <p>This tool displays your public IP and connection information for educational purposes only | No data is stored or shared</p>
        </div>
    </div>
    
    <div class="particles" id="particles"></div>
    
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Create floating particles
            const particlesContainer = document.getElementById('particles');
            for (let i = 0; i < 50; i++) {
                const particle = document.createElement('div');
                particle.classList.add('particle');
                particle.style.left = `${Math.random() * 100}%`;
                particle.style.top = `${Math.random() * 100}%`;
                particle.style.animationDuration = `${Math.random() * 5 + 3}s`;
                particle.style.animationDelay = `${Math.random() * 5}s`;
                particle.style.opacity = Math.random() * 0.7 + 0.3;
                particle.style.width = `${Math.random() * 4 + 2}px`;
                particle.style.height = particle.style.width;
                particlesContainer.appendChild(particle);
            }
            
            // Initialize with sample data
            updateDisplay({
                ip: "192.168.1.1",
                country: "United States",
                region: "California",
                city: "Los Angeles",
                postal: "90001",
                isp: "Comcast Cable",
                connection: "Cable",
                browser: "Chrome 115",
                platform: "Windows 10"
            });
            
            // Spin button functionality
            const spinBtn = document.getElementById('spinBtn');
            const winMessage = document.getElementById('winMessage');
            
            spinBtn.addEventListener('click', function() {
                // Show spinning animation
                spinBtn.disabled = true;
                winMessage.textContent = "Rolling...";
                winMessage.classList.remove('win-animation');
                
                // Add reel spinning animation
                document.getElementById('reel1').style.transform = "translateY(-750px)";
                document.getElementById('reel2').style.transform = "translateY(-750px)";
                document.getElementById('reel3').style.transform = "translateY(-750px)";
                
                // Simulate API call to get real IP data
                setTimeout(() => {
                    // For demo, generate random values
                    const cities = ["New York", "Chicago", "Miami", "San Francisco", "Seattle"];
                    const isps = ["Comcast", "Verizon", "AT&T", "Spectrum", "Cox"];
                    const connections = ["Cable", "Fiber", "DSL", "5G", "Satellite"];
                    
                    const data = {
                        ip: `${Math.floor(Math.random() * 255)}.${Math.floor(Math.random() * 255)}.${Math.floor(Math.random() * 255)}.${Math.floor(Math.random() * 255)}`,
                        country: "United States",
                        region: "California",
                        city: cities[Math.floor(Math.random() * cities.length)],
                        postal: "900" + Math.floor(Math.random() * 100).toString().padStart(2, '0'),
                        isp: isps[Math.floor(Math.random() * isps.length)],
                        connection: connections[Math.floor(Math.random() * connections.length)],
                        browser: "Chrome " + (Math.floor(Math.random() * 50) + 100),
                        platform: ["Windows 10", "Windows 11", "macOS", "iOS", "Android"][Math.floor(Math.random() * 5)]
                    };
                    
                    // Update display
                    updateDisplay(data);
                    
                    // Show win message
                    winMessage.textContent = "Connection details revealed!";
                    winMessage.classList.add('win-animation');
                    
                    // Reset button
                    spinBtn.disabled = false;
                }, 2000);
            });
            
            // Function to update display with data
            function updateDisplay(data) {
                document.getElementById('ipDisplay').textContent = data.ip;
                document.getElementById('country').textContent = data.country;
                document.getElementById('region').textContent = data.region;
                document.getElementById('city').textContent = data.city;
                document.getElementById('postal').textContent = data.postal;
                document.getElementById('isp').textContent = data.isp;
                document.getElementById('connection').textContent = data.connection;
                document.getElementById('browser').textContent = data.browser;
                document.getElementById('platform').textContent = data.platform;
            }
        });
    </script>
</body>
</html>
