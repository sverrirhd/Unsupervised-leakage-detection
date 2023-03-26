<h1>Leakage Detection with Non-Negative Decomposition Models Constrained with Single Fixed Component</h1><h2>Author</h2><p>Sverrir Heiðar Davíðsson<br>DTU Compute (Department of Applied Mathematics and Computer Science)<br>Danmarks Tekniske Universitet<br>Kgs. Lyngby, Denmark<br><a href="mailto:SverrirHD@gmail.com" target="_new">SverrirHD@gmail.com</a></p><h2>Overview</h2><p>This repository contains the implementation and relevant resources for the paper "Leakage Detection with Non-Negative Decomposition Models Constrained with Single Fixed Component." The project focuses on addressing non-revenue water (NRW) challenges by proposing an alteration to two non-negative decomposition models, non-negative matrix factorization (NMF), and non-negative parallel factor analysis (PARAFAC) for leakage detection in water distribution systems.</p><h2>Repository Structure</h2><pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">.
├── code/                     <span class="hljs-comment"># Source code for the project</span>
├── pdf/                      <span class="hljs-comment"># PDF of the research paper</span>
├── presentation/             <span class="hljs-comment"># Slides with a presentation of the project</span>
└── README.md                 <span class="hljs-comment"># This README file</span>
</code></div></div></pre><h2>Paper Abstract</h2><p>This paper proposes an alteration to two non-negative decomposition models, non-negative matrix factorization NMF and non-negative parallel factor analysis (PARAFAC), for leakage detection in water distribution systems. The proposed alteration is a change to the alternating least squares algorithms used to fit both models such that a single component (or factor) remains fixed and flat. This pattern is supposed to resemble the expected pattern of leakages. The paper describes three experiments that show:</p><ol><li>A flat weekly pattern is the latent representation of leakages.</li><li>The alteration enables both models to extract the flat pattern where the unaltered methods were previously unable to do so, and the effect is just as accurate of an estimation of leakages.</li><li>The method generalizes well to dissimilar usage patterns and is able to detect multiple known leakage repairs as a proxy for leakage detection.</li></ol><h2>Key Concepts</h2><ul><li>Non-negative matrix factorization (NMF)</li><li>Parallel factor analysis (PARAFAC)</li><li>Leak detection</li><li>Pattern analysis</li><li>Unsupervised learning</li><li>Water distribution systems</li></ul><h2>Getting Started</h2><p>To run the code provided in this repository, follow these steps:</p><ol><li>Clone the repository to your local machine.</li><li>Ensure that you have the necessary dependencies installed (e.g., NumPy, SciPy, scikit-learn, and Tensorly).</li><li>Run the main script to execute the experiments as described in the paper.</li></ol><h2>Additional Resources</h2><ul><li><a href="./pdf/" target="_new">PDF</a> - The PDF version of the research paper.</li><li><a href="./presentation/" target="_new">Presentation</a> - Slides with a presentation of the project.</li></ul><h2>Contact</h2><p>For any questions or comments, please contact the author at <a href="mailto:SverrirHD@gmail.com" target="_new">SverrirHD@gmail.com</a>.</p>