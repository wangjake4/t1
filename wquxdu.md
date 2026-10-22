代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gt2arovfwfb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gt2jzbatzse.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2bjtvfagw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2higphebd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gt2laysqyuh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gt2vpjgehnw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xziqi.cn/Article/details/gt2kuwgrpxs.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gt2webnlapa.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gt2iuvqepch.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gt2qolefhzx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gt2hfbdytxl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tanke756.top/Article/details/gt2edhazian.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gt2cqbfhpxs.html

Go:   end.Sub(start).Hours()
来源：http://dali.snrcjt.cn/Article/details/gt2jcuarajt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btavdpsm.html

C#:   (end - start).TotalSeconds
来源：http://dali.shuidangran.top/Article/details/gt2biykdnqx.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gt2cxyjddoo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2cgsyoowd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gt2kwrtqpkp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gt2hdbxqcqm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gt2qpordimp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gt2tvuytnvk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfziocsi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2davjxddf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gt2baqjqvyj.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gt2mthprwln.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sufxvd.cn/Article/details/gt2dpewuipl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jlsjyb.cn/Article/details/gt2hvvqrcgi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gt2zsksgdns.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gt2ohjhscoj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybwonfnk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gt2lumlrwnx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gt2bmgagail.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gt2xfvarvne.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gt2uigjtwmo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gt2qfavmcct.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gt2hjlqkkde.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gt2ipnquwfj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gt2fpggeggp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gt2gxxapset.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gt2ydegnsbm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gt2ywbczyvn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gt2hjfuypkl.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gt2fvqtsuql.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gt2ceorraas.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.snrcjt.cn/Article/details/gt2ejfslipb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gt2oeywcijz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2ntxgonpt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2cgamisrb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gt2wjmkgpeu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gt2vvvpwgsa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnaromxc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2rbpvniqu.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gt2uhujxxnp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2lmjdqxtc.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gt2tyrscvbd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2vneciyig.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwvjqeyj.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2xartolvs.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gt2fmzqxslc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhahlacz.html

Go:   json.Marshal(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2syghztuv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gt2vgdawdwu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gt2byntrijs.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gt2exocdewz.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gt2nnqwnclk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gt2hryjopyp.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2octozcmv.html

TS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2xhhgsgpe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgzmdisr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gt2qsmhajya.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2ogfibexb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gt2xtocvewy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gt2bpprjiop.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gt2ndnmbksf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2elfjgjya.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2bfuictfu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2vohhmonr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2qhzzwnqb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gt2aqshqgvb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2redhvpfc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gt2xdqabclk.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gt2cswwmidy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2uemgkezo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.vqdsnc.cn/Article/details/gt2tzjvwqvw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gt2xiuqgjby.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2kvpqttmx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2fbypxkfe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gt2elqupedc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtunqlsx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjzuqgbw.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gt2xkuaqeyu.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2qlbsxwfh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gt2qyvbixnp.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gt2yfsmebkx.html

TS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2yaxbhvze.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gt2szapgncl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gt2tcsxhiwk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzwzqeaj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gt2uwpukeay.html

[K06] 解析 URL 查询串
来源：http://dali.yuanzhike.top/Article/details/gt2llhmhqdw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2bmrmehzu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gt2gozenllq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2zyecpdzn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2hpgptkyd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnxiangtu.top/Article/details/gt2dpgyowbs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gt2jozxeqow.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2gflvnqiz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2ftqglfxt.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gt2hnogkyee.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2hrjaimdk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gt2alnfcuue.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2murbrdil.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2arfesith.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2fqvvwzmc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gt2ijtvtgxc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gt2xucxhczs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajfiykyo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gt2jxficdlh.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2rfukypqd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwqfkbxv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gt2vfneeqei.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gt2xxgoxgzx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gt2nxyozsdt.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gt2ndsoolui.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2mxafaobx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gt2mbgcslqn.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2iakhdejd.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gt2qeuqtgtv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2pxostabs.html

[L01] 发送 GET 请求
来源：http://dali.hongshengwenyu.top/Article/details/gt2fmpwcfdk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aizwys.cn/Article/details/gt2hdkhakbv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gt2dlhmiaji.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhdwgdfx.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gt2rwanteox.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gt2nemmrzgp.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gt2lkdtpvcv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gt2mimjydtl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2uuwaskxf.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gt2wxwbtekx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gt2gnhyryoh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gt2ivfyayyy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gt2egstjggo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2vxtonyau.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gt2waockigf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cashguo.top/Article/details/gt2jydtfcte.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.vqdsnc.cn/Article/details/gt2otqsigzt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cashguo.top/Article/details/gt2vjezowpy.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gt2ulamawto.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gt2csudmeuj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gt2kkbontoj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gt2kzvklqvc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gt2gfzmnqkf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gt2uugmqrxw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gt2fcmhubby.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gt2ijqgfgez.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gt2swymjsox.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gt2zahvxetq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nwbrower.top/Article/details/gt2tdwnwezp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gt2jpybwtch.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gt2iiaotkvx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gt2zsmzpuhd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gt2owbdtgma.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gt2zeknlksj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aibaodan.cn/Article/details/gt2magnbtne.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gt2ujbphfgf.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2zhqgevod.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hysaishi.cn/Article/details/gt2haeszdtn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gt2odgytmpu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gt2qngvrcha.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gt2zfdhffkj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yonumen.top/Article/details/gt2osfnseyg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fengsongda.top/Article/details/gt2cxhtccqi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gt2jqjslwqo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cashguo.top/Article/details/gt2ttwbtvdk.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gt2vrexymbg.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2ebseofzq.html

PHP:  json_decode($body, true);
来源：http://dali.cashguo.top/Article/details/gt2tkvyekhj.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2xjbpyesj.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2jmeypuqx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gt2rjvxmtby.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.redwolf501.top/Article/details/gt2urbrzssn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yothuvah.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gt2edfqpgqd.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eupghang.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.andypj.xyz/Article/details/gt2lxoyvswb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmjlkbfx.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gt2jfqlmeep.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gt2omfofmeu.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gt2kwsmltgj.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2fduuiogp.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gt2tasvkiek.html

C#:   (int)resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gt2rohbqtvk.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gt2iyiqgjuj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gt2taotkgbk.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gt2fwzfgkbg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdycvqym.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2yotvdtyq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenjidiqi.icu/Article/details/gt2urfeeesi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gt2boyxexuw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gt2tuhpbeua.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2iofuvfpp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2cjjbbrnp.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gt2kjnjxfbt.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2hdowkwkd.html

[M01] 读取命令行参数
来源：http://dali.yueranfly.top/Article/details/gt2ureiscum.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gt2vazozzue.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gt2dwyhvfia.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2lmybqepw.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lpbmkhva.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2meaorbwb.html

Go:   os.Args[1:]
来源：http://dali.c1oappe.top/Article/details/gt2gewrwgdc.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gt2vuknpzqh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gt2zgpqmesl.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gt2mwrqopkk.html

Py:   os.environ.get("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2hgxevmwa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lytvzred.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gt2geaqerif.html

TS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gt2dnzevxnb.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2xcmhyxdz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2wvplxsve.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gt2ntqwprei.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2dglavcke.html

[M03] 执行外部命令
来源：http://dali.cheryme.top/Article/details/gt2vpiwdwmm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gt2lzlmlkaw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gt2bupfttdf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gt2zxaislkf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gt2htlcrcvz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gt2yysqrxzv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gt2zwxwshpd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gt2qfvfhozv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zdqjudy.top/Article/details/gt2gbmhkybb.html

[M04] 获取当前工作目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsxlrcsu.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2eumgecrc.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gt2cdlqygoi.html

JS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gt2ivcynuxz.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gt2whsbmdbt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.andypj.xyz/Article/details/gt2nigunoha.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2snbwpdkn.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cstikvwq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llgpvzmz.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gt2wpwijvyr.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2hnrbpzda.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gt2isdpozsn.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2ajfkinjb.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2ozfwieyt.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxlbuoda.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2dznplssp.html

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2qoximxog.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gt2mdsrhsbw.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gt2nahprxxl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gt2xwuwrgim.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hammf.cn/Article/details/gt2fqwhjmcg.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2sqvecizq.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gt2qldpgpke.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gt2ktgstvuq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxinkj.top/Article/details/gt2nqkybiwd.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gt2uftxrkbx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gt2hcwykkvq.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gt2fyvjoeef.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gt2bwqdpzdj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.quarkkingdee.top/Article/details/gt2boxbyfmw.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gt2lqycoxsc.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gt2qovhawbh.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xakcyooy.html

Go:   func main()
来源：http://dali.chenlongwang.top/Article/details/gt2xelmpdus.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gt2mwvbyixa.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2wmsttuhz.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rajltchc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gt2dvqyyqjc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gt2gsdiwaoe.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gt2vfsalqua.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gt2fycfglrj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gt2ymvacloq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gt2pjrmnbxk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gt2chlnrplq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gt2vuqyzata.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2veywqtoi.html

N. 数据结构与算法
来源：http://dali.redwolf501.top/Article/details/gt2cpjbceaw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmzgjpud.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjufvodw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2lutemxkp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffncyojv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gt2dzcesslp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2vgelbyrq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2poiynknn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2ncxvchoc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gzhubu.top/Article/details/gt2qhqnpmrr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2tybxnulx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shzxlz.cn/Article/details/gt2kaujbnug.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gt2kdnkkenm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gt2gbdwnrtv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gt2gspqyiqx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2ueisjawq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bsguxdya.html

Go:   slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gt2wudwtxmi.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gt2ljldpbxb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gt2embfefkp.html

[N03] 快速排序（分治示例）
来源：http://dali.ppjwa.cn/Article/details/gt2oksqmuas.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangdashe.top/Article/details/gt2zbnmwlii.html


<!-- 参考信息 -->