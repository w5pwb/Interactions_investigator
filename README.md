# Interactions_investigator

A copy of the original email sent ot me detailing what I am supposed to do.

"Since multiple interactions can be curated from the same paper and interactions between the same two genes/gene products, A-B, can be curated from multiple papers, we'd also like to know how many distinct gene pairs are represented in IMEx, how many in FlyBase and how many gene pairs they have in common. This will be your mission.

One little difficulty in this task is that the FlyBase.txt file uses FlyBase gene IDs ( FBgn numbers) in columns 1 and 2 while the Dmel_intact2.txt file mostly uses UniProt IDs so we need to convert the UniProt IDs to FBgn IDs. We haven't yet done this conversion but if you'd like to think about that I'm including an ID mapping file, idmapping2.txt, which has UniProt IDs in column 1 and FBgn IDs in column 2. We will also send you updated files with IDs that can be directly compared when we have them. This is just to get you started thinking about the project."

I interpreted this as writing code to first find all unique interactions in both the imex data and the FB data and then compare the two to see how many unique interactions the data sets shared with each other.
