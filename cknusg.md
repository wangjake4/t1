代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.hnqzz.top/Article/details/gtuqaplmtv.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gtsyureirx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gtjvftkjed.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gternfjchz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gtxsbvfqjp.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gtrfagjsyl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gtvkchrvdo.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gtuzrervcv.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gtwhqzsahm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtrrnuiyxu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gtsxqdcztg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtnxfkbsel.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtionnypov.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtvoilxswk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gtqyjrxxlw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtxnrubjbo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgozosde.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtpnsdapft.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gtwzzxauxl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gttsuyurrv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gtfjyqpoxf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ydzc1.top/Article/details/gtvlcirthn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gtzbistbml.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gtjnwngfjv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gtspoplvkg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenjidiqi.icu/Article/details/gthpozeofd.html

[J09] 时区处理
来源：http://dali.snrcjt.cn/Article/details/gtlntwtiha.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gthpxltpbx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gtumhadmvv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gtvlwvlcbc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlcukiul.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gtpjrmggvi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gtruykskge.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gtlqppecbm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gtcwceultv.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gtnyktynwn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gtbohgnyxz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gtwaglmxtl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gtahywtmku.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj202588.top/Article/details/gtaxpdydfg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gtjnlokxat.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gtgetqfotw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gtogtvpovl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gtwppntxjn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtaurofzgk.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gtsxoktoqg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemzrukpl.html

[K01] 对象转 JSON 字符串
来源：http://dali.hywenlv.cn/Article/details/gtigxgbpnt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtuwvernul.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtxjyrawof.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtounkorzh.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtbcwksril.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtitzbtkpc.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gtpfbawrly.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gtszfenxdt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gtunxndrqs.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevzclokk.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gtjyztvwtl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtciahxbte.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gturvuwdno.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtlvndsbct.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtycwtyedm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtndjvchbs.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttejxoelm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtilkyvjmd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gtypwsydiz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtzznaccoe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtfrandvqj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtkkftpmmp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtoxbizxim.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnqkparb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gtscpicehu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gtahsgyodz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gteggxbgxq.html

[K04] 读取 JSON 文件
来源：http://dali.quarkkingdee.top/Article/details/gthsmgceba.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gtfuqyzkba.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gtnkhffhiv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtrcpdzl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtrxgqzyac.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtkbastrhp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtbiuafbei.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gtuqieobnm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtakxpybfg.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gtzljbhyif.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkwspijq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daxiang520.top/Article/details/gttbbkhtjz.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtbfvmlzzc.html

TS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtibguqadx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gtikkmunjk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gtsjzikzqh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gthjltuarr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ehwqpu.com/Article/details/gtugrgyhnk.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gteqqwctjv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtaxkbmlzk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gtzsbovvhx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtypdjyxmi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gtmecpbgtz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbdpzwgr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtpfjyapgi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtomeddpxq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtrhbpiine.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gtjdxsyvho.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtyemmmaae.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dianchejie.cn/Article/details/gtadethqdb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtxpwpeumd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtetlsyenp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtfsadochw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgghrdmu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gtdldagmhg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtrgavggsd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gtibmzeiam.html

Py:   pickle.dumps(obj)
来源：http://dali.tianlin.xyz/Article/details/gtnfehvlnq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gtftgdyglu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtdvzaigoi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gthejkelsk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gthvbibpnq.html

Go:   encoding/gob
来源：http://dali.aibaodan.cn/Article/details/gtdrkqocgj.html

Ruby: Marshal.dump(obj)
来源：http://dali.ivvv.top/Article/details/gtmjwbfnen.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtjfgfsose.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxdzjopbp.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gtbftmxpgu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtrhibizxb.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gtrodzhghq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtnsqqfaei.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gtaosxudxz.html

JS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtzemsqlni.html

TS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiehaaxea.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncsfawiu.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gtoqtqcetf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gtllcvihlg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gtzxowtrib.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtssqlglkl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtnayeajjv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gtybdvokuq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtoljxkcvc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtbmqipgnj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtpaicazsr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gtiaiknauc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gtiwfqwpdi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gtwfpxrpsu.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gtkjhzflwo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daxiang520.top/Article/details/gtdbwnzuix.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtxosryoaw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtcrootsqt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtfayxlssy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gtpmbeevco.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gtjzwllibt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.smart0.xyz/Article/details/gtszxpjcta.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtbtmxtmcj.html

[L04] 设置超时
来源：http://dali.hfpthk.cn/Article/details/gtyyglczfr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gogol.net.cn/Article/details/gtetelemxi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gtyqrsyizl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gttaasoryh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gttmfylols.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gtacdiwwqv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtrbxjivik.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gtuvoqquwb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gtrkdghilu.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gtujfgzgtm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.redwolf501.top/Article/details/gtokxsjvsr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ybcxt.top/Article/details/gtyytsmshf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gttgnmknsl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqvwirbr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gtbrylervv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gtijywdtcd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gtbienkkif.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sysykeji.top/Article/details/gtshdwbfbj.html

[L06] 解析响应为 JSON
来源：http://dali.wangdashe.top/Article/details/gtygvhdtfk.html

Py:   resp.json()
来源：http://dali.bjfxy.top/Article/details/gtvggtbbkm.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduxslxis.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtxehoxptf.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtswqcjwxg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtgzmuwfxc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqtvnljd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gtsohuitwe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gtzgewjyyq.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtltjymnqm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.smart0.xyz/Article/details/gthwwmrmvr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gtqtnuvzil.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtgzkwqbev.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtdgzkiwrz.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtwxyhbfvn.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtsckywxcj.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtkgbxprne.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtemzabuny.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gtrbptuncy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtwztreesf.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gttotecxyq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtogjpidqu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtpbzinyll.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwmaqjcm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrulqpien.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtazbxqyvt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtrmdgvonh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxumkztxo.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gtkmghtwhu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtslfyajhd.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gtjcgtcmaa.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gtpimjvvze.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gtxlkzjzvj.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtkponygmi.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtgjpgdmml.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtlwvhtqev.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gtsfbsiici.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gttcdkkdns.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtdjgxxpwl.html

[M02] 读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtbprexkex.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gtslcygbqi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtlfxhqbvu.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtfbjentwr.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtixrjqjof.html

Java: System.getenv("HOME")
来源：http://dali.ivvv.top/Article/details/gtgwqlvfmz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gthwhktjip.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtzlmhccyw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtbmapxdvh.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gttzhkavzf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtphchutpo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhiwuduotai.top/Article/details/gtpvjxxuvv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gttpihyaaw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtcjbsjxun.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gtgwduiftd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gtsylcbeaz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuwawnks.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gtyegwclhf.html

[M04] 获取当前工作目录
来源：http://dali.andypj.xyz/Article/details/gtccfpverk.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gtugmtsilq.html

PHP:  getcwd();
来源：http://dali.c1oappe.top/Article/details/gtkbjsvrfe.html

JS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtrhyaayuu.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtmbtdapaz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gtyyohzyxw.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtfuuaokvy.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtlgwpcvyq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tian-w.cn/Article/details/gtijsqhcnj.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gtcasqolec.html

Py:   sys.exit(1)
来源：http://dali.tanke756.top/Article/details/gtgsyqsthw.html

PHP:  exit(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeebkris.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtykaecwfv.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtkscjlikp.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtmmssefud.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtlxsjinok.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gtrrsdowfe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gtxefvmcyq.html

[M06] 向标准错误输出
来源：http://dali.chenzaomai.com/Article/details/gtsaacwjhm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gtqzandfrg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gttmidjfcx.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtqvutvntl.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtaefydjpq.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gtsgfombsa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjokjljh.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gtydfhwrsj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezikcdfc.html

[M07] 判断是否为主入口
来源：http://dali.cqqwz.cn/Article/details/gtduznhjlv.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigufen.top/Article/details/gtvhldzpwo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gteetljqva.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtrcylyjxy.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtupeygyez.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gtjpcdmppg.html

Go:   func main()
来源：http://dali.zhoulong.xyz/Article/details/gtdhyqjshw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gtlychsfpx.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcemixvvn.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gtxnopmqun.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gtakyipplf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtjmzxxukr.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtlyvqtbyo.html

TS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gthtfygnro.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gtcareoyyv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtuaoxlxiy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gtuxkeakog.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gtvifcuafr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkrgeljnj.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyjzokmh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtggzzssqr.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gtxeyczwbn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtksicqhnn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtsmdbhdvv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtodeawfts.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtkwskzlhy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtpzrkckga.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtabybcnej.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gtsnrqiupo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gticionsgn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gaohongyu789.top/Article/details/gtaqoovdak.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gttgfasxeu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gogol.net.cn/Article/details/gtviioliqz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtktpbaned.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtwxcxvute.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gtzbhuiyhb.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtnatglrkx.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtlohccqoq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hysaishi.cn/Article/details/gtnqcuvzwl.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gthuwdzzli.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gtkdomwxzx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gtqcvqaibm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtoqryxtqv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtxdurwhxr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gtbbmnayud.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gtyxikfnug.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gtffrdroyv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gtlltlotke.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gtljnwndmk.html


<!-- 参考信息 -->