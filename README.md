Unit 12 | Assignment - Web Visualization Dashboard (Lattitude)
Lattitude - Latitude Analysis Dashboard with Attitude

The website must consist of 7 pages total, including:

 1. A landing page(landing.html) containing:
      An explanation of the project.
      Links to each visualizations page.
 2. Four visualization pages (visualization-image-1.html,visualization-image-2.html, visualization-image-3.html,visualization-image-4.html      )each with:
       A descriptive title and heading tag.
       The plot/visualization itself for the selected comparison.
       A paragraph describing the plot and its significance.
  3. A "Comparisons" page(comparisons.html) that:
       Contains all of the visualizations on the same page so we can easily visually compare them.
       Uses a bootstrap grid for the visualizations.
       The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
  4.  A "Data" page (data.html) that:
          Displays a responsive table containing the data used in the visualizations.
          The table must be a bootstrap table component.
          
Run HTML:
  HTML, style.css, output_data/fig, output_data/cities.csv, assets/css, assets/js

Hint: How to make bootstrap dropdown to work: from 
       I figured it out and the simplest way to do this ist just copy and past the CDN of bootstrap link that can be found in https://www.bootstrapcdn.com/ and the Jquery CDN Scripts that can be found here https://code.jquery.com/ and after you copy the links, the bootstrap links paste on the head of HTML and the Jquery Script paste in body of HTML like the example below:

    <!DOCTYPE html>
    <html>
      <head>

        <title>Purrfect Match Landing Page</title>
        <!-- Latest compiled and minified CSS -->
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
        <!--<link rel="stylesheet" href="griddemo.css">

        <!-- Optional theme -->
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css">
        <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">

      </head>

      <body>

        <!-- Latest compiled and minified JavaScript -->
        <script src="https://code.jquery.com/jquery-3.1.1.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js">      </script>    
      </body>
    </html>
