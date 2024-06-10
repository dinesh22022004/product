<?php

$con=mysqli_connect('localhost','root','','task3');
session_start();

if(mysqli_connect_error()){
    echo "<script>alert('can not connect to data base');</script>";
    exit();
}

if(isset($_POST['submit']))
{
  $query="INSERT INTO ee_shop(district,taluka) VALUES ('$_POST[district]','$_POST[taluka]')";
 
  if(mysqli_query($con,$query))
  {
           $_SESSION['taluka']=$_POST['taluka'];
           echo "<script>
           window.location.href='main.php';
           </script>";
                
                }
                else
                {

                    echo"
                    <script>
                    alert('Server Down !');
                window.location.href='index.php';
                </script>
                "; 
                }
}


?>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Select District and Taluka</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f4f4f4;
  }
  .container {
    text-align: center;
    width: 90%;
    max-width: 400px;
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
  }
  h1 {
    color: #333;
    margin-bottom: 20px;
  }
  label {
    font-weight: bold;
    display: block;
    margin-bottom: 5px;
  }
  select {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    font-size: 16px;
    border: 1px solid #ccc;
    border-radius: 4px;
  }
  button {
    width: 100%;
    padding: 15px;
    font-size: 18px;
    color: white;
    background-color: #28a745;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    margin-top: 20px;
  }
  button:hover {
    background-color: #218838;
  }
  .hidden {
    display: none;
  }
</style>
</head>
<body>
<form action="#" method="POST">
<div class="container">
  <h1>Select District and Taluka</h1>
  <div>
    <label for="district">District:</label>
    <select id="district" name="district">
      <option value="">Select District</option>
      <!-- Add all Maharashtra districts here -->
      <option value="Ahmednagar">Ahmednagar</option>
      <option value="Akola">Akola</option>
      <option value="Amravati">Amravati</option>
      <option value="Aurangabad">Aurangabad</option>
      <option value="Beed">Beed</option>
      <option value="Bhandara">Bhandara</option>
      <option value="Buldhana">Buldhana</option>
      <option value="Chandrapur">Chandrapur</option>
      <option value="Dhule">Dhule</option>
      <option value="Gadchiroli">Gadchiroli</option>
      <option value="Gondia">Gondia</option>
      <option value="Hingoli">Hingoli</option>
      <option value="Jalgaon">Jalgaon</option>
      <option value="Jalna">Jalna</option>
      <option value="Kolhapur">Kolhapur</option>
      <option value="Latur">Latur</option>
      <option value="Mumbai City">Mumbai City</option>
      <option value="Mumbai Suburban">Mumbai Suburban</option>
      <option value="Nagpur">Nagpur</option>
      <option value="Nanded">Nanded</option>
      <option value="Nandurbar">Nandurbar</option>
      <option value="Nashik">Nashik</option>
      <option value="Osmanabad">Osmanabad</option>
      <option value="Palghar">Palghar</option>
      <option value="Parbhani">Parbhani</option>
      <option value="Pune">Pune</option>
      <option value="Raigad">Raigad</option>
      <option value="Ratnagiri">Ratnagiri</option>
      <option value="Sangli">Sangli</option>
      <option value="Satara">Satara</option>
      <option value="Sindhudurg">Sindhudurg</option>
      <option value="Solapur">Solapur</option>
      <option value="Thane">Thane</option>
      <option value="Wardha">Wardha</option>
      <option value="Washim">Washim</option>
      <option value="Yavatmal">Yavatmal</option>
    </select>
  </div>
  <div id="talukaContainer" class="hidden">
    <label for="taluka">Taluka:</label>
    <select id="taluka" name="taluka">
      <option value="">Select Taluka</option>
    </select>
  </div>
  <button id="submitBtn" class="hidden" name="submit">Submit</button>
</div>

<script>
  const districtSelect = document.getElementById('district');
  const talukaContainer = document.getElementById('talukaContainer');
  const talukaSelect = document.getElementById('taluka');
  const submitBtn = document.getElementById('submitBtn');
  const mainHtmlPath = 'main.php'; // Path to the main.html file

  // Define taluka options for each district
  const talukaOptions = {
    Ahmednagar: ["Akole", "Jamkhed", "Karjat", "Kopergaon", "Newasa", "Nagar", "Parner", "Pathardi", "Rahata", "Rahuri", "Sangamner", "Shrirampur", "Shevgaon", "Shrigonda"],
    Akola: ["Akola", "Balapur", "Patur", "Barshitakali", "Murtizapur", "Akot", "Telhara"],
    Amravati: ["Amravati", "Achalpur", "Warud", "Chandurbazar", "Chandur Railway", "Chikhaldara"],
    Aurangabad: ["Aurangabad", "Kannad", "Soygaon", "Sillod", "Phulambri", "Khuldabad", "Vaijapur", "Gangapur", "Paithan"],
    Beed: ["Beed", "Georai", "Patoda", "Ashti", "Shirur (Kasar)", "Ambajogai", "Kaij", "Majalgaon", "Dharur", "Parli (Vaijnath)","Wadwani"],
    Bhandara: ["Bhandara", "Tumsar", "Pauni", "Mohadi", "Sakoli", "Lakhani", "Lakhandur"],
    Buldhana: ["Buldhana", "Chikhli", "Deulgaon Raja", "Malkapur", "Motala", "Nandura", "Mehkar", "Sindkhed Raja", "Lonar", "Khamgaon", "Shegaon", "Jalgaon Jamod", "Sangrampur"],
    Chandrapur: ["Chandrapur", "Bhadravati","Warora", "Chimur", "Nagbhid", "Bramhapuri", "Sindewahi"],
    Dhule: ["Dhule", "Sakri", "shindkheda", "Shirpur"],
    Gadchiroli: ["Armori", "Chamorshi", "Mulchera", "Aheri", "Gadchiroli", "Sironcha", "Etapalli", "Bhamragad", "Desaiganj", "Dhanora", "Kurkheda", "Korchi"],
    Gondia: ["Gondia", "Tiroda", "Goregaon", "Deori", "Amgaon", "Salekasa", "Arjuni Morgaon", "Sadak Arjuni"],
    Hingoli: ["Hingoli","Basmath", "Kalamnuri", "Aundha Nagnath", "Sengaon"],
    Jalgaon: ["Jalgaon", "Bhusaval", "Yaval", "Raver", "Muktainagar", "Amalner", "Chopda", "Erandol", "Palora", "Chalisgaon", "Jamner", "Pachora", "Bhadgaon", "Dharangaon", "Bodwad"],
    Jalna: ["Jalna", "Ambad", "Partur", "Bhokardan", "Jafrabad", "Badnapur", "Ghansavangi", "Mantha"],
    Kolhapur: ["Kolhapur", "Gadhinglaj", "Karveer", "Bhudargad", "Panhala", "Kagal", "Shirol", "Hatkanangale", "Ajara","Chandgad",  "Gaganbawada", "Radhanagari", "Shahuwadi"],
    Latur: ["Latur", "Udgir", "Nilanga", "Ausa", "Ahemadpur", "Chakur", "Renapur", "Deoni", "Jalkot", "Shirur Anantpal"],
    Mumbai: ["Andheri", "Borivali", "Kurla"],
    Nagpur: ["Ramtek", "Umred", "Kalameshwar", "Katol", "Kamthi", "Kuhi", "Narkhed", "Nagpur"],
    Nanded: [],
    Nandurbar: ["Nandurbar", "Nashik", "Osmanabad"],
    Nashik: ["Nashik", "Osmanabad", "Palghar"],
    Osmanabad: ["Osmanabad", "Palghar", "Parbhani"],
    Palghar: ["Palghar", "Parbhani", "Pune"],
    Parbhani: ["Parbhani", "Pune", "Raigad"],
    Pune: ["Pune", "Raigad", "Ratnagiri"],
    Raigad: ["Raigad", "Ratnagiri", "Sangli"],
    Ratnagiri: ["Ratnagiri", "Sangli", "Satara"],
    Sangli: ["Sangli", "Satara", "Sindhudurg"],
    Satara: ["Satara", "Sindhudurg", "Solapur"],
    Sindhudurg: ["Sindhudurg", "Solapur", "Thane"],
    Solapur: ["Solapur", "Thane", "Wardha"],
    Thane: ["Thane", "Wardha", "Washim"],
    Wardha: ["Wardha", "Washim", "Yavatmal"],
    Washim: ["Washim", "Yavatmal"],
    Yavatmal: ["Yavatmal"]
  };

  // Function to populate taluka options based on selected district
  function populateTalukas() {
    const selectedDistrict = districtSelect.value;
    const talukas = talukaOptions[selectedDistrict] || [];
    talukaSelect.innerHTML = '<option value="">Select Taluka</option>';
    talukas.forEach(taluka => {
      const option = document.createElement('option');
      option.value = taluka;
      option.textContent = taluka;
      talukaSelect.appendChild(option);
    });
    talukaContainer.classList.toggle('hidden', talukas.length === 0);
    submitBtn.classList.toggle('hidden', talukas.length === 0);
  }

  // Event listener to populate taluka options when district is changed
  districtSelect.addEventListener('change', populateTalukas);

  // Event listener to redirect to main.html when the submit button is clicked
  submitBtn.addEventListener('click', () => {
    const selectedTaluka = talukaSelect.value;
    if (selectedTaluka) {
      window.location.href = mainHtmlPath;
    }
  });

  // Initially populate taluka options based on default selected district
  populateTalukas();
</script>
</form>
</body>
</html>
