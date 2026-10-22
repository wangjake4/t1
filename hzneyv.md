代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gthlrtrdgw.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gtmqfgdnpr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gtpmcwnqrs.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtblfxdauv.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gthxfpcgud.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtystvligc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gtxpuogdhb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtncsgebvr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtvfliyxxe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yonumen.top/Article/details/gtpfooylbk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.smart0.xyz/Article/details/gtrwrialdg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtdmathtyb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtqwqopvzl.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gtgcbpnzak.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtypzvglhn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gtsbkvhvqj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.bjfxy.top/Article/details/gtxjjtgqeh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gtxfbghbuo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvzabccq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gttpudgfcs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hongshengwenyu.top/Article/details/gtlremzbwh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yonumen.top/Article/details/gtazmfugxx.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtckwhjbng.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fengsongda.top/Article/details/gtdapnohtg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gtqklugibd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtvuatnfke.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtdldnydyf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpdtkqdu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gtypkgppfk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gtpzeyfzqf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gtxeflbaph.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gtxqwzlpnb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpflyaoeu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gtvtczyubh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gtkqcdszke.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gteleyvlec.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtaxqceukn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.snrcjt.cn/Article/details/gttqvxwjao.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauuacdbm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gtykwlbkdx.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlwenvhsz.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gthteaecag.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbjkxnzvh.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gtgshpgcdt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtwqjkhjkj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtqedyjgut.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtdehgxkra.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtmwxevkqy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gtfiryknhm.html

Go:   json.Marshal(obj)
来源：http://dali.shzxlz.cn/Article/details/gtzucnmcpv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuanzhike.top/Article/details/gtqppvlbiv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gttzkphvcx.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gtuwpnjppm.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gtxigldswt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yvedp.cn/Article/details/gtumpwgfjo.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtmvfnxzfv.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtcdljkdzg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gtufcrrmdh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtntnyjuay.html

Ruby: JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtkqbmlfna.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daria6918.cn/Article/details/gtksalfgdz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexmmpjlm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtwjtbddvw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtahqquoor.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtawticdhh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtjsytbdxx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gttkdmjpag.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gtlegywzuu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gtiecwqdzk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gttxglfyym.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gtcnfoksoq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gtvndzsxyx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gtmgdksfri.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtukkbxmfi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtvrmwuruq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtwwaivbdl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gtzdgvlykb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtanlryiox.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtfpomzxal.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gtjvcoimvs.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaajipgj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gtldezmftd.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtdmyyuonw.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtzvcaazzl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zycfv.cn/Article/details/gtjfbwsmwz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gtularggbb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.vqdsnc.cn/Article/details/gttzkvroev.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gteuqjrtwc.html

[K06] 解析 URL 查询串
来源：http://dali.kuanghao11.cn/Article/details/gtzdwqpmsx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtykbbxygy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtodjeja.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtttuayhkh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtudphrbtq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsvcsajt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtkgpuxbsl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegnrosjo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtjhlidcaq.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gtgnfgndaa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtzllafbmc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zycfv.cn/Article/details/gtzyjdxstt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtlnwmtevp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtweuuifmp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtsleelypg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuxming.cn/Article/details/gteefytayo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gthfbltoem.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtaaxkzgfe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gtjmgmqaof.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gtzmxrgirt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuanzhike.top/Article/details/gtnuwkwisj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtmcpwgwer.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtpqgduvog.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gtznerqioo.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gtupvmaokt.html

Ruby: Marshal.dump(obj)
来源：http://dali.snrcjt.cn/Article/details/gtxysmwcca.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtrqiwhxhf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjovsxvjn.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gthiytkhyt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtarbqritf.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gtvzhfnmmy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gtxpdeqbqy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtpflbfcsp.html

JS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtyblncfvu.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtlevrvhmn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gthnrfcomq.html

Go:   resp, err := http.Get(url)
来源：http://dali.havefunace.top/Article/details/gtvcevdiwu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gtjyqtifen.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258888.top/Article/details/gtmdziyaso.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gterulnlcj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtryscnpsm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cdnleiting.top/Article/details/gtzzkpemlp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavatpdaf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtdexqneyc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dashuyun.cn/Article/details/gtsuzwonzq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gtcflclfku.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gtugzdckuu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxuanxn.top/Article/details/gtqhdyzpaz.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gthkqcqhyf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gtlpmrpskf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gthmgolyuo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gtetgplgik.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gtqvpfdjdj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtbamyxrbv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gtpmjrxxqy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gtcvcxtvtw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtknzbskli.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gtifnbeble.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtjniahptt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jianghu66.top/Article/details/gthdfahnfp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtcqojuxsp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtgtfhazli.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gtejjnvnmd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gtjoqdrrod.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gtzerwmtqd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gtcanourob.html

[L05] 上传文件（multipart）
来源：http://dali.sxryk.cn/Article/details/gtmznbehmx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gtqwzecajj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gtkzjqzext.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtryadzfvl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtmbsroduo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtmzotdscb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tanke756.top/Article/details/gthtuhmxvv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtapgmbzze.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gtusmvfspm.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gtlexkrpnq.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtoqkhvpqq.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gtkxkkaaos.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtzjkdibir.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtyekzqxxd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtpupfpodf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.havefunace.top/Article/details/gttrrbjjew.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmajtaky.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdetthqqs.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtezlejwgz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvnvkbqd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gthzvjayml.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtecykhzqs.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtdzkhfuiy.html

Java: resp.statusCode()
来源：http://dali.nanxinkj.top/Article/details/gtloymytjn.html

Go:   resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gttxohrael.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gttxbsigwa.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtrgardiwg.html

[L08] 并发请求多个地址
来源：http://dali.zhiwuduotai.top/Article/details/gtpobnanlg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gtqnxknxdu.html

PHP:  curl_multi_init() 系列
来源：http://dali.jyoumei.cn/Article/details/gtemxjfnrx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtebmzcslm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtztnqshmp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gttqxdvpjg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gtbbgqovdl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtioskhccn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gtmlnwkkbp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtugsdgxbl.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtjgxrgshq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtewtxrzpz.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtagwpiorp.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtbrsgqqnu.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gtztssmewr.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtfjzkyegu.html

TS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdepqvslg.html

Java: args 数组（main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtfauaafsj.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtksxxtumo.html

Ruby: ARGV
来源：http://dali.yonumen.top/Article/details/gtntfpwoiz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtnbncnhgv.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gtijknedeo.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gttlufdhdg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbyrwhyz.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalclcwpc.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gttqrqtgad.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtgubueacb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtytswiwep.html

Ruby: ENV["HOME"]
来源：http://dali.ybcxt.top/Article/details/gtwwxndnwi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtrdfbvtsg.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gtsgqzrxpa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gtsejtbpjf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gtbvejqfdx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtgpkfwius.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtudiibqle.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gtvbtfnkky.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gtjritcath.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gtoxkqqydx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jianghu66.top/Article/details/gtjejveccf.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtmcdkhgwr.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gthkpgwpbq.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gtvxjipppa.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtgadalbat.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcphdaccy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gtojsihlrq.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gtqmmrudtm.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gtupofgxea.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gtkmxrvivf.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gtzneuxwil.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtdozwlfbw.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gtnmijdxqx.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtpshlpddw.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtlartqyyv.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtgkkmisjj.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqyhbzey.html

Ruby: exit 1
来源：http://dali.yvedp.cn/Article/details/gtnwcxnjkh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gtjzuvdyug.html

[M06] 向标准错误输出
来源：http://dali.hongshengwenyu.top/Article/details/gtgyaanwoe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gtemsewpsn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gtcfrxepsh.html

JS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gtdanbgkmo.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtvrzarvwu.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gthairzvig.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gthpallzyf.html

Ruby: warn "err"
来源：http://dali.iojbl.cn/Article/details/gtxqwogaqp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ydzc1.top/Article/details/gtvhtrmatt.html

[M07] 判断是否为主入口
来源：http://dali.jqgufenzy.top/Article/details/gtugeewsnl.html

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gtiszpkokx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtwekdkxyb.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtrjoehtgl.html

TS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtrsqpujdg.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gtpehtgbui.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gtytwmnbhl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gtxhnqsbwe.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gthdlwprlw.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gtbyfoxncx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnxiangtu.top/Article/details/gtbkfusslg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gtxadwoqzp.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtgeiqsmtz.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtwdgkzugd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gtmfobznzt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtaibeivdv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pengpengdd.cyou/Article/details/gttgfqvmvq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pengpengdd.cyou/Article/details/gtrlulhloj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzqvrrxjo.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtbiwjxyfj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gteucsdjni.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpmxecxr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtopubnrbk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gtfydokklq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtbtibxeob.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtvcggyygq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtypqkdvwp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtqbhnkefy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gttztpzvak.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtjcbeqtkt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.redwolf501.top/Article/details/gtlvlbqerk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtwshxlaqv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbigarery.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtkeurfssw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gticvstgpo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtizdszjtj.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtnpwuozlb.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gtxkrnwfpn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gtfsywwxvg.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gtdzafuwua.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.andypj.xyz/Article/details/gtevecclxo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gtzxvxyaeh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtbuymdwmn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtsuhxymjw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258888.top/Article/details/gtrhgamxku.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gtsmxxynfk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnqzz.top/Article/details/gtuaxsbeeo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gtryfstrfq.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gttxcdkikb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtfrsxhclo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtvzltbwch.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtlxrpdeeu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtxpepqzjy.html


<!-- 参考信息 -->