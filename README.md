# Unsupervised Machine Learning for Spotify Playlist Creation

## Summary
This project focused on clustering a dataset of 5,000 Spotify songs to create thematic playlists based on similar audio features. The goal was to apply unsupervised machine learning techniques, minimizing human intervention, to automatically generate cohesive and enjoyable playlists.

## Languages and Libraries Used
- **Languages**: Python
- **Libraries**: Scikit-Learn (for dimensionality reduction and clustering algorithms)

## Key Learnings
- Gained practical skills in dimensionality reduction, using Principal Component Analysis (PCA) to simplify the data while retaining variance.
- Developed proficiency in implementing and tuning unsupervised ML algorithms, especially k-means clustering.
- Learned the importance of balancing machine-driven clustering with human evaluation, especially in subjective areas like music curation.

## Challenges Overcame
- Determining an optimal number of clusters required experimenting with various *k* values; settled on *k=24* after analysis.
- Addressed data preprocessing by normalizing features such as tempo, energy, danceability, and valence to improve clustering results.

## Additional Reflections
The project showcased the capability of machine learning to organize music data efficiently, yet highlighted that certain subjective tasks benefit from human insight. Despite clustering success, some outliers indicated that human intervention remains valuable for refining playlists, combining both machine efficiency and human intuition.
