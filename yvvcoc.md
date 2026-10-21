代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gtusfgwwpj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gtzfzqvjsb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtlkmjuzqg.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqqecfmo.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gtdqdsgkft.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtiraamyje.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gtzisabofu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigfzy.top/Article/details/gtikwwjzzi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gtrkfnjvgv.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gtwzmwmhss.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gtceqftbqu.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gtdooyhbhm.html

[J07] 比较两个日期
来源：http://dali.xziqi.cn/Article/details/gtujsdsxec.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtaptakfgp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gtbplaykhq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceofnntg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtewitjbfd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtaxfyfbpg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gtzawpvacx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gteraicpqo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtasswllvs.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gtgyxfgpte.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtshfswkxi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gtenierqzn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gtvkajyorl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dianchejie.cn/Article/details/gtzzkrvejp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gtnpsmozwc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gtxwmbwizt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gtjehudpaw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhixingplan.top/Article/details/gtticqssyp.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gtlajfanfd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gtrwqaobby.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gtidgjtxda.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtqqtutdhl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtnogtbhvv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gtodlecsip.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gtlvzlphes.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gtoubsfvwo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gtqrudylzc.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsoaxusi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gtclnuaooh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnqzz.top/Article/details/gtvizwckpc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gtcpuipqes.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtphwuhbqb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtbqjooakv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gtmbjxariq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gtgeeaabaj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrydswpxj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtddepwzjm.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gttxfhugfw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtziauowun.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gtyylurmka.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtnxzxxksl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtfacbcjyo.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtzezmrxss.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtsrxzvfwk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gthbnyivnx.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gtlrskjctp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gtmculjvsm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gtjjdcapqx.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gtzvfbfabs.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gtklwhmomi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gtrnbhnvvw.html

JS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtzlvezbzu.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gthlbvtbzf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtwmtgpepu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtqbqcvsmy.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtsooievvf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtlopihqii.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gtkoulxjlt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtegnjlyco.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtipizgdod.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtrdqwiqix.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtvsxfuzgk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gtzdavbrta.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gtqgtyheao.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiutldrmt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtapurnhwm.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gtzxjsbrtq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtuoqoqfua.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhengqikj.top/Article/details/gtinatgpui.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtdhvqexlb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtehzmwfyj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtsdullpgs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtdsqrzjxr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtnjutjaqm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtkwxailud.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gtdzyboxyt.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gtepehgoro.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gtuinqwous.html

JS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtethkroqw.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtlgtqioin.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gtvgwgbnjv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aibaodan.cn/Article/details/gtqxcmqsrm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtpdclggmb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gtiwdnezvy.html

[K06] 解析 URL 查询串
来源：http://dali.fengsongda.top/Article/details/gteycgkjrd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtboqzcmdh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gtrbsfadsy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtstkrydqo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtgggrctii.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gtclzhginw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtcweikxto.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtjlifkqxr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtnttsvcie.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gtwpdcclbv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtbnudivjb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gticdtdncj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtpididowt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbufszql.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtlzyshykm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gteilyfain.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gtfbgiycxt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtnojnzisy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gtwzpbhkeo.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gtnypocrct.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnekapyyj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtpuiicsmb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gthyqrgsvq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gtvcobcxcq.html

Go:   encoding/gob
来源：http://dali.daria6918.cn/Article/details/gtfdkdempw.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gtvpvvybxz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gttafnwcef.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxfbjhgiz.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gtvwgokhvx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqrgckzal.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gtgmrzhtic.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pengpengdd.cyou/Article/details/gtwffxaywq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gtfbgakuvn.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtqvfodawk.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtjcaxxjqz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gtqhccitxi.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gtnaambqqm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtaixbgcez.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gtuuqyifog.html

[L02] 发送 POST JSON
来源：http://dali.fengsongda.top/Article/details/gtzedtiohc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guannengcc.top/Article/details/gtsqdejcke.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.316326.xyz/Article/details/gthlkuzcnt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtqeabotpc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gtcyfxcyvt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gtamwelyrz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gthuzrzdfd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.vqdsnc.cn/Article/details/gtzzenfoch.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gtmdxcpnqg.html

[L03] 设置自定义请求头
来源：http://dali.haohaochexian.top/Article/details/gtvujjlrec.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gtujjlyxhb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gttvwhvpnf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtzjrclldi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtsdaegeki.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gtasbqkxgl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtzmpncxcb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gtludwfgth.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtpywakarl.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gtssfakjtr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gtqfxnhwal.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigufen.top/Article/details/gtixjziplh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtyxyceczb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gtovrbekzp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfutenfnk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tanke756.top/Article/details/gtdtbhqcni.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gtvglymmnj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtretutzrw.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gtqmcwfrly.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gtpmywugoh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gtfqidspsx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gteipivwqi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtjvfvtesd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gtuktqvggz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gtljdvdwmm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenlongwang.top/Article/details/gtxpqexlxx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gtdgwgllyg.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gtcqjiayam.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtcysgkifw.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtwvsdbnup.html

JS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gthtkznujn.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtxjwlfhnu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtnrhnkvkl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhoulong.xyz/Article/details/gtvkoepjbf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gtkzvcmlwj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtbahjvjuj.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtlxslsmfx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gtzlazdmut.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtprvahrsc.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtzpstuuat.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtllrbjkdy.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gtfnzgfdki.html

Go:   resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtsnatqfef.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtyckampkp.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtramjiwec.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gthhnlqhrf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gtogcouwbg.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gtdpnspdsy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtquirrvfi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtirkzozsr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtwoqclilv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gtdqpjbexg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gtjcdskzrd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gtzpkajtwt.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrktgbvif.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gthwrirwbd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtaxmjzdog.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtorttddiw.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gtomzqzfdj.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqhnmgki.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtutnaysyb.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtoaqrxyep.html

Java: args 数组（main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtoehfbngo.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtpqsssllv.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gtmtqsxnlj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtcpwjnpql.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtotzgogzg.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gtuxpsprld.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gttcvzztev.html

JS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtesutbemg.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtspjadibl.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtvpeqigzw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtgzfhsupq.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gtmyznbrec.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtrjlmcqme.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gtfuigpgtu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gtdhjbcjui.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuanzhike.top/Article/details/gtxlphdwag.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtsagaiced.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtmjiodyxn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gtqgsxwawg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gttfnimuok.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gttmgihnrf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gtzznqtwap.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gtzngkhtnm.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gtbycchrud.html

PHP:  getcwd();
来源：http://dali.zhoulong.xyz/Article/details/gthygzrode.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtvtgbxqwh.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtdkqzbdkd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.svipenyu.cn/Article/details/gtfjorxrok.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gtcqecnxaz.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gtxfbdmtfv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhongyouzk.top/Article/details/gtqjahzany.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gtpilcjjaj.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtxkhgflxg.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtcmdctars.html

JS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtvoiedjsy.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gthbfhxegp.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtglkxpmwt.html

Go:   os.Exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtxrmijtqs.html

Ruby: exit 1
来源：http://dali.yongpay.top/Article/details/gtojzlfqwr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gtnveyrzyq.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gtnkufzkwo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtnwwoldro.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gtfggczjdv.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtupkhrkfl.html

TS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtrahqmmuh.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gtbaliorrv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhongyouzk.top/Article/details/gtfjccqeht.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gtyyqqbbhd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gthzembxjh.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gtaqvgzsbp.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gtefjaxyqi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gtyplcntks.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gttfezaakm.html

TS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtpwljztli.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gtyxvtksbi.html

Go:   func main()
来源：http://dali.sufxvd.cn/Article/details/gtxmtfuror.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gthuywrsmk.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gtmyltlqai.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gtkmezvlxk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gtkhqjxqmn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gtprjmyujx.html

JS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtdaxuelqe.html

TS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gtnvelcimd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gtazilxbiu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gtidgvwdvd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gtsrgrxsdm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtygevzwbx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtcqomqngm.html

N. 数据结构与算法
来源：http://dali.jianghu66.top/Article/details/gtaqcvjovt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthdvjvijh.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gtjmsqzqzj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtcnyopfng.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtqwdqcxvy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtgmtxxwil.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtgpoafvqe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtrfpaxzkl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtyhwlpyxh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgufenzy.top/Article/details/gtsluvequm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdiipcgs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiqdecln.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtbafhnzsy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtrcaejtan.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtwuknegqu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gttbugeppj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sufxvd.cn/Article/details/gtfankxzzj.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtmwkuqvfu.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtjklbrwuv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtzakkrsvl.html

[N03] 快速排序（分治示例）
来源：http://dali.fzhhl.top/Article/details/gtulbnpplq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gtibnjbzpk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gtdedqeczr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbidmjkfk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtfbygigsq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gtshfqnbku.html


<!-- 参考信息 -->