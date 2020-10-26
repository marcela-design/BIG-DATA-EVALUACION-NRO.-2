# BIG-DATA-EVALUACION-NRO.-2
    "Version": "2020-10-17",
    "Statement": [
        {
            "Sid": "VisualEditor0",
            "Effect": "Allow",
            "Action": [
                "logs:CreateLogStream",
                "logs:PutLogEvents",
		"logs:CreateLogGroup"
            ],
            "Resource": "*"
        },
        {
            "Sid": "VisualEditor1",
            "Effect": "Allow",
            "Action": [
		"Insumos_navideños:DescribeStream",
                "Insumos_navideños:GetShardIterator",
		"Insumos_navideños:GetRecords",
                "dynamodb:BatchWriteItem",
                "dynamodb:PutItem",
		"sns:Publish"
            ],
            "Resource": "*"
        }
    ]
}
