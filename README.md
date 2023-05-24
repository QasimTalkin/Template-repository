---
marp: true
theme: gaia
style: |
  section.lead h1 {
  text-align: center;
  }
  section.middle li{
  text-align: center;
  }
  pre {
  font-size: 0.95rem;
  border-radius: 0.5rem;
  margin: 0.5rem;
  }
  blockquote {
    color: #aee660;
    background: #1c3a4f;
    border-left: 10px solid #aee660;
    padding: 0.5em;
    font-size: 0.75rem;
  }
  section.split {
    overflow: visible;
    display: grid;
    grid-template-columns: 50% 50%;
    grid-template-rows: 100px auto;
    grid-template-areas:
        "slideheading slideheading"
        "leftpanel rightpanel";
  }
  section.split h3,
  section.split .ldiv,
  section.split h3 {
      grid-area: slideheading;
      font-size: 50px;
    }
  section.split .ldiv { grid-area: leftpanel; }
  section.split .rdiv { grid-area: rightpanel; }
---
<!-- headingDivider: 2 -->
<!--
theme: gaia
class: lead
-->

# Template Readme
