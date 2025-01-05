# 🎥 Movie Recommendation System  

Welcome to the **Movie Recommendation System** repository! This project demonstrates a machine learning-based recommendation system that suggests movies based on Content Based Recommender.  

## 🚀 Features  

- Recommends top 5 similar movies for any selected movie.  
- Fetches movie posters using The Movie Database (TMDb) API for an enhanced user experience.  
- Interactive web interface built using **Streamlit** for easy access and usability.  

## 📋 Table of Contents  

- [Demo](#demo)  
- [Technologies Used](#technologies-used)  
- [Setup Instructions](#setup-instructions)  
- [How It Works](#how-it-works)  
- [Future Improvements](#future-improvements)  

## 🌟 Demo  

Check out the live application here: [Demo Link](#). *(Replace with your Streamlit app URL once deployed)*  

## 💻 Technologies Used  

- **Python** for backend logic.  
- **Pandas** and **NumPy** for data processing.  
- **Pickle** for saving precomputed similarity matrices.  
- **Streamlit** for the interactive web application.  
- **TMDb API** for fetching movie posters and additional movie information.  

## 🛠️ Setup Instructions  

Follow these steps to get the app running on your local machine:  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/narenkdk/ml-projects.git  
   ```  

2. Navigate to the project directory:  
   ```bash  
   cd ml-projects 
   ```  

3. Install the required dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. Download the necessary data files:  
   - Add your `movies_dict.pkl` and `similarity.pkl` files to the project directory.  

5. Add your TMDb API key:  
   - Create a `.env` file in the project directory and add the following:  
     ```env  
     TMDB_API_KEY=your_api_key_here  
     ```  

6. Run the Streamlit app:  
   ```bash  
   streamlit run app.py  
   ```  

7. Open the app in your browser at `http://localhost:8501`.  

## 🧠 How It Works  

1. **Data Preprocessing**:  
   - The dataset is preprocessed to compute a similarity matrix using cosine similarity.  

2. **Recommendation Logic**:  
   - The app uses the similarity matrix to recommend movies based on the selected movie.  

3. **Poster Fetching**:  
   - TMDb API fetches movie posters for a visually appealing experience.  

4. **Streamlit UI**:  
   - An intuitive web interface is provided for users to select a movie and view recommendations.  

## 🌱 Future Improvements  

- Add user-based and collaborative filtering models for better recommendations.  
- Support multiple genres and advanced filtering options.  
- Optimize performance for large datasets.  
- Integrate user authentication for personalized recommendations.  

## 🤝 Contributing  

Contributions are welcome! Feel free to submit issues or pull requests.  

## 📄 License  

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.  

## 📧 Contact  

For any inquiries, feel free to reach out:  
- **Name**: [Your Name]  
- **Email**: your_email@example.com  
- **GitHub**: [Your GitHub Profile](https://github.com/your-username)  
