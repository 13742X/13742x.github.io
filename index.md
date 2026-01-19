# Steven Garner

Entrepreneur | Researcher | Inventor | Whitepapers & Patents

[Email](mailto:13742x@gmail.com) • [GitHub](https://github.com/13742x) • [LinkedIn](https://www.linkedin.com/in/steven_garner/) • [Google Scholar](https://scholar.google.com/citations?user=JKIrY4IAAAAJ&hl=en)

---

## Filter Publications
<button onclick="filterPub('all')">All</button>
<button onclick="filterPub('granted')">Granted Patents</button>
<button onclick="filterPub('pending')">Pending Patents</button>
<button onclick="filterPub('whitepaper')">White Papers</button>

<div id="pub-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1.2rem; margin-top: 1rem;">

  <!-- Granted Patents -->
  <div class="publication granted" style="background-color:#cce5ff; border-radius:12px; padding:1rem; box-shadow:0 2px 6px rgba(0,0,0,0.1); transition: transform 0.2s;">
    <strong>2025 | Granted Patent</strong>
    <p><em>Digital storage and data transport system using file fragments assigned to data storage packets</em></p>
    <p><a href="https://patents.google.com/patent/US12468833B2/en" target="_blank">US12468833B2</a></p>
  </div>

  <div class="publication granted" style="background-color:#cce5ff; border-radius:12px; padding:1rem; box-shadow:0 2px 6px rgba(0,0,0,0.1); transition: transform 0.2s;">
    <strong>2023 | Granted Patent</strong>
    <p><em>Digital storage and data transport system</em></p>
    <p><a href="https://patents.google.com/patent/US11604888B2/en" target="_blank">US11604888B2</a></p>
  </div>

  <!-- Pending Patents -->
  <div class="publication pending" style="background-color:#e2e3e5; border-radius:12px; padding:1rem; box-shadow:0 2px 6px rgba(0,0,0,0.1); transition: transform 0.2s;">
    <strong>2025 | Pending Patent</strong>
    <p><em>Authenticating videos using AI and blockchain technologies</em></p>
    <p><a href="https://patents.google.com/patent/US20250259431A1/en" target="_blank">US18438646</a></p>
  </div>

  <!-- White Papers -->
  <div class="publication whitepaper" style="background-color:#d4edda; border-radius:12px; padding:1rem; box-shadow:0 2px 6px rgba(0,0,0,0.1); transition: transform 0.2s;">
    <strong>2026 | White Paper</strong>
    <p><em>The Case for APM AIM</em></p>
    <p><a href="https://github.com/13742x/publications/blob/main/2026/2026-APM-AIM.pdf" target="_blank">PDF</a></p>
  </div>

  <div class="publication whitepaper" style="background-color:#d4edda; border-radius:12px; padding:1rem; box-shadow:0 2px 6px rgba(0,0,0,0.1); transition: transform 0.2s;">
    <strong>2026 | White Paper</strong>
    <p><em>FIDO2 for SMEs</em></p>
    <p><a href="https://github.com/13742x/publications/blob/main/2026/2026-Why-You-Only-Need-FIDO2.pdf" target="_blank">PDF</a></p>
  </div>

 <div class="publication whitepaper" style="background-color:#d4edda; border-radius:12px; padding:1rem; box-shadow:0 2px 6px rgba(0,0,0,0.1); transition: transform 0.2s;">
    <strong>2025 | White Paper</strong>
    <p><em>AI Driven Dynamic Indexing for Unstructured Data Storage</em></p>
    <p><a href="https://github.com/13742X/publications/blob/75dbd89b521b7e399bfe4ad991f76f968733ea91/2025/White-Paper-AI-DRIVEN-DYNAMIC-INDEXING-FOR-UNSTRUCTURED-DATA-STORAGE.pdf" target="_blank">PDF</a></p>
  </div>

  <div class="publication whitepaper" style="background-color:#d4edda; border-radius:12px; padding:1rem; box-shadow:0 2px 6px rgba(0,0,0,0.1); transition: transform 0.2s;">
    <strong>2025 | White Paper</strong>
    <p><em>Use Case for Military and Defence and DSM Fragmentation</em></p>
    <p><a href="https://github.com/13742X/publications/blob/main/2025/2025-White-Paper-Military-Use-Case-For-Fragmentation.pdf" target="_blank">PDF</a></p>
  </div>

  <div class="publication whitepaper" style="background-color:#d4edda; border-radius:12px; padding:1rem; box-shadow:0 2px 6px rgba(0,0,0,0.1); transition: transform 0.2s;">
    <strong>2024 | White Paper</strong>
    <p><em>Sharding Files for Redundancy, Security, and Privacy: The Shard Share Protocol</em></p>
    <p><a href="https://drive.google.com/file/d/1ADT3dGgQY-jVuIqJ94dPnKG3uXOUMjk_/view" target="_blank">WWW</a></p>
  </div>

  <div class="publication whitepaper" style="background-color:#d4edda; border-radius:12px; padding:1rem; box-shadow:0 2px 6px rgba(0,0,0,0.1); transition: transform 0.2s;">
    <strong>2022 | White Paper</strong>
    <p><em>Unus Protocol</em></p>
    <p><a href="https://docs.google.com/document/d/e/2PACX-1vTYEJe181NQG0Fk3GzQWamRbMHfHxLsRNk8PaZFWSQbc1jhcxtx7B4fFflT1PFUgOLADmgp6lXdhdvt/pub" target="_blank">WWW</a></p>
  </div>

  <div class="publication whitepaper" style="background-color:#d4edda; border-radius:12px; padding:1rem; box-shadow:0 2px 6px rgba(0,0,0,0.1); transition: transform 0.2s;">
    <strong>2021 | White Paper</strong>
    <p><em>Double Entry Contract (DEC) Accounting on a Distributed Accounting Ledger</em></p>
    <p><a href="https://accdefi.com/accdefiwhitepaper.html" target="_blank">WWW</a></p>
  </div>

</div>

<script>
function filterPub(type) {
  const pubs = document.querySelectorAll('.publication');
  pubs.forEach(pub => {
    if (type === 'all') {
      pub.style.display = 'block';
    } else if (pub.classList.contains(type)) {
      pub.style.display = 'block';
    } else {
      pub.style.display = 'none';
    }
  });
}

// Hover effect
const allPubs = document.querySelectorAll('.publication');
allPubs.forEach(pub => {
  pub.addEventListener('mouseenter', () => {
    pub.style.transform = 'scale(1.03)';
  });
  pub.addEventListener('mouseleave', () => {
    pub.style.transform = 'scale(1)';
  });
});
</script>
