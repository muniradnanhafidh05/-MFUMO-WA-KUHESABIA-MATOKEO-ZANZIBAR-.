<!doctype html>
<html lang="sw"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>MFUMO WA KUHISABIYA MATOKEO ZANZIBAR</title> 
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
    
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f7fa;
    }
    
    .header {
      background: linear-gradient(135deg, #1e5799 0%, #207cca 51%, #2989d8 100%);
      color: white;
      padding: 30px 0;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    
    .header h1 {
      margin: 0;
      font-size: 2.5rem;
      text-transform: uppercase;
      letter-spacing: 2px;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
    }
    
    .header-image {
      width: 100%;
      max-height: 300px;
      object-fit: cover;
      margin-top: 20px;
      border-bottom: 5px solid #f8c537;
    }
    
    .container {
      max-width: 1000px;
      margin: 30px auto;
      padding: 30px;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    }
    
    .form-group {
      margin-bottom: 25px;
    }
    
    label {
      display: block;
      margin-bottom: 8px;
      font-weight: bold;
      color: #2c3e50;
    }
    
    input, select {
      width: 100%;
      padding: 12px;
      border: 1px solid #ddd;
      border-radius: 6px;
      font-size: 16px;
      transition: border 0.3s;
    }
    
    input:focus, select:focus {
      border-color: #3498db;
      outline: none;
      box-shadow: 0 0 0 3px rgba(52,152,219,0.2);
    }
    
    .date-section {
      display: flex;
      gap: 15px;
      margin-bottom: 25px;
    }
    
    .date-section div {
      flex: 1;
    }
    
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 25px 0;
    }
    
    th, td {
      border: 1px solid #ddd;
      padding: 12px;
      text-align: left;
    }
    
    th {
      background-color: #3498db;
      color: white;
      font-weight: bold;
    }
    
    tr:nth-child(even) {
      background-color: #f8f9fa;
    }
    
    .btn {
      background-color: #f8c537;
      color: #2c3e50;
      border: none;
      padding: 12px 25px;
      border-radius: 6px;
      cursor: pointer;
      font-size: 16px;
      font-weight: bold;
      transition: all 0.3s;
      margin-right: 10px;
      margin-top: 10px;
    }
    
    .btn:hover {
      background-color: #e6b22e;
      transform: translateY(-2px);
    }
    
    .btn-primary {
      background-color: #3498db;
      color: white;
    }
    
    .btn-primary:hover {
      background-color: #2980b9;
    }
    
    .result-box {
      background-color: #f8f9fa;
      padding: 20px;
      border-radius: 8px;
      margin-top: 30px;
      border-left: 5px solid #3498db;
    }
    
    .student-result {
      margin-bottom: 15px;
      padding: 15px;
      background-color: white;
      border-radius: 6px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }
    
    .footer {
      text-align: center;
      padding: 20px;
      color: #7f8c8d;
      font-size: 14px;
      margin-top: 50px;
    }
    
    @media print {
      .no-print {
        display: none;
      }
      body {
        background-color: white;
      }
      .container {
        box-shadow: none;
      }
    }
  </style> 
 </head> 
 <body> 
  <div class="header"> 
   <h1>MFUMO WA KUHISABIYA MATOKEO ZANZIBAR</h1> 
   <img src="https://images.unsplash.com/photo-1523050854058-8df90110c9f1?ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1350&amp;q=80" alt="Wanafunzi wakisoma" class="header-image"> 
  </div> 
  <div class="container"> 
   <div class="form-group"> <label for="teacherName">Jina la Mwalimu:</label> 
    <input type="text" id="teacherName" placeholder="Andika jina lako kamili"> 
   </div> 
   <div class="date-section"> 
    <div class="form-group"> <label for="year">Mwaka wa Matokeo:</label> <select id="year"> <option value="">Chagua Mwaka</option> <option value="2023">2023</option> <option value="2024">2024</option> <option value="2025">2025</option> <option value="2026">2026</option> </select> 
    </div> 
    <div class="form-group"> <label for="month">Mwezi:</label> <select id="month"> <option value="">Chagua Mwezi</option> <option value="Januari">Januari</option> <option value="Februari">Februari</option> <option value="Machi">Machi</option> <option value="Aprili">Aprili</option> <option value="Mei">Mei</option> <option value="Juni">Juni</option> <option value="Julai">Julai</option> <option value="Agosti">Agosti</option> <option value="Septemba">Septemba</option> <option value="Oktoba">Oktoba</option> <option value="Novemba">Novemba</option> <option value="Desemba">Desemba</option> </select> 
    </div> 
    <div class="form-group"> <label for="date">Tarehe:</label> 
     <input type="number" id="date" min="1" max="31" placeholder="Tarehe"> 
    </div> 
   </div> 
   <h2>Weka Alama za Wanafunzi</h2> 
   <table id="studentsTable"> 
    <thead> 
     <tr> 
      <th>#</th> 
      <th>Jina la Mwanafunzi</th> 
      <th>Namba ya Usajili</th> 
      <th>Kiswahili</th> 
      <th>English</th> 
      <th>Hesabati</th> 
      <th>Biology</th> 
      <th>Chemistry</th> 
      <th>Physics</th> 
      <th>Maarifa</th> 
      <th class="no-print">Hatua</th> 
     </tr> 
    </thead> 
    <tbody> <!-- Rows will be added here by JavaScript --> 
    </tbody> 
   </table> <button class="btn no-print" onclick="addStudentRow()">+ Ongeza Mwanafunzi</button> <button class="btn btn-primary no-print" onclick="calculateAll()">Hesabu Matokeo Yote</button> <button class="btn no-print" onclick="window.print()">Chapisha Matokeo (PDF)</button> 
   <div id="resultsContainer"></div> 
  </div> 
  <div class="footer no-print">
    MFUMO WA KUHISABIYA MATOKEO ZANZIBAR © <span id="currentYear"></span> 
  </div> 
  <script>
    // Set current year in footer
    document.getElementById("currentYear").textContent = new Date().getFullYear();
    
    // Initialize with 3 empty rows
    window.onload = function() {
      for (let i = 0; i < 3; i++) {
        addStudentRow();
      }
      
      // Set current month
      const months = ["Januari", "Februari", "Machi", "Aprili", "Mei", "Juni", 
                     "Julai", "Agosti", "Septemba", "Oktoba", "Novemba", "Desemba"];
      const currentMonth = months[new Date().getMonth()];
      document.getElementById("month").value = currentMonth;
      
      // Set current date
      document.getElementById("date").value = new Date().getDate();
      
      // Set current year
      document.getElementById("year").value = new Date().getFullYear();
    };
    
    function addStudentRow() {
      const tbody = document.querySelector("#studentsTable tbody");
      const row = document.createElement("tr");
      const rowNum = tbody.children.length + 1;
      
      row.innerHTML = `
        <td>${rowNum}</td>
        <td><input type="text" placeholder="Jina" class="student-name"></td>
        <td><input type="text" placeholder="Usajili" class="reg-number"></td>
        <td><input type="number" min="0" max="100" class="subject-mark"></td>
        <td><input type="number" min="0" max="100" class="subject-mark"></td>
        <td><input type="number" min="0" max="100" class="subject-mark"></td>
        <td><input type="number" min="0" max="100" class="subject-mark"></td>
        <td><input type="number" min="0" max="100" class="subject-mark"></td>
        <td><input type="number" min="0" max="100" class="subject-mark"></td>
        <td><input type="number" min="0" max="100" class="subject-mark"></td>
        <td class="no-print"><button class="btn" onclick="removeRow(this)">Futa</button></td>
      `;
      
      tbody.appendChild(row);
    }
    
    function removeRow(button) {
      const row = button.closest("tr");
      row.remove();
      updateRowNumbers();
    }
    
    function updateRowNumbers() {
      const rows = document.querySelectorAll("#studentsTable tbody tr");
      rows.forEach((row, index) => {
        row.cells[0].textContent = index + 1;
      });
    }
    
    function calculateAll() {
      const teacher = document.getElementById("teacherName").value || "Mwalimu";
      const year = document.getElementById("year").value || "----";
      const month = document.getElementById("month").value || "----";
      const date = document.getElementById("date").value || "--";
      
      const rows = document.querySelectorAll("#studentsTable tbody tr");
      let resultsHTML = `
        <div class="result-box">
          <h2>MATOKEO YA WANAFUNZI - ${year}</h2>
          <p>Mwalimu: ${teacher} | Tarehe: ${date} ${month} ${year}</p>
          <hr>
      `;
      
      rows.forEach(row => {
        const name = row.querySelector(".student-name").value || "Mwanafunzi";
        const reg = row.querySelector(".reg-number").value || "-";
        const marks = Array.from(row.querySelectorAll(".subject-mark")).map(input => {
          return input.value ? parseInt(input.value) : 0;
        });
        
        // Calculate average
        const total = marks.reduce((sum, mark) => sum + mark, 0);
        const average = Math.round(total / marks.length);
        
        // Determine grade
        let grade, division;
        if (average >= 75) { grade = "A"; division = "I"; }
        else if (average >= 65) { grade = "B"; division = "II"; }
        else if (average >= 45) { grade = "C"; division = "III"; }
        else if (average >= 30) { grade = "D"; division = "IV"; }
        else { grade = "F"; division = "0"; }
        
        // Add to results display
        resultsHTML += `
          <div class="student-result">
            <h3>${name} - ${reg}</h3>
            <p><strong>Alama:</strong> ${marks.join(", ")}</p>
            <p><strong>Wastani:</strong> ${average}</p>
            <p><strong>Gredi:</strong> ${grade}</p>
            <p><strong>Division:</strong> ${division}</p>
          </div>
        `;
      });
      
      resultsHTML += `</div>`;
      document.getElementById("resultsContainer").innerHTML = resultsHTML;
    }
  </script> 
 </body>
</html>
