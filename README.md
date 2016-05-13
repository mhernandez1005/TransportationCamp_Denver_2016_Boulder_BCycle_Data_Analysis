# Welcome, this page is about Boulder BCycle data analysis sponsored by TransporationCamp Denver 2016

http://transportationcamp.org/events/colorado-2016/

Transportation camp encourages data analysis by providing 3 types of data.
Visit their website to learn more about transporation camps unconference.

The remaning information is about the analysis of Boulder BCycle data.

We wanted to use the data to visualize the Boulder BCycle goals.

Boulder BCycle has several goals to help the community.
http://blog.boulderbcycle.com/about/

Here are a few we picked to drive our investigation:

  - Encourage more people in Boulder to ride a bike—or bike more often—to promote their personal health as well as our community’s quality of life.
  - Demonstrate how bike-sharing programs can make communities healthier, stronger, friendlier, more mobile and more vital.
  - Demonstrate how bike-sharing programs can help minimize mobility and social equity disadvantages experienced by low-income or other marginalized people.
  - Put more smiles on the faces of more people in Boulder—all day, every day!

The following questions were developed with Boulder BCycle goals in mind:

  - Are more bcycles being checked out?
  - Is the number of users going up?
  - Can we quantify the average time riders are using the bikes?
  - Can we quantify the total time riders are using the bikes?

Filtering and Grouping:
  
  - Included only Boulder based riders.
  - Group data by rider_id
  - Created a Primary key between rider_id and checkout_location

Initial draft findings

![alt tag](https://github.com/mhernandez1005/TransportationCamp_Denver_2016_Boulder_BCycle_Data_Analysis/blob/master/static/images/Count%20of%20BCycle%20Trips%20Per%20Month%20for%20different%20pass%20types.png)

  - The number of checkouts is increasing for all pass types.
  - As expected, the season has a strong influence on the number of checkouts.
  - The chart was made by binning the checkout counts by year-month.
  - The chart was grouped by pass type.
