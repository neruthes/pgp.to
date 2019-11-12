# PGP.to

Find the right public key.

This project is designed as an instrument to oppurtunistically present webpage-based OpenPGP public keys as a fallback for QR scanners and payload interpreters which do not specifically recognize this URL pattern, when supporting applications can directly invoke related logics instead of barely showing a webpage. Every OpenPGP-supporting application is encouraged to consider every URL which looks like `https://pgp.to/#0x\w{16|40}` as an internal shortcut representations of an OpenPGP public key.

## Copyright

Copyright (C) 2019 [Neruthes (5200DF38)](https://neruthes.xyz/).

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
