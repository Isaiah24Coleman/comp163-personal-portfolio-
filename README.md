# comp163-personal-portfolio-
full_name = "Jordan Smith"
student_email = "jsmith@ncat.edu"
hometown = "Charlotte, NC"
graduation_semester = "Spring 2028"
major = "Computer Science"

current_courses = ["COMP 163", "MATH 150", "ENG 101", "HIS 105"]
completed_courses = [ "Biology", "Chemistry", "Calculus", "Spanish II", "World History" ]
credit_hours = [ 3, 3, 3, 3 ]
gpa_history = [3.2, 3.6, 3.4, 3.7]

emergency_contact = ("Mom", "Hannah Smith", "704-555-0199" )
home_address = ("456 Oak Street", "Charlotte", "NC", "28202")
instagram_info = ("Instagram", "@jordan_codes", 312 )
twitter_info = ("Twitter", "@jordandev", 127 )
birthday = ("Birthday", 5, 22, 2006 )

current_skills = {"Python basics", "HTML", "Problem solving", "Time management", "Photography" }
skills_to_learn = {"JavaScript", "Data structures", "Git", "Web design", "Public speaking" }
career_interests = {"Software development", "Web development", "Data science", "Game development"}
hobbies = {"Gaming", "Photography", "Reading", "Soccer", "Music"}
entertainment_backlog = {"One Piece", "Barry", "Life", "Incantation", "Memento" }

course_credits = {"COMP 163": 3, "MATH 150": 3, "ENG 101": 3, "HIS 105": 3  }
course_professors = { "COMP 163": "Prof. Rhodes", "MATH 150": "Dr. Lee", "ENG 101": "Dr. Martinez", "HIS 105": "Dr. Brown"}
course_rooms = {"COMP 163": "M-Eric 300", "MATH 150": "Marteena 201", "ENG 101": "Crosby 121", "HIS 105": "Crosby 210" }
monthly_budget = {"Food": 450, "Entertainment": 200, "Books": 125, "Transportation": 100 }
study_hours = {"Programming": 10, "Math": 8, "English": 4, "History": 3 }
contact_directory ={ "Mom": "704-555-0199", "Roommate": "336-5557821", "Academic Advisor": "336-334-5000" }

total_current_credits = sum(credit_hours)
cumulative_gpa =round( sum(gpa_history)/len (gpa_history), 2)
count_completed_courses = len(completed_courses)
total_weekly_study_hours = sum(study_hours.values())
academic_load = total_current_credits + total_weekly_study_hours
monthy_budget_total = sum(monthly_budget.values())
daily_food_budget = round(monthly_budget["Food"]/ 30,2)
annual_budget = monthy_budget_total * 12
study_cost_per_hour = round(monthly_budget["Books"]/total_weekly_study_hours, 2)

total_social_media_followers = instagram_info[2]+twitter_info[2]
skill_comparison_count = (len(current_skills),len(skills_to_learn))
contact_directory_size_analysis = len(contact_directory)
entertainment_backlog_management_count = len(entertainment_backlog)
academic_workload_assessment = "credits" + "total_weekly_study_hours"
hobbies_count = len(hobbies)
