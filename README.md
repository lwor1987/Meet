# Meet
 
 (Description)
 
  This is a build that will be a serverless, progressive web aplication made with react that will be using a test-driven development. The Meet Application will be able to fetch upcoming events using googles Calander Api.
  
  (Feature 2: Show/Hide Event's Details)
  
   As a user. I should be able to expand or hide an event element. So that I can search through the events that are in the city I searched.  
   
   *Scenario 1*: An event element is collapsed by default.
      Given: The main page is open. 
      When: There is not an event selected.
      Then: The current event element will collapse by default. 
   
   *Scenario 2*: The user can expand an event to see its details. 
      Given: The user clicked the event button.
      When:  The use chooses an event. 
      Then: The details of the event will be shown the user. 
      
    *Scenario 3*: The user can collapse an event to hide its details. 
      Given: The event element is opened. 
      When: The user can close the event element. 
      Then: The details will collapse and become hidden. 
      
      
    (Feature 3: Specify Numbers of Events)
    
     
     As a user, I should be able to choose the amount of events that are listed. So I will able to know how many events are being shown at one time. 
     
    *Scenario 1*: When the user hasn't specified a number, 32 is the default number. 
      Given: The user searched for event results for a city. 
      When: The user does not choose a specific amount of search results. 
      Then: The default search amount will be set to 32 for the city. 
      
     *Scenario 2*: The user can change the number of events they want to see. 
       Given: The user opened the search results. 
       When: The user is able to change the default number. 
       Then: The results will change from the default number to what the user selected. 
       
       (Feature 4: Use the App When Offline)
       
    As a user, I should be able to use my application offline. So that I can still use the application without internet connection.
    
    *Scenario 1*: Show cached data when there's no internet connection.
      Given: The application has no internet connection. 
      When: The data is stored.
      Then: The data will be shown.
      
     *Scenario 2*: Show error when user changes the settings (city, time range).
       Given: The user opens the settings tab.
       When: The user changes the settings. 
       Then: An error will appear. 
       
     (Feature 5: Data Visualization)
      As a user, I should be able to view a chart or list of the events taking place. So that I can sort through my options. 
      
    *Scenario 1*: Show a chart with the number of upcoming events in each city. 
      Given: The user selected a city.
      When: The user clicks on the upcoming event for the city. 
      Then: A chart will appear with the a list of events coming up in the city.
       
   
  
 
