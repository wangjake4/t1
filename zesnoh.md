代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtkicxykln.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtplkefoyi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwftporj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gthyhncjsd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gtzbvlkkql.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gtgrqrvtzh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxosqwma.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gtafiidyju.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gtfgggjiie.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gtufpuwjmf.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtoruzhixb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigfzy.top/Article/details/gtvmyahvej.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtsukivvod.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtgjvejsvh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtgquojkdg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gtmjcxpfmc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gttygxtvod.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gtxlosqbda.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gtvzussgdh.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gtamnrldpw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenjidiqi.icu/Article/details/gtbvwteiav.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gtgmpprnqv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtisstawrv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuanzx.com/Article/details/gtsodvsoki.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gtbdlfboun.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gtdzsweimy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gtsedhevxm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtocldpnmw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxvqwpbmq.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gtndjdwbgg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqkdawjmx.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenlongwang.top/Article/details/gtoydoewas.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtaqdgpzdv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtmspsfvow.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtjwoymxds.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtildxocuu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fzhhl.top/Article/details/gtsmqethbq.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gtbquchtrh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gtsaqrphos.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gtjmzzhjny.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gtgjbtcexu.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gtqslxjrqs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gtpynsdduk.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtpghbyndv.html

TS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gthmbnpiyp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gteyxcdlpd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtblemywnz.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gthcdnadjb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gttysnixcc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtsyzntdsl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gttiipztnb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gthfmwxbol.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtdfrulhnx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtpjozaarx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gtzfxysezz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gtuhyrgxoh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenlongwang.top/Article/details/gtwweuomhx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gtzqtpsnvv.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtpedlobjn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cheryme.top/Article/details/gtwlzyfykx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtqszvkael.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtoklqtnfp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gtzkvapgnd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtfxghkjaz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtlbstfrwd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gttqwdsltm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtvbipnood.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gtlugmufhx.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gtrdkaodfe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yangfankeji.com/Article/details/gtozpcqlsf.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtfnpdmqrq.html

TS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtitfhnnli.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gtgwafeugu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gtbefdmtpd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gtughomzos.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gtbhanqjxr.html

[K06] 解析 URL 查询串
来源：http://dali.shuidangran.top/Article/details/gtlqitklxd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtvkyekwlt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gtitzqltbe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtvjbilvbs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtxcdibfgz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jlsjyb.cn/Article/details/gtvxharwic.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtcqhtixpc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtbybfscum.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtscijqxkb.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gtcdruafpp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtejyuzuqk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fengsongda.top/Article/details/gttyprchcz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtmkqlrmki.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtafwakeec.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gteymysnhb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zdqjudy.top/Article/details/gtgjcqfrki.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gttkqamerl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtkmunqbrm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gtcvxecbfw.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtasxpxlvu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sufxvd.cn/Article/details/gtyiyixsnr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucfhcumw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtztgxjzxt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gtsrutvyof.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gtpixvdizd.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gtbccxkvtz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtwavclfkk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gttavbgxkq.html

L. 网络请求
来源：http://dali.316326.xyz/Article/details/gtkwmglyqm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjktghhcc.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gtpcxpoifh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gthbstmner.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gtaremefjp.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtsvanajwk.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtbficvkqq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnhsrpsg.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gtpfgmzjid.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gtmzywqvmw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtmbdyxodd.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigjotwht.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtphboootj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gtjumnpsmg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gthvdaeaci.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtcyhiyuft.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtbujmeyeb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xziqi.cn/Article/details/gtxvhtcaeb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttedzgofd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sxryk.cn/Article/details/gtjfkcochu.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gteppfethl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gtxojmalbd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gtlrhxkodc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtkqtckvii.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtgjxtvthr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.316326.xyz/Article/details/gtufwrswdd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtwunscaqd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigufen.top/Article/details/gttpaafvlw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtailuhjnv.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gteztnrgvd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gtiwdefuks.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hysaishi.cn/Article/details/gtuzhqwfbk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtzmlueotm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtcglwyfma.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gtzbztjfsr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gtmcgrabym.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigfzy.top/Article/details/gtjtbmdsoc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtynzdzcjb.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gtvplbrzbv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gtvfqpscxm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gtidwambkd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtzyrrzsjf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtzcbqcceu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gtsqvseetc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hongshengwenyu.top/Article/details/gtdmbjgtnu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gtrzxiwanm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtmlafnlff.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gtmfqqswyy.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtysuwmwwk.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtsgwdyyje.html

JS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtfmuchubm.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtcijrbutr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtcffqgvur.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gtwmpmusph.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gtzpfopmyy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gtmffkyllt.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycvvhlll.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gtxiquskrg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gtbpcetyip.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtazjyahrz.html

TS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwofmmywv.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtokoframh.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtzwhhsofm.html

Ruby: resp.code.to_i
来源：http://dali.yueranfly.top/Article/details/gttoldlwnw.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtfrnqwjvl.html

[L08] 并发请求多个地址
来源：http://dali.smart0.xyz/Article/details/gtcjrbyzdj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cucudq.cn/Article/details/gtlxslkxja.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gtsxmmqfnr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gteopdvbsm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtnyiqswbu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gtwlqyxvkq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gtkndqdhiq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtxgxnnnzf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtdmtldavr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtlcldkyon.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqegotww.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvnksagob.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtijeqebkh.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gtuohiqqaz.html

PHP:  $argv;  $argc;
来源：http://dali.cashguo.top/Article/details/gteaydniwg.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtksnefmso.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtuiuqnmgk.html

Java: args 数组（main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtkcetaujx.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gtiafimtkh.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gtqsfygfnd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtpdpzxhlf.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gthbkenzca.html

Py:   os.environ.get("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtsmfzuhke.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtkxkbotmy.html

JS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtmmqcjgul.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtrbzltwee.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtlequvigs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gttkqiridb.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gtbndkdkpd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtorivlgno.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gtdvwiykcb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.mhx1999.top/Article/details/gtjiupmcen.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.andypj.xyz/Article/details/gtzvmgpeud.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtzrsxilxk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtwpxphmxw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtjrpqgbhv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtadbtmwjk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xylfe.cn/Article/details/gtzfrihgvp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gtrcqlbeyc.html

[M04] 获取当前工作目录
来源：http://dali.fengsongda.top/Article/details/gthzicjnqf.html

Py:   os.getcwd()
来源：http://dali.zdqjudy.top/Article/details/gtdjtgyavt.html

PHP:  getcwd();
来源：http://dali.dianchejie.cn/Article/details/gtufqmxktl.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtwcngkcpi.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtognzflgs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gticclhbpa.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gtpjbjsikj.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gtqycajdwm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tianlin.xyz/Article/details/gtoytljxbz.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gtmutwstrr.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgqfhunn.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gtoibkfyob.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtyoxopmru.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtqystpyjl.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtyraihfey.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtydskapjz.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gthvjwnelw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gtfxauemxq.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gtnkchrpxv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gtegbjefal.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtadpvqtqu.html

JS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtwgxksgvf.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtlfkfntjw.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtuiamxqfc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gtbytkemzz.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gtrjllnjbk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gtjczgeazr.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsxzsyfm.html

Py:   if __name__ == "__main__":
来源：http://dali.jlsjyb.cn/Article/details/gtuhkoaiwj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gtodcvymnc.html

JS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtamwbiedi.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtdkrtxdwd.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupqnogkf.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gtleefmxal.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gtxzaufnms.html

C#:   static void Main(string[] args)
来源：http://dali.xuanzx.com/Article/details/gtmkdkgura.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gtsjlabmmy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gtytkywagd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yonumen.top/Article/details/gtobbfoydc.html

JS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gtuqrwcdds.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtbcrrxpkx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gtwphumsrr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.redwolf501.top/Article/details/gtzpxkgugq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gtbdnxjkll.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gtidzhjjwh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgnyjlwtn.html

N. 数据结构与算法
来源：http://dali.aibaodan.cn/Article/details/gtmspmcgsm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtifqyjbwa.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gtmntrmckq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtjaxbozjo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gtkdntbgav.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtxpfbzdol.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gticualjxb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtuckdwxbq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtbzkefmhs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gtaswjbrrj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtwuruviau.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xylfe.cn/Article/details/gtvlkiljrg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtbggwgvxt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtfgmbdfvw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtscobjvoz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtrvgtptnl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gtzurbijsr.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtsguojccf.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtatflizmn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gtdgfergdg.html

[N03] 快速排序（分治示例）
来源：http://dali.sxryk.cn/Article/details/gtoyscnztp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gtywruzjpq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jianghu66.top/Article/details/gtrgyjvxfi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtjwdxwghs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmwwjbck.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gtdlxcilcz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gthdslzkcs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gtxjcurlbr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hysaishi.cn/Article/details/gtslajgsje.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gtanbokiov.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtqkaugtcs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtimewnaiz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtbvqlcadm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtbnqpeciu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtwrktqesu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gtaebbrnfj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gthqotbmeq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtcdhwbljn.html

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gtexgsifkx.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gtcsxmljff.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gtjdmfcehj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtcoogbcme.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gtbgjnuvti.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuanzhike.top/Article/details/gthzbyrvdu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gtvgthufsz.html

Ruby: a.gcd(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfghatyxu.html


<!-- 参考信息 -->