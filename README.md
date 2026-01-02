<!DOCTYPE html>  <html lang="bn">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>শোনার যন্ত্র সমাধান</title>  
    <style>  
        body { font-family: 'Noto Sans Bengali', Arial, sans-serif; margin: 0; padding: 0; line-height: 1.6; color: #333; }  
        header { background: #007bff; color: white; padding: 1rem; text-align: center; }  
        nav { background: #f8f9fa; padding: 0.5rem; text-align: center; }  
        nav a { margin: 0 1rem; text-decoration: none; color: #007bff; }  
        section { padding: 2rem; max-width: 1200px; margin: auto; }  
        .hero { background: url('https://via.placeholder.com/1200x400?text=শোনার+যন্ত্র+হিরো+ইমেজ') no-repeat center/cover; height: 400px; display: flex; align-items: center; justify-content: center; color: white; text-shadow: 2px 2px 4px rgba(0,0,0,0.5); }  
        .products { display: flex; flex-wrap: wrap; justify-content: space-around; }  
        .product { border: 1px solid #ddd; padding: 1rem; margin: 1rem; width: 300px; text-align: center; }  
        footer { background: #343a40; color: white; text-align: center; padding: 1rem; }  
        @media (max-width: 768px) { .products { flex-direction: column; } }  
    </style>  
</head>  
<body>  
    <header>  
        <h1>শোনার যন্ত্র সমাধান</h1>  
        <p>উন্নত শোনার মাধ্যমে জীবনকে আরও ভালো করুন</p>  
    </header>  
    <nav>  
        <a href="#home">হোম</a>  
        <a href="#about">আমাদের সম্পর্কে</a>  
        <a href="#products">পণ্য</a>  
        <a href="#services">সেবা</a>  
        <a href="#contact">যোগাযোগ</a>  
    </nav>  <section id="home" class="hero">  
    <div>  
        <h2>শোনার যন্ত্র সমাধানে স্বাগতম</h2>  
        <p>আপনার জীবনের মান উন্নত করতে সর্বশেষ শোনার প্রযুক্তি আবিষ্কার করুন।</p>  
        <button onclick="alert('আজই যোগাযোগ করুন!')">শুরু করুন</button>  
    </div>  
</section>  
  
<section id="about">  
    <h2>আমাদের সম্পর্কে</h2>  
    <p>আমরা আপনার প্রয়োজন অনুসারে উচ্চ-মানের শোনার যন্ত্র প্রদানে বিশেষজ্ঞ। আমাদের অডিওলজিস্টদের দল ব্যক্তিগত যত্ন এবং সেরা প্রযুক্তি নিশ্চিত করে।</p>  
</section>  
  
<section id="products">  
    <h2>আমাদের পণ্য</h2>  
    <div class="products">  
        <div class="product">  
            <h3>কানের পিছনে শোনার যন্ত্র</h3>  
            <p>অদৃশ্য এবং শক্তিশালী, সব ধরনের শোনার সমস্যার জন্য উপযুক্ত।</p>  
            <p>মূল্য: ১,২০০ টাকা</p>  
        </div>  
        <div class="product">  
            <h3>কানের ভিতরে শোনার যন্ত্র</h3>  
            <p>আরাম এবং স্পষ্টতার জন্য কাস্টম-ফিট।</p>  
            <p>মূল্য: ৮০০ টাকা</p>  
        </div>  
        <div class="product">  
            <h3>রিচার্জেবল শোনার যন্ত্র</h3>  
            <p>যাওয়ার পথে জীবনের জন্য সুবিধাজনক ওয়্যারলেস চার্জিং।</p>  
            <p>মূল্য: ১,৫০০ টাকা</p>  
        </div>  
    </div>  
</section>  
  
<section id="services">  
    <h2>আমাদের সেবা</h2>  
    <ul>  
        <li>শোনার মূল্যায়ন এবং পরামর্শ</li>  
        <li>কাস্টম ফিটিং এবং সমন্বয়</li>  
        <li>রক্ষণাবেক্ষণ এবং মেরামত</li>  
        <li>প্রশিক্ষণ এবং সহায়তা</li>  
    </ul>  
</section>  
  
<section id="contact">  
    <h2>যোগাযোগ করুন</h2>  
    <p>ইমেইল: info@hearingaidsolutions.com</p>  
    <p>ফোন: (১২৩) ৪৫৬-৭৮৯০</p>  
    <p>ঠিকানা: ১২৩ শোনার স্ট্রিট, অডিওটাউন, বাংলাদেশ</p>  
    <form>  
        <label for="name">নাম:</label><br>  
        <input type="text" id="name" name="name"><br>  
        <label for="email">ইমেইল:</label><br>  
        <input type="email" id="email" name="email"><br>  
        <label for="message">বার্তা:</label><br>  
        <textarea id="message" name="message"></textarea><br>  
        <button type="submit">পাঠান</button>  
    </form>  
</section>  
  
<footer>  
    <p>&copy; ২০২৩ শোনার যন্ত্র সমাধান। সর্বস্বত্ব সংরক্ষিত।</p>  
</footer>  
  
<script>  
    // সাধারণ ফর্ম ভ্যালিডেশন  
    document.querySelector('form').addEventListener('submit', function(e) {  
        e.preventDefault();  
        alert('আপনার বার্তার জন্য ধন্যবাদ!');  
    });  
</script>

</body>  
</html>  
