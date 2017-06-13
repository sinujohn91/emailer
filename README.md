**BUG**
Replace the first button generated code with the second button generated code.

## sample data
```json
[{ "name": "na_email",
  "content": {
    "heading": "Your weekly Analysis Newsletter",
    "subject": "something",
    "publisher": "www.thequint.com",
    "duration": "May 24 - May 30",
    "dashboard_url": "http://google.com",
    "polltype_url": "http://facebook.com",
    "quintype_url": "http://yahoo.com"
  }
}, {
  "name": "na_listTwo",
  "content": {
    "heading": "Top Authors",
    "column_two_heading": "Author",
    "column_three_heading": "Page Views",
    "column_four_heading": "Visits",
    "link_url": "http://google.com",
    "link_label": "More Insights",
    "list": [{
      "item_index": "1",
      "item_heading": "Rajeev Kumar",
      "item_sub_heading": "17 stories this week",
      "item_pageviews": "4,356",
      "item_visits": "3,345",
      "item_change": "40",
      "item_change_color": "#20c8a0"
    }, {
      "item_index": "2",
      "item_heading": "Alok Prasanna Kumar",
      "item_sub_heading": "12 stories this week",
      "item_pageviews": "4,891",
      "item_visits": "2,345",
      "item_change": "40",
      "item_change_color": "#20c8a0"
    }, {
      "item_index": "3",
      "item_heading": "Priyanka Thirumurthi",
      "item_sub_heading": "19 stories this week",
      "item_pageviews": "3,243",
      "item_visits": "2,345",
      "item_change": "40",
      "item_change_color": "#e74c3c"
    }]
  }
}, {
  "name": "na_graphOne",
  "content": {
    "current_value": "66,431",
    "current_value_label": "Page Views",
    "previous_value": "20,292",
    "previous_value_label": "Last Week",
    "change_color": "#e74c3c",
    "graph": [{
      "bar_width": "14.28",
      "bar_height_percentage": "20",
      "label": "M"
    }, {
      "bar_width": "14.28",
      "bar_height_percentage": "70",
      "label": "T"
    }, {
      "bar_width": "14.28",
      "bar_height_percentage": "50",
      "label": "W"
    }, {
      "bar_width": "14.28",
      "bar_height_percentage": "80",
      "label": "T"
    }, {
      "bar_width": "14.28",
      "bar_height_percentage": "30",
      "label": "F"
    }, {
      "bar_width": "14.28",
      "bar_height_percentage": "60",
      "label": "S"
    }, {
      "bar_width": "14.28",
      "bar_height_percentage": "80",
      "label": "S"
    }]
  }
}, {
  "name": "na_graphTwo",
  "content": {
    "current_value": "4,234",
    "current_value_label": "Page Views",
    "previous_value": "1,292",
    "previous_value_label": "Last Week",
    "change_color": "#20c8a0",
    "graph": [{
      "bar_width": "14.28",
      "bar_height_percentage": "30",
      "label": "M"
    }, {
      "bar_width": "14.28",
      "bar_height_percentage": "60",
      "label": "T"
    }, {
      "bar_width": "14.28",
      "bar_height_percentage": "80",
      "label": "W"
    }, {
      "bar_width": "14.28",
      "bar_height_percentage": "20",
      "label": "T"
    }, {
      "bar_width": "14.28",
      "bar_height_percentage": "10",
      "label": "F"
    }, {
      "bar_width": "14.28",
      "bar_height_percentage": "90",
      "label": "S"
    }, {
      "bar_width": "14.28",
      "bar_height_percentage": "40",
      "label": "S"
    }]
  }
}, {
  "name": "na_graphThree",
  "content": {
    "heading": "Traffic sources",
    "current_value": "78,431",
    "current_value_label": "Page Views",
    "previous_value": "80,292",
    "previous_value_label": "Last Week",
    "current_label_indicator":  "This Week",
    "previous_label_indicator":  "Last Week",
    "change_color": "#e74c3c",
    "graph": [{
      "percentage": {
        "current": "70",
        "previous": "90",
        "change": "-20"
      },
      "bar_width": "16.7",
      "label": "Social",
      "value": "26,687",
      "change_color": "#e74c3c"
    }, {
      "percentage": {
        "current": "40",
        "previous": "80",
        "change": "-40"
      },
      "bar_width": "16.7",
      "label": "Google",
      "value": "20,168",
      "change_color": "#e74c3c"
    }, {
      "percentage": {
        "current": "90",
        "previous": "70",
        "change": "+20"
      },
      "bar_width": "16.7",
      "label": "Facebook",
      "value": "1,687",
      "change_color": "#20c8a0"
    }, {
      "percentage": {
        "current": "30",
        "previous": "40",
        "change": "+10"
      },
      "bar_width": "16.7",
      "label": "Direct",
      "value": "2,668",
      "change_color": "#20c8a0"
    }, {
      "percentage": {
        "current": "70",
        "previous": "80",
        "change": "-10"
      },
      "bar_width": "16.7",
      "label": "Main",
      "value": "6,777",
      "change_color": "#e74c3c"
    }, {
      "percentage": {
        "current": "40",
        "previous": "50",
        "change": "-10"
      },
      "bar_width": "16.7",
      "label": "Others",
      "value": "1,222",
      "change_color": "#e74c3c"
    }]
  }
}, {
  "name": "na_listOne",
  "content": {
    "heading": "Top Articles",
    "column_two_heading": "Article",
    "column_three_heading": "Page Views",
    "column_four_heading": "Visits",
    "link_url": "http://google.com",
    "link_label": "More Insights",
    "list": [{
      "item_index": "1",
      "item_heading": "Bill Clinton Co-Authors Thriller Novel &hellip;",
      "item_sub_heading": "By Alok Prasanna Kumar on May 29",
      "item_pageviews": "4,356",
      "item_visits": "2,345"
    }, {
      "item_index": "2",
      "item_heading": "Baahubali 2: Who Killed Baahubali? Kattappa or SS Rajamouli?",
      "item_sub_heading": "By Priyanka Thirumurthi on May 24",
      "item_pageviews": "4,891",
      "item_visits": "2,345"
    }, {
      "item_index": "3",
      "item_heading": "Andhra MLA Moves Trees That Were Going to Be Axed, on His Own Dime",
      "item_sub_heading": "By Tanmoy Bhaduri on May 26",
      "item_pageviews": "3,243",
      "item_visits": "2,345"
    }, {
      "item_index": "4",
      "item_heading": "Sridevi Was the First Choice for Queen Sivagami in ‘Baahubali’",
      "item_sub_heading": "By Rajeev Kumar on May 25",
      "item_pageviews": "3,152",
      "item_visits": "2,345"
    }, {
      "item_index": "5",
      "item_heading": "SC Sentences Justice Karnan to 6-Month Jail For Contempt of Court",
      "item_sub_heading": "By Alok Prasanna Kumar on May 24",
      "item_pageviews": "2,342",
      "item_visits": "2,345"
    }]
  }
}]

```



# Foundation for Emails Template

[![devDependency Status](https://david-dm.org/zurb/foundation-emails-template/dev-status.svg)](https://david-dm.org/zurb/foundation-emails-template#info=devDependencies)

**Please open all issues with this template on the main [Foundation for Emails](http://github.com/zurb/foundation-emails/issues) repo.**

This is the official starter project for [Foundation for Emails](http://foundation.zurb.com/emails), a framework for creating responsive HTML devices that work in any email client. It has a Gulp-powered build system with these features:

- Handlebars HTML templates with [Panini](http://github.com/zurb/panini)
- Simplified HTML email syntax with [Inky](http://github.com/zurb/inky)
- Sass compilation
- Image compression
- Built-in BrowserSync server
- Full email inlining process

## Installation

To use this template, your computer needs [Node.js](https://nodejs.org/en/) 0.12 or greater. The template can be installed with the Foundation CLI, or downloaded and set up manually.

### Using the CLI

Install the Foundation CLI with this command:

```bash
npm install foundation-cli --global
```

Use this command to set up a blank Foundation for Emails project:

```bash
foundation new --framework emails
```

The CLI will prompt you to give your project a name. The template will be downloaded into a folder with this name.

### Manual Setup

To manually set up the template, first download it with Git:

```bash
git clone https://github.com/zurb/foundation-emails-template projectname
```

Then open the folder in your command line, and install the needed dependencies:

```bash
cd projectname
npm install
```

## Build Commands

Run `npm start` to kick off the build process. A new browser tab will open with a server pointing to your project files.

Run `npm run build` to inline your CSS into your HTML along with the rest of the build process.

Run `npm run litmus` to build as above, then submit to litmus for testing. *AWS S3 Account details required (config.json)*

Run `npm run mail` to build as above, then send to specified email address for testing. *SMTP server details required (config.json)*

Run `npm run zip` to build as above, then zip HTML and images for easy deployment to email marketing services.

### Speeding Up Your Build

If you create a lot of emails, your build can start to slow down, as each build rebuilds all of the emails in the
repository. A simple way to keep it fast is to archive emails you no longer need by moving the pages into `src/pages/archive`.
You can also move images that are no longer needed into `src/assets/img/archive`. The build will ignore pages and images that
are inside the archive folder.

## Litmus Tests (config.json)

Testing in Litmus requires the images to be hosted publicly. The provided gulp task handles this by automating hosting to an AWS S3 account. Provide your Litmus and AWS S3 account details in the `example.config.json` and then rename to `config.json`. Litmus config, and `aws.url` are required, however if you follow the [aws-sdk suggestions](http://docs.aws.amazon.com/AWSJavaScriptSDK/guide/node-configuring.html) you don't need to supply the AWS credentials into this JSON.

```json
{
  "aws": {
    "region": "us-east-1",
    "accessKeyId": "YOUR_ACCOUNT_KEY",
    "secretAccessKey": "YOUR_ACCOUNT_SECRET",
    "params": {
        "Bucket": "elasticbeanstalk-us-east-1-THIS_IS_JUST_AN_EXAMPLE"
    },
    "url": "https://s3.amazonaws.com/elasticbeanstalk-us-east-1-THIS_IS_JUST_AN_EXAMPLE"
  },
  "litmus": {
    "username": "YOUR_LITMUS@EMAIL.com",
    "password": "YOUR_ACCOUNT_PASSWORD",
    "url": "https://YOUR_ACCOUNT.litmus.com",
    "applications": ["ol2003","ol2007","ol2010","ol2011","ol2013","chromegmailnew","chromeyahoo","appmail9","iphone5s","ipad","android4","androidgmailapp"]
  }
}
```

## Manual email tests (config.json)

Similar to the Litmus tests, you can have the emails sent to a specified email address. Just like with the Litmus tests, you will need to provide AWS S3 account details in `config.json`. You will also need to specify to details of an SMTP server. The email address to send to emails to can either by configured in the `package.json` file or added as a parameter like so: `npm run mail -- --to="example.com"`

```json
{
  "aws": {
    "region": "us-east-1",
    "accessKeyId": "YOUR_ACCOUNT_KEY",
    "secretAccessKey": "YOUR_ACCOUNT_SECRET",
    "params": {
        "Bucket": "elasticbeanstalk-us-east-1-THIS_IS_JUST_AN_EXAMPLE"
    },
    "url": "https://s3.amazonaws.com/elasticbeanstalk-us-east-1-THIS_IS_JUST_AN_EXAMPLE"
  },
  "mail": {
    "to": [
      "example@domain.com"
    ],
    "from": "Company name <info@company.com",
    "smtp": {
      "auth": {
        "user": "example@domain.com",
        "pass": "12345678"
      },
      "host": "smtp.domain.com",
      "secureConnection": true,
      "port": 465
    }
  }
}
```

For a full list of Litmus' supported test clients(applications) see their [client list](https://litmus.com/emails/clients.xml).

**Caution:** AWS Service Fees will result, however, are usually very low do to minimal traffic. Use at your own discretion.

