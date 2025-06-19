@import url('https://fonts.googleapis.com/css2?family=Source+Code+Pro&display=swap');

body {
  background: #000;
  color: #0f0;
  font-family: 'Source Code Pro', monospace;
  margin: 0; padding: 0;
  display: flex;
  flex-direction: column;
  height: 100vh;
  overflow: hidden;
}

#timer {
  background: #060;
  color: #0f0;
  text-align: center;
  font-weight: bold;
  padding: 5px 0;
  user-select: none;
}

#terminal {
  flex-grow: 1;
  padding: 10px;
  overflow-y: auto;
  white-space: pre-wrap;
  outline: none;
  position: relative;
  filter: none;
  transition: filter 0.3s ease;
}

.glitch {
  animation: glitch-flicker 0.15s infinite;
}

@keyframes glitch-flicker {
  0%, 100% { opacity: 1; text-shadow: none; }
  50% { opacity: 0.6; text-shadow: 1px 0 #0f0, -1px 0 #0f0; }
}

#inputLine {
  display: flex;
  border-top: 1px solid #0f0;
}

#prompt {
  padding: 5px 10px;
  user-select: none;
}

#cmdInput {
  background: black;
  border: none;
  outline: none;
  color: #0f0;
  flex-grow: 1;
  font-family: 'Source Code Pro', monospace;
  font-size: 1em;
  padding: 5px 10px;
}

button {
  background: #060;
  border: 1px solid #0f0;
  color: #0f0;
  padding: 10px 20px;
  cursor: pointer;
  font-family: 'Source Code Pro', monospace;
  font-size: 1em;
  margin-top: 20px;
}

button:hover {
  background: #090;
}

/* Final message wave effect */
.wave {
  display: inline-block;
  animation: waveMotion 2s infinite;
  font-weight: bold;
}

.wave:nth-child(odd) {
  animation-delay: 0s;
}

.wave:nth-child(even) {
  animation-delay: 1s;
}

@keyframes waveMotion {
  0%, 100% { transform: translateY(0); color: #0f0; }
  50% { transform: translateY(-4px); color: #7fff7f; }
}
