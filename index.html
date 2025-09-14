<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Modern Daily Timetable</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    .day-card {
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .day-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.15);
    }
    .checkbox-custom {
      width: 1.5rem;
      height: 1.5rem;
      accent-color: #ffafcc;
    }
    .task-item {
      transition: background-color 0.3s, transform 0.2s;
    }
    .task-item:hover {
      background-color: #ffc8dd;
      transform: translateX(5px);
    }
  </style>
</head>
<body class="bg-gradient-to-r from-[#cdb4db] via-[#ffc8dd] to-[#a2d2ff] min-h-screen flex flex-col items-center py-10">

  <!-- Header with Real Time Date & Time -->
  <div class="text-center mb-8">
    <h1 class="text-4xl font-extrabold text-gray-800 mb-2">📅 My Modern Daily Timetable</h1>
    <p id="dateTime" class="text-lg font-medium text-gray-700"></p>
  </div>

  <!-- 3-Day Calendar -->
  <div class="flex gap-6 mb-10">
    <div id="yesterday" class="day-card bg-white rounded-xl shadow-md p-4 w-40 text-center">
      <h2 class="font-semibold text-gray-600" id="yesterdayDate"></h2>
      <ul class="mt-2 text-sm text-gray-700" id="tasksYesterday"></ul>
    </div>
    <div id="today" class="day-card bg-white rounded-2xl shadow-lg p-6 w-64 text-center border-4 border-[#ffafcc]">
      <h2 class="font-bold text-2xl text-[#ff4d6d]" id="todayDate"></h2>
      <ul class="mt-4 text-left space-y-2 font-bold" id="tasksToday"></ul>
    </div>
    <div id="tomorrow" class="day-card bg-white rounded-xl shadow-md p-4 w-40 text-center">
      <h2 class="font-semibold text-gray-600" id="tomorrowDate"></h2>
      <ul class="mt-2 text-sm text-gray-700" id="tasksTomorrow"></ul>
    </div>
  </div>

  <!-- Timetable -->
  <div class="bg-white shadow-xl rounded-2xl p-8 w-full max-w-3xl">
    <h2 class="text-2xl font-bold text-gray-800 mb-6 text-center">📝 Today's Tasks</h2>
    <div class="space-y-4">
      <label class="flex justify-between items-center bg-[#bde0fe] p-4 rounded-xl shadow task-item">
        <span>6:00 AM – 6:45 AM: Wake up, walk, and exercise</span>
        <input type="checkbox" class="checkbox-custom" data-task="Wake up, walk, and exercise">
      </label>
      <label class="flex justify-between items-center bg-[#bde0fe] p-4 rounded-xl shadow task-item">
        <span>6:45 AM – 7:15 AM: Freshen up</span>
        <input type="checkbox" class="checkbox-custom" data-task="Freshen up">
      </label>
      <label class="flex justify-between items-center bg-[#bde0fe] p-4 rounded-xl shadow task-item">
        <span>7:15 AM – 9:15 AM: Focused study and skill building</span>
        <input type="checkbox" class="checkbox-custom" data-task="Focused study and skill building">
      </label>
      <label class="flex justify-between items-center bg-[#bde0fe] p-4 rounded-xl shadow task-item">
        <span>9:15 AM – 9:50 AM: Breakfast</span>
        <input type="checkbox" class="checkbox-custom" data-task="Breakfast">
      </label>
      <label class="flex justify-between items-center bg-[#bde0fe] p-4 rounded-xl shadow task-item">
        <span>10:00 AM – 4:15 PM: College hours</span>
        <input type="checkbox" class="checkbox-custom" data-task="College hours">
      </label>
      <label class="flex justify-between items-center bg-[#bde0fe] p-4 rounded-xl shadow task-item">
        <span>4:30 PM – 9:00 PM: Intensive skill learning</span>
        <input type="checkbox" class="checkbox-custom" data-task="Intensive skill learning">
      </label>
      <label class="flex justify-between items-center bg-[#bde0fe] p-4 rounded-xl shadow task-item">
        <span>9:00 PM – 9:30 PM: Dinner</span>
        <input type="checkbox" class="checkbox-custom" data-task="Dinner">
      </label>
      <label class="flex justify-between items-center bg-[#bde0fe] p-4 rounded-xl shadow task-item">
        <span>9:30 PM – 11:30 PM: Evening study</span>
        <input type="checkbox" class="checkbox-custom" data-task="Evening study">
      </label>
      <label class="flex justify-between items-center bg-[#bde0fe] p-4 rounded-xl shadow task-item">
        <span>11:30 PM – 11:50 PM: Wind down, plan next day, relax</span>
        <input type="checkbox" class="checkbox-custom" data-task="Wind down, plan next day, relax">
      </label>
      <label class="flex justify-between items-center bg-[#bde0fe] p-4 rounded-xl shadow task-item">
        <span>11:50 PM: Sleep 😴</span>
        <input type="checkbox" class="checkbox-custom" data-task="Sleep 😴">
      </label>
    </div>
  </div>

  <script>
    function updateDateTime() {
      const now = new Date();
      const options = { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric'};
      document.getElementById('dateTime').textContent = now.toLocaleDateString('en-IN', options) + ' ' + now.toLocaleTimeString('en-IN');
    }
    setInterval(updateDateTime, 1000);
    updateDateTime();

    function setDates() {
      const today = new Date();
      const yesterday = new Date(today);
      const tomorrow = new Date(today);
      yesterday.setDate(today.getDate() - 1);
      tomorrow.setDate(today.getDate() + 1);

      document.getElementById('yesterdayDate').textContent = yesterday.toLocaleDateString('en-IN', { day: 'numeric', month: 'short'});
      document.getElementById('todayDate').textContent = today.toLocaleDateString('en-IN', { day: 'numeric', month: 'short'});
      document.getElementById('tomorrowDate').textContent = tomorrow.toLocaleDateString('en-IN', { day: 'numeric', month: 'short'});
    }
    setDates();

    const checkboxes = document.querySelectorAll('.checkbox-custom');
    const tasksToday = document.getElementById('tasksToday');

    checkboxes.forEach(cb => {
      cb.addEventListener('change', (e) => {
        const task = e.target.getAttribute('data-task');
        const existing = tasksToday.querySelector(`[data-task='${task}']`);
        if (e.target.checked) {
          if (!existing) {
            const li = document.createElement('li');
            li.textContent = task;
            li.className = "list-disc list-inside text-gray-800";
            li.setAttribute('data-task', task);
            tasksToday.appendChild(li);
          }
        } else {
          if (existing) tasksToday.removeChild(existing);
        }
      });
    });
  </script>
</body>
</html>
