

<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Louisiana Off-Grid Earthship Systems Report</title>
<style>
:root{
  --green:#143d27; --green2:#2f5c38; --gold:#b48a34; --blue:#1f6c9b; --orange:#d8891f;
  --paper:#fbf8ef; --ink:#1d211b; --muted:#5d665b; --line:#d7cfb9; --card:#fffdf7;
}
*{box-sizing:border-box} html{scroll-behavior:smooth}
body{margin:0;background:#e7e0cf;color:var(--ink);font-family:Inter,Segoe UI,Arial,sans-serif;line-height:1.55}
.report{max-width:1180px;margin:0 auto;background:var(--paper);box-shadow:0 0 30px rgba(0,0,0,.18)}
.hero{padding:56px 54px 44px;background:linear-gradient(135deg,#102b1d,#214c31 55%,#7c6529);color:white;position:relative;overflow:hidden}
.hero:after{content:"";position:absolute;right:-100px;top:-100px;width:360px;height:360px;border-radius:50%;background:rgba(255,255,255,.08)}
.kicker{font-size:.82rem;letter-spacing:.16em;text-transform:uppercase;color:#e9d7a1;font-weight:700;margin-bottom:16px}
h1{font-family:Georgia,serif;font-size:3.1rem;line-height:1.04;margin:0 0 16px}.subtitle{font-size:1.16rem;color:#f0eadb;max-width:820px}.meta{margin-top:28px;display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:12px}.meta div{background:rgba(255,255,255,.08);border:1px solid rgba(255,255,255,.16);border-radius:14px;padding:12px}.meta b{display:block;color:#e9d7a1;font-size:.75rem;text-transform:uppercase;letter-spacing:.08em}.meta span{font-size:1rem}
.content{padding:40px 54px 60px}.toc{display:flex;flex-wrap:wrap;gap:10px;margin-bottom:28px}.toc a{color:var(--green);border:1px solid var(--line);background:var(--card);padding:8px 12px;border-radius:999px;text-decoration:none;font-size:.88rem}.toc a:hover{background:#f1ead8}
section{margin:34px 0 50px}h2{font-family:Georgia,serif;font-size:2rem;color:var(--green);border-top:3px solid var(--line);padding-top:24px;margin:0 0 14px}h3{font-size:1.15rem;color:var(--green2);margin:22px 0 8px}.lead{font-size:1.08rem;color:#333;max-width:920px}.grid{display:grid;gap:18px}.two{grid-template-columns:repeat(2,minmax(0,1fr))}.three{grid-template-columns:repeat(3,minmax(0,1fr))}.four{grid-template-columns:repeat(4,minmax(0,1fr))}
.card{background:var(--card);border:1px solid var(--line);border-radius:18px;padding:18px;box-shadow:0 2px 8px rgba(0,0,0,.04)}.card h3,.card h4{margin-top:0}.big-number{font-size:2.25rem;font-weight:900;color:var(--green);line-height:1}.unit{font-weight:700;color:var(--muted)}.callout{border-left:5px solid var(--gold);background:#f2ead6;border-radius:12px;padding:18px;margin:20px 0}.warning{border-left-color:#b75b2b;background:#f8eadf}.good{border-left-color:var(--green2);background:#eaf2e6}
ul{padding-left:22px}li{margin:.25rem 0}table{width:100%;border-collapse:collapse;margin:16px 0;background:var(--card);border:1px solid var(--line);font-size:.95rem}th{background:var(--green);color:white;text-align:left;padding:10px}td{border-top:1px solid var(--line);padding:9px;vertical-align:top}tr:nth-child(even) td{background:#f6f1e6}.formula{font-family:ui-monospace,Menlo,Consolas,monospace;background:#1d211b;color:#f7f1df;border-radius:14px;padding:14px 16px;overflow:auto}.note{font-size:.86rem;color:var(--muted)}
.diagram{background:#fff;border:1px solid var(--line);border-radius:18px;padding:18px;margin:18px 0;overflow:auto}.diagram svg{width:100%;min-width:720px;height:auto}.box{fill:#fffdf7;stroke:#2f5c38;stroke-width:2}.dash{stroke-dasharray:7 6}.label{font-family:Inter,Arial,sans-serif;font-weight:700;fill:#173a27;font-size:14px}.small{font-size:12px;font-weight:500;fill:#4d5a4d}.flow-e{stroke:#d8891f;stroke-width:4;fill:none;marker-end:url(#arrowE)}.flow-w{stroke:#1f6c9b;stroke-width:4;fill:none;marker-end:url(#arrowW)}.flow-d{stroke:#1f6c9b;stroke-width:3;fill:none;stroke-dasharray:7 5;marker-end:url(#arrowW)}.flow-c{stroke:#2f5c38;stroke-width:3;fill:none;stroke-dasharray:6 5;marker-end:url(#arrowC)}
.footer{background:#153a27;color:#e9dfc4;padding:28px 54px;font-size:.86rem}.refs{columns:2;column-gap:34px}.refs li{break-inside:avoid;margin-bottom:6px}
@media(max-width:860px){.content,.hero{padding-left:24px;padding-right:24px}h1{font-size:2.25rem}.meta,.two,.three,.four{grid-template-columns:1fr}.refs{columns:1}.diagram svg{min-width:760px}}
@media print{body{background:white}.report{box-shadow:none}.toc{display:none}section{break-inside:avoid}.hero{background:#153a27!important;-webkit-print-color-adjust:exact;print-color-adjust:exact}}
</style>
</head>
<body>
<main class="report">
<header class="hero">
  <div class="kicker">Updated from MCHE 358 PowerPoint · Spring 2026</div>
  <h1>Louisiana Off-Grid Earthship Systems</h1>
  <p class="subtitle">A design-basis report for a 2,000 ft² single-family residence in Lafayette, Louisiana: renewable power, battery autonomy, water independence, humidity control, and climate-adapted Earthship principles.</p>
  <div class="meta">
    <div><b>Location</b><span>Lafayette, Louisiana</span></div>
    <div><b>Residence</b><span>2,000 ft² · 4 occupants</span></div>
    <div><b>Climate</b><span>Hot-humid, CZ-2A</span></div>
    <div><b>Design Goal</b><span>Off-grid power + water resilience</span></div>
  </div>
</header>
<div class="content">
<nav class="toc">
  <a href="#overview">Overview</a><a href="#background">Earthship Adaptation</a><a href="#architecture">System Architecture</a><a href="#components">Components</a><a href="#loads">Loads</a><a href="#pv">PV Array</a><a href="#battery">Battery</a><a href="#efficiency">Efficiency</a><a href="#water">Water</a><a href="#safety">Safety</a><a href="#validation">Validation</a><a href="#cost">Cost</a><a href="#conclusion">Conclusion</a>
</nav>

<section id="overview">
<h2>1. Project overview</h2>
<p class="lead">The project designs an off-grid renewable energy and water system for a 2,000 ft² single-family residence in Lafayette, Louisiana. The home is intended to be independent of utility power and water service, powered primarily by rooftop PV with battery storage, with a generator and backup well reserved for emergency or deficit conditions.</p>
<div class="grid four">
  <div class="card"><div class="big-number">10</div><span class="unit">kW DC PV array</span><p>35 × 400 W modules, sized for December worst-week solar availability plus margin.</p></div>
  <div class="card"><div class="big-number">210</div><span class="unit">kWh LFP battery bank</span><p>Designed for about 3 days of autonomy using conservative round-trip, DoD, and end-of-life factors.</p></div>
  <div class="card"><div class="big-number">40.6</div><span class="unit">kWh/day peak design load</span><p>Includes HVAC, dehumidifier, water heater, pumps, lighting, plug loads, ERV fan, and standby loads.</p></div>
  <div class="card"><div class="big-number">91%</div><span class="unit">rainwater demand coverage</span><p>Rainwater supplies most annual demand, with a backup well covering dry-season and deficit margin.</p></div>
</div>
</section>

<section id="background">
<h2>2. Earthship background and Lafayette adaptation</h2>
<div class="grid two">
  <div class="card"><h3>Traditional Earthship model</h3><ul><li>Developed by Michael Reynolds beginning in the 1970s.</li><li>Self-sufficient systems: power, water, waste, and food.</li><li>Solar PV plus battery storage.</li><li>Rainwater catchment and reuse.</li><li>Passive heating/cooling using thermal mass.</li><li>Optimized around arid high-desert climate assumptions.</li></ul></div>
  <div class="card"><h3>Lafayette redesign logic</h3><ul><li>Hot-humid climate breaks passive-only cooling assumptions.</li><li>Active HVAC and dehumidification become dominant electrical loads.</li><li>High rainfall makes rainwater harvesting viable.</li><li>Raised foundation is favored over berming for flood and moisture risk.</li><li>FEMA flood compliance and mold prevention become core design drivers.</li></ul></div>
</div>
<div class="callout warning"><strong>Key design shift:</strong> the Louisiana Earthship is not a direct transplant of a Taos Earthship. It is a hybrid, climate-adapted off-grid residence where moisture control, HVAC, and flood-aware construction are essential systems rather than optional upgrades.</div>
</section>

<section id="architecture">
<h2>3. System architecture</h2>
<p>The PowerPoint defines two primary architecture chains: an electrical system and a water system. The electrical system routes PV generation through power electronics and storage to building loads, while the water system captures rainfall, diverts first flush, stores water, pumps it through filtration, and supplies potable use with backup well redundancy.</p>
<div class="diagram" aria-label="Electrical and water system flow diagrams">
<svg viewBox="0 0 980 520" role="img">
<defs><marker id="arrowE" markerWidth="10" markerHeight="10" refX="8" refY="3" orient="auto"><path d="M0,0 L0,6 L9,3 z" fill="#d8891f"/></marker><marker id="arrowW" markerWidth="10" markerHeight="10" refX="8" refY="3" orient="auto"><path d="M0,0 L0,6 L9,3 z" fill="#1f6c9b"/></marker><marker id="arrowC" markerWidth="10" markerHeight="10" refX="8" refY="3" orient="auto"><path d="M0,0 L0,6 L9,3 z" fill="#2f5c38"/></marker></defs>
<text x="20" y="36" class="label" font-size="22">Electrical system</text>
<rect x="30" y="70" width="130" height="58" rx="10" class="box"/><text x="95" y="102" text-anchor="middle" class="label">PV Array</text>
<path d="M160 99 L210 99" class="flow-e"/><rect x="210" y="70" width="150" height="58" rx="10" class="box"/><text x="285" y="96" text-anchor="middle" class="label">Charge</text><text x="285" y="113" text-anchor="middle" class="label">Controller</text>
<path d="M360 99 L410 99" class="flow-e"/><rect x="410" y="70" width="120" height="58" rx="10" class="box"/><text x="470" y="103" text-anchor="middle" class="label">Inverter</text>
<path d="M530 99 L580 99" class="flow-e"/><rect x="580" y="70" width="140" height="58" rx="10" class="box"/><text x="650" y="96" text-anchor="middle" class="label">Breaker</text><text x="650" y="113" text-anchor="middle" class="label">Panel</text>
<path d="M795 99 L735 99" class="flow-e dash"/><rect x="795" y="70" width="130" height="58" rx="10" fill="#fffdf7" stroke="#2f5c38" stroke-width="2" stroke-dasharray="8 6"/><text x="860" y="104" text-anchor="middle" class="label">Generator</text>
<rect x="310" y="176" width="140" height="58" rx="10" class="box"/><text x="380" y="211" text-anchor="middle" class="label">Battery</text><path d="M470 128 L470 164 L380 164 L380 176" class="flow-e"/><path d="M380 176 L380 164 L470 164 L470 128" class="flow-c"/>
<rect x="330" y="18" width="300" height="36" rx="8" fill="#fffdf7" stroke="#2f5c38" stroke-width="2" stroke-dasharray="8 6"/><text x="480" y="41" text-anchor="middle" class="label">EMS + BMS</text><path d="M480 54 L480 70" class="flow-c"/>
<path d="M650 128 L650 268" class="flow-e"/><g><rect x="35" y="286" width="125" height="52" rx="10" class="box"/><text x="98" y="317" text-anchor="middle" class="label">HVAC</text><rect x="180" y="286" width="140" height="52" rx="10" class="box"/><text x="250" y="317" text-anchor="middle" class="label">Dehumidifier</text><rect x="340" y="286" width="150" height="52" rx="10" class="box"/><text x="415" y="317" text-anchor="middle" class="label">Water Heater</text><rect x="510" y="286" width="120" height="52" rx="10" class="box"/><text x="570" y="317" text-anchor="middle" class="label">Pumps</text><rect x="650" y="286" width="150" height="52" rx="10" class="box"/><text x="725" y="317" text-anchor="middle" class="label">Lights & Plugs</text></g><path d="M650 268 L98 268 L98 286" class="flow-e"/><path d="M650 268 L250 268 L250 286" class="flow-e"/><path d="M650 268 L415 268 L415 286" class="flow-e"/><path d="M650 268 L570 268 L570 286" class="flow-e"/><path d="M650 268 L725 268 L725 286" class="flow-e"/>
<text x="20" y="404" class="label" font-size="22">Water system</text>
<g><rect x="30" y="430" width="90" height="52" rx="10" class="box"/><text x="75" y="461" text-anchor="middle" class="label">Rain</text><rect x="145" y="430" width="90" height="52" rx="10" class="box"/><text x="190" y="461" text-anchor="middle" class="label">Roof</text><rect x="260" y="430" width="130" height="52" rx="10" class="box"/><text x="325" y="461" text-anchor="middle" class="label">First-Flush</text><rect x="415" y="430" width="110" height="52" rx="10" class="box"/><text x="470" y="461" text-anchor="middle" class="label">Cistern</text><rect x="550" y="430" width="90" height="52" rx="10" class="box"/><text x="595" y="461" text-anchor="middle" class="label">Pump</text><rect x="665" y="430" width="110" height="52" rx="10" class="box"/><text x="720" y="461" text-anchor="middle" class="label">Filtration</text><rect x="800" y="430" width="130" height="52" rx="10" class="box"/><text x="865" y="461" text-anchor="middle" class="label">Potable Use</text></g><path d="M120 456 L145 456" class="flow-w"/><path d="M235 456 L260 456" class="flow-w"/><path d="M390 456 L415 456" class="flow-w"/><path d="M525 456 L550 456" class="flow-w"/><path d="M640 456 L665 456" class="flow-w"/><path d="M775 456 L800 456" class="flow-w"/><rect x="420" y="342" width="110" height="45" rx="8" fill="#fffdf7" stroke="#1f6c9b" stroke-width="2" stroke-dasharray="8 6"/><text x="475" y="370" text-anchor="middle" class="label">Backup Well</text><path d="M475 387 L475 430" class="flow-d"/>
</svg>
</div>
</section>

<section id="components">
<h2>4. Component decisions</h2>
<table><thead><tr><th>Component</th><th>Selection</th><th>Why it was selected</th></tr></thead><tbody>
<tr><td>PV modules</td><td>Q CELLS Q.PEAK 400 W</td><td>Commercial 25-year warranty, about 21% efficiency, and good performance at reasonable price.</td></tr>
<tr><td>Charge controller / inverter</td><td>Sol-Ark 15K-2P</td><td>Combines MPPT, charge control, and DC-AC inverter functions; handles running load and startup surges.</td></tr>
<tr><td>Battery</td><td>48 V LFP bank, FranklinWH or EG4 class</td><td>LFP chemistry avoids thermal runaway concerns relative to NMC and supports long cycle life for indoor conditioned installation.</td></tr>
<tr><td>Generator</td><td>14 kW propane standby</td><td>Emergency backup only; propane storage can remain available during grid outages.</td></tr>
<tr><td>Heat pump</td><td>2.5 ton, SEER2 17 variable-speed</td><td>High efficiency with variable-speed part-load operation that improves humidity management.</td></tr>
<tr><td>Heat pump water heater</td><td>UEF 3.5 class</td><td>Roughly 3.5× more efficient than electric resistance water heating, which helps off-grid sizing.</td></tr>
<tr><td>Whole-house dehumidifier</td><td>90 pint/day Aprilaire or Ultra-Aire class</td><td>Independent moisture control during periods when the AC is not cycling enough for latent removal.</td></tr>
</tbody></table>
</section>

<section id="loads">
<h2>5. Load profile and design considerations</h2>
<div class="grid two"><div class="card"><h3>Climate and envelope drivers</h3><ul><li>Cooling design temperature: 94 °F.</li><li>Coincident wet-bulb: 78 °F.</li><li>Ventilation air latent load: each pound of vent air must lose about 53 grains of moisture.</li><li>Envelope target: 1.5 ACH50, compared with a code-minimum style 5.0 ACH50 case.</li><li>Wall concept: R-21 cavity insulation plus R-7 continuous insulation.</li></ul></div><div class="card"><h3>All-electric load drivers</h3><ul><li>Heat pump for cooling and heating.</li><li>Heat pump water heater with UEF 3.5.</li><li>Whole-house dehumidifier treated as a major load.</li><li>Water-system loads explicitly counted: cistern pump, UV sterilizer, and well backup pump.</li><li>ERV fan included as a continuous ventilation load.</li></ul></div></div>
<table><thead><tr><th>Load</th><th>kWh/day</th><th>Derivation / basis</th></tr></thead><tbody>
<tr><td>Heat pump cooling</td><td>15.0</td><td>2.5 ton at SEER2 17, 10 hr/day at 60% capacity.</td></tr>
<tr><td>Domestic hot water</td><td>6.5</td><td>4 occupants × 17 gal/day at UEF 3.5; conservative.</td></tr>
<tr><td>Whole-house dehumidifier</td><td>6.0</td><td>90 pt/day unit at 600 W, 40% duty.</td></tr>
<tr><td>Plug loads + appliances</td><td>6.0</td><td>Typical 4-occupant home.</td></tr>
<tr><td>ERV ventilation fan</td><td>1.9</td><td>80 W continuous ventilation fan assumption.</td></tr>
<tr><td>Cistern booster pump</td><td>1.5</td><td>1 hp jet pump, on-demand cycling.</td></tr>
<tr><td>Refrigerator</td><td>1.4</td><td>ENERGY STAR class assumption.</td></tr>
<tr><td>Standby loads</td><td>1.0</td><td>Router, BMS, EMS continuous loads.</td></tr>
<tr><td>Lighting</td><td>0.8</td><td>LED lighting, 200 W connected, 4 hr average.</td></tr>
<tr><td>UV + well backup</td><td>0.5</td><td>Water treatment support.</td></tr>
<tr><td><strong>Total peak design day</strong></td><td><strong>40.6</strong></td><td>Annual average later estimated near 26 kWh/day and 9,490 kWh/year.</td></tr>
</tbody></table>
</section>

<section id="pv">
<h2>6. PV array sizing</h2>
<div class="formula">P_DC = E_daily / ( PSH × η_system )<br>η_system = 0.78 &nbsp; // off-grid derate including battery cycling losses</div>
<table><thead><tr><th>Sizing basis</th><th>E_daily</th><th>PSH</th><th>P_DC</th></tr></thead><tbody>
<tr><td>Annual average</td><td>26 kWh/day</td><td>4.9</td><td>6.8 kW</td></tr>
<tr><td>December monthly average</td><td>30 kWh/day</td><td>3.6</td><td>10.7 kW</td></tr>
<tr><td>December worst-week</td><td>26 kWh/day</td><td>2.5</td><td>13.3 kW</td></tr>
<tr><td><strong>Selected system</strong></td><td colspan="3"><strong>14 kW DC array = 35 × 400 W modules</strong></td></tr>
</tbody></table>
<div class="callout good"><strong>Interpretation:</strong> the PV array is not sized just for annual average production. It is sized around the weak solar condition: December worst-week availability, with margin for degradation and weather variability.</div>
</section>

<section id="battery">
<h2>7. Battery sizing</h2>
<div class="formula">E_nameplate = ( E_daily × Days_auto ) / ( RTE × DOD × EOL )<br>(40 × 3) / (0.90 × 0.80 × 0.80) = 208 kWh nominal</div>
<div class="grid four"><div class="card"><div class="big-number">40</div><span class="unit">kWh/day</span><p>Peak design day load.</p></div><div class="card"><div class="big-number">3</div><span class="unit">days</span><p>Autonomy target for worst sequential cloudy stretch.</p></div><div class="card"><div class="big-number">0.90</div><span class="unit">RTE</span><p>LFP battery round-trip efficiency at conditioned temperature.</p></div><div class="card"><div class="big-number">0.80</div><span class="unit">EOL factor</span><p>Industry-standard warranty endpoint.</p></div></div>
<p><strong>Selected battery system:</strong> approximately <strong>210 kWh LFP</strong> at 48 V DC, represented as 14 modules at roughly 15 kWh each, such as FranklinWH aPower 2 or EG4 PowerPro class modules.</p>
</section>

<section id="efficiency">
<h2>8. End-to-end efficiency</h2>
<table><thead><tr><th>Stage</th><th>Multiplier</th><th>Basis</th></tr></thead><tbody>
<tr><td>Module STC → operating</td><td>0.92</td><td>Temperature, soiling, mismatch.</td></tr>
<tr><td>DC wiring</td><td>0.98</td><td>Conduction losses.</td></tr>
<tr><td>Charge controller / MPPT</td><td>0.97</td><td>DC-DC conversion.</td></tr>
<tr><td>Battery RTE, cycled</td><td>0.90</td><td>Charge/discharge efficiency.</td></tr>
<tr><td>Inverter</td><td>0.95</td><td>DC to AC switching losses.</td></tr>
<tr><td>AC distribution</td><td>0.99</td><td>Branch circuit losses.</td></tr>
<tr><td><strong>End-to-end, battery-cycled</strong></td><td><strong>0.74</strong></td><td>Product of all above.</td></tr>
<tr><td><strong>PV-direct path</strong></td><td><strong>0.82</strong></td><td>Skips battery round-trip efficiency loss.</td></tr>
</tbody></table>
<p class="note">The inverter should prioritize PV-direct operation when instantaneous PV production matches load, reducing avoidable battery cycling losses.</p>
</section>

<section id="water">
<h2>9. Water system feasibility</h2>
<div class="formula">Annual Yield = Catchment Area × Rainfall × Conversion × Efficiency<br>= 2,000 ft² × 62.64 in/yr × 0.623 gal/(ft²·in) × 0.85<br>= 66,300 gal/year</div>
<table><thead><tr><th>Quantity</th><th>Value</th></tr></thead><tbody>
<tr><td>Annual rainfall yield</td><td>66,300 gal/year</td></tr><tr><td>Annual demand</td><td>73,000 gal/year for 4 occupants × 50 gal/day</td></tr><tr><td>Annual deficit</td><td>~7,000 gal/year, covered by backup well</td></tr><tr><td>Cistern capacity</td><td>5,000 gal</td></tr><tr><td>Storage at peak demand</td><td>~25 days</td></tr><tr><td>Rainwater contribution</td><td>~91% of annual demand</td></tr>
</tbody></table>
<div class="callout"><strong>Engineering interpretation:</strong> Lafayette rainfall makes rainwater harvesting viable, but not perfectly sufficient at the selected household water demand. The backup well is therefore not a convenience; it is a defined resilience component.</div>
</section>

<section id="safety">
<h2>10. Redundancy and safety</h2>
<div class="grid three"><div class="card"><h3>Electrical protection</h3><ul><li>BMS monitors per-cell voltage and temperature.</li><li>BMS balances cells and protects the battery bank.</li><li>Smart panel sheds non-critical loads at low SOC.</li></ul></div><div class="card"><h3>Water safety</h3><ul><li>UV sterilizer plus carbon filtration on potable water.</li><li>Backup well as secondary source.</li><li>Water quality testing is part of commissioning.</li></ul></div><div class="card"><h3>Operational resilience</h3><ul><li>3-day battery autonomy covers typical cloudy stretches.</li><li>14 kW propane generator is emergency backup.</li><li>Target generator runtime is less than 50 hr/year.</li></ul></div></div>
</section>

<section id="validation">
<h2>11. Validation and testing plan</h2>
<div class="grid two"><div class="card"><h3>Pre-build simulation</h3><ul><li>Manual J load calculation for formal HVAC sizing.</li><li>8,760-hour energy balance simulation in NREL SAM or HOMER Pro.</li><li>Statistical worst-case PSH analysis using Lafayette TMY3 data.</li></ul></div><div class="card"><h3>Commissioning and operation</h3><ul><li>12-month inverter telemetry log using Sol-Ark cloud gateway.</li><li>Sub-meter CTs on HVAC, DHW, plug loads, and pumps.</li><li>Quarterly water quality testing for coliforms, pH, TDS, and turbidity.</li></ul></div></div>
<p><strong>Key performance indicators:</strong> predicted vs. actual kWh/month, battery depth-of-discharge distribution, and generator runtime hours.</p>
</section>

<section id="cost">
<h2>12. Cost estimate</h2>
<table><thead><tr><th>Component</th><th>Capital cost</th></tr></thead><tbody>
<tr><td>14 kW PV array, panels + racking + install</td><td>~$42,000</td></tr>
<tr><td>210 kWh LFP battery bank</td><td>~$150,000–190,000</td></tr>
<tr><td>Sol-Ark 15K hybrid inverter + balance of system</td><td>~$15,000</td></tr>
<tr><td>14 kW propane standby generator + transfer equipment</td><td>~$8,000</td></tr>
<tr><td>Water system: cistern, pumps, filtration, UV</td><td>~$12,000</td></tr>
<tr><td><strong>Capital total</strong></td><td><strong>~$227,000–267,000</strong></td></tr>
</tbody></table>
<div class="callout warning"><strong>Economic result:</strong> the system is technically feasible but economically marginal in Louisiana. The battery bank dominates first cost, and a grid-tied solar-plus-battery system remains much cheaper if full utility independence is not required.</div>
</section>

<section id="conclusion">
<h2>13. Conclusions</h2>
<ul><li>The system is technically feasible using commercially available components.</li><li>The design is sized to handle Lafayette weather year-round without routine generator runtime.</li><li>Predicted consumption is about 9,490 kWh/year, roughly below the Louisiana average stated in the PowerPoint.</li><li>The original Earthship concept does not transplant cleanly to Louisiana without major changes.</li><li>Hot-humid conditions force active HVAC and dehumidification.</li><li>Indoor planters should be avoided or heavily limited because they add humidity load.</li><li>Berming is avoided because saturated soils and flood risk make it inappropriate for the design basis.</li></ul>
<div class="callout good"><strong>Final position:</strong> this is best understood as a Louisiana-adapted, Earthship-inspired off-grid residence: resilient, self-contained, and climate-aware, but not passive-only and not economically optimized for short payback.</div>
</section>

<section id="references">
<h2>Selected references from the PowerPoint</h2>
<ul class="refs"><li>ASHRAE 169-2020, Climatic Data for Building Design Standards.</li><li>NREL PVWatts Version 5 Manual, Dobos 2014, NREL/TP-6A20-62641.</li><li>NREL UL Lafayette solar measurement station, DOI 10.7799/2301601.</li><li>NREL National Solar Radiation Database / TMY3 Lafayette.</li><li>NWS Lake Charles Forecast Office, Lafayette Climate Information, 1991–2020 normals.</li><li>U.S. EIA Residential Energy Consumption Survey, 2020.</li><li>NEC 2023: NFPA 70 Articles 690, 705, and 285.</li><li>NFPA 855, stationary energy storage systems.</li><li>ASCE 7-22, Minimum Design Loads for Buildings and Structures.</li><li>IECC 2021, Climate Zone 2A envelope provisions.</li><li>ENERGY STAR Single-Family New Homes Program v3.2.</li><li>DOE Building America hot-humid climate guidance.</li><li>Building Science Corporation BSI-001 and BSI-096.</li><li>ACCA Manual J, 8th Edition.</li><li>ASHRAE 62.2-2022 residential ventilation.</li><li>EnergySage 2026 Louisiana solar market data.</li><li>Manufacturer datasheets: Sol-Ark, Q CELLS, FranklinWH, EG4, IronRidge, Generac.</li><li>Reynolds, M., Earthship Volumes I–III.</li><li>Freney, Soebarto, and Williamson, ASME Energy Sustainability Conference, 2007.</li><li>American Rainwater Catchment Systems Association standards.</li><li>Louisiana State Sanitary Code and local cistern requirements.</li></ul>
</section>
</div>
<footer class="footer">Louisiana Off-Grid Earthship Systems · Updated HTML report based on the uploaded MCHE 358 PowerPoint · Prepared for Google Sites / webpage embedding.</footer>
</main>
</body>
</html>
