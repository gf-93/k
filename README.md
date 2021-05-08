<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title></title>
	</head>
	<script type="text/javascript">
		<% String price = request.getParameter()%>
		var price = <%= price %>
		$("#price").text(price)
	</script>
	<body>
		<div style="background-color: #393a3f; color: aliceblue; height:250px;font-size: 60px; text-align: center;">确认交易</div>
		<div style="background-color: #ededed; height: 600px;">
			<div style="font-size: 60px;">需付费</div>
			<div id="price"></div>
		</div>
		<button style="background-color:#1aac19; color: white; font-size: 60px; margin-left: 340px;">立即支付</button>
	</body>
</html>
