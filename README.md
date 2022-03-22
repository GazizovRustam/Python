value_second: int = int(input('Please enter second: '))
time_minute = value_second // 60
time_second_remainder = value_second % 60
time_hour = value_second // 3600
time_hour_minute = value_second // 60 % 60
time_hour_minute_second_remainder = value_second % 60
if value_second >= 60:
    if value_second < 3600:
        print('Time:', time_minute, 'minute',',', time_second_remainder ,'second')
    elif value_second >= 3600:
        print('Time: ',time_hour,'hour',time_hour_minute,'minute',time_hour_minute_second_remainder,'second')
    elif value_second >= 3600:
        print('Time: ',time_hour,'hour',time_hour_minute,'minute',time_hour_minute_second_remainder,'second')
