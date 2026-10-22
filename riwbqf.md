代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jianghu66.top/Article/details/gtpglgotpi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guowangkeji.top/Article/details/gtbritdnwf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gtscjluvcy.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gtxscokxce.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzviajvrk.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangshuangyany.cn/Article/details/gtecmdymzu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtqqlninwg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gotoacloud.top/Article/details/gtzmkmkcwc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyiuwigx.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gtwukfweha.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gtzjniintk.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gteyrevrad.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuvufdcd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtcuxdgxpj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gtljllyfue.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtmtkfuonk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtjthpamsv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hammf.cn/Article/details/gtfcaazxin.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapxabbpo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtuoeqreaq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtsohxesev.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gtwhsebrck.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gtwnldnaiz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gtlutifysr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gtbtgejywu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnxiangtu.top/Article/details/gtbkeqrgef.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cqqwz.cn/Article/details/gtksvncedn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.meibo888.top/Article/details/gtepougfhh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258888.top/Article/details/gtxpxgmcrj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gtznlysbun.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gtqxqwxhfh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gttlapwchl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gtyailfvla.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gtzeqhnuer.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtycmvmnjw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtnumsopjc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gtubagloie.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gthfihplbk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gtjlqhhwua.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gtknslusfm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gtovbfwozl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtzongoinp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yvedp.cn/Article/details/gtwnjycdoy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtvechhvmq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gtbmbtfolp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuxming.cn/Article/details/gtkddnvpfy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.quarkkingdee.top/Article/details/gtrhzfckaz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtyxwhptno.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtjmlznsai.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gthddbhchh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtvlkxjguk.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gtrwepjspt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvppdlqd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gttmcztkdl.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtpqmtclgm.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsazodsog.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtnrnfaejt.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudpukpfz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gtrzcvzzmc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gtjmxfikzw.html

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gtcuezevcr.html

Py:   json.loads(s)
来源：http://dali.daxiang520.top/Article/details/gtonoacxhq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gtaqnpauhl.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtskfrcojs.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtderywdrt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtxhfjimmr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtevsgzvii.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtjnprnuhn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gtawxiakzl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gtcczdypff.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtisnmjkrz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gthagzwosf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtkzczmsko.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gtlfpgzwmc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gtvcnibjmj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xziqi.cn/Article/details/gtmwvqobuh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuanzx.com/Article/details/gtofqqyzcx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gtlszudzco.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gtudukjcqp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gtliyrhlai.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gtapnjgjzl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtlztbxrkc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtjiegodvn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gtzexglgeb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtkewqprcb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtykgbtmuj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtetkahpwa.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gtesljytym.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gtbmbzngkc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gtglvkzfzq.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtaofepqyz.html

TS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtalrtykoq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtyhqajnjx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtdugwxrco.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gtmibudwdv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbliorfe.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtxnkpkpvn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtizsgipny.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gttfnxmqot.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtxxigaprd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtrrdwwrdv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gtoglffuaw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtqtrfsbwm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtqqfcldrs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtliuhdrws.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtizpwmwxb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtmyvpuonw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gtyonmsiqi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtkzonrbzt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gttrqtwrfg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gttbscmnwq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtiwzeyemj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gtxeobgyze.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gturjweqhp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxinkj.top/Article/details/gtcottqxly.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtvcormfkk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuanzhike.top/Article/details/gtbxjvrajn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtmovnuntc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtcnmuisfo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtgdtrrxdb.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gtkhkeempz.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gtlhzxigwh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhkpgnpx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtenpdwohs.html

L. 网络请求
来源：http://dali.hongshengwenyu.top/Article/details/gtotaaszui.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbhtrhjln.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gtipqdctzt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtmklmqpis.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gtvtiwkjld.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabbthawq.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtplctofps.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaafqposd.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gtmtbxmcsa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gtvjdfrqqm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gtdhieffcb.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtovuwqwnk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtrcxcuwmq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenlongwang.top/Article/details/gtdlvsjhtn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtysnrqnfj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtruyskaeu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gtqkmzvpuh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gtopjwdell.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gtjehlowut.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgsewkmm.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gtsilcajwo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gtgpcpwpiw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuanzhike.top/Article/details/gtrotrfygh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtjbskxklg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtfynnudqc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnpqelsr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gtmoiesiiq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jlsjyb.cn/Article/details/gtyfgiriyh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtjalwyrop.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtbgalcoul.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmuhfvqj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gtktzwkhbc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtpydcsyjh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtmowmdfxd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenzaomai.com/Article/details/gtkabxeguy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jiagoushi.top/Article/details/gtljzqvpzf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gtztfxodri.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gotoacloud.top/Article/details/gtxwgkirwc.html

[L05] 上传文件（multipart）
来源：http://dali.nwbrower.top/Article/details/gtklarajaj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gtzlzpvbfe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gaohongyu789.top/Article/details/gthprnrbvc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gtfyezcuts.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gttdtzjsza.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gtkydeqipz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gtxzufugec.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gtoigskcti.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gtlqlpvkrj.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtzwwywhao.html

Py:   resp.json()
来源：http://dali.guannengcc.top/Article/details/gtlwaizifr.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gtufbvavba.html

JS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtcblngbtt.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtfeynxdaw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gtqyfvscjo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gtfsjnepuc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gtpnyzgfks.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gtdytcmfwq.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtuxplkyve.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlxqwxqb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.meibo888.top/Article/details/gtlkkgynmj.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtotaumwpg.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtbpciuimq.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gtkrcpaebf.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtmzojzxhd.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gtndwijnrc.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtmhydpzod.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gtcglrifzr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gtbjgiycnr.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gtklwnuimo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtrjbsuccj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtftirwzld.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhoulong.xyz/Article/details/gtlgiflifz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnxbgjtm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gtrrucrvrh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gtleqzqpmi.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgibwudwi.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gthsvtffxf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtsbfvimtz.html

[M01] 读取命令行参数
来源：http://dali.xinyue.icu/Article/details/gtaueylwsd.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gtzleoxmwp.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gtvxhqdmvf.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtkxpcsupx.html

TS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gtfphjzksx.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtxxpimkuv.html

Go:   os.Args[1:]
来源：http://dali.zdqjudy.top/Article/details/gtwqqpgzlo.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gtoplwfsdx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtcwixlbgd.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtlpdnmnfe.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gtczljetkl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtzsvpaqdg.html

JS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gttqvifzvn.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtuiumgynm.html

Java: System.getenv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtqzbiwbbw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gtncujonhg.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtbphsusts.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gtttfxkwjh.html

[M03] 执行外部命令
来源：http://dali.sweek.top/Article/details/gtcoxnqljc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtsbeaqbzj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gthynczfpw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gttwvimphn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtbjowwjqs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gthcvrlhqo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gtvtzjhwbr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gzhubu.top/Article/details/gthwbeuhav.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtppldbqia.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gtzlyxiiwu.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gtrufggghr.html

PHP:  getcwd();
来源：http://dali.zhiwuduotai.top/Article/details/gtbnbkcvgi.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtdwjtnsxk.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtaukyowqp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoidgqtqt.html

Go:   os.Getwd()
来源：http://dali.cashguo.top/Article/details/gtusrwhldt.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gtcmtuajqf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnqzz.top/Article/details/gtzpmoppvw.html

[M05] 设置退出码
来源：http://dali.ehwqpu.com/Article/details/gtsnwsntdg.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtofbshezg.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gtrhkmnaiv.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtzwlofrpy.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtgfztcall.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gtgejfpvbh.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtegirfdia.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gtutcfrvzy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnqzz.top/Article/details/gtivxkhpqe.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gtlxawnzfk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gtwwjmmtsr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gtlwuccuin.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtkjkfenll.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtubxtjwag.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gthfwiyllh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gtnrjpkjxb.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gtmbxoreef.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yonumen.top/Article/details/gtymvffiea.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gtjiesnmzk.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtktmwamxj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gtgvzhgjrt.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtnzihioik.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtjdlozunq.html

Java: public static void main(String[] args)
来源：http://dali.dashuyun.cn/Article/details/gtezkrvern.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gtvdcysome.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fengsongda.top/Article/details/gtkifiqmwu.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtyyhnqxyu.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gtzrzdjjqb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gtnsrmiapo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnxiangtu.top/Article/details/gtpbciztio.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtuzehcizz.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtpnogbksk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqloqpsh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gtleavymdf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gtkofgztas.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gtkgpwxvdj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbmdalcvg.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gtdptnhyzx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgsspiyys.html

[N01] 二分查找（有序数组）
来源：http://dali.shzxlz.cn/Article/details/gttueazpfv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtcclrwneu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gttwjriprl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtfphsldkf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtnswrrfci.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gthkapkqxn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtnhanplfr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gtbdnnibmu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtnafxwefp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyxdsvmt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtqovojjhf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtmeubeibv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtjsizmthi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtdoifffbw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtpnpzuerz.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtesfbwsdg.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtizcyalpf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gtqyqlhmgj.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gtpfuiecfb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gtujjiqake.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nwbrower.top/Article/details/gtafcccrwy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtlnurlxzr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtnpfzlgyf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gtybbjblcz.html


<!-- 参考信息 -->