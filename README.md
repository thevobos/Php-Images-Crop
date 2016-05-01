# php-images-crop

[![SensioLabsInsight](https://insight.sensiolabs.com/projects/8910a56a-8e28-4bce-9bc1-6b4dad39dab4/big.png)](https://insight.sensiolabs.com/projects/8910a56a-8e28-4bce-9bc1-6b4dad39dab4)

Php İmages Crop


		include("crop.php");

		$images = new crop;

		$images->image("app/storage/deneme.jpg") // image path 
			->targetw(width)
			->targeth(height)
			->xcor(cor x)
			->ycor(cor y)
			->width(width)
			->height(height)
			->quality(100) // quality
			->run();
