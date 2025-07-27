# 🌌 Quantum Adaptive Music Creator

An experimental web application that generates adaptive music using quantum-inspired algorithms and real-time audio synthesis. This project combines quantum computing concepts with music theory to create unique, mood-based compositions that evolve through quantum superposition, entanglement, and wave function collapse.

## ✨ Features

### 🎵 Quantum Music Generation
- **Mood-Based Composition**: Six distinct moods (Happy, Sad, Energetic, Relaxed, Romantic, Mysterious)
- **Real-time Audio Synthesis**: Multiple synthesizer layers (lead, bass, pad, percussion)
- **Adaptive Parameters**: Dynamic tempo, volume, and quantum parameter control

### ⚛️ Quantum-Inspired Elements
- **Qubit System**: Four qubits representing melody, harmony, rhythm, and timbre
- **Quantum Entanglement**: Correlated musical parameters between entangled qubits
- **Superposition States**: Multiple simultaneous musical possibilities until collapse
- **Wave Function Collapse**: Definitive state selection from quantum probabilities
- **Quantum Random Generation**: Enhanced randomness using quantum-inspired algorithms

### 🎛️ Interactive Controls
- **Classical Parameters**: Tempo (60-180 BPM), Volume (0-100%)
- **Quantum Parameters**: Coherence (0-100%), Entanglement Degree (0-100%)
- **Quantum Effects**: Superposition Mix (0-100%), Quantum Uncertainty (0-100%)
- **Real-time Visualization**: Animated quantum states and entanglement patterns

## 🚀 Getting Started

### Prerequisites
- Modern web browser with Web Audio API support
- No additional installations required

### Installation
1. Clone or download the project files
2. Open `index.html` in a web browser
3. The application will automatically initialize the quantum audio system

### Usage
1. **Select a Mood**: Choose from six available moods to set the base musical parameters
2. **Adjust Parameters**: Fine-tune classical and quantum parameters using the sliders
3. **Generate Music**: Click "Play" to start the quantum music generation
4. **Experiment**: Use "Quantum Regenerate" to create variations or "Collapse Wave Function" for definitive states

## 🎼 Technical Architecture

### Audio Engine
- **Library**: Tone.js v14.7.77 for Web Audio synthesis
- **Synthesizers**: 
  - Lead synth with quantum-influenced oscillator types
  - Bass synth with quantum timing variations
  - Pad synth for harmonic content
  - Noise synth for percussion elements
- **Effects**: Quantum-enhanced reverb with randomized parameters

### Quantum System
```javascript
// Quantum state representation
quantumState = {
    qubits: [
        { id: 'melody', state: [amplitude, phase], entangled: boolean },
        { id: 'harmony', state: [amplitude, phase], entangled: boolean },
        { id: 'rhythm', state: [amplitude, phase], entangled: boolean },
        { id: 'timbre', state: [amplitude, phase], entangled: boolean }
    ],
    entangledPairs: [[0,1], [2,3]], // melody-harmony, rhythm-timbre
    superpositionStates: Map // Historical superposition choices
}
```

### Music Generation Algorithm
1. **Quantum State Preparation**: Initialize qubits based on selected mood
2. **Entanglement Creation**: Establish correlations between musical dimensions
3. **Superposition Application**: Generate multiple simultaneous musical possibilities
4. **Probability Calculation**: Use quantum amplitudes to weight musical choices
5. **Wave Function Collapse**: Select definitive notes/rhythms based on quantum probabilities

## 🎯 Mood Configurations

| Mood | Key | Tempo | Quantum Bias | Complexity |
|------|-----|-------|--------------|------------|
| Happy | C Major | 140 BPM | 0.8 | 0.6 |
| Sad | A Minor | 80 BPM | 0.3 | 0.4 |
| Energetic | E Major | 160 BPM | 0.9 | 0.9 |
| Relaxed | G Major | 90 BPM | 0.5 | 0.3 |
| Romantic | F Major | 100 BPM | 0.7 | 0.5 |
| Mysterious | D Minor | 110 BPM | 0.2 | 0.8 |

## 🔬 Quantum Algorithms

### Quantum Random Number Generation
```javascript
quantumRandom(min, max) {
    const coherence = getCoherence();
    const uncertainty = getUncertainty();
    
    let qValue = 0;
    for (let i = 0; i < 8; i++) {
        qValue += Math.random() * coherence + 
                 (1 - coherence) * Math.random() * uncertainty;
    }
    return min + (qValue / 8) % 1 * (max - min);
}
```

### Quantum Superposition
Creates weighted combinations of musical elements where multiple states exist simultaneously until measurement (playback).

### Quantum Entanglement
Correlates musical parameters so that changing one immediately affects its entangled partner, creating musically coherent relationships.

## 🎨 Visual Elements

### Quantum Visualization
- **Qubit Display**: Real-time quantum state visualization with spinning orbs
- **Entanglement Lines**: Animated connections showing quantum correlations
- **Quantum Wave**: Dynamic background representing the overall quantum field
- **Color Morphing**: Gradient animations reflecting quantum coherence levels

### UI/UX Features
- **Glassmorphism Design**: Modern translucent interface elements
- **Quantum Field Animation**: Background quantum interference patterns
- **Responsive Layout**: Adaptive grid system for different screen sizes
- **Real-time Feedback**: Live parameter updates and status indicators

## 🛠️ Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 66+ | ✅ Full Support |
| Firefox | 60+ | ✅ Full Support |
| Safari | 14+ | ✅ Full Support |
| Edge | 79+ | ✅ Full Support |

**Requirements:**
- Web Audio API support
- ES6+ JavaScript features
- CSS Grid and Flexbox support

## 🔧 Development

### File Structure
```
quantum-music-creator/
├── index.html          # Main application file
└── README.md          # This file
```

### Customization
- **Add New Moods**: Extend the `moodParameters` object
- **Modify Quantum Parameters**: Adjust qubit initialization and entanglement patterns
- **Custom Visualizations**: Enhance the quantum visualization system
- **Audio Effects**: Add more Tone.js effects and processing

### Performance Optimization
- Quantum calculations are optimized for real-time performance
- Audio synthesis uses efficient Tone.js scheduling
- Visual animations use CSS transforms and GPU acceleration

## 🎪 Known Limitations

- **Quantum Simulation**: This is a quantum-inspired system, not true quantum computing
- **Audio Latency**: Some browsers may introduce audio delay
- **Memory Usage**: Extended sessions may accumulate quantum state history
- **Mobile Performance**: Complex visualizations may impact mobile performance

## 🙏 Acknowledgments

- **Tone.js**: Incredible Web Audio framework by Yotam Mann
- **Quantum Computing Concepts**: Inspired by quantum mechanics principles
- **Music Theory**: Classical harmony and composition techniques
- **Web Audio API**: Browser-native audio synthesis capabilities
---

**"Where quantum mechanics meets musical creativity"** 🎵⚛️

*Experience the uncertainty principle in music - where every note exists in superposition until you hear it.*
