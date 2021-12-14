# Print Slip Report

<img src="https://github.com/SydneyUniLibrary/print-slip-report/wiki/images/anzreghackathon2021-peopleschoiceaward.png" width="200" align="right">
An Ex Libris Cloud App alternative to Alma's built-in print slip report.

This an attempt to make an Cloud App solution for the idea to [allow configuration of which columns are in the the Print Slip Report](https://ideas.exlibrisgroup.com/forums/308173-alma/suggestions/12375144-allow-configuration-of-which-columns-are-in-the-th) that was posted on Idea Exchange.

This app was developed as part of the [ANZREG](https://anzreg.igelu.org/) 2021 Cloud Apps hackathon.

## Note on the origin of this cloudapp

The code of this Cloudapp has been transferred to this repository in consultation with the original developers. The original code comes from the following repository: https://github.com/SydneyUniLibrary/print-slip-report
Further development and maintenance will happen in this repository.

## Help
The Print Slip Report app is equivalent to printing the slip report within Fulfilment > Pick Form Shelf on Alma Pick Up Requested Resources screen. But with this app on the columns you select will print. No more downloading the report into Excel and hiding columns!

### Getting started

1. Sign into Alma. You can choose a location if you want.
1. Click on the Cloud App Center icon in the top-right of your Alma screen.
1. Click the magnifying class icon next to Available Apps.
1. Type in Print Slip Report.
1. Click on Print Slip Report's tile.
1. Click the Install button.

### Printing the slip report

1. Sign into Alma. You can choose a location if you want.
1. Click on the Cloud App Center icon in the top-right of your Alma screen.
1. Under installed apps click Print Slip Report's tile.
1. Under library code, enter the code for your library.
1. Under circulation desk code, enter the code for your circulation desk.
1. Click on the columns you want to print. The columns with the checkmarks will be included in the print. The columns with empty boxes will be hidden.
1. Click the print button.
1. A window will pop up and after a moment the print slip report will appear.
1. Type ⌘P on macOS and Ctrl+P on Windows.
1. Change the print options as you need.
1. Click the print button.

### Troubleshooting
**I don't see the Cloud App Center icon**<br>
Cloud Apps have not been enabled for your Alma. Contact your Alma administrator to have Cloud Apps enabled.

**I don't find Print Slip Report under Installed Apps.**<br>
Install the app by following the steps under the heading "Getting started".

**I don't find Print Slip Report when I search for it**<br>
Your Alma administrator has selected which apps are available to you. Contact your Alma administrator to have the Print Slip Report app made available in your Alma.

**The popup window disappears and I see a message about not being authorised.**<br>
Your Alma user needs a circulation desk operator role. Contact your Alma administrator about your Alma roles.

Currently having just a requests operator role doesn't work. This is will be fixed in the June release of Alma.

**The popup window disappears and I see a message about valid library codes.**<br>
If you entered the name of your library, you need to enter its code instead. The message has the codes your libraries. If you don't know which code to use, contact your Alma administrator.

**The popup window disappears and I see a message about valid circulation desk codes.**<br>
If you entered the name of the circulation desk, you need to enter its code instead. The message has the codes for the circulation desks at your library. If you don't know which code to use, contact your Alma administrator.

**Requests I've already printed and appearing again**<br>
The app doesn't mark requests as having been printed. Alma will remove them from the print when the request is actioned or marked missing.

**I used the facets and selections to the Pick Up Requested Resources screen, but all the requests printed**<br>
The app doesn't use the Pick Up Requested Resource screen. It always prints all of the requested resources that need to be picked up for the your library and circulation desk.

**Not all of the column I selected are in the print**<br>
You selected too many columns to fit on the page. Try printing in landscape instead of portrait, or select fewer columns.


## License

Copyright 2021 Amy Leong, Jim Nicholls, Cattleya Tantri, Lani Valentine

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
