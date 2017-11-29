# DataMoviz Data

This repository contains data used for the [DataMoviz project](https://github.com/quentinus95/datamoviz).

## Data import

Be sure to drop your `datamoviz-api` database before import.

1. Install [Git LFS](https://git-lfs.github.com/)
2. Run `git lfs install`
3. In the DataMoviz repository, run the following command `git submodule update --init --recursive`
4. Go in `data/` directory, and run `mongorestore --collection movies --db datamoviz-api dump/datamoviz-api/movies.bson`

You're done!
