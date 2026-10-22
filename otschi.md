代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtxbpuqqob.html

Ruby: Time.now + 7 * 86400
来源：http://dali.mhx1999.top/Article/details/gtgkfnsfkq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtuelhjsjg.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gtgkldwfrd.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgnjtolq.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtjglifxzk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cqqwz.cn/Article/details/gtxoerpsfl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gtarxxjgop.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gtfkelxvgg.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gtyaaxvwji.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gtmjbzyamt.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gtjcjabfen.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gtlynfucnq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtnutocrrc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gtorrohikq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtwgfluhey.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gtpvgjhysq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gtrzigaidy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gttwalapxs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtlpmfwubk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtytlrqrod.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gtbrfswazf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcozhoky.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gtuurimzhj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gtslazlump.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gtkjndnufl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gtipulhuxz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gtoheshmff.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gtnpbbyhmw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gticxscxsl.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gtvuchxctu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtrecgtgtg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gtcllbcyzr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtlvvfiaie.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gtpglcymls.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pycfn.com/Article/details/gtfksmntye.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hongshengwenyu.top/Article/details/gtxutjqhjj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gtthmbxcvm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gtyqtuuvzf.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gttymelzgi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtrxyklflr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gtyatzaqxr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gtptbincym.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtcjywejwd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.mhx1999.top/Article/details/gtyfzthulc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gtqwmtuxbv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtedcnmebd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gtcxcflnzu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtddayabqx.html

K. JSON 与序列化
来源：http://dali.jianghu66.top/Article/details/gtgvyuvaom.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgmrytuko.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmcvaijw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtvexsyesi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gtqbfkopig.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtuwvpfaqm.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtevekrwri.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gtbhzxrkyu.html

Go:   json.Marshal(obj)
来源：http://dali.yuxming.cn/Article/details/gttgveynzj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gtkgfvegcc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtfkxkuhce.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gtszxtnqzl.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gtbizfjrud.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gtsielyovw.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtkptuzpsq.html

TS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gthaywnsgh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gthwxngsqc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtoopglpuq.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtgweeksrv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtyjyqleoi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hongshengwenyu.top/Article/details/gtpxaqafie.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gttysmglvv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgpnihel.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtmrolaygq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtmdgeotay.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pycfn.com/Article/details/gttdtykrre.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gtqrckwsiw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gtymfljrld.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gtpkxvyvul.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gtcoclbnbk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gteigvmdro.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yueranfly.top/Article/details/gtgaaxsyhv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtgxkmrymm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtypxncdkf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtblxefavg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtikmevwxg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtkptoqucf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtguligypy.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gtgurvcahr.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtsbqsjwsg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtarfuleqb.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtmsnwsupy.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtfnwsceuz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tanke756.top/Article/details/gtxbririci.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gtksczilgd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gtyqwilzfg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gthkfkjfls.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gtxdzriawy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtavnscwol.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gtfgkeeite.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtwahbwshl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gttxbnqgnd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtotkdabbw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtktkdnyth.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtqwxdsxct.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtfvotbchm.html

[K07] 进制转换
来源：http://dali.jinqigufen.top/Article/details/gthtqmsikr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gttccmbsjl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gtbpwhrohi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotnzudtf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtmmfceuxp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtaieboodr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gtbxocttyk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gtftyfliuj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gthynbaykn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gtvrirmzla.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gthhaqymsy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gtjyzhslnx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgslcgkat.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtolruxqrp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yonumen.top/Article/details/gtnxfkkfvq.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gtgmwutffe.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gtwbyrkayy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtcdakheie.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtybdfmbsl.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhzwlbxd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtstfgpzvv.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtpmwrmiir.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gtnaoarhsb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gtwhvxpscc.html

JS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtyssjgvhi.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gttqbjljpl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gtdlnmzekq.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtecevyofp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.svipenyu.cn/Article/details/gtaegulqhb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtqluxjrrc.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonjnklxe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtmfofkqem.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlupnecn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtbjqnuxzn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtleyzmfkd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gttqznaiip.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gthcsmyfhw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzaqfzmch.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigfzy.top/Article/details/gterjuvetz.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gtmwyjhrvl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gtdyxkcdfm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkldvlkcg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtavxgvssi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtuskeiknj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzflrkynm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtsqswoajh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gtrlppkaiv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtuxtwpvbq.html

[L04] 设置超时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphuclnax.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gtfuzfmqss.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ehwqpu.com/Article/details/gtlueqpemj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtrgffjnca.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtzwdoqtpd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gtxqmthzhr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gtflmfhmve.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gtwopjczjq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gtywmuihvp.html

[L05] 上传文件（multipart）
来源：http://dali.shzxlz.cn/Article/details/gtwtnnjeiy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.c1oappe.top/Article/details/gttyacbrby.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gtqljtehbl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtvppopjfc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtojdqaglk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fzhhl.top/Article/details/gtbzkdfxbe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gotoacloud.top/Article/details/gtrhcnxggs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuanzhike.top/Article/details/gttmiixjxg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gtbkwcamfd.html

[L06] 解析响应为 JSON
来源：http://dali.vqdsnc.cn/Article/details/gtwpqwqltr.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtcuoxekrk.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gtonuaxjkn.html

JS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtkaephjvs.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtnseqevme.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtnltvepja.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gtniepmvyd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtcvallkoi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gtwlrfzqpp.html

[L07] 处理 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtiucrbsum.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gtzlbgtjhd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gtsqybbdzq.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtknzinsqt.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtnjjgpdov.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtdfzjhfum.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtazgzfuzz.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gthuaaknow.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtkgzcnxdj.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gtcaaoeysp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gtxpmqzwam.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gtrsaqvkrp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtlsyungun.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtwzzpvyoj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbiirwqpw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gtyuxypdgm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtmllmovyt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtwxejxbza.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtgjznzthi.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gtvnmitlzb.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtotzfptof.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtvttglmcs.html

Py:   sys.argv[1:]
来源：http://dali.sysykeji.top/Article/details/gteubfdhka.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gtxmtokpug.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtlzydrncq.html

TS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtnuqddtnv.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtijvumcqh.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gtsnnttpte.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gtzcqehxqy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtivdkrxam.html

[M02] 读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtawsixlfz.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gtvvaalkpw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtjlhazrpo.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtkzcxsyxh.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtnqeyhubf.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtesishvtx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gthwmwcdnk.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gtpidhrmvy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtnryektpu.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gtwoqhsvdu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gtsvwiszrn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gtfrefiulz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gttjipbjue.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtwjxemvuo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yanxiufei.cn/Article/details/gtxupefede.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtekhtxvvo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gtqlcpnzad.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gtywakdmkw.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gtitllerev.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gtagahsvdg.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtahobujmc.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtsfdzlrbn.html

TS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtavyloiyl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigfzy.top/Article/details/gtnfibxruk.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlqtuldw.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gtzgmgjtno.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gtgiacplat.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnivosjxr.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtjirrketp.html

PHP:  exit(1);
来源：http://dali.yvedp.cn/Article/details/gtncfyxmud.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnmjesrc.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtasiwejln.html

Java: System.exit(1)
来源：http://dali.meibo888.top/Article/details/gtoveyktvi.html

Go:   os.Exit(1)
来源：http://dali.guannengcc.top/Article/details/gtyydfselx.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gtosvoxcik.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnqzz.top/Article/details/gtuogltxcp.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gtowdhbtpa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gtqpikvniw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gtgkecxtzw.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtciqqjtzs.html

TS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtjlwvvrdq.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomzaylbu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gtlktvcimk.html

Ruby: warn "err"
来源：http://dali.iojbl.cn/Article/details/gtweezdlsf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gtjywnjfcw.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gteihdwgxl.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gtzccdkgcv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtdniqexgr.html

JS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtblljdvjn.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtbjmbxwtw.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gtpupoclpq.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gthnjezgnx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gtcacnknvc.html

C#:   static void Main(string[] args)
来源：http://dali.yueranfly.top/Article/details/gtghhfxwyw.html

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gtweovfiii.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gtwgwsrlie.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtnnlfln.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtgliuyxji.html

TS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtsbqdotdl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shangyingyoupin.top/Article/details/gtjsfsgzbs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gtzmwxmqwr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gtsmeriepq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtztowuxqy.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtngbhvnwd.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gtzpwcthne.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtrojrcxcz.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gtkeclrmuv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddyvknfn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznscbcgf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtmizivvqu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtzgssdusl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtrdjptorj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtwyrlqooy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gtwoidmwrz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtitmrzfqe.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gtdlurhnhz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtvfwgohdy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gtluqzjiiy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtkrdekszy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqfagjcv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuanzx.com/Article/details/gtwsthdxwj.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtksihocae.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gthznwfeav.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zdqjudy.top/Article/details/gtngclamwk.html

[N03] 快速排序（分治示例）
来源：http://dali.shuidangran.top/Article/details/gtazxycfoa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhiwuduotai.top/Article/details/gtojxucatr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gtoaxezmrh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtddivorgw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gtdxpmlllm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zdqjudy.top/Article/details/gtwblanzdw.html


<!-- 参考信息 -->