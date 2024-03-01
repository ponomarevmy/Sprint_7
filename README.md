# Яндекс практикум Sprint_7

<h2> Тестирование API https://qa-scooter.praktikum-services.ru/docs/#api-Courier-Login</h2>

Создание курьра - `test_create_courier.py`
<table>
	<tbody>
		<tr>
			<td>test_create_courier</td>
			<td>Создание курьера</td>
		</tr>
		<tr>
			<td>test_courier_was_created</td>
			<td>Нельзя создать двух одинаковых курьеров с одинаковыми логинами</td>
		</tr>
        <tr>
			<td>test_create_courier_without_login</td>
			<td>Нельзя создать курьера без логина</td>
		</tr>
        <tr>
			<td>test_create_courier_without_password</td>
			<td>Нельзя создать курьера без пароля</td>
		</tr>
	</tbody>
</table>

Авторизация - `test_login_courier.py`
<table>
	<tbody>
		<tr>
			<td>test_courier_log_in</td>
			<td>Авторизация под курьером выдает id</td>
		</tr>
		<tr>
			<td>test_courier_log_negative</td>
			<td>Ошибка при авторизации если логин или пароль не корректные</td>
		</tr>
        <tr>
			<td>test_courier_log_not_all_data</td>
			<td>Ошибка при авторизации если не зполнить логин или пароль</td>
		</tr>
    </tbody>
</table>

Создание заказ `test_create_order.py`
<table>
	<tbody>
		<tr>
			<td>test_create_order</td>
			<td>Создание заказа</td>
		</tr>
    </tbody>
</table>


Список заказов `test_list_orders.py`
<table>
	<tbody>
		<tr>
			<td>test_list_order</td>
			<td>В тело ответа возвращается список заказов</td>
		</tr>
    </tbody>
</table>