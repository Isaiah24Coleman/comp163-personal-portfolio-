# comp163-personal-portfolio-
full_name = "Isaiah Coleman"
student_email = "ilcoleman@ncat.aggies.edu"
hometown = "Charlotte, NC"
graduation_semester = "Spring 2028"
major = "Computer Science"

current_courses = ["COMP 163", "MATH 131", "ENG 101", "HIS 105"]
completed_courses = [ "Biology", "Chemistry", "Spanish II", "World History" ]
credit_hours = [ 3, 3, 3, 3 ]
gpa_history = [3.2, 3.6, 3.4, 3.7]

emergency_contact = ("Mom", "Jamie Coleman", "704-555-0199" )
home_address = ("1610 Oak Street", "Charlotte", "NC", "28202")
instagram_info = ("Instagram", "2cool4you", 312 )
twitter_info = ("Twitter", "@zaydagreat", 127 )
birthday = ("Birthday", 5, 22, 2006 )

current_skills = {"Python basics", "HTML", "Problem solving", "Time management", "Public speaking" }
skills_to_learn = {"JavaScript", "Data structures", "Git", "Web design",}
career_interests = {"Software development", "Web development", "Data science", "Game development, Cyber Security"}
hobbies = {"Gaming", "Photography", "Reading", "Football", "Music"}
entertainment_backlog = {"Bleach", "Barry", "Life", "Fast n Furious", "Memento", 2k }

course_credits = {"COMP 163": 3, "MATH 131": 3, "ENG 101": 3, "HIS 105": 3  }
course_professors = { "COMP 163": "Prof. Rhodes", "MATH 150": "Dr. Park", "ENG 101": "Dr. Martinez", "HIS 105": "Dr. Brown"}
course_rooms = {"COMP 163": "M-Eric 300", "MATH 131": "Marteena 201", "ENG 101": "Crosby 121", "HIS 105": "Crosby 210" }
monthly_budget = {"Food": 500, "Entertainment": 300, "Books": 100, "Transportation": 100 }
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
