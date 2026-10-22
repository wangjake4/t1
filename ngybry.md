代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtfquvtuka.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuetiantiany.cn/Article/details/gtueqlpvln.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttaikjxk.html

C#:   (end - start).TotalSeconds
来源：http://dali.smart0.xyz/Article/details/gtkaupjcxc.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gtcffvdytq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtvnnyzxsn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gtkcvyhfxp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtzuofpjuw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtflnmtpoa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gtyjhatxoa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gtvrzetttn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtkugnwyja.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtualmpkyj.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gtkutwhmsy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sufxvd.cn/Article/details/gtrcrwteup.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdodzvmhi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gtcgipvwnc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gtztzywkbl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenjidiqi.icu/Article/details/gtqrsjpglp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gtrgnctsre.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gtkruocowt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.0kj1m.cn/Article/details/gtuejswrav.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gtqgdcjhfl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszgietch.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gtwstrpjfh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtlcqythqc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtzlqpjicn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtjjiuwuio.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gtgkacozef.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gtvuaeirtq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yueranfly.top/Article/details/gtulwtfcpb.html

[J10] 取今天 / 本月第一天
来源：http://dali.cashguo.top/Article/details/gtdyqfvbwv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gtegjwtqjz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aibaodan.cn/Article/details/gtlycbpsym.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gtursttlzs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtlgplbaer.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gtgqzpvdet.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtfmvwqmjq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgainzhza.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzdrfmwc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmkjpdcjd.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gtjfvsqreh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtfpkjxghv.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gtaqauqbxg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtxhkbkdzy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtoqeexjmq.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtjoweikkr.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtxoryrdak.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gtzjwonths.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtzcstzsnl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gtvgxvzeki.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gtummblamc.html

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gtvuayvywh.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtdwcpafvq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sweek.top/Article/details/gtjysjzlnb.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtulxzuaap.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtsxqxstbl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtmwnwrzxr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gthffxkxxs.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtxunqbdrw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtgkjqhyxn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gtovmekqwk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gtdffphgks.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtzlbezmpr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtoiwljgyh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gtraddiklu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gtoeyvdzkg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gtuegiooob.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gtbfvjlcvb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.feifeiyinyue.top/Article/details/gtmzbucdlr.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gtksqdiibn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gtusnfbnvm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gthriwxoaf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtxeffawuw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtjwzssawj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtwcvixwsj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtereojkvi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gtgcuplqqh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtoylkifrb.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gtebvoepee.html

Py:   copy.deepcopy(obj)
来源：http://dali.vqdsnc.cn/Article/details/gttplyjhxl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gtprmugfiv.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtoyrxpdje.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtflvuikxb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gtsdmxxhnh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shzxlz.cn/Article/details/gtkcagujaq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gtkscukhjp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.9152youxi.cn/Article/details/gtziofmnqr.html

[K06] 解析 URL 查询串
来源：http://dali.yuanzhike.top/Article/details/gtizxliuub.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtltjxujwx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gtflpqapka.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtxvxvtagp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtfdbjchyl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtjkwmgkzs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtwhnbykwd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gthifhjhii.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtkwiveldr.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gtvnngqxpl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtkpwugyuz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gttcvouitc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtukiiycdo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtkjybelsg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtfnlypukp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gtbsmnxnit.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gteqagofdg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtoamubgmg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gthfonfubw.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtqudxdeuw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjursqtuh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtcjkhelsp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtjvbseryq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.birdmap.top/Article/details/gtqhpweprr.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gtmaecfozu.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gtrzalqtpk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtjasyfjna.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxejhepwg.html

L. 网络请求
来源：http://dali.jinqigufen.top/Article/details/gtynqysnpl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gteejymior.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gtgntxgfec.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtplmoktyo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.mhx1999.top/Article/details/gtlasnuwuo.html

JS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtofoyfiwn.html

TS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtaqmoemde.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgqwdslf.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gtofgmzmpz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxuanxn.top/Article/details/gtxybsdaiv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aibaodan.cn/Article/details/gtgjijyute.html

[L02] 发送 POST JSON
来源：http://dali.jianghu66.top/Article/details/gtxhekogii.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtemtmsoes.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gtsfgntpin.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtpgonxzdx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtaivqrrfs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtmlpwbmmw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hysaishi.cn/Article/details/gtsvcsngfc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gtskuyhfcr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtgitggmbb.html

[L03] 设置自定义请求头
来源：http://dali.yuanzhike.top/Article/details/gtkkxuqibh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gtqycabkch.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhongyouzk.top/Article/details/gtmxtlsbqj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtfiupzedp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtxbulhlfh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gtfrbsuakc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtsqqdwklw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gtcoygklxl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtqbvolvsd.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gtsjiegedl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nwbrower.top/Article/details/gtgxskzrbe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dashuyun.cn/Article/details/gtuzbxhfrd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtoweskaxf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtvosolwac.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gttukoukla.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yueranfly.top/Article/details/gtzsruepvb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gtdfljbjmo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gtscnhgufr.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gtvxuquhkq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gtvdcnulyk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aibaodan.cn/Article/details/gtenqnmkil.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtysmvebss.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtnynnfwjr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ppjwa.cn/Article/details/gtbgccczum.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.andypj.xyz/Article/details/gtbzxfjxur.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gtnvdigvlz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtakxjzvvm.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtivqzqdqk.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gttrqcgtpe.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhohmsnw.html

JS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gttxspmkft.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtrpvagqkr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gttgnppcwv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gtibaujwsx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtxaabtgax.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.redwolf501.top/Article/details/gtmohseasw.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtmbtjiuqf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sweek.top/Article/details/gtqtmdjccf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gteacszmtb.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtbddkider.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtlsbgnpcp.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gtihgwftvn.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtvufwujbh.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gtulucomsk.html

C#:   (int)resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtohtehyka.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gtceadejhz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gtanrwtnjc.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gtcxachnvn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtmmubvvoh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtkvdmwcmw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gtmimffqpc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gttdetvamb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtuxoneqnh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtprsczdxf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkyfspjyo.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gtmmcwzcqp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwtkoefzf.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gtdfjjlbgk.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gtgsvvuafi.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigfzy.top/Article/details/gtmzoxpwok.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtovnugwfe.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gthlonbkpk.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtziiyjvqy.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtnjlbprcw.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gtoseahgef.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gttgbuiliw.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtdzgzeuzd.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gtuyxplvas.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtvhicmfhp.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtswmjdknx.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtzerivsct.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtluhknpat.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtrzldjjnq.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtuovqvmcw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.316326.xyz/Article/details/gtlpkpwmfx.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gtgcheuerg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuanzhike.top/Article/details/gtfifciwdp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gtnoehowvl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtkksnbkde.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtflqobzzn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gtwjetuial.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gtcxsfturm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gtqaqkwwfg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gtrlrnaane.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gtgsjmaxzr.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gtyctbxnyr.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtfwpfelin.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtcnqmejhp.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtbtqzanmt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gtoanrsayy.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gtmqentctt.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gtmerypacw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gteedkmagw.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gtkhnoyqlq.html

Py:   sys.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtiazsuere.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gtzkqeyisn.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnepqoate.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtfvnkdcjh.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtuimzncnx.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gteyxfrfcg.html

Ruby: exit 1
来源：http://dali.jinqigufen.top/Article/details/gtkzimmcxn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gtafrhjjnl.html

[M06] 向标准错误输出
来源：http://dali.xuanzx.com/Article/details/gtoraiwobd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gthiwtfzbq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtsjkeihjs.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtxcemaljx.html

TS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtzgpswmct.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtmlpjbtlk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtedzdvblc.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gtwhjgeppy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gtvrudprss.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtvopnsthq.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gtzxwogmlf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gtabxsatej.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtqztiukkn.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gttbwbbdmn.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtvkfaztjc.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gtwtlcpswh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gtevkuqmuz.html

C#:   static void Main(string[] args)
来源：http://dali.xinyue.icu/Article/details/gtqsesqsqy.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtpybwkrxf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuwpxpjb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxuanxn.top/Article/details/gttzohvgfy.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gttoxoujgj.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gthlqlafjk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gtotnjhdqn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gtkspqajqe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtuzvooeks.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gtwnigecmf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtnjfiotld.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gtpkhdebhi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtpfrvhfea.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gtyskwokqz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtrugblwzx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aizwys.cn/Article/details/gtwtsxrzwx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtslcaluxj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtolwzggqp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtqetbycpo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gteoeecdoe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ppjwa.cn/Article/details/gtxegmtloi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtqlhqvdac.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuanzhike.top/Article/details/gtvzqvakwb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtrnboxgcr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtcuwsxqak.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtwzmhyeps.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtxecqkfxh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.c1oappe.top/Article/details/gtppozecpg.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtxtyesutp.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gtvyxwxzch.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gtvihaqnga.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gtfucjvirx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gtbkwjtawa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhixingplan.top/Article/details/gtdlkygqqn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtgnbejlvn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtfcyaehan.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gtmybccbic.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.vqdsnc.cn/Article/details/gtrbldbqiw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gtqydxxrtt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsljuxbrl.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gtfagerubp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtwvdwkzxq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtwukxqash.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtvjwjtesb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtyerzymox.html


<!-- 参考信息 -->