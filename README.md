Welcome</br>
Movie Recommendation Engine</br>
This is a movie recommendation website based on User-based collaborating filtering.</br>


Installation</br>
-Clone this repo on your local machine.</br>
-Go to the project directory.</br>
-Create a virtual environment on your device by</br>
	virtualenv <environment name></br>
-Activate the virtual environment by typing</br>
	<environment name>\Scripts\activate</br>
-Run</br>
	python install -r req.txt</br>
-Run server Locally</br>
	python manage.py runserver</br>
-Go to localhost:8000</br>


Characterstics</br>
-User can login by username, password.</br>
-User can search movies by name.</br>
-User can give ratings to the movies.</br>
-User can get Movie Recommendation based on ratings given by the User.</br>

Algorithm</br>
-Collaborative filtering is the predictive process behind recommendation engines.</br>
Recommendation engines analyze information about users with similar tastes to assess the probability that a target individual will enjoy something, such as a video, a book or a product. Collaborative filtering is also known as social filtering.
-Collaborative filtering uses algorithms to filter data from user reviews to make personalized recommendations for users with similar preferences.
Collaborative filtering is also used to select content and advertising for individuals on social media.
-Three types of collaborative filtering commonly used in recommendation systems are neighbor-based, item-to-item and classification- based.

For this project I have used neighbor-based recommendation system that is User-user based collaborating filtering.
