# CineNow APP

CineNow is a modern and intuitive Android app designed for movie lovers who want quick and reliable access to popular films. Powered by The Movie Database (TMDB) API, CineNow delivers up-to-date movie information with a clean and engaging user experience.

## ✨ Key Features

### 🎬 Popular Movies   
Browse a constantly updated list of trending and popular films, refreshed daily using real-time TMDB data.   

### 📄 Detailed Movie Information   
Access complete details for each movie, including title, synopsis, release date, rating, genres, and official poster.   

### 🖥️ Smooth & Intuitive Interface   
Enjoy a clean, user-friendly layout that makes navigation effortless and visually appealing.    

## 🔑 API Setup (TMDB)   

This project requires a TMDB API Read Access Token.   
For security reasons, the token is not included in the repository.   

### To run the app:   
	1.	Create a free account at https://www.themoviedb.org/   
	2.	Go to Settings → API and copy your API Read Access Token    
	3.	In the project root, create a file named: local.properties   
  
	4.	Add your token: API_KEY="YOUR_TMDB_TOKEN_HERE"   

	5.	Sync the project in Android Studio.   
That’s it! The app will now run using your local API key.   

### :camera_flash: Screenshots
<!-- You can add more screenshots here if you like -->
<img src="https://github.com/ComunidadeDevSpace/CineNow/assets/11612508/9690f66d-fb65-4cd7-82db-954473cb6c2d" width=260/> <img src="https://github.com/ComunidadeDevSpace/CineNow/assets/11612508/f8006a40-8855-4d6f-b9b9-a44a8c991fe1" width=260/>


## Tecnologias
- 100% Kotlin
- Compose
  - Column
  - Row
  - Modifier
  - Spacer
  - LazyRows
  - ComposePreview
  - NavHostController
  - AsyncImage
- Retrofit
- Okhttp3
- TMDB API

## License
```
The MIT License (MIT)

Copyright (c) 2025 Francisco Cleonis Costa de Souza

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
