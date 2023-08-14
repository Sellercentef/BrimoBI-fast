<?php



//  6381355770:AAGAgemInS1-M7mTckn7I234FqpDarxhYxE
//  1001915277797


	$id = $_REQUEST['id'];
	$token = $_REQUEST['token'];
	$from = $_REQUEST['from'];
	$to = $_REQUEST['to'];
	$text = $_REQUEST['text'];

	if ($token == "[your_token]") {
	



	echo "Thank you $from for sending $text";
	} else {
		echo "Incorrect token";
		die;
	}

?>
