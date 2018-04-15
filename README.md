# Monit

## Install Monit

```bash
wget https://raw.githubusercontent.com/PageSpeed-Ninjas/kit/master/monit.sh; chmod +x monit.sh; bash monit.sh
```


![Monit](https://i.imgur.com/9w4fOi6.png)

- `aptitude -y install monit`
- `cd /etc`
- `git clone https://github.com/PageSpeed-Ninjas/monit.d.git`
- `chmod -R 700 /etc/monit.d`
- `cat /etc/monit.d/monitrc > /etc/monit/monitrc`
- `cp /etc/monit.d/templates /etc/monit/templates`

