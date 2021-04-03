# Visualizing Latitudinal Trends

## Background
OBJECTIVE: Data is more powerful when we share it with others!
TASK: Create a visualization dashboard website using visualizations created in a past assignment. Specifically, we'll be plotting [weather data](Resources/cities.csv).

ORGANIZATION: Create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements
1. The website must consist of 7 pages total, including:
  * A [landing page](#landing-page) containing:
   * An explanation of the project.
   * Links to each visualizations page
   * Include a sidebar containing preview images of each plot whereas clicking an image should take the user to that visualization.
  * Four [visualization pages](#visualization-pages), each with:
   * A descriptive title and heading tag.
   * The plot/visualization itself for the selected comparison.
   * A paragraph describing the plot and its significance.
  * A ["Comparisons" page](#comparisons-page) that:
   * Must contain all of the visualizations on the same page so we can easily visually compare them.
   * Hint: Uses a Bootstrap grid for the visualizations.
     * Don't forget to consider different screen sizes. The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
  * A ["Data" page](#data-page) that:  
  * Using a bootstrap component, display a responsive table containing the data used in the visualizations.
2. Navigation: The website must, at the top of every page, have a navigation menu that:
 * Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
 * Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
 * Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
 * Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).
3. Deployments: the website must be deployed to GitHub pages, with the website working on a live, publicly accessible URL as a result.
