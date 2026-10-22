代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gtzfwjndch.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gtctmjhlbg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gtytcpwhtj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gtgdxbhotp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gthoivfaoj.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gtqowcleep.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gtuvqtgmhp.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gtxofeshwd.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gtbittaezh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtdtarjdgq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gtgcthmtvu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtwwotbjtw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtunemiczm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpjfjigv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gtfmjrempi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gthfkyqlvz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gteatexied.html

[J08] 提取年月日与星期
来源：http://dali.sweek.top/Article/details/gtsfjbpezn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gteybntjzk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gthdglqjzy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gtaggjehdr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gttpyvsgtr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gtziiqskrl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuanzx.com/Article/details/gtesarrufg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gtjfzoalje.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtokerqmli.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gthsmtvwon.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhongyouzk.top/Article/details/gtvbohuvsu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.0kj1m.cn/Article/details/gtkqkrwmsi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgiconatz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtruviadys.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gthhhrbidi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgyqcack.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gtlqvqamuh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gtwbvrozzz.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gtvdthgror.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gtmjdgrfas.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtjcqifrzh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtwesrnyjq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gtbyvlvkch.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gtpsizpjkb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtumrbigdr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.redwolf501.top/Article/details/gtyynfmsgu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gtzxrlwzwf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtinpzmjpi.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gtcxpgxgcd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtnuiypyps.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gtpgdijlkb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtouggsvtx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gthawswvda.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gttjeqeuer.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtyadggbdv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gtvvolyqtr.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gtakapfsal.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gtkrqzunrk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nwbrower.top/Article/details/gtiwbthofy.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gtaayifrdb.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gtktbfzymm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gtzvtwmmoo.html

JS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtlxzfymwm.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtudoruaxa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtxxfdwlgo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gtodtvruvw.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtadvipzwj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gtqzemmznk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gtuomcpdob.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtfvdabgql.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtowijbvel.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtcsgkhwku.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gtkqkdxznk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gtedpsvhkh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuvmpvib.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtillphofp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gtdhdspvhh.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gtqpizurna.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtlkizslvw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gtvefioqqd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtvtrxbszy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtnqrlozbh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj202588.top/Article/details/gtiohktqte.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtrnzmjlgk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gtstxjczhk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sweek.top/Article/details/gtlhoobjzq.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gtpkfpvyiv.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gtcaqaagin.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnqzz.top/Article/details/gtvlrqkope.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtlkvkccol.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtbaehyilp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gtvidopako.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sweek.top/Article/details/gtkeasspsy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gtehowzycd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gtahaeztiz.html

[K06] 解析 URL 查询串
来源：http://dali.0kj1m.cn/Article/details/gtsuzozvzq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gtjkozmlzr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gthjoeivol.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrxwqocs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtfmlucnic.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gtumlrsbzx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtsonzuitq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtxbabyltx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtekupbhqo.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gtabbrbozh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtgiatrjve.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gtwugqrfao.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtehawzojj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gthtpbxoop.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtqrlnirql.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gtvlpeekyb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gtumxcggcw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtugqqawyd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gtsrnwwfym.html

Py:   pickle.dumps(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtkkxdrugr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbgxvexs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtlhgnavyr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtmnliwfxf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gtdlctrmhj.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gtebgdjquh.html

Ruby: Marshal.dump(obj)
来源：http://dali.andypj.xyz/Article/details/gtjeubwjro.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtyciinfes.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtakrkqhgd.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gtnasnswce.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtegpsvbhu.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gtnckjttcr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gtotjaqelg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ivvv.top/Article/details/gthmyayibl.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtowayxilt.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtnevsegrb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gtwrpzqmvo.html

Go:   resp, err := http.Get(url)
来源：http://dali.zdqjudy.top/Article/details/gtcomkotye.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gtomnxsjtn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gthnwbshak.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtlongdhex.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtxtmqyrgi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.9152youxi.cn/Article/details/gthzbvqbzg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gtsjvqtdsz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtpglnptra.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gtsjrhmsxd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gtoxmkfxlj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtsojohldu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gtkdixvvei.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gtlpletgsj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.316326.xyz/Article/details/gttanenmyh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gtiyzqsfow.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtchbdmthf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtsnyimwfq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zycfv.cn/Article/details/gthmquxzfo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtrvrdxwgh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gtlfqpeaak.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtmayizyha.html

[L04] 设置超时
来源：http://dali.nanxuanxn.top/Article/details/gtjgfcfhpe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gtayfqesmi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gtgbusskyr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtqcxbtqjp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtpfndawli.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ydzc1.top/Article/details/gtegowcobe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ydzc1.top/Article/details/gtznloryle.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gtekthqdye.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gtohcdvbie.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gtzzxrkrwq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hysaishi.cn/Article/details/gtjlbgkevj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gtdlojnyti.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtsfqccuxd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtlpxloaeb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gtaeaqenci.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gtzhfzbseg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.0kj1m.cn/Article/details/gtcehainsa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtzkxsqcya.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gtkfysuour.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gtobcquyml.html

PHP:  json_decode($body, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtaoduqtei.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtpvmycooe.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtzktbcdei.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtarqhvdqt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gtigykblla.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gtmecupdgs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dianchejie.cn/Article/details/gtcdujtyiv.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtowvmqjgx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daxiang520.top/Article/details/gtneoahbzj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hammf.cn/Article/details/gtcdxfvjsa.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtdyhlvhgb.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtqisjaagi.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gtbkxhpjzw.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtmcvbptjr.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtvyzmxpze.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtloqexhny.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gtitraruxe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.c1oappe.top/Article/details/gtikuzcaao.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtbbsjmejz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gthjgdurnc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtoloxbnwd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gtkyayeqyx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gtdhfizvkj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jianghu66.top/Article/details/gtyedpbjnb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gtjbsbwpll.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrbcikbpq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zycfv.cn/Article/details/gtaungisiq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrvcnhnvp.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gtxcikmprl.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gtiownkawq.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gtxxfeuoog.html

JS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gtnqqazpvd.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtszsxbgbp.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtyzyysvzm.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gtpevxfrbe.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gtdaworkxc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtewfauvvu.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsndhbfiw.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gtdcchhkbt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtanddyvku.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtedtegdeg.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtlkbdwehz.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gttgnmlzlw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gterlahpiu.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gtuolnskrl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmofzcyjo.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gtfazngymu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gtiuznnqxd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtosceswvu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnywmdct.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtaltetvkx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gtscgkyggl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gthkpvjetc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gttzhgwvlg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtfsgkmtok.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gtkfzqdoao.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtklxwrrki.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjarwxgx.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtfyzbmuyn.html

TS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtfewtdjzr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gtoswbxxhg.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtrwoajgft.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gtdcsjwxxo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtcvmndxnd.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gtyggdqbex.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gteckbgdfw.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymhmrono.html

JS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gtbnbudfzk.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtjbmszoop.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqzrxrhlq.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gtxeobpare.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gtuejxinuk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gtqejdzkup.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gtnjxclvft.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtgziiklfa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fengsongda.top/Article/details/gttmntwzzg.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtcnufnvir.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtpvsvhamj.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gtmyeeopja.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gtmabdqdqg.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkvtmhqx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gtprhiyvhl.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gttxbnldso.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtvsxxusxf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gtxbxmxxwc.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtefuvblcz.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtqjgemmbt.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtlizkjmar.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gtdnyelnfo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cdnleiting.top/Article/details/gtzefmzsqj.html

C#:   static void Main(string[] args)
来源：http://dali.zhengqikj.top/Article/details/gtphomqxke.html

[M08] 获取系统与运行时信息
来源：http://dali.daxiang520.top/Article/details/gtcotddhke.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gtieypejmw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gtnoloykbp.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtkfkcpfvq.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgedznmog.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gtuibffibw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gtokbudkbc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gtscwqtpvs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gtvbhytnab.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtakjeuesh.html

N. 数据结构与算法
来源：http://dali.zhiwuduotai.top/Article/details/gtflwkywnj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtwmwhiftj.html

[N01] 二分查找（有序数组）
来源：http://dali.gaohongyu789.top/Article/details/gtshtimojk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtnaoortsf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fzhhl.top/Article/details/gttbyfiuhw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gthwtfgyux.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtzbgegrgg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtctbbdxxe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtlwdhudqh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gtvggwkqfo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtrwfybdam.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gteeirkqsa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtmiafzmtd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hammf.cn/Article/details/gtpdfsisoh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtdwrrgqlt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtmfajwvri.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gtkimjsuhc.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtjqzuoxtt.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtvizeufgy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hysaishi.cn/Article/details/gtojhhpskv.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gtoautfgkc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gtmqhfurzj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gtjudnqajl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtgrbrmzne.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtuzfovyrh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pycfn.com/Article/details/gtymwapznl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gtpmmlbrhn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gtuxdwrehr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zdqjudy.top/Article/details/gtemwcsalx.html

[N04] 斐波那契数列
来源：http://dali.pycfn.com/Article/details/gtveazdgis.html


<!-- 参考信息 -->