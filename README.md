<!DOCTYPE html>
<html lang="en">

	<head>
		<meta charset="UTF-8">
		<meta http-equiv="X-UA-Compatible" content="IE=edge">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>Document</title>

	</head>

	<body>
		<style>
			.area {
				display: grid;
				grid-template-columns: repeat(12, 2em);
				grid-template-rows: repeat(18, 2em);
				background: repeating-linear-gradient(90deg,#dddddd88 0 1.95em, #bbbbbb88 1.95em 2.05em), repeating-linear-gradient(180deg,#dddddd88 0 1.95em, #bbbbbb88 1.95em 2.05em);
				width: fit-content;
				height: fit-content;
			}
			.area .L {
				grid-area: var(--xy);
				background: #ffffffdd;
				border: solid 1px #333333;
				border-radius: 2px;
			}
		</style>

		<div class="area">
			<div class="L" style="--xy: 1 / 1 / 3 / 3 ;"></div>
		</div>
	</body>

</html>
