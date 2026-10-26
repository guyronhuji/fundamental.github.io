The Lineage Explorer is an interactive reference for working out which human cell
types a panel of protein markers points to, and for inspecting the evidence behind
each call. It runs entirely in the browser — no server, no network requests — so it
also works offline once the page has loaded.

**What it covers**

- **160 human cell profiles** across 14 lineage families: T cells, B and plasma cells, NK
  cells, monocytes and macrophages, dendritic cells, granulocytes and mast cells,
  blood and progenitors, innate lymphoid cells, endothelium, stroma and mural cells,
  epithelium and carcinoma, neural and glial cells, muscle, bone and adipose, and
  pluripotent cultures.
- **314 markers**, with aliases, cellular compartment, and allotype, subunit and
  dimer variants kept distinct.
- **Protein and RNA treated as separate modalities**, so a surface panel is never
  silently matched against a transcriptional signature.
- **53 references** behind 128 source entries, linked from each profile.

**Two ways in**

Search by *pattern* to start from the markers you measured and rank the cell types
consistent with them, or by *context* to start from a cell type and read its full
marker panel. Matches are scored transparently — every contributing marker is shown,
along with the exceptions that should give you pause.

<p>
  <a href="/interactive/Cell_Lineage_Explorer.html" target="_blank" rel="noopener">
    Open the Lineage Explorer in a new tab ↗
  </a>
  &nbsp;— recommended for small screens.
</p>

<div style="position:relative;width:100%;height:85vh;min-height:640px;overflow:hidden;border:1px solid #dce3df;border-radius:12px;">
  <iframe
    src="/interactive/Cell_Lineage_Explorer.html"
    title="Lineage Explorer — human cell and marker atlas"
    loading="lazy"
    allowfullscreen
    style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;">
  </iframe>
</div>
