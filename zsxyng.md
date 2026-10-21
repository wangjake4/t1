代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gthmuucybt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnwlvwqu.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gtebdspkfo.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gtglgjpxkk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.feifeiyinyue.top/Article/details/gtejowudfv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtglagkzgq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtmbudeiov.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gthaxznfes.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgufenzy.top/Article/details/gtardkxric.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtzinnchkp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtuhwajtxw.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtyinzxkpp.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtusymngkg.html

PHP:  $end->diff($start)->days;
来源：http://dali.yongpay.top/Article/details/gtqrfmqfsf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtrgdglmdz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gotoacloud.top/Article/details/gtxtdgciyx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gtusjzjzet.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxinkj.top/Article/details/gthpqlbebr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gtvfwcpzgh.html

C#:   (end - start).TotalSeconds
来源：http://dali.vqdsnc.cn/Article/details/gtonojyhdk.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gtyzordkhh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtbsfjomgh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtmbosbfdb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtcymnozdy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtdxhydlyd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuanzx.com/Article/details/gtffeazxza.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtwcmqpskw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtnhmuyhzr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtyeqepzrn.html

[J08] 提取年月日与星期
来源：http://dali.feifeiyinyue.top/Article/details/gtnmuhgkmw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sufxvd.cn/Article/details/gttcgpzfvv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gtbbrzzhjr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gtceznyrpn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkzapirx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gteqdiiymp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gtwflkviem.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuxming.cn/Article/details/gtlbymklfl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gtcxwtixuk.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gtlxtdtnfp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gtdlylyvly.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gtdejglctt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtobtgjqoo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtnokavjon.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtdxaflfzn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gtfkwrgkkc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gtvsmpczmm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gtgdizolps.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gtickttwxk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gtmpreaegq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtuqjjqnfc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gtwcwfamwa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gttodbwqmx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gtbxhjwica.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhiwuduotai.top/Article/details/gtxezocpqm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gtllbszltr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gtxaqxppsx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtlobzpfvu.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gtsqdyjfrh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxpvznqyk.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gtnubdqnub.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtqkyojvka.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtgwipnpap.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtqamgnnlu.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtishqrzhs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gtvxqycmzp.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gtgkbinnjx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gtcjcyvntq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gotoacloud.top/Article/details/gtlxvynymg.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gtayitqtyw.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gtvflcxnqn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258888.top/Article/details/gtmkyojssg.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtitepxbfw.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtzhtbkfqm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtiuyhvliq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtsscvcqnu.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtisxfxxoa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.bjfxy.top/Article/details/gtkjrzsrjq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.birdmap.top/Article/details/gtxorpjiai.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtantqsume.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtylqtkrtp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gthueedaja.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtnkuccvtv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtthcxqupi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gtjsxtwfjd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gtakzqqpzm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gtgqincvcj.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gtikfaojjo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gtkuxuqtfw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gthagcpqez.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtixlyzbyj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtfsxgvmts.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtahdrcpmk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtjpqzgqbn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtsynjtkly.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtisqilxjo.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtiejpkkuu.html

Py:   copy.deepcopy(obj)
来源：http://dali.9152youxi.cn/Article/details/gtotcnvmpg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gtctziwico.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtculzwlfq.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtyqcxxczb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gtpaoomimr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gtklqvbwxl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtbhburikd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangdashe.top/Article/details/gtieuvouod.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gtonucmucu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtpbtlbnsu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gtrgsymifs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtnfgmpgoj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtmqlhlhwd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gtzsunzgaj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtwmwbfuyz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtobbeonex.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtlzvybjvs.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtnygwvztg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtyjtfbnoj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gtcanmansx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtzpdlrcsi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtkbrlpbtp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtowzihfpc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gtujshjswt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gtmezlrpsl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtkitvdbzy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258888.top/Article/details/gtbxoktwrv.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gtxwmdhgvs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigufen.top/Article/details/gticuoczkg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaqmavay.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtpbahhmyw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gtdawvmvhd.html

Go:   encoding/gob
来源：http://dali.aizwys.cn/Article/details/gtphcznbnb.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtupfzzhfg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtcqkiezzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqydagoef.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbwltwbh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtpglklbuf.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gtytdnifxh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gtctkxznru.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gtsgeseuew.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqosjxwax.html

TS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gtecgfyocy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gtyjjlmlnq.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofksfvob.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtynnroqdh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtnmbxkafw.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtzzcekfyj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gtssdqvwtd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtwdujclsv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtwycakzkg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtfiypcvmz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gtbuftngyf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.bjfxy.top/Article/details/gtlgguwenw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gtnaoaessm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnqzz.top/Article/details/gtaiuwzzar.html

[L03] 设置自定义请求头
来源：http://dali.hywenlv.cn/Article/details/gtkagykgmh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gtbcvwbzkx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tian-w.cn/Article/details/gtttcwqqhx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtnjbfalvw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtysltzrjh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtgjjlvkfd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtyvfkutko.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gtdwumtbxn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtakdzbdmt.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtjdzfkuvw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgfzy.top/Article/details/gtyrgaprpm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guowangkeji.top/Article/details/gteasyzflw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtvfczpker.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtyhdgugyl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtihfelxpt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gtmvyhwjfe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gtuhvkpbwm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gttthtknyk.html

[L05] 上传文件（multipart）
来源：http://dali.yangfankeji.com/Article/details/gtchpuofch.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gtxkhntpiw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gtiilfkioc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtsvuvavde.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtvinahtfv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gtwpojjzob.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gtweinapll.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtjsqohlkv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hywenlv.cn/Article/details/gteuifjaju.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gtitacfnwb.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwhrjwit.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gtzemxxhts.html

JS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtrezdqhei.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtegtamojx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gtnnoverma.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gotoacloud.top/Article/details/gtuxwtkwdu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gtdgmtchok.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjxxgjks.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtifahfvml.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gtfuyyohew.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnxiangtu.top/Article/details/gtacemxbdo.html

JS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtdjkjpknx.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gttwnpucxl.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gtfvxmhojk.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtatkmnune.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gtjirqipbd.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtsbzowjqw.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gtehaktqfe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hywenlv.cn/Article/details/gtakcuoobo.html

PHP:  curl_multi_init() 系列
来源：http://dali.hysaishi.cn/Article/details/gtkpcchyjy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtbwzopjjb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtebrtjeet.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cucudq.cn/Article/details/gtjajsijns.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gtkvannmkn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtvmhkaxhj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtzipqsbuk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtqnuijoaz.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhengqikj.top/Article/details/gtofcxulge.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkzwlwpbc.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gtvffeixjq.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gtjfoaqloy.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtoixgnaiv.html

JS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtmshzjvut.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtpehklokg.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtwmlxnoti.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gtnvzsvqrk.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtksrcvymm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtiumzjfvt.html

[M02] 读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gtgadyohyd.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebboqffj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtpqptnnoz.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtlkfkuwnr.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtmlexucal.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtoesueibh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtefwbforg.html

Ruby: ENV["HOME"]
来源：http://dali.gzhubu.top/Article/details/gtgfjftsba.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtkeaxceoa.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gtunrmdyhr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gthwfyqprw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gtwlznezck.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtntczwiym.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtatitvkmi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gtumvsddsm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gtmoslttzf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gtnfvqsljd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gtvvfrexyj.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gthuddblqs.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtjpawfhoz.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gtzjpcpxyx.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtmdpcwnkj.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtgmiwowce.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangshuangyany.cn/Article/details/gtozpkarkc.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gtluzjzvvg.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gtvfubdkru.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gtbwsznrfb.html

[M05] 设置退出码
来源：http://dali.shzxlz.cn/Article/details/gtvueykkvw.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtsqaqgebh.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gtzjwqtpcu.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtfcuaqnvl.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gttibxgkyg.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtuccxbfpu.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtgfwwamol.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnajwode.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gtuotjcfaj.html

[M06] 向标准错误输出
来源：http://dali.meibo888.top/Article/details/gtgzjulhcr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gtcteenbgd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cdnleiting.top/Article/details/gtogrtutfr.html

JS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtbbaxxbjd.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtkaylxtqo.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gtlmeikwtj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gtjuwvtvlu.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gtyskmvssw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gtibryfwjh.html

[M07] 判断是否为主入口
来源：http://dali.jyoumei.cn/Article/details/gtlvjiubxh.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gtmjgshreq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shangyingyoupin.top/Article/details/gtxyqpswsx.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtchjbkoyq.html

TS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gttkinldnz.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtmmdokhjm.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gtqapxuhgw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtcahupdmb.html

C#:   static void Main(string[] args)
来源：http://dali.nanxinkj.top/Article/details/gtvpyjzmro.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gtibeclsoy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtneqgkytw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtwhxrevjs.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtomrijfat.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtzpvbccuq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.vqdsnc.cn/Article/details/gtugliowpd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cqqwz.cn/Article/details/gtahykcifb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gtkbylyuuc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gtqsodatlj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbltdghgs.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gtpgyuujta.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtoqpndoyp.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gtsgbmvzvs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gttafluelt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gtymawslsz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gttoqjcsji.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtaztiphyl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtxuigngqv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtrxiglphr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gtcobzmlyg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtkxjgzosv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gtzvnobbqn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gturoynizd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.mhx1999.top/Article/details/gtsojsised.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtkreyklwh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtpubmanoq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gtdcxdyzaf.html

Go:   slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtwnlcspzk.html


<!-- 参考信息 -->