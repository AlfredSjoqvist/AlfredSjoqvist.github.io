<!-- Top section / intro -->
<table style="width:100%;max-width:900px;border:0;border-spacing:0;border-collapse:separate;margin:0 auto;">
  <tr>
    <td style="padding:0;">
      <table style="width:100%;border:0;border-spacing:0;border-collapse:separate;margin:0 auto;">
        <tr>
          <!-- Text -->
          <td style="padding:2%;width:60%;vertical-align:middle;">
            <p style="font-size:32px;font-weight:700;text-align:center;margin:0 0 10px 0;">
              Alfred Sjöqvist
            </p>
            <p style="text-align:justify;margin:6px 0;">
              Computer engineering and cognitive science student, currently focusing on systems, AI, and secure vision pipelines.
              I like projects where hardware, algorithms, and user experience all meet.
            </p>
            <p style="text-align:justify;margin:6px 0;">
              Right now I’m especially interested in trustworthy ML, real-time systems, and making complex tools actually usable.
              Always happy to talk about projects, research, or collaborations.
            </p>
            <p style="text-align:center;margin-top:10px;">
              <a href="mailto:YOUR_EMAIL_HERE" target="_blank">Email</a> &nbsp;/&nbsp;
              <a href="https://www.linkedin.com/in/YOUR_LINKEDIN_HERE" target="_blank">LinkedIn</a> &nbsp;/&nbsp;
              <a href="https://github.com/AlfredSjoqvist" target="_blank">GitHub</a>
            </p>
          </td>

          <!-- Photo -->
          <td style="padding:2.5%;width:40%;max-width:40%;vertical-align:middle;text-align:center;">
            <!-- Replace with your actual headshot -->
            <img
              src="images/alfred-headshot.jpg"
              alt="Alfred Sjöqvist"
              style="width:85%;max-width:230px;border-radius:50%;object-fit:cover;"
            />
          </td>
        </tr>
      </table>

      <!-- Divider -->
      <hr style="border:none;height:0.8px;background-color:#222;width:95%;margin:20px auto 10px auto;" />

      <!-- Projects header -->
      <table style="width:100%;border:0;border-spacing:0;border-collapse:separate;margin:0 auto;">
        <tr>
          <td style="padding:10px 20px 0 20px;width:100%;vertical-align:bottom;">
            <h2 style="margin-bottom:5px;">Selected Projects</h2>
            <p style="margin-top:0;color:#555;">
              A few projects I am proud of. Most are work-in-progress and open to contributions.
            </p>
          </td>
        </tr>
      </table>

      <!-- Project list -->
      <table style="width:100%;border:0;border-spacing:0;border-collapse:separate;margin:0 auto;">
        <tbody>

          <!-- 1. Secure camera / vision systems project -->
          <tr>
            <td style="padding:20px;width:25%;vertical-align:middle;text-align:center;">
              <img
                src="images/secure-vision.png"
                alt="Secure Vision Systems"
                width="160"
                style="border-radius:8px;object-fit:cover;"
              />
            </td>
            <td style="padding:20px;width:75%;vertical-align:middle;">
              <a href="https://github.com/AlfredSjoqvist/secure-real-time-vision-systems" target="_blank">
                <span style="font-weight:600;font-size:18px;">
                  Secure Real-Time Vision Systems
                </span>
              </a>
              <br/>
              <span style="color:#666;font-size:14px;">
                Axis Communications · Bachelor thesis (confidential code, public write-up)
              </span>
              <p style="margin-top:8px;">
                Research project on processing and visualising multi-camera metadata in real time under strict
                security and privacy constraints. Explores secure data flows, timing guarantees, privacy-aware
                aggregation, and human-interpretable visual abstractions for surveillance environments.
              </p>
            </td>
          </tr>

          <!-- 2. Crypto forecasting -->
          <tr>
            <td style="padding:20px;width:25%;vertical-align:middle;text-align:center;">
              <img
                src="images/crypto-forecasting.png"
                alt="Crypto price forecasting"
                width="160"
                style="border-radius:8px;object-fit:cover;"
              />
            </td>
            <td style="padding:20px;width:75%;vertical-align:middle;">
              <a href="https://github.com/AlfredSjoqvist/crypto-price-forecasting" target="_blank">
                <span style="font-weight:600;font-size:18px;">
                  Crypto Price Forecasting with Deep Learning
                </span>
              </a>
              <p style="margin-top:8px;">
                End-to-end PyTorch pipeline for short-horizon Bitcoin prediction. Includes Binance data ingestion,
                technical indicators with <code>pandas_ta</code>, Kalman and wavelet denoising, GRU/LSTM models,
                and backtesting with PnL curves and baseline comparisons.
              </p>
            </td>
          </tr>

          <!-- 3. Autonomous racecar embedded -->
          <tr>
            <td style="padding:20px;width:25%;vertical-align:middle;text-align:center;">
              <img
                src="images/autonomous-racecar.png"
                alt="Autonomous racecar"
                width="160"
                style="border-radius:8px;object-fit:cover;"
              />
            </td>
            <td style="padding:20px;width:75%;vertical-align:middle;">
              <a href="https://github.com/AlfredSjoqvist/autonomous-racecar-embedded" target="_blank">
                <span style="font-weight:600;font-size:18px;">
                  Embedded Autonomous Racecar
                </span>
              </a>
              <p style="margin-top:8px;">
                Full-stack robotics project combining embedded C/C++, Rust, and Python to control a model racecar.
                Integrates LiDAR processing, mapping, and real-time control loops to drive autonomously through
                cone-based tracks.
              </p>
            </td>
          </tr>

          <!-- 4. FPGA CPU + Blackjack -->
          <tr>
            <td style="padding:20px;width:25%;vertical-align:middle;text-align:center;">
              <img
                src="images/fpga-blackjack.png"
                alt="FPGA Blackjack CPU"
                width="160"
                style="border-radius:8px;object-fit:cover;"
              />
            </td>
            <td style="padding:20px;width:75%;vertical-align:middle;">
              <a href="https://github.com/AlfredSjoqvist/fpga-microcoded-blackjack-cpu" target="_blank">
                <span style="font-weight:600;font-size:18px;">
                  Microcoded Blackjack CPU on FPGA
                </span>
              </a>
              <p style="margin-top:8px;">
                Custom microcoded processor in VHDL with a hand-rolled instruction set, assembler, and memory
                architecture. Demonstrated with a working Blackjack game running entirely on the FPGA.
              </p>
            </td>
          </tr>

          <!-- 5. Genealogy platform -->
          <tr>
            <td style="padding:20px;width:25%;vertical-align:middle;text-align:center;">
              <img
                src="images/traedet-genealogy.png"
                alt="Trädet genealogy platform"
                width="160"
                style="border-radius:8px;object-fit:cover;"
              />
            </td>
            <td style="padding:20px;width:75%;vertical-align:middle;">
              <a href="https://github.com/AlfredSjoqvist/traedet-genealogy-platform" target="_blank">
                <span style="font-weight:600;font-size:18px;">
                  Trädet: Accessible Genealogy Platform
                </span>
              </a>
              <p style="margin-top:8px;">
                Full-stack web app for visualising family trees and historical records, designed around Nielsen’s
                usability heuristics and accessibility principles. Built as part of a research project on usable
                genealogy interfaces.
              </p>
            </td>
          </tr>

          <!-- 6. CohSort NLP project -->
          <tr>
            <td style="padding:20px;width:25%;vertical-align:middle;text-align:center;">
              <img
                src="images/cohsort.png"
                alt="CohSort"
                width="160"
                style="border-radius:8px;object-fit:cover;"
              />
            </td>
            <td style="padding:20px;width:75%;vertical-align:middle;">
              <a href="https://github.com/AlfredSjoqvist/cohsort" target="_blank">
                <span style="font-weight:600;font-size:18px;">
                  CohSort: Cohesion-Aware Sentence Reordering
                </span>
              </a>
              <p style="margin-top:8px;">
                Research code for an NLP system that reorders sentences in news summaries using cohesion metrics
                built from LSA, SBERT embeddings, and simulated annealing, exploring how text structure affects
                readability.
              </p>
            </td>
          </tr>

          <!-- 7. Amazon sentiment analysis -->
          <tr>
            <td style="padding:20px;width:25%;vertical-align:middle;text-align:center;">
              <img
                src="images/amazon-sentiment.png"
                alt="Amazon sentiment analysis"
                width="160"
                style="border-radius:8px;object-fit:cover;"
              />
            </td>
            <td style="padding:20px;width:75%;vertical-align:middle;">
              <a href="https://github.com/AlfredSjoqvist/amazon-sentiment-analysis" target="_blank">
                <span style="font-weight:600;font-size:18px;">
                  Amazon Review Sentiment Analysis
                </span>
              </a>
              <p style="margin-top:8px;">
                Classic NLP pipeline in Python using <code>scikit-learn</code> with custom text preprocessing,
                TF-IDF features, and multiple classifiers (logistic regression, Naive Bayes, decision trees,
                gradient boosting) evaluated on large review data.
              </p>
            </td>
          </tr>

        </tbody>
      </table>

      <br/>
      <p style="text-align:center;font-size:12px;color:#777;">
        (Images are placeholders &mdash; drop your own screenshots into <code>images/</code> and update the paths.)
      </p>
    </td>
  </tr>
</table>
