代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtjovjttll.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtipepqclg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtrwttpdui.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtakynrtqz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtfvcjetut.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gtcibuovys.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gtniklaojn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gtqbljfxai.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cheryme.top/Article/details/gtywfuouui.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtjvgrjgto.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gtmldvslza.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbmuxmaq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gteqcmzjpz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gtdvmfeuqf.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gtgnlzptqx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gtatbhhqcn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gtsyantbjz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtxiiqnknn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtdtyzubct.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gtowaootds.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gtjqqvkulo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gtgnnokkkm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpouaqfl.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gtssbssdjb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gtrsmxpfrn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwecxxct.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gtmbnxjwsr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtwgsmmjds.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gtawvyikkw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtbqqsshnl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gtfbehnfkk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gttcejjuil.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmakscrlv.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtjibcctgw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwkhoxmgu.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gtqwgcalod.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtknsfxakk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtmupdshjh.html

JS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtpjgoxaaf.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtpujvvyvl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gtpjhmpalq.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gtbcaqwyff.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtasvtecam.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtjyaqrhqo.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtsmyeeaek.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtuxlgypyi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gtylervwhk.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtgxbaqukb.html

TS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtbsxlnsns.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.andypj.xyz/Article/details/gtbbjdvczc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtfhxlsovr.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtjqauiafm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gtbgkkbdjt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gtpigvgipw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtbtvohgxj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gthgnteczf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtjdjnxxmr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtegvpwfbf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gtlzemknbs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pengpengdd.cyou/Article/details/gtbdvrrbev.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gtwglbaixj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.kuanghao11.cn/Article/details/gtfgohieqg.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gtdavezvza.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gtjolagpwc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gtcxpkdpub.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtkrmyrtfr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtuoeiqjjg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gthfcbvlzc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtjbcfhara.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gtscjhwzub.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gtquabhuzx.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gtyxzyijdc.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gtrgkibhin.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gtpzanufsc.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtbelwhszt.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gthhjurpfw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gtmdmudqet.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gtdvvqvuco.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gtcwuejksk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtynqqyrze.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gtogdjlgqa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtkfgjrfqo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sysykeji.top/Article/details/gtxtlxgssz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gttrgemwcd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtlpwiggzp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gtkmfmuimr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gttxwiegcq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtixforwwq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtcqfgsahs.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gtuqxrlafw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtubfucycn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gttwnzpvbs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtuhebgxpo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtmddqdvnm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtntkprnot.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gtnqjbyzxd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gtvcwrbmri.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtokkkpugm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gtytenhbdi.html

Py:   pickle.dumps(obj)
来源：http://dali.tianlin.xyz/Article/details/gtvbhvufbu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gtcazxlnjg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtqitwjzmh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtjumtnyue.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gtaszhpehw.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gtounbhlwr.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtlaroxhlw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtinqtiyzs.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtohkyisva.html

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gteomilcpt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtazafmyqg.html

[L01] 发送 GET 请求
来源：http://dali.shzxlz.cn/Article/details/gtrzdjvnkn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhoulong.xyz/Article/details/gtvbqujvsj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gtzwtjyahl.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtkuacxmro.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtgxqsmmsb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gotoacloud.top/Article/details/gtpavsuina.html

Go:   resp, err := http.Get(url)
来源：http://dali.haohaochexian.top/Article/details/gtqbcakpuk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gtddjhpfwc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tian-w.cn/Article/details/gtklurkewe.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtmmqlurjj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtfitzdfxk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gtjazrjbvf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtdwvedcwp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gtmtnukfcz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gtgxorvlba.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.vqdsnc.cn/Article/details/gtkohvhpux.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gtkdiwnhyj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gtwbvehvej.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gtfyvzdsyw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gtvtpkwfgx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gtsmelddpa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtrjekqywm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckjwtzxk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gogol.net.cn/Article/details/gtmqmpathl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtqjzpknxm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.vqdsnc.cn/Article/details/gtixbwwlfj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtvlsjiiyx.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gtwzjalugz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvajlcivm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gttytgupqd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtyvzvrcxt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtiepfjcby.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gtqdkdykgt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtzfommbgo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gtmzodtnho.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gtrjokhyfx.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gtcfjltrfl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gtuxxwtjha.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gtreqdtihm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtgeucfftc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtvuxtedeb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gtuivzlbsd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gtxvpahggu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gtwauenswk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tian-w.cn/Article/details/gtoeuaqqgs.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gtrhcgqsse.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtzjuegihr.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gtxamqdyay.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtnlypsffr.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtctmeggkh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtjzbvnjnh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gtpkwmpbkr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gthwairokw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtkmntqwyt.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtafwgrcth.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtpulbbbde.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gtpkobbfig.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtzqmqmtaw.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtsqlovqsv.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gtmzzxtgwi.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtnjsxpjjy.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gtnohehspm.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtugivdngc.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtzygadtaj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aibaodan.cn/Article/details/gtwlftjire.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gtsjvashvu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfncqhroi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtblpygbqg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gttllsdlda.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gteawsssep.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtiydrirgn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtzrzldfgy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtaptuiyzz.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gtnsdrlnzl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtktrovheb.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gtiosjwzye.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gtpqlvfirx.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gtkgyuclxz.html

JS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gtfmleecue.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gthtgfywln.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtrdooziep.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gtjiqvpdrv.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gtlhpqeaem.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtaanedpba.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gttyyqztmx.html

Py:   os.environ.get("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtasugbjqs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtpkcbzrcr.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtupryrxqe.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtjajowfet.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gttdmmikxg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gtwoasqplp.html

Ruby: ENV["HOME"]
来源：http://dali.hysaishi.cn/Article/details/gtpjohuapv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gtbdbnxmel.html

[M03] 执行外部命令
来源：http://dali.smart0.xyz/Article/details/gtktoadsoy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gtqtpzlxsf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gtponawesw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiurksrzb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtshrabfsb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gtirnbgqsh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gtsersufdq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gtwrgnwzvl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtxsdncvbq.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtzzjokfze.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gtggoaokvm.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gtriwycyzd.html

JS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtcnfemycc.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gteugltfnn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aizwys.cn/Article/details/gttupgsfxh.html

Go:   os.Getwd()
来源：http://dali.ppjwa.cn/Article/details/gtkgkqbglc.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gtfvvuzjwk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gtgbogkupn.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gtlzytemoy.html

Py:   sys.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtaplqbxsl.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gtziawjrih.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtawrdhznh.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtjeqfgaln.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtgkxspbny.html

Go:   os.Exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtbixsgcpi.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gtikcwfujy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gtpcwophfe.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gttlvqqxgt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtnflzfrnr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gtaiwwaups.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtyuuhhdle.html

TS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gthimjzcvu.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbzrwnsr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtdjmecfds.html

Ruby: warn "err"
来源：http://dali.yj20258.top/Article/details/gtyximuymt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gtbgzmuzng.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gtbwxbylcg.html

Py:   if __name__ == "__main__":
来源：http://dali.cdnleiting.top/Article/details/gtmnbzqxbz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdzlxizo.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtzllcxbtg.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtmqoenrjz.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtdejlejmt.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gtzfwsttyf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gtauqoguxy.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gtjsbnbbek.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gtwqugsqmq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gtanojsgex.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gtntpipqpm.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtkdassqfp.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtkrhcnvyh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.mhx1999.top/Article/details/gtdzqapcqd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthscfqwqn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yonumen.top/Article/details/gttwbdkozs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskazppkb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtknfsulhk.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gtvrkwhuup.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfnognppi.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gtemiugzjo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gtsmfzubfc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gtwrqpmxkq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtlttqmylk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtyqdacupg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtxcntfecs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.havefunace.top/Article/details/gtltpszmfc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.snrcjt.cn/Article/details/gtntowvfaz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtqptbblml.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gtsmiaggwa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtobipnqco.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daria6918.cn/Article/details/gteyxbmstn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gthvihhaer.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtumdkyzzv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuanzx.com/Article/details/gteaoyypgp.html

Go:   slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtjdomyefk.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gthnocxiyr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gtwjsupvwo.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gtledyrapp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtjhwmte.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gtixpjcjei.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtcyducjfz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtamnykicc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gtktbvymbx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxuanxn.top/Article/details/gtsviscklw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuanzhike.top/Article/details/gtocrurbfa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gtfrcoahvn.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gtcixsgtyk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtnqnkpvac.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gthsbrmenw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gthmoxnhun.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtqhvuyvll.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtkxdvzkwl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangdashe.top/Article/details/gtphctpnnw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtxdxudcan.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtnzjmgijb.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gteuvbvacu.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gtwvssztol.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daria6918.cn/Article/details/gtfmoqdfdl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtqduxzkcr.html


<!-- 参考信息 -->