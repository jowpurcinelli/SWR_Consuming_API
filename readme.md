SWR is a library for API consuming.
It is not made to substitute other api technologies (Axios,Fetch, etc...). It is a wrapper around other libraries, that make posible apply a "cache invalidation strategy" Providing a better User Eperience.
Every http request the user made, is saved in the cache. Any user interaction, will first search for the results inside of the cache. If it already exists, will revalidate the dates that appeared lately, or not, as the info demands. 
It can be intergrated with any back-end technologie.

- Real time requests.
- GraphQL





