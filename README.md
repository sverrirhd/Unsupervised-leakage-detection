<h1>Leakage Detection with Non-Negative Decomposition Models Constrained with Single Fixed Component</h1><h2>Author</h2><p>Sverrir Heiðar Davíðsson<br>DTU Compute (Department of Applied Mathematics and Computer Science)<br>Danmarks Tekniske Universitet<br>Kgs. Lyngby, Denmark<br><a href="mailto:SverrirHD@gmail.com" target="_new">SverrirHD@gmail.com</a></p><h2>Overview</h2><p>This repository contains the implementation and relevant resources for the paper "Leakage Detection with Non-Negative Decomposition Models Constrained with Single Fixed Component." The project focuses on addressing non-revenue water (NRW) challenges by proposing an alteration to two non-negative decomposition models, non-negative matrix factorization (NMF), and non-negative parallel factor analysis (PARAFAC) for leakage detection in water distribution systems.</p>

<h2>Paper Abstract</h2>
<p>This paper proposes an alteration to two non-negative decomposition models, non-negative matrix factorization NMF and non-negative parallel factor analysis (PARAFAC), for leakage detection in water distribution systems. The proposed alteration is a change to the alternating least squares algorithms used to fit both models such that a single component (or factor) remains fixed and flat. This pattern is supposed to resemble the expected pattern of leakages. The paper describes three experiments that show:</p>
<ol>
    <li>A flat weekly pattern is the latent representation of leakages.</li>
    <li>The alteration enables both models to extract the flat pattern where the unaltered methods were previously unable to do so, and the effect is just as accurate of an estimation of leakages.</li>
    <li>The method generalizes well to dissimilar usage patterns and is able to detect multiple known leakage repairs as a proxy for leakage detection.</li>
</ol>
<h2>Key Concepts</h2>
<ul>
    <li>Non-negative matrix factorization (NMF)</li>
    <li>Parallel factor analysis (PARAFAC)</li>
    <li>Leak detection</li>
    <li>Pattern analysis</li>
    <li>Unsupervised learning</li>
    <li>Water distribution systems</li>
</ul>

<h2>Additional Resources</h2><ul><li><a href="https://github.com/sverrirhd/Unsupervised-leakage-detection/raw/main/Final%20project%20-%2002830%20-%20SHD.pdf" target="_new">PDF</a> - The PDF version of the research paper.</li>
<li><a href="https://github.com/sverrirhd/Unsupervised-leakage-detection/raw/main/Final%20presentation%20-%20Advanced%20project.pdf" target="_new">Presentation</a> - Slides with a presentation of the project.</li>
</ul><h2>Contact</h2><p>For any questions or comments, please contact the author at <a href="mailto:SverrirHD@gmail.com" target="_new">SverrirHD@gmail.com</a>.</p>