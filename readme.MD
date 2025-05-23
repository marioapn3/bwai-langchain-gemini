# BWAI LangChain Project

## English

### Prerequisites
- Python 3.8 or higher
- Docker and Docker Compose (for Redis)
- Google Cloud API Key for Gemini

### Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/marioapn3/bwai-langchain-gemini
cd bwai-langchain
```

2. **Create and activate virtual environment**
```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Set up environment variables**
Create a `.env` file in the root directory with:
```
GOOGLE_API_KEY=your_api_key_here
```

5. **Start Redis using Docker**
```bash
docker-compose up -d
```

6. **Run Jupyter Notebook**
```bash
jupyter notebook --ip=0.0.0.0 --port=8888
```

7. **Access the notebook**
Open your browser and navigate to `http://localhost:8888`

### Project Structure
- `index.ipynb`: Main notebook containing the LangChain implementation
- `data/`: Directory for storing data files
- `requirements.txt`: Python dependencies
- `docker-compose.yaml`: Redis configuration

### Additional Resources
- [Gemini API Documentation](https://ai.google.dev/gemini-api/docs/models?hl=id)

---

## Bahasa Indonesia

### Prasyarat
- Python 3.8 atau lebih tinggi
- Docker dan Docker Compose (untuk Redis)
- API Key Google Cloud untuk Gemini

### Petunjuk Instalasi

1. **Clone repository**
```bash
git clone <repository-url>
cd bwai-langchain
```

2. **Buat dan aktifkan virtual environment**
```bash
python -m venv env
source env/bin/activate  # Di Windows: env\Scripts\activate
```

3. **Instal dependensi**
```bash
pip install -r requirements.txt
```

4. **Siapkan variabel lingkungan**
Buat file `.env` di direktori utama dengan isi:
```
GOOGLE_API_KEY=your_api_key_here
```

5. **Mulai Redis menggunakan Docker**
```bash
docker-compose up -d
```

6. **Jalankan Jupyter Notebook**
```bash
jupyter notebook --ip=0.0.0.0 --port=8888
```

7. **Akses notebook**
Buka browser dan arahkan ke `http://localhost:8888`

### Struktur Proyek
- `index.ipynb`: Notebook utama yang berisi implementasi LangChain
- `data/`: Direktori untuk menyimpan file data
- `requirements.txt`: Dependensi Python
- `docker-compose.yaml`: Konfigurasi Redis

### Sumber Daya Tambahan
- [Dokumentasi Gemini API](https://ai.google.dev/gemini-api/docs/models?hl=id)