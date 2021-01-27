# Hub

The hub is the center of the 3D-Beacons network. It has the following functions:
  1. Holds the [registry](https://github.com/3D-Beacons/3d-beacons-registry) which records meta-information about all participating Beacons, and lists all API endpoints that each individual beacon supports.
  2. Runs monitoring process to check the status of each beacon
  3. Processes the user's request, converts into the corresponding calls and sends to all available beacons
  4. Retrieves the results from all available beacons and collates to the user

More details could be found in the [repository](https://github.com/3D-Beacons/3d-beacons-hub-api) 