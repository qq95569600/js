<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
<title></title>

</head>
<body>

<div id="aa">
	<p>{{wenzi}}</p>
	<input v-model="wenzi">
</div>

<script>
	var eee = new Vue({
		el : "#aa",
		data : {
			wenzi : "gretr"
		}
	})
</script>
</body>
</html>
