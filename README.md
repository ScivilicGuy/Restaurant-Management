# README #

This project is a restaurant management website that can be used by both diners and restaurants. Diners can find vouchers for registered restaurants and restaurants can manage their menu, vouchers, loyalty system and profile. 
Included functionalities include user and restaurant profile management, vouchers, search filtering, reviews, recommendations, loyalty system and chatbot. 

### BACKEND SETUP (DO FIRST - terminal 1) ###

1. Open QTerminal 
2. Create a folder to store project (e.g. mkdir COMP3900)
3. Change directory to created folder (e.g. cd COMP3900)
4. Download ZIP file from Github and extract to project folder (e.g. COMP3900)
5. Run 'cd {PRESS TAB}' to change to downloaded project folder
6. Type in: sudo bash setup.sh
7. Enter root password: lubuntu
8. Type in: pip install flask==2.3.2 flask_cors==4.0.0 apscheduler==3.10.1
9. Type in: cd backend
10. To run the backend, type in: python3 -m src.server

### FRONTEND SETUP (terminal 2) ###

1. Open another instance of QTerminal 
2. Change directory to project folder (e.g. cd COMP3900/capstone-project-3900w16afiveguys-1-main)
3. Type in: curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
4. Type in: source ~/.bashrc
5. Type in: nvm install 18.6.0 
6. Type in: npm install --global yarn 
7. Type in: cd frontend
8. Type in: yarn install
9. To run the frontend, type in: yarn start

NOTE: allow location access to be able to use the application
