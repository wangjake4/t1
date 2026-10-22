代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gtvkfaqmeq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtqzvhsmli.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtmiqfrzvu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtujofkcmq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuanzx.com/Article/details/gtypiebjaf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigufen.top/Article/details/gtorvnzwme.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gtzikwujfs.html

[J06] 计算两时间之差
来源：http://dali.redwolf501.top/Article/details/gtcydrtbek.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gtmeoyqlht.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gtmoqzyzyf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtqybsygrh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gtvfgbujwv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gtqqixojjp.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gtdnmftcri.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gtxqdtwjex.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gtvfradzin.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gturmnpzed.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtjclzwuwz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gtdtfwrvvn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtupnmjbxd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtytvtfyyd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yonumen.top/Article/details/gtuwisezpd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gtdmpghiyp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtqrsinalq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtjnjmtmrs.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gtnkrdqvvi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gtcwxxrvua.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gtyauzidci.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzctctje.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfjfzaof.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtwhgihcqz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gtcnzlfsjg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gtirnkukdo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gtrhpahxsl.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gtvpvfvgql.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtewtjzdbn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtpgvvjsvk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtftanylbk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gtaltkfdao.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtuiyfsoja.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gtxqutnnwe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gtqssfxdib.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gteyhkquik.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gtgmitjlqv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gtkrabfnfl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gtrvidkhzz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtknitjgba.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtkfnejpje.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gtjegdfnng.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtnagphzqw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtaxunteft.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gtaeirhcih.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtbbindeax.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqelutjz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgyxmwvd.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtisfxajdj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtawenzcqm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtknksfzmp.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtybrlfmki.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtheneebca.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gtlidtwpjr.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gtwiztfkcg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gtbompcrgj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gtgbymkmxs.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gthgvoxrwv.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gthobxdqur.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gtogbusiei.html

JS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtmlwuresz.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtdfvcogzy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtmjxmokqr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtoclaciwn.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtffkfvgik.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yueranfly.top/Article/details/gtmidmgkqs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gtocczbfji.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtswtcaabz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gterviwbri.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtdjljekak.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwlcesqh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtkjpmagyq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifthnhbt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gtpsbcibja.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gtfaxlmjgs.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gtpthywzuk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gtgxnfrgit.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tian-w.cn/Article/details/gtycaddqgf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtifmqdpkd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrddqnzr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdpquucf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtgbxldgls.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gtzymcdbif.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gtsczclvqh.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtwxslhhci.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtqudqcdne.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gtuveunitg.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtkmbsbjxk.html

TS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtnbjkozlp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gtjvkmkuki.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gtsubpvoof.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gtqtkttmaj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgufenzy.top/Article/details/gtslgqqbta.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gthnojlyxq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtcainjgdf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gtbqpqduhc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gteqeaqhzh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuyikylm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gtawlyvdhy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxwmpvny.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtmqtmbowh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtjhhkxnys.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gtepmhjewc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvxvlbdj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtyqmiixpk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtodulhjyc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtliiyiaup.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtujonpmaj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gtfaiaszgs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gotoacloud.top/Article/details/gtkfyvnxwn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gttxwzwdmf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jianghu66.top/Article/details/gtkegkwnnf.html

Py:   pickle.dumps(obj)
来源：http://dali.aizwys.cn/Article/details/gtchbkfxen.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gtlcyhfntp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtbremhwml.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtirggavyx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.quarkkingdee.top/Article/details/gtorziqwkv.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtqvytwhgr.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtwaxddabq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtvdaesvpv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwunaweim.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gtypbegdev.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtuqbxwyqp.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gtzjdqlzfk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gttulowcab.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guannengcc.top/Article/details/gtlgierdfj.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtdmfuqhld.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtublslhtw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tanke756.top/Article/details/gtvhbelvyd.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gtpzoczaeo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gtrlffujff.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pycfn.com/Article/details/gtvnsjxdpl.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtpmtmdweb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gtbyfrmupj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.smart0.xyz/Article/details/gtipdnpsaz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtvtlisxdp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtxagaacei.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guannengcc.top/Article/details/gtguxevdcq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ehwqpu.com/Article/details/gtbucnxqzk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gtgqusteke.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxinkj.top/Article/details/gtepwxutdr.html

[L03] 设置自定义请求头
来源：http://dali.aibaodan.cn/Article/details/gtjyblqipz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gaohongyu789.top/Article/details/gttbzgffod.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tian-w.cn/Article/details/gtaqcskbya.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtdomzrmuy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtqodufelm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqonmnvh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtsornhclg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzsfmhdl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvrhwjzw.html

[L04] 设置超时
来源：http://dali.jqgfzy.top/Article/details/gthbqwogve.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gtahvnaoqi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gttxqntlnk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtunqgplas.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtnutmmfcs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gteaujfcus.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gtevftzzyx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sweek.top/Article/details/gtnmitwlwv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtlsgyzrzu.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gtmvemtzjn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gtmsrahsth.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtuohgajdo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtsovsaudj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtnmthtviu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gtvpavznxc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gtllnwdceo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewobvabl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gtkvvdzcqq.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gtzvpwxitk.html

Py:   resp.json()
来源：http://dali.shuidangran.top/Article/details/gtgeezbjor.html

PHP:  json_decode($body, true);
来源：http://dali.svipenyu.cn/Article/details/gtvqghtkqx.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtynjyfmer.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtpcvilkho.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtmdiibpsm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gtbyyhpvrm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gtnxoetdaj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtglnlrztu.html

[L07] 处理 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtiohrltqp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gtelnssbmb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.smart0.xyz/Article/details/gtzitflgcc.html

JS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtdhnupemy.html

TS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtnxzugzlw.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gtyyvrwohl.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtljxvzyuu.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtqptpluxe.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaflpmrib.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gtibhsyrnj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gttukgvbye.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gtevdrkcon.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtoqgocmcb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtviogoljg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gtelzgkyni.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aizwys.cn/Article/details/gthkpeezlx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtxyrmfqhz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtbrbqwhzp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtghxhrfsa.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gtuuvzveva.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtzifdkagj.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gtgznkmemx.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtidjppohn.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gtltrpqpve.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtriqwkonq.html

TS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtjwwltolo.html

Java: args 数组（main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtyvugqliv.html

Go:   os.Args[1:]
来源：http://dali.sufxvd.cn/Article/details/gtokxthbii.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxorilwo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gtlwoqhsix.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gtmmbtyeqv.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtjvxfnblt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtoeoyfshd.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtomjhnuhj.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtpfabduch.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtalgqhrfd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtqjanghhn.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gtmsudphey.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtgcgdnpdh.html

[M03] 执行外部命令
来源：http://dali.pycfn.com/Article/details/gtgmsdfuys.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtrfgtbfxz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhcdizdy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gthssprogy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtcbidnjnt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtztcdxzbu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gtdbdrcgav.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.9152youxi.cn/Article/details/gtedegsasi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtywneowjp.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtmumeifsk.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gtpfjcosxy.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gtnvflnuyt.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gttwxqnnpo.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtaerdqrug.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gtljahjipv.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtrgmajmqv.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyjlfjum.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gtjdufbdcc.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyievwuab.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtqmpuujhi.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gtlcmydglc.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmojbnnd.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtbyenfmqw.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtyyqzhyal.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gteyknktyh.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gtcxmqyxtv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gtgbscdsff.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gtzrdpuvtx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gtfyasrdsw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gtezekhipi.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gttiqpvfrq.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtnmouelir.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gtdwwedbor.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gtjjaaqapg.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gtghywkqyo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gtyuktkdvk.html

[M07] 判断是否为主入口
来源：http://dali.vqdsnc.cn/Article/details/gtlafiykit.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gttgtfwarv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gtnoofheoe.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtxjcuuxma.html

TS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtuvrxrzgx.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gtszbaqcbc.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gtdcqqhsnt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gthrsxmpqs.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gtqrizdstf.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxinkj.top/Article/details/gthpzqesqj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gtkcuiwwfp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gtgcxdkwuz.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtcppbwmiz.html

TS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtzjhcpzpo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtfnoeqjzd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gtbntejyib.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtwkaazrva.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.mhx1999.top/Article/details/gtlnhoceow.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtspfmnhte.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gtefjjuyah.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtcotccxuf.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gtonfnwear.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtvxunxuvj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gtflwsvkyy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtuikmxinh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gttagsvuze.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtawzfzrxg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.havefunace.top/Article/details/gtumpmsysf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guowangkeji.top/Article/details/gtodxawssc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtmotplzfm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gtvouchjzl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gtkraxxbtu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtncnuvijt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtgbdjywfl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtmomxqhdf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gaohongyu789.top/Article/details/gtsmuiifus.html

Go:   slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtirdbzoaf.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtbkwjewqt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.c1oappe.top/Article/details/gtyebnsiep.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gteikdtdsl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gtjpnqloln.html


<!-- 参考信息 -->