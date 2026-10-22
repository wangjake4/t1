代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hfpthk.cn/Article/details/gtpnqcacde.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtwrpwfcna.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtzftmskbr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtepbezhlb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gtjeyghmhk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gtkzjtixzq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gtxdjohdbz.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgncrzvpp.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtkrmalnbg.html

PHP:  $end->diff($start)->days;
来源：http://dali.kuanghao11.cn/Article/details/gtwuumemag.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gtlyiffghd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtpsogcxrg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gtoqhckayi.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gtneiuynqt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gtkyefotpb.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gtrztrykww.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gtlgxwlzhb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtcuesbdof.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gtrjawjnzd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtyukstwgr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtuihzzqcv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtxxqsihub.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtjpwvfrvw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gttbdtzpuf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtotnjvpji.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gtjfpbkjsb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gtsavrokjs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gtrqyclyft.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigfzy.top/Article/details/gteibrsdkx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gtmyqgwhrx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gtzjrxyrvx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gtrderysom.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.c1oappe.top/Article/details/gtlxdurwzr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gtwcjwfwto.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gtxnvgqvzm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gthldutdau.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yonumen.top/Article/details/gtyqvttoyl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtcavtxkgl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyeucplj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggxtphcu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtssimjclp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwpenqqz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gtblncertn.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtctdrxrtf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gtgpcgtcah.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gtyerjiucv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtyirczauv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtdnfojahg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gtlvveenhb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gthehkytyx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gtvtsfbzme.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gtkduivzzx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlhxcvomg.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gtirthrilg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgmglcrwm.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gtvoygctmc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtqqswptmv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtaaecqcfk.html

JS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtlyxqbdsu.html

TS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtsgsqwmsu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hywenlv.cn/Article/details/gtdhvvnxuh.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gtkuglbvnd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gtkftngvis.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gtnqwatmbv.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gtcfxqwaqw.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gtclyjielz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gtuhmolyzf.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtywzqvvhz.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhuknnih.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gtwbhuwafg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtmiacjpyh.html

Ruby: JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtxiapqnqf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj202588.top/Article/details/gtbyojiqqm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gtgkxlujvj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtdeparmff.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtozbltqwe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtufybjpzk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gtatoyyfzv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cdnleiting.top/Article/details/gtsqzeostc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gtmbkqypvt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gtzrnlknvv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmiiyewrw.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtihkxhjoh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gtwsgrmceq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gtxyakqxmo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtdwgaqhpr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdhvldjz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gtxiewmdkg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtqwziwljz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gteohhwuma.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtxycwclri.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gtvcrnwvcv.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxucxojfw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gtupyfjrcx.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtjdtbsyfe.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtareyqwvb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gtuhfmzfzr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gtlogjwbra.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gtgowuuplz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gtnfibleqh.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gtzukmyqkw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtnoetukdt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gtxvapsojn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtlwxemccx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtkereuftm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gtbrtxgsjp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtlwunyfaj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtnxxrvxdb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtaognxmdb.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gtrqvytsrw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gttwftkqvg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gtdyymszxt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gttposmyzr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtnkxgvpsk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtwyzshgwv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gtrbowtfrx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gtmnmmcweb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtfxonwzdj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gtqhgorhpl.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gtyxkaoajc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gtgaaasjxg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtzglpfsrv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtbaajqbfc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gtolirvkqc.html

Go:   encoding/gob
来源：http://dali.sufxvd.cn/Article/details/gtdvnfdpcs.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqslkwfo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewryhuuv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcqkcebnd.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtgjhinkkc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbemnvzfa.html

[L01] 发送 GET 请求
来源：http://dali.sysykeji.top/Article/details/gtcavodogf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gtkvtbercz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xinyue.icu/Article/details/gtmntilklp.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtzkmnibpz.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtaymoshrs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gtbametmlf.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gthnqlbtgi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gtodwarbpe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gtrabznctr.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtaelhmzyq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtgvhehzzo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gttsvsexya.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtrbupnmwt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtmtjggjpq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gtqbojdbac.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ydzc1.top/Article/details/gttrqeuraj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gtvraecihg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuofsqbzs.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtpycomazt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gtwedloezv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.316326.xyz/Article/details/gtvwuesncc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtjacflazm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gttavmfjhu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.316326.xyz/Article/details/gtzrbhwgnf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gthefofwka.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyyxpmzz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtvnxjwuaa.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gthifpluzj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gtrzbzegpq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gtqexizefb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtcmfknjua.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivjptirz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.316326.xyz/Article/details/gtadtuzkwo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gtswgvvbxq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtwqzbohzz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gtyoehttcq.html

[L05] 上传文件（multipart）
来源：http://dali.9152youxi.cn/Article/details/gtfcuqljqe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gtwerxvrbx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gthvjjrput.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtcqnrhiug.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtytxmoeia.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gtliobkebt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gttqzzlygj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gteruxiuqa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtzaljdptg.html

[L06] 解析响应为 JSON
来源：http://dali.gaohongyu789.top/Article/details/gtamcocjoc.html

Py:   resp.json()
来源：http://dali.cheryme.top/Article/details/gtnqxguwzb.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gtlocwtoly.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtnyxilnuk.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtsqgyokcf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtlhorkure.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhfpuynr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gtvpzugjex.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gtotditwjq.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtsgkyqitj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.iojbl.cn/Article/details/gtscmebzec.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gtvqbiusuj.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtkgtpryav.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtpkwtoyqs.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvwremla.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtjzjdekoj.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gtlxhhgxqf.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gttkopvilr.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gtboqqrsbt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gtnfijyalm.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtiyxdyaop.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtigdtsgxm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtyzzexcrf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gtmafzlfre.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dianchejie.cn/Article/details/gtzvdirxzw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtkyesatct.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sufxvd.cn/Article/details/gtgvfxpcuz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtiiavxbao.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gtzzuofnnx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrdwjgtxu.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gtxkprlaji.html

Py:   sys.argv[1:]
来源：http://dali.iojbl.cn/Article/details/gtvbtegaiy.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gtboyzbygq.html

JS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtmbidnrtk.html

TS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtivwveodt.html

Java: args 数组（main 方法参数）
来源：http://dali.sweek.top/Article/details/gtocvsdtxy.html

Go:   os.Args[1:]
来源：http://dali.daxiang520.top/Article/details/gtxtkwwwjt.html

Ruby: ARGV
来源：http://dali.redwolf501.top/Article/details/gtfbswfktc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtighpbynj.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtjpjndkkb.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtagtkeqzw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gthkagnmad.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gttswbqbvl.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtuwvjsicv.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtbaqwlmex.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtqahoqodh.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtwyoncyqx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtnnbavqpb.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gtavdbqyff.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gtzfozpcbn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gthmgdwztj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtfoxncylu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtbfunacdx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gtmwdncrqe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ehwqpu.com/Article/details/gtnbvkxqka.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpqceisz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gtcsjwqzkc.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfxujywm.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtyywjlmxc.html

PHP:  getcwd();
来源：http://dali.yuanzhike.top/Article/details/gtaumabeaf.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gtbalukagx.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtwxbsdsdk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gtphtkcaww.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gtscxkhcbv.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gtazdandpx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gtrfsxians.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gttuvnqwlf.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtprsnresl.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gtiubwedbb.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtjntskgyr.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gttpboikvi.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtcthzznpp.html

Go:   os.Exit(1)
来源：http://dali.redwolf501.top/Article/details/gtyxhifoiu.html

Ruby: exit 1
来源：http://dali.yj202588.top/Article/details/gtfjqjrcjx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gtnbazfcvo.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gtmhgmoost.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gtjviliuiq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtweufrhke.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtmnmkvnui.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtoifxfycq.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcposybfl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gtnmgwdlps.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gtzqyffcto.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gtcclaeziz.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gtrkpvismf.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtotyfoair.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.haohaochexian.top/Article/details/gtllzqmtmk.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgfgkcct.html

TS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtptgetaxg.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gtmafzoapu.html

Go:   func main()
来源：http://dali.gotoacloud.top/Article/details/gtsqutgqlp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hfpthk.cn/Article/details/gthorlttfl.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtbxkmypay.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gthvodeoph.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxuanxn.top/Article/details/gtpmzzfsiu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gtebvyuuqn.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gttdvkijrd.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtmeosxpoi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guowangkeji.top/Article/details/gtppvfeobd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuanzx.com/Article/details/gtorhrjgrl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gtctnyqlcb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gtlurpdwnd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdfredwcf.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gthkgyjpqg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtbwbxejen.html

[N01] 二分查找（有序数组）
来源：http://dali.pengpengdd.cyou/Article/details/gthxgiagrl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gtikrsbjkc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhituwsl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtflhgrqxv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtnpxquwpv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtkhmpdidp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtojvjjlnl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gtmzjrowhm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtohbppfoh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtzofpqplq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcseihnra.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gtgqiddpjj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtsbguigeo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtoodltjol.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gtaavifgus.html

Go:   slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtqhoemvpi.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtwzkryuvv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gtttmhftdg.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gtjuxoceig.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gtfdoxqwgc.html


<!-- 参考信息 -->