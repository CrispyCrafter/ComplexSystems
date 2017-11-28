# ComplexSystems
Brief overview and informational resources on working with complex hierarchial systems via Python

The goal of this repository is to provide interactive, explorartory information on the mathematics, theory and python modules to manipulate and understand complex hierarchial systems.
The following topics are to be discussed in depth and explored within the context of python.

1. Natural language processing and sentiment analysis - *Computing sense from sentence*

2. Graph theory as complex mathematical structues -
*Traverse, characterise and manipulate all the birds of all the feathers*
3. Hyperbolic Geometry and hierarchial data structures -
*I think therefore I ... remap space into something more suitable for exponential information*
4. Bayesian statistics - *Helping Plato's prisoners understand the sun better.*

#### 1. Natural language processing and sentiment analysis


#### 2. Graph theory as complex mathematical structues
*Traverse, characterise and manipulate all the birds of all the feathers*


#### 3. Hyperbolic Geometry and hierarchial data structures
*I think therefore I ... remap space into something more suitable for exponential information*

Off the bat it seems a bit out of place looking into Hyperbolic geometry for simple hierarchial data. Afterall we have access to a plethora of excellent [Data Models](https://en.wikipedia.org/wiki/Data_model), each of which with it's own use case, optimisations and programmatic implementations. The problem comes in when you 'actually' go out into the wild to find or scrape the most juicy, abundant, scattered and ['dirty'](https://www.forbes.com/sites/gilpress/2016/03/23/data-preparation-most-time-consuming-least-enjoyable-data-science-task-survey-says/#394af0756f63) data to satisfy your needs. All this precious information now existing as a snapshot of your guesstimated imposed data model. What if we could remap and infer the 'latent hierarchy' of our new prised dataset, without the need to explicilty, and often erroneously imposing a novel data model.

Enter [Nickel and Kiela](https://arxiv.org/pdf/1705.08039.pdf) with their excellent paper on: *Poincaré Embeddings for Learning Hierarchical Representations*. So before we jump head first into a Hyperbolic rabit-hole, let's first look into exaclty [where](https://en.wikipedia.org/wiki/Feature_learning) their work would apply, why [Poincaré](https://en.wikipedia.org/wiki/Poincar%C3%A9_disk_model) and what is meant by [embedding](https://en.wikipedia.org/wiki/Embedding).

Starting from the back, embedding in this context can be thought of as mathematical means of representing a arbitrary object in an 'invariant' structure of another. To explain this differently imagine looking straight down at yourself from wherever you are. Now take the position of all the items around you as representing points on a flat surface. On the surface, or, structure of the flat surface all these object are black dots, yet each represent a physical object which you can see and touch. In this sense you have embedded three-dimensioanal objects as points in a two-dimensional structure. Now because you've embedded complex objects in a more manageable, quantifiable space you can go ahead and measure the distance between points, figure out if there is some pattern to where objects are scattered around you, and perhaps decide to tidy up. Neat right :)

Now imagine instead of looking straight down at yourself, from where you are, you decide to go straight up beyond the tallest object you can see. More stuff right? Ok no problem just more points on the flat surface. Now head for the clouds, and now the atmosphere and now space. Each time you went up, more and more 'things' needed to be mapped sure, but more importantly your flat surface you used to emded 'things' on now seems to no longer work so well. To visualise this take a flat peice of paper and wrap it around a ball or an orange or whatever curved object you can find. Try to cover the object entirely. Go ahead and draw a straight line around the object so that the end stops where the line began. You'll notice a few strange things. First off the line should now be broken into shorter segements, depending on how you folded the paper. Next up you'll notice even though the initial line was, point to point, a reasonably straight line, it's now become round. Ok that's easy you say, "just make you're flat a surface ball". Nothing really changes, does it? When your're close enough to yourself locally, everthing seems flat and the curvature 'goes away', when you're up in space curvature is really important. Congratulations you've embedded the earth and all visible object into a spherical coordinate system in three dimensions. For alternative strategies have a look at how we currently [map](https://en.wikipedia.org/wiki/Map_projection) the earth.


![The world on Goode’s homolosine projection. 15° graticule. Imagery is a derivative of NASA’s Blue Marble summer month composite with oceans lightened to enhance legibility and contrast. Image created with the Geocart map projection software.](https://upload.wikimedia.org/wikipedia/commons/f/f2/Goode_homolosine_projection_SW.jpg "Logo Title Text 1")


Ok so what does this all mean you must ask? When we mapped your immediate surroundings into flat space or curved space we allowed opened up your world to measure, study and perhaps predict patterns in a embedded mathematical framework. In computer science we often try to take one object or set of object and 'remap' them into a 'uniform' framework from where we can measure, manipulate and hopefully predict patterns. More often than not we remap objects like words, images, phrases or concepts into abstract spaces beyond three dimensions, or N-dimensional space as a mathematician might say. By doing we hope to group similar items, and attempt to predict outcomes based on the relative position of objects.

Simply put the paper presented by [Nickel and Kiela](https://arxiv.org/pdf/1705.08039.pdf) have managed to find a way to embed hierarchical information into a different 'coordinate' system or uniform space, which upon optimisation groups similar object closer to one-another. The refference to the mathematician [Poincaré](https://en.wikipedia.org/wiki/Poincar%C3%A9_disk_model) is the method they used to project or map these objects in N-dimensional hyperbolic space, similar to how we map the earth onto a flat surface. For more information on hyperbolic geometry you can refer to excellent [course material](http://torus.math.uiuc.edu/jms/m302/02Sp/handouts/) of George Francis

To interact with this strategy of embedding information from python go ahead and check out [TatsuyaShirakawa's](https://github.com/TatsuyaShirakawa/poincare-embedding) github repo.

# 4. Bayesian statistics
*Helping Plato prisoners see the sun quicker.*
