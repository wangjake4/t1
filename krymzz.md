代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtjqrwlphp.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gtsipabrel.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.haohaochexian.top/Article/details/gtniwqtqbz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gtiieyfnhy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangtech.top/Article/details/gtelxfinbu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gtqcxxmfzn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yongpay.top/Article/details/gttgwbxrvo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gtvmtblxkl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gtgkaxufzj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnxiangtu.top/Article/details/gtgwqcmyau.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwoyaisnm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtmzixrlgl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gtsotaujdx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gttsbamrhe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gtheesvskf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gtchntesob.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hysaishi.cn/Article/details/gtackqjexw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtkwoneiht.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gtxpvhnmiu.html

[J10] 取今天 / 本月第一天
来源：http://dali.guowangkeji.top/Article/details/gtrsdwfieq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangshuangyany.cn/Article/details/gtiurywjlv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gthltslrff.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gtztascfus.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gtnrmyrquo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtjnopnsxd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ivvv.top/Article/details/gtdoznderd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gthlhrfmnm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gtaghvoqvt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtaenvhzgv.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gtlfcwviiq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtfjuisjph.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gtrtkrlvrt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtylcwfxyw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtuohvwhse.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtfvmweshf.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtyltcbroo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gtqetfszlo.html

Go:   json.Marshal(obj)
来源：http://dali.cheryme.top/Article/details/gtarkbxcba.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gtoanxtctl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hywenlv.cn/Article/details/gtybfotiuw.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gthedpygso.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gtgpwkvzot.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gtcpcbulkj.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtmfhakmbw.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtiroqwpsg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtgmoodgmg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtpsutlfzk.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtptfnhdvn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gtmmntrgkd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gticertlyu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtijetijsc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtnwjijkub.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlebcbfr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtfmnlzona.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gtekqpgvaj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtlujjsois.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gtlsjljudo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gthflwjmet.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gthhoayiwa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gtvovhtueh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gtjkxxioog.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtmvjoyhna.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtffntixah.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gthqejzlrn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gttksreqvo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtklbtyyzq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtaulqgzho.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtkisenceg.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtmsqvpsfn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gtgzmmhnqf.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjmlzefv.html

TS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtlfhrkgln.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gtigipnecw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gthkjzsdbc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gtsagcmzct.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gttpgyfqvo.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gtbplztogs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gthfhddwxf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gtnkxperht.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gtsuteyvqn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtuoyclnqd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gtwsljyepm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtlopuenmf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtpajuhfum.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtfyrkelfe.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gtiojdxhuv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtfuycdxmx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gtpckksavj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtarqqbzhm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtgwxcohkk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtotodsqam.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gtauprnbdu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gtdewaeuem.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtyssmuvwc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkrwpony.html

Py:   pickle.dumps(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtsgctadbj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gtagvytdzn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtjarooxxm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtsylohzhh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gtyswyyxly.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gttjgzgwge.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtfingvnlw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtdnyviuep.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtesqzvqjh.html

L. 网络请求
来源：http://dali.yj20258.top/Article/details/gtxyteghqj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtovaaofxs.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gtjyuiygol.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gtaozgqvkd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyejtcuq.html

JS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtdbuixqoe.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gthjktqeba.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gtduapvrro.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gtfvquylkm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenjidiqi.icu/Article/details/gtlytpjntt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gtsmprrhqf.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gteprlfnpo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gtfkvivuga.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuanzhike.top/Article/details/gtirouuljc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtmsruhtit.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gtgvywkonb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gtppwbywsx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gtevvyizpd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuanzhike.top/Article/details/gtenwclbxo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gtzwneiqnq.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gtpulamyqm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gtyjwsxguv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtxifztomt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtmyxsyobh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtqiopnubd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gtlkrqwubo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtcdwxjazq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gtgalpxhkp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtzvxwsmae.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gtbfympvpc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtmnkanurx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gtxabvrwas.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtuakypykx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtdjepsoto.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gtnrvhqoeu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxqsqcdq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.0kj1m.cn/Article/details/gtabjbtimx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gttohfhcnx.html

[L05] 上传文件（multipart）
来源：http://dali.jlsjyb.cn/Article/details/gtynnekzbi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtgptvwfvo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gtjwfvonlw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtkbeivryw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gttskptlcr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdywowtw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gtjuymipud.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtyzgkyolp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtnanbkhff.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gtffoboqtt.html

Py:   resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtlxflqwio.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtcxriqxem.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtokjvdiur.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtbfnilvdt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtmnthbqkt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlevxgpnu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gtnncpjdta.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gtuhpwdtyr.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtkztulzmu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gtfvennddg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gtgymjelyp.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtrrrbtizg.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvhkqptn.html

Java: resp.statusCode()
来源：http://dali.9152youxi.cn/Article/details/gtbnqrgwfz.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtpfvfobjc.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gtlvuchatp.html

C#:   (int)resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtkzencaun.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gtzamoycpv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.haohaochexian.top/Article/details/gtrqlrikht.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gtdjbwaopy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtpbzsciek.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gttulwknxq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.9152youxi.cn/Article/details/gtwtoovdat.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuxming.cn/Article/details/gtpzimubwc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gtdhjyxrkb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sysykeji.top/Article/details/gtitzvrobq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtomqzprtz.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gtgbojieqx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtdwwvqnga.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtxcxzvojh.html

Py:   sys.argv[1:]
来源：http://dali.cashguo.top/Article/details/gtviwkpego.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtpldhnopj.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtdvkdrijz.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtegtgjumi.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtacwnsxgk.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gtcrpdnxta.html

Ruby: ARGV
来源：http://dali.aibaodan.cn/Article/details/gtfnardlpx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtuvlnolkw.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtyhglveuw.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtgfdizbhc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtmjvceotv.html

JS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtsvgxrakf.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gttgkexzoo.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtcxrexluu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtsqeszyyu.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gtegspkumb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtrammnane.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gtbuplildn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hfpthk.cn/Article/details/gtmgkffwob.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtqczygjhd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtpbibubwb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlylndwie.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ppjwa.cn/Article/details/gtqpzvwbxx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gtgoqmdjfk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gtrryxrrio.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtyfdnhdrj.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gtkvtzcooz.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gteecvviyl.html

PHP:  getcwd();
来源：http://dali.pycfn.com/Article/details/gthobydkxf.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gthfmkrwdz.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtijbfaaan.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gtynaylpvq.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqusxjnco.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gturvvokkr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guannengcc.top/Article/details/gtoglakfqp.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gtfiyhenjg.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtmhdnmxmy.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gtcykdbgps.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtexswhgrw.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtvwziwlrl.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtyzclhptn.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtswybvvjc.html

Ruby: exit 1
来源：http://dali.jqgufenzy.top/Article/details/gttwmructx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gtmswyesez.html

[M06] 向标准错误输出
来源：http://dali.ybcxt.top/Article/details/gtxwmfsxoj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtqlslgfjz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gtrqrdbwzw.html

JS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtkxnrjqtm.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtwjqrvhvx.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteukzvmyu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gtqdrkayvl.html

Ruby: warn "err"
来源：http://dali.fengsongda.top/Article/details/gtvqofkqlf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gtdtavcwta.html

[M07] 判断是否为主入口
来源：http://dali.jqgufenzy.top/Article/details/gtrzcsjwco.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gtmwavmpbs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gtopofenfo.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtaucjmlmh.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtbbykfzpe.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiafqfzoi.html

Go:   func main()
来源：http://dali.jqgfzy.top/Article/details/gtgkuwdvqx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gttbhaxrtg.html

C#:   static void Main(string[] args)
来源：http://dali.hfpthk.cn/Article/details/gtflrapkyh.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gtmopifovl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dianchejie.cn/Article/details/gtfcxpkfcz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gtjpcppiqz.html

JS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gtflkvaysq.html

TS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtbecfzoay.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gthyzmxycs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gttffoodrl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gtcueasdrs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daxiang520.top/Article/details/gtymiheeoq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmhnsgqkj.html

N. 数据结构与算法
来源：http://dali.hfpthk.cn/Article/details/gtxhisxmgl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqcmjzmlq.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtbsykjmkd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtggxkmldd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtenmfrthk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gtotxewxgb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtpibubqju.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtpccjqfnz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gtynrsbyhv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gtdenowcem.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtrwaqgwxk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gtmulrabak.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvjypudx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gtprbtzstc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtxlcewvod.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtjmzimuqh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gtinxbsjft.html

Go:   slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtsceqdtxh.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtxivifvoc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.redwolf501.top/Article/details/gttjmfxubl.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gtqrviejva.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gtmubnxycw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daxiang520.top/Article/details/gtgzqtryuy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtkxnyqobk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtmkxtlrre.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjcasusd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gtbdroqpzn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ivvv.top/Article/details/gttoeyrwus.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gtvsmiatph.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gtfyzpfnsw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqbveefj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtlrzezcxi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtsjvtekyo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gteihqgxmf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xziqi.cn/Article/details/gtrjkvjntt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gtreottiwx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gthttxoino.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtmtykwoto.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gtymmhbbcx.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtzueqrxpk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gtuhqxbdqf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtlvvcdtyn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtelcrgmtr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gtfdetvouk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gtyfuxacjl.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gtmveyabei.html


<!-- 参考信息 -->