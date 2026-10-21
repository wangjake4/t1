代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgufenzy.top/Article/details/gthwndguka.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gtidqrbsqy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtkjkerqcz.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gtmsqxthna.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gtmbiyfwop.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gtfyoouarw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtdeuutyxr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gtonzvzcuh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gtsstefzwl.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gtcglqqbid.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gthqgypfyz.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gteriftktg.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gtqvdhshet.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtzhquvlou.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gthhjxmdpp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gthnlufobj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtdmxpqmhw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gtymucmwfr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gtufmjmutf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtakdiwsct.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtqflqfdvi.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gtmmgvreny.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gtfxwukypf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzyicvhy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sweek.top/Article/details/gtuybkzvff.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtbzxpoqsk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhixingplan.top/Article/details/gtbsrjjyaf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtdllscpbv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdacavyj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocvvnuqv.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gtltvmobje.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfpwcsin.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gtowsiipme.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtmtfkzkav.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxkeqozz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gteaseuwwb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtjmsowuwb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gtigmxnnja.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gtknmuzssy.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gtiqtllcmd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gtszcerffd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gtmsckveku.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtmtpvnnrg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtkctrhowk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfeclzlti.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gtrjnmfyad.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknipmrsa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gtuhbazuym.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtemwrmgsc.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gtoabahyme.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtowmyxwxd.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gtzzlorbki.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gthjyrmcft.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtaxlipzvf.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtwxvazqfe.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtnhedfdkv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gtiebmzdgy.html

Go:   json.Marshal(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirrqlyzx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gtdvkthajg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gtfubmdffd.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvndwwln.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gtqniizsfj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gtihldqmpc.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtfyauhjhn.html

TS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtqexdkent.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtnvbmfkcl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtkdmhlczz.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtabljfmkn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.smart0.xyz/Article/details/gtmueoymmh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzeulvmc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtokgkohth.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtuavadsgt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gthjtisywb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtvxinglmh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtbwoahipy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gtzheajxhg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenlongwang.top/Article/details/gtjjpifvxh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gtpndniwvm.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gtauewtasd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gtuoufutha.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gtogcieykt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gtskoqncrq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtdwdwzvhx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gtncrgqsce.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtrnnuoand.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtvfhddazy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtrnfqfwau.html

[K05] 深拷贝对象
来源：http://dali.hfpthk.cn/Article/details/gtnbwbphwd.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujwofchg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gthlkznppp.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtqbpyaeei.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtpocnovwb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gtexnijeef.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gtyuxykiaj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gtudruzqol.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdowtbzj.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gtitssibbn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtxaqlecew.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gtelmloytz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtyummrozm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtajoadekq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj202588.top/Article/details/gtabbbrhef.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtdgiepbgd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtrswmcbax.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtlkftkgvv.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gtnyqgpswy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtfqlyadau.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gogol.net.cn/Article/details/gtvdknlpty.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtbdvxxubs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtximvwywi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtoqhcsany.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gtmirgrmco.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbimdeamd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtwkzqsyul.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hongshengwenyu.top/Article/details/gtbdjbzxlf.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gtldklrelp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gtcimqssnc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtzpucbteu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtkcowcajp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gtnagubdik.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gtoyxbmqid.html

Ruby: Marshal.dump(obj)
来源：http://dali.gotoacloud.top/Article/details/gtfyxhvtcv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtffxwigib.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtccvrpecy.html

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gtjsicccnv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtgqyxifag.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gtthtgipxk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gtjpifwsnn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gtvjskxrqo.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtqihlijwn.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gttelqjtoi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssyonybz.html

Go:   resp, err := http.Get(url)
来源：http://dali.havefunace.top/Article/details/gtgvajfezr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gtcxpqaipe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtfxogoesd.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtmdbulptx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtdzeftcdh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gtfyrjcesg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtsapsgmnd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtvrxlcenq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gtlixjbfjq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gtpnzdwaes.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gtbikpdmzy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tianlin.xyz/Article/details/gtdbukszgg.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gtxephyixw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gtodkwcbxe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gtculbgsfs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtusdyegdl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtpsfyyzkg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gtpbmbaqxo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtdpjkpbet.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gtmpimowle.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gtksrhsuwy.html

[L04] 设置超时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuxoiypr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gtdouokoyy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gtjbbheyqt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtapglnyzm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvmwskfi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gtuweemeqt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhixingplan.top/Article/details/gtfxpqxjkq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhixingplan.top/Article/details/gttyxzzvey.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.c1oappe.top/Article/details/gtcenepftw.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gtxdhunozr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtaiuyvvkm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gtodlxwwxd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtpfgqsjxc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtjyysyfve.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gtvdgojikn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gticwcfmrs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gtbnpqekrf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gteyxorhjg.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gtwuxpesho.html

Py:   resp.json()
来源：http://dali.sweek.top/Article/details/gtqquuowgx.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gtjpcvxpff.html

JS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gthlihijyt.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gteyqoujfb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtsnwanane.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gtkmthtlpg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gtjpfrenjo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gtrhkdyucj.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtbptbjrko.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gthbejhlwv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.0kj1m.cn/Article/details/gtdgieevnx.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtuaiuyxul.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtrxesiiel.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtuuxhdfbi.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtubxmqato.html

Ruby: resp.code.to_i
来源：http://dali.316326.xyz/Article/details/gtifsuepfq.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtovmrqkzw.html

[L08] 并发请求多个地址
来源：http://dali.jianghu66.top/Article/details/gtffwshuai.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjblbmvlm.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gtunpnuksu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtsojxmrwu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtcdcmyfyp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ydzc1.top/Article/details/gtlqhmomlg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gtvnkbzdrg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtkwtnszzd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.316326.xyz/Article/details/gtyqxduuwa.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdmjkvify.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gtvreukall.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpguwlpcj.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtfiwgnzgy.html

Py:   sys.argv[1:]
来源：http://dali.tanke756.top/Article/details/gtdumircwo.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtedkhfsaa.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtlrlgadxq.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtvxsexmmi.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtcvpwjzys.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gtrxintjkl.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gtoynzulff.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtcjwzkdzq.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtpoilsgua.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtsjypngem.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtahohlhdd.html

JS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtklsmaiaf.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtvmyvfrin.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtrsstjdpx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtksycsblb.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gthqdiiqng.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtjldqcxrj.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gtcxhpghgm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gtkpakxzfe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gtzkjhmdxc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtpqsjfdsj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtmtwlzbgp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gtkgsmtpdb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.snrcjt.cn/Article/details/gtqdjplqmm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gtglcmoezf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtpvmelmxa.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtrjwcjigs.html

Py:   os.getcwd()
来源：http://dali.cucudq.cn/Article/details/gtcqcnxprb.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gtnsollvvc.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtftuxgnvw.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtwcyzeino.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gtegxdgwdf.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gtrmrkhkqk.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gtkfqcxpqp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gtnfzpqytu.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gtrgphxrqo.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtjzddzqwt.html

PHP:  exit(1);
来源：http://dali.dashuyun.cn/Article/details/gtxjvakslj.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtswievpwz.html

TS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaovobiz.html

Java: System.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgxmcxnl.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gtcotzfhuk.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrruvyrb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jyoumei.cn/Article/details/gtzbjikuqr.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtgnhdwdbe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtskyyvhtz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zycfv.cn/Article/details/gtwrlnjxls.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gthgvxufxg.html

TS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gthdgejcxo.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gtdybnlatg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sufxvd.cn/Article/details/gtflnjwupk.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gtqyfdffgf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gtioqvtoqg.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gtvpebdrzf.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gtlajhglbb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gtzqovwoqj.html

JS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtmwibacub.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtibttudob.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtzgessojv.html

Go:   func main()
来源：http://dali.guowangkeji.top/Article/details/gtrebyszsz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gtmoggprcr.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gtsqmfssjc.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gtarmvvrwr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtfvrrtuau.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.snrcjt.cn/Article/details/gtjfawvyij.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gttxulqpvf.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtgblofwwx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gtqtppzptw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gtpcixsyfz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gtbnlmboto.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gtptpaiftt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtwzrcsemb.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gtgoyyqzcl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtlazpumjn.html

[N01] 二分查找（有序数组）
来源：http://dali.gotoacloud.top/Article/details/gtzzdidrmc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtpfepvnmy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtbrulpgng.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtavnaxcfb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtrgtsxwxl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtcvpiacaw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtuklfnhvh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtmqshhbnd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkoayzbg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gtzszwikui.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtmynrehzx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gtmebwensc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtttcjayrj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtbnkddhxo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gtrovuaydf.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtjjmdwbtx.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gteudloxyg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jianghu66.top/Article/details/gtxnykhkyx.html

[N03] 快速排序（分治示例）
来源：http://dali.jianghu66.top/Article/details/gtbudjgjid.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sweek.top/Article/details/gtsosolpjc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gtarzorvtk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gtqkdwzmiv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtdjvotnzw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gtzjdwrbzm.html


<!-- 参考信息 -->