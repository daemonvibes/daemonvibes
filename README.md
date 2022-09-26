

;;001x  description


```python
<<<<<<< HEAD
main = ['python', 'cracking']

infrastructure_obj = [
    'ALL Game Servers', 'Website downed', 'DataBase downed'
 ]
=======
{
main = ['python', 'cracking']
>>>>>>> df0a30273051c8e4a08c4355cc242b148c096f9a

infrastructure = [
    'ALL Dedicated Hosts', 'ALL Web Hosts', 'ALL deployed VPS',
    'ALL network bandwidth'
 ]
mode = input('Targets (view):\n')

claim_attack = print(f'{infrastructure_obj} of Zeroping.ro')
claim_attack2= print(f'{infrastructure_obj} of Bugged.ro')
claim_attack3 = print(f'{infrastructure_obj} of xenon.minecraft-romania.ro')
claim_attack4 = print(f'{infrastructure_obj} of Nephrite.ro')
claim_attack5 = print(f'{infrastructure_obj} of B-zone.ro\n')
desc = print(f'Daemon | {main}')

def start():
    if mode == 'view':
        print(desc)
        print(claim_attack, claim_attack2, claim_attack3, claim_attack4, claim_attack5)
    else:
        exit(start)

```

## Infos

 - [Website](https://daemonzz.xyz)

 
