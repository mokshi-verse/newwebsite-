project title: Web3 Resume Builder with NFT Badges
domain: web development 
problem statement: A full-stack web application for building professional resumes with blockchain-themed styling and NFT skill badges stored on the Aptos blockchain.

abstract: Web3 Resume Builder with NFT Badges is a full-stack web application designed to revolutionize the way professionals showcase their skills. This project combines modern resume-building features with the power of blockchain technology, allowing users to mint and display verifiable NFT skill badges on their resumes via the Aptos blockchain.
The platform offers five professionally designed blockchain-themed resume templates, providing users with a visually appealing and futuristic portfolio. Users can log in securely using Gmail authentication, choose a resume template, customize it with personal and professional details, and export it as a PDF or HTML file. The application features auto-save functionality to preserve user changes every 25 seconds, ensuring a seamless and uninterrupted editing experience.
A standout feature is the integration of Petra Wallet, enabling users to mint skill badges as NFTs. These badges serve as blockchain-verified credentials, adding authenticity and uniqueness to a resume. The user can add badges by connecting their wallet, inputting badge details, and confirming the minting transaction.
Built using Python Flask for the backend and HTML/CSS/JavaScript with Bootstrap for the frontend, the application uses SQLite via SQLAlchemy for local data management. Styling is enhanced with neon high-tech UI components from uiverse.io, delivering a modern Web3 aesthetic.
This project demonstrates the convergence of traditional resume-building tools and decentralized technology, offering a unique solution for professionals in the blockchain era.

## Technology Stack
- **Backend**: Python Flask
- **Database**: SQLAlchemy with SQLite
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Blockchain**: Aptos blockchain for NFT badges
- **Styling**: Custom CSS with neon high-tech elements from uiverse.io

## Features
- **Blockchain-Themed Resume Templates**: Choose from 5 professionally designed templates with blockchain and Web3 styling
- **NFT Skill Badges**: Mint verifiable skill badges as NFTs on the Aptos blockchain
- **Petra Wallet Integration**: Connect your Petra wallet to mint and manage NFT badges
- **Gmail Authentication**: Secure login with your Google account
- **Auto-Save Functionality**: All changes are automatically saved every 25 seconds
- **Export Options**: Download your resume as PDF or HTML
- **Responsive Design**: Works on all device sizes
  
## Installation
1. Clone the repository
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Install wkhtmltopdf for PDF generation:
   ```
   sudo apt-get install wkhtmltopdf
   ```
4. Set up environment variables:
   ```
   export FLASK_APP=app
   export FLASK_ENV=development
   export SECRET_KEY="your-secret-key"
   export GOOGLE_CLIENT_ID="your-google-client-id"
   export GOOGLE_CLIENT_SECRET="your-google-client-secret"
   export APTOS_NODE_URL="https://fullnode.devnet.aptoslabs.com/v1"
   ```
5. Run the application:
   ```
   flask run
   ```
   
Alternatively, you can use the provided run.sh script:
```
chmod +x run.sh
./run.sh
```

## Project Structure

- `/app`: Main application code
  - `/models.py`: Database models
  - `/aptos_client.py`: Aptos blockchain integration
  - `/routes`: API routes and endpoints
- `/static`: Static assets
  - `/css`: Stylesheets
  - `/js`: JavaScript files
  - `/images`: Images and icons
- `/templates`: HTML templates
  - `/resume_templates`: Resume template files
- `/tests.py`: Unit tests

## Usage

1. Sign in with your Google account
2. Choose a resume template
3. Customize your resume with your information
4. Connect your Petra wallet to mint NFT skill badges
5. Add your NFT badges to your resume
6. Export your resume as PDF or HTML

## NFT Badge Integration

The application uses the Aptos blockchain to mint and store NFT skill badges. Each badge represents a skill or certification that can be verified on the blockchain. The badges are displayed on your resume to showcase your verified skills.

To mint a badge:
1. Navigate to the NFT Badges page
2. Connect your Petra wallet
3. Fill in the badge details (name, description, image)
4. Click "Mint NFT Badge"
5. Confirm the transaction in your Petra wallet

## Development

To run the application in development mode:
```
export FLASK_ENV=development
flask run
```

To run tests:
```
python tests.py
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- Aptos blockchain for NFT functionality
- uiverse.io for neon high-tech CSS elements

website preview:


![Screenshot 2025-04-13 112040](https://github.com/user-attachments/assets/3b380a97-84ef-447b-b9ba-c288967d2061)

![Screenshot 2025-04-13 112137](https://github.com/user-attachments/assets/c2984f50-f72d-4f34-b013-d0f0ecd5e2f4)

![Screenshot 2025-04-13 112154](https://github.com/user-attachments/assets/ebab879c-071c-4b7f-8f61-e805739bfe5e)

![Screenshot 2025-04-13 112223](https://github.com/user-attachments/assets/d4225b28-bb6b-4c31-a7be-e65d05ced4ef)
