Copyright (C) 2012-2014 by BIPS

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

About
=====
+ Bitcoin payments via BIPS for PrestaShop.
+ Version 0.4

System Requirements
===================
+ BIPS API, Merchant Secret
+ Curl PHP Extension
+ JSON Encode
  
Configuration Instructions
==========================
    1. Upload files to your PrestaShop installation.
    2. Go to your PrestaShop administration Modules list.
    3. Click on Payments and Gateways in the Categories list, find BIPS and click [Install] 
    4. In module settings "Invoice API key" <- set your BIPS Invoice API key.
    5. In module settings "IPN secret" <- set your BIPS Instant Payment Notification secret.

### Tested with:

+ PrestaShop™ 1.6.0.6