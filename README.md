
<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Morningness-Eveningness Questionnaire (MEQ)</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 0;
            background-color: #eee6ed;
            color: #333;
        }
        h1 {
            text-align: center;
            color: #ee7623;
        }
        .question {
            margin-bottom: 20px;
        }
        .answers {
            margin-left: 20px;
        }
        .answers label {
            display: block;
        }
        #result {
            margin-top: 20px;
            padding: 15px;
            border: 1px solid #984a12;
            border-radius: 5px;
            background-color: white;
            color: #ffc69d;
        }
        button {
            display: block;
            margin: 20px auto;
            padding: 10px 20px;
            background-color: #ee7623;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #91440d;
        }
    </style>
</head>
<body>
    <h1>Morningness-Eveningness Questionnaire (MEQ)</h1>
    <form id="meq-form">
        
        <div class="question">
            <p><b>1. Ажлын өдрүүд эсвэл хичээлийн өдрүүдэд хэдэн цагт босдог вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q1" value="5"> 6 цагаас өмнө  </label>
                <label><input type="radio" name="q1" value="4"> 6:00 – 6:59    </label>
                <label><input type="radio" name="q1" value="3"> 7:00 – 7:59    </label>
                <label><input type="radio" name="q1" value="2"> 8:00 – 8:59    </label>
                <label><input type="radio" name="q1" value="1"> 9 цагаас хойш  </label>
            </div>
        </div>
       
        <div class="question">
            <p><b>2. Амралтын өдрүүдэд эсвэл чөлөөт өдрүүдэд хэдэн цагт босдог вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q2" value="5"> 6 цагаас өмнө  </label>
                <label><input type="radio" name="q2" value="4"> 6:00 – 6:59    </label>
                <label><input type="radio" name="q2" value="3"> 7:00 – 7:59    </label>
                <label><input type="radio" name="q2" value="2"> 8:00 – 8:59    </label>
                <label><input type="radio" name="q2" value="1"> 9 цагаас хойш  </label>
              </div>
        </div>

        <div class="question">
            <p><b>3. Ажлын өдрүүд эсвэл хичээлийн өдрүүдэд хэдэн цагт унтдаг вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q3" value="5"> 21 цагаас өмнө     </label>
                <label><input type="radio" name="q3" value="4"> 21:00 – 21:59      </label>
                <label><input type="radio" name="q3" value="3"> 22:00 – 22:59      </label>
                <label><input type="radio" name="q3" value="2"> 23:00 – 23:59     </label>
                <label><input type="radio" name="q3" value="1"> Шөнө дундаас хойш  </label>
              </div>
        </div>

        <div class="question">
            <p><b>4. Амралтын өдрүүдэд эсвэл чөлөөт өдрүүдэд хэдэн цагт унтдаг вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q4" value="5"> 21 цагаас өмнө     </label>
                <label><input type="radio" name="q4" value="4"> 21:00 – 21:59      </label>
                <label><input type="radio" name="q4" value="3"> 22:00 – 22:59     </label>
                <label><input type="radio" name="q4" value="2"> 23:00 – 23:59      </label>
                <label><input type="radio" name="q4" value="1"> Шөнө дундаас хойш  </label>
              </div>
        </div>

        <div class="question">
            <p><b>5. Өглөө сэрэхэд танд хэр амар байдаг вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q5" value="5"> Маш амархан        </label>
                <label><input type="radio" name="q5" value="4"> Харьцангуй амархан </label>
                <label><input type="radio" name="q5" value="3"> Тийм ч амархан биш </label>
                <label><input type="radio" name="q5" value="2"> Огт амаргүй        </label>
                <label><input type="radio" name="q5" value="1"> Маш хэцүү          </label>
              </div>
        </div>

        <div class="question">
            <p><b>6. Амралтын өдрүүдэд өглөө сэрэхэд хэр амар байдаг вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q6" value="5"> Маш амархан        </label>
                <label><input type="radio" name="q6" value="4"> Харьцангуй амархан </label>
                <label><input type="radio" name="q6" value="3"> Тийм ч амархан биш </label>
                <label><input type="radio" name="q6" value="2"> Огт амаргүй        </label>
                <label><input type="radio" name="q6" value="1"> Маш хэцүү          </label>
              </div>
        </div>

        <div class="question">
            <p><b>7. Өглөө 6 цагаас өмнө босох талаар танд ямар сэтгэгдэл төрдөг вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q7" value="5"> Маш их дуртай      </label>
                <label><input type="radio" name="q7" value="4"> Маш амархан        </label>
                <label><input type="radio" name="q7" value="3"> Харьцангуй амархан </label>
                <label><input type="radio" name="q7" value="2"> Бага зэрэг хэцүү  </label>
                <label><input type="radio" name="q7" value="1"> Маш хэцүү          </label>
              </div>
        </div>

        <div class="question">
            <p><b>8. Шөнө дундаас хойш сэрүүн байх талаар таны бодол?</b></p>
            <div class="answers">
                <label><input type="radio" name="q8" value="5"> Маш их дуртай      </label>
                <label><input type="radio" name="q8" value="4"> Маш амархан       </label>
                <label><input type="radio" name="q8" value="3"> Харьцангуй амархан </label>
                <label><input type="radio" name="q8" value="2"> Бага зэрэг хэцүү   </label>
                <label><input type="radio" name="q8" value="1"> Маш хэцүү          </label>
              </div>
        </div>

        <div class="question">
            <p><b>9. Хэзээ таны оюун ухаан хамгийн сайн ажилладаг вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q9" value="5"> Өглөө эрт (05:00 – 09:00) </label>
                <label><input type="radio" name="q9" value="4"> Өглөө (09:00 – 12:00)     </label>
                <label><input type="radio" name="q9" value="3"> Үд дунд (12:00 – 18:00)   </label>
                <label><input type="radio" name="q9" value="2"> Орой (18:00 – 21:00)      </label>
                <label><input type="radio" name="q9" value="1"> Шөнө орой (21:00 – 00:00) </label>
              </div>
        </div>

        <div class="question">
            <p><b>10. Хэзээ таны бие хамгийн эрч хүчтэй байдаг вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q10" value="5"> Өглөө эрт (05:00 – 09:00) </label>
                <label><input type="radio" name="q10" value="4"> Өглөө (09:00 – 12:00)    </label>
                <label><input type="radio" name="q10" value="3"> Үд дунд (12:00 – 18:00)   </label>
                <label><input type="radio" name="q10" value="2"> Орой (18:00 – 21:00)      </label>
                <label><input type="radio" name="q10" value="1"> Шөнө орой (21:00 – 00:00) </label>
              </div>
        </div>

        <div class="question">
            <p><b>11. Өдрийн аль цагт таны нойр хамгийн их хүрдэг вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q11" value="5"> Орой (21:00 - 00:00)         </label>
                <label><input type="radio" name="q11" value="4"> Оройн цагаар (18:00 - 21:00) </label>
                <label><input type="radio" name="q11" value="3"> Үдээс хойш (12:00 - 18:00)  </label>
                <label><input type="radio" name="q11" value="2"> Өглөө (09:00 - 12:00)       </label>
                <label><input type="radio" name="q11" value="1"> Өглөө эрт (05:00 - 09:00)  </label>
              </div>
        </div>

        <div class="question">
            <p><b>12. Өглөө (09:00-өөс өмнө) та хэр сэргэлэн байдаг вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q12" value="5"> Маш сэргэг  </label>
                <label><input type="radio" name="q12" value="4"> Харьцангуй сэргэг</label>
                <label><input type="radio" name="q12" value="3"> Тийм ч сэргэг биш </label>
                <label><input type="radio" name="q12" value="2"> Огт сэргэг биш   </label>
                <label><input type="radio" name="q12" value="1"> Маш их нойрмог    </label>
              </div>
        </div>

        <div class="question">
            <p><b>13. Үдээс хойш (12:00 - 18:00)та хэр сэргэлэн байдаг вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q13" value="5"> Маш сэргэг       </label>
                <label><input type="radio" name="q13" value="4"> Харьцангуй сэргэг </label>
                <label><input type="radio" name="q13" value="3"> Тийм ч сэргэг биш </label>
                <label><input type="radio" name="q13" value="2"> Огт сэргэг биш    </label>
                <label><input type="radio" name="q13" value="1"> Маш их нойрмог     </label>
              </div>
        </div>

        <div class="question">
            <p><b>14. Орой (18:00 - 00:00)та хэр сэргэлэн байдаг вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q14" value="5"> Маш сэргэг        </label>
                <label><input type="radio" name="q14" value="4"> Харьцангуй сэргэг </label>
                <label><input type="radio" name="q14" value="3"> Тийм ч сэргэг биш </label>
                <label><input type="radio" name="q14" value="2"> Огт сэргэг биш    </label>
                <label><input type="radio" name="q14" value="1"> Маш их нойрмог      </label>
              </div>
        </div>

        <div class="question">
            <p><b>15. Шөнө дунд (00:00-с хойш) та хэр сэргэлэн байдаг вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q15" value="5"> Маш сэргэг        </label>
                <label><input type="radio" name="q15" value="4"> Харьцангуй сэргэг</label>
                <label><input type="radio" name="q15" value="3"> Тийм ч сэргэг биш </label>
                <label><input type="radio" name="q15" value="2"> Огт сэргэг биш    </label>
                <label><input type="radio" name="q15" value="1"> Маш их нойрмог      </label>
              </div>
        </div>

        <div class="question">
            <p><b>16. Өглөөний үйл ажиллагаанд (09:00-өөс өмнө) хэр их дуртай вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q16" value="5"> Маш их        </label>
                <label><input type="radio" name="q16" value="4"> Нэлээд дуртай  </label>
                <label><input type="radio" name="q16" value="3"> Жаахан дуртай   </label>
                <label><input type="radio" name="q16" value="2"> Тийм ч их биш   </label>
                <label><input type="radio" name="q16" value="1"> Огт дуртай биш  </label>
              </div>
        </div>

        <div class="question">
            <p><b>17. Оройн үйл ажиллагаанд (18:00 - 00:00) хэр их дуртай вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q17" value="5"> Маш их         </label>
                <label><input type="radio" name="q17" value="4"> Нэлээд дуртай   </label>
                <label><input type="radio" name="q17" value="3"> Жаахан дуртай  </label>
                <label><input type="radio" name="q17" value="2"> Тийм ч их биш  </label>
                <label><input type="radio" name="q17" value="1"> Огт дуртай биш</label>
              </div>
        </div>

        <div class="question">
            <p><b>18. Та ямар цагт дасгал хөдөлгөөн хийхийг илүүд үздэг вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q18" value="5"> Өглөө эрт (05:00 - 09:00)  </label>
                <label><input type="radio" name="q18" value="4"> Өглөө (09:00 - 12:00)      </label>
                <label><input type="radio" name="q18" value="3"> Үдээс хойш (12:00 - 18:00) </label>
                <label><input type="radio" name="q18" value="2"> Орой (18:00 - 21:00)       </label>
                <label><input type="radio" name="q18" value="1"> Шөнө дунд (21:00 - 00:00)  </label>
              </div>
        </div>

        <div class="question">
            <p><b>19. Та гол хоолоо ямар цагт идэх дуртай вэ?</b></p>
            <div class="answers">
                <label><input type="radio" name="q19" value="5"> Өглөө эрт (05:00 - 09:00) </label>
                <label><input type="radio" name="q19" value="4"> Өглөө (09:00 - 12:00)      </label>
                <label><input type="radio" name="q19" value="3"> Үдээс хойш (12:00 - 18:00) </label>
                <label><input type="radio" name="q19" value="2"> Орой (18:00 - 21:00)       </label>
                <label><input type="radio" name="q19" value="1"> Шөнө дунд (21:00 - 00:00)  </label>
              </div>
        </div>

        <button type="button" onclick="calculateScore()">Submit</button>
    </form>
    <div id="result" style="display: none;"></div>

    <script>

const questions = document.querySelectorAll('.question');

questions.forEach((question, index) => {
    const inputs = question.querySelectorAll('input[type="radio"]');
    inputs.forEach(input => {
        input.addEventListener('change', () => {
            if (index + 1 < questions.length) {
                questions[index + 1].scrollIntoView({ behavior: 'smooth' });
            }
        });
    });
});
function calculateScore() {
        let totalScore = 0;
        const form = document.getElementById('meq-form');
        const questions = form.querySelectorAll('.question');
        let allAnswered = true;

        questions.forEach((question) => {
            const answer = question.querySelector('input[type="radio"]:checked');
            if (answer) {
                totalScore += parseInt(answer.value, 10);
            } else {
                allAnswered = false;
            }
        });

        const resultDiv = document.getElementById('result');
        if (!allAnswered) {
            resultDiv.style.display = 'block';
            resultDiv.style.color = 'red';
            resultDiv.innerText = 'Бүх асуултанд хариулна уу.';
        } else {
            resultDiv.style.display = 'block';
            resultDiv.style.color = '#00509e';

            if (totalScore > 60) {
                resultDiv.innerHTML = `Үр дүн: ${totalScore}. <b>Та бол "Өглөөний хүн".</b><br>Та өглөөг эрч хүчтэй, бүтээлч өнгөрөөдөг.`;
            } else if (totalScore <= 60 && totalScore >= 30) {
                resultDiv.innerHTML = `Үр дүн: ${totalScore}. <b>Та өглөө, орой аль алинд нь зохицож чаддаг.</b>`;
            } else  if (totalScore < 30) {
                resultDiv.innerHTML = `Үр дүн: ${totalScore}. <b>Та бол "Шөнийн хүн".</b><br>Та шөнийн цагаар илүү үр бүтээлтэй байдаг.`;
            }
        }
    }
    </script>
</body>
</html>
