# aws-cheatsheet
A cheatsheet containing AWS CloudTrail events that can be used for Incident Response purposes or Detection Engineering. 
If you see room for improvements please let us know via an issue or create a pull request. 

| Initial Access | Execution | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery | Lateral Movement | Exfiltration | Impact |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ConsoleLogin | StartInstance | CreateAccessKey | CreateGroup | StopLogging | GetSecretValue | ListUsers | AssumeRole | CreateSnapShot | PutBucketVersioning |
| PasswordRecoveryRequested | StartInstances | CreateUser | CreateRole | DeleteTrail | GetPasswordData | ListRoles | SwitchRole | ModifySnapshotAttributes  | RunInstances |
| GetSigninToken | Invoke | CreateNetworkAclEntry | UpdateAccessKey | UpdateTrail | RequestCertificate | ListIdentities |  | ModifyImageAttribute | DeleteAccountPublicAccessBlock  |
|  | SendCommand | CreateRoute | PutGroupPolicy | PutEventSelectors | UpdateAssumeRolePolicy | ListAccessKeys |  | SharedSnapshotCopyInitiated |  |
|  |  | CreateLoginProfile | PutRolePolicy | DeleteFlowLogs |  | ListServiceQuotas |  | SharedSnapshotVolumeCreated |  |
|  |  | AuthorizeSecurityGroupEgress | PutUserPolicy | DeleteDetector |  | ListInstanceProfiles |  | ModifyDBSnapshotAttribute |  |
|  |  | AuthorizeSecurityGroupIngress | AddRoleToInstanceProfile | DeleteMembers |  | ListBuckets |  | PutBucketPolicy |  |
|  |  | CreateVirtualMFADevice | AddUserToGroup | DeleteSnapshot |  | ListGroups |  | PutBucketAcl |  |
|  |  | CreateConnection |  | DeactivateMFADevice |  | GetSendQuota |  |  |  |
|  |  | ApplySecurityGroupsToLoadBalancer |  | DeleteCertificate |  | GetCallerIdentity |  |  |  |
|  |  | SetSecurityGroups |  | DeleteConfigRule |  | DescribeInstances |  |  |  |
|  |  | AuthorizeDBSecurityGroupIngress |  | DeleteAccessKey |  | GetBucketAcl |  |  |  |
|  |  | CreateDBSecurityGroup |  | LeaveOrganization |  | GetBucketVersioning |  |  |  |
|  |  | ChangePassword |  | DisassociateFromMasterAccount |  | GetAccountAuthorizationDetails |  |  |  |
|  |  | SetDefaultPolicyVersion |  | DisassociateMembers |  |  |  |  |  |
|  |  |  |  | StopMonitoringMembers |  |  |  |  |  |
