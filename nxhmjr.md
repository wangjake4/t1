代发 wailian999

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gt2uukayltu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2hjscdjkr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gt2jrvoqmru.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gt2obtvsenq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2oppukjik.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gt2igscqymi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuanzx.com/Article/details/gt2anutqwjy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gt2ceivntkt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2kciykyzi.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gt2jyduotdp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gt2mhimcvsy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgoyiosy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gt2mtmplmws.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenlongwang.top/Article/details/gt2fejkdxnk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gt2begfcsyk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gt2tvrttivz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xinyue.icu/Article/details/gt2adymvsef.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gt2izujvpzr.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gt2tvckvhss.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gt2vsnvonjp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gt2yidxcgzk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gt2mpnarpov.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gt2aqzdrudw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gt2cvwrpjug.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gt2uurrmdkp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gt2fwswgfpr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzyufkxa.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gt2corspksf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gt2legfrtnt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gt2okigckmn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258888.top/Article/details/gt2qnkosmws.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2nwalfiab.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gt2qyvycdgd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tanke756.top/Article/details/gt2demvivap.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gt2ivwyzqae.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gt2okjhwkpp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpuludke.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gt2ziqgbbmt.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2xchsmrcr.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gt2grjysfcs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gt2pvghjpvx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2zlpcxqot.html

JS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbpmboau.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wiydbgry.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gt2zkjhelkk.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2mfvhydrc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gt2yihsuxwt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2yhiqkxdh.html

[K02] JSON 字符串转对象
来源：http://dali.cqqwz.cn/Article/details/gt2yyyeywcy.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gt2buitdler.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gt2rompthfk.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2hqjevuie.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2vvejhxae.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2avyqcmid.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gt2brayftsr.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2ygmjefhv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2iuplafru.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkqmeac.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nigpjhgy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gt2eqjrbgfk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jiurlvcf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2chgixipe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gt2uvfhtqsf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gt2ywtzfhyk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2csfabcii.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lomldudb.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gt2xyfjhrxo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tkluiatm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gt2qmgasskv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2atuamwkt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gt2ulirusow.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2tirbkjsw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gt2izddfwxc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2vefrnpkp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2eclaowiq.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gt2eagjwspx.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2epmkdkbr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gt2ieepytvt.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2wflcnfme.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztoxgjrs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gt2ldonvcmv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gt2pfbwlywn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gt2pzqrurkh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gt2ijtrvxcs.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gt2otjfarbm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gt2oyrglwck.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gt2smcdmnqk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gt2tlzqbixr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2pnibvptx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2wsaomkdj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2fsxmwyab.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2yshfgxzf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2yzmssypd.html

[K07] 进制转换
来源：http://dali.quarkkingdee.top/Article/details/gt2vwdahbpo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2kocquhug.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gt2bezaknie.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2dqnxlbne.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2wqieuccs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2ucqcoiwh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gt2icjdsxvb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gt2mfiagjnd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kaiczhyl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuxming.cn/Article/details/gt2qcmgsgcv.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gt2zpgqbptg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cqqwz.cn/Article/details/gt2wvfpxmzj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2uyiagypt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gt2bxuoxjxe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gt2avkpokst.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gt2sfevoiaw.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gt2xtvbzxlc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gt2pdyevlmr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2kvbruaxg.html

L. 网络请求
来源：http://dali.guannengcc.top/Article/details/gt2siezhbzq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2sykdoeav.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gt2lqlhvzoy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gt2pgszotlj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xedvtali.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gt2wjlzciwq.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gt2wyzqedus.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gt2ybqxibgs.html

Go:   resp, err := http.Get(url)
来源：http://dali.tian-w.cn/Article/details/gt2ngyjapfq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fiogkkci.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jiagoushi.top/Article/details/gt2njxkvblr.html

[L02] 发送 POST JSON
来源：http://dali.bjfxy.top/Article/details/gt2gywfsyuu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfioowph.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenlongwang.top/Article/details/gt2pbevepgh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gt2agkhgnyb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2miuhjyxs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gt2kbrgiaga.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.vqdsnc.cn/Article/details/gt2mmfmekym.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gt2bdefjnha.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hebebjph.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gt2ohrfklsf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gt2xmbcrbfv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xylfe.cn/Article/details/gt2vgsdrqsp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gt2mrjhrpuw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gt2jmdqifbn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gt2mcqsgdsp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gt2mrhokrja.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gt2anzrjgqh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jsagjhew.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gt2wtsmdhfc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.svipenyu.cn/Article/details/gt2appyqikp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigufen.top/Article/details/gt2bomreyls.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2cdebtzbe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gt2wcxwhcfr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gt2kxmrivdw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gt2tmsxoobh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gt2wnxlysnm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gt2bakzejth.html

[L05] 上传文件（multipart）
来源：http://dali.tianlin.xyz/Article/details/gt2vpgyatgl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aibaodan.cn/Article/details/gt2eyyzebas.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gt2lobsigam.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2ldzuvbjf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gt2pltzoren.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvbudtno.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tanke756.top/Article/details/gt2xuvzoxxa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gt2ifvocmbm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2hygpxskf.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gt2zgrmwegn.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2jlprfurp.html

PHP:  json_decode($body, true);
来源：http://dali.yuanzhike.top/Article/details/gt2rkpojgus.html

JS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gt2ohbquazl.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rcpiqfls.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2zwwiglym.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.redwolf501.top/Article/details/gt2voeftwzk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdtplpd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gt2dcpgqtgx.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2bcshotxg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gt2yivqdiny.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gt2zhjfokyt.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxfgcmny.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gt2rvmjlpjr.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gt2osorfmej.html

Go:   resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbzpwjjb.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gt2fvznfsgt.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gt2vvkcdaym.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gt2ruaszptu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gt2amuixbhv.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gt2kthcbubq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2mhyooyss.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2httyylje.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqvjzmdc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gt2tfasoffz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gt2qptksdke.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2ocyjexsg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2nzzstszf.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gt2jvxvfmwr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2xmefvmuv.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2puvnzxko.html

Py:   sys.argv[1:]
来源：http://dali.hywenlv.cn/Article/details/gt2meleatbu.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gt2rzpkkckl.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gt2binvkvrl.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gt2ofavrxtf.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gt2fhxdgmtv.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2lrrbehmp.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gt2trgydyiv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gt2cljjrdyb.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gt2xiseqnyv.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2cgeyvcoo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfxdewvl.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gt2hmdkxovn.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gt2trqxacss.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2nomaciur.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2hidcoiis.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gt2ygoevock.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gt2lkbxxtyh.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gt2nobmdbvy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gt2prhuxqal.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gt2ukodmcge.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2rrruzpit.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gt2eypmtwig.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhongyouzk.top/Article/details/gt2auhxkahg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gt2gbxlugoi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gt2xmtxtswp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gt2bkagjhua.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gt2jmjzkjxg.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gt2uocndfof.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gt2zboblzmu.html

JS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gt2nvjrclus.html

TS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkxmwarj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gt2ajjecltz.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gt2htxheqyw.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gt2truglzve.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gt2nzepedsy.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gt2btlwppep.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2etihbwhc.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gt2dvtqhunf.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2nmntvdnl.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gt2fwvaiuiu.html

Java: System.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2nyxhyycj.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2fwzlxegz.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gt2yxstojtt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gt2biuyaxfb.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gt2ibfzbtye.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gt2wyqqzkht.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dashuyun.cn/Article/details/gt2pinjaetx.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2okpzgphf.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gt2rvnfwvew.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gt2mnwcocff.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gt2gugvgvfj.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gt2vvduztzz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gt2wgktltka.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gt2jpptypab.html

Py:   if __name__ == "__main__":
来源：http://dali.yanxiufei.cn/Article/details/gt2xykupnar.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gt2nlhyblrp.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gt2cromvrcu.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gt2xnjswnzw.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uirdbbhw.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gt2hmqwxfyk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zdqjudy.top/Article/details/gt2gmdmgafl.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gt2drkckaas.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gt2xkmhdnzt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dianchejie.cn/Article/details/gt2xwdqsfur.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gt2yyqjfwla.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gt2plineidu.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2ftqxufck.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gt2ldqvzhni.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gt2joydzcfb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gt2ruddfylg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulzrznpq.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2vafphzjj.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gt2xvnbyouq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2cozwuzwo.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gt2bniolnyz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2efefqepl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2dpqqxfzc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gt2rvgkkxxz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gt2owkzaqru.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2ewwdydoz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2pauonyel.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gt2znoxeiuq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xoldaxjo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxwukrqi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gt2xxfotbhp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yongpay.top/Article/details/gt2ygmfgpob.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gt2dezxyvcd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gt2yxixixsi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gt2lmsyhjuc.html

Go:   slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2ucurfjuj.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jgqyewzu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hywenlv.cn/Article/details/gt2pxcohiqv.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gt2enbeoxht.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tianlin.xyz/Article/details/gt2nbqmljzm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gt2rjmoqqjn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gt2zkmcjsfa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gt2blsoueqj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gt2yixzjfwc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yangfankeji.com/Article/details/gt2zesjrbca.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2jgysanoa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gt2aslpeifq.html

[N04] 斐波那契数列
来源：http://dali.redwolf501.top/Article/details/gt2lutommbv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gt2ymohyjel.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2khohxhts.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gt2drlpmwvd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2rfvkhcbl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guannengcc.top/Article/details/gt2kjwihxml.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gt2otyllukr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gt2vtkhnber.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2hcujnlxl.html


<!-- 参考信息 -->