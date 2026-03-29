🚀 AI Study Planner & Study Hub                                                           
                                      
                                                                        
A powerful and intelligent web-based study management system built using Flask (Python), SQLite, and JavaScript.                                    
This project helps students efficiently manage their study schedule, track progress, and boost productivity using smart AI-based features.                        
                                                                                        
📖 Overview                                                                  
                                                                              
The AI Study Planner & Study Hub is designed to solve common student problems like:                                          
                                                                    
Lack of planning 📉                                              
Poor time management ⏱️                                            
No progress tracking ❌                                    
Inefficient study methods 📚                                                      
                                                                                  
This system provides a complete solution with:                                          
                                                                              
Task management                                                  
Progress tracking                                              
Pomodoro timer                                              
AI-generated study plans                                              
Advanced study tools (Study Hub)                                                    
✨ Key Features 
                                                                            
🔐 1. Authentication System                                                            
Secure User Signup & Login                                                          
Passwords stored using hashing (Werkzeug)                                            
Session-based authentication                                              
Logout functionality                                                        
                                                                          
✔ Ensures user data safety and privacy                                                      
                                                                                            
📊 2. Dashboard – AI Study Planner                                                            
                                                                                                
The main screen where users manage their study tasks.                                            
                                                                          
Features:                                                                  
➕ Add new study tasks                                                            
✅ Mark tasks as completed                                                            
🗑️ Delete tasks                                                
📈 Real-time progress tracking                                    
🎯 Priority selection (Low / Medium / High)                                                
💾 Data stored in browser (localStorage)                                                            
📉 Progress Tracking:                                                      
Total tasks count                                                                            
Completed tasks                                                                            
Progress bar (auto calculated)    
                                                                            
⏱️ 3. Pomodoro Timer System                                                    
                                                                              
Built-in focus timer for productivity.                                                                
                                                                                      
Default: 25 minutes (Pomodoro technique)                                                    
Start / Stop / Reset controls                                                          
Automatically marks task complete after timer                                                          
Tracks total focus time                                                                            
                                                                                      
✔ Helps improve concentration and discipline                                                            
                                                                          
🤖 4. AI Task Suggestions                                                      
                                                                            
Smart study suggestions like:                                                
                                                      
Practice problems                                                
Revision sessions                                                          
Flashcards                                                            
Break reminders                                                  
                                                                      
Also includes:                                                            
👉 Random smart task generator                                                      
                                                                                    
🧠 5. AI Study Plan Generator (Backend Logic)                                                              
                                                                          
From app.py:                                                                            
                                                                                    
Generates structured plan:                                                                    
📘 Basics                                                                              
🧠 Practice                                                                
🚀 Advanced                                                                    
📝 Revision                                                                    
                                                                                
✔ Automatically adds tasks to dashboard                                                        
                                                                                
🧩 6. Study Hub (Advanced Module)                                                      
                                                                                            
A powerful multi-tool section for students.                                                                      
                                                                                      
📚 Study Planner Tool                                                        
Add subjects with:                                                                
Study hours/day                                                                
Priority level                                                                        
Total days                                                                    
                                                                                          
✔ Generates optimized daily study plan                                                        
                                                                                  
🧠 AI Tutor (Simulated)                                                                        
Answers questions instantly                                                      
Covers:                                                                        
Academic subjects                                                                    
AI/ML concepts                                                              
Study tips                                                                  
                                                                                  
✔ Works using predefined intelligent responses                                                    
                                                                      
💡 Flashcards Generator                                                          
Input: Notes                                                              
Output: Q&A flashcards                                                      
                                                                        
Example:                                                              
                                                                          
Q: What is Photosynthesis?                                                          
A: Photosynthesis                                                              
                                                                            
✔ Useful for revision and memory                                                      
                                                                    
📝 Quiz Generator                                                                          
Enter topic → Generates quiz questions                                                          
Includes:                                                        
Multiple choice format                                                  
Answers                                                  
                                                                        
✔ Helps in self-testing                                                        
                                                                          
📊 Study Analytics                                                              
Shows:                                                                
Subjects list                                                            
Total study hours                                                              
                                                                      
✔ Gives overview of study plan                                                                  
                                                                                
🛠️ Tech Stack                                                        
Layer	Technology                                                    
Backend	Flask (Python)                                                        
Database	SQLite                                                                  
Frontend	HTML, CSS, JavaScript                                                          
Styling	Bootstrap + Custom UI                                                              
Security	Werkzeug Password Hashing                                                                    
📂 Project Structure                                                            
AI-Study-Planner/                                                                        
│                                                                                      
├── app.py                # Main Flask application                                                          
├── database.db           # SQLite database                                                              
│                                                                                  
├── templates/                                                                        
│   ├── dashboard.html   # Main dashboard UI                                                      
│   ├── login.html       # Login page                                                        
│   ├── signup.html      # Signup page                                                            
│   └── studyhub.html    # Study Hub tools                                                          
⚙️ Installation & Setup                                                              
                                                                                            
Follow these steps to run the project locally:                                                    
                                                                              
1️⃣ Clone Repository                                                                      
git clone https://github.com/your-username/ai-study-planner.git                                                  
cd ai-study-planner                                                                    
2️⃣ Install Dependencies                                                        
pip install flask werkzeug                                                          
3️⃣ Run Application                                                            
python app.py                                                                    
4️⃣ Open in Browser                                                            
http://127.0.0.1:5000                                                            
🔄 Application Flow                                                                
User signs up                                                    
Logs into system                                                              
Access dashboard                                                      
Adds & manages study tasks                                                            
Uses Pomodoro timer                                                                        
Gets AI suggestions                                                                
Opens Study Hub for advanced tools                                                            

