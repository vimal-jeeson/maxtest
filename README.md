<!DOCTYPE html>
<html>
<head>
<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>
</head>
<body>

<h2>Images Side by Side</h2>
<p>How to create side-by-side images with the CSS float property:</p>

<div class="row">
  <div class="column">
    <img src="http://d25tmfuvd960zw.cloudfront.net/146313/850x1275_SuperFunKudumbam_146313_090acd55-5efa-4a2a-8457-3e7780e4bc3f.jpg" alt="Snow" style="width:100%">
  </div>
  <div class="column">
    <img src="http://d25tmfuvd960zw.cloudfront.net/141324/850x1275_WhereWeStand_141324_ef4a2575-b6b2-4ab1-b34f-c637640ee2e9.jpg" alt="Forest" style="width:100%">
  </div>
  <div class="column">
    <img src="http://d25tmfuvd960zw.cloudfront.net/125091/850x1275_OruChiriIruChiriBumperChiri_125091_d13be302-8362-49a6-a8ae-92e6f6db8435.jpg" alt="Mountains" style="width:100%">
  </div>
</div>

</body>
</html>
