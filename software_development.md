

Planning  
	Two kinds:   
		Dev and Design start at the same time  
		Design first, then dev  


Learning  
	If we know what we're building, learn components nessecary and also try to choose components that don't require much learning, or will be extremely maintainable going forward  
	If we don't yet, ideate on what we're building and learn things that will probably be generally useful (frontend frameworks, study up on algorithms you might need to use, databases etc)  

Building  
	Setup framework scaffold  
	Get core CRUD views together  
	Conceptualize data model  
	Integrate authentication if authentication is required for data  
	Secure sensitive user data (passwords, ssns, cc#, login tokens, api tokens, anything that could be used to impersonate or inappropriately identify the user)  
	Get backend accepting data, applying business logic and validation and persisting data, then displaying persisted data  
	Stabilize API  
	Configure nessecary algorithms (ranking, predictive algorithms, suggestions, etc)  
	Configure nessecary integrations (login systems, attached services like mail, hosted db, security certs, scraping and other improvised solutions)  
	Build out frontend in detail (single-page apps, analytics, etc)  
	If there are alternate delivery methods for the data, build out alternate methods (ad data, internal vs customer site, emails, etc)  
	Add monitoring  
	Productize and apply business logic to API, by locking down certain parts and providing convienience for third-party service integration  
	Configure authentication on API  

Launch! Iterate here, continue doing things from the building section, while starting on engineering  

Engineering  
	Develop style guide for interfaces (in code)  
	Develop code style guide & review process  
	Decide internal library usage (ie jQuery, modernify, text editors, packages, tools (lodash vs underscore))
	Build asset pipeline (CDNs)  
	Create build script for automated installs, startups, upgrades, asset recompilation, CSS preprocessor compilation  
	Add deploy process, attached to code review and quality assurance and security assurance process  
	Document deploy process (compliance)  
	Create testing protocol & begin to get test coverage  
  
  
	Setup monitors  
		Continuous integration monitoring  
		Data  
		Resource availability and response time  
		Server stability  
		Server availability and response time  
		Exception monitoring  
		Log monitoring  
		HTTP status monitoring  
		Analytics and activity monitoring - delta alerts (no one's signed up in 3 hours when our average is 56 per hour?)  
	Perform security audits, pen testing, and fix flaws  
	DDoS protection  



