代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gtwxriscqx.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gtiwxujhyp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtykshpeyy.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtckyakmjy.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gtnwlbqmnz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtgdufpzar.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtcotufmob.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtpyywxmwi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtzodduyzt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtihqrvisu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gtzfapcbuq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtksktyupo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtkautgljk.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gtmqremkcs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gtvwxxdiwn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtslnrdrxa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gttmufqhsv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gtjmpitmxw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gtxrpowgua.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yvedp.cn/Article/details/gtnilgnstl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gtlqrxcklg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtumjifcbk.html

[J09] 时区处理
来源：http://dali.wangdashe.top/Article/details/gtihzvysho.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gtmwegpsfk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gtagszoxfr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gthbxqlbxv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gtesjcxbqv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gtycfrmytf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gtdjdfczbh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtrzfapcqq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gtvfppcdsj.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gtrdkwzsek.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yonumen.top/Article/details/gtwbzcysfa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gtmgffwkji.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtayyqssbe.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtcngixyia.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gtkqpizyhp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gtlddvraft.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.quarkkingdee.top/Article/details/gtrcztmksq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gtemkbpqok.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtsnthbqwd.html

K. JSON 与序列化
来源：http://dali.feifeiyinyue.top/Article/details/gtdtqxdsgc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqzopjppo.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtndpzkkfw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtghnewhox.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtwrrerblw.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtkyzulagi.html

TS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gttxdlnaif.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gtvvumtlcq.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtdslibsrt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gttcpqnifw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtgsupoeqd.html

[K02] JSON 字符串转对象
来源：http://dali.sxryk.cn/Article/details/gtylhazhkt.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gtexizqcyh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gtpilugprf.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gthpojrkyr.html

TS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtgipowify.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gtvmvbxwer.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtggbkyejs.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpmaqyxm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gtnywsualk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gtygdioghe.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtzhoxjbpq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtzusrwvqh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtygsrktem.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtarsjgujq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gtljkbwdmz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gtoicrwtld.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gtyiacffum.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sufxvd.cn/Article/details/gthnliihaf.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtytfdjgwf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gthxkhzums.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gtmpmlssup.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtvrnjsyjz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gttqnjckoc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258888.top/Article/details/gtmhghlqip.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtpdrdxepu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gterorkmvm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gthhczywyt.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gtcuxlpdsk.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtmpvrmxcj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gtdtxyjsmv.html

JS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtetkrmyie.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtzhbhadjs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gtgkdbmwxe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gtzmncebwx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gtayinlvrn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbmcgmtl.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gttmqmofqc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gtnusjyyki.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gtlbubfdcc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtgxgkwqsj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtfniymgzl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gtdcjmwhwz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtrfysztpv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtruccesrl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtkhctgrkh.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gtjdhzzwnx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtoomyarnv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtnyyvsgee.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtyiuiwkuw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtotzewnmn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtlxkgiisd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gtpepgstgd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyihvprn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbbwverq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gtrgqmjtfa.html

Py:   pickle.dumps(obj)
来源：http://dali.yuxming.cn/Article/details/gtclytylla.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.meibo888.top/Article/details/gttogeqqak.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtvrsqbnrw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtwsqiibuu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gtxouwxref.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gtlqckkztf.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjatnvyuc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtftqfczmd.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtpibcmpfg.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofpqiqox.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmsroalxn.html

[L01] 发送 GET 请求
来源：http://dali.smart0.xyz/Article/details/gtnulqnuxa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gtgbwpalka.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gtiumlipmo.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtqbyyobhy.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtxxyhcgmz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gtlkvdqleq.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gtzifzlvmg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtaizvuhkn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aibaodan.cn/Article/details/gthddjqbbt.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtaklpghpj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtmhzhafsf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.smart0.xyz/Article/details/gteibauzuq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtnyzebxih.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtngkvvlmy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgoujjrfl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gtqkarlhrs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gtjxawtucz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gtkvopirjc.html

[L03] 设置自定义请求头
来源：http://dali.jinqigfzy.top/Article/details/gtjfcsqwkz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbsthhax.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gtznxykhjx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtbfnsjksl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtcuuhvirs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.feifeiyinyue.top/Article/details/gtaapawotz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtidjvqzix.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gtjakogtwr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtcxopvgrx.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gtcgqjupml.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tianlin.xyz/Article/details/gtoswcjabv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gtgorbfzek.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtttdqleaa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtlfitbisz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gtbcvirnkx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhixingplan.top/Article/details/gtyhtmvilk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtcihnqalt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj202588.top/Article/details/gtgvhvisfa.html

[L05] 上传文件（multipart）
来源：http://dali.ybcxt.top/Article/details/gtvrhqhugk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gtngvnwvya.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gtnqudevmj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtcdlhxdxv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtljbzxecc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gttshibjoy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.havefunace.top/Article/details/gtqjdimnqp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gtgyuaiwnv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gtfkxbvjcd.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gtmmnrxuxy.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtgyobgxhb.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gtelpgfnoa.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtvrrprbez.html

TS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gttfbjsyiy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtfqfnxcye.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gtofhywqmf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gtbcbvgbpe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzsmzjel.html

[L07] 处理 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gtpbaiowpl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gtwqysuwjh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gtyqdzocow.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtchjkmvta.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtthgohyzl.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gtvdpmtvpd.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtfgakfpoc.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gtrhgciveo.html

C#:   (int)resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gtfvrhfaph.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxfbfsgn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gtolqfvhjs.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gtcfflhfnh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtmzbsnnmr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtstptuvgn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtiognrcdk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gtklcozpsq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gtqdkpinfr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gtgehzazxy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtpenictxb.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gtdlghzuda.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsaqssoti.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtznuuwsfj.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtllovacbd.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiephtaqh.html

JS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzltmseqt.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtpvtbvwis.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gttcgbnqev.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtfcqolymy.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gtkqxecnop.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtdmxdsdmf.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gttifqvvkb.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gtnliovtdb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtojzlwvag.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtgupsapko.html

TS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtvbtvdbvi.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtwwbyudan.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gthngpmkfk.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gtohoyxoxj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtqvbifeho.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gtvxlqgnyj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gtjbyrsbdx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sxryk.cn/Article/details/gtgncavwfa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtbavicrhp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtqaxrseyj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gtblvzhhmu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gtlakvwusz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gtsrtsgloz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gtvadyamdc.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gteakcotjc.html

Py:   os.getcwd()
来源：http://dali.yj20258.top/Article/details/gtclqxjmyq.html

PHP:  getcwd();
来源：http://dali.wangdashe.top/Article/details/gtqwycaklo.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gthulrliny.html

TS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtmsjoxuak.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tian-w.cn/Article/details/gtfyctphgt.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gtfagqrxqa.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gtmbzpftoi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiiedbflu.html

[M05] 设置退出码
来源：http://dali.ehwqpu.com/Article/details/gtszcbsmus.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtfgymwyoj.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gtfsxpnkqi.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtutxfcupw.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtzzhkxktj.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtbxmyrtnf.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtalrnvicr.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtgatkgrap.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xinyue.icu/Article/details/gtfdvrwsqs.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtqvgkasdo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gtwsynvpju.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gtobwysknb.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtxaomtiyj.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtuavpzuia.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gtqkuzypcg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gtjnhucggj.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gtfnamfgrr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gtvnbsvdax.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gtepkksdep.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtxencjyke.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shangyingyoupin.top/Article/details/gtycviiddy.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtdngypzxs.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtwsbbfryz.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gtasbyefmo.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gtrvtsawsl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gtanoyuuek.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtembvvjlg.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gtbievtlpr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtftlidjpz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gtadrxhqfg.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtplhagdyj.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtszicrnms.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gtpllynzqj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gtlaxpeues.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gtwhjzxwcw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fengsongda.top/Article/details/gthonmcvkv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtaxthngqt.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gtflbqvrdm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtjbqvewwt.html

[N01] 二分查找（有序数组）
来源：http://dali.c1oappe.top/Article/details/gtiblhgfub.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtzoiaekkz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gtpnskpalw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtgqkrlmzo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtqhlnvnqg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtynrlmtiy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtgyfyuaej.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gtseixqwiv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtiyhttjhb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gtbdtwoymr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtzghzofrc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gtqtgmbbvu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gthzfnsevu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gttpbpxrsm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtkgpmiyxf.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gtfseprwhl.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfkiahys.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtwuwmdnpu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gteyljiwvh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gtzjutfeka.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gtdtmgllto.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpwjibbe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpcnckpa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pycfn.com/Article/details/gtynngnkqa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gtowcvxkax.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtveqzjmtj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gtzxirsjyd.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gtpdslnmqh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtppvocurw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtzbttfdyt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtywafnhqd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtvctqhdeu.html


<!-- 参考信息 -->