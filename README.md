# Monte-s-scorecards
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <title>Baseball Scorecard</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <h1>Baseball Scorecard</h1>
    </header>

    <div class="controls">
      <label>Away Team: <input id="awayName" value="Away"></label>
      <label>Home Team: <input id="homeName" value="Home"></label>
      <button id="addInning">+ Inning</button>
      <button id="resetBtn">Reset</button>
      <button id="exportBtn">Export CSV</button>
      <button id="printBtn">Print</button>
    </div>

    <section id="scorecard">
      <table id="scoreTable" cellspacing="0">
        <thead>
          <tr id="headerRow"></tr>
        </thead>
        <tbody>
          <tr id="awayRow"></tr>
          <tr id="homeRow"></tr>
        </tbody>
      </table>
    </section>

    <footer class="note">Tip: Click numbers to edit. Use Export to save a CSV. Print-friendly layout included.</footer>

    <script src="app.js"></script>
  </body>
</html>


