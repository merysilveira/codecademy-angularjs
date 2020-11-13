# Bolt Network 1

Bolt Network wants to create an AngularJS app for their program pages. The program page displays information about a show’s airing time on the network.


#### 1. Create a new module:
1. In **js/app.js**, create a new module named `BoltNetworkApp`.
2. In the view, use `ng-app` to attach the `BoltNetworkApp` module to the `<body>` element.

#### 2. Create a new controller:
1. In the controller, make a new property called `$scope.program`, and set it equal to the following object


    {
      series: "Sherlock",
      series_img: "img/sherlock.jpg",
      genre: "Crime drama",
      season: 3,
      episode: "The Empty Hearse",
      description: "Two years after his reported Reichenbach Fall demise, Sherlock, who has been cleared of all fraud charges against him, returns with Mycroft's help to a London under threat of terrorist attack. John has moved on and has a girlfriend, Mary Morstan. Sherlock enlists Molly to assist him, but when John is kidnapped by unknown assailants and is rescued by Sherlock and Mary, John returns to help find the terrorists and an underground plot to blow up the Houses of Parliament during an all night sitting on Guy Fawkes Night.",
      datetime: new Date(2014, 11, 31, 21, 00, 00, 00)
    }
2. In the view, use `ng-controller` to attach `MainController` to the `<div class="main">` element.

#### 3. Display the data in the view:

1. Inside `<div class="main">`, display the details of `program` using expressions.
2. Use the `date` filter to format the **Date**, **On air**, and **Time** fields as shown in the [preview](https://content.codecademy.com/projects/4/bolt-network-1/index.html "preview"). 

#### 4. View the result by visiting in the browser.
1. Visiting index.html in the browser