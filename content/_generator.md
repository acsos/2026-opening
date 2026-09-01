
+++

title = "ACSOS 2026 - Opening Ceremony"
description = "Acsos 2026 Opening"
outputs = ["Reveal"]

+++

{{< slide background-video="tesori-shorter-zoom-lr.mp4" background-video-loop="true" background-video-muted="true" background-opacity="0.95">}}

<img src="animations/acsos-logo-2026.svg"
style="width:35em" />

# Welcome to Cesena

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

<div style="font-family:inherit; width:96%; margin:0 auto; color:#f7fbff;">
  <h1 style="margin:0 0 .15em; font-size:1.9em; letter-spacing:.04em;">Two streams. One community.</h1>
  <div style="display:grid; grid-template-columns:1fr 1.05fr 1fr; gap:1.8em; align-items:center; position:relative;">
    <div style="position:absolute; left:30%; right:30%; top:50%; height:3px; background:linear-gradient(90deg,#48c6ef,#f6d365,#48c6ef); opacity:.8;"></div>
    <div style="position:absolute; left:31%; top:calc(50% - .35em); color:#ffe5a3; font-size:1em; z-index:3;">➜</div>
    <div style="position:absolute; right:31%; top:calc(50% - .35em); color:#ffe5a3; font-size:1em; z-index:3; transform:rotate(180deg);">➜</div>
    <div style="text-align:left; position:relative; z-index:1;">
      <div style="display:inline-block; padding:.18em .55em; border-radius:999px; background:#1677a8; font-weight:bold; font-size:.8em;">ICAC</div>
      <div style="margin-top:.25em; padding:.42em .55em; border-left:3px solid #48c6ef; background:rgba(16,48,81,.8); font-size:.9em; line-height:1.2;">
        <div><b>2004</b> · New York, NY, USA</div><div><b>2005</b> · Seattle, WA, USA</div><div><b>2006</b> · Dublin, Ireland</div><div><b>2007</b> · Jacksonville, FL, USA</div><div><b>2008</b> · Chicago, IL, USA</div><div><b>2009</b> · Barcelona, Spain</div><div><b>2010</b> · Washington, DC, USA</div><div><b>2011</b> · Karlsruhe, Germany</div><div><b>2012</b> · San Jose, CA, USA</div><div><b>2013</b> · San Jose, CA, USA</div><div><b>2014</b> · Philadelphia, PA, USA</div><div><b>2015</b> · Grenoble, France</div><div><b>2016</b> · Würzburg, Germany</div><div><b>2017</b> · Columbus, Ohio, USA</div><div><b>2018</b> · Trento, Italy</div><div><b>2019</b> · Umeå, Sweden</div>
      </div>
    </div>
    <div style="position:relative; z-index:2; text-align:center;">
      <div style="margin:auto; width:5.8em; height:5.8em; border-radius:50%; display:flex; align-items:center; justify-content:center; background:radial-gradient(circle at 35% 30%,#ffe082,#e89436 65%,#bb5a35); box-shadow:0 0 0 .12em rgba(255,224,130,.35), 0 0 1.2em rgba(255,190,80,.45); color:#17324d; font-size:1em; font-weight:900; letter-spacing:.04em;">ACSOS</div>
      <div style="position:relative; z-index:4; display:inline-block; margin-top:.35em; padding:.12em .28em; border-radius:.22em; background:rgba(8,59,111,.96); color:#ffe5a3; font-size:1em; font-weight:bold;">Autonomic Computing &amp;<br>Self-Organizing Systems</div>
      <div style="margin:.7em auto 0; padding:.5em .7em; border-top:2px solid rgba(255,224,130,.65); border-bottom:2px solid rgba(255,224,130,.65); text-align:left; background:rgba(255,255,255,.08); font-size:.85em; line-height:1.3; white-space:nowrap;">
        <div><b>2020</b> · <s>Washington D.C.</s> · Virtual</div>
        <div><b>2021</b> · <s>Washington D.C.</s> · Virtual</div>
        <div><b>2022</b> · Virtual</div>
        <div><b>2023</b> · Toronto, Canada</div>
        <div><b>2024</b> · Aarhus, Denmark</div>
        <div><b>2025</b> · Tokyo, Japan</div>
        <div><b>2026</b> · <span style="color:#ffe5a3; font-weight:bold;">Cesena, Italy</span></div>
      </div>
    </div>
    <div style="text-align:left; position:relative; z-index:1;">
      <div style="display:inline-block; padding:.18em .55em; border-radius:999px; background:#7046a3; font-weight:bold; font-size:.8em;">SASO</div>
      <div style="margin-top:.25em; padding:.42em .55em; border-left:3px solid #c59bff; background:rgba(42,33,76,.8); font-size:.9em; line-height:1.2;">
        <div><b>2007</b> · Boston, MA, USA</div><div><b>2008</b> · Venice, Italy</div><div><b>2009</b> · San Francisco, CA, USA</div><div><b>2010</b> · Budapest, Hungary</div><div><b>2011</b> · Ann Arbor, MI, USA</div><div><b>2012</b> · Lyon, France</div><div><b>2013</b> · Philadelphia, PA, USA</div><div><b>2014</b> · London, UK</div><div><b>2015</b> · Cambridge, MA, USA</div><div><b>2016</b> · Augsburg, Germany</div><div><b>2017</b> · Tucson, AZ, USA</div><div><b>2018</b> · Trento, Italy</div><div><b>2019</b> · Umeå, Sweden</div>
      </div>
    </div>
  </div>
</div>

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

<style>
  .cesena-carousel {
    display: flex;
    align-items: center;
    justify-content: space-around;
    gap: .6em;
    width: 82%;
    height: 5.5em;
    margin: -.1em auto .45em;
    border-radius: .45em;
    background: rgba(255,255,255,.7);
    overflow: hidden;
  }
  .cesena-carousel img {
    flex: 1 1 0;
    min-width: 0;
    width: 0;
    height: 100%;
    max-height: 100%;
    margin: 0;
    padding: .35em;
    box-sizing: border-box;
    object-fit: contain;
  }
  .cesena-carousel img:nth-child(3) { max-height: 100%; }
  .cesena-carousel img:nth-child(4) { max-height: 100%; }
</style>
<div class="cesena-carousel" aria-label="ACSOS in Cesena partners">
  <img src="ieee-cs.png" alt="IEEE Computer Society" />
  <img src="Cesena+DISI_pos.png" alt="Cesena and DISI" />
  <img src="comune.png" alt="Comune di Cesena" />
  <img src="serinar.png" alt="Ser.In.Ar." />
</div>

# ACSOS in Cesena

* A campus of the **University of Bologna** in *Romagna*
* Hosts about one third of the **Department of Computer Science and Engineering**
* Home of several ACSOS/SASO contributors
* Recent and modern infrastructure
* Cesena hosted a hybrid *IEEE ACSOS special event* in 2022
    * three speakers
    * rich social program

![](https://2026.acsos.org/getImage/orig/rocca+%281%29.png)
![](https://2026.acsos.org/getImage/orig/piazza+far+%281%29.png)
![](https://2026.acsos.org/getImage/orig/bonci+%281%29.png)
![](https://2026.acsos.org/getImage/orig/abazzia+%281%29.png)

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Moving in the Campus, floor 1

<div style="display:inline-block; background:rgba(255,255,255,.85); padding:.5em; border-radius:.5em;">

![](floor1.svg)

</div>

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Moving in the Campus, floor 0

<div style="display:block; width:fit-content; margin:0 auto; background:rgba(255,255,255,.9); padding:.1em; border-radius:.5em; transform:scale(1.05); transform-origin:center;">

<img src="floor0.svg" alt="Floor 0 map" style="display:block;" />

</div>

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Finding electricity plugs

![](seats.jpg)

* Plugs are located every five seats or so, look at the bottom-right of your seat
    * Plugs are Italian "Bipasso", also compatible with German plugs

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Malatestiana Library Visit

![](https://static-www.comune.cesena.fc.it/wp-content/uploads/2023/09/biblioteca_malatestiana_antica.png.webp)

### *Wednesday*, **18:00** (turn 1) and **19:00** (turn 2)

* Malatestiana Library visits are **limited**!
* We secured *50* places, allocated to the first 50 people who registered *and* expressed interest
    * If you are among the lucky ones, you'll find a **ticket in your badge**
    * The *first 25* registrants have been allocated to *turn 1*, the **other 25** to **turn 2**
* Tickets are *not nominal*:
    * You can *swap* tickets with someone else
    * You can *give away* your ticket
    * If you change your mind and no longer wish to visit the Malatestiana, please consider giving away your ticket!


---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Conference dinner and award ceremony

### *Wednesday*, **19:00** to **02:00**

<div style="display:flex; flex-direction:row; flex-wrap:nowrap; gap:1em; align-items:center; justify-content:center; width:100%;">
  <img src="https://2026.acsos.org/getImage/orig/msg1097443369-2716.jpg" alt="Teatro Verdi interior" style="display:block; flex:0 0 48%; width:48%; height:16em; object-fit:contain; background:#fff0;" />
  <img src="https://2026.acsos.org/getImage/orig/_MG_0090.jpg" alt="Teatro Verdi venue" style="display:block; flex:0 0 48%; width:48%; height:16em; object-fit:contain; background:#fff0;" />
</div>

* Teatro Verdi, Cesena
    * In the city center, a *half-hour* walk from the Campus
* **Aperitivo** starts at 19:00
* The **three-course dinner** will be served afterwards
    * *Around* 20:20
    * we will allow enough time for those visiting the Malatestiana Library to join
* After dinner, the stage will become a **dance floor**
    * Open bar available

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Reaching Teatro Verdi

<div style="text-align: center;"> 
    <iframe src="https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d11229.017523034237!2d12.23174566336883!3d44.141620135874646!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e2!4m5!1s0x132ca5001772debd%3A0x793506a75e8e1a42!2sUniversit%C3%A0%20di%20Bologna%20-%20Campus%20di%20Cesena%2C%2047521%20Cesena%20FC%2C%20Italia!3m2!1d44.1478167!2d12.235488799999999!4m5!1s0x132ca4c9fa8d80c3%3A0xfd0d08ff05861f90!2sTeatro%20Verdi%2C%20Via%20Luigi%20Sostegni%2C%2013%2C%2047521%20Cesena%20FC%2C%20Italia!3m2!1d44.135393699999995!2d12.2485599!5e1!3m2!1ses-419!2sco!4v1783950745972!5m2!1ses-419!2sco" width="1500" height="900" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="strict-origin-when-cross-origin"></iframe>
</div> 

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Additional Social events

<div style="width:70%; height:12em; margin:0 auto; overflow:hidden; line-height:0;">
  <img src="https://github.com/acsos/acsos2026/blob/main/acsos-ase-lr.png?raw=true" alt="ACSOS ASE image" style="display:block; width:100%; height:100%; object-fit:cover; object-position:center 35%;" />
</div>

{{% multicol %}}
{{% col %}}
* *Today*: **Wine**, Views, and Dinner on Romagna’s Balcony
    * Wine tasting and dinner in Bertinoro
    * A bus will pick up participants right from the campus at the end of the last session
{{% /col %}}
{{% col %}}
* *Thursday*: **ACSOS GP** on the Riviera: Racing & Dinner
    * Kart racing in Riccione
    * Non-racing Riccione walk option
    * Dinner in Rimini at Bounty
{{% /col %}}
{{% col %}}
* *Friday*: Along Leonardo’s Canal: **Cesenatico** and Fish Dinner
    * Visit to the maritime museum
    * Visit to Leonardo's Canal and Cesenatico city center
    * Fish dinner near the beach
        * Meat and veggy options avail.
{{% /col %}}
{{% /multicol %}}

<div style="position:absolute; left:8%; right:40%; bottom:-8em; z-index:5; display:flex; align-items:center; justify-content:space-around; gap:2em;">
  <div style="flex:1; text-align:right; font-size:1.15em;">
    <b>Register at:</b><br />
    <span style="font-size:.8em;">serinarpayments.it/acsos-2026/</span>
  </div>
  <div style="flex:0 0 auto; padding:.1em; background:rgba(255,255,255,.95); border-radius:.5em;">
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=500x500&amp;data=https%3A%2F%2Fserinarpayments.it%2Facsos-2026%2F" alt="QR code for Ser.In.Ar. ACSOS 2026 registration" style="display:block; width:7em; height:7em;" />
  </div>
</div>

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# ACSOS 2026 Social Coordination via Telegram

<div style="display:flex; align-items:center; justify-content:space-around; gap:2em; width:90%; margin:1em auto 0;">
  <div style="flex:1; text-align:center;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Telegram_logo.svg" alt="Telegram logo" style="display:block; width:12em; height:12em; margin:0 auto .6em;" />
    <div style="font-size:1.25em; font-weight:700;">https://t.me/+u-8V_NYXBpo1MWY0</div>
  </div>
  <div style="flex:1; text-align:center;">
    <div style="display:inline-block; padding:.6em; background:rgba(255,255,255,.95); border-radius:.5em;">
      <img src="https://api.qrserver.com/v1/create-qr-code/?size=500x500&amp;data=https%3A%2F%2Ft.me%2F%2Bu-8V_NYXBpo1MWY0" alt="QR code for the ACSOS Social Coordination Group" style="display:block; width:11em; height:11em;" />
    </div>
  </div>
</div>

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Pics, or didn't happen

<div style="display:flex; align-items:center; justify-content:space-around; gap:2em; width:90%; margin:1em auto 0;">
  <div style="flex:1; text-align:center;">
    <img src="https://logos-world.net/wp-content/uploads/2022/05/Google-Photos-Logo.png" alt="Google Photos logo" style="display:block; width:20em; height:20em; margin:0 auto .6em;" />
    <div style="font-size:1.15em; font-weight:700;">https://photos.app.goo.gl/S2NSXuZUPYkGQfLo6</div>
  </div>
  <div style="flex:1; text-align:center;">
    <div style="display:inline-block; padding:.6em; background:rgba(255,255,255,.95); border-radius:.5em;">
      <img src="https://api.qrserver.com/v1/create-qr-code/?size=500x500&amp;data=https%3A%2F%2Fphotos.app.goo.gl%2FS2NSXuZUPYkGQfLo6" alt="QR code for ACSOS 2026 photos" style="display:block; width:11em; height:11em;" />
    </div>
  </div>
</div>


---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}
<img src="acsos-logo-cesena.svg"
alt="ACSOS 2026 logo"
style="position:absolute; top:-0.5em; right:0em; width:25vmin; z-index:10; pointer-events:none;" />

# Program at a glance

<style>
  /* Center the Researchr page title ("Program at a Glance"). */
  h1 {
    text-align: center;
  }

.acsos-program {
    --blue:#366092;
    --grid:#a9a9a9;
    --break:#f2f2f2;
    --main:#ffe599;
    --keynote:#b1ed39;
    --workshop:#c9daf8;
    --special:#f4cccc;
    --social:#ffffff;
    --panel:#dbe5f1;
    --phd:#f9cb9c;
    --poster:#b4a7d6;
    --tutorial:#bbd6a7;

    width: 100%;
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica, sans-serif;
    color: #111;
    background: #fff;
  }

  .acsos-program,
  .acsos-program * {
    box-sizing: border-box;
  }

  .acsos-program h1 {
    margin: 0 0 8px;
    text-align: center;
    color: var(--blue);
    font-size: 34px;
    letter-spacing: .2px;
  }

  .acsos-program .subtitle {
    margin: 0 0 22px;
    text-align: center;
    color: #555;
    font-size: 17px;
    font-style: italic;
  }

  .acsos-program table.program {
    width: 100%;
    border-collapse: collapse;
    table-layout: fixed;
    font-size: 15px;
  }

  .acsos-program .program th,
  .acsos-program .program td {
    border: 1px solid var(--grid);
    padding: 7px 8px;
  }

  .acsos-program .program th {
    height: 52px;
    color: #fff;
    background: var(--blue);
    text-align: center;
    font-weight: 700;
    font-size: 18px;
  }

  .acsos-program .program th .date {
    display: block;
    margin-top: 3px;
    font-size: 13px;
    font-weight: 400;
    opacity: .9;
  }

  .acsos-program .program td.time {
    width: 118px;
    text-align: right;
    vertical-align: middle;
    font-size: 18px;
    font-weight: 700;
    color: #333;
    background: #fff;
    white-space: nowrap;
  }

  .acsos-program .program td.event {
    text-align: center;
    vertical-align: middle;
    font-weight: 600;
    line-height: 1.25;
  }

  .acsos-program .program td.event .minor {
    display: block;
    margin-top: 4px;
    font-size: 12px;
    font-weight: 400;
  }

  .acsos-program .program td.event .room {
    display: block;
    margin-top: 4px;
    font-size: 11px;
    font-weight: 400;
    color: #666;
    line-height: 1.2;
  }

  .acsos-program .break { background: var(--break); font-style: italic; font-weight: 400 !important; }
  .acsos-program .main { background: var(--main); }
  .acsos-program .keynote { background: var(--keynote); }
  .acsos-program .workshop { background: var(--workshop); }
  .acsos-program .special { background: var(--special); }
  .acsos-program .social { background: var(--social); }
  .acsos-program .panel { background: var(--panel); }
  .acsos-program .phd { background: var(--phd); }
  .acsos-program .poster { background: var(--poster); color: #111; }
  .acsos-program .poster-break {
    background: linear-gradient(to top right, var(--break) 0 49.5%, var(--poster) 50.5% 100%);
    color: #111;
  }
  .acsos-program .tutorial { background: var(--tutorial); }
  .acsos-program .blank { background: #fff; color: #999; font-weight: 400 !important; }

  .acsos-program .evening td {
    height: 64px;
  }

  .acsos-program .legend {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 8px 14px;
    margin-top: 18px;
    font-size: 13px;
  }

  .acsos-program .legend > span {
    display: inline-flex;
    align-items: center;
    gap: 6px;
  }

  .acsos-program .swatch {
    width: 18px;
    height: 13px;
    flex: 0 0 18px;
    border: 1px solid #888;
    border-radius: 0 !important;
    box-shadow: none !important;
    padding: 0 !important;
    margin: 0;
    display: inline-block;
    line-height: 0;
  }

  .acsos-program .footnote {
    margin-top: 14px;
    text-align: center;
    font-size: 12px;
    color: #666;
  }

  .acsos-program .table-responsive {
    width: 100%;
    overflow-x: auto;
    overflow-y: hidden;
    -webkit-overflow-scrolling: touch;
    border: 1px solid var(--grid);
  }

  .acsos-program .table-responsive .program {
    min-width: 980px;
    border: 0;
  }

  .acsos-program .table-responsive .program th:first-child,
  .acsos-program .table-responsive .program td:first-child {
    border-left: 0;
  }

  .acsos-program .table-responsive .program th:last-child,
  .acsos-program .table-responsive .program td:last-child {
    border-right: 0;
  }

  @media (max-width: 768px) {
    .acsos-program h1 {
      font-size: 27px;
      line-height: 1.15;
    }

    .acsos-program .subtitle {
      margin-bottom: 16px;
      font-size: 14px;
      line-height: 1.4;
    }

    .acsos-program .table-responsive {
      position: relative;
      margin: 0 -2px;
    }

    .acsos-program .table-responsive .program {
      min-width: 900px;
      font-size: 13px;
    }

    .acsos-program .program th {
      height: 46px;
      padding: 6px;
      font-size: 15px;
    }

    .acsos-program .program th .date {
      font-size: 11px;
    }

    .acsos-program .program th,
    .acsos-program .program td {
      padding: 6px;
    }

    .acsos-program .program td.time {
      width: 100px;
      font-size: 12px;
    }

    .acsos-program .program td.event {
      line-height: 1.2;
    }

    .acsos-program .program td.event .minor {
      font-size: 11px;
    }

    .acsos-program .program td.event .room {
      font-size: 10px;
      font-weight: 400;
    }

    .acsos-program .legend {
      gap: 8px 12px;
      font-size: 12px;
    }

    .acsos-program .footnote {
      font-size: 11px;
      line-height: 1.4;
    }
  }

  @media (max-width: 480px) {
    .acsos-program h1 {
      font-size: 23px;
    }

    .acsos-program .subtitle {
      font-size: 13px;
    }

    .acsos-program .table-responsive .program {
      min-width: 820px;
      font-size: 12px;
    }

    .acsos-program .program th {
      font-size: 14px;
    }

    .acsos-program .program td.time {
      width: 92px;
      font-size: 11px;
    }

    .acsos-program .legend {
      justify-content: flex-start;
    }
  }
</style>

<div class="acsos-program">
<div class="table-responsive">
    <table class="program">
        <colgroup>
            <col style="width:8%">
            <col style="width:18.4%">
            <col style="width:18.4%">
            <col style="width:18.4%">
            <col style="width:18.4%">
            <col style="width:18.4%">
        </colgroup>
        <thead>
            <tr>
            <th></th>
            <th>Monday<span class="date">7 September</span></th>
            <th>Tuesday<span class="date">8 September</span></th>
            <th>Wednesday<span class="date">9 September</span></th>
            <th>Thursday<span class="date">10 September</span></th>
            <th>Friday<span class="date">11 September</span></th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td class="time">09:00–09:30</td>
                <td class="event main">Registration</td>
                <td class="event main">Opening<span class="room">Aula Magna</span></td>
                <td class="event keynote" rowspan="2">Keynote<span class="minor">Marco Dorigo</span><span class="room">Aula Magna</span></td>
                <td class="event keynote" rowspan="2">Keynote<span class="minor">Ivona Brandic</span><span class="room">Aula Magna</span></td>
                <td class="event workshop" rowspan="4">Workshops<span class="minor">AICR-ACS · SISSY</span><span class="room">AICR-ACS: 2.3 · SISSY: 2.4</span></td>
            </tr>
            <tr>
                <td class="time">09:30–10:00</td>
                <td class="event workshop" rowspan="3">Workshops<span class="minor">SaSSO4 · AI4AS</span><span class="room">SaSSO4: 2.10 · AI4AS: 2.4</span></td>
                <td class="event keynote">Keynote<span class="minor">Valeria Cardellini</span><span class="room">Aula Magna</span></td>
            </tr>
            <tr>
                <td class="time">10:00–10:30</td>
                <td class="event main" rowspan="2">Main-track session<span class="room">Aula Magna</span></td>
                <td class="event main" rowspan="2">Main-track session<span class="room">Aula Magna</span></td>
                <td class="event main" rowspan="2">Main-track session<span class="room">Aula Magna</span></td>
            </tr>
            <tr>
                <td class="time">10:30–11:00</td>
            </tr>
            <tr>
                <td class="time">11:00–11:30</td>
                <td class="event break">Coffee break<span class="room">2.13</span></td>
                <td class="event break">Coffee break<span class="room">2.13</span></td>
                <td class="event break">Coffee break<span class="room">2.13</span></td>
                <td class="event break">Coffee break<span class="room">2.13</span></td>
                <td class="event break">Coffee break<span class="room">2.13</span></td>
            </tr>
            <tr>
                <td class="time">11:30–12:00</td>
                <td class="event workshop" rowspan="3">Workshops<span class="minor">SaSSO4 · AI4AS</span><span class="room">SaSSO4: 2.10 · AI4AS: 2.4</span></td>
                <td class="event main" rowspan="3">Main-track session<span class="room">Aula Magna</span></td>
                <td class="event main" rowspan="3">Main-track session<span class="room">Aula Magna</span></td>
                <td class="event main" rowspan="3">Main-track session<span class="room">Aula Magna</span></td>
                <td class="event workshop" rowspan="3">Workshops<span class="minor">AICR-ACS · SISSY</span><span class="room">AICR-ACS: 2.3 · SISSY: 2.4</span></td>
            </tr>
            <tr>
                <td class="time">12:00–12:30</td>
            </tr>
            <tr>
                <td class="time">12:30–13:00</td>
            </tr>
            <tr>
                <td class="time">13:00–13:30</td>
                <td class="event break" rowspan="2">Lunch<span class="room">Sala Polivalente</span></td>
                <td class="event break" rowspan="2">Lunch<span class="room">Sala Polivalente</span></td>
                <td class="event poster-break" rowspan="2">Lunch &amp; Posters<span class="room">Lunch: Sala Polivalente · Posters: 2.3</span></td>
                <td class="event poster-break" rowspan="2">Lunch &amp; Posters<span class="room">Lunch: Sala Polivalente · Posters: 2.3</span></td>
                <td class="event break" rowspan="2">Lunch<span class="room">Sala Polivalente</span></td>
            </tr>
            <tr>
                <td class="time">13:30–14:00</td>
            </tr>
            <tr>
                <td class="time">14:00–14:30</td>
                <td class="event tutorial" rowspan="3">Tutorials 1 &amp; 2<span class="minor">SaSSO4 also running</span><span class="room">T1: 2.3 · T2: 2.4 · SaSSO4: 2.10</span></td>
                <td class="event keynote" rowspan="2">Keynote<span class="minor">Carlo Ghezzi</span><span class="room">Aula Magna</span></td>
                <td class="event main" rowspan="4">Main-track session<span class="room">Aula Magna</span></td>
                <td class="event main" rowspan="4">Main-track session<span class="room">Aula Magna</span></td>
                <td class="event workshop" rowspan="3">Workshops<span class="minor">AICR-ACS · SISSY</span><span class="room">AICR-ACS: 2.3 · SISSY: 2.4</span></td>
            </tr>
            <tr>
                <td class="time">14:30–15:00</td>
            </tr>
            <tr>
                <td class="time">15:00–15:30</td>
                <td class="event phd">PhD flash talks<span class="room">Aula Magna</span></td>
            </tr>
            <tr>
                <td class="time">15:30–16:00</td>
                <td class="event break">Coffee break<span class="room">2.13</span></td>
                <td class="event poster">Poster flash talks<span class="room">Aula Magna</span></td>
                <td class="event break">Coffee break<span class="room">2.13</span></td>
            </tr>
            <tr>
                <td class="time">16:00–16:30</td>
                <td class="event tutorial" rowspan="3">Tutorials 3 &amp; 4<span class="minor">SaSSO4 also running</span><span class="room">T3: 2.3 · T4: 2.4 · SaSSO4: 2.10</span></td>
                <td class="event poster-break">Coffee break &amp; Posters<span class="room">Coffee: 2.13 · Posters: 2.3</span></td>
                <td class="event poster-break">Coffee break &amp; Posters<span class="room">Coffee: 2.13 · Posters: 2.3</span></td>
                <td class="event poster-break">Coffee break &amp; Posters<span class="room">Coffee: 2.13 · Posters: 2.3</span></td>
                <td class="event workshop" rowspan="4">Workshops<span class="minor">AICR-ACS · SISSY</span><span class="room">AICR-ACS: 2.3 · SISSY: 2.4</span></td>
            </tr>
            <tr>
                <td class="time">16:30–17:00</td>
                <td class="event main" rowspan="3">Main-track session<span class="room">Aula Magna</span></td>
                <td class="event panel" rowspan="2">ACSOS in Practice / Doctoral Symposium breakouts<span class="room">In Practice: Aula Magna · DS: 2.3 / 2.4</span></td>
                <td class="event panel" rowspan="2">Expert Panel / Doctoral Symposium breakouts<span class="room">Panel: Aula Magna · DS: 2.3 / 2.4</span></td>
            </tr>
            <tr>
                <td class="time">17:00–17:30</td>
            </tr>
            <tr>
                <td class="time">17:30–18:00</td>
                <td class="event blank">—</td>
                <td class="event special">Malatestiana library visit<span class="room">Biblioteca Malatestiana</span></td>
                <td class="event main">Closing<span class="room">Aula Magna</span></td>
            </tr>
            <tr class="evening">
                <td class="time">Evening</td>
                <td class="event social"><a href="https://2026.acsos.org/attending/welcome-reception">Welcome Reception</a><span class="room">Rocca Malatestiana</span></td>
                <td class="event social"><a href="https://2026.acsos.org/attending/social-events">Additional SE: Wine Tasting &amp; Dinner in Bertinoro</a><span class="room">Bertinoro · off-site</span></td>
                <td class="event social"><a href="https://2026.acsos.org/attending/main-social-event">Banquet at Teatro Verdi</a><span class="room">Teatro Verdi</span></td>
                <td class="event social"><a href="https://2026.acsos.org/attending/social-events">Additional SE: Kart Race in Riccione &amp; Dinner in Rimini</a><span class="room">Riccione / Rimini · off-site</span></td>
                <td class="event social"><a href="https://2026.acsos.org/attending/social-events">Additional SE: Visit to Cesenatico &amp; Fish Dinner on the beach</a><span class="room">Cesenatico · off-site</span></td>
            </tr>
        </tbody>
    </table>
</div>
<div class="legend">
  <span><span class="swatch keynote" aria-hidden="true"></span>Keynote</span>
  <span><span class="swatch main" aria-hidden="true"></span>Main track</span>
  <span><span class="swatch workshop" aria-hidden="true"></span>Workshop</span>
  <span><span class="swatch tutorial" aria-hidden="true"></span>Tutorial</span>
  <span><span class="swatch phd" aria-hidden="true"></span>Doctoral Symposium</span>
  <span><span class="swatch poster" aria-hidden="true"></span>Posters / demos</span>
  <span><span class="swatch poster-break" aria-hidden="true"></span>Posters + break / lunch</span>
  <span><span class="swatch panel" aria-hidden="true"></span>Panel / in-practice</span>
  <span><span class="swatch special" aria-hidden="true"></span>Special event</span>
  <span><span class="swatch break" aria-hidden="true"></span>Break / lunch</span>
</div>
</div>

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Keynote speakers

<div style="display:grid; grid-template-columns:repeat(4, 1fr); gap:1em; width:97%; margin:.4em auto 0; font-family:inherit;">
  <div style="padding:.5em .6em; border-top:5px solid #f6d365; border-radius:.35em; background:rgba(66,54,27,.5); text-align:center; min-height:20em;">
    <div style="margin-bottom:.35em; color:#ffe5a3; font-size:.72em; font-weight:bold;">Tuesday · 09:10–10:00<br><span style="font-size:.9em;">main track keynote</span></div>
    <img src="https://2026.acsos.org/getImage/orig/valeria.jpg" alt="Valeria Cardellini" style="width:8em; height:8em; object-fit:cover; border-radius:50%; border:4px solid #f6d365;">
    <h3 style="margin:.35em 0 .1em; font-size:1.15em;">Valeria Cardellini</h3>
    <div style="font-size:.7em; color:#f8e5a6;">Tor Vergata University of Rome</div>
    <p style="margin:.8em 0 0; font-size:.78em; line-height:1.25; color:#ffe5a3;"><b>Adaptive Serverless Computing Across the Cloud-Edge Continuum</b></p>
  </div>
  <div style="padding:.5em .6em; border-top:5px solid #48c6ef; border-radius:.35em; background:rgba(16,48,81,.5); text-align:center; min-height:20em;">
    <div style="margin-bottom:.35em; color:#ffe5a3; font-size:.72em; font-weight:bold;">Wednesday · 09:00–10:00<br><span style="font-size:.9em;">main track keynote</span></div>
    <img src="https://2026.acsos.org/getImage/orig/IMG_6111.jpeg" alt="Marco Dorigo" style="width:8em; height:8em; object-fit:cover; border-radius:50%; border:4px solid #48c6ef;">
    <h3 style="margin:.35em 0 .1em; font-size:1.15em;">Marco Dorigo</h3>
    <div style="font-size:.7em; color:#b9d7ee;">Université Libre de Bruxelles</div>
    <p style="margin:.8em 0 0; font-size:.78em; line-height:1.25; color:#ffe5a3;"><b>Bridging Centralized and Decentralized Control in Robot Swarms through Self-Organizing Hierarchies</b></p>
  </div>
  <div style="padding:.5em .6em; border-top:5px solid #c59bff; border-radius:.35em; background:rgba(42,33,76,.5); text-align:center; min-height:20em;">
    <div style="margin-bottom:.35em; color:#ffe5a3; font-size:.72em; font-weight:bold;">Thursday · 09:00–10:00<br><span style="font-size:.9em;">main track keynote</span></div>
    <img src="https://2026.acsos.org/getImage/orig/Ivona_2015.jpg" alt="Ivona Brandic" style="width:8em; height:8em; object-fit:cover; border-radius:50%; border:4px solid #c59bff;">
    <h3 style="margin:.35em 0 .1em; font-size:1.15em;">Ivona Brandic</h3>
    <div style="font-size:.7em; color:#d9c7ff;">TU Wien</div>
    <p style="margin:.8em 0 0; font-size:.78em; line-height:1.25; color:#ffe5a3;"><b>Bridging Classical and Quantum Computing: Lessons, Challenges, and Opportunities</b></p>
  </div>
  <div style="padding:.5em .6em; border-top:5px solid #8ee3a8; border-radius:.35em; background:rgba(24,67,53,.5); text-align:center; min-height:20em;">
    <div style="margin-bottom:.35em; color:#ffe5a3; font-size:.72em; font-weight:bold;">Tuesday · 14:00–15:00<br><span style="font-size:.9em;">doctoral symposium keynote</span></div>
    <img src="https://www.deib.polimi.it/allegati/peopledeib/528646/foto.jpg" alt="Carlo Ghezzi" style="width:8em; height:8em; object-fit:cover; border-radius:50%; border:4px solid #8ee3a8;">
    <h3 style="margin:.35em 0 .1em; font-size:1.15em;">Carlo Ghezzi</h3>
    <div style="font-size:.7em; color:#bfe8cc;">Politecnico di Milano</div>
    <p style="margin:.8em 0 0; font-size:.78em; line-height:1.25; color:#ffe5a3;"><b>Being a researcher — in turbulent times</b></p>
  </div>
</div>

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Thank you, Organizing committee!

<style>.organizing-committee img { width:6.5em !important; height:6.5em !important; }</style>
<div class="organizing-committee" style="display:grid; grid-template-columns:repeat(8, 1fr); gap:0em 0em; width:98%; margin:.2em auto 0; font-family:inherit;">
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/aishwaryaprajna1/62a5d5ac-c586-4c4d-be55-13146844477c/small-avatar?1783981636000" alt="Aishwaryaprajna" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #48c6ef;"><br><b>Aishwaryaprajna</b><br><small>Workshop Co-Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/elsykaddoum/1161794a-11eb-4de2-8cca-12b59014e71e/small-avatar?1783978918000" alt="Elsy Kaddoum" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #48c6ef;"><br><b>Elsy Kaddoum</b><br><small>Workshop Co-Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/mirkodangelo/dd31249a-36b6-4045-9a7d-5e43e3a7faab/small-avatar?1783971708000" alt="Mirko D'Angelo" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #48c6ef;"><br><b>Mirko D'Angelo</b><br><small>Registration Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/iliasgerostathopoulos/9507ce32-cdf5-4017-92e8-601ec47d6bbc/small-avatar?1783980312000" alt="Ilias Gerostathopoulos" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #48c6ef;"><br><b>Ilias Gerostathopoulos</b><br><small>Tutorial Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/gabrielerussorusso/5a3c9cb1-ecbc-40d2-b41b-e4e7af6e7c6a/small-avatar?1783976833000" alt="Gabriele Russo Russo" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #48c6ef;"><br><b>Gabriele Russo Russo</b><br><small>Tutorial Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/robertocasadei1/92e59e53-27e1-466d-a37f-bb9e544bfbf8/small-avatar?1783972936000" alt="Roberto Casadei" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #48c6ef;"><br><b>Roberto Casadei</b><br><small>Finance Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/davidking2/7bf00105-c090-4e55-9594-d324bd9f5aa4/small-avatar?1783978534000" alt="David King" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #48c6ef;"><br><b>David King</b><br><small>Sponsorship Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/sventomforde/a583aa07-eb34-4a81-8456-cdd3fcb1b828/small-avatar?1783977537000" alt="Sven Tomforde" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #48c6ef;"><br><b>Sven Tomforde</b><br><small>Sponsorship Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/kirstiebellman/4ea94fbb-5598-4c72-bbc3-101b03b77f37/small-avatar?1783977321000" alt="Kirstie Bellman" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #c59bff;"><br><b>Kirstie Bellman</b><br><small>Community Building</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/eliahenrichs/fe13c582-eaa0-4422-ac46-14d6ce088ac3/small-avatar?1783981430000" alt="Elia Henrichs" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #c59bff;"><br><b>Elia Henrichs</b><br><small>Community Building</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/jennakline/c9429982-7f32-4933-8826-33cb8dce6a2a/small-avatar?1783976693000" alt="Jenna Kline" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #c59bff;"><br><b>Jenna Kline</b><br><small>Community Building</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/lukasesterle/ae43d672-7068-4348-8e92-a57de6d51cce/small-avatar?1783976362000" alt="Lukas Esterle" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #c59bff;"><br><b>Lukas Esterle</b><br><small>PhD Symposium Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/fatemehgolpayegani/6a3dc4fc-2f1a-459b-b9b0-fae63db5e78a/small-avatar?1783977118000" alt="Fatemeh Golpayegani" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #c59bff;"><br><b>Fatemeh Golpayegani</b><br><small>PhD Symposium Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/jialongli/9041c3fb-c30f-4f28-90c1-10101d7eb8e2/small-avatar?1783975054000" alt="Jialong Li" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #c59bff;"><br><b>Jialong Li</b><br><small>Proceedings Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/antoniobucchiarone/c4daeb1e-caef-4257-86c9-db298c00ef86/small-avatar?1783977827000" alt="Antonio Bucchiarone" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #c59bff;"><br><b>Antonio Bucchiarone</b><br><small>Publicity Co-Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/angelacortecchia/dd87e5ca-4cbb-4c85-aa53-1c9c182f7c66/small-avatar?1783971651000" alt="Angela Cortecchia" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #c59bff;"><br><b>Angela Cortecchia</b><br><small>Publicity Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/davidedomini/2cb78b24-09fe-481e-86a1-d442d3766d67/small-avatar?1783975087000" alt="Davide Domini" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #c59bff;"><br><b>Davide Domini</b><br><small>Social Experience Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/nathanlloyd/503b23f2-25f0-4af4-abb4-f1ebbb206c57/small-avatar?1783975711000" alt="Nathan Lloyd" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #c59bff;"><br><b>Nathan Lloyd</b><br><small>Publicity Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getDefaultImage/small-avatar?1783984388000" alt="Markus Stumptner" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #c59bff;"><br><b>Markus Stumptner</b><br><small>Publicity Co-Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/gianlucaaguzzi/2bb4627f-ccd6-46c4-b64f-84927839816d/small-avatar?1783975971000" alt="Gianluca Aguzzi" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #f6d365;"><br><b>Gianluca Aguzzi</b><br><small>Web Chair and AI Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/juancrosero/d00181b3-0e41-41fd-a307-e0c2bbca3d2d/small-avatar?1783979952000" alt="Juan C. Rosero" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #f6d365;"><br><b>Juan C. Rosero</b><br><small>Web Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/alessandrovittoriopapadopoulos/eae05955-4c9c-49af-86f8-c0fc596fc735/small-avatar?1783980803000" alt="Alessandro Vittorio Papadopoulos" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #f6d365;"><br><b>Alessandro V. Papadopoulos</b><br><small>In Practice Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/anapetrovska/67284fb9-40e5-4d8b-ac0e-ac94f4d07730/small-avatar?1783973805000" alt="Ana Petrovska" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #f6d365;"><br><b>Ana Petrovska</b><br><small>In Practice Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/nicolascardozo/4bf0b997-c8f9-4d9f-ba4b-7379d19ab2a3/small-avatar?1783978667000" alt="Nicolás Cardozo" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #f6d365;"><br><b>Nicolás Cardozo</b><br><small>Artifact Evaluation</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/evangelospournaras1/4decdc9f-3762-4911-9574-ee337b04db28/small-avatar?1783972918000" alt="Evangelos Pournaras" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #f6d365;"><br><b>Evangelos Pournaras</b><br><small>Artifact Evaluation</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/simondobson/77b6968c-3756-4ffe-ba36-ad7681f1a498/small-avatar?1783978693000" alt="Simon Dobson" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #f6d365;"><br><b>Simon Dobson</b><br><small>Expert Panel Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/mirgitafrasheri/83f99c2e-558f-45ef-b9a2-4adf8a8f6666/small-avatar?1783979386000" alt="Mirgita Frasheri" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #f6d365;"><br><b>Mirgita Frasheri</b><br><small>Expert Panel Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/martinabaiardi/0a8dcd66-71f5-47b0-bebc-36b98e23887b/small-avatar?1783972953000" alt="Martina Baiardi" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #f6d365;"><br><b>Martina Baiardi</b><br><small>Student Volunteers</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/sonaghahremani/a4bf5eea-aa10-4ff1-8a6c-73d9157f3735/small-avatar?1783981539000" alt="Sona Ghahremani" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #f6d365;"><br><b>Sona Ghahremani</b><br><small>Student Volunteers</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/ghassanalfalouji/269547a9-1615-4386-8283-195a06ab51c8/small-avatar?1783981655000" alt="Ghassan Al-Falouji" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #f6d365;"><br><b>Ghassan Al-Falouji</b><br><small>Demo &amp; Poster Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/nasimbeigimohammadi/01b785fd-6d5f-4133-b09b-ca142864e70a/small-avatar?1783979259000" alt="Nasim Beigi-Mohammadi" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #f6d365;"><br><b>Nasim Beigi-Mohammadi</b><br><small>Demo &amp; Poster Co-Chair</small></div>
  <div style="text-align:center; font-size:20px; line-height:1.1;"><img src="https://2026.acsos.org/getProfileImage/marcoedoardosantimaria/5c661a31-e1ce-4648-9240-ef2a05081973/small-avatar?1783975831000" alt="Marco Edoardo Santimaria" style="width:4.1em; height:4.1em; object-fit:cover; border-radius:50%; border:3px solid #f6d365;"><br><b>Marco Edoardo Santimaria</b><br><small>AI Chair</small></div>
</div>

---

# Thank you, volunteers!

![](https://i.imgflip.com/b0595b.jpg)

(placeholder for their picture)

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

<img src="acsos-logo-cesena.svg"
alt="ACSOS 2026 logo"
style="position:absolute; top:-1em; right:0em; width:25vmin; z-index:10; pointer-events:none;" />


# General and PC Chairs

{{< multicol >}}
{{< col >}}
<img src="ivana.jpg" alt="Danilo" style="width:10em" /><br>
Ivana Dusparic<br>
Trinity College Dublin, Ireland
{{< /col >}}
{{< col >}}
<img src="danilo.jpg" alt="Danilo" style="width:10em" /><br>
Danilo Pianini<br>
University of Bologna, Italy
{{< /col >}}
{{< /multicol >}}

{{< multicol >}}
{{< col >}}
<img src="robert.jpg" alt="Danilo" style="width:10em" /><br>
Robert René Maria Birke<br>
University of Turin, Italy
{{< /col >}}
{{< col >}}
<img src="christian.JPG" alt="Danilo" style="width:10em" /><br>
Christian Krupizer<br>
University of Hohenheim, Germany
{{< /col >}}
{{< /multicol >}}

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Robert René Maria Birke, 1980-2026

{{< multicol >}}
{{< col >}}
<img src="robert.jpg" alt="Danilo" style="width:25em" />
{{< /col >}}
{{< col >}}

<p>
<h2>Robert passed away on August 18, few days before the conference.</h2>
</p>
<p>
<h3>Robert was a beloved member of our community and a dedicated researcher. His passing is a great loss to all of us.</h3>
</p>
<p>
<h2>Today at 13:30, those willing to remember him are invited to join us in Aula Magna (where we are now).</h2>
</p>
{{< /col >}}
{{< /multicol >}}

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}
<img src="acsos-logo-cesena.svg"
alt="ACSOS 2026 logo"
style="position:absolute; top:-7em; right:0em; width:25vmin; z-index:10; pointer-events:none;" />

# ACSOS 2026: Numbers

{{< multicol >}}
{{% col %}}

### Conference

* **4** workshops
* **4** tutorials
* **3** keynotes
* **1** PhD symposium keynote
* **2** posters (+**8** from main-track papers)
* **6** artifacts (+**6** from main-track papers)
* **109** Registered participants
    * including keynote speakers and volunteers

{{% /col %}}
{{% col %}}

### Main track

* **106** Abstract submissions
* **100** Complete submissions
* **20** Desk rejects (non-anonymous, AI-gen)
* **16** Accepted papers (A.R. 16%)
* **7** Conditional accepts, 100% success rate
* **23** Full papers in toal (A.R. **23%**)
* **10** Short papers 
* **5** Vision papers
* **38** Main-track presentations

{{% /col %}}
{{< /multicol >}}

---


{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Authors per submission

<div style="background:rgba(255,255,255,.25); border-radius:.5em; padding:.4em;">
{{< chart 92 780 >}}
{
  "type": "bar",
  "indexAxis": "y",
  "data": {
    "labels": ["1", "2", "3", "4", "5", "6", "7", "8", "9", "11", "21"],
    "datasets": [{
      "label": "Submissions",
      "data": [23, 19, 26, 16, 9, 5, 1, 3, 2, 1, 1],
      "backgroundColor": "rgba(246,211,101,.68)",
      "borderColor": "#000000",
      "borderWidth": 1,
      "borderRadius": 5
    }]
  },
  "options": {
    "responsive": true,
    "maintainAspectRatio": false,
    "font": { "family": "Audiowide" },
    "plugins": {
      "legend": { "display": false },
      "datalabels": { "color": "#e6f5ff", "anchor": "end", "align": "top", "textAlign": "center", "offset": 8, "font": { "family": "Audiowide", "size": 48, "weight": "bold" } }
    },
    "scales": {
      "x": { "beginAtZero": true, "title": { "display": true, "text": "Author count", "color": "#e6f5ff", "font": { "family": "Audiowide", "size": 54, "weight": "bold" } }, "ticks": { "color": "#e6f5ff", "font": { "family": "Audiowide", "size": 48, "weight": "bold" }, "stepSize": 5 }, "grid": { "display": false }, "border": { "color": "#000000", "width": 4 } },
      "y": { "title": { "display": true, "text": "Number of papers", "color": "#e6f5ff", "font": { "family": "Audiowide", "size": 54, "weight": "bold" } }, "ticks": { "display": false }, "grid": { "display": false }, "border": { "color": "#000000", "width": 4 } }
    }
  }
}
{{< /chart >}}
</div>
<div style="text-align:center; margin-top:.4em; color:#b9d7ee; font-size:.8em;">106 submissions &nbsp;·&nbsp; mean: 3.4 authors</div>

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# What we work on

<div style="width:94%; height:23em; margin:.2em auto 0; padding:.6em; border-radius:.5em; background:rgba(16,48,81,.42);">
  <canvas id="acsos-keyphrase-wordcloud"></canvas>
</div>
<script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.7/dist/chart.umd.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/chartjs-chart-wordcloud@4.4.5/build/index.umd.min.js"></script>
<script>
  Chart.defaults.font.family = 'Audiowide';
  Chart.register(ChartWordCloud.WordCloudController, ChartWordCloud.WordElement);
  new Chart(document.getElementById('acsos-keyphrase-wordcloud'), {
    type: 'wordCloud',
    data: {
      labels: ['self-adaptive systems', 'software engineering for adaptive', 'Adaptive and self-managing systems', 'Computer Vision and Pattern Recognition', 'Large Language Models', 'managed system', 'autonomic computing and self organizing', 'self-organizing systems', 'over time', 'Deep Learning', 'software engineering for self adaptive systems', 'managing system', 'Deep Learning Models', 'noise level', 'Multi-Agent Systems', 'Autonomic Computing', 'impacts of adaptation actions', 'Medical Image Analysis', 'trajectory cae', 'Machine Learning'],
      datasets: [{
        data: [100, 54, 48, 46, 46, 42, 38, 36, 36, 34, 34, 32, 32, 32, 32, 30, 30, 30, 30, 28],
        fit: false,
        color: ['#ffe082', '#48c6ef', '#c59bff', '#8ee3a8', '#f6d365']
      }]
    },
    options: {
      plugins: { legend: { display: false }, tooltip: { enabled: true } },
      elements: { word: { font: { family: 'Audiowide', weight: 'bold' }, padding: 4, rotate: 0, rotationSteps: 1 } }
    }
  });
</script>
<div style="text-align:center; margin-top:.4em; color:#b9d7ee; font-size:.62em;">keyphrases weighted by occurrence in submissions · top terms shown · data from easychair</div>

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Submitting authors by country, map

<div style="width:96%; margin:.1em auto 0; padding:.35em .5em .15em; border-radius:.6em; background:rgba(16,48,81,.48);">
  <svg id="acsos-authors-map" viewBox="0 0 1200 600" role="img" aria-label="World map showing countries represented by ACSOS submitting authors" style="display:block; width:100%; height:24em;"></svg>
</div>
<script src="https://cdn.jsdelivr.net/npm/d3@7/dist/d3.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/topojson-client@3/dist/topojson-client.min.js"></script>
<script>
  (() => {
    const authorsByCountry = {
      '036': ['au', 'Australia', 1], '040': ['at', 'Austria', 24], '056': ['be', 'Belgium', 3],
      '076': ['br', 'Brazil', 23], '124': ['ca', 'Canada', 13], '156': ['cn', 'China', 1],
      '170': ['co', 'Colombia', 3], '208': ['dk', 'Denmark', 7], '250': ['fr', 'France', 9],
      '276': ['de', 'Germany', 78], '300': ['gr', 'Greece', 5], '356': ['in', 'India', 6],
      '372': ['ie', 'Ireland', 6], '376': ['il', 'Israel', 2], '380': ['it', 'Italy', 45],
      '392': ['jp', 'Japan', 3], '400': ['jo', 'Jordan', 1], '578': ['no', 'Norway', 3],
      '688': ['rs', 'Serbia', 4], '702': ['sg', 'Singapore', 2], '724': ['es', 'Spain', 3],
      '752': ['se', 'Sweden', 9], '756': ['ch', 'Switzerland', 6], '792': ['tr', 'Turkey', 2],
      '826': ['gb', 'United Kingdom', 21], '840': ['us', 'United States', 28]
    };
    const svg = d3.select('#acsos-authors-map');
    const width = 1200, height = 600;
    const projection = d3.geoNaturalEarth1().fitSize([width, height], { type: 'Sphere' });
    const path = d3.geoPath(projection);
    const defs = svg.append('defs');
    const map = svg.append('g');
    map.append('path').datum({ type: 'Sphere' }).attr('d', path).attr('fill', 'rgba(255,255,255,.04)').attr('stroke', '#b9d7ee').attr('stroke-width', 2);
    fetch('https://cdn.jsdelivr.net/npm/world-atlas@2/countries-110m.json')
      .then(response => response.json())
      .then(world => {
        const countries = topojson.feature(world, world.objects.countries).features;
        countries.forEach(country => {
          const id = String(country.id).padStart(3, '0');
          const entry = authorsByCountry[id];
          if (entry) {
            const clipId = `acsos-country-${id}`;
            const clip = defs.append('clipPath').attr('id', clipId).attr('clipPathUnits', 'userSpaceOnUse');
            clip.append('path').datum(country).attr('d', path);
            const bounds = path.bounds(country);
            map.append('image')
              .attr('href', `https://flagcdn.com/w320/${entry[0]}.png`)
              .attr('x', bounds[0][0]).attr('y', bounds[0][1])
              .attr('width', bounds[1][0] - bounds[0][0]).attr('height', bounds[1][1] - bounds[0][1])
              .attr('preserveAspectRatio', 'xMidYMid slice')
              .attr('clip-path', `url(#${clipId})`);
          }
          map.append('path')
            .datum(country)
            .attr('d', path)
            .attr('fill', 'transparent')
            .attr('stroke', entry ? '#ffffff' : 'rgba(185,215,238,.45)')
            .attr('stroke-width', entry ? .8 : .8)
            .append('title')
            .text(entry ? `${entry[1]} · ${entry[2]} submitting authors` : (country.properties.name || '')); 
        });
      });
  })();
</script>
<div style="text-align:center; margin-top:.25em; color:#b9d7ee; font-size:.7em;">Flags mark the 26 countries represented among ACSOS submitting authors</div>


---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Submitting authors by continent

<div style="background:rgba(255,255,255,.25); border-radius:.5em; padding:.4em;">
{{< chart 100 780 >}}
{
  "type": "bar",
  "indexAxis": "y",
  "data": {
    "labels": ["Europe", "North America", "South America", "Asia", "Oceania"],
    "datasets": [{
      "label": "Authors",
      "data": [223, 41, 26, 17, 1],
      "backgroundColor": "rgba(246,211,101,.68)",
      "borderColor": "#000000",
      "borderWidth": 1,
      "borderRadius": 5
    }]
  },
  "options": {
    "responsive": true,
    "maintainAspectRatio": false,
    "font": { "family": "Audiowide" },
    "plugins": {
      "legend": { "display": false },
      "datalabels": { "color": "#e6f5ff", "anchor": "end", "align": "top", "textAlign": "center", "offset": 5, "font": { "family": "Audiowide", "size": 42 } }
    },
    "scales": {
      "x": { "beginAtZero": true, "max": 100, "title": { "display": true, "text": "Continent", "color": "#e6f5ff", "font": { "family": "Audiowide", "size": 48, "weight": "bold" } }, "ticks": { "color": "#e6f5ff", "font": { "size": 35 }, "stepSize": 10, "max": 100 }, "grid": { "display": false }, "border": { "color": "#000000", "width": 4 } },
      "y": { "title": { "display": true, "text": "Author count", "color": "#e6f5ff", "font": { "family": "Audiowide", "size": 48, "weight": "bold" } }, "ticks": { "color": "#e6f5ff", "font": { "size": 30 }, "autoSkip": true }, "grid": { "display": false }, "border": { "color": "#000000", "width": 4 } }
    }
  }
}
{{< /chart >}}
</div>
<div style="text-align:center; margin-top:.35em; color:#b9d7ee; font-size:.72em;">308 country-attributed authors · Turkey counted with Asia</div>


---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Submitting authors by country

<div style="background:rgba(255,255,255,.25); border-radius:.5em; padding:.4em;">
{{< chart 100 900 >}}
{
  "type": "bar",
  "indexAxis": "y",
  "data": {
    "labels": ["Germany", "Italy", "United States", "Austria", "Brazil", "United Kingdom", "Canada", "France", "Sweden", "Denmark", "India", "Ireland", "Switzerland", "Greece", "Serbia", "Belgium", "Colombia", "Japan", "Norway", "Spain", "Israel", "Singapore", "Turkey", "Australia", "China", "Jordan"],
    "datasets": [{
      "label": "Submitting authors",
      "data": [78, 45, 28, 24, 23, 21, 13, 9, 9, 7, 6, 6, 6, 5, 4, 3, 3, 3, 3, 3, 2, 2, 2, 1, 1, 1],
      "backgroundColor": "rgba(246,211,101,.68)",
      "borderColor": "#000000",
      "borderWidth": 1,
      "borderRadius": 5
    }]
  },
  "options": {
    "responsive": true,
    "maintainAspectRatio": false,
    "font": { "family": "Audiowide" },
    "plugins": {
      "legend": { "display": false },
      "datalabels": { "color": "#e6f5ff", "anchor": "end", "align": "top", "textAlign": "center", "offset": 5, "font": { "family": "Audiowide", "size": 27 } }
    },
    "scales": {
      "x": { "beginAtZero": true, "max": 100, "title": { "display": false, "text": "Country", "color": "#e6f5ff", "font": { "family": "Audiowide", "size": 42, "weight": "bold" } }, "ticks": { "color": "#e6f5ff", "font": { "size": 35 }, "stepSize": 10, "max": 100 }, "grid": { "display": false }, "border": { "color": "#000000", "width": 4 } },
      "y": { "title": { "display": true, "text": "Author count", "color": "#e6f5ff", "font": { "family": "Audiowide", "size": 42, "weight": "bold" } }, "ticks": { "color": "#e6f5ff", "font": { "size": 30 }, "autoSkip": true }, "grid": { "display": false }, "border": { "color": "#000000", "width": 4 } }
    }
  }
}
{{< /chart >}}
</div>
<div style="text-align:center; margin-top:.35em; color:#b9d7ee; font-size:.72em;">359 submitting authors across 26 countries</div>

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Accepted authors by country

<div style="width:96%; margin:.1em auto 0; padding:.35em .5em .15em; border-radius:.6em; background:rgba(16,48,81,.48);">
  <svg id="acsos-accepted-authors-map" viewBox="0 0 1200 600" role="img" aria-label="World map showing countries represented by estimated ACSOS accepted authors" style="display:block; width:100%; height:24em;"></svg>
</div>
<script src="https://cdn.jsdelivr.net/npm/d3@7/dist/d3.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/topojson-client@3/dist/topojson-client.min.js"></script>
<script>
  (() => {
    const acceptedByCountry = {
      '040': ['at', 'Austria', 6], '076': ['br', 'Brazil', 6], '124': ['ca', 'Canada', 3],
      '170': ['co', 'Colombia', 3], '208': ['dk', 'Denmark', 4], '250': ['fr', 'France', 6],
      '276': ['de', 'Germany', 35], '356': ['in', 'India', 1], '372': ['ie', 'Ireland', 1],
      '380': ['it', 'Italy', 15], '752': ['se', 'Sweden', 1], '756': ['ch', 'Switzerland', 2],
      '826': ['gb', 'United Kingdom', 11], '840': ['us', 'United States', 6]
    };
    const svg = d3.select('#acsos-accepted-authors-map');
    const width = 1200, height = 600;
    const projection = d3.geoNaturalEarth1().fitSize([width, height], { type: 'Sphere' });
    const path = d3.geoPath(projection);
    const defs = svg.append('defs');
    const map = svg.append('g');
    map.append('path').datum({ type: 'Sphere' }).attr('d', path).attr('fill', 'rgba(255,255,255,.04)').attr('stroke', '#b9d7ee').attr('stroke-width', 2);
    fetch('https://cdn.jsdelivr.net/npm/world-atlas@2/countries-110m.json')
      .then(response => response.json())
      .then(world => {
        topojson.feature(world, world.objects.countries).features.forEach(country => {
          const id = String(country.id).padStart(3, '0');
          const entry = acceptedByCountry[id];
          if (entry) {
            const clipId = `acsos-accepted-country-${id}`;
            const clip = defs.append('clipPath').attr('id', clipId).attr('clipPathUnits', 'userSpaceOnUse');
            clip.append('path').datum(country).attr('d', path);
            const bounds = path.bounds(country);
            map.append('image').attr('href', `https://flagcdn.com/w320/${entry[0]}.png`)
              .attr('x', bounds[0][0]).attr('y', bounds[0][1]).attr('width', bounds[1][0] - bounds[0][0]).attr('height', bounds[1][1] - bounds[0][1])
              .attr('preserveAspectRatio', 'xMidYMid slice').attr('clip-path', `url(#${clipId})`);
          }
          map.append('path').datum(country).attr('d', path).attr('fill', 'transparent')
            .attr('stroke', entry ? '#ffffff' : 'rgba(185,215,238,.45)').attr('stroke-width', .8)
            .append('title').text(entry ? `${entry[1]} · ${entry[2]} estimated accepted authors` : (country.properties.name || '')); 
        });
      });
  })();
</script>
<div style="text-align:center; margin-top:.25em; color:#b9d7ee; font-size:.7em;">Flags mark the 14 countries with estimated accepted authors</div>

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Accepted authors by continent

<div style="background:rgba(255,255,255,.25); border-radius:.5em; padding:.4em;">
{{< chart 100 780 >}}
{
  "type": "bar",
  "indexAxis": "y",
  "data": {
    "labels": ["Europe", "South America", "North America", "Asia"],
    "datasets": [{
      "label": "Estimated accepted authors",
    "data": [80, 9, 9, 1],
      "backgroundColor": "rgba(246,211,101,.68)",
      "borderColor": "#000000",
      "borderWidth": 1,
      "borderRadius": 5
    }]
  },
  "options": {
    "responsive": true,
    "maintainAspectRatio": false,
    "font": { "family": "Audiowide" },
    "plugins": {
      "legend": { "display": false },
      "datalabels": {
          "color": "#e6f5ff",
          "anchor": function(context) { return context.dataIndex === 0 ? "center" : "end"; },
          "align": function(context) { return context.dataIndex === 0 ? "top" : "top"; },
          "textAlign": "center",
          "offset": 5,
          "font": { "family": "Audiowide", "size": 42 }
      }
    },
    "scales": {
      "x": { "beginAtZero": true, "max": 100, "title": { "display": false, "text": "Continent", "color": "#e6f5ff", "font": { "family": "Audiowide", "size": 48, "weight": "bold" } }, "ticks": { "color": "#e6f5ff", "font": { "family": "Audiowide", "size": 35 }, "stepSize": 10, "max": 100 }, "grid": { "display": false }, "border": { "color": "#000000", "width": 4 } },
      "y": { 
        "title": { "display": true, "text": "Author count", "color": "#e6f5ff", "font": { "family": "Audiowide", "size": 48, "weight": "bold" } },
        "ticks": { "color": "#e6f5ff", "font": { "family": "Audiowide", "size": 30 }, "autoSkip": true },
        "grid": { "display": false }, "border": { "color": "#000000", "width": 4 } }
    }
  }
}
{{< /chart >}}
</div>
<div style="text-align:center; margin-top:.35em; color:#b9d7ee; font-size:.72em;">Whole-author estimates from country author counts × country acceptance rate</div>

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Accepted authors by country

<div style="background:rgba(255,255,255,.25); border-radius:.5em; padding:.4em;">
{{< chart 100 780 >}}
{
  "type": "bar",
  "indexAxis": "y",
  "data": {
    "labels": ["Germany", "Italy", "United Kingdom", "Brazil", "France", "United States", "Austria", "Denmark", "Colombia", "Canada", "Switzerland", "Sweden", "Ireland", "India"],
    "datasets": [{
      "label": "Estimated accepted authors",
    "data": [35, 15, 11, 6, 6, 6, 6, 4, 3, 3, 2, 1, 1, 1],
      "backgroundColor": "rgba(246,211,101,.68)",
      "borderColor": "#000000",
      "borderWidth": 1,
      "borderRadius": 5
    }]
  },
  "options": {
    "responsive": true,
    "maintainAspectRatio": false,
    "font": { "family": "Audiowide" },
    "plugins": {
      "legend": { "display": false },
      "datalabels": { "color": "#e6f5ff", "anchor": function(context) { return context.dataIndex === 0 ? "center" : "end"; }, "align": function(context) { return context.dataIndex === 0 ? "top" : "top"; }, "textAlign": "center", "offset": 5, "font": { "family": "Audiowide", "size": 27 } }
    },
    "scales": {
      "x": { "beginAtZero": true, "max": 100, "title": { "display": false, "text": "Country", "color": "#e6f5ff", "font": { "family": "Audiowide", "size": 42, "weight": "bold" } }, "ticks": { "color": "#e6f5ff", "font": { "size": 35 }, "stepSize": 10, "max": 100 }, "grid": { "display": false }, "border": { "color": "#000000", "width": 4 } },
      "y": { "title": { "display": true, "text": "Author count", "color": "#e6f5ff", "font": { "family": "Audiowide", "size": 42, "weight": "bold" } }, "ticks": { "color": "#e6f5ff", "font": { "size": 30 }, "autoSkip": true }, "grid": { "display": false }, "border": { "color": "#000000", "width": 4 } }
    }
  }
}
{{< /chart >}}
</div>
<div style="text-align:center; margin-top:.35em; color:#b9d7ee; font-size:.72em;">Whole-author estimates from country author counts × country acceptance rate</div>

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Proceedings

<div style="display:flex; align-items:center; justify-content:space-around; gap:2em; width:90%; margin:1em auto 0;">
  <div style="flex:1; text-align:center;">
    <img src="https://liberconference.eu/wp-content/uploads/2019/04/IEEE-XploreDigitalLibrary.jpg" alt="IEEE Xplore logo" style="display:block; width:30em; height:auto; max-width:100%; margin:0 auto 1em;" />
    <div style="font-size:1.05em; line-height:1.7; text-align:left; display:inline-block;">
      <div><b>URL:</b> TODO</div>
      <div><b>Username:</b> TODO</div>
      <div><b>Password:</b> TODO</div>
    </div>
  </div>
  <div style="flex:1; text-align:center;">
    <div style="display:inline-block; padding:.6em; background:rgba(255,255,255,.95); border-radius:.5em;">
      <img src="https://api.qrserver.com/v1/create-qr-code/?size=500x500&amp;data=TODO" alt="QR code for IEEE Xplore proceedings" style="display:block; width:11em; height:11em;" />
    </div>
  </div>
</div>

---

{{< slide background-iframe="animations/ribbons.html" background-interactive="true" >}}

# Adaptive Serverless Computing Across the Cloud-Edge Continuum

<div style="display:flex; align-items:center; gap:2em; width:92%; margin:.7em auto 0; text-align:left;">
  <div style="flex:0 0 31%; text-align:center;">
    <img src="https://2026.acsos.org/getImage/orig/valeria.jpg" alt="Valeria Cardellini" style="display:block; width:15em; height:15em; max-width:100%; margin:0 auto .8em; object-fit:cover; border-radius:50%; border:6px solid #f6d365;" />
    <div style="font-size:.85em; line-height:1.2; color:#ffe5a3;">Valeria Cardellini</div>
    <div style="font-size:.6em; line-height:1.25; color:#b9d7ee; margin-top:.35em;">Full Professor of Computer Science and Engineering<br />University of Rome Tor Vergata, Italy</div>
  </div>
  <div style="flex:1; padding:1em 1.2em; border-left:5px solid #f6d365; border-radius:.35em; background:rgba(66,54,27,.5); font-size:.72em; line-height:1.35; color:#ffe5a3;">
    <div style="font-size:1.35em; font-weight:700; margin-bottom:.45em; color:#ffe082;">Abstract</div>
    <p>Serverless computing, particularly Function-as-a-Service, has transformed application deployment through event-driven execution and automatic scaling. Across the heterogeneous Cloud-Edge continuum, however, cloud-centric platforms struggle with changing node availability, network conditions, data locality, and energy constraints.</p>
    <p>This keynote explores adaptive serverless computing, where scheduling, execution offloading, and resource management continuously respond to infrastructure, workload, and user requirements. Context-aware orchestration makes decentralized runtime decisions that balance performance, cost, and sustainability.</p>
    <p>Using Serverledge, a decentralized open-source FaaS platform for distributed continuum environments, the talk shows how adaptive execution can provide efficient, resilient, and low-latency serverless performance without centralized control. It closes with challenges and a vision for autonomous serverless platforms.</p>
  </div>
</div>
