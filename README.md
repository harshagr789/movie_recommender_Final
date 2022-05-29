Welcome
Movie Recommendation Engine
This is a movie recommendation website based on User-based collaborating filtering.


Installation
-Clone this repo on your local machine.
-Go to the project directory.
-Create a virtual environment on your device by
	virtualenv <environment name>
-Activate the virtual environment by typing
	<environment name>\Scripts\activate
-Run
	python install -r req.txt
-Run server Locally
	python manage.py runserver
-Go to localhost:8000


Characterstics
-User can login by username, password.
-User can search movies by name.
-User can give ratings to the movies.
-User can get Movie Recommendation based on ratings given by the User.

Algorithm
-Collaborative filtering is the predictive process behind recommendation engines.
Recommendation engines analyze information about users with similar tastes to assess the probability that a target individual will enjoy something, such as a video, a book or a product. Collaborative filtering is also known as social filtering.
-Collaborative filtering uses algorithms to filter data from user reviews to make personalized recommendations for users with similar preferences.
Collaborative filtering is also used to select content and advertising for individuals on social media.
-Three types of collaborative filtering commonly used in recommendation systems are neighbor-based, item-to-item and classification- based.

For this project I have used neighbor-based recommendation system that is User-user based collaborating filtering.
