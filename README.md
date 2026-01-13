# BATCH-29
BATCH 29 SSC
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SSC Batch 29 | Official Verified Portal</title>
    <meta name="description" content="Exclusive portal for SSC Batch 29 Blue Bird High School. Verification required for profile visibility.">

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        /* --- VARIABLES & RESET --- */
        :root {
            --primary-blue: #004aad;
            --primary-dark: #002b66;
            --accent-gold: #ffc107;
            --alert-red: #fee2e2;
            --alert-text: #b91c1c;
            --text-dark: #1f2937;
            --text-gray: #4b5563;
            --bg-light: #f3f4f6;
            --white: #ffffff;
            --shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: 'Inter', sans-serif;
            color: var(--text-dark);
            background-color: var(--bg-light);
            scroll-behavior: smooth;
        }

        h1, h2, h3 { font-family: 'Playfair Display', serif; }
        a { text-decoration: none; color: inherit; transition: 0.3s; }
        ul { list-style: none; }
        img { max-width: 100%; display: block; }

        /* --- ALERT BANNER --- */
        .alert-banner {
            background-color: var(--alert-red);
            color: var(--alert-text);
            text-align: center;
            padding: 12px 20px;
            font-weight: 700;
            border-bottom: 1px solid #fca5a5;
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        /* --- HEADER --- */
        header {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 15px rgba(0,0,0,0.05);
            border-top: 4px solid var(--primary-blue);
        }

        .navbar {
            max-width: 1200px;
            margin: 0 auto;
            padding: 15px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
            font-weight: 700;
            color: var(--primary-blue);
            font-size: 1.1rem;
        }
        
        .logo span { color: var(--accent-gold); }

        .nav-links { display: flex; gap: 25px; }
        .nav-links a { font-weight: 500; color: var(--text-dark); font-size: 0.95rem; }
        .nav-links a:hover { color: var(--primary-blue); }
        
        .mobile-toggle { display: none; font-size: 1.5rem; cursor: pointer; }

        /* --- HERO SECTION --- */
        .hero {
            background: linear-gradient(rgba(0, 51, 122, 0.9), rgba(0, 74, 173, 0.85)), 
                        url('https://images.unsplash.com/photo-1523050854058-8df90110c9f1?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            height: 80vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            padding: 0 20px;
        }

        .hero-content h1 { font-size: 3rem; margin-bottom: 15px; line-height: 1.2; }
        .hero-content h3 { font-family: 'Inter', sans-serif; font-weight: 400; font-size: 1.2rem; margin-bottom: 25px; opacity: 0.9; }
        
        .btn {
            padding: 12px 30px;
            border-radius: 50px;
            font-weight: 600;
            cursor: pointer;
            display: inline-block;
            transition: 0.3s;
            border: none;
            font-size: 0.95rem;
        }
        
        .btn-primary { background: var(--white); color: var(--primary-blue); }
        .btn-primary:hover { background: var(--accent-gold); color: var(--primary-dark); transform: translateY(-2px); }
        .btn-outline { border: 2px solid var(--white); color: var(--white); margin-left: 10px; }
        .btn-outline:hover { background: var(--white); color: var(--primary-blue); }
        .btn-submit { background: var(--primary-blue); color: white; width: 100%; border: none; }
        .btn-submit:hover { background: var(--primary-dark); }

        /* --- SECTIONS COMMON --- */
        .section { padding: 80px 20px; max-width: 1200px; margin: 0 auto; }
        .section-title { text-align: center; margin-bottom: 50px; }
        .section-title h2 { font-size: 2.2rem; color: var(--primary-blue); margin-bottom: 10px; }
        .section-title p { color: var(--text-gray); max-width: 700px; margin: 0 auto; }

        /* --- SUBMISSION FORM CARD --- */
        .submission-container {
            background: white;
            border-radius: 15px;
            box-shadow: var(--shadow);
            overflow: hidden;
            border: 1px solid #e5e7eb;
            margin-bottom: 60px;
        }

        .submission-header {
            background: var(--primary-dark);
            color: white;
            padding: 25px;
            text-align: center;
        }
        
        .submission-header h2 { color: white; margin-bottom: 5px; font-size: 1.5rem; }
        .submission-header p { opacity: 0.9; font-size: 0.9rem; }

        .submission-body {
            padding: 40px;
            max-width: 600px;
            margin: 0 auto;
        }

        .form-group { margin-bottom: 20px; }
        .form-group label { display: block; margin-bottom: 8px; font-weight: 600; font-size: 0.9rem; }
        .form-control {
            width: 100%;
            padding: 12px;
            border: 1px solid #d1d5db;
            border-radius: 6px;
            font-family: inherit;
            transition: 0.2s;
        }
        .form-control:focus { outline: none; border-color: var(--primary-blue); box-shadow: 0 0 0 3px rgba(0, 74, 173, 0.1); }

        .disclaimer-box {
            background: #fffbeb; /* Yellowish warning bg */
            border-left: 4px solid var(--accent-gold);
            padding: 15px;
            margin-bottom: 20px;
            font-size: 0.9rem;
            color: #92400e;
            line-height: 1.5;
        }

        .checkbox-group { display: flex; gap: 10px; align-items: flex-start; margin-bottom: 25px; }
        .checkbox-group input { margin-top: 4px; }

        /* --- DIRECTORY (GRID) --- */
        .directory-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); gap: 30px; }
        .student-card {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: var(--shadow);
            transition: 0.3s;
            position: relative;
            border-top: 4px solid var(--primary-blue);
        }
        .student-card:hover { transform: translateY(-5px); box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1); }
        .card-img { height: 260px; overflow: hidden; position: relative; }
        .card-img img { width: 100%; height: 100%; object-fit: cover; transition: 0.5s; }
        .student-card:hover .card-img img { transform: scale(1.05); }
        
        .verified-badge {
            position: absolute;
            bottom: 10px;
            right: 10px;
            background: white;
            color: #0095f6; /* Instagram Blue */
            width: 30px; height: 30px;
            border-radius: 50%;
            display: flex; align-items: center; justify-content: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
            font-size: 14px;
        }

        .card-info { padding: 20px; text-align: center; }
        .card-info h3 { font-size: 1.1rem; color: var(--primary-blue); margin-bottom: 5px; font-family: 'Inter', sans-serif; font-weight: 700; }
        .card-info p { font-size: 0.85rem; color: var(--text-gray); margin-bottom: 10px; }
        .ig-link { color: #0095f6; font-weight: 600; font-size: 0.85rem; cursor: pointer; }

        /* --- ADMIN SECTION --- */
        .admin-card {
            background: var(--primary-dark);
            color: white;
            border-radius: 15px;
            padding: 40px;
            display: flex;
            align-items: center;
            gap: 30px;
            box-shadow: var(--shadow);
            flex-wrap: wrap;
        }
        .admin-img { width: 100px; height: 100px; border-radius: 50%; border: 4px solid var(--white); object-fit: cover; flex-shrink: 0; }
        .admin-info h2 { color: var(--accent-gold); margin-bottom: 5px; font-family: 'Inter', sans-serif; }
        .admin-ig { display: inline-block; background: rgba(255,255,255,0.15); padding: 8px 15px; border-radius: 50px; margin: 5px 5px 5px 0; font-size: 0.9rem; transition: 0.3s; cursor: pointer; }
        .admin-ig:hover { background: #0095f6; transform: translateY(-2px); }
        
        .final-rule {
            margin-top: 20px;
            background: rgba(255,255,255,0.1);
            padding: 15px;
            border-radius: 8px;
            font-size: 0.9rem;
            border-left: 3px solid var(--accent-gold);
        }

        /* --- FOOTER --- */
        footer { background: #111827; color: #9ca3af; padding: 60px 20px 20px; text-align: center; }
        .footer-links { display: flex; justify-content: center; gap: 20px; margin-bottom: 30px; }
        .footer-links a:hover { color: white; }
        .strict-notice { font-size: 0.8rem; color: #4b5563; margin-top: 20px; border-top: 1px solid #374151; padding-top: 20px; }

        /* --- RESPONSIVE --- */
        @media (max-width: 768px) {
            .nav-links { display: none; }
            .mobile-toggle { display: block; }
            .hero-content h1 { font-size: 2.2rem; }
            .admin-card { text-align: center; justify-content: center; }
            .submission-body { padding: 20px; }
        }
    </style>
</head>
<body>

    <!-- STRICT NOTICE BANNER -->
    <div class="alert-banner">
        ⚠️ <strong>Final Approval Policy:</strong> Profiles will NOT be visible until Admin approves your verification.
    </div>

    <!-- NAVIGATION -->
    <header>
        <div class="navbar">
            <div class="logo">
                <i class="fas fa-dove"></i> SSC Batch <span>29</span>
            </div>
            <div class="mobile-toggle"><i class="fas fa-bars"></i></div>
            <nav class="nav-links">
                <a href="#home">Home</a>
                <a href="#submit">Submit Profile</a>
                <a href="#directory">Directory</a>
                <a href="#admin">Admin</a>
            </nav>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Welcome to the<br>SSC Batch 29 Portal</h1>
            <h3>Blue Bird High School & College, Sylhet, Bangladesh</h3>
            <a href="#submit" class="btn btn-primary">Submit Your Profile</a>
            <a href="#directory" class="btn btn-outline">View Approved Batchmates</a>
        </div>
    </section>

    <!-- SUBMISSION FORM SECTION -->
    <section id="submit" class="section">
        <div class="submission-container">
            <div class="submission-header">
                <h2>Account & Profile Submission</h2>
                <p>SSC Batch 29 • Blue Bird High School & College</p>
            </div>
            <div class="submission-body">
                
                <div class="disclaimer-box">
                    <strong>🔒 IMPORTANT NOTICE:</strong><br>
                    Your profile will enter <strong>ADMIN REVIEW ONLY</strong> status upon submission.
                    Your profile <strong>WILL NOT BE DISPLAYED</strong> on the website until the admin approves your Instagram verification.
                </div>

                <form id="profileForm">
                    <div class="form-group">
                        <label for="fullName">Full Name <span style="color:red">*</span></label>
                        <input type="text" id="fullName" class="form-control" placeholder="Enter your full name as per school records" required>
                    </div>

                    <div class="form-group">
                        <label for="instagramID">Instagram ID <span style="color:red">*</span> (Required for verification)</label>
                        <input type="text" id="instagramID" class="form-control" placeholder="e.g., @username" required>
                        <small style="color: var(--text-gray);">Your Instagram must be real, active, and your own profile.</small>
                    </div>

                    <div class="form-group">
                        <label for="currentCity">Current City / Profession (Optional)</label>
                        <input type="text" id="currentCity" class="form-control" placeholder="e.g., Sylhet (Software Engineer)">
                    </div>

                    <div class="form-group">
                        <label for="photo">Profile Photo (Simulation)</label>
                        <input type="file" id="photo" class="form-control" accept="image/*">
                        <small style="color: var(--text-gray);">Upload a clear profile photo.</small>
                    </div>

                    <div class="checkbox-group">
                        <input type="checkbox" id="terms" required>
                        <label for="terms" style="font-size: 0.9rem;">
                            I understand that my profile will remain <strong>HIDDEN</strong> and invisible to the public until Ankur Das verifies my identity and approves my entry.
                        </label>
                    </div>

                    <button type="submit" class="btn btn-submit">
                        <i class="fas fa-paper-plane"></i> Submit Profile for Review
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- DIRECTORY SECTION -->
    <section id="directory" class="section">
        <div class="section-title">
            <h2>Approved Directory</h2>
            <p>Profiles verified and approved by Admin Ankur Das.</p>
        </div>

        <div class="directory-grid">
            <!-- Student 1: Ankur Das -->
            <div class="student-card">
                <div class="card-img">
                    <img src="https://picsum.photos/seed/ankur/300/400" alt="Ankur Das">
                    <div class="verified-badge"><i class="fas fa-check"></i></div>
                </div>
                <div class="card-info">
                    <h3>Ankur Das</h3>
                    <p>Owner / Admin</p>
                    <span class="ig-link" onclick="window.open('https://instagram.com/mr.ankur.mindset')">@mr.ankur.mindset</span>
                </div>
            </div>

            <!-- Student 2 -->
            <div class="student-card">
                <div class="card-img">
                    <img src="https://picsum.photos/seed/sifat/300/400" alt="Sifat Ahmed">
                    <div class="verified-badge"><i class="fas fa-check"></i></div>
                </div>
                <div class="card-info">
                    <h3>Sifat Ahmed</h3>
                    <p>Verified Classmate</p>
                    <span class="ig-link">@sifat.bluebird</span>
                </div>
            </div>

            <!-- Student 3 -->
            <div class="student-card">
                <div class="card-img">
                    <img src="https://picsum.photos/seed/nayeem/300/400" alt="Nayeem Islam">
                    <div class="verified-badge"><i class="fas fa-check"></i></div>
                </div>
                <div class="card-info">
                    <h3>Nayeem Islam</h3>
                    <p>Verified Classmate</p>
                    <span class="ig-link">@nayeem_29</span>
                </div>
            </div>

             <!-- Student 4 -->
             <div class="student-card">
                <div class="card-img">
                    <img src="https://picsum.photos/seed/sumaiya/300/400" alt="Sumaiya Akter">
                    <div class="verified-badge"><i class="fas fa-check"></i></div>
                </div>
                <div class="card-info">
                    <h3>Sumaiya Akter</h3>
                    <p>Verified Classmate</p>
                    <span class="ig-link">@sumaiya_uk</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ADMIN / CONTACT SECTION -->
    <section id="admin" class="section">
        <div class="section-title">
            <h2>Admin & Verification Control</h2>
            <p>All submissions are reviewed by the owner.</p>
        </div>

        <div class="admin-card">
            <img src="https://picsum.photos/seed/ankur/200/200" alt="Ankur Das" class="admin-img">
            <div class="admin-info">
                <h3>Website Owner & Admin</h3>
                <h2>Ankur Das</h2>
                
                <div style="margin: 15px 0;">
                    <span class="admin-ig" onclick="window.open('https://instagram.com/mr.ankur.mindset')">
                        <i class="fab fa-instagram"></i> @mr.ankur.mindset
                    </span>
                    <span class="admin-ig" onclick="window.open('https://instagram.com/ankur.pza')">
                        <i class="fab fa-instagram"></i> @ankur.pza
                    </span>
                </div>

                <div class="final-rule">
                    <i class="fas fa-exclamation-triangle" style="color: var(--accent-gold);"></i> <strong>Final Rule (No Exceptions):</strong><br>
                    Profiles will NOT be published, visible, or accessible on the website unless they are verified and approved by admin. Approval is mandatory for EVERY profile.
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer>
        <div class="footer-links">
            <a href="#home">Home</a>
            <a href="#submit">Submit Profile</a>
            <a href="#directory">Directory</a>
            <a href="#admin">Admin</a>
        </div>
        <p>&copy; 2024 SSC Batch 29 | Blue Bird High School & College, Sylhet.</p>
        <div class="strict-notice">
            <i class="fas fa-shield-alt"></i> This is a private community. Verification by Ankur Das is mandatory.
        </div>
    </footer>

    <!-- JAVASCRIPT -->
    <script>
        // Handle Form Submission Simulation
        document.getElementById('profileForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Simulate the "Pending Review" state
            const name = document.getElementById('fullName').value;
            const instagram = document.getElementById('instagramID').value;

            // Show the alert with the policy enforcement
            alert(`\n✅ PROFILE SUBMITTED SUCCESSFULLY\n\nHello ${name},\n\nYour profile is now in ADMIN REVIEW ONLY status.\n\nYour entry is currently HIDDEN.\nIt will NOT be visible to anyone until Ankur Das verifies your Instagram (@${instagram}) and approves your profile.\n\nPlease wait for admin approval.`);
            
            // Reset form
            this.reset();
        });

        // Mobile Menu
        const toggleBtn = document.querySelector('.mobile-toggle');
        const navLinks = document.querySelector('.nav-links');

        toggleBtn.addEventListener('click', () => {
            if (navLinks.style.display === 'flex') {
                navLinks.style.display = 'none';
            } else {
                navLinks.style.display = 'flex';
                navLinks.style.flexDirection = 'column';
                navLinks.style.position = 'absolute';
                navLinks.style.top = '70px';
                navLinks.style.left = '0';
                navLinks.style.width = '100%';
                navLinks.style.background = 'white';
                navLinks.style.padding = '20px';
                navLinks.style.boxShadow = '0 5px 10px rgba(0,0,0,0.1)';
            }
        });
    </script>
</body>
</html>
