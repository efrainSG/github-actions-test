# Secrets
First of all must create an environment for the secrets, after it's possible add new secrets.
# YAML sintax
<pre>
key: value
key2: value2
key3:
    key1: value1
    key2: value2
jsonObject: { key: value, key2: value2, key3: { key1: value1, key2: value2 } }
array:
    - item1
    - item2
    - { key: value, key2: value2 }
jsonArray: [item]
objectsArray:
    - key1: value1
      key2: value2
      key3: value3
    - key2: value2
      key4: value4
longText1: >
    Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aenean commodo ligula eget dolor.
    Aenean massa.
    Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
    Donec qu...
longText2: |
    Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aenean commodo ligula eget dolor.
    Aenean massa.
    Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
    Donec qu...
</pre>
