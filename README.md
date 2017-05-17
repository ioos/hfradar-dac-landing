# HF Radar DAC
The front page / home page for IOOS HF-Radar DAC


# Installation

1. Download and install nodeJS (should come with npm)
2. Install bower
   
   ```
   npm install -g bower
   ```

   _You may need to run as sudo_

3. Use node to build the project dependencies

   ```
   npm install
   ```

4. Use bower to install the UI depencies

   ```
   bower install
   ```

5. Run the project

    ```
    bin/www
    ```

# Developing

Most of this project are static files. The initial pages are loaded as jade
templates.  
