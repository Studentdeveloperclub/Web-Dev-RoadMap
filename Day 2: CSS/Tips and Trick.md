# Additional Materials

## 💡 How to add custom icons using font-awesome

> **Step 1**:  copy all.min.css from [cdn links](https://cdnjs.com/libraries/font-awesome) by clicking on lik tag `</>` Now add this link before `</head>` tage that means inside `<head> paste here </head>`
>
> **Step 2**: Now go to the [font-awesome](https://fontawesome.com/search) platform and search icon that you want for example profile, close, menu.
>
> **Step 3**: Now select free icon(Not labeled with pro) and click on `HTMl` tab and copy `<i class="fa-solid fa-user"></i>` tag and paste which place you want use

### Example

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>How To Use Custom Icon</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css"/>
</head>
<body>
    <nav>
        <div class="logo">
            <i class="fa-brands fa-google"></i>
        </div>
        <div class="user">
            <i class="fa-solid fa-user"></i>
        </div>
    </nav>
</body>
</html>
```
