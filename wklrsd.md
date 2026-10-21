代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gtsnnnavrb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtyvvfuhau.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gtvyctezjf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtvkhukzjk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.andypj.xyz/Article/details/gtgnuftiww.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtxwxdukow.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gtyhzwitdx.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gtgrdayaul.html

Py:   (end - start).total_seconds()
来源：http://dali.cashguo.top/Article/details/gtxfdwtobl.html

PHP:  $end->diff($start)->days;
来源：http://dali.bjfxy.top/Article/details/gtbsrubfsg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gtrwfowsmr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gtqdmcdpqz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gtkrylcyqi.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gtgoyrrsjd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gtkhgusrle.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gtpibsjdqv.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gtmttvchmo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtmbjzzdjz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ybcxt.top/Article/details/gtisbymrvs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gttbvlxxth.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtxgjiddpb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gturfjhwlo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuanzx.com/Article/details/gthhkwurao.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtcgpyhwww.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtisqhodoe.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gtpfdgysfo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gteluvqnne.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gtnvfervdf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.snrcjt.cn/Article/details/gtsnslifhw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtbovpalvr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.snrcjt.cn/Article/details/gtjkrbqnpp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gtwkqgriqg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gtbgomqptr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gtiiznnalq.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gtescvmpfp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtcrpjzppj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.iojbl.cn/Article/details/gtgrtmyava.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gteuhavlpy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtxgogcken.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gtafkjukpo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gtcdwqdxct.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtfotljqyv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gticnmhpsb.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gtxrmpvnwv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.bjfxy.top/Article/details/gtyhbwqgzx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ehwqpu.com/Article/details/gttbfjhezb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gtdzbdqqwq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtzfypeamx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gtzlewmqhi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gtmjxiwifc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gttwgfqsji.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.mhx1999.top/Article/details/gtxeembgbi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdberloru.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gtkeuautlm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthdcoqdge.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtljglndgz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gttloelyke.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtfbwkivfg.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtchradsej.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtoouhhakr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yangfankeji.com/Article/details/gtvwuxbsds.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtcuydmmxz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gtngqyoduf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtliwxgwsy.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbkpbvvj.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gtmjtxelfl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258888.top/Article/details/gtabxxcggi.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtdelybeav.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtfdgcbblg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtxfxunzei.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtedoqcexm.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtsotxnpjj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzointfuq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.c1oappe.top/Article/details/gtzfqzvjnm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtiejkmalr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtwsqancwi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtlmmrfdmz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtmpebsine.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.iojbl.cn/Article/details/gtrecrnobz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gtqdejghjm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtzjfubnbp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gtjxbxcwld.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gtqiboigyv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzfgiztj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gtgvuqivrb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtvkfvplls.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gttwpmvxcm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gtqwwuowhn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gtyiwzvbld.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtrmjsqxes.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtsanlqild.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gtoikstncv.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gtiajjlwzy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zdqjudy.top/Article/details/gtmzczehtt.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhrmkqwl.html

TS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gthkxtieec.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gtttjucekh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gthpycgcgo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gtwuofyouj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gtubulefpg.html

[K06] 解析 URL 查询串
来源：http://dali.daxiang520.top/Article/details/gtehwmhpxt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gthqyucimw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gttzrgbaov.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtsunvayif.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnicjucjj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlckrvejp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtvxkgeytc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtgnvaxlal.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtiqqgifmx.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gtzpgnrjbn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtnkvridrf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gtkfcyfyxv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtqapixyvy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtotyerguw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtgptyzelk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gtbxrhegwa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gtceqjalne.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtlhgnnlgx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gtosqbxbwu.html

Py:   pickle.dumps(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnornvxyt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gtzkfavfcx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtjmckwcva.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtmpgbmijt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gtsfggiyqm.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gterbcfmuj.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtyrgfjb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtuylkxkgf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtdifsvjvx.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gtayhmrbtm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtofujahzd.html

[L01] 发送 GET 请求
来源：http://dali.zhixingplan.top/Article/details/gtbydeqado.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gtlzohulew.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gtbdqynoap.html

JS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtgdanpcys.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gttckgadna.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtbufkijif.html

Go:   resp, err := http.Get(url)
来源：http://dali.ehwqpu.com/Article/details/gttdzerirx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gtuiqiiwba.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gtshailxht.html

[L02] 发送 POST JSON
来源：http://dali.fzhhl.top/Article/details/gttgwzmzvp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtvxpzfjvr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gtkpwebxxy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtqumtttwq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gtfkqbuhwi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gtmgcmlydp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ehwqpu.com/Article/details/gtamwyxwro.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtkcpzvgmt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dianchejie.cn/Article/details/gtmqshybmg.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gtbymvsail.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gtpraaudjy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gtcjqqaqba.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtkmxdcndn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtymbcbayc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gtdjtfvskj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtpbxrlqvh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gtdvhuhhzf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtakdcmbqj.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gtbicggxsp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gtkdpltwwa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gtejrlxeri.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gteafeufwx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtwdbowzat.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gtporfekeg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gtvngdqthz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtexrfxbwx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.haohaochexian.top/Article/details/gtibyvmkgn.html

[L05] 上传文件（multipart）
来源：http://dali.iojbl.cn/Article/details/gtdsspghmp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yonumen.top/Article/details/gtzokcnraa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhengqikj.top/Article/details/gtythpdvvi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gtpizclwed.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtnrmixvjf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gtihvbjtgg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gtzeptqsws.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfwytjgn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtqcdyduna.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtylrfavkz.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gthqpgghdk.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtztkqtmos.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gttujszscu.html

TS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtiwryvznc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtaivqmqma.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ybcxt.top/Article/details/gtrzzykgvm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigufen.top/Article/details/gtzmyvlpja.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gthlbvfibm.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtqoolrpja.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gtmykaayok.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtyqukelwy.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gteytsixkw.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtjhhxdxqo.html

Java: resp.statusCode()
来源：http://dali.gzhubu.top/Article/details/gtthmhwvqj.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuczngsf.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gtiegwkubq.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtinlqgyxe.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gtshcfhluz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.mhx1999.top/Article/details/gthfqcxyli.html

PHP:  curl_multi_init() 系列
来源：http://dali.kuanghao11.cn/Article/details/gtuufoxzbj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtciqbxknm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gttilgyqcz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gtlxlpamrz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daria6918.cn/Article/details/gterjyxsja.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gtwjejuvec.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxuanxn.top/Article/details/gttsjozagj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtdvxyamti.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gtuuihlqvn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gteglullqd.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtsvupokcx.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gtdopxtksu.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gtoxsqrnhf.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtnftehhhk.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtscolevkx.html

Java: args 数组（main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtvfpyjndo.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gtpbqsvuca.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gtoplmgcdw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtfommbzem.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtombpnvey.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gtbkxoalyc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gttiiggqnw.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtiqmvdsnb.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtnlukauug.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gtxjyngqhh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtdriksurr.html

Ruby: ENV["HOME"]
来源：http://dali.fzhhl.top/Article/details/gtqlunbrpw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtzmvuyfvl.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtxwhbplss.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hfpthk.cn/Article/details/gtxhzisbkh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gtsfgkodza.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtmffsqjmb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtpotwxqad.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtndshspxz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gtllsrzgot.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtklpsfjpo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gtytbmdatp.html

[M04] 获取当前工作目录
来源：http://dali.0kj1m.cn/Article/details/gtnldfsrad.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtvxccncam.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gthymtyjgq.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtafaevkiw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gthwjuisij.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gtwhhgskaz.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gtiniqpcwh.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gtlbgwwxwp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gtofdrlcsp.html

[M05] 设置退出码
来源：http://dali.tian-w.cn/Article/details/gtolwtfqst.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtfybxcbiv.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gtloqsrgun.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtqkgvxviu.html

TS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtvlbgauix.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtukesrzih.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtumlnfpsc.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gtexqegynv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yanxiufei.cn/Article/details/gttvtjstwi.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gtabwjqrse.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gtprgjkukt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gtfagoygxx.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtvoykipsb.html

TS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtdcsxoxwo.html

Java: System.err.println("err")
来源：http://dali.yonumen.top/Article/details/gtblzmvqmw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gtgspzxksu.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtrrixnqix.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsytvvzsz.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gtesdeqvyr.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gtogrwkedp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daxiang520.top/Article/details/gtbnabgawp.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtltjtmylc.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gttkymaxcr.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdixzunzb.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gtwofcahcb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gtjwekkuaq.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gtxedtpikm.html

[M08] 获取系统与运行时信息
来源：http://dali.shuidangran.top/Article/details/gtcxtnljcw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gtksmvuwln.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gteuyigzif.html

JS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtifovbkqu.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gttewvwxnd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gtfmnuumqa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tanke756.top/Article/details/gtoeifbwcp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gtfogmkyei.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gtygucztid.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjxtzkwaf.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gtqfppxbfc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtesrgvxnf.html

[N01] 二分查找（有序数组）
来源：http://dali.iojbl.cn/Article/details/gtiictozrf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtqclsukzb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtllyhetlj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtfyodnfjb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtbsebqqaz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtbktedafl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtierlbqjv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gtwtrxbmsj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtybuyyrmj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gttdxkrmvy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtburlatjd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jiagoushi.top/Article/details/gtojcvqwju.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtzoexicsu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtqxndjuvp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gtkztjcdqr.html

Go:   slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtyzoklcun.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtqxuuuonx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.svipenyu.cn/Article/details/gtodhtrmdp.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gtynhfffwd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gtznglzeyb.html


<!-- 参考信息 -->