---
title: "Program"
featured_image: "/images/conference.jpg"
type: page   # use the theme's page layout (needed since Hugo 0.146)
position_vertical: 35%
menu:
  main:
    weight: 1
---
The format of ALPSY is flexible and can be adjusted to provide time for discussion and group work as much as possible. 

### SPEAKERS

<style>
.speaker-grid {
  display: flex;
  flex-direction: column;
  gap: 1.2em;
  margin: 1.5em 0 2.5em;
}

.speaker-card {
  background: #fff;
  border: 1px solid #ddd;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.07);
  display: flex;
  flex-direction: row;
  overflow: hidden;
}

.speaker-card img {
  width: 160px;
  min-width: 160px;
  height: 180px;
  object-fit: cover;
  object-position: top;
  display: block;
}

.speaker-card-body {
  padding: 0.85em 1em 1em;
  display: flex;
  flex-direction: column;
  flex: 1;
}

@media (max-width: 600px) {
  .speaker-card {
    flex-direction: column;
  }
  .speaker-card img {
    width: 100%;
    min-width: unset;
    height: auto;
    object-fit: contain;
  }
}

.speaker-card-name {
  font-size: 0.97em;
  font-weight: 700;
  color: #0066cc;
  margin-bottom: 0.15em;
}

.speaker-card-name a {
  color: inherit;
  text-decoration: none;
}

.speaker-card-name a:hover {
  text-decoration: underline;
}

.speaker-card-affil {
  font-size: 0.78em;
  color: #666;
  margin-bottom: 0.75em;
  line-height: 1.35;
}

.speaker-card-talks {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  flex-direction: column;
  gap: 0.45em;
}

.speaker-card-talks li {
  font-size: 0.82em;
}

.speaker-card-talks .talk-title {
  font-style: italic;
  font-weight: 600;
  color: #111;
}

.slides-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.2em;
  vertical-align: middle;
  margin-left: 0.4em;
  padding: 0.15em 0.3em;
  border: 1px solid #e8c1bd;
  border-radius: 4px;
  background: #fff;
  color: #c62828;
  font-size: 0.85em;
  font-weight: 600;
  font-style: normal;
  line-height: 1;
  text-decoration: none;
  transition: background 0.15s, border-color 0.15s;
}

.slides-btn:hover,
.slides-btn:focus-visible {
  background: #fdecea;
  border-color: #c62828;
}

.slides-btn .fa {
  font-size: 1.25em;
}

.speaker-card-talks details.abstract {
  display: block;
  margin-top: 0.2em;
}

.speaker-card-talks details.abstract > summary {
  list-style: none;
  cursor: pointer;
  display: inline;
  font-size: 0.85em;
  font-style: normal;
  font-weight: normal;
  color: #0066cc;
  text-decoration: underline;
}
.speaker-card-talks details.abstract > summary::-webkit-details-marker { display: none; }
.speaker-card-talks details.abstract > summary::marker { content: ""; }
.speaker-card-talks details.abstract > summary::before { content: "Show abstract"; }
.speaker-card-talks details.abstract[open] > summary::before { content: "Hide abstract"; }

.speaker-card-talks details.abstract .abstract-text {
  display: block;
  margin-top: 0.4em;
  font-size: 0.88em;
  font-style: italic;
  font-weight: normal;
  color: #444;
  padding-left: 0.7em;
  border-left: 3px solid #ccc;
  line-height: 1.5;
}
</style>

<div class="speaker-grid">

  <div class="speaker-card">
    <img src="/alpsy27/speakers/bruno-buchberger.png" alt="Bruno Buchberger" style="object-position: 60% top">
    <div class="speaker-card-body">
      <div class="speaker-card-name"><a href="https://www.brunobuchberger.com/">Bruno Buchberger</a></div>
      <div class="speaker-card-affil">RISC, Johannes Kepler University Linz — Austria</div>
      <!-- TODO (ALPSY 2027): add the talk once known (see the template below).
      <ul class="speaker-card-talks">
        <li>
          <span class="talk-title">Talk title</span>
        </li>
      </ul>
      -->
    </div>
  </div>

</div>

<!-- TODO (ALPSY 2027): one card per speaker. Photos go in static/alpsy27/speakers/, slides in static/alpsy27-pdf/.
  <div class="speaker-card">
    <img src="/alpsy27/speakers/name.png" alt="Speaker Name">
    <div class="speaker-card-body">
      <div class="speaker-card-name"><a href="https://speaker-homepage">Speaker Name</a></div>
      <div class="speaker-card-affil">Affiliation — Country</div>
      <ul class="speaker-card-talks">
        <li>
          <span class="talk-title">Talk title</span> <a class="slides-btn" href="/alpsy27-pdf/Name.pdf" download title="Download slides (PDF)" aria-label="Download slides (PDF)"><i class="fa fa-file-pdf-o" aria-hidden="true"></i></a>
          <details class="abstract"><summary></summary>
            <div class="abstract-text">Abstract text.</div>
          </details>
        </li>
      </ul>
    </div>
  </div>
-->


### PROGRAM

The detailed program will be announced soon.

<!-- TODO (ALPSY 2027): replace the line above with one block per day, e.g.
<details><summary><b>Day, DD.MM</b></summary>

##### 9:00 - 9:15 Opening remarks
##### 9:15 - 9:45 Speaker Name
##### 10:30 - 11:00 Coffee break
##### 12:30 - 14:00 Lunch
##### 19:00 Dinner

</details>
-->
