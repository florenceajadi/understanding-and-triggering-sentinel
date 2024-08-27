<h4>Understanding and Triggering Sentinel</h4>

<p>
  <img src="https://github.com/user-attachments/assets/beac9f4d-3882-4cf5-9113-faccb96c8bef" height="80%" width="80%" />
  <img src="https://github.com/user-attachments/assets/67bb06b1-fb36-450c-a87f-246cf697464e" height="80%" width="80%" />
   <img src="https://github.com/user-attachments/assets/240f8a2f-a155-41d0-849e-b2b97dc33999" height="80%" width="80%" />
</p>
<h5>Triggering Malware Outbreak</h5>
<p> This script generates files with the EICAR test string. The EICAR string is a test pattern used to check the functionality of antivirus software. When an antivirus program scans a file containing 
  this string, it detects a test virus. This is useful for testing the antivirus software's response to known threats without actually dealing with real malware. Since the value of $TOTAL_VIRUSES_TO_MAKE is set to 1 or 10,
  it will generate only one or ten file(s) named EICAR-0.txt. 
 </p>

  <p>
     <img src="https://github.com/user-attachments/assets/c3ce0f98-9cc9-4acc-9f7b-bebd1d3fbd6f" height="80%" width="80%" />
     <img src="https://github.com/user-attachments/assets/0098fcff-c5b4-4ac7-b344-30cb26b611ad" height="80%" width="80%" />
    <p>This query is used to retrieve and analyze specific events from the Windows Defender Operational log related to the completion of scans or specific tasks done by the Windows Defender. 
      By filtering and displaying EventID 1116 or 1117, it focuses on certiain events that's related to the Defender's result. </p>
  </p>
<p>
  <img src="https://github.com/user-attachments/assets/3ff77636-4057-4416-a009-733f2d879252" height="80%" width="80%" />
   <img src="https://github.com/user-attachments/assets/4581b795-18e2-45e9-85e3-b51736a8cfa8" height="80%" width="80%" />
</p>
<h5>Triggering Possible Privilege Escalation (AKV Critical Credential Retrieval or Update)</h5>
<p>Monitoring and identifying activities related to a specific pswd in AKV focusing on secret operations like SecretGet and SecretSet where secrets can be retrieved or updated. All while using Tenant-Global-Admin-Password to
filter those specific critical pswds. </p>
  <p>
 <img src="https://github.com/user-attachments/assets/0748ca54-e49b-4689-84f9-ebfc990dbfae" height="80%" width="80%" />
     <img src="https://github.com/user-attachments/assets/050f78a5-545e-49cf-86f3-756ea9789fb7" height="80%" width="80%" />
     <img src="https://github.com/user-attachments/assets/41becdac-933d-46f0-916e-6ada474e3e49" height="80%" width="80%" />
    <p>This retrieves and displays events from the Windows Firewall log that have EventID 2003. This hel;ps in monitoring firewall rule changes or configs in Windows, allowing admins to track modifications and making sure the firewall settings 
    are properly managed and secure.</p>
  </p>
   <p>
 <img src="https://github.com/user-attachments/assets/259da168-09de-4bdb-b844-01815da66d00" height="80%" width="80%" />
    <p>Able to analyze audit logs to find users who have had changes or resets 10 or more times. </p>
  </p>
