代发 wailian999

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gtcuqvnzhj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcgfqepn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtzknpgzas.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtycdytqge.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtbohfcklz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gtppqtctkg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtohnadzcc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtqirdndmg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtzspgtzlb.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gtebphxies.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gzhubu.top/Article/details/gtuvqlbjan.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhhfhavd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gttxcbstvd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gtxcrdvugo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gtncwcswnx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sxryk.cn/Article/details/gtnxcznpvz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gtqjohqrpy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gtzwoeqkov.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gtacyjnrxa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhengqikj.top/Article/details/gtowgzwxan.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gtvnlxjodo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtdnmmfzpf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtgutdaxng.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gtssensosl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gtzwcxqxnv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtvmvbhocl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gtrlblkjmz.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gtthbeucvh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gtttcniizn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtrmetwhif.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gtodiycbru.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gtbxolidhz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gtspwavykf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gtcusbndyp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkqxzajy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gtuiscsbsz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtbxucmmnc.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtcktakght.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtbfmsejut.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gtiehxgmsi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtvijnxehv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtrpvtcvsp.html

JS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtrcobhbij.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtiytxsyxc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gtnlpzfulk.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtyqintcta.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tian-w.cn/Article/details/gtraeihdto.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gtqyjmiapy.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gturfuqucn.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gtwlezkajn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjqfvkao.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gthagfdbti.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtfccbfchr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtbxvwdomc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtpzcqsifv.html

Ruby: JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtkmbovekp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gtekfsoowr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gtsrimifmw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtktaypapj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtthcupblx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtdnfkxdmt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnwpzojf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gtsaxwcwfd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gtkqrbvshp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gtwmzxielj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gtxdaqzzcw.html

[K04] 读取 JSON 文件
来源：http://dali.316326.xyz/Article/details/gtffyzkzhi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxuanxn.top/Article/details/gtjmpxumvy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gtpypweqae.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtbxppqdgj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtzlwksdwc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtmszakuwl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtottyvgih.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtapofczxa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtcvwxbhsw.html

[K05] 深拷贝对象
来源：http://dali.hfpthk.cn/Article/details/gttcwbhrwa.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtsvjcutyp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gtosbueamp.html

JS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtoeukiohi.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtacqyhbxb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cqqwz.cn/Article/details/gtpdazppas.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gtmepcqpbx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtdusmsybb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gtnagcbwov.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gtyzsnmdhy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtbbkfslna.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gthwziqroo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtqbmtxpph.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gtiyoxhxyd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.kuanghao11.cn/Article/details/gtiqkrtibx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gthswemstm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtpbzfpjpa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtjxhcipbf.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gtyrxrnski.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtekmyebso.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gtzfuxnmeq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbadninwj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gttvmkvqoc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtjcwywvhq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtniismntv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gtjmuinyio.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gttdubhvon.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenlongwang.top/Article/details/gtscgftinl.html

Py:   pickle.dumps(obj)
来源：http://dali.daxiang520.top/Article/details/gtpbcjkday.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gtcijuutia.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtbkjuncua.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtyuqxdoul.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gtcjhfbdsx.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gtazlwrkmt.html

Ruby: Marshal.dump(obj)
来源：http://dali.ivvv.top/Article/details/gtweinhnpo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtvljksslp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtznsfkhoo.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gtnsdnyyjj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtuvikzhjl.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gtvnfzwchb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlcfsucs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gtygelcbnp.html

JS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtixgzvafo.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtganlbfsg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.svipenyu.cn/Article/details/gtcnopukfn.html

Go:   resp, err := http.Get(url)
来源：http://dali.svipenyu.cn/Article/details/gtwkyswrhw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gtivjdjszh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gtjmjhmqli.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtuejhtcqi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtcqikefyi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jianghu66.top/Article/details/gtrzsyknyq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtvnztgpzg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtpmzpokon.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhoulong.xyz/Article/details/gttgoofnnj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gtncpqiptg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gtxyzqngsv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxvuqppj.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gtrthtnpun.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cucudq.cn/Article/details/gtwkrsleis.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tian-w.cn/Article/details/gtdnapiuep.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtmcwfwusv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlatcdtdk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gtieuhbjon.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtxqocdbri.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hfpthk.cn/Article/details/gtqzuihuvb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgwsocpm.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gtqxwtosxf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.andypj.xyz/Article/details/gtxkahdctv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.snrcjt.cn/Article/details/gtbslgdwqk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtimcmdwis.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtldknzioh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.316326.xyz/Article/details/gtknbiurrs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxuanxn.top/Article/details/gtxgcgpmwd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gtjmcusnhs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.haohaochexian.top/Article/details/gtkzgqoloh.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gtwjwbvggf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gtzfocflex.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.0kj1m.cn/Article/details/gtoimbrdha.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtggsnbugq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gthkkxhvva.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xziqi.cn/Article/details/gtmdznhuck.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gtnpsqzfrg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gteqgwtovb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtujoaddxu.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gtbqmasaxf.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gtouicrehn.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuuacotkc.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtceifuoxp.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtmisyhxvp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtricncwze.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gtohtmwgco.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtfndszlre.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yvedp.cn/Article/details/gtznwroudw.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtdvhcpkmp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxpbellf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gtjwpwxkmv.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtggxiwgbg.html

TS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtrqtvsyjs.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtnoukadbg.html

Go:   resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtdrohrqqn.html

Ruby: resp.code.to_i
来源：http://dali.jyoumei.cn/Article/details/gtredjweuh.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtmgjlbgto.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gtputyeqwb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gtfavgnvhv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gtxzpaquyf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtebeigily.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtrgksiovj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gtagzlcels.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tanke756.top/Article/details/gtgiblirbo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tian-w.cn/Article/details/gtavryufny.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gtknqhumpf.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtztroflln.html

M. 命令行 / 进程 / 环境
来源：http://dali.tianlin.xyz/Article/details/gtrdpdrswu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtubgzouxw.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtblzgksyx.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gttzivxkjq.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gtgllyokjf.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtkcztjhzp.html

TS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtesfaptec.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gttagrhldk.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtchftspha.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gttvjiliac.html

C#:   args 数组（Main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtdotfmdlq.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtzgohhjih.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gtqpljmeuo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtgvnlpunw.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtuiicchvt.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtrdclnbii.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtpwvpulxo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtjqtxqbcy.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtaollutiq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gthsbfnwgm.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gtxblunlzk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gtevvnvhqu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpgwkerb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtyghnmojg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtawvvlsvw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtmiwuimud.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.vqdsnc.cn/Article/details/gtkupdnirv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtsxnpjepv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gtlodfiaoh.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gtfbndcdds.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gtiorzywir.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gtykvucjgy.html

JS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtyzmigeol.html

TS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtpwbiiejs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gtcnzpkqyy.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gtqwgfwolv.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gtmfngmlsi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvxyoqlo.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrphepihb.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtdnwbxrln.html

PHP:  exit(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtodpxmqia.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtejtdxtrc.html

TS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcldqkjqs.html

Java: System.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtzbjklwzu.html

Go:   os.Exit(1)
来源：http://dali.zycfv.cn/Article/details/gtbjtmechl.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gtuwnctixe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtebxwmtst.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gttbrpqzoq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtjdkaiskj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gthlswagcq.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuubniqw.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtgucqoslo.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gtnjzakcle.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gtrunkrhgr.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gttnuhvxnv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.iojbl.cn/Article/details/gtzeddupdw.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtcbrqrpsx.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigufen.top/Article/details/gthircfhzk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gtqfvtuegx.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gthdsnbpap.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gteowrzscw.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gtibxbzyfh.html

Go:   func main()
来源：http://dali.daria6918.cn/Article/details/gtonevifqx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gtnufmwtzc.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gtdevoyxrg.html

[M08] 获取系统与运行时信息
来源：http://dali.hfpthk.cn/Article/details/gtfqgzfxau.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gtxbjwhjlp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj202588.top/Article/details/gtdqlymfzj.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtqcvziigv.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtutcwkpxo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gtgpmbvxqp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gtwuawdfvr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtutqttepm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gtkhriffbx.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtzuccqknt.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gtyktakfmg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgaxewndn.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtqmasfsyf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gttcdoornc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gteomvrtfl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtmeljfxlc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtcnmntrsn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtkbzgxiar.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkicrmhsc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gtkkhsjktf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtwvxqvxpg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gtmuwzfqvj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gtvwqwiwis.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gzhubu.top/Article/details/gtberznfot.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtckribdwk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtlaehxlko.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtknzfdnxj.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gtlqtxdxrz.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtfchxhaxf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenlongwang.top/Article/details/gtpgutovfh.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gtapjobztv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.316326.xyz/Article/details/gtgjtgogph.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtjjyskaab.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtrzzwmtvz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtgxnxswko.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gthutqngtu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.meibo888.top/Article/details/gtldlkaklb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gtuwvjlvao.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gtpjxiivsd.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gtjpuqfqyz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsptwsbzi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gtqviytmve.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtiuzuetui.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtkgdiewge.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guannengcc.top/Article/details/gtpumyglol.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgufenzy.top/Article/details/gtfjwhcrci.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gttipybccf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtfohlaxvl.html


<!-- 参考信息 -->