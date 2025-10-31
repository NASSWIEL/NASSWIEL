
<p align="center">
  <!-- Container: adjust width as you wish -->
  <svg width="1000" height="360" viewBox="0 0 1000 360" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="ML library logos in 3D cards">
    <defs>
      <filter id="dropShadow" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur in="SourceAlpha" stdDeviation="8" result="blur"/>
        <feOffset in="blur" dx="0" dy="10" result="offset"/>
        <feComponentTransfer>
          <feFuncA type="linear" slope="0.25"/>
        </feComponentTransfer>
        <feMerge>
          <feMergeNode in="offset"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>

      <linearGradient id="fade" x1="0" x2="0" y1="0" y2="1">
        <stop offset="0%" stop-color="white" stop-opacity="0.28"/>
        <stop offset="100%" stop-color="white" stop-opacity="0.0"/>
      </linearGradient>

      <linearGradient id="cardGrad" x1="0" x2="1" y1="0" y2="1">
        <stop offset="0" stop-color="#ffffff"/>
        <stop offset="1" stop-color="#f3f6fb"/>
      </linearGradient>

      <linearGradient id="rim" x1="0" x2="1" y1="0" y2="1">
        <stop offset="0%" stop-color="#e6eefc"/>
        <stop offset="100%" stop-color="#dfeaf9"/>
      </linearGradient>

      <clipPath id="logoClip">
        <rect x="0" y="0" width="120" height="120" rx="14" ry="14"/>
      </clipPath>
    </defs>

    <!-- Card 1: TensorFlow -->
    <g transform="translate(40,30)">
      <g filter="url(#dropShadow)">
        <rect x="0" y="0" width="180" height="240" rx="18" ry="18" fill="url(#cardGrad)"/>
        <rect x="1.5" y="1.5" width="177" height="237" rx="16.5" ry="16.5" fill="none" stroke="url(#rim)" stroke-width="2"/>
      </g>

      <g transform="translate(90,95) rotate(-12) translate(-60,-60)">
        <g transform="translate(10,20)">
          <rect x="0" y="0" width="120" height="120" rx="14" ry="14" fill="#ffffff"/>
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/a/ab/TensorFlow_logo.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
          </g>
        </g>

        <g transform="translate(10,150) scale(1,-1)" opacity="0.28">
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/a/ab/TensorFlow_logo.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
            <rect x="0" y="0" width="120" height="120" fill="url(#fade)"/>
          </g>
        </g>
      </g>
    </g>

    <!-- Card 2: PyTorch -->
    <g transform="translate(260,30)">
      <g filter="url(#dropShadow)">
        <rect x="0" y="0" width="180" height="240" rx="18" ry="18" fill="url(#cardGrad)"/>
        <rect x="1.5" y="1.5" width="177" height="237" rx="16.5" ry="16.5" fill="none" stroke="url(#rim)" stroke-width="2"/>
      </g>

      <g transform="translate(90,95) rotate(-8) translate(-60,-60)">
        <g transform="translate(10,20)">
          <rect x="0" y="0" width="120" height="120" rx="14" ry="14" fill="#ffffff"/>
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/1/10/PyTorch_logo_icon.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
          </g>
        </g>

        <g transform="translate(10,150) scale(1,-1)" opacity="0.26">
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/1/10/PyTorch_logo_icon.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
            <rect x="0" y="0" width="120" height="120" fill="url(#fade)"/>
          </g>
        </g>
      </g>
    </g>

    <!-- Card 3: scikit-learn -->
    <g transform="translate(480,30)">
      <g filter="url(#dropShadow)">
        <rect x="0" y="0" width="180" height="240" rx="18" ry="18" fill="url(#cardGrad)"/>
        <rect x="1.5" y="1.5" width="177" height="237" rx="16.5" ry="16.5" fill="none" stroke="url(#rim)" stroke-width="2"/>
      </g>

      <g transform="translate(90,95) rotate(-10) translate(-60,-60)">
        <g transform="translate(10,20)">
          <rect x="0" y="0" width="120" height="120" rx="14" ry="14" fill="#ffffff"/>
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
          </g>
        </g>

        <g transform="translate(10,150) scale(1,-1)" opacity="0.2">
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
            <rect x="0" y="0" width="120" height="120" fill="url(#fade)"/>
          </g>
        </g>
      </g>
    </g>

    <!-- Card 4: Keras -->
    <g transform="translate(700,30)">
      <g filter="url(#dropShadow)">
        <rect x="0" y="0" width="180" height="240" rx="18" ry="18" fill="url(#cardGrad)"/>
        <rect x="1.5" y="1.5" width="177" height="237" rx="16.5" ry="16.5" fill="none" stroke="url(#rim)" stroke-width="2"/>
      </g>

      <g transform="translate(90,95) rotate(-6) translate(-60,-60)">
        <g transform="translate(10,20)">
          <rect x="0" y="0" width="120" height="120" rx="14" ry="14" fill="#ffffff"/>
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/a/ae/Keras_logo.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
          </g>
        </g>

        <g transform="translate(10,150) scale(1,-1)" opacity="0.22">
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/a/ae/Keras_logo.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
            <rect x="0" y="0" width="120" height="120" fill="url(#fade)"/>
          </g>
        </g>
      </g>
    </g>

    <!-- Second row, Card 5: JAX -->
    <g transform="translate(40,205)">
      <g filter="url(#dropShadow)">
        <rect x="0" y="0" width="180" height="240" rx="18" ry="18" fill="url(#cardGrad)"/>
        <rect x="1.5" y="1.5" width="177" height="237" rx="16.5" ry="16.5" fill="none" stroke="url(#rim)" stroke-width="2"/>
      </g>

      <g transform="translate(90,95) rotate(-11) translate(-60,-60)">
        <g transform="translate(10,20)">
          <rect x="0" y="0" width="120" height="120" rx="14" ry="14" fill="#ffffff"/>
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/9/9a/Jax_logo.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
          </g>
        </g>

        <g transform="translate(10,150) scale(1,-1)" opacity="0.18">
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/9/9a/Jax_logo.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
            <rect x="0" y="0" width="120" height="120" fill="url(#fade)"/>
          </g>
        </g>
      </g>
    </g>

    <!-- Card 6: Hugging Face -->
    <g transform="translate(260,205)">
      <g filter="url(#dropShadow)">
        <rect x="0" y="0" width="180" height="240" rx="18" ry="18" fill="url(#cardGrad)"/>
        <rect x="1.5" y="1.5" width="177" height="237" rx="16.5" ry="16.5" fill="none" stroke="url(#rim)" stroke-width="2"/>
      </g>

      <g transform="translate(90,95) rotate(-7) translate(-60,-60)">
        <g transform="translate(10,20)">
          <rect x="0" y="0" width="120" height="120" rx="14" ry="14" fill="#ffffff"/>
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/d/d6/Hf-logo-with-title.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
          </g>
        </g>

        <g transform="translate(10,150) scale(1,-1)" opacity="0.20">
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/d/d6/Hf-logo-with-title.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
            <rect x="0" y="0" width="120" height="120" fill="url(#fade)"/>
          </g>
        </g>
      </g>
    </g>

    <!-- Card 7: ONNX -->
    <g transform="translate(480,205)">
      <g filter="url(#dropShadow)">
        <rect x="0" y="0" width="180" height="240" rx="18" ry="18" fill="url(#cardGrad)"/>
        <rect x="1.5" y="1.5" width="177" height="237" rx="16.5" ry="16.5" fill="none" stroke="url(#rim)" stroke-width="2"/>
      </g>

      <g transform="translate(90,95) rotate(-9) translate(-60,-60)">
        <g transform="translate(10,20)">
          <rect x="0" y="0" width="120" height="120" rx="14" ry="14" fill="#ffffff"/>
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/1/17/Open_Neural_Network_Exchange_logo.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
          </g>
        </g>

        <g transform="translate(10,150) scale(1,-1)" opacity="0.17">
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/1/17/Open_Neural_Network_Exchange_logo.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
            <rect x="0" y="0" width="120" height="120" fill="url(#fade)"/>
          </g>
        </g>
      </g>
    </g>

    <!-- Card 8: XGBoost -->
    <g transform="translate(700,205)">
      <g filter="url(#dropShadow)">
        <rect x="0" y="0" width="180" height="240" rx="18" ry="18" fill="url(#cardGrad)"/>
        <rect x="1.5" y="1.5" width="177" height="237" rx="16.5" ry="16.5" fill="none" stroke="url(#rim)" stroke-width="2"/>
      </g>

      <g transform="translate(90,95) rotate(-5) translate(-60,-60)">
        <g transform="translate(10,20)">
          <rect x="0" y="0" width="120" height="120" rx="14" ry="14" fill="#ffffff"/>
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/5/58/XGBoost_logo.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
          </g>
        </g>

        <g transform="translate(10,150) scale(1,-1)" opacity="0.20">
          <g clip-path="url(#logoClip)">
            <image href="https://upload.wikimedia.org/wikipedia/commons/5/58/XGBoost_logo.svg"
                   width="120" height="120" preserveAspectRatio="xMidYMid meet" />
            <rect x="0" y="0" width="120" height="120" fill="url(#fade)"/>
          </g>
        </g>
      </g>
    </g>

  </svg>
</p>


---

## Featured Projects

### [ShopEase](https://github.com/NASSWIEL/ShopEase)
Comprehensive e-commerce mobile application designed to provide a seamless shopping experience. Built with Flutter for the frontend and FastAPI for the backend, offering a robust solution for both customers and vendors.  
**Tech:** Dart, Flutter, Python, FastAPI.

### [Node.js E-commerce API](https://github.com/NASSWIEL/nodejs-ecommerce-api)
Production-ready RESTful backend for e-commerce: authentication & authorization (JWT), file uploads, modular architecture, payment integration, and role-based access control.  
**Tech:** JavaScript, Node.js, Express, MongoDB.

### [Real-Time Object Detection For Cars](https://github.com/NASSWIEL/Real-Time-Object-Detection-For-Cars)
Real-time computer vision system for detecting and tracking vehicles using deep learning models.  
**Tech:** Python, PyTorch/TensorFlow, OpenCV.

### [RAG (Retrieval-Augmented Generation)](https://github.com/NASSWIEL/RAG)
Implementation of RAG systems combining large language models with retrieval mechanisms for enhanced knowledge-grounded responses.  
**Tech:** Python, LLMs, Vector Databases.



---

## Contact & Links

- 🌐 Portfolio — https://www.asswiel.me/  
