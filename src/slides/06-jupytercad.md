<section>
  <h2 style="text-transform: none;">
    JupyterCAD
    <img
      src="images/jcad.png"
      alt="JupyterCAD"
      style="height: 1em; vertical-align: middle; margin-right: 0.3em;"
    />
  </h2>
  <video
    src="video/jcad/jcad.mp4"
    autoplay
    loop
    muted
    playsinline
    style="max-width: 80%; margin-top: 2rem;"
  ></video>
</section>

<section>
  <h3>About JupyterCAD</h3>
  <ul>
    <li class="fragment">Browser-native 3D modeling for JupyterLab</li>
    <li class="fragment">Built on <strong>OpenCascade</strong> (via WebAssembly)</li>
    <li class="fragment">Parametric, sketch-driven design</li>
    <li class="fragment">Integrates with Python code cells</li>
  </ul>
</section>

<!-- Vertical stack for features -->
<section>
  <h3>Sketch-based Modeling</h3>
  <p class="fragment">Draw 2D sketches and turn them into 3D shapes</p>
  <video src="video/jcad/jcad-sketch.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
</section>

<section>
  <h3>Boolean Operations</h3>
  <p class="fragment">Cut, union, and intersect shapes with precision</p>
  <video src="video/jcad/jcad-cut.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
</section>

<section>
  <h3>Geometric Operations</h3>
  <p class="fragment">Chamfer and fillet edges using UI or Python</p>
  <video src="video/jcad/jcad-chamfer.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
</section>

<section>
  <h3>Multiple Visualization Modes</h3>
  <p class="fragment" style="font-size: 1.9rem;">Explore models with <strong>Exploded View</strong>, <strong>Clip Plane</strong>, and <strong>Wireframe</strong></p>
  <video src="video/jcad/jcad-views.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1.5rem; border: 1px solid #ccc;"></video>
</section>

<section>
  <p><strong>🎛️ Transform controls with snapping</strong></p>
  <p class="fragment">Precise geometric manipulation in the browser</p>
  <video src="video/jcad/jcad-transform.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
</section>

<section>
  <p><strong>🧮 Python API for programmatic geometry</strong></p>
  <p class="fragment">Write Python code to generate & modify shapes</p>
  <video src="video/jcad/jcad-console.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
</section>

<section>
  <p><strong>📓 Notebook integration</strong></p>
  <p class="fragment">CAD alongside your code & documentation</p>
  <video src="video/jcad/jcad-notebook.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
</section>

<section>
  <p><strong>🤝 Collaborative editing</strong></p>
  <p class="fragment" style="font-size: 1.9rem">CRDT-based real-time co-editing via Y.js & PyCRDT</p>
  <video src="video/jcad/jcad-collaborative.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
</section>

<section>
  <h3>💬 Suggestions Support</h3>
  <p class="fragment" style="font-size: 1rem">
    Collaborators can propose changes without modifying the actual model.
  </p>
  <p class="fragment" style="font-size: 1rem">
    Editors receive these as <strong>suggestions</strong> and can choose to <strong>accept</strong> or <strong>reject</strong> them.
  </p>
  <p class="fragment" style="font-size: 1rem">
    Enables asynchronous review cycles, just like pull requests in code!
  </p>
  <video src="video/jcad/jcad-suggestions.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
</section>

<section>
  <h3>📁 File Format Support</h3>
  <ul>
    <li class="fragment"><strong>FCStd</strong> — Read, edit, and export <em>FreeCAD</em> project files natively</li>
    <li class="fragment"><strong>STL</strong> — Import mesh models for quick inspection or editing</li>
    <li class="fragment"><strong>STEP</strong> — Bring in precise solid geometry from external CAD tools</li>
  </ul>
  <p class="fragment" style="margin-top: 1rem;">
    Move between tools without friction — with support for common CAD formats.
  </p>
</section>

<section>
  <div style="display: flex; justify-content: center; align-items: center; gap: 1rem; margin-bottom: 1rem;">
    <a
      href="./lite/lab"
      target="_blank"
      style="display: flex; align-items: center; gap: 1rem; text-decoration: none; color: inherit;"
    >
      <h3 style="text-transform: none; margin: 0;">JupyterCAD in Action</h3>
      <img
        src="images/jcad.png"
        alt="JupyterCAD Logo"
        style="height: 60px; object-fit: contain;"
      />
    </a>
  </div>

  <iframe
    src="./lite/lab"
    style="
      border: none;
      width: 100vw;
      height: 90vh;
      zoom: 0.75;
      transform: scale(1);
      transform-origin: top left;
    "
  ></iframe>
</section>

