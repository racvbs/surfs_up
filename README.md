# surfs_up

Module 9 - Challenge

### ### Purpose

In order to invest better, we must do the analysis of climate

### Information

We have the database and we're going to analyse climate in june and december

## Results

June:

![image](https://user-images.githubusercontent.com/85086918/143178784-891b1ce2-d4dd-4343-86e3-bd9c5590e42f.png)

December:

![image](https://user-images.githubusercontent.com/85086918/143178807-4b960590-8d22-4f36-81ab-a3ade4af0f54.png)

```
Technical Notes:
We use sqlite as follows:

# Python SQL toolkit and Object Relational Mapper
import sqlalchemy
from sqlalchemy.ext.automap import automap_base
from sqlalchemy.orm import Session
from sqlalchemy import create_engine, func

engine = create_engine("sqlite:///hawaii.sqlite")

# reflect an existing database into a new model
Base = automap_base()
# reflect the tables
Base.prepare(engine, reflect=True)

```

**Conclusion: Temperatures are higher in june, but I think this is alredy known, we just demonstrate the data.**
