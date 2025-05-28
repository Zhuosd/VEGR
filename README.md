### Notice!!

The codebase of VEGR will be publicly released upon the acceptance of the corresponding paper submission. Our goal is to promote transparency, reproducibility, and further development of voice-aware recommendation techniques.

Please stay tuned — we look forward to sharing our implementation soon.

# VEGR
Voice Empowered Graph Representation for Personalized Recommendation Assistants

Recommendation system, currently a highly sought-after technology, is extensively utilized to assist users in discovering preferred content from vast amounts of information by learning individual interactions. However, existing RS methods rely on text-based interactions (e.g., user-item), overlooking the potential preference signals carried by users’ voice, which could enhance accessibility, provide more diverse data insights, and increase user engagement. The advent of sophisticated speech processing technology has created a wealth of potential for the development of authentic voice-based RSs, offering promising avenues for future growth and innovation. In this paper, we propose a novel voice-empowered recommendation framework named VEGR, which captures the intrinsic semantic correlation between voice and historical interactions, representing voice preference within a collaborative filtering paradigm. To better encode the voice characteristics of users, VEGR establishes a semantic conduit between voice and text feature information through feature retrieval. Moreover, all the voice and text representational information is smooth upon high-order graph convolutional networks, which is to learn user-voice-item interaction patterns and thereby facilitating the prediction of user preferences. Extensive experiments validate the feasibility and consistent superiority of our method over existing text-based recommendation models.


