# php-images-crop
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
