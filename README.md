value_second: int = int(input('Please enter second: '))
time_minute = value_second // 60
time_second_remainder = value_second % 60
time_hour = value_second // 3600
time_hour_minute = value_second // 60 % 60
time_day = value_second // 86400
time_day_hour = value_second // 3600 % 24
if value_second >= 60:
    if value_second < 3600:
        print('Time:', time_minute, 'minute', time_second_remainder, 'second')
    elif value_second >= 3600:
        if value_second < 86400:
            print('Time: ', time_hour, 'hour', time_hour_minute, 'minute', time_second_remainder, 'second')
        else:
            if value_second >= 86400:
                print('Time: ', time_day, 'day', time_day_hour, 'hour', time_hour_minute, 'minute',
                      time_second_remainder, 'second')
