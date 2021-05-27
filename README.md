# ������������� ������

���� ������ ������ � hex-������� � ������ `Start` � `Stop`.

```html
<button type="button" data-action="start">Start</button>
<button type="button" data-action="stop">Stop</button>
```

```js
const colors = [
  '#FFFFFF',
  '#2196F3',
  '#4CAF50',
  '#FF9800',
  '#009688',
  '#795548',
];
```

������ ������, ������� ����� ������� ������ `Start`, ��� � ������� ������ ����
���� `body` �� ��������� �������� �� ������� ��������� ������-�����. ��� �������
�� ������ `Stop`, ��������� ����� ���� ������ ���������������.

> ?? ����, �� ������ `Start` ����� ������ ����������� ���������� ���. ������
> ���, ����� ���� ��������� ���� ��������, ������ `Start` ���� �� �������.

��� ��������� ���������� ����� (������ �������� ������� ������), ���������
������� `randomIntegerFromInterval`.

```js
const randomIntegerFromInterval = (min, max) => {
  return Math.floor(Math.random() * (max - min + 1) + min);
};
```
