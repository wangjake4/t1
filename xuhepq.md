代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gtpmabhezd.html

PHP:  $end->diff($start)->days;
来源：http://dali.cashguo.top/Article/details/gthieurezk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gtduriietq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gtcsvrtfwn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gtrxtacaxt.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhiwuduotai.top/Article/details/gttfjwjnks.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gtanelfxja.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gtimliktpk.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gtvubsukqc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtndtlhqmb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cqqwz.cn/Article/details/gtewfgglyw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtmckupvtf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtepcyembo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gtmjtyyheb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gthgeltzlb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtrzejlfvp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtksvzdpho.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gtbzsyzxxd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gtztxzxuhu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuanzhike.top/Article/details/gtlkikfklu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gogol.net.cn/Article/details/gtlltinttr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtdcwuanzp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gtkxhzfgbi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gtmmcbelbt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gtbmzirlsy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.redwolf501.top/Article/details/gtwhcmzlxt.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gtjrwxoybi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gtfzwlarfs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gtogzygqcl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtztzkyzzb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gttepvrfjl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gtfcouutak.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gturhunzfp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guowangkeji.top/Article/details/gtjgbkgljb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtlxlwrwnh.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gtwiygdamc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhiwuduotai.top/Article/details/gtyemondjn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttefzixij.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hammf.cn/Article/details/gtvqdshiha.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gtljsjujhp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gtxmirnbrl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gtgusxbgis.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gtamdoeiuw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guannengcc.top/Article/details/gtklfbfnhf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqotykzsq.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtvygttu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvtkpvmx.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gteftrhrqf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtoncblxmd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtsfwnqmjj.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtslfrfhse.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtfavqjkwt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gtmtxcizjy.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gtvtdnnbrk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.havefunace.top/Article/details/gtlugakydf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtduuypctj.html

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gthncxwqgi.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtesiskruo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gtutxsqpqf.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtgwztheoe.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtsbxwilto.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtwbrdehtt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtiqxtonqq.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtxdhufttn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gtswuuecmh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenjidiqi.icu/Article/details/gtqyziriuj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtbssccsqe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtvattcezw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtkwibrpvi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtsjfioidl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcqwsooy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gtoeeolhkn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gtwqiattuc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gtfdacvrcg.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaepjyyqi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jlsjyb.cn/Article/details/gtxvfyuyvi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.haohaochexian.top/Article/details/gtomzzhalf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtcjragnuu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtavxjvakj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cheryme.top/Article/details/gteqeqjtfk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtxtgvnmgp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtxwnukqcw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtkqlwfsqf.html

[K05] 深拷贝对象
来源：http://dali.gzhubu.top/Article/details/gtlzhnoprw.html

Py:   copy.deepcopy(obj)
来源：http://dali.ybcxt.top/Article/details/gtfzfiuyes.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gtaudflbmx.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtjfuwzmwt.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtoideenpb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgbfmdei.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gtjtuwjojd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gtvytckspd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gtjtxutilj.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gttxmzsugt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtyeodkdve.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gttvqaqyrj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtqfzvdush.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtddhdxbfo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gtmcqfwsgk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtwhzloygb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtizwyrdrx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtrzvfdolq.html

[K07] 进制转换
来源：http://dali.yj20258888.top/Article/details/gtrsfliuzy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtsgqovfvx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gtjisvcrqe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtkupfluqg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtelqkciga.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gturfseret.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlvpkera.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gtfloggide.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtwpugqxjj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gtkuqdbmkf.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gtzvnsdazl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gtluyziiah.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gtmphacoew.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtewvtklae.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gtdxoslgwk.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gtwkbxmlea.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gtymwnwdqi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtqytkyntb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtblqqdsro.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxhjowlr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthpgzkvcx.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gtwqoihvwr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gtgrfuaxww.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gtutpjkhdw.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtioirdunn.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtjrrdgcog.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.haohaochexian.top/Article/details/gtrgjrutmd.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtselsjkup.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gtkqugpcyi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258888.top/Article/details/gtznprnohx.html

[L02] 发送 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtrambdkyr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtvdsaasym.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtukedxqzk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtyeuzjebc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtbypuptsa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gtueqtwzhv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gtrgwugehg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxinkj.top/Article/details/gtdwfteqbi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gtkhayrauq.html

[L03] 设置自定义请求头
来源：http://dali.pycfn.com/Article/details/gtecgcptqq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouqozcxf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtsshfhkxn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtvynbxprk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtjcxekojj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gtqzssqswp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtmzgpwyzm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtrzurrixf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtgvxlrzfn.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gtsmiqidgo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jiagoushi.top/Article/details/gtuhhkquwx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.snrcjt.cn/Article/details/gtmizjesca.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gttsatlfcx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtjtfosqkn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aibaodan.cn/Article/details/gtfmqrvpae.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gtxuvslxnq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtljrpmppy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.redwolf501.top/Article/details/gtoafazzil.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gtojybfere.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gtszprnycd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxinkj.top/Article/details/gtmuhpialv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtzxknakhz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtyvqwlvar.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.svipenyu.cn/Article/details/gtukxxkrmf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gtgnyvpher.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gtmyloootg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hammf.cn/Article/details/gtkgvglxqz.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtnwqzojxl.html

Py:   resp.json()
来源：http://dali.hammf.cn/Article/details/gtqjighqxo.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmwsndhm.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtstlagjao.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtohwwawih.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gtprzzlair.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gtaicywnbj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gtjwwhauaq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gtgomovceq.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtywyadtas.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gtajkqalhg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gttgoaojbo.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtrjrsnufr.html

TS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtibrnmssa.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gtekhaznpn.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtfrdmngcc.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gteawmnoei.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjvogxgf.html

[L08] 并发请求多个地址
来源：http://dali.chenlongwang.top/Article/details/gtbuljewaq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtdsrudgxo.html

PHP:  curl_multi_init() 系列
来源：http://dali.yueranfly.top/Article/details/gtrcomseam.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtmjofdmht.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtvedwfaxi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiwpjzjq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gtlhrcspxc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxmjquch.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoxyhesn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtamrfioyy.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gtuuuuggrg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpdkmsbzn.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtgtfomhxy.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gtylpdtmcx.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gtzmiwjyql.html

JS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gtndjadayj.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtmeeadxsm.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtglciliof.html

Go:   os.Args[1:]
来源：http://dali.sweek.top/Article/details/gtqdnbxpdv.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gthfxshqae.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtbjapahgk.html

[M02] 读取环境变量
来源：http://dali.aizwys.cn/Article/details/gtqlsqsiji.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gtwfolqwvf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtouqnpmlu.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtuyufwzxl.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gthradyloy.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtwgzfxvan.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtkhciubmp.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gtsndrvyoy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtwqalrior.html

[M03] 执行外部命令
来源：http://dali.dianchejie.cn/Article/details/gtcxribigb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtojoxtlxp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.quarkkingdee.top/Article/details/gtayesuokl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtqottpenz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gthorldhcn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gtbxkwsxfz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gteyyxeuwn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtlpgmvlvj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtbinkusqi.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gtsgszqrji.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gtynytdxpq.html

PHP:  getcwd();
来源：http://dali.dianchejie.cn/Article/details/gtadksiuem.html

JS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtvmidlybz.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtgophufgy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtnbzsbqda.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gttlkgcifu.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gtejodymwc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.birdmap.top/Article/details/gtxrudiqlr.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdokljdb.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtrfefyywl.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gtrmyuqevg.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtuecuckgr.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtepsmoqic.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtoyfzwdsh.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gtpoaejngw.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gtqsivwcla.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cdnleiting.top/Article/details/gtrrbdbvnu.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gtxcxvleno.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtgmxdfmch.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtzucabdxt.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtzoncdacl.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtngddeiga.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gtawsjpgsy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gtaekeileb.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gtjpfcvaiz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gtkjxtqccz.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gtwsllimas.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gtlttntwcv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gttpfcpzlq.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtiqduuscl.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtpejhkoxz.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gtcswwfksd.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gtcedwelpe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gtiurqfufi.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtiejxxubb.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gtdpfrsnuq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gtbvdgexao.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gthiqdnhho.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtbcwvokyn.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtjkybvevt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gtekysqdut.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.birdmap.top/Article/details/gtpxomcxxz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gtrlwcdrno.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gtufwqrdlo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtjeqmvrxl.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gtulazbblv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtotltjhji.html

[N01] 二分查找（有序数组）
来源：http://dali.redwolf501.top/Article/details/gtphrvhahi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtyqbocvmm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258888.top/Article/details/gtygnphmob.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtgyauuhvc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtwwvbxegx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gthotakcyd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtycdcbagu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gtvtnpenaz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtzmrovqpb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gtzedjoteb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtabwmvppz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtoijniufv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtlhxfkmfv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtloozguyn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jlsjyb.cn/Article/details/gtmebhufty.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtauosxqrf.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gtycnwhgjh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigufen.top/Article/details/gtjzbublvo.html

[N03] 快速排序（分治示例）
来源：http://dali.zhiwuduotai.top/Article/details/gtrqsficqd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yueranfly.top/Article/details/gtkdqhumzc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfobjdpo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtbfnlfohw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gtgyflocdi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xinyue.icu/Article/details/gtkuglqhqi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gtmvduwylk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gtfzvgoawo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gzhubu.top/Article/details/gtnwfafcfn.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjkkqutc.html


<!-- 参考信息 -->