# HTML Forms
## `The <from> HTML`
- The HTML `<form>` element is used to create an HTML form for user input
- Is a `container` for different `types of input elements`, such as: text fields, checkboxes, radio buttons, submit buttons
## `The <label> Element`
- When a user `clicks or touches/taps a label`, the browser `passes the focus to its associated input`
- The first way

![image](https://user-images.githubusercontent.com/88178841/147376240-4a642301-7360-491d-86ec-f654be366979.png)
![image](https://user-images.githubusercontent.com/88178841/147376228-c2554253-1702-4b36-b507-28a9e448313b.png)
- The second way

![image](https://user-images.githubusercontent.com/88178841/147376261-cf5454bc-f802-4f73-818d-a67156d20787.png)


## `The <input> Element`
![image](https://user-images.githubusercontent.com/88178841/147376004-f6d5c8fc-d65f-4ea7-a0f1-75d12c8318ba.png)

### `Text Fields`
- The `<input type="text">` defines a single-line `input field for text input.`
- ![image](https://user-images.githubusercontent.com/88178841/147376053-646a9010-6245-4f43-a80d-1497eeac96bc.png)
![image](https://user-images.githubusercontent.com/88178841/147376058-977dc97e-8e75-4741-b9e8-9b4d76435858.png)

## `Radio Buttons`
- The `<input type="radio">` defines a radio button.
- `The name duplicate` => user select ONE of a limited number of choices.
- 
![image](https://user-images.githubusercontent.com/88178841/147377492-f939c520-53e3-46c4-9f14-8d1683d80e31.png)
![image](https://user-images.githubusercontent.com/88178841/147377118-1cedb3ca-f1db-4c07-8376-7dd2f723460e.png)
## `Checkboxes`
- The `<input type="checkbox">` defines a checkbox.
- User `select ZERO or MORE` options of a limited number of choices.

![image](https://user-images.githubusercontent.com/88178841/147377525-26e09ff5-4755-434b-95fb-77a35894d784.png)
![image](https://user-images.githubusercontent.com/88178841/147377528-cee3306a-d0bb-4b59-94c3-8abac38c084f.png)

## `The Submit Button`
- The `<input type="submit">` defines a button for submitting the form data to a form-handler.

![image](https://user-images.githubusercontent.com/88178841/147377611-ea8ee445-5b34-42a0-aa48-0720e3b7e3f7.png)
![image](https://user-images.githubusercontent.com/88178841/147377620-0afea5ed-4f9a-4edd-8fee-6fb34d481733.png)

## `Password Input`

![image](https://user-images.githubusercontent.com/88178841/147410171-0135a96b-c5f9-4a28-880d-0168993ee5b9.png)
![image](https://user-images.githubusercontent.com/88178841/147411321-eb2ab821-a912-442d-84b2-15d46e916971.png)

## `Number Input`

![image](https://user-images.githubusercontent.com/88178841/147411364-b7cb4dc8-ed4a-43fc-b32e-cd77318aaef4.png)
![image](https://user-images.githubusercontent.com/88178841/147411371-85292101-f21f-49d7-8431-cd0936378efc.png)

## `Range Input`
- thiết lập `type` để `"range"` mà tạo ra một thanh trượt.
- Đặt giá trị `tối thiểu` và `tối đa` của thanh trượt, gán giá trị cho thuộc tính `min` và `max` của `<input>`
- Linh hoạt của thanh trượt bằng cách gán cho `step` thuộc tính `một giá trị`.

![image](https://user-images.githubusercontent.com/88178841/147413196-0e46b531-0035-45b0-9d8e-8d33dc95e845.png)
![image](https://user-images.githubusercontent.com/88178841/147413201-c976b1ea-e8c8-4043-8771-67514d5f2451.png)

## `Dropdown list`
- Phần tử `<select>` để tạo danh sách thả xuống.
- Tạo danh sách thả xuống, thêm nhiều `<option>` phần tử, mỗi phần tử có 1 `<value>` thuộc tính, được sử dụng khi `<form>` được gửi
- Theo mặc định chỉ 1 trong các tùy chọn có thể được chọn

![image](https://user-images.githubusercontent.com/88178841/147813120-e0a87855-57a9-4cad-a5f6-bbbc1b94bd94.png)
![image](https://user-images.githubusercontent.com/88178841/147813193-cc1d3e36-4e33-4790-b2df-e3747e1648d9.png)
![image](https://user-images.githubusercontent.com/88178841/147813197-72e001c8-891b-4698-80ef-b04d60f2dbe9.png)

## `Datalist`
- Danh sách thả xuống nhưng người dùng có thể nhập và lọc các tùy chọn từ `<datalist>`
- Ví dụ:

![image](https://user-images.githubusercontent.com/88178841/147814757-67271f1f-6388-486f-9c1d-33cfdd2ffafd.png)

## `The Name Attribute for <input>`
- Each `input field` `ust have` a `name attribute` to be submitted.
