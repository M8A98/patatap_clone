# NOTES


for (var x = 0; x < 1000; x+=100){
	for(var y = 0; y < 1000; y +=100){
	new Path.Circle(new Point(x, y), 10).fillColor = 'blue';	
	}
}

X | Y Each X produces 10 Ys

0   0
0   100
..  900
100 0

console.log(view.size.width);
console.log(view.size.height);

Point.random() is like Math.random() but in x and y as well.