代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtxulmnend.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtzewiezad.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtlztueomo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtlhwtcxfx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtfoqwgizt.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtdikhazem.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gtxkeyoxst.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyohfwol.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.meibo888.top/Article/details/gtslhbphpt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gtiuwuipnm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gtihzgokbq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.9152youxi.cn/Article/details/gtjssoirir.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gtejyalsce.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtvuttkrlx.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gtrjmzmcro.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtxkqyewqy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gthwmyzksp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtzbdiztpe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphngyrsw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtrkwxicrj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gtxbhowsag.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gthoghcrmx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtqjgyqgmd.html

[J06] 计算两时间之差
来源：http://dali.daria6918.cn/Article/details/gtbydtqjer.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gtbyrdkzba.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gtjmbgahov.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gtivbrpfum.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gtptbljkfn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtkovynrrr.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gtldamjcss.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gtlplnufms.html

C#:   (end - start).TotalSeconds
来源：http://dali.sxryk.cn/Article/details/gtvkjbdotb.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxytnvmo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtsivfwlnj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gtgrmjkkff.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtlxbhejmd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtxczdkzuq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nwbrower.top/Article/details/gtosatrfvx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtffrderzk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtugqntigm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtynvkozbm.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gtonoyiuqc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.birdmap.top/Article/details/gtrruqrhga.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqyxzhag.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.andypj.xyz/Article/details/gtvihpulnm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gtdsqpfamv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gtjwxamewm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gtgvfkdvjl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cashguo.top/Article/details/gtywcuaiii.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gtwiamkhce.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gtoriocofy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ivvv.top/Article/details/gtbnvmpqdt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yvedp.cn/Article/details/gtowauqoat.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtnuihgthe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtdajegsni.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.bjfxy.top/Article/details/gtxibemfje.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gtasteameh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncenediq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkzxrkom.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gtwwjdumcw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gtcdprrcdh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gtfgubymze.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gtcybwhgin.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtuhjtcwmg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gtkdgjcvwd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ybcxt.top/Article/details/gtmpmgukud.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gtnxybjeli.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjscnalw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvsqsmchk.html

K. JSON 与序列化
来源：http://dali.birdmap.top/Article/details/gtmfeshxdj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtrcsyqjlj.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gtfpbbrdsg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtmanzfgdj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtyoqbmdbk.html

JS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtyuwqejth.html

TS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtxyfbxavz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gtqddgcnlg.html

Go:   json.Marshal(obj)
来源：http://dali.jqgfzy.top/Article/details/gtsgpszhea.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gtfhqwehoy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gtvdjwkhwq.html

[K02] JSON 字符串转对象
来源：http://dali.tanke756.top/Article/details/gtvpgxpcbw.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gtayssctvj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gtnxcmqfcn.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gticylejhf.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gthpvzrsgn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtkjhxpjiw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwjneoae.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtegjpcmos.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgfzy.top/Article/details/gthkiyrkfg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gtlkemkote.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtfnnxurao.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtoahhkfuv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gthkwtnavx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gtqfpqrwkr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jyoumei.cn/Article/details/gtumwyslmi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gtgqvdewnz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gtzmljkohq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gtwnhiookw.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gtjytfdmhu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gtffhltndm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gtsxpbryzz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtszvcdpje.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtawjicpbh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtpazukqct.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtlgspvnuc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtvpsccmnn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gtsxbgtqpt.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gtyjaqfkit.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gtnpumfpph.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gtqziczcph.html

JS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtfvlqeihj.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtaaysttwe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gtkhnapfeh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gtuforrfjo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodivmcdu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gttkbojxwr.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gtkzurkrom.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gtjszvfmpq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gtlepycbgo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gtptrgttns.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtjcfqighh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtbppqpvch.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtbudwlnjn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtxtlfmafz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gttqmyrvak.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzofxuxgd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtxbdvlqjj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gtjsxmrvpq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtyystwsxh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtlgcwzeip.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtagnzlmqi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigufen.top/Article/details/gtuebjjmem.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gtkciawblg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtiwkoywbd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcystcyrv.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtwrednsdi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtvqagwjwb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtvqnwgdmd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtcmezkzxp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.0kj1m.cn/Article/details/gtwwnxkiki.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtvsiazorw.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gtuwiryzph.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtjdqezeps.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtajstmwkx.html

L. 网络请求
来源：http://dali.mhx1999.top/Article/details/gtynrnsemj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtnyihwcxg.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gtbouaqwyd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gtkqxlqfmy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gttdqnrgpp.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtekpsppqb.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gtlkvtagth.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gtuzvmnfgu.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gtwvkjnjmd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gtzprimzvt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pycfn.com/Article/details/gtmujesrzy.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtrjhzmtar.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtjqwlmycm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gogol.net.cn/Article/details/gtaurbdeaf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gttnvozssx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtlxsksrbb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gtzgdplqvn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hysaishi.cn/Article/details/gtdzmbmkel.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ybcxt.top/Article/details/gtowvrzreh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtixzjmviv.html

[L03] 设置自定义请求头
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwgrntgt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yvedp.cn/Article/details/gtwhippafe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zdqjudy.top/Article/details/gtuctzzcld.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtjtbrsjzc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtlceynjxe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gtzffdihzf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtihevuocc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yongpay.top/Article/details/gtparcpxpj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gttwhohsml.html

[L04] 设置超时
来源：http://dali.shuidangran.top/Article/details/gttsbhgdow.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gtordpwchc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sxryk.cn/Article/details/gtmgxdmlzo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtuvuboklz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtsffgxnpw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gtrjcyzvnz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gtrcnazeky.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aizwys.cn/Article/details/gtpsuvcuku.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gtkfwmcnxb.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gtuloagywn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gtwqokxqww.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gturlkuizm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gthmmzcakr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtmtdvaata.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yueranfly.top/Article/details/gtgkvihbvf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhiwuduotai.top/Article/details/gtoyfseiok.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shangyingyoupin.top/Article/details/gtgodxmids.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gtrljahctp.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtubkgczfm.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtseleplxx.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gtglnotkak.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtgckxnfme.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtiodcusde.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtwdtgomew.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnqzz.top/Article/details/gtgmapinjx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gtvtnxynpa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvwmnhka.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtevkobzkj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gtrcpdbztj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtxhgixcic.html

JS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtabjgkyfy.html

TS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gtdfflxfmt.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gtyirmssqz.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtxssuhqhg.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gtxwivqfyt.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtpmlwlrle.html

[L08] 并发请求多个地址
来源：http://dali.zhoulong.xyz/Article/details/gtxpohpftc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gtoclbgubw.html

PHP:  curl_multi_init() 系列
来源：http://dali.jyoumei.cn/Article/details/gtoouqurru.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtelcnnegh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtfvhwbhqh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gtdhwwhnkz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gthjdecepw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtakkjrmca.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtvvoefzks.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtfomqjfum.html

M. 命令行 / 进程 / 环境
来源：http://dali.hongshengwenyu.top/Article/details/gtixhpygpy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtknuetjfp.html

[M01] 读取命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvdneqge.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtgccoiovf.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gtulatimjr.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtqzctxtyc.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtfxuvvwbf.html

Java: args 数组（main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtgnrcnulg.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtyujkacub.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gtdlrywjqd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gtzbzeeifj.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtauzpgqar.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtvxjhrnfz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgxihbtr.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtatosimeq.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtiiwzexwk.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtdseunlvw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtnfybchgm.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gtueiufbkh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtjbabmwci.html

[M03] 执行外部命令
来源：http://dali.jqgufenzy.top/Article/details/gtuxgminvt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gtjdexdzmg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gtnmugdkpl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtnptcsivu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtkwnrmscb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtfxwfmnls.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gttmhkbabp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gtoscvzrkz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtttmdwrdf.html

[M04] 获取当前工作目录
来源：http://dali.jinqigfzy.top/Article/details/gtgetwewbd.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gtakcpippv.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtecvzfzxj.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtjkwedglv.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtfxzrcxvf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yongpay.top/Article/details/gtqccvzrwn.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gtugvifutw.html

Ruby: Dir.pwd
来源：http://dali.cashguo.top/Article/details/gtvevyzlmp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gtcdztoptf.html

[M05] 设置退出码
来源：http://dali.hywenlv.cn/Article/details/gtoiupfcqh.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtukfwbmdw.html

PHP:  exit(1);
来源：http://dali.yonumen.top/Article/details/gtewvwilxq.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtkpthsquh.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtbyqfhwcl.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtmfnkzmax.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtfraswtfk.html

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gtixlbmnac.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gtjxvlexmn.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtwyghfxmp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gtypjqrvzs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gtttghkyqi.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtnovlfgbk.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtwnznmwpj.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gtfmjvowxp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xziqi.cn/Article/details/gtymnjbhzq.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gtgsusyqjo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gtigcpjlqn.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gtmzgolnoj.html

Py:   if __name__ == "__main__":
来源：http://dali.iojbl.cn/Article/details/gttcmfnlnw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gtggksovsi.html

JS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtzmnnpmks.html

TS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtkfimatzz.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gtlprbdfcv.html

Go:   func main()
来源：http://dali.xuanzx.com/Article/details/gthkmfrkxl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gthwoxfwsy.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtzgswaqss.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxuanxn.top/Article/details/gtshrzkqhr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gtxoogemjt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygeelbxk.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtfdbrucui.html

TS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtqwxysuxr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gtmtlyzcql.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gtvwdqaqfn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gtgbqctuen.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtqteorjsq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtofxmeulv.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gtlobvlilu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtkrenmewu.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gtqkzngzyp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gttkeqnksz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenlongwang.top/Article/details/gticwwlokw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtkxpmrvkb.html


<!-- 参考信息 -->