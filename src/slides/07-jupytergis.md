<section>
  <h2 style="text-transform: none;">
    JupyterGIS
    <img
      src="images/jgis.png"
      alt="JupyterGIS"
      style="height: 1em; vertical-align: middle; margin-right: 0.3em;"
    />
  </h2>
  <video
    src="video/jgis/jgis.mp4"
    autoplay
    loop
    muted
    playsinline
    style="max-width: 80%; margin-top: 2rem;"
  ></video>
</section>


<section>
  <h3>About JupyterGIS</h3>
  <ul>
    <li class="fragment">A full-featured GIS toolkit inside JupyterLab</li>
    <li class="fragment">Supports raster and vector layers</li>
    <li class="fragment">Built with <strong>OpenLayers</strong> + <strong>GDAL</strong> (WebAssembly)</li>
  </ul>
</section>

<!-- Vertical stack for features -->
  <section>
    <h3>🗺️ Vector & Raster Data Support</h3>
    <p class="fragment" style="font-size: 1.9rem">Load local and cloud-hosted data into your notebook session</p>
    <video src="video/jgis/jgis-layers.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
  </section>

  <section>
    <h3>🖍️ Vector Symbology</h3>
    <p class="fragment">Visualize vector data using <strong>graduated</strong> and <strong>categorized</strong> rendering styles</p>
    <video src="video/jgis/jgis-vector-symbology.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
  </section>

  <section>
    <h3>🖍️ Raster Symbology</h3>
    <p class="fragment">Use <strong>multiband rendering</strong> to style raster datasets like satellite imagery</p>
    <video src="video/jgis/jgis-raster-symbology.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
  </section>

  <section>
    <h3>🔄 Dynamic Layer Management</h3>
    <p class="fragment">Add, remove, and style layers with a built-in interactive UI</p>
    <video src="video/jgis/jgis-layer-management.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
  </section>

  <section>
  <h3>🔍 Identify Panel</h3>
  <p class="fragment">
    Click on features in the map to instantly inspect their attributes.
  </p>
  <video src="video/jgis/jgis-identify.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
</section>


  <section>
  <h3>⏳ Time Slider</h3>
  <p class="fragment">
    Visualize how data changes over time with an interactive slider.
  </p>
  <video src="video/jgis/jgis-timeslider.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
</section>


  <section>
  <h3>🧩 QGIS Compatibility</h3>
  <p class="fragment">
    Import and export QGIS files, layers, and styles seamlessly.
  </p>
  <video src="video/jgis/jgis-qgis.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
</section>

  <section>
  <h3>📝 Annotation & Collaboration</h3>
  <p class="fragment">
    Add notes, draw shapes, and collaborate in real-time.
  </p>
  <video src="video/jgis/jgis-annotation.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
</section>


  <section>
    <h3>📓 Notebook + Python Integration</h3>
    <p class="fragment">Use Python code cells to add, style, and transform spatial layers</p>
    <video src="video/jgis/jgis-notebook.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
  </section>

  <section>
    <h3>🧪 Client-Side Processing</h3>
    <p class="fragment">Perform buffer, dissolve, centroid and overlays with GDAL-WASM — no server required</p>
    <video src="video/jgis/jgis-processing.mp4" autoplay loop muted playsinline style="max-width: 90%; margin-top: 1rem;"></video>
  </section>

<!-- <section>
  <h3>🌐 Scientific Edge: GDAL in the Browser</h3>
  <ul>
    <li class="fragment"><strong>Raster reprojection</strong> & CRS transformations</li>
    <li class="fragment"><strong>Zonal statistics</strong> on raster/vector intersections</li>
    <li class="fragment"><strong>Geometry operations</strong> like clipping & intersection</li>
    <li class="fragment">Fully client-side & offline-capable</li>
    <li class="fragment">Ideal for environmental science, urban planning, and climate research</li>
  </ul>
</section> -->

<section>
  <div style="display: flex; justify-content: center; align-items: center; gap: 1rem; margin-bottom: 1rem;">
    <a
      href="./lite/lab"
      target="_blank"
      style="display: flex; align-items: center; gap: 1rem; text-decoration: none; color: inherit;"
    >
      <h3 style="text-transform: none; margin: 0;">JupyterGIS in Action</h3>
      <img
        src="images/jgis.png"
        alt="JupyterGIS Logo"
        style="height: 60px; object-fit: contain;"
      />
    </a>
  </div>

  <iframe
    src="./lite/lab"
    style="
      border: none;
      width: 100vw;
      height: 80vh;
      zoom: 0.75;
      transform: scale(1);
      transform-origin: top left;
    "
  ></iframe>
</section>
