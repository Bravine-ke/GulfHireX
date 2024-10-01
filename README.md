
# GulfHireX

**GulfHireX** is an overseas recruitment platform designed to connect skilled professionals with job opportunities in the Gulf region. It offers a wide range of services including job placement, visa assistance, interview coaching, and post-placement support. The platform streamlines the recruitment process, ensuring both candidates and employers find the right match.

## Features

- **Job Placement Services**: Helping candidates secure employment with trusted Gulf-based companies.
- **Resume Writing Assistance**: Professional help to improve candidate resumes.
- **Interview Coaching**: Guidance to help candidates succeed in job interviews.
- **Visa and Immigration Support**: Assistance with the visa process to work abroad.
- **Cultural Orientation**: Preparing candidates for their new work environment and cultural practices.
- **Post-Placement Follow-Up**: Ensuring a smooth transition after placement with ongoing support.
- **Skills Assessment**: Evaluating candidates to match them with the right job opportunities.
- **Networking Opportunities**: Connecting professionals through industry events and workshops.

## Technology Stack

- **Frontend**: HTML, CSS (Tailwind CSS)
- **Backend**: Python (Flask)
- **Database**: SQLite (or any preferred database solution)
- **Images & Media**: Hosted locally or through cloud storage
- **Deployment**: Azure (or any preferred cloud hosting service)

## Installation

### Prerequisites

- Python 3.x installed on your system
- Flask installed (`pip install Flask`)
- Set up a virtual environment for the project (optional but recommended)
  
### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repo/gulfhirex.git
   cd gulfhirex
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:

   ```bash
   flask run
   ```

   The app should now be running at `http://127.0.0.1:5000/`.

### Folder Structure

```
GulfHireX/
├── static/
│   ├── images/          # Store images for services and company logo
│   ├── css/             # Custom stylesheets
├── templates/
│   ├── base.html        # Main layout template
│   ├── services.html    # Services page
│   └── about.html       # About us page
├── app.py               # Main Flask application file
├── README.md            # Documentation
└── requirements.txt     # Project dependencies
```

## Usage

1. **Local Development**: Run `flask run` and access the app on your local machine.
2. **Deployment**: Deploy the app to Azure (or another cloud platform) following the provider’s instructions for hosting Flask apps.
3. **Database Integration**: Modify the `app.py` file to integrate with a database of your choice (SQLite, PostgreSQL, etc.).

## Contribution

Feel free to open issues and submit pull requests for any improvements. Whether it's bug fixes, new features, or code optimizations, all contributions are welcome!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any inquiries or support related to the GulfHireX platform, please contact us at [support@gulfhirex.com](mailto:support@gulfhirex.com).

---


