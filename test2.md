# Senate hearings

<link rel="stylesheet" type="text/css" href="css/markdown.css">
<link rel="shortcut icon" href="ico/favicon.png" type="image/x-icon">

<script>
var current_month = <?= $init['MMDDYY']; ?>;
</script>
<script>
    var date = new Date();
    var formattedDate = ('0' + date.getDate()).slice(-2);
    var formattedMonth = ('0' + (date.getMonth() + 1)).slice(-2);
    var formattedYear = date.getFullYear().toString().substr(2,2);
    var dateString = formattedMonth + formattedDate + formattedYear;
    var output = document.querySelector('#output');
    var MMDDYY = dateString;
</script>

|-|
| [Schedule](https://www.senate.gov/committees/committee_hearings.htm) |

| Committee | HLS | hls.js | ISVP | Committee Website |
|-|-|-|-|-|
| Agriculture, Nutrition and Forestry | <script>document.write('<a href="https://ag-f.akamaihd.net/i/ag' + MMDDYY + '_1@76440/master.m3u8">HLS</a>');</script> | <script>document.write('<a href="/hlsjsvideo.html?stream=https://ag-f.akamaihd.net/i/ag' + MMDDYY + '_1@76440/master.m3u8">hls.js</a>');</script> | <script>document.write('<a href="https://www.senate.gov/isvp/?comm=ag&filename=ag' + MMDDYY + '">ISVP</a>');</script> | [Committee Website](https://www.agriculture.senate.gov/hearings) |
