![GTKN_egXcAAXDxT](https://github.com/user-attachments/assets/28ff1a66-e7ef-4ec4-adc5-6d1df18c853f)

# Assisterr Incentivized Testnet


## Join Testnet
https://build.assisterr.ai/?ref=66b533f4f92dab2f27784a6d

## Auto daily claim
> if only you are using a windows server you can use this

1- In your browser, Press `F12` or `CTRL+SHIFT+I` to open **Developer window**, You can Write anything in `Console` tab
* Make sure you are in your [assisterr dashboard](https://build.assisterr.ai/dashboard) (daily claim page) when openning Developer window

![Screenshot_169](https://github.com/user-attachments/assets/bd66d7f8-b80e-4f65-b8b2-5f6ed9e1775b)

2- To allow pasting codes, write: `allow pasting`

3- Paste this code when your Assisterr site is open
```
function dailyClaim() {
    // Select Button
    var claimButton = document.querySelector("button.inline-flex.items-center.justify-center.whitespace-nowrap.rounded-md.text-sm.font-medium.ring-offset-background.transition-colors.disabled\\:pointer-events-none.disabled\\:opacity-50.focus-visible\\:outline-\\[darkgrey\\].border.border-input.bg-background.hover\\:bg-accent.hover\\:text-accent-foreground.h-10.px-4.py-2.mt-4.md\\:mt-12.max-w-96.w-full");
    
    if (claimButton) {
        claimButton.click();
        console.log("Daily claim done");
    } else {
        console.log("Daily claim button not found");
    }
}

// Repeats per 12h (43200000 ms)
setInterval(dailyClaim, 43200000);

dailyClaim();
```
