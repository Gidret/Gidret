<p align="center">
 <img width="100%" src="assets/gidret.gif" />
</p>

<div align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Google+Sans&size=30&pause=1000&color=F7EC00&center=true&vCenter=true&width=435&lines=Hello%2C+I%60m+Gidret" alt="Typing SVG" /></a>
</div>

<img width="25%" align='right' src="assets/img.jpg">

<br>

<h3 align="left">
Hi there
<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"/>
</h3>

I'm Gidret, a Full-Stack Web Developer & UI/UX Designer. I want to become a software architecture & design pro. <br>
I've dreamed of building beautiful, world-changing applications since I was a kid.

<details>
  <summary>More about me</summary>

- **Name**: Gidret
- **From**: Russia
- Full-Stack Dev | UI/UX Designer
- I have a solid foundation in frontend, backend, interface design & prototyping


</details>
<br>

---

<h2 align="center">Technologies</h2> 

<div align="center">

[![My Skills](https://skillicons.dev/icons?i=html,css,php,mysql,git)](https://skillicons.dev) <br>
[![My Skills](https://skillicons.dev/icons?i=js,threejs,react,figma,blender)](https://skillicons.dev)

<img src="https://github-readme-stats-two-nu.vercel.app/api/top-langs/?username=Gidret&layout=compact&theme=tokyonight&hide_border=true" width="40%" alt="Top Languages" />

</div>



---

<h2 align="center">My statistics</h2>

<div align="center">
  <a href="https://git.io/streak-stats">
    <img src="https://github-readme-streak-stats.herokuapp.com?user=Gidret&theme=tokyonight&hide_border=true" width="50%" alt="GitHub Streak" />
  </a>
</div>

<br>

<p align="center">
  <img src="https://github-readme-stats-two-nu.vercel.app/api?username=Gidret&show_icons=true&theme=tokyonight&hide_border=true" width="50%" alt="GitHub Stats" />
</p>

<div align="center">
  <img src="https://github-activity-graph.vercel.app/graph?username=Gidret&bg_color=1a1b26&color=7aa2f7&line=7aa2f7&point=bb9af7&area=true&hide_border=true" alt="Activity Graph" />
</div>

<br>

---

<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Анализ числовых наборов</title>
    <style>
        :root {
            --primary-color: #4f46e5;
            --primary-hover: #4338ca;
            --bg-color: #f3f4f6;
            --card-bg: #ffffff;
            --text-color: #1f2937;
            --border-color: #e5e7eb;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: var(--card-bg);
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
        }

        h1, h2 {
            color: var(--primary-color);
        }

        .task-description {
            background: #eef2ff;
            padding: 15px;
            border-left: 4px solid var(--primary-color);
            border-radius: 4px;
            margin-bottom: 25px;
            line-height: 1.5;
        }

        .form-group {
            margin-bottom: 20px;
        }

        label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
        }

        input[type="number"], textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid var(--border-color);
            border-radius: 6px;
            font-size: 16px;
            box-sizing: border-box;
        }

        textarea {
            resize: vertical;
            height: 100px;
        }

        button {
            background-color: var(--primary-color);
            color: white;
            border: none;
            padding: 12px 20px;
            font-size: 16px;
            font-weight: 600;
            border-radius: 6px;
            cursor: pointer;
            transition: background-color 0.2s;
        }

        button:hover {
            background-color: var(--primary-hover);
        }

        .result-box {
            margin-top: 20px;
            padding: 15px;
            background: #f9fafb;
            border: 1px solid var(--border-color);
            border-radius: 6px;
        }

        /* Стили для таблицы */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        th, td {
            border: 1px solid var(--border-color);
            padding: 12px;
            text-align: left;
        }

        th {
            background-color: #f9fafb;
            font-weight: 600;
        }

        .tag {
            display: inline-block;
            padding: 4px 8px;
            border-radius: 4px;
            font-weight: bold;
            font-size: 14px;
        }
        .tag-1 { background: #d1fae5; color: #065f46; }
        .tag-minus1 { background: #fee2e2; color: #991b1b; }
        .tag-0 { background: #fef3c7; color: #92400e; }
    </style>
</head>
<body>

<div class="container">
    <h1>Лабораторная работа / Задание</h1>
    
    <div class="task-description">
        <strong>Условие:</strong> Дано целое число K, а также K наборов ненулевых целых чисел. Каждый набор содержит не менее двух элементов, признаком его завершения является число 0. 
        <br>• Если элементы возрастают — вывести <b>1</b>.
        <br>• Если элементы убывают — вывести <b>-1</b>.
        <br>• Иначе — вывести <b>0</b>.
    </div>

    <!-- Интерактивная часть (Задание 1) -->
    <h2>Интерактивный расчет</h2>
    <div class="form-group">
        <label for="setsInput">Введите наборы чисел (каждый набор с новой строки, числа через пробел, в конце каждого набора укажите 0):</label>
        <textarea id="setsInput" placeholder="Пример:&#10;2 5 8 0&#10;10 6 3 0&#10;3 5 4 0">2 5 8 0
10 6 3 0
3 5 4 0</textarea>
    </div>
    <button onclick="processSets()">Запустить расчет</button>

    <div class="result-box" id="outputResult">
        <strong>Результаты выполнения появятся здесь...</strong>
    </div>

    <!-- Таблица тестирования (Задание 2) -->
    <h2>Таблица тестирования</h2>
    <table>
        <thead>
            <tr>
                <th>Действие</th>
                <th>№ шага</th>
                <th>Описание шага</th>
                <th>Ожидаемый результат</th>
                <th>Фактический результат</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Ввод возрастающего набора</td>
                <td>1</td>
                <td>Ввести набор: <code>2 5 8 0</code></td>
                <td><span class="tag tag-1">1</span> (возрастает)</td>
                <td><span class="tag tag-1" id="fact-1">1</span></td>
            </tr>
            <tr>
                <td>Ввод убывающего набора</td>
                <td>1</td>
                <td>Ввести набор: <code>10 6 3 0</code></td>
                <td><span class="tag tag-minus1">-1</span> (убывает)</td>
                <td><span class="tag tag-minus1" id="fact-2">-1</span></td>
            </tr>
            <tr>
                <td>Ввод смешанного набора</td>
                <td>1</td>
                <td>Ввести набор: <code>3 5 4 0</code></td>
                <td><span class="tag tag-0">0</span> (не возрастает и не убывает)</td>
                <td><span class="tag tag-0" id="fact-3">0</span></td>
            </tr>
        </tbody>
    </table>
</div>

<script>
    function analyzeArray(arr) {
        // Убираем всё после первого нуля (включая сам ноль)
        const zeroIndex = arr.indexOf(0);
        if (zeroIndex !== -1) {
            arr = arr.slice(0, zeroIndex);
        }
        
        if (arr.length < 2) return 0;

        let status = 0;
        if (arr[1] > arr[0]) status = 1;
        else if (arr[1] < arr[0]) status = -1;
        else status = 0;

        for (let i = 2; i < arr.length; i++) {
            let prev = arr[i - 1];
            let curr = arr[i];

            if (status === 1 && curr <= prev) {
                status = 0;
            } else if (status === -1 && curr >= prev) {
                status = 0;
            }
        }
        return status;
    }

    function processSets() {
        const text = document.getElementById('setsInput').value;
        const lines = text.trim().split('\n');
        let htmlOutput = '<strong>Результаты:</strong><br><ul>';

        lines.forEach((line, index) => {
            const numbers = line.trim().split(/\s+/).map(Number);
            const res = analyzeArray(numbers);
            
            let tagClass = 'tag-0';
            if (res === 1) tagClass = 'tag-1';
            if (res === -1) tagClass = 'tag-minus1';

            htmlOutput += `<li>Набор №${index + 1} ([${numbers.join(', ')}]): результат = <span class="tag ${tagClass}">${res}</span></li>`;
        });

        htmlOutput += '</ul>';
        document.getElementById('outputResult').innerHTML = htmlOutput;
    }
</script>

</body>
</html>
