# circleci-orbs
Public CircleCI Orbs by AirSwap

## To publish manually

1) Create a new orb
`circleci orb create airswap/ORB_NAME`

2) Validate the orb
`circleci config validate ORB_NAME.yml`

3) Publish a new orb
`circleci orb publish ORB_NAME.yml airswap/ORB_NAME@0.0.1`