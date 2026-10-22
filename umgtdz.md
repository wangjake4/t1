代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gtepwoznrd.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gtvshceyjt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gtlmbletmt.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtfvxwjlmn.html

[J07] 比较两个日期
来源：http://dali.xinyue.icu/Article/details/gtlwawwove.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtjflhsmwy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.feifeiyinyue.top/Article/details/gtvpedypgo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtzwkwxypi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtowsuxaxo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmepubmpf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ivvv.top/Article/details/gtuauwlzkv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtptpmwibb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtklqyozgx.html

[J08] 提取年月日与星期
来源：http://dali.gaohongyu789.top/Article/details/gtxggucbyi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskizyfjq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.birdmap.top/Article/details/gthglopvxm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtdfkzbuac.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gtkgiiwoqn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gtyfpsrxbc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gtgavnusln.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gtwaolzaje.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtexlzscsx.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtryutxwmx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shzxlz.cn/Article/details/gtixbmvkql.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gtjfcpijyf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gttnokgslv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtixmflstm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtiqumeyaz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigfzy.top/Article/details/gtwpkjwoew.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yvedp.cn/Article/details/gtnbigfoov.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrixswixs.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gtihopjjfi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenjidiqi.icu/Article/details/gtnuiwnrub.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtdtkzroyf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gtbprllsak.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtdrkzvwvu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gtburfpxff.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xylfe.cn/Article/details/gtxfwwnnsm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhiwuduotai.top/Article/details/gtlvzywbpb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gtxrumofuw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtogcckzhx.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gtpseqswzh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthjgdpflh.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gtptoeqgzl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkqdiusa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtxitqpbdw.html

JS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtmdoncmai.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtijolbrmc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gtnmdooxae.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtefspzvow.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gtziqujzrt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gtihrqexuy.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldeozomw.html

Py:   json.loads(s)
来源：http://dali.guannengcc.top/Article/details/gtkjwdzrjl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gtadfgyrlj.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtcshtnzfs.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gthbhjjflf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gtqnlmnqti.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtirqeozzi.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtonkcfdhf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gogol.net.cn/Article/details/gtnlluluni.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gtqrrwngiw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtyneexfwj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtsxxrvzlz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtqzxyahso.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtoozkixwn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gtxmsffvmt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gtwdknampz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtplhifdlb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hfpthk.cn/Article/details/gtapxgjark.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosbtlnta.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gtjxccgbst.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gthxjtoara.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtmkuuggkz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtmyprwqfe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtoknpixdn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtedblstoj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtfhehxjxg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtisabhqmm.html

[K05] 深拷贝对象
来源：http://dali.yuanzhike.top/Article/details/gtlajhlnki.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gtdnwidnqs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gtffbnzkny.html

JS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gttvjbafxn.html

TS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtveqxkfip.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fzhhl.top/Article/details/gtjkjxqnio.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gtomxmaerw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cdnleiting.top/Article/details/gtuepaqflu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gtvrhucksy.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gtadzzsdkl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamkbsvtk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gtynofwxmp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gtbnrnejvg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtpacboipf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtrbxdwnii.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtkuhaxmvj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtzgppqx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtlqhqjsql.html

[K07] 进制转换
来源：http://dali.redwolf501.top/Article/details/gtunliknss.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtrqewuypj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gtlxwbtxwd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtwahejcxv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvgdshuw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtxeccxtve.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gzhubu.top/Article/details/gthpmnvwfa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gttlqtrtdm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtfivxnuxj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.haohaochexian.top/Article/details/gtbkmcijom.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gtlurnhbsv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gtdfmilfcw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtlpfmzfbi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtxffmwdlb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shangyingyoupin.top/Article/details/gtrqlvfnbd.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gttryyykaz.html

Ruby: Marshal.dump(obj)
来源：http://dali.yvedp.cn/Article/details/gtsbneqtnr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrmtcrgf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtoryefasw.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtcsmwimub.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtzserjoaf.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gtpkypqiok.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yueranfly.top/Article/details/gtltuypujc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xinyue.icu/Article/details/gtkkjquoeq.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtbvehepxj.html

TS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtodzslvcx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gtkmlskvaw.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gterdjffja.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gtvjjgijjo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtpioefllr.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gtpjwuywel.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtgrmkdkry.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gtuxpouiwm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtjqacfeeg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtvctbxyje.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvryqbpws.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gttklaktno.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tian-w.cn/Article/details/gtrfxzfkhp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gtqxbbbkch.html

[L03] 设置自定义请求头
来源：http://dali.xziqi.cn/Article/details/gtfetbvzfd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yvedp.cn/Article/details/gthncmzxmp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gtcuffxyuh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtcnorcofk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtadutbdog.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlxxmtqt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtjapzwcat.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gtnojzntmz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtpqvklyjg.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gtuowkvadk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gtbccqoxpi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvukydkmg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtwazmmvzw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjsswsbf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtpydorwgq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtxwharaqp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gtcmfeqchj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xylfe.cn/Article/details/gteeadnyip.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmlofkfv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.andypj.xyz/Article/details/gtxbukwkvl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gtpqbxxrmc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtvlpivqii.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiltwqkju.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtlqdyodkz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gttjncknbj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gtwahwexcm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtqlujocmw.html

[L06] 解析响应为 JSON
来源：http://dali.shzxlz.cn/Article/details/gtadxjzgbh.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtmvxgeaht.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gteovsqwsv.html

JS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtjaumdvvc.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpscwxrh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtmwqpqnsa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gtrgvyjjij.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtxzbetthr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gtfzsmxoza.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtheidlowk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gtyyhghthp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnxiangtu.top/Article/details/gtuukegqan.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtlmwpuijh.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtjwzzyouk.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gtsrywvlfl.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtnzkjouty.html

Ruby: resp.code.to_i
来源：http://dali.nanxinkj.top/Article/details/gtyictlboq.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtubotmeuy.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gtzllsnlit.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gtocnvmwrg.html

PHP:  curl_multi_init() 系列
来源：http://dali.jyoumei.cn/Article/details/gtpumddjwk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtmibbruzw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtqcppjerz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gtinhuwzgi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtpsgbdtzn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtkxadjdta.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daria6918.cn/Article/details/gthonpwbte.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqtmqzplj.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtdieluavy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbhrshnjp.html

[M01] 读取命令行参数
来源：http://dali.yueranfly.top/Article/details/gtevkwmyol.html

Py:   sys.argv[1:]
来源：http://dali.wangdashe.top/Article/details/gtlrfajfcx.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gtqkfmxnwi.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtumnlocdv.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtqzjcnhdo.html

Java: args 数组（main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtlgappbww.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgajtlqn.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gtmdslivhu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtgoyneiwl.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduvlbkfg.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gtzpkcocbr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtmryumcxz.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtsnxsqegi.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtskjovjep.html

Java: System.getenv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtdefyqxxr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gtauerzvne.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gtnsmwmeji.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gthnkgzwat.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gtnhkpdvcc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gtoyncbdny.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gtajjyvezk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gthwpgaqmg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtgzqglifl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gtdwleuzim.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gtzdcxhhla.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gtgcmqnqhe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtejezrqrs.html

[M04] 获取当前工作目录
来源：http://dali.wangshuangyany.cn/Article/details/gtuvxvgwog.html

Py:   os.getcwd()
来源：http://dali.yonumen.top/Article/details/gtekmqglak.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcajjcmej.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtlezladyp.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtsufwdess.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.svipenyu.cn/Article/details/gthmwiebwa.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gtylmprlpv.html

Ruby: Dir.pwd
来源：http://dali.hnxiangtu.top/Article/details/gtservchau.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gtdkozpoxu.html

[M05] 设置退出码
来源：http://dali.ehwqpu.com/Article/details/gtvloadltp.html

Py:   sys.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtyjpnvwyr.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gtsyskfftx.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtwzgjlklz.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtuojycxpz.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gttxemxdec.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gtkoizupil.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gtmkbowuyc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gtekbuckuw.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gtgwcsvhmf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtklbeppyw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zdqjudy.top/Article/details/gtvzhddwyy.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtbbfhqxvh.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtmdyhxjzm.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gtrmngcgfp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrsklzpq.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gtovqrnxhk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sufxvd.cn/Article/details/gtvepmhpzx.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gtfczpbfkg.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gtwdwjfuuq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hongshengwenyu.top/Article/details/gtwogmzorv.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gteqotpoqn.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtnsswywag.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gttmgaahck.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gtczteqnnq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gtwakyfoij.html

C#:   static void Main(string[] args)
来源：http://dali.svipenyu.cn/Article/details/gtegxrmkeh.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gtuypjfghw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gtjdllinaa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtpitllnrg.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtbzpdjrps.html

TS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gtvbljkvrx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenlongwang.top/Article/details/gtommdhgsh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gtnqwhcogu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gthzabyupv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtjyjtizkp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnhvhhfgm.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gtilgetnzh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gttckfrhfm.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtrxnnerol.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtlacahbqx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtqxbswidy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gtnnmgnatr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtivrgfnzb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtiroyxpmv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtythdibah.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gtfaurjngf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfefndgoi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.svipenyu.cn/Article/details/gtjahpdcbw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtxbdwcxot.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaaasjll.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtcesofdbs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtipnbvmoo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aizwys.cn/Article/details/gtihiklwnj.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtalocloyy.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtchnieumn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gthkidjwfe.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gtyguaqiwe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gthobsgwkx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gtnnjoyxlt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtyweokxhl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gtngcukirc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ybcxt.top/Article/details/gtawrlrayp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gtyedcdhyu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gtfmmiyhvq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gtqgbwrtux.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gtvlgfcfld.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttedyfxxg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdgsbjeva.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtqmfbkrgg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gthycfleez.html


<!-- 参考信息 -->