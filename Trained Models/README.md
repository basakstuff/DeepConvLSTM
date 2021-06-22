## Task A: Modes of Locomotion
The goal of this task is to classify modes of locomotion from body-worn sensors. A model with nine different hyperparameter changes has been trained for this task. In addition, Null and No Null classes were also evaluated, and their results were compared.

## Task B: Gestures
This task concerns the recognition of right arm movements performed in the daily activities’ scenario included in the OPPORTUNITY dataset. A full set of sensors are under consideration for this task, including a motion jacket, 12 Bluetooth accelerometers fitted to the body, and inertial sensors in the feet.

## Tests 

|     Test Name    |     Batch Size    |     Optimizer    |     Filter Size    |     # of Filters    |     Epochs    |     Sliding Window Step    |     Sliding Window     Length    |
|------------------|-------------------|------------------|--------------------|---------------------|---------------|----------------------------|----------------------------------|
|     A            |     100           |     RMSprop      |     5              |     64              |     50        |     12                     |     24                           |
|     B            |     100           |     RMSprop      |     5              |     64              |     50        |     12                     |     24                           |
|     C            |     100           |     RMSprop      |     5              |     64              |     100       |     12                     |     24                           |
|     D            |     200           |     RMSprop      |     5              |     64              |     50        |     12                     |     24                           |
|     E            |     200           |     RMSprop      |     5              |     64              |     100       |     12                     |     24                           |
|     F            |     100           |     RMSprop      |     5              |     92              |     50        |     12                     |     24                           |
|     G            |     100           |     RMSprop      |     5              |     128             |     50        |     12                     |     24                           |
|     H            |     100           |     RMSprop      |     5              |     64              |     50        |     12                     |     128                          |
|     I            |     200           |     RMSprop      |     5              |     92              |     100       |     12                     |     24                           |
|     J            |     100           |     ADAM         |     5              |     64              |     50        |     12                     |     24                           |
|     K            |     200           |     ADAM         |     5              |     64              |     100       |     12                     |     24                           |
