# Creating Tab UI with CSS and HTML only

This is a simple example of how to create a tab UI with CSS and HTML only. It is a very simple example, but it can be used as a starting point for more complex UIs.

## Usage

1. Clone the repository 
2. (Optional) Edit the `index.html` file to add your own tabs and run the `index.html` file in your browser to get a preview of the UI
3. Copy contents of css in the folder: `static/css/style.css` to your own css file

## Example
**Create the tab container**
- First add a tab container, your html should look like this:

```html
    <div class="tab-container">
        ...
    </div>
```
- Then add a tabs div, your html should look like this:


```html
    <div class="tab-container">
        <div class="tabs">
            <label for="tab-1" class="tab"> Tab 1 </label>
            <label for="tab-2" class="tab"> Tab 2 </label>
            <label for="tab-3" class="tab"> Tab 3 </label>
        </div>
    </div>
```

- finally (for the tab container), add the slider element like this: 

```html 
    <div class="tab-container">
        <div class="tabs">
            <label for="tab-1" class="tab"> Tab 1 </label>
            ...
            <span class="slider"></span>
        </div>
    </div>
```

- Now add the content for each tab, your html should look like this:

```html
    <div class="tab-container">
        <div class="tabs">
            <label for="tab-1" class="tab"> Tab 1 </label>
            ...
            <span class="slider"></span>
        </div>
        <div class="panels">
            <div class="panel">
                <input type="radio" id="tab-1" name="tab-group-1" checked />
                <div class="content">
                    <h2>Tab 1 Content</h2>
                </div>
            </div>
            ...
        </div>
    </div>
```

