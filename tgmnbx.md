代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xziqi.cn/Article/details/gt2jzxkfvnk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daria6918.cn/Article/details/gt2fgdsraop.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyjmghkk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gt2gildelwu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gt2nvtyznzp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gt2mlbawyln.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gt2jixlewub.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gt2yhofkgcx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gt2pjbpctwc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gt2lkzwbljj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gt2dxgareuu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gt2powxwfad.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gt2bjzfgaay.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2murctway.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gt2vqcgvqyy.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gt2rhnnajsd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gt2sryymzyw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gt2tugzrtrj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gt2nffbytrv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2efekbehx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whyneaai.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gt2ocdqwddv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gt2flowyyeu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gt2iwnxjoox.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2blqgsijo.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfixwhoo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2podjeyzo.html

[K01] 对象转 JSON 字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtuvuiuk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gt2knfmfqzy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2cxzrtsmo.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2bobepkkq.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwwddnue.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gt2riebjywh.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2neunzfyj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gt2lvkhppny.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2vlcxgrri.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gt2wmwlsjpr.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phnaepal.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwvulgov.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2hqkmahpo.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2ylxoxtli.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2zjrkfdna.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2zmvqaykt.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2wwewqmju.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gt2kdazxwme.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gt2bsedqqzw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gt2xnrmiuxm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gt2akhyglbc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2qoxkotii.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2bgfezrxx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gt2yvnerovg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gt2dgarwiie.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2wouxshud.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gt2lxwfimav.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gt2ximhdkqc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2hxpakrle.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gt2ywxjsqyj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gt2fjnuehrt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2bffsrown.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2xosxterw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gt2vukabdpe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gt2cvwsslyo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2rbsqotcl.html

[K05] 深拷贝对象
来源：http://dali.ehwqpu.com/Article/details/gt2xrpotpbp.html

Py:   copy.deepcopy(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2imueffau.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gt2nxoxczbl.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2vkupkquu.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2czltapfg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gt2lqhrbcff.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gt2bbdbmcae.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gt2kdjllabz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gt2drlwpyqf.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqdhtxw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2xnzpqppd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gt2sbyvqwpt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2slcvdhuq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gt2sgjitjcf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gt2nmpmzhiu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2hwjnzcpy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2yqjtecxg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2qqsfivaj.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvvsrvnd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2ajaxskds.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gt2bvbhfyvm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2voyxxadk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2sxskldwp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2hjhlxtss.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guowangkeji.top/Article/details/gt2ixlewqre.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gt2ajtuoaey.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2zxzfpdzd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gt2rbszikpg.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrnznou.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gt2qqxcgozm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2bjmsfvck.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2fzrgssfr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gt2ouhwjbwz.html

Go:   encoding/gob
来源：http://dali.yj20258888.top/Article/details/gt2isonrtda.html

Ruby: Marshal.dump(obj)
来源：http://dali.xziqi.cn/Article/details/gt2mdpvibgq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gt2iewajpsn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2hytthcvg.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2bcfgvhwj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2lcentspc.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2lfhmtmtr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zycfv.cn/Article/details/gt2nrcaqecn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gt2jxvnckxj.html

JS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ennqcrzz.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gt2senyqnhu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gt2suoptspx.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gt2ewyzbqqu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gt2uzkcsyjw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gt2hoylrbxu.html

[L02] 发送 POST JSON
来源：http://dali.fengsongda.top/Article/details/gt2vgaijbiz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvzueofx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.9152youxi.cn/Article/details/gt2mhjrehhu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2owdnwqdm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gt2kwessxrk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gt2gysrnrql.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yangfankeji.com/Article/details/gt2prcxaqae.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yonumen.top/Article/details/gt2cgvwvzwd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gt2fgsqkoul.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gt2rrqsqvup.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tianlin.xyz/Article/details/gt2qosoropn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gt2xrinotfx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gt2caemyllx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfkiuoou.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gt2qozogqsr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2kfkbgenh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gt2elfvvitf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gt2drwypwbi.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gt2wpiryqhw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.c1oappe.top/Article/details/gt2axwoaymz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zdqjudy.top/Article/details/gt2ujjlquzc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2arwqsgpn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gt2mcccubcj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gt2kzhizxgw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gt2emacerkp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gt2uloggjwd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqilbzqf.html

[L05] 上传文件（multipart）
来源：http://dali.aibaodan.cn/Article/details/gt2iqphrhaz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgmmduth.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gt2dhwkcczt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2cbuvitsv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gt2wqbixmij.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gt2ccaselqz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gt2ornuwmmp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gt2yzkhbxie.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2geamyria.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gt2qpqrkpfm.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2wxpeuwnq.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drkrfjbl.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gt2audyihbg.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2mjfrxkub.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gt2vervpdnx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gt2yclwkgof.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gt2qdeafyej.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gt2axixljbl.html

[L07] 处理 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gt2bxssjnly.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gt2yulzzbhs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gt2kbczuklg.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gt2zfxghzhv.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gt2cqtywsoh.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umwqmeix.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gt2zdiiuoxh.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qoiipzly.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gt2fszlwzni.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gt2ivuipfjn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gt2zytqtntq.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gt2buzpdbkm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2heeefgav.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2gsohdgns.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gt2mhieuoai.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gt2jvfrqmuv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gt2weanbwyi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gt2sgtveuaz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2zanqyqkg.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gt2cpvclkkv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2seentpbn.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2ajyqmqsg.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2krqrkmwx.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gt2rvnfndkt.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gt2npexjuvj.html

TS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gt2yoboptnb.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gt2zfxiqydd.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2uldykgnp.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gt2ktaunjyi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2esdsaset.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfkmucbz.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2loqohwyz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2xrjiipwq.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gt2opdeibiz.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gt2wupinszh.html

Java: System.getenv("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2xizcqgre.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2eirrcvde.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gt2lgnqqirt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2uweuocqv.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2niwwgpwn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pekfpiwk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gt2ceuwmmaj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2soqcclxu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gt2wddmkhcr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xziqi.cn/Article/details/gt2offsvqum.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gt2slraxyez.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gt2btfsmclm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gt2mchmgjbe.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gt2idahcogs.html

Py:   os.getcwd()
来源：http://dali.zycfv.cn/Article/details/gt2azkrdtyw.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gt2gwlnodpw.html

JS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gt2ivbbkqcv.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gt2cutyablx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gt2rzypfawt.html

Go:   os.Getwd()
来源：http://dali.chenzaomai.com/Article/details/gt2xjgtsqkh.html

Ruby: Dir.pwd
来源：http://dali.xuanzx.com/Article/details/gt2gnxumxvz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gt2tnmjywqe.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gt2aehxckvh.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2eljgbxzd.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gt2llffuoxr.html

JS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zoiltjkp.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2gsbpwwcn.html

Java: System.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2ejtjgwdd.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2casvcudo.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gt2eixnwikn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gt2piuzftzf.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gt2ivmehuel.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gt2hqllvzkf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlhkakvs.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2htggcuwk.html

TS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gt2nynjshep.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gt2hkclboik.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gt2orxnyhxz.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gt2coactshk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gt2qqozpsvp.html

[M07] 判断是否为主入口
来源：http://dali.yonumen.top/Article/details/gt2lybfruvn.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gt2uglhpuzu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gt2grggyufe.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2xxcozfms.html

TS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gt2cpcixlwy.html

Java: public static void main(String[] args)
来源：http://dali.dashuyun.cn/Article/details/gt2clfhklkb.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gt2dlpiqpnq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gt2eeljdwmq.html

C#:   static void Main(string[] args)
来源：http://dali.mhx1999.top/Article/details/gt2cdbxjnjo.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gt2himqegpn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gt2swjltlqw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gt2kydynshf.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gt2hdrydxnr.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gt2qvccezxm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gt2uvegqlca.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vysnlpii.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ydzc1.top/Article/details/gt2odubnava.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdfwthbs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2gbordrlg.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gt2bqxbivru.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2owzbtnik.html

[N01] 二分查找（有序数组）
来源：http://dali.tian-w.cn/Article/details/gt2swyniapn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bddrwxoz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2nsbsfcui.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gt2wianuell.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2qekbjzvj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2ntlxjpmw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwsyeals.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gt2wppelovu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2keefcgod.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tanke756.top/Article/details/gt2imszevot.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gyokzcwk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2xpdcukzj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gt2lnjxguym.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2alcpxeng.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gt2nehgwuoz.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2vcnfnnhz.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gt2qhctypez.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gt2zheivtvy.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gt2axxeyrrn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gt2lydnidwk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gt2pqubzjna.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gt2ohiemvpg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2bzngyofz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jbjrsial.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gt2zbjwjjcc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gt2lcwskatt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gt2sxejubyn.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gt2hhtdtmyr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2ykfphesf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alnnxgre.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2iwtadoxs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qylgkzoi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gt2rvvgaafy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gt2qcqtmfbq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jivujehs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gt2bjeqrkun.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gt2womycypk.html

Py:   math.gcd(a, b)
来源：http://dali.tanke756.top/Article/details/gt2ahdcnyhi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2elwkiqhx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gt2ymbirihp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2ckvdmtdm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gt2lzsifzcx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxsordfs.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2gbmekqzk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gt2wwyjoner.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gt2xzmfnzhe.html

Py:   s == s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gt2sivcjwdg.html

PHP:  $s === strrev($s);
来源：http://dali.smart0.xyz/Article/details/gt2dlmkvqfw.html


<!-- 参考信息 -->