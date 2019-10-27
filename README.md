This fork is mainly for HONDA Bosch cars
based on Zorrobytes curvatureFactorLearner 0.6.5
, plus:
+ press gas without disangagement
+ no alert sound for "Turn Exceeds Steering Limit"
+ camera offset 0.02
+ LQR (more tourque for Honda)

It contains a learner to learn your curvature factor. This means no more hugging curves, and has some ability to autotune controls.

Panda update required!
1. Send:  cd /data/openpilot/panda/board && pkill -f boardd
2. Send: cd /data/openpilot/panda/board && make
3. reboot
