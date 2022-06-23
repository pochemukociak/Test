{
  "id": "4bd32430-31e2-47be-b7b9-ef0983d125d6",
  "version": "2.0",
  "name": "Recorder",
  "url": "https://demoqa.com",
  "tests": [{
    "id": "4442e154-ded0-4f9f-8762-6f8ae97ee605",
    "name": "Test",
    "commands": [{
      "id": "746d52d0-9dd5-434b-9bb1-0c50e4e48e75",
      "comment": "",
      "command": "open",
      "target": "/",
      "targets": [],
      "value": ""
    }, {
      "id": "fd9629e7-fa8f-46c9-8f72-fd8591e08fbc",
      "comment": "",
      "command": "setWindowSize",
      "target": "1346x708",
      "targets": [],
      "value": ""
    }, {
      "id": "cc1b6d10-d447-4bca-ace6-51d6e4804d97",
      "comment": "",
      "command": "click",
      "target": "css=.card:nth-child(1) .card-body",
      "targets": [
        ["css=.card:nth-child(1) .card-body", "css:finder"],
        ["xpath=//div[@id='app']/div/div/div[2]/div/div/div/div[3]", "xpath:idRelative"],
        ["xpath=//div[3]", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "0627a2df-67d3-4a83-8694-2a824681f4a8",
      "comment": "",
      "command": "click",
      "target": "css=.show #item-1 > .text",
      "targets": [
        ["css=.show #item-1 > .text", "css:finder"],
        ["xpath=//li[@id='item-1']/span", "xpath:idRelative"],
        ["xpath=//li[2]/span", "xpath:position"],
        ["xpath=//span[contains(.,'Check Box')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "e1bccfe2-7587-4f22-b0d9-641f428adcce",
      "comment": "",
      "command": "click",
      "target": "css=.rct-icon-uncheck",
      "targets": [
        ["css=.rct-icon-uncheck", "css:finder"]
      ],
      "value": ""
    }, {
      "id": "b04c34de-2e4c-4621-923b-4dd89356e226",
      "comment": "",
      "command": "click",
      "target": "id=item-2",
      "targets": [
        ["id=item-2", "id"],
        ["css=.show #item-2", "css:finder"],
        ["xpath=//li[@id='item-2']", "xpath:attributes"],
        ["xpath=//div[@id='app']/div/div/div[2]/div/div/div/div/div/ul/li[3]", "xpath:idRelative"],
        ["xpath=//li[3]", "xpath:position"],
        ["xpath=//li[contains(.,'Radio Button')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "051567dd-0da0-4140-af2f-900118015fe6",
      "comment": "",
      "command": "click",
      "target": "css=.custom-control:nth-child(3) > .custom-control-label",
      "targets": [
        ["css=.custom-control:nth-child(3) > .custom-control-label", "css:finder"],
        ["xpath=//div[@id='app']/div/div/div[2]/div[2]/div[2]/div[3]/label", "xpath:idRelative"],
        ["xpath=//div[3]/label", "xpath:position"],
        ["xpath=//label[contains(.,'Impressive')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "13d2b2ad-9278-4038-9b14-2dae31ff81fe",
      "comment": "",
      "command": "click",
      "target": "css=.custom-control:nth-child(2) > .custom-control-label",
      "targets": [
        ["css=.custom-control:nth-child(2) > .custom-control-label", "css:finder"],
        ["xpath=//div[@id='app']/div/div/div[2]/div[2]/div[2]/div[2]/label", "xpath:idRelative"],
        ["xpath=//label", "xpath:position"],
        ["xpath=//label[contains(.,'Yes')]", "xpath:innerText"]
      ],
      "value": ""
    }]
  }],
  "suites": [{
    "id": "51a6dcdb-8519-482d-9635-b11e9477dda0",
    "name": "Default Suite",
    "persistSession": false,
    "parallel": false,
    "timeout": 300,
    "tests": ["4442e154-ded0-4f9f-8762-6f8ae97ee605"]
  }],
  "urls": ["https://demoqa.com/"],
  "plugins": []
}
