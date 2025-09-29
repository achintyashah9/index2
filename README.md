## 🏗 Architecture

- *Backend*: Python FastAPI with SQLAlchemy ORM
- *Frontend*: Flutter mobile app with Dart
- *Database*: PostgreSQL with Alembic migrations
- *AI*: OpenAI API integration
- *Deployment*: Docker containers with GitHub Actions

## 🚀 Quick Start

### Backend Setup

bash
# Clone repository
git clone https://github.com/yourusername/fitfusion-pro.git
cd fitfusion-pro

# Setup Python environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Setup environment variables
cp .env.example .env
# Edit .env with your configuration

# Run database migrations
alembic upgrade head

# Start backend server
uvicorn app.main:app --reload


### Flutter Setup

bash
# Navigate to Flutter app
cd mobile_app

# Install Flutter dependencies
flutter pub get

# Run the app
flutter run


## 📁 Project Structure

