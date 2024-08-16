### Way №1 (I suggested first)

1. Item 1
2. Item 2
3. Item 3  
    
    3.1 Item 3a  
    3.2 Item 3b  
    ```
    let message = 'Hello world';
    alert(message);
    ```
    3.2.1 Item 3ba  
    ```
    let message = 'Hello world';
    alert(message);
    ```
4. Item 3c  
```
let message = 'Hello world';
alert(message);
```

### Way №2 (original with little modification)

1. Item 1  
2. Item 2  
3. Item 3  
    1. Item 3a  
    2. Item 3b  
        ```
        let message = 'Hello world';
        alert(message);
        ```
        1. Item 3ba  
            ```
            let message = 'Hello world';
            alert(message);
            ```
4. Item 3c  
    ```
    let message = 'Hello world';
    alert(message);
    ```

### Way №3 (most universal)

1. Item 1
2. Item 2  
3. Item 3
<ul>
3.1 Item 3a <br>
3.2 Item 3b <br>
    <pre><code>let message = 'Hello world';
    alert(message);</code></pre>
<ul>
3.2.1 Item 3ba <br>
    <pre><code>let message = 'Hello world';
    alert(message);</code></pre>
</ul>
3.3 Item 3c <br>   
    <pre><code>let message = 'Hello world';
    alert(message);</code></pre>
</ul>

### Way №4 (also possible)

1. Item 1  
2. Item 2  
3. Item 3  
$\hspace{1cm}$ 3.1 Item 3a  
$\hspace{1cm}$ 3.2 Item 3b  
```
\hspace{1cm}$ let message = 'Hello world';
\hspace{1cm}$ alert(message);
```  
$\hspace{2cm}$ 3.2.1 Item 3ba  
```
$\hspace{2cm}$ let message = 'Hello world';
$\hspace{2cm}$ alert(message);
```
$\hspace{1cm}$ 3.3 Item 3c     
```
$\hspace{1cm}$ let message = 'Hello world';
$\hspace{1cm}$ alert(message);
```

