代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gtikavywme.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gtaiqzihir.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gtrgilpkoi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gtfxaklyzm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtlmuaulao.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenjidiqi.icu/Article/details/gtpwdzslec.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gtxyqmokkr.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gtctjnwnaj.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gtxfyujchu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gthwtoxrtu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gtytmcmzml.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtjyzezkne.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtaukuwzqj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gturlxyxmr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtkffzgdur.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtwclestle.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtxbqbonez.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gthcwalegb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gteajxvgvv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gtgushqiyt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtchbznyln.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypwyqfks.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gtsseydygh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gtgexyljhv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtmnvijlmq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gtaieepepg.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gttlyaadav.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gtkxwymsnc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gtrnyzwupg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtqgeojilm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtoeazmocf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgfzy.top/Article/details/gtgrbojhgr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gotoacloud.top/Article/details/gtihikxneq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gtmftxedeu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gtnkvoqmmi.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtztnpcajb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jyoumei.cn/Article/details/gtmauigels.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gtrlpwhblv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ehwqpu.com/Article/details/gtvpotemdn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtjqljtjmi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gticyadbvm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gtndsyowmv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gtowcwcsih.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gtnxdwljir.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtsnrpnymf.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gtztloufnu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtokmvcjfn.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gtbltzwpqz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtjbabfmga.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdbwzwmg.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtdfyrlmvo.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtzlmfpwak.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sweek.top/Article/details/gtmkatagkn.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gtrsarefxo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gtytbhxqoh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gtweczvaaj.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gtjgpigiyc.html

Py:   json.loads(s)
来源：http://dali.redwolf501.top/Article/details/gtslzlefeu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.haohaochexian.top/Article/details/gtccktikns.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtbnqzcgsp.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtovvxacsx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gtidkznyhv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtogrtcxnn.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gttykmdetj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtrketwtqd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gtmwifuyrt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtsoqnvwxb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtlqhqcfbe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gthhhscbhi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtqbjnxhgd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gtzyjuqedg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gtyjtltnhy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yongpay.top/Article/details/gtlgutyvod.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gtcnktfokr.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigfzy.top/Article/details/gtfiqtqvzj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yueranfly.top/Article/details/gtkbnlozvb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gtxoagwpbf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtfhtjtqbi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtkvlrrbul.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtgngehemx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtosvcggnw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gttawkqvri.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gtuvggjvba.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gticyxcxwp.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehksktnt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gtadnulzdx.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtzamepdgb.html

TS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtuptscrbd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gtiittivqn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gtylkvkemh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gtqwchpaiw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtzbrakfaa.html

[K06] 解析 URL 查询串
来源：http://dali.birdmap.top/Article/details/gttqrjeapu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gtvxvdajbk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gtqwgvbfuy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtdbtpqutm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqjlaigy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenlongwang.top/Article/details/gtfsfgnzyv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtmkynqjou.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtabnhiakb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtlgruzobn.html

[K07] 进制转换
来源：http://dali.andypj.xyz/Article/details/gtcxslxaup.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtlepowqzx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gtmfpkzkxx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtrxfikrai.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtjgypvrwp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtqhbxjfdx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpqyjpnq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gtgedjxqke.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtaqvntxpl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gtyionnvjf.html

Py:   pickle.dumps(obj)
来源：http://dali.wangdashe.top/Article/details/gtrpwlyvqu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gtcqihnryi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtkczpmxnu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtltmbsgva.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gtumloteje.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gtfreirlrq.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gtfzeeqagy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtolcnqjev.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlhdvvdib.html

L. 网络请求
来源：http://dali.sysykeji.top/Article/details/gtkkgtshek.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqwoabrto.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gtecpqfjec.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gtukdmtpuy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gtkbnzpicx.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtzfbzmgkv.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtqqwrsbsc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gtqxqzqoyf.html

Go:   resp, err := http.Get(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtmagoffse.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhengqikj.top/Article/details/gtpnwivwfi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gtnqtjsoyy.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtakgvwpzf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtjorfadgf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guowangkeji.top/Article/details/gtkmscspts.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwfeojxl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gtxiacuila.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.haohaochexian.top/Article/details/gtgiowgtck.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sweek.top/Article/details/gtdexdmpqq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gthjlnabej.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gtuyvjmlev.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gtawvlzfoh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gtwhvtytmh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.vqdsnc.cn/Article/details/gtevhuqnjn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtflyfeage.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gthqdeusti.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gtmgsbszgj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmothdwx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhiwuduotai.top/Article/details/gtojrebzjk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtokiwtwfm.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdgxsans.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtiixlgxdn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gtxzxqfrjl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtczeevckd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtrnoskkcn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtagddbymd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gtxpgfmdrp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenjidiqi.icu/Article/details/gtjppkpmhb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtytxdhmeh.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gthxqdqjcr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gticvnmaxx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ydzc1.top/Article/details/gtzlolbbxb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtrjihrvsl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtpslgsbfk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gteizmpdff.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtlizlndgd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tian-w.cn/Article/details/gtknzugved.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gtyxkhqcgv.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbewimmk.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtkmbvruza.html

PHP:  json_decode($body, true);
来源：http://dali.cqqwz.cn/Article/details/gtiotbsdib.html

JS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtmdnlttrl.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqusarnze.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gtzzqmnppc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtupinlvlx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gtweyuvtej.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gtnssjzkqc.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtqlwzyfem.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gtcawidpvp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtvlnvsmha.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtgmaqzzgg.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtrxeohjck.html

Java: resp.statusCode()
来源：http://dali.cashguo.top/Article/details/gtyhnfrmtt.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtjnvnogss.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gtotgvgrdt.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtxdztbkoj.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gtdcavnhej.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gtjvgmozvh.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikxlzdxj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gttvrhawtc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gthvyowpfe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gtvfaelarx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gthncrjdsp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtnsgkyhbj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtuzycmnxy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthhovozna.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gtzojtctfn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtuqqyeqze.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gtxxfnshtl.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gtmaehtqzz.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gtmanonjeo.html

JS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gtjtidlrds.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtelzwkkxa.html

Java: args 数组（main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtzgktwmng.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gtqpzxwidk.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gtgvaujyos.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtkaowcgea.html

[M02] 读取环境变量
来源：http://dali.xylfe.cn/Article/details/gtzdqdhuuw.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gthyfuskjo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtcrtwurxj.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtwpvgkbyy.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtfwzkopbv.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtaxopyuej.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtpqdopood.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gtfbfxjvnk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtfducngfv.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gtniftcdfg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gtbkzdfjzq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtontwhyfo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtumqxculc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gthftwrcyb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gtkdxmquwx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gtsvjmxzrs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ybcxt.top/Article/details/gtjwezvjyk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtesfpeokh.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gtshulhxob.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gtwwptrnsx.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gtotrjkmvg.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtmxfqqkim.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtxtnpwtqf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gtejtmpuxs.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtfmetpsjr.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtjrbbaioc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.havefunace.top/Article/details/gthzcadfnr.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gtiqluahal.html

Py:   sys.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtzqbifagj.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gtqwwsmzva.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtxzknikui.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtazjolcve.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtsuvajztr.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gtvujfqgia.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtjczizmrb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtbxmciruo.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtgytanoea.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gttzqahzog.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.vqdsnc.cn/Article/details/gtzrqkouif.html

JS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtstjvqgds.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtnxyisfki.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gtblvqhrug.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hammf.cn/Article/details/gtambdcsos.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtpxzyiksh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gtlnrmcovg.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gtimkyivyq.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gtvycljufo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhiwuduotai.top/Article/details/gtvdpfjbuk.html

JS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtlagdhpta.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtgltwecpn.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gtwlfgsqrt.html

Go:   func main()
来源：http://dali.sufxvd.cn/Article/details/gtfsncjpno.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtvpwbzhgz.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gtapudmyqq.html

[M08] 获取系统与运行时信息
来源：http://dali.mhx1999.top/Article/details/gtrjvfilqe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtuoiqpmur.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gtzotlxqre.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtkaeabztc.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtzgxduyml.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hongshengwenyu.top/Article/details/gtkqbbtvxr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gtqlzrufxc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gzhubu.top/Article/details/gtpncnfhpr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gtkwxujryz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtajaejhlj.html

N. 数据结构与算法
来源：http://dali.zdqjudy.top/Article/details/gtdbntehmd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtstbnujpm.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gtivlskicu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtluoekjas.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtvyqpvyjd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtrccizgdc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gtorvutrtc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtuhpgitbi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtozsbiaqo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ehwqpu.com/Article/details/gteyojzwpc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtgznpibmi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gtznriinxr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gthilmjbsr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sysykeji.top/Article/details/gtnllqmlbc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtycjneumc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtcoswhant.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gtxmpntpvw.html

Go:   slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtffdjmobo.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtnzhoaddv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gtzubpbgpk.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gtrpdzzadz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhongyouzk.top/Article/details/gtysbejmqk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhixingplan.top/Article/details/gtxxnbjuhq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtusnvsldi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtrovrccfo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtueqqhiek.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gotoacloud.top/Article/details/gtnlhaqwdw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gtfvcoudwj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gteaspmdio.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gtxkrvcfiz.html


<!-- 参考信息 -->