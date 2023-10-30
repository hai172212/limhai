<!doctype html>
<html>
<head>
    <meta name="viewport" content="width=device-width"/>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <title>Simple Transactional Email</title>
</head>
<body>
<div
        style="
          background-color: #f3f5f9;
          color: #383f50;
          font-family: sans-serif;
          font-size: 14px;
          line-height: 1.4;
          margin: 0;
          padding: 0;
        "
>
    <table
            border="0"
            cellpadding="0"
            cellspacing="0"
            style="border-collapse: separate"
            bgcolor="#f3f5f9"
            width="100%"
    >
        <tbody>
        <tr>
            <td style="font-family: sans-serif; font-size: 14px" valign="top">
                &nbsp;
            </td>
            <td
                    style="
                  display: block;
                  font-family: sans-serif;
                  font-size: 14px;
                  margin: 0 auto !important;
                  max-width: 580px;
                  padding: 10px;
                "
                    width="580"
                    valign="top"
            >
                <div
                        style="
                    box-sizing: border-box;
                    display: block;
                    margin: 0 auto;
                    max-width: 580px;
                    padding: 10px;
                  "
                >
                    <table
                            border="0"
                            cellpadding="0"
                            cellspacing="0"
                            style="
                      background: #fff;
                      border-collapse: separate;
                      border-radius: 3px;
                    "
                            width="100%"
                    >
                        <tbody>
                        <tr>
                            <td
                                    style="
                            border-radius: 3px 3px 0 0;
                            color: #fff;
                            font-family: sans-serif;
                            font-size: 16px;
                            font-weight: 500;
                            line-height: 0;
                            padding: 30px;
                          "
                                    bgcolor="#ebebec"
                                    valign="top"
                                    align="center"
                            >
                                <img
                                        src="https://surveybox-ui-git-dev-surveybox.vercel.app/surveybox-logo.png"
                                        alt="SurveyBox"
                                        width="100"
                                        height="90"
                                        style="border: none; max-width: 100%"
                                        class="CToWUd a6T"
                                        data-bit="iit"
                                        tabindex="0"
                                />
                                <div
                                        style="opacity: 0.01; left: 599.487px; top: 51px"
                                >
                                    <div
                                            role="button"
                                            tabindex="0"
                                            aria-label="Download attachment "
                                            jslog="91252; u014N:cOuCgd,Kr2w4b,xr6bB; 4:WyIjbXNnLWY6MTc2Njk2OTc4MTAwNTAwMTYyNSIsbnVsbCxbXV0."
                                            data-tooltip-class="a1V"
                                            data-tooltip="Download"
                                    >

                                    </div>
                                </div>
                            </td>
                        </tr>
                        <tr>
                            <td
                                    style="
                            box-sizing: border-box;
                            font-family: sans-serif;
                            font-size: 14px;
                            padding: 40px;
                          "
                                    valign="top"
                            >
                                <table
                                        border="0"
                                        cellpadding="0"
                                        cellspacing="0"
                                        style="border-collapse: separate"
                                        width="100%"
                                >
                                    <tbody>
                                    <tr>
                                        <td
                                                style="
                                    font-family: sans-serif;
                                    font-size: 14px;
                                  "
                                                valign="top"
                                        >
                                            <p
                                                    style="
                                      font-family: sans-serif;
                                      font-size: 18px;
                                      font-weight: bold;
                                      margin: 0;
                                      margin-bottom: 15px;
                                    "
                                            >
                                                Hello <span th:text="${data.firstName}"></span> &nbsp; <span
                                                    th:text="${data.lastName}"></span>
                                            </p>
                                            <p
                                                    style="
                                      font-family: sans-serif;
                                      font-size: 14px;
                                      font-weight: normal;
                                      margin: 0;
                                      margin-bottom: 15px;
                                    "
                                            >
                                                You've entered
                                                <strong
                                                ><a
                                                        th:text="${data.email}"
                                                        href="#"
                                                        target="_blank"
                                                >Email</a
                                                ></strong
                                                >
                                                as the contact email address for
                                                SurveyBox. Help us secure your account by
                                                verifying this address. Just click the
                                                button below and sign in using your
                                                SurveyBox password.
                                            </p>
                                        </td>
                                    </tr>
                                    <tr>
                                        <td
                                                style="
                                    font-family: sans-serif;
                                    font-size: 14px;
                                  "
                                                valign="top"
                                        >
                                            <table
                                                    class="m_2844503864481953822btn-primary"
                                                    border="0"
                                                    cellpadding="0"
                                                    cellspacing="0"
                                                    style="
                                      border-collapse: separate;
                                      box-sizing: border-box;
                                    "
                                                    width="100%"
                                            >
                                                <tbody>
                                                <tr>
                                                    <td
                                                            align="center"
                                                            style="
                                            font-family: sans-serif;
                                            font-size: 14px;
                                            padding-bottom: 15px;
                                          "
                                                            valign="top"
                                                    >
                                                        <table
                                                                border="0"
                                                                cellpadding="0"
                                                                cellspacing="0"
                                                                style="border-collapse: separate"
                                                                width="auto"
                                                        >
                                                            <tbody>
                                                            <tr>
                                                                <td
                                                                        style="
                                                    border-radius: 5px;
                                                    font-family: sans-serif;
                                                    font-size: 14px;
                                                  "
                                                                        bgcolor="#5bc84d"
                                                                        valign="top"
                                                                        align="center"
                                                                >
                                                                    <a
                                                                            title="Verify your email address"
                                                                            style="
                                                      background-color: #005dc5;
                                                      border: 1px solid #005dc5;
                                                      border-radius: 5px;
                                                      box-sizing: border-box;
                                                      color: #fff;
                                                      display: inline-block;
                                                      font-size: 14px;
                                                      font-weight: bold;
                                                      margin: 0;
                                                      padding: 12px 25px;
                                                      text-decoration: none;
                                                      text-transform: capitalize;
                                                    "
                                                                            th:href="@{${urlVerify}}"
                                                                            target="_blank"
                                                                    >Verify</a
                                                                    >
                                                                </td>
                                                            </tr>
                                                            </tbody>
                                                        </table>
                                                    </td>
                                                </tr>
                                                </tbody>
                                            </table>
                                        </td>
                                    </tr>
                                    <tr>
                                        <td
                                                style="
                                    font-family: sans-serif;
                                    font-size: 14px;
                                  "
                                                valign="top"
                                        >
                                            <p
                                                    style="
                                      color: #97a1b7;
                                      font-family: sans-serif;
                                      font-size: 12px;
                                      font-weight: normal;
                                      line-height: 1.2;
                                      margin: 0;
                                      margin-bottom: 15px;
                                    "
                                            >
                                                You’re receiving this email because you
                                                recently created a new SurveyBox account
                                                or updated your email address. If this
                                                wasn’t you, please ignore this email. Button
                                                not working? Copy the link below and paste
                                                it into your browser:
                                                <strong
                                                ><a
                                                        th:href="@{${urlVerify}}"
                                                        target="_blank"
                                                        th:data-saferedirecturl="@{${urlVerify}}"
                                                        th:text="${urlVerify}"
                                                >Url verify</a
                                                ></strong
                                                >
                                            </p>
                                        </td>
                                    </tr>
                                    </tbody>
                                </table>
                            </td>
                        </tr>
                        </tbody>
                    </table>
                    <div
                            style="
                      clear: both;
                      padding-top: 20px;
                      text-align: center;
                      width: 100%;
                    "
                    >
                        <table
                                border="0"
                                cellpadding="0"
                                cellspacing="0"
                                style="border-collapse: separate"
                                width="100%"
                        >
                            <tbody>
                            <tr>
                                <td
                                        style="
                              color: #999;
                              font-family: sans-serif;
                              font-size: 12px;
                            "
                                        valign="top"
                                        align="center"
                                >
                                    <p
                                            style="
                                color: #999;
                                font-family: sans-serif;
                                font-size: 12px;
                                font-weight: normal;
                                margin: 0;
                                margin-bottom: 15px;
                                text-align: center;
                              "
                                    >
                                        Please do not reply to this message; it was sent
                                        from an unmonitored email address. This message is
                                        a service email from SurveyBox. For questions
                                        or technical assistance please contact us at
                                        <a
                                                href=""
                                                style="
                                  color: #999;
                                  font-size: 12px;
                                  text-align: center;
                                  text-decoration: underline;
                                "
                                                target="_blank"
                                        >support@surveybox.com</a>.
                                    </p>
                                    <p
                                            style="
                                color: #999;
                                font-family: sans-serif;
                                font-size: 12px;
                                font-weight: normal;
                                margin: 0;
                                margin-bottom: 15px;
                                text-align: center;
                              "
                                    >
                                        © 2023 SurveyBox | . All rights reserved.
                                    </p>
                                </td>
                            </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </td>
            <td style="font-family: sans-serif; font-size: 14px" valign="top">
                &nbsp;
            </td>
        </tr>
        </tbody>
    </table>
</div>
</body>
</html>
