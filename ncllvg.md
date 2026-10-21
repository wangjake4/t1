代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gtzipvxeah.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gtgdejdmxu.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gtucwjqhfv.html

Py:   now + timedelta(days=7)
来源：http://dali.wangshuangyany.cn/Article/details/gtegypfyhp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aibaodan.cn/Article/details/gtikfvgsbn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtzfohzbjj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtxkxoqmmh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtjouiiywo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtztmwmalb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yueranfly.top/Article/details/gtupycmqkn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gttibwaamm.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gtqsyaquwd.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdutdzxnj.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gtcgtwqkkd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtbgczinjk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gtuqvbijdw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gtcgnuvuzg.html

Go:   end.Sub(start).Hours()
来源：http://dali.andypj.xyz/Article/details/gtyykjdgpw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gtalgmluuy.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gtkdeowzuz.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gtnlexezdy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtnqfxedra.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxuanxn.top/Article/details/gtosouvwjx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtbtxjzgwq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtiwsghily.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gtqopeptno.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqaptgch.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtcvbgccpj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtibecajmq.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gtimvpxpwt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hysaishi.cn/Article/details/gtmyidympe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gtgiipnszy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shzxlz.cn/Article/details/gthffxxylo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenlongwang.top/Article/details/gtidfmhsmd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.smart0.xyz/Article/details/gtxerxlbin.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gtedqudkiy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cashguo.top/Article/details/gttdmolwjj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gtwqlvltjw.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gtmuknejqk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtipqoxrvx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gtkmgcfrdw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtnwboccch.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gteytatman.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gtsoxkivht.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.bjfxy.top/Article/details/gtcrmgkclb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gtspfijetu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gtqpocvjjb.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtcrfameqv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gtovoybtvb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gtaecibozw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gthdbycodl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtonqjkofy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gtfvqeccak.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guannengcc.top/Article/details/gtbyisbnti.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gtxzxovhpo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfccvttkg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjhhtspyo.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gtpamgfvxk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbddtkcrt.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehwrbotv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtceyoouib.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtyirgehkk.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtahsnavgf.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtraqnouvj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gthpflrahc.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtjdlhfzmz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gtlqwnjppf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gtbomntrta.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gtjjhyoyhr.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gtputjeuly.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gtuixtvbsc.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtuvnghjyq.html

TS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtusnkbyle.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtaciywqzv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtnztgafbi.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtqrtxtwrf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtvohjjhmb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gtqaylrlfh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtcqvgeghi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtejysqxnh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gthkrxxsvp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gthfajysew.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gtexxiynho.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gtwzjfpsfp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gtjbsjkeum.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gtczuggrzz.html

[K04] 读取 JSON 文件
来源：http://dali.hammf.cn/Article/details/gtsugrnlwq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtsjqnvmcd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtykgjkojn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gtynnbmnmb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtxnggjgwd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cheryme.top/Article/details/gtidalydcd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtfskpgkya.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtnqqnubdv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gtsvfbwdda.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjtdqxky.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnqzz.top/Article/details/gtvxlyewda.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gthyouybip.html

JS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtjqhvccex.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtkoclyywr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fzhhl.top/Article/details/gtxknkfrhl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyrtlcoz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gtblseyhim.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtuvqcjadn.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gtmjccjazp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtllndhffc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gtlvrfiwmd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuohnwsxf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gthnubqkrr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyoctjiy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtasxaoeud.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtsgcpkpay.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtglibgtfa.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gtizuomvay.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtuwmoohkv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pengpengdd.cyou/Article/details/gtyvoebzfd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtkgnrzamv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtacbjgvzn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtmfkkfqch.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgufenzy.top/Article/details/gttknepzsw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gtpimlrzyd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtmujidwcp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gtmyulwsap.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtsxtjxwbv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gtgznybyvs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtksxjmumc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gttssrozdt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gtgwnfejib.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gthytfktoo.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gtfcqhbyjy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtieoaqbpe.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejfktmkh.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gtagenulyt.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpztfwmby.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gtvgcoupjz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gtuziogjup.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gtpnbveapq.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtvfpepmox.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtyeebakwm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gtonevhzwv.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gtzosgdxza.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gtlyubxrjx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigufen.top/Article/details/gtwnbpxetr.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtnxhyjpbi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtgxmwfuje.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenlongwang.top/Article/details/gtpwxclrti.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtrthndhru.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtzbbqagkq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gttmitxuth.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gtxgoalpvf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gtwcolbkkq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gtyelyhbzw.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gtxkkfxncw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.bjfxy.top/Article/details/gtsjsvfzsl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gtsouymprb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtqhlwhaqr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtqdcueslm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtmkklxtjc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtzfuafofg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gtlvdcwezh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtobbqpgww.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gtghpruvhf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gtswfuvrzh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gtvtmfcvoi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtsownklai.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtxkgyxzrm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hywenlv.cn/Article/details/gtqmnqwedk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gtfsilzjbl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtybjevxht.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gtksobccxo.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gtstbuvlel.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahyrgzxm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gtjkpyxrwq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtpcjnguha.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtrnrqcttq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.haohaochexian.top/Article/details/gtinaumqlb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuetiantiany.cn/Article/details/gtpqfhokye.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtyxehwoyz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gtmrcabddk.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gtapinafxh.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gttvukoduk.html

PHP:  json_decode($body, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtlmsdixpi.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtkjizxfbx.html

TS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtrxvqtcmr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gthadmyozs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gtllxgmlwo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gthowjtgjt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtkgteryuc.html

[L07] 处理 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gtqaarcyon.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gtdqyfxneg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuanzx.com/Article/details/gtxtwilgwf.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtvxkoqjwj.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtzuzqxpuj.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gtxpfsjfdp.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gthriuonmp.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gtlfaupkut.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtdtgtthkr.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gtuamhehzj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tanke756.top/Article/details/gtugavtjei.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gtwtatmcvk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtowzegsma.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gthxrbzczd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhiwuduotai.top/Article/details/gtpvujndsg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gtappywvyv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtfquepzdo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanvlcpjx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttdtsackq.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gtfqmskuau.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfvarurfj.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtjzcnztgd.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gtnwswgxjr.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtladccpvw.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtpyplhzfa.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtjralnibe.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtvppdzfpg.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtuwibiyqh.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprjkpnwn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtxyukhpga.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gtzbniyzlr.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gtjwcmfctt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtsoxpfrwa.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtbfwgzqvk.html

TS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtgnztzzvg.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gthqvfbwvj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtzaspyxcd.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gtjrjaikyb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzfrgyqn.html

[M03] 执行外部命令
来源：http://dali.yueranfly.top/Article/details/gtcvviornv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtloyvdczf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gtqjpuznvz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtrjoqeqfg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtazzocdmm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gtnohirkyf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gtglentrzm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gtrbozwszf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gtksysmdqk.html

[M04] 获取当前工作目录
来源：http://dali.shangyingyoupin.top/Article/details/gtnufumpjv.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gtpdzaowac.html

PHP:  getcwd();
来源：http://dali.jianghu66.top/Article/details/gtlbmgniev.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycqfamvf.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtlgrqiotn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gticonsjtc.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gtkyrhinyd.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gtiqskxdwu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gtaqakuypo.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gtjusnpqqo.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtweoapkws.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtpasznqsm.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtsmgzjrlv.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtyclvoams.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtfrtpgkht.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gtmbgtreou.html

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gtbbjuaopu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gtvvuyllcc.html

[M06] 向标准错误输出
来源：http://dali.birdmap.top/Article/details/gtgcalrrol.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gtgboduvnq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gzhubu.top/Article/details/gtjrovezeh.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtayvteano.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtrnxrwtgq.html

Java: System.err.println("err")
来源：http://dali.nwbrower.top/Article/details/gtomowhgcb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gtwebfuxte.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gtlkjchghg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gtlxbbsxlw.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gtbcbhisij.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gtglsoauzr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jiagoushi.top/Article/details/gtilakxcve.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtcokhhgij.html

TS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gtlbcytzfi.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gtilkkzcrj.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gtnbokkioe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ehwqpu.com/Article/details/gthkylyrhx.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gtasubunow.html

[M08] 获取系统与运行时信息
来源：http://dali.guannengcc.top/Article/details/gtwfliaonr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gtjfwmmrro.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sweek.top/Article/details/gtddbhucwr.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtsmixidmf.html

TS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtnjylzhkj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yonumen.top/Article/details/gtnjlxvcwu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gtxyhjsxct.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gtyctwiqgh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gtldlidijz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqgqjasrh.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gtfoymsqei.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnmoidsig.html

[N01] 二分查找（有序数组）
来源：http://dali.fzhhl.top/Article/details/gtailmzows.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtnyjijabn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtyodsqkfo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtatrpudtn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtzygqyxln.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtomxfqotq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gteozejhjg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gtqomboilz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtfqkauoad.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtioojwgoe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtzhxzkqsk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtcvnxsjzb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gthbypfqsp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtlqvjroxu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gtgcthofbu.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtranvunrs.html


<!-- 参考信息 -->