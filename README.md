<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>All Mode Yasin - অ্যাপস ও সফটওয়্যার</title>
    <style>
        body {
            font-family: 'SolaimanLipi', Arial, sans-serif;
            margin: 0; padding: 0;
            background: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 1rem 2rem;
            text-align: center;
            font-size: 1.8rem;
            font-weight: bold;
        }
        nav {
            background: #004085;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 1rem 1.5rem;
            display: block;
            transition: background 0.3s;
        }
        nav a:hover, nav a.active {
            background: #0056b3;
        }
        main {
            max-width: 1000px;
            margin: 2rem auto;
            background: white;
            padding: 2rem;
            border-radius: 8px;
        }
        h2 {
            border-bottom: 2px solid #007bff;
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
            color: #004085;
        }
        ul.app-list {
            list-style: none;
            padding: 0;
        }
        ul.app-list li {
            margin-bottom: 1rem;
            padding-bottom: 0.6rem;
            border-bottom: 1px solid #ddd;
        }
        .app-name {
            font-weight: 600;
            font-size: 1.1rem;
            color: #007bff;
            cursor: pointer;
            display: inline-block;
        }
        .app-details {
            margin-top: 0.5rem;
            padding-left: 1.5rem;
            display: none;
            color: #555;
        }
        button.buy-btn {
            background-color: #28a745;
            border: none;
            padding: 0.4rem 1rem;
            border-radius: 4px;
            color: white;
            cursor: pointer;
            margin-top: 0.5rem;
            font-weight: bold;
        }
        button.buy-btn:hover {
            background-color: #218838;
        }
        .payment-info {
            background: #e9ecef;
            padding: 1rem;
            margin-top: 1rem;
            border-radius: 6px;
        }
        form.request-form {
            margin-top: 2rem;
        }
        form.request-form label {
            display: block;
            margin-bottom: 0.3rem;
            font-weight: 600;
        }
        form.request-form input, form.request-form textarea {
            width: 100%;
            padding: 0.6rem;
            margin-bottom: 1rem;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 1rem;
            font-family: inherit;
        }
        form.request-form button {
            background-color: #007bff;
            border: none;
            padding: 0.6rem 1.5rem;
            color: white;
            font-weight: 600;
            border-radius: 4px;
            cursor: pointer;
            font-size: 1rem;
        }
        form.request-form button:hover {
            background-color: #0056b3;
        }
        footer {
            text-align: center;
            padding: 1rem;
            margin-top: 3rem;
            color: #777;
            font-size: 0.9rem;
            border-top: 1px solid #ddd;
        }
        @media (max-width: 600px) {
            nav {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

<header>
    All Mode Yasin - অ্যাপস ও সফটওয়্যার
</header>

<nav>
    <a href="#" class="nav-link active" data-section="free-phone">ফ্রি ফোন অ্যাপস</a>
    <a href="#" class="nav-link" data-section="free-pc">ফ্রি পিসি সফটওয়্যার</a>
    <a href="#" class="nav-link" data-section="premium-phone">প্রিমিয়াম ফোন অ্যাপস</a>
    <a href="#" class="nav-link" data-section="premium-pc">প্রিমিয়াম পিসি সফটওয়্যার</a>
    <a href="#" class="nav-link" data-section="request-app">অ্যাপস অনুরোধ করুন</a>
</nav>

<main>
    <!-- Free Phone Apps -->
    <section id="free-phone" class="content-section">
        <h2>ফ্রি ফোন অ্যাপস</h2>
        <ul class="app-list">
            <li>
                <span class="app-name">Google Drive</span>
                <div class="app-details">
                    গুগল ড্রাইভ ফাইল সংরক্ষণ এবং শেয়ার করার জন্য।
                    <br />
                    <a href="https://play.google.com/store/apps/details?id=com.google.android.apps.docs" target="_blank" rel="noopener noreferrer">ডাউনলোড করুন</a>
                </div>
            </li>
            <li>
                <span class="app-name">Microsoft Office</span>
                <div class="app-details">
                    অফিস ডকুমেন্ট তৈরির জন্য জনপ্রিয় অ্যাপ।
                    <br />
                    <a href="https://play.google.com/store/apps/details?id=com.microsoft.office.officehubrow" target="_blank" rel="noopener noreferrer">ডাউনলোড করুন</a>
                </div>
            </li>
            <li>
                <span class="app-name">Snapseed</span>
                <div class="app-details">
                    ফটো এডিটিংয়ের জন্য গুগলের জনপ্রিয় অ্যাপ।
                    <br />
                    <a href="https://play.google.com/store/apps/details?id=com.niksoftware.snapseed" target="_blank" rel="noopener noreferrer">ডাউনলোড করুন</a>
                </div>
            </li>
            <li>
                <span class="app-name">WhatsApp</span>
                <div class="app-details">
                    মোবাইল মেসেজিং ও কলিং অ্যাপ।
                    <br />
                    <a href="https://play.google.com/store/apps/details?id=com.whatsapp" target="_blank" rel="noopener noreferrer">ডাউনলোড করুন</a>
                </div>
            </li>
            <!-- আরো ফ্রি ফোন অ্যাপ এখানে যোগ করতে পারবে -->
        </ul>
    </section>

    <!-- Free PC Software -->
    <section id="free-pc" class="content-section" style="display:none;">
        <h2>ফ্রি পিসি সফটওয়্যার</h2>
        <ul class="app-list">
            <li>
                <span class="app-name">Microsoft Visual Studio Code</span>
                <div class="app-details">
                    কোড এডিটর ও ডেভেলপমেন্ট টুল।
                    <br />
                    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener noreferrer">ডাউনলোড করুন</a>
                </div>
            </li>
            <li>
                <span class="app-name">7-Zip</span>
                <div class="app-details">
                    ফাইল কম্প্রেশন এবং আর্কাইভিং সফটওয়্যার।
                    <br />
                    <a href="https://www.7-zip.org/" target="_blank" rel="noopener noreferrer">ডাউনলোড করুন</a>
                </div>
            </li>
            <li>
                <span class="app-name">GIMP</span>
                <div class="app-details">
                    ফ্রি ছবি এডিটিং সফটওয়্যার।
                    <br />
                    <a href="https://www.gimp.org/" target="_blank" rel="noopener noreferrer">ডাউনলোড করুন</a>
                </div>
            </li>
            <li>
                <span class="app-name">VLC Media Player</span>
                <div class="app-details">
                    মিডিয়া প্লেয়ার সব ধরনের ফাইল প্লে করার জন্য।
                    <br />
                    <a href="https://www.videolan.org/vlc/" target="_blank" rel="noopener noreferrer">ডাউনলোড করুন</a>
                </div>
            </li>
            <!-- আরো ফ্রি পিসি সফটওয়্যার এখানে যোগ করতে পারবে -->
        </ul>
    </section>

    <!-- Premium Phone Apps -->
    <section id="premium-phone" class="content-section" style="display:none;">
        <h2>প্রিমিয়াম ফোন অ্যাপস</h2>
        <ul class="app-list">
            <li>
                <span class="app-name">Adobe Premiere Pro Mobile</span>
                <div class="app-details">
                    প্রিমিয়াম ভিডিও এডিটিং অ্যাপ।  
                    <br />মূল্য: ৭০০ টাকা  
                    <br />
                    <button class="buy-btn" data-app="Adobe Premiere Pro Mobile">কিনুন</button>
                </div>
            </li>
            <li>
                <span class="app-name">Kinemaster Pro</span>
                <div class="app-details">
                    পেশাদার ভিডিও এডিটিং অ্যাপ।  
                    <br />মূল্য: ৬০০ টাকা  
                    <br />
                    <button class="buy-btn" data-app="Kinemaster Pro">কিনুন</button>
                </div>
            </li>
            <li>
                <span class="app-name">PicsArt Premium</span>
                <div class="app-details">
                    ফটো এডিটিং এর জন্য প্রিমিয়াম অ্যাপ।  
                    <br />মূল্য: ৫০০ টাকা  
                    <br />
                    <button class="buy-btn" data-app="PicsArt Premium">কিনুন</button>
                </div>
            </li>
            <!-- আরো প্রিমিয়াম ফোন অ্যাপ এখানে যোগ করতে পারবে -->
        </ul>
    </section>

    <!-- Premium PC Software -->
    <section id="premium-pc" class="content-section" style="display:none;">
        <h2>প্রিমিয়াম পিসি সফটওয়্যার</h2>
        <ul class="app-list">
            <li>
                <span class="app-name">Adobe Photoshop CC</span>
                <div class="app-details">
                    জনপ্রিয় প্রিমিয়াম ছবি এডিটিং সফটওয়্যার।  
                    <br />মূল্য: ১০০০ টাকা  
                    <br />
                    <button class="buy-btn" data-app="Adobe Photoshop CC">কিনুন</button>
                </div>
            </li>
            <li>
                <span class="app-name">Microsoft Office 365</span>
                <div class="app-details">
                    অফিস কাজের জন্য প্রিমিয়াম সফটওয়্যার।  
                    <br />মূল্য: ৯০০ টাকা  
                    <br />
                    <button class="buy-btn" data-app="Microsoft Office 365">কিনুন</button>
                </div>
            </li>
            <li>
                <span class="app-name">Adobe Premiere Pro</span>
                <div class="app-details">
                    প্রিমিয়াম ভিডিও এডিটিং সফটওয়্যার।  
                    <br />মূল্য: ১২০০ টাকা  
                    <br />
                    <button class="buy-btn" data-app="Adobe Premiere Pro">কিনুন</button>
                </div>
            </li>
            <!-- আরো প্রিমিয়াম পিসি সফটওয়্যার এখানে যোগ করতে পারবে -->
        </ul>
    </section>

    <!-- Request App Form -->
    <section id="request-app" class="content-section" style="display:none;">
        <h2>যে অ্যাপস নেই, জিজ্ঞাসা করুন</h2>
        <p>আপনি যে অ্যাপস গুলো পেতে চান তা নিচের ফর্মে লিখে পাঠান। আমরা যত দ্রুত সম্ভব সেটি আপডেট করব।</p>
        <form class="request-form" id="appRequestForm">
            <label for="name">নাম:</label>
            <input type="text" id="name" name="name" placeholder="আপনার নাম লিখুন" required />
            
            <label for="email">ইমেইল:</label>
            <input type="email" id="email" name="email" placeholder="আপনার ইমেইল লিখুন" required />
            
            <label for="appname">অ্যাপের নাম বা সফটওয়্যার নাম:</label>
            <textarea id="appname" name="appname" rows="4" placeholder="অ্যাপ/সফটওয়্যার এর নাম লিখুন" required></textarea>
            
            <button type="submit">জমা দিন</button>
        </form>
        <p id="formMessage" style="color: green; display: none;">আপনার অনুরোধ গ্রহণ করা হয়েছে। ধন্যবাদ!</p>
    </section>
</main>

<footer>
    &copy; ২০২৫ All Mode Yasin - সকল অধিকার সংরক্ষিত।
</footer>

<script>
    // নেভিগেশন লিংকগুলো ক্লিক হলে সেকশন দেখানো
    const navLinks = document.querySelectorAll('nav .nav-link');
    const sections = document.querySelectorAll('.content-section');

    navLinks.forEach(link => {
        link.addEventListener('click', e => {
            e.preventDefault();
            navLinks.forEach(l => l.classList.remove('active'));
            link.classList.add('active');

            const target = link.getAttribute('data-section');
            sections.forEach(section => {
                if(section.id === target) {
                    section.style.display = 'block';
                } else {
                    section.style.display = 'none';
                }
            });
        });
    });

    // অ্যাপ নাম ক্লিক করলে বিস্তারিত দেখানো/লুকানো
    const appNames = document.querySelectorAll('.app-name');
    appNames.forEach(name => {
        name.addEventListener('click', () => {
            const details = name.nextElementSibling;
            if(details.style.display === 'block') {
                details.style.display = 'none';
            } else {
                details.style.display = 'block';
            }
        });
    });

    // কিনুন বাটনে ক্লিক করলে পেমেন্ট তথ্য দেখানো
    const buyButtons = document.querySelectorAll('.buy-btn');
    buyButtons.forEach(btn => {
        btn.addEventListener('click', () => {
            const app = btn.getAttribute('data-app');
            alert(`অ্যাপের নাম: ${app}\n\nমূল্য: বিস্তারিত পেমেন্ট পেজে দেখানো হবে।\nবিকাশ/নগদ নাম্বার: 01751576073\n\nপেমেন্ট করার পর আমাদের ফেসবুক আইডিতে যোগাযোগ করুন।`);
        });
    });

    // ফর্ম সাবমিট হ্যান্ডলিং (এখানে শুধু ডেমো, ডেটা কোথাও পাঠানো হয় না)
    const form = document.getElementById('appRequestForm');
    const formMessage = document.getElementById('formMessage');
    form.addEventListener('submit', e => {
        e.preventDefault();
        // এখানে AJAX দিয়ে সার্ভারে পাঠাতে পারো যদি সার্ভার থাকে
        form.reset();
        formMessage.style.display = 'block';
    });
</script>

</body>
</html>
