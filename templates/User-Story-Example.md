Story Title

Automatically Create Employee from HRIS Feed

Business Objective

Reduce manual employee creation by automatically creating new employees received from the HRIS daily employee feed.

Business Requirements

• System imports employee records every morning.
• New employees are automatically created.
• Existing employees are updated.
• Terminated employees become inactive.
• Duplicate employee IDs are rejected.

Business Rules

BR-001 Employee IDs must be unique.

BR-017 Only Active employees receive course assignments.

Acceptance Criteria

Given...

When...

Then...

Risks

• Duplicate HRIS IDs
• HRIS feed failure

Dependencies

• Daily CSV Feed
• HRIS FTP Server

Edge Cases

• Missing email
• Missing location
• Invalid job title

...