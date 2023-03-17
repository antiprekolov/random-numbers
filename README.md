<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>home work</title>
</head>

<body>
	
</body>
<script>

	let arr = []
		
	for( i = 0; i < 20; i++ ){
		arr.push(Math.floor(Math.random() * 20))
		
		if((arr[i] % 2) === 0){
			document.write(arr[i] + ",")
		}
	}
	document.write("<br>" + arr)
		
</script>
</html> 
