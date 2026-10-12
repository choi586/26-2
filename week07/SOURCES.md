# 7週目・資料

内容原本（2026-10-08確認）：
https://www.notion.so/3f3fa81fdf6181a9b0e1c1008b33b396

共通デザイン：week01/index.html、week02/index.html、week06/index.html、SLIDE_GUIDE.md。
表紙・固定1280×720キャンバス・操作は既存週を継承。
タイトル52.48px、主な本文30–34px、中心となる問い44px。

全14枚：根拠 → 問題 → Value → Solution → Scope → 中間企画案 → 伝わる資料の作り方。
原稿の長い列挙は代表項目に絞り、定量・定性、根拠2〜3個、問題文、体験の変化、中心となる機能2〜3個、範囲、資料の選択・核心文の趣旨を保持。
リピーターのタイトル例と場所保存からの拡張例は原稿に基づく授業用の例。調査結果・実在サービスの実績として追加していない。
Valueはユーザーの写真挿入依頼（2026-10-13）により、同じ旅行者の状態変化を示す写真風AI画像2枚に差し替え。実在の利用者・サービスの実績を示す写真ではなく、原稿の「利用前と利用後の経験」を説明する授業用イメージ。
活動一覧に7週目のテンプレートURLはまだないため、未確認リンクや新しい活動は追加していない。

## 6ページの写真

生成方法：組み込みimage_gen。AfterはBeforeを参照し、人物・服装・背景・照明・構図を維持。
保存先：
- assets/value-before.png
- assets/value-after.png

最終プロンプト：
Before — Use case: photorealistic-natural. Asset type: BEFORE photo in a Japanese university tourism service lecture, shown next to a matching AFTER photo. Create one realistic editorial lifestyle photograph, landscape 2.2:1 wide framing, no collage. An East Asian woman traveler in her mid twenties with shoulder-length straight dark hair, wearing a plain cream knit sweater, seated at a light oak desk in a modest naturally lit room with an off-white wall. She is trying to plan a trip. An open laptop, smartphone, an unfolded paper street map and a few itinerary notes are on the desk. She is hesitating and mildly frustrated, one hand at her temple, looking down between the map and her phone, as if struggling to decide a travel route. Natural, recognisable facial expression, not melodramatic. Camera at desk level, medium-wide waist-up view, place her face, hands and essential travel papers centrally so they remain visible in a very wide horizontal crop. Neutral daylight, realistic skin texture, candid academic teaching illustration, no glamour or advertising styling. Any device screens and papers have simple indistinct shapes rather than readable text, no fabricated brands or app logos. No captions, no letters, no watermark, no decorative effects. The next photo will show the exact same woman, clothes, desk, room and camera angle relaxed after organising the trip.

After — Use case: identity-preserve. Asset type: AFTER photo paired with the supplied BEFORE image for a university lecture about service value. Input image 1 is the edit target and identity/composition reference. Keep the exact same woman, facial identity, cream sweater, hair, room, desk, laptop, daylight, camera angle and wide 2.2:1 framing. Change her state from hesitant and frustrated to visibly relaxed and quietly pleased after organising her travel plan. She sits upright with a natural soft smile while checking the smartphone in her right hand; her left hand rests comfortably on the desk instead of at her temple. Neatly fold the large loose paper map and place it beside one tidy itinerary notebook; keep the scene believable and leave the same laptop, mug and room furniture in their original locations. Show reduced effort and a sense of calm through posture, expression and a tidier desk. Natural editorial photography, realistic hands and skin, not a victory pose or commercial smile. Do not add other people, logos, readable text, captions, watermarks, screens claiming a specific app or decorative effects. Preserve the original photograph's colour and light so the BEFORE/AFTER comparison reads as the same person at the same table.
