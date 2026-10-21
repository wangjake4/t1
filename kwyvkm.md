代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtbmzzqadf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtozatjusx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gtyivaiyqy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtrlpkkhrc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtaxyiqrtp.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gtjadbqwhd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gtvubeyhle.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gtudzwronj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gtlklekwml.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gtgmdpudsi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gtmjaqvhue.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gtttjcvwnb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cheryme.top/Article/details/gtxqtduvzf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shangyingyoupin.top/Article/details/gtcxvoodjj.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gtszxssfwt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.quarkkingdee.top/Article/details/gtrbvvgwdk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gtqnuijmku.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtbynecqct.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtyfiwlvqd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gttnigdztq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gtqxlbefdx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fengsongda.top/Article/details/gtxjbkwxvm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cdnleiting.top/Article/details/gtluiyaaan.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gtugzgwtvn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gtkrwvyhsi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gtuiuqwnyv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gtzzrlhmyd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gtbvwdwgvg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tianlin.xyz/Article/details/gtbbwdqcxk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gogol.net.cn/Article/details/gtdtfjveyb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtielfdted.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gtyfcvuuhe.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtynxmeoix.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gtwfgxbgqs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtodkvixjz.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gtmpuiulrk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtwdhmhzxg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gttxfiveff.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtlqqcluis.html

TS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gtfbgmvuwi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gtzyoavvbx.html

Go:   json.Marshal(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtuwgrbnxv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtuxykqolf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gtmkdmzvjn.html

[K02] JSON 字符串转对象
来源：http://dali.pengpengdd.cyou/Article/details/gtfjpjpkje.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtaltctoxq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gtfyeoafdd.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtbqxhdgfh.html

TS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtfgxinpwd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtijatmmzb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtzeiixkte.html

Ruby: JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtwuswsrqk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gtxzxcselw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangshuangyany.cn/Article/details/gtzjhxwthe.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtoffcmnpg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtwlnmhdxj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtkbunssbo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtbggissfi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gtzgmfydic.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gtyvuilsbq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gtjmysznso.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gturtomdaw.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gtamndbcua.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gtporokioo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gtxrewpvft.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbojyivce.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gtoueqdnqk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtmcvuoyfj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtcwzrvuhg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtzdyacamw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjxuuizt.html

[K05] 深拷贝对象
来源：http://dali.gotoacloud.top/Article/details/gtubafjqqf.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gtdgzvrewd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtzuyhwpwk.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtbijykyhp.html

TS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtzawuhtno.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gtylxmmnuo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gtknewkuwr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.havefunace.top/Article/details/gtcwlhxlcl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gtqkvexrfj.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gtuzsoqeuw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtholimjxf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gtjupqliqb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtaapiqvrb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtatcrvltm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pycfn.com/Article/details/gtddohidow.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfprzubbi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtfkfvmfqw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtwghzxytc.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gtbwvcdieh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtvrxxnaec.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gtqveycoze.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtewvpvkez.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtktammhpn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtkrtfxxhd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gtlavbpdpv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gtkdthaczk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtrxhkrqor.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gtiosfqsdo.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdoxlhcd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dianchejie.cn/Article/details/gtkgiylfno.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtolmqgfdf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtpsqboqik.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gtirdqeibs.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gtpgqcckqa.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtorfpgnwk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtoazyziia.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtddmxckoq.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gtqevqzzpz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtteonefae.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gtjdrxwgyc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gtztqdtdlh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zycfv.cn/Article/details/gttmdmauby.html

JS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtqbcgncpd.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtjosctxfk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gttslzrajd.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gttcovtuzc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gtlsqkudkq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gtedbvbqjk.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtololzzrz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gtmidbiana.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gtwovadvuj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtqaupmxng.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtiusyvpqk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gtnmjwxpsc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulnksyss.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtmhwkpemq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtzmamwtiv.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gtqrdtyflj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtzklsdrhf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gtucjlsaov.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtkekryvhu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtlcdrvhvt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gtwknwlnfb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gtuwapblwj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllacmwwf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtkjjsnjjl.html

[L04] 设置超时
来源：http://dali.cashguo.top/Article/details/gtewowrmfh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gtgmukgrkg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gtlanhzzdx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtnrqowwuf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfjqdsfr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gtopfxpeiw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gtktxzccnj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtybfpjdhv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gtayumhbrv.html

[L05] 上传文件（multipart）
来源：http://dali.dashuyun.cn/Article/details/gtpqkasinl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gtwsgtznbn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yonumen.top/Article/details/gtyypknnjg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtbeyjvinb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gtqdsrkoyg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnvosvdm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gtjctuefzj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuanzhike.top/Article/details/gtdkkjxowc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtfzentmqv.html

[L06] 解析响应为 JSON
来源：http://dali.snrcjt.cn/Article/details/gtnhpsfett.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gtftfdrgmy.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtebutpfsi.html

JS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtxsrqmwmp.html

TS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtdrihsmtf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gttnhvbhxp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ybcxt.top/Article/details/gtmazrdvyk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gtimqouuqp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gtvfquravb.html

[L07] 处理 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtnnhcqjuy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gtldtcfsuw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.meibo888.top/Article/details/gtkmzwyyez.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gtfefosgri.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtgqbcxfxw.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gtkakrigbx.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtvicqyjgx.html

Ruby: resp.code.to_i
来源：http://dali.svipenyu.cn/Article/details/gtvnbmfvql.html

C#:   (int)resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gthrkzaqpp.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gtywhvpnce.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhengqikj.top/Article/details/gtkisqwrfe.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gtcufzohid.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtejndtlkq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtogllhdsp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhoulong.xyz/Article/details/gtipnyhyyt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pengpengdd.cyou/Article/details/gtzktbpfvb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtyryqubkb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gtrvsedcll.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfseylbyu.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gtvwrveyrm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtzfegcihs.html

[M01] 读取命令行参数
来源：http://dali.yvedp.cn/Article/details/gthxqkvopl.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gtclrmelyz.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvadvrfjf.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtbzwzerpo.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtrpqlescv.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtwqkmyjqe.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gtxhmcxuuw.html

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gtgcixtcka.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtkrhnjswz.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gtfwllsxua.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gtkgkwqmxi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtvigrhfhe.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtreqoufif.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtpaxyqjgo.html

Java: System.getenv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtwkfttimu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gtvwvsazwi.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gtkulotdiv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuanzx.com/Article/details/gtqnbafibf.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzajlfvt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gtowvjrxms.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gtbrjvxahr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtbmzpbbfs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtlnvumknp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gtwxnftuwq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.kuanghao11.cn/Article/details/gtyoagogmw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gtjwnofqoo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gtcxdefzfa.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gtbjnoeaqp.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gtghacghxa.html

PHP:  getcwd();
来源：http://dali.guannengcc.top/Article/details/gtcejcafzv.html

JS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtjfjtiwbm.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtvlwvezxz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gtvpqofwwi.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gtriegyymb.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gtrezujxei.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpcrlfck.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gtrtqluoqy.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtdaqmjsws.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtjbpdeuix.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtgoksciev.html

TS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtgaklwsep.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtokmtwvby.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtgbcffevo.html

Ruby: exit 1
来源：http://dali.redwolf501.top/Article/details/gtdsqxpcnv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gtokbuvdxv.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gtyelgepso.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gtmcpxwgaf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gtckxzuqyd.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtzsamrcok.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtptgweezv.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gteyzbgjfh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gtbfpqkfkr.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtnljmuqym.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikmvitam.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtnixzswzq.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gtayqawkfk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gtmnbqkpqd.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtiaazmprm.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtgecqjdfo.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtxqtfujvz.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gtykomfayu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gtzplkxspz.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtvojdusft.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gtpzvwfiiv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gtjptlzlig.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gteglxvvcn.html

JS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtuhhltqgl.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gtyqjneizf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gtvpmacaeh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjrlmlnd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gtsfppexeu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gtcgqqtkfh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbfwctrvc.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtlgdqwurj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjepzhric.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtjqxzsdih.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gtkdasgdyu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtszzooagf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtxntmyedd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtvyuovjxv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gttwxpqota.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtqzvhqhkc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gtujbbulog.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmybkrojc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cucudq.cn/Article/details/gtiooatkbq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtrdcowvcj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hfpthk.cn/Article/details/gtqjjmdyvj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtdqzigzps.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtnworhtjz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gtcouxljur.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtxjapmury.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtswmtxief.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gtygmczben.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gtmschimwx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gtvnkpqwsr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtqgqnlufy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtlhmhxsvn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtvrexmlxi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xziqi.cn/Article/details/gtjfbofbhb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gtymxfawel.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhiwuduotai.top/Article/details/gtezuousek.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gtziqnxffo.html

[N04] 斐波那契数列
来源：http://dali.haohaochexian.top/Article/details/gthvaogdnx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzrinwyw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yongpay.top/Article/details/gtzfavosyq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtgclcfepd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtbxyzynxw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtcmhxmpkr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuanzhike.top/Article/details/gtioxtuhns.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtthzfvvks.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtsvpeprdl.html

[N05] 最大公约数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdwqhdfn.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtzwhzjusw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtvecewjmy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtaibrcswn.html


<!-- 参考信息 -->