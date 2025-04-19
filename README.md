<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>PLAN-IA - Planilha de Precificação Inteligente</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      background-color: #f4faff;
    }

    h1 {
      text-align: center;
      color: #007BFF;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
      background-color: #ffffff;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }

    th, td {
      border: 1px solid #ccc;
      padding: 10px;
      text-align: center;
    }

    th {
      background-color: #e6f0ff;
    }

    input[type="number"], input[type="text"], input[type="date"] {
      width: 100%;
      padding: 5px;
      box-sizing: border-box;
    }

    input[readonly] {
      background-color: #f9f9f9;
      font-weight: bold;
    }

    .ia-msg {
      font-weight: bold;
      font-size: 0.9em;
    }

    #addRowBtn {
      margin-top: 15px;
      padding: 10px 20px;
      background-color: #007BFF;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }

    #addRowBtn:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <h1>PLAN-IA - Precificação Inteligente com IA</h1>

  <table id="priceTable">
    <thead>
      <tr>
        <th>Data da Compra</th>
        <th>Produto</th
