<h3> Problem Definition </h3>

<p> This project was done as part of a hackathon organized by ShopUp. </p>

<p>ShopUp helps small businesses (merchants) by collecting their products and distributing them to their respective customers. This process goes through several steps.</p>

<p>Firstly, the merchants upload their product information on the system. Then, ShopUp sends delivery persons to the merchants to collect their products. The products are brought to one of the four hubs, which are situated at Mirpur, Kalabagan, Malibagh and Mohakhali respectively. Then, at around midnight, the products are distributed to the different hubs according to their respective delivery orders. Finally, in the morning, the products are dispatched for the customers from the hubs.</p>

<p>In total, ShopUp has to deal with 500-600 product deliveries on a single day. Our goal is to automate the sorting and scheduling process, which could significantly decrease the delivery cost and time.<p>

<h3> The dataset </h3>

<p>We collect the dataset from <i><strong>openstreetmap.org</strong></i>. The dataset consists of different random coordinates in Dhaka. We use <strong>281</strong> data points in total as delivery points.</p>


<h3> Output </h3>
The outputs of the work are stored in the '/maps' folder.
<h3> Remaining Works </h3>
<ul>
<li>We have tried k-means, spectral and affinity propagation models for clustering the delivery points. There are several other models like Gaussian mixture, DBSCAN, JarvisPatrick, Birch and so on. We have yet to test which one is actually best in our country's context, where we have to deal with heavy traffic conditions and a very dense graph.</li>
<li>We have not yet integrated the part where the delivery persons collect the products from the merchants.</li>
<li>We have not yet implemented the interhub communication.</li>
</ul>

<h3>Thank you</h3>
<p>In this project, 
<list>
    <li>I, Nahian Ashraf, have dealt with data visualization and the implementation.</li>
    <li>Muntasir Wahed has dealt with the concept and modeling the solution as well as the implementation.</li>  
    <li>Abid Naziri Sami has collected all data.</li>
</list>    
</p>
