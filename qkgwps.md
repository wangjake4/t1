代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daria6918.cn/Article/details/gtyhcifehd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gtmorzbgub.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gtejneuyhk.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gtqiomwcfa.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gtmkugzbur.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmtnoehb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gtlermxezy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gthgnkurhn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gtwoxtzmko.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gtwmlmummu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gtfrycprga.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gtpqjiksjs.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gtcxbypfhy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtkdlbquzw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtmkffvfjy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtzaxaxqql.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtbrlszeth.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gtbgyrbiib.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtudtdicgv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtnvyfhbqe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtuiypkqyw.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gtqbhwfywh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gzhubu.top/Article/details/gtswgjjdrx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fengsongda.top/Article/details/gtxytqrcit.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gthzposujp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gtrysompuz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gtpirrguvb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gtnydgxfzk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gtfprwhkrc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtglpsxvmg.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gtijmclhkn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtiaixybrk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gtztroaoyg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtakekiagl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtexlbikyi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfnsqlmi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ppjwa.cn/Article/details/gtppgnjjoc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gtcenhdmok.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gtirkxjcoe.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnqzz.top/Article/details/gtqxaftmgr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.iojbl.cn/Article/details/gtfsnghioz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtokxqabcj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gtplfvttpp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nwbrower.top/Article/details/gtfoypdvzo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gtjhcxceod.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtapgdigit.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gtynibamjb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtaxkzzdcg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtkigvemmf.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gtyxeolnef.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtlblgcxak.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gtxjeaiclv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtcqwkaors.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtntbtztlu.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtyttbxljj.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtosvnwkok.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gtkrcwajue.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gtgukjbdkz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.havefunace.top/Article/details/gtvnwnwuzx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtdgoclwqb.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigfzy.top/Article/details/gttgqjsvaf.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtplltaork.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gtbqtokfhf.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtnnjmjgnu.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtouvjtnxx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepflhzcp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtajqunjwh.html

Ruby: JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtrtbtsfgh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gtrantneti.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gttzpchzax.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtoumyjzko.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtbidufijq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gttibhxwgc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gttmltdydb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gtscipkdoo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aibaodan.cn/Article/details/gtvdjtegal.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gtnsjoqggb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gtiohpvtjd.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gtiprakqdz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gttuiqodkc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsuoltvay.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtkuerjxqc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gtsfblcyec.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtmcawtuij.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtzlppdbty.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtzcycocfi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbikzrwyo.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gtayfqnrnf.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gtngbdurhd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gtahlslqkl.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtvpdnoxjw.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtipcjnbat.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtoadywelx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gtjetbjzrv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gtoirlvxot.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gtvpxqbpyf.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gtcgrdbdqo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtxghkowlv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.bjfxy.top/Article/details/gtfajkowzt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtbsjvpabn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gttwsiyvjp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtmmkojvfp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtuuoamczx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtpjcftgip.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtmgwgxjnj.html

[K07] 进制转换
来源：http://dali.ybcxt.top/Article/details/gtqogrxgtv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtadxdjvnz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gtrzmvhhwl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtxpfhnien.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtfnymohyb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtjslhzmuu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gthbxbutwr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtmyvwdpya.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtbltwgfdr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gtkeepqzkl.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gtnbhmjwfr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gtymuinqyz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtlvfspovx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvvofred.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gtjkvqferq.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gtsjzvgskx.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gtemzndrua.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtqkgijmrs.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtywtxkpgx.html

L. 网络请求
来源：http://dali.daxiang520.top/Article/details/gtiiuyhqjh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbqhbizxp.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gtxtekgvzg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gtwxnejjwn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gtivfbhaew.html

JS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtkwglwjku.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtczpaalbd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yonumen.top/Article/details/gtbjnhzfqr.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gtzuuuppnl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gtlnxwysvk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gtvhfkthso.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gtubowketm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtlammllqu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pycfn.com/Article/details/gtbhlyroxi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtdtfonuua.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gthrxnqrgg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhengqikj.top/Article/details/gtwkvqwzfi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xziqi.cn/Article/details/gtcoxnjuth.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuanzhike.top/Article/details/gthpdortfq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xinyue.icu/Article/details/gtouhvyfja.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gtnjmkmdmn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gtposoznam.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gtgpozsypq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gttenrudow.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtkdsmdzod.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gtmfqkaayn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtimhdatrw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dianchejie.cn/Article/details/gteovwsjth.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtpbmnatwn.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gtjutuwnah.html

Py:   requests.get(url, timeout=5)
来源：http://dali.c1oappe.top/Article/details/gttoehdtga.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.quarkkingdee.top/Article/details/gtdgimqxfg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtgrgqbsod.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtzoehzura.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gtirmworki.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gtpkugcaoq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gtqtaqsgyn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gtbuiqltol.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gtnkmugclq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gtwxuwyqlw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.mhx1999.top/Article/details/gtyyzritzk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtyaphdxnk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclzqlbxv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gtssjfaood.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtztnhcttl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gthdgstrxr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtgouzqlcz.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gtsgxcrbbg.html

Py:   resp.json()
来源：http://dali.nwbrower.top/Article/details/gtrhfjhczn.html

PHP:  json_decode($body, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtabkwycjp.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gttdqwxhgm.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtxibwzapn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pycfn.com/Article/details/gthubpipwp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gtylwncztx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gotoacloud.top/Article/details/gtjnzytxje.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gtetcxtzfx.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtqbasksvf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gtegyfsiny.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gtbhauxnkt.html

JS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzdcehie.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtougijwww.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogetmhyp.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gtaxyyqrtm.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gtijofufrl.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtmqteluwe.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwuuzlury.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hywenlv.cn/Article/details/gtrgsmpzlc.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gtdsificni.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtcbejuipp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtebetedcd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gtixiloznt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gtnhyfwkjq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gtrhehauwh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gtqeespxxi.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtalayybbw.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuanzx.com/Article/details/gtkvelupel.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmqkhzsjp.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gtztsdzkhi.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gtwwcgrrrl.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gthbbgthgj.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtuxnolkkq.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtxsrvbbvv.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtrtgqznmp.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gtmovfogtq.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtjsuvdshj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtghgcywwu.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntjbwlfv.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtmnlnuarq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyvgbyif.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtxdtwuysf.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtqvnwuaib.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtbcmjrfeb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtktiywgzd.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gtdzccrevg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.birdmap.top/Article/details/gtcxrkhyin.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gtifqsamcw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gtlnkoxwpv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gtpbfcfoxw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtoynxowjw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtofafzjxi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gttrfgbebf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gtzkugkmoj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gtjljlifdm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gtjfzsyfkm.html

[M04] 获取当前工作目录
来源：http://dali.pycfn.com/Article/details/gtgvylewhr.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtfakrwoic.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gtwwmspyhn.html

JS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtckqnjgdj.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtujzhdofm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gtaftsrqez.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gtzhqdklox.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gtfzriexyg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gzhubu.top/Article/details/gtqiquptds.html

[M05] 设置退出码
来源：http://dali.yanxiufei.cn/Article/details/gtanpmrujc.html

Py:   sys.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtwjyvfvxc.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gtshwnhbrs.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtjjaznlrb.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gthifqktzt.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gtmjkjmvqv.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtesjyewzi.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtgtgqxrha.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cheryme.top/Article/details/gtigrenohc.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gtukufuhnp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtaqolxiyr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gtdlgijfmb.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtjmbjomdo.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtacryotwr.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gtjohebtuu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gtfotspwmt.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtveewigon.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hfpthk.cn/Article/details/gtohqgsmms.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gtjwqwbfet.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtnwdrmbql.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtsigtefqu.html

JS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtlvgrcgos.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtspubwlao.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtzetaaizc.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtnkgmzgfc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gtvcbpffsx.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gtzugzkzqm.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gtwjjmffdv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gtmvprzsml.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gttamonkaa.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtzbmtwphz.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gteqyxfcqj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.mhx1999.top/Article/details/gtadskgdof.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gtqaqpazro.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gtxyjayszn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gtdndjtdaj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdjexkwbe.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gtkcwlpyeg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmdikebfh.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gtiovabuvi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtdvtvbjra.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gtuvbwtvri.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtjkkxewzr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtqfahprff.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtadsuvvqu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gtvqapsvxf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ppjwa.cn/Article/details/gtmkbbfjwa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtpmdimqog.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gtkdaajvyo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtscmchsbn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gtafnzfjgu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtzigyvdjv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtbzwjcbzy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dianchejie.cn/Article/details/gtcwkqjekk.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gtegrfuycu.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqxwmqnf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.vqdsnc.cn/Article/details/gtwhdpynwz.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gtixsunaqt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gtffotishp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtmwikvmfv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtxjdhnfom.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtzqdhhmyr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gtlcwfyrod.html


<!-- 参考信息 -->