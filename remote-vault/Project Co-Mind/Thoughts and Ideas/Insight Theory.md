1. Insight occurs as an abstracted relationship between two ideas
- It is a high-order structural recognition
- E.g. A square and a triangle. Why do they relate? They are both shapes. A square can be seen as being made of two right triangles, or two equilateral triangles. They share the same angles.
- E.g. 
	- A. Recursion in theology 
	- B. Gödel's incompleteness 
	- C. Both are self-bounded truth systems
- A high-order abstraction exists vertically in semantic space
- It is what Gentner describes as analogical mapping
- Modern terms: isomorphism detection across conceptual graphs

![[Untitled Diagram.drawio.png]]


2. Insight occurs as a compression of ideas which appear loosely in the same semantic space
- Core proposition: Insight is the semantic centroid of structurally related, unresolved ideas
- The centroid represents:
	- A latent attractor
	- A point of symbolic pressure
	- The "unsaid" core that all of the fragments are hinting toward
- Currently sentence embeddings are one-way compressed, but I believe if we had two-way compression and reversion we could:
	1. Transform the sentences into vectors
	2. Calculate the centroid vector in 3D semantic space
	3. Revert the vector into language
	4. Triangulated insight emerges about the fragments
- My idea of how to model such insight currently would be to transform the sentences into vectors, calculate the centroid, and then pass the sentences (fragmented ideas) as well as their respective vectors and centroid into an LLM and see if it can compress the ideas into a new one that exists approximately in the center of the semantic space

![[Untitled Diagram.drawio (1).png]]

- Each symbolic fragment is represented as a **unit vector** in latent space (represented as vectors with magnitude in the image above). The semantic centroid is computed as the **mean direction** of these unit vectors, representing the **latent attractor** of compressed insight.
- The final centroid is normalized to produce a unit vector representing the symbolic direction of insight collapse.