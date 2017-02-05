var like_button = document.getElementsByClassName('b-link js-profile-header-vote'); 


	var counter = 0;
	var random = 0;
	var liked_profiles = 0;


	(function next() {
	    if (counter++ >= 1000000) return;
	    setTimeout(function() {
		try {
	        like_button[0].click(); 
		} catch(TypeError) {}
	        next();
		console.log("Liked "+liked_profiles+" profiles")
		liked_profiles = liked_profiles + 1
	    }, Math.floor((Math.random() * 6500) + 3000));
	})();
