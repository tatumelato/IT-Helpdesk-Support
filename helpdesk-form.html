<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 600px;
            margin: 20px auto;
            padding: 20px;
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
            color: white;
            min-height: 100vh;
        }
        .form-container {
            background: linear-gradient(135deg, #2b5876 0%, #4e4376 100%);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.3);
            border: 1px solid rgba(255,255,255,0.1);
        }
        h1 {
            color: white;
            text-align: center;
            margin-bottom: 30px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        .form-group {
            margin-bottom: 20px;
        }
        label {
            display: block;
            margin-bottom: 8px;
            color: white;
            font-weight: bold;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.2);
        }
        input[type="text"],
        input[type="email"],
        select,
        textarea {
            width: 100%;
            padding: 12px;
            border: 2px solid rgba(255,255,255,0.2);
            border-radius: 8px;
            box-sizing: border-box;
            background: rgba(255,255,255,0.9);
            font-size: 14px;
            transition: all 0.3s ease;
        }
        input[type="text"]:focus,
        input[type="email"]:focus,
        select:focus,
        textarea:focus {
            outline: none;
            border-color: #4a90e2;
            box-shadow: 0 0 10px rgba(74,144,226,0.5);
        }
        textarea {
            height: 120px;
            resize: vertical;
        }
        button {
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 1px;
            position: relative;
            transform-style: preserve-3d;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
            box-shadow: 0 6px 0 #132347,
                       0 8px 10px rgba(0,0,0,0.3);
        }
        button:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 0 #132347,
                       0 12px 15px rgba(0,0,0,0.3);
        }
        button:active {
            transform: translateY(4px);
            box-shadow: 0 2px 0 #132347,
                       0 4px 5px rgba(0,0,0,0.3);
        }
        .request-info {
            background: rgba(255,255,255,0.1);
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 20px;
            display: flex;
            justify-content: space-between;
            border: 1px solid rgba(255,255,255,0.2);
        }
        .request-info span {
            font-size: 14px;
        }
        .severity-high {
            color: #ff4444;
            font-weight: bold;
        }
        .severity-medium {
            color: #ffbb33;
            font-weight: bold;
        }
        .severity-low {
            color: #00C851;
            font-weight: bold;
        }
        select option {
            background-color: white;
            color: #333;
        }
        .contact-selection {
            margin-top: 15px;
            display: none;
        }
        .contact-selection.visible {
            display: block;
        }
    </style>
</head>
<body>
    <div class="form-container">
        <h1>Mapetla Car Wash Help Desk</h1>
        <div class="request-info">
            <span>Request #: <strong id="requestNumber"></strong></span>
            <span>Time: <strong id="requestTime"></strong></span>
        </div>
        <form id="helpDeskForm" onsubmit="submitForm(event)">
            <div class="form-group">
                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name" required>
            </div>

            <div class="form-group">
                <label for="email">Email Address:</label>
                <input type="email" id="email" name="email" required>
            </div>

            <div class="form-group">
                <label for="phone">Phone Number:</label>
                <input type="text" id="phone" name="phone" required>
            </div>

            <div class="form-group">
                <label for="requestType">Request Type:</label>
                <select id="requestType" name="requestType" required onchange="toggleContactSelection()">
                    <option value="">Select Request Type</option>
                    <option value="it">IT Support (Tatu)</option>
                    <option value="other">Other Matters</option>
                </select>
            </div>

            <div id="contactSelection" class="form-group contact-selection">
                <label for="contact">Select Contact Person:</label>
                <select id="contact" name="contact" required>
                    <option value="">Select Contact Person</option>
                    <option value="euphorea">EuphoRea</option>
                    <option value="tomford">Tomford</option>
                </select>
            </div>

            <div class="form-group">
                <label for="severity">Severity Level:</label>
                <select id="severity" name="severity" required>
                    <option value="">Select Severity</option>
                    <option value="high" class="severity-high">High - Urgent attention needed</option>
                    <option value="medium" class="severity-medium">Medium - Important but not urgent</option>
                    <option value="low" class="severity-low">Low - General inquiry</option>
                </select>
            </div>

            <div class="form-group">
                <label for="description">Description of Issue:</label>
                <textarea id="description" name="description" required></textarea>
            </div>

            <button type="submit">Submit Request</button>
        </form>
    </div>

    <script>
        // Generate request number and set current time on page load
        window.onload = function() {
            // Generate random request number (Year + Random 4 digits)
            const year = new Date().getFullYear();
            const random = Math.floor(1000 + Math.random() * 9000);
            document.getElementById('requestNumber').textContent = `${year}-${random}`;
            
            // Set current time
            updateTime();
            // Update time every second
            setInterval(updateTime, 1000);
        }

        function updateTime() {
            const now = new Date();
            const timeString = now.toLocaleTimeString();
            const dateString = now.toLocaleDateString();
            document.getElementById('requestTime').textContent = `${dateString} ${timeString}`;
        }

        function toggleContactSelection() {
            const requestType = document.getElementById('requestType').value;
            const contactSelection = document.getElementById('contactSelection');
            const contactSelect = document.getElementById('contact');
            
            if (requestType === 'other') {
                contactSelection.classList.add('visible');
                contactSelect.required = true;
            } else {
                contactSelection.classList.remove('visible');
                contactSelect.required = false;
            }
        }

        function submitForm(event) {
            event.preventDefault();
            
            const requestNumber = document.getElementById('requestNumber').textContent;
            const requestTime = document.getElementById('requestTime').textContent;
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const phone = document.getElementById('phone').value;
            const requestType = document.getElementById('requestType').value;
            const severity = document.getElementById('severity').value;
            const description = document.getElementById('description').value;

            let whatsappNumber;
            let supportName;

            if (requestType === 'it') {
                whatsappNumber = '+27732296540';
                supportName = 'Tatu';
            } else {
                const contact = document.getElementById('contact').value;
                if (contact === 'euphorea') {
                    whatsappNumber = '+27733214017';
                    supportName = 'EuphoRea';
                } else if (contact === 'tomford') {
                    whatsappNumber = '+27834359005';
                    supportName = 'Tomford';
                }
            }

            const message = `Help Desk Request #${requestNumber}\nSubmitted: ${requestTime}\n\nFor: ${supportName}\nFrom: ${name}\nEmail: ${email}\nPhone: ${phone}\nSeverity: ${severity}\n\nIssue Description:\n${description}`;

            const whatsappUrl = `https://wa.me/${whatsappNumber}?text=${encodeURIComponent(message)}`;
            window.open(whatsappUrl, '_blank');

            // Reset form after submission
            document.getElementById('helpDeskForm').reset();
            // Generate new request number
            const year = new Date().getFullYear();
            const random = Math.floor(1000 + Math.random() * 9000);
            document.getElementById('requestNumber').textContent = `${year}-${random}`;
            
            // Hide contact selection after reset
            document.getElementById('contactSelection').classList.remove('visible');
            
            alert('Your request has been submitted. You will be redirected to WhatsApp to send your message.');
        }
    </script>
</body>
</html>
