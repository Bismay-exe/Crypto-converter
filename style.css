/* Custom CSS for Glassmorphism and Animations */

/* Keyframe Animations */
@keyframes float {
    0%, 100% {
        transform: translateY(0px) rotate(0deg);
    }
    33% {
        transform: translateY(-20px) rotate(1deg);
    }
    66% {
        transform: translateY(-10px) rotate(-1deg);
    }
}

@keyframes glow {
    0% {
        box-shadow: 0 0 20px rgba(0, 255, 136, 0.3), 0 0 40px rgba(0, 212, 255, 0.2);
    }
    100% {
        box-shadow: 0 0 30px rgba(0, 255, 136, 0.5), 0 0 60px rgba(0, 212, 255, 0.3);
    }
}

@keyframes slideUp {
    0% {
        opacity: 0;
        transform: translateY(50px);
    }
    100% {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes fadeIn {
    0% {
        opacity: 0;
    }
    100% {
        opacity: 1;
    }
}

@keyframes pulse {
    0%, 100% {
        transform: scale(1);
    }
    50% {
        transform: scale(1.05);
    }
}

@keyframes shimmer {
    0% {
        background-position: -200% 0;
    }
    100% {
        background-position: 200% 0;
    }
}

/* Glass Effects */
.glass-card {
    backdrop-filter: blur(16px);
    -webkit-backdrop-filter: blur(16px);
    background: rgba(30, 41, 59, 0.3);
    border: 1px solid rgba(255, 255, 255, 0.1);
    box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
}

.glass-button {
    backdrop-filter: blur(16px);
    -webkit-backdrop-filter: blur(16px);
    position: relative;
    overflow: hidden;
}

.glass-button::before {
    content: '';
    position: absolute;
    top: 0;
    left: -100%;
    width: 100%;
    height: 100%;
    background: linear-gradient(
        90deg,
        transparent,
        rgba(255, 255, 255, 0.1),
        transparent
    );
    transition: left 0.5s;
}

.glass-button:hover::before {
    left: 100%;
}

/* Navigation Enhancements */
.nav-link {
    position: relative;
    padding: 0.5rem 0;
}

.nav-link::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 0;
    height: 2px;
    background: linear-gradient(90deg, #00FF88, #00D4FF);
    transition: width 0.3s ease;
}

.nav-link:hover::after {
    width: 100%;
}

/* Crypto Card Enhancements */
.crypto-card {
    position: relative;
    overflow: hidden;
}

.crypto-card::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: linear-gradient(
        135deg,
        rgba(0, 255, 136, 0.05) 0%,
        rgba(0, 212, 255, 0.05) 100%
    );
    opacity: 0;
    transition: opacity 0.3s ease;
}

.crypto-card:hover::before {
    opacity: 1;
}

.crypto-card:hover {
    transform: translateY(-10px) scale(1.02);
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4);
}

/* Input Field Enhancements */
input[type="number"], select {
    position: relative;
    transition: all 0.3s ease;
}

input[type="number"]:focus, select:focus {
    transform: translateY(-2px);
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
}

/* Result Display Enhancements */
#inr-result, #crypto-result {
    position: relative;
    overflow: hidden;
}

#inr-result::before, #crypto-result::before {
    content: '';
    position: absolute;
    top: 0;
    left: -100%;
    width: 100%;
    height: 100%;
    background: linear-gradient(
        90deg,
        transparent,
        rgba(0, 255, 136, 0.1),
        transparent
    );
    animation: shimmer 2s infinite;
}

/* Social Icon Enhancements */
.social-icon {
    position: relative;
    display: inline-block;
    padding: 0.5rem;
    border-radius: 50%;
    transition: all 0.3s ease;
}

.social-icon::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    border-radius: 50%;
    background: radial-gradient(circle, rgba(0, 255, 136, 0.1), transparent);
    opacity: 0;
    transform: scale(0);
    transition: all 0.3s ease;
}

.social-icon:hover::before {
    opacity: 1;
    transform: scale(1);
}

.social-icon:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
}

/* Hero Section Enhancements */
#home {
    position: relative;
}

#home::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: radial-gradient(
        ellipse at center,
        rgba(0, 255, 136, 0.05) 0%,
        rgba(0, 212, 255, 0.05) 50%,
        transparent 100%
    );
    animation: pulse 4s ease-in-out infinite;
}

/* CTA Button Special Effects */
#cta-button {
    position: relative;
    overflow: hidden;
}

#cta-button::after {
    content: '';
    position: absolute;
    top: 50%;
    left: 50%;
    width: 0;
    height: 0;
    border-radius: 50%;
    background: rgba(255, 255, 255, 0.1);
    transform: translate(-50%, -50%);
    transition: width 0.6s, height 0.6s;
}

#cta-button:active::after {
    width: 300px;
    height: 300px;
}

/* Scrollbar Styling */
::-webkit-scrollbar {
    width: 8px;
}

::-webkit-scrollbar-track {
    background: #0F172A;
}

::-webkit-scrollbar-thumb {
    background: linear-gradient(180deg, #00FF88, #00D4FF);
    border-radius: 4px;
}

::-webkit-scrollbar-thumb:hover {
    background: linear-gradient(180deg, #00D4FF, #00FF88);
}

/* Mobile Responsiveness */
@media (max-width: 768px) {
    .crypto-card:hover {
        transform: translateY(-5px) scale(1.01);
    }
    
    #home h1 {
        font-size: 2.5rem;
    }
    
    .glass-card {
        margin: 1rem 0;
    }
}

/* Loading Animation for Calculator Results */
.calculating {
    position: relative;
}

.calculating::after {
    content: '';
    position: absolute;
    top: 50%;
    right: 1rem;
    width: 20px;
    height: 20px;
    border: 2px solid rgba(0, 255, 136, 0.3);
    border-top: 2px solid #00FF88;
    border-radius: 50%;
    animation: spin 1s linear infinite;
    transform: translateY(-50%);
}

@keyframes spin {
    0% { transform: translateY(-50%) rotate(0deg); }
    100% { transform: translateY(-50%) rotate(360deg); }
}

/* Gradient Text Animation */
.gradient-text {
    background: linear-gradient(
        45deg,
        #00FF88,
        #00D4FF,
        #00FF88,
        #00D4FF
    );
    background-size: 400% 400%;
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: gradientShift 3s ease infinite;
}

@keyframes gradientShift {
    0%, 100% {
        background-position: 0% 50%;
    }
    50% {
        background-position: 100% 50%;
    }
}

/* Particle Effect for Background */
.particle {
    position: absolute;
    width: 4px;
    height: 4px;
    background: rgba(0, 255, 136, 0.6);
    border-radius: 50%;
    animation: float 6s ease-in-out infinite;
}

.particle:nth-child(2) {
    background: rgba(0, 212, 255, 0.6);
    animation-delay: -2s;
    animation-duration: 8s;
}

.particle:nth-child(3) {
    background: rgba(255, 255, 255, 0.3);
    animation-delay: -4s;
    animation-duration: 10s;
}

/* Enhanced Focus States */
input:focus, select:focus, button:focus {
    outline: none;
    box-shadow: 0 0 0 3px rgba(0, 255, 136, 0.3);
}

/* Smooth Transitions for All Interactive Elements */
* {
    transition: all 0.3s ease;
}

/* High Performance Animations */
.animate-float,
.animate-glow,
.animate-slide-up,
.animate-fade-in {
    will-change: transform, opacity;
}

/* Dark Mode Enhancements */
body {
    background-attachment: fixed;
    background-image: 
        radial-gradient(circle at 20% 80%, rgba(0, 255, 136, 0.05) 0%, transparent 50%),
        radial-gradient(circle at 80% 20%, rgba(0, 212, 255, 0.05) 0%, transparent 50%);
}

/* Print Styles */
@media print {
    .glass-card, .glass-button {
        background: white !important;
        color: black !important;
        border: 1px solid #ccc !important;
    }
    
    .animate-float, .animate-glow {
        animation: none !important;
    }
}
