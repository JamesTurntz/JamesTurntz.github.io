<!DOCTYPE html>
<html>

	<head>
		<meta charset="utf-8" />
		<title>Styx</title>
	</head>

	<body>

		<iframe id="myiframe" src="http://styx.wpblog.jp/" frameborder="0" scrolling="auto" width="100%" height="100%" onload="load()"></iframe>

		<script>
			function load() {
				var ifm = document.getElementById("myiframe");

				ifm.height = document.documentElement.clientHeight;
				ifm.width = document.documentElement.clientWidth;
			}
		</script>
	</body>

</html>
