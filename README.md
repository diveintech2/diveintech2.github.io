# diveintech2.github.io

To add a user, we need to change 2 parts of the code : 

Part 1 : the profile (see example)
  - instead of typeMakerDesignOrFreeLance, put the words "makers" or "designers" or "freelancers"
  - instead of CityName1, put their City (CityName2, if it's San Francisco, or any 2 words city, write it this way: 'San Francisco')
  - instead of profileName, put their profile name (duh)
  - instead of twitterAdress, put their twitter url
  - instead of twitterDescription, put their twitter description
  - instead of twitterPic, put their twitter picture location (it should be saved in the img folder for now ... we can make a GET request to their API at some point!)

<!-- profile name -->
				<li class="mix typeMakerDesignOrFreeLance CityName1 radio3 CityName2">
                    <div class="image-container">
                    <div class="twitter">
                        <a href="twitterAddress" target="_blank">
                            <img class="icon icon-twitter" src="img/twitter.png" alt="profileName" data-pin-nopin="true">
                        </a>
                    </div>
                    <a href="twitterAddress" target="_blank">
                        <div class="name">profileName</div>
                        <div class="blurb">
                              twitter description
                        </div>
                        <img src="twitterPic" alt="profileName">
                    </a>
                    </div>
                </li>

                
Part 2 : the city
  - cityName : put their city name (don't forget that theire is a . before the city name!)
  - increment the number of checbox if we add a new city : say we add Cracovia, that will be checkbox7
						
	Example : 
	        <li>
			<input class="filter" data-filter=".Belgrade" type="checkbox" id="checkbox6">
			<label class="checkbox-label" for="checkbox6">Belgrade</label>
		</li>

                
                
