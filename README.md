# stephanta 🎅🏻
This year, the Rings and I are taking our Secret Santa to Zoom, and Stephanie (aka Stephanta) is picking up/dropping off our gifts from across the HRM to maintain our anonymity. To ensure she spends the least amount of time possible on the road, the route distance would need to be minimized while also minimizing the number of stops, so the order in which the houses are visited must be considered. 

This optimization problem seems like some cruel and twisted version of the travelling salesman problem, so I attempted to throw together a solution using the Google Maps API Distance Matrix. This brute force approach of testing all permutations could definitely use some work, but it's the best I could come up with in an hour, and was totally worth it to save Steph some gas. Enjoy! 

---

Instructions:
1. Download and open the Jupyter Notebook
2. Upload 'secretsanta.csv' (each row includes name, postal code, and recipient name) to the notebook
3. Replace the `/` in `gmaps = googlemaps.Client(key='/')` with the API key I provided
4. Run each block to find the optimal route!
