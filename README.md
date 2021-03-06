# Mini Vote

  Site to collaboratively define a list of items and vote on them together.


## Requirements

   * [Node.js](https://nodejs.org/en/); tested with 8.9.4, 8.11.3 LTS, and v14.15.3
   * [NPM](https://www.npmjs.com); tested with 5.6.0, 6.1.0, 6.3.0, and 6.14.9
   * [Meteor](https://www.meteor.com/install); tested with 1.6-1.6.1.4


## Notes

   TODO


## Installation

   `git clone https://github.com/lkremkow/mini-vote.git mini-vote`

   `cd mini-vote/`

   `npm install`

   If you are on MacOS, also run: `npm install fsevents` (fsevents is only on MacOS, not Linux). It's not included in package.json, so you need to manually add it in on MacOS.


## Re-Installation

   `cd mini-vote/`

   `git fetch --all`

   `git reset --hard origin/master`

   `git pull origin master`


## Usage

   Start the site locally:

   `meteor run --port 127.0.0.1:4050`

   Delete everything:

   `rm -rf .meteor/local/`

   `rm -rf node_modules/`


## Source

   https://github.com/lkremkow/mini-vote.git


## Contributing

   TODO: Write instructions how to reports bugs and contribute. Link to public repository.


## History

   TODO: Write history.


## Credits

   TODO: Write credits.


## License

   Copyright (C) 2018 Leif Kremkow <kremkow@tftg.net> (http://www.tftg.com)

   This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, version 3 of the License.

   This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.

   You should have received a copy of the GNU Affero General Public License along with this program. If not, see <http://www.gnu.org/licenses/>.
