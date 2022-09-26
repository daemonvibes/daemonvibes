

# _Description:


```python 
infrastructure_obj = [
    'Website downed', 'DataBase downed'
 ]

main = ['python', 'cracking']
infrastructure = [
    'ALL Dedicated Hosts', 'ALL Web Hosts', 'ALL deployed VPS',
    'ALL network bandwidth'
 ]
infra_main = f"['All Game servers'] + {infrastructure_obj}"

mode = input('Targets (view):')

claim_attack = print(f'{infra_main} of Zeroping.ro')
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
## Output code
### Targets (view):view
['All Game servers'] + ['Website downed', 'DataBase downed'] of Zeroping.ro

['Website downed', 'DataBase downed'] of Bugged.ro

['Website downed', 'DataBase downed'] of xenon.minecraft-romania.ro

['Website downed', 'DataBase downed'] of Nephrite.ro

['Website downed', 'DataBase downed'] of B-zone.ro

#### Daemon | ['python', 'cracking']

### Process finished with exit code 0
## Infos

 - [Website](https://daemonzz.xyz)

 
