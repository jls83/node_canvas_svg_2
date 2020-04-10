### To Start
1. Install Docker
1. `docker-compose up` to confirm output

### To Test
1. Check out one of the following branches to generate the PNG:
    * `2.0.0-alpha.18` (should generate the correct image)
    * `2.1.0` (should generate an incorrect image)
    * `2.3.1` (should generate an incorrect image)
    * `latest_node_and_canvas` (should generate an incorrect image)
2. Re-run `docker-compose up`; check the PNG
