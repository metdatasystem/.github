# Welcome to the Meteorological Data System (MDS)

The MDS aims to be an open-source central data collection, storage, and distribution system for all weather and climate data.

Current efforts are focused on building the system for the United States and NOAA (since their data is free), but the ultimate goal is to support data collection and sharing internationally.

## Previous attempts

This project is based on a few original concepts and is more like version 4 of an idea.

[Version 1](https://github.com/TheRangiCrew/NWWS-SERVER) was written in TypeScript and utilised Supabase for the database. It wasn't very good and crashed every couple of hours it ran.

[Version 2](https://github.com/TheRangiCrew/NWWS-GO) was the first implementation written in Go and used SurrealDB for the database. It was an improvement and could run for some time without crashing but was still unreliable and had a lot of inaccurate data.

[Version 3](https://github.com/TheRangiCrew/mds) is what the current implementation is derived from. A lot of learning and practice came from this version and was the most reliable version at the time.
It initially used SurrealDB, like version 2, but I quickly fell back in love with PostgreSQL and reimplemented everything to use it.

While this version is technically version/attempt 4, it is in a new repo and a new space (organisation). Therefore, versions and tags are not derived from any versions or tags that may or may not have existed in other repos.
