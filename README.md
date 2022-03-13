# Rocket-League-Goal-Probability

- Dataset: 100 1v1 ssl replays from https://ballchasing.com/group/project-rqtdzuwqlp
- Cleaning: Created column that finds which team scores the next goal. Removed rows after goal was scored. Removed rows where no goal was scored by the end of regulation
- Models: Logistic (not created yet), Random Forest, XGBoost
-
- Issues: I think that I forgot to remove rows after a goal was scored. However, I do not think this should make a huge difference. 
