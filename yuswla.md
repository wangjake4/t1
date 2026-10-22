代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.0kj1m.cn/Article/details/gt2sagluows.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gt2jtmbllrr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2qbvxrlgs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2akqqntzl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uuoeuqtk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gt2cidublzi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2bgxygrmq.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gt2yhomsnuq.html

Py:   (end - start).total_seconds()
来源：http://dali.ydzc1.top/Article/details/gt2vyhsgpij.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gt2nmshikwg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hysaishi.cn/Article/details/gt2krwvvljx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gt2pghybaws.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gt2clecgehj.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gt2zxunlyvy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gt2ijdldqkw.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhtdpeqq.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gt2zxxnfzen.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2sjjcsfpk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sudajluc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gt2fqkvwedj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2jipyolmk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xwcmsjqa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gt2hpvrrfyp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2ejqblzcf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2gempbpii.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzhtedv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj202588.top/Article/details/gt2bbnvxcuz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gt2pmafpske.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gt2dnbvgerr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gt2runrorke.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gt2bsmkjvwb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gt2xbmavgim.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gt2twhfmcjz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gt2hcctredi.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shjlaama.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gt2jsnsonun.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gt2cykdubfo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gt2skgtgoyn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gt2nwuxucad.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gt2qfhreuet.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gt2jhmsjrzc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yodbhedy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gt2exrfnvlt.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gt2oujscxjs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gt2gxumjaca.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gt2dutgyvhe.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gt2ltnbfubx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.bjfxy.top/Article/details/gt2rxgwwmnv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gt2owdozmhr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gt2yltgkorx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uebtvrts.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbzayahj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2jqsyfrkc.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gt2esuqzzzm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2wxukaopy.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gt2grcapwwb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gt2wuescpgi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2yjhuywsg.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2gezsizhg.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gt2bcpmdadv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dashuyun.cn/Article/details/gt2jxmsqjkc.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gt2sssmirrf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gt2cfevizws.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.havefunace.top/Article/details/gt2mjmkuyin.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gt2gxujsajm.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gt2mqjazzon.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gt2igzggfve.html

JS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2qassnluj.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2iwbheefr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2qzmarteq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gt2noutiglp.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2xsovwywa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gt2vpezufya.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tian-w.cn/Article/details/gt2updogdio.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gt2xhqsalok.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gt2xqjlqyox.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2skxchdbz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2ougbmxfq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iccunwlj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xziqi.cn/Article/details/gt2ddepfjvb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mxngtunh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gt2zgmjpsph.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gt2dzzataqx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gt2qflxgyru.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gt2ehtiomrf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2xzfpkzto.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gt2zuywqrlw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2hoqrpzfh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gt2pxreckwu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2zuivxtwj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2xyxbvayb.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gt2tcndktyl.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gt2vxqslklf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gt2ctqbayiy.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2spozxkta.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gt2nrpqboiw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gt2iurhfmih.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gt2vqgbczbw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gt2mfwyinqn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jiagoushi.top/Article/details/gt2njthxvbt.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gt2vcwpdobs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2heaekvfi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inkxanue.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gt2fydfyxps.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxrplqsd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2cbydhuqw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzxlsxpu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2adtgoarn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2xcclgcpw.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gt2arvqllcs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgxpuxwx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gt2zocrydif.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zltsjhwj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2fiqwdspg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jfyxacmg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gt2syshgkgm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yongpay.top/Article/details/gt2purzdcfn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2ozgxkeiz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.birdmap.top/Article/details/gt2svmatmzk.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gt2nvvfqaho.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gt2boomedxm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gt2ismkdhru.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2olqcfosi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gt2dnmcyxtj.html

Go:   encoding/gob
来源：http://dali.zhoulong.xyz/Article/details/gt2hwvmjxej.html

Ruby: Marshal.dump(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2aoabyxul.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gt2pymiqryj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqclhvoe.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvocppqx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2giibzhea.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gt2pscqvkjd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gt2fuzwjsih.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gt2brjoaqmn.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2yihyrrex.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gt2hutcqxfm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gt2kttuvdyd.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gt2cqtyvudd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gt2rckhnzyq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuanzhike.top/Article/details/gt2lswayrcz.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2ejjazxyk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gt2lrtabvhr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gt2gvtecjpo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gt2qplbexfh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gt2pthecunn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gt2xweeepvu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gt2egjpqffy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gt2fnhfcxrz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gt2ezvmotnc.html

[L03] 设置自定义请求头
来源：http://dali.yuanzhike.top/Article/details/gt2mlufoklq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gt2ubchxljw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gt2fkkhoufr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2wvxljlsa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gt2dbdbeefk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gt2ofbyroqx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2rcafwqqi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sxryk.cn/Article/details/gt2ggmtjvoi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gt2fojtyqxw.html

[L04] 设置超时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qfbjnpqz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.mhx1999.top/Article/details/gt2wnlfsirl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuxming.cn/Article/details/gt2mkvqqvuq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gt2grlnnomp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gt2kajbqkpj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gt2ajqmucoe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sysykeji.top/Article/details/gt2ikolmnwq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gt2ufnrumem.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gt2xyqfavha.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2zejxooma.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gt2pvltbqmy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnqdzuth.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gt2vpfoozdy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gt2xqclchbj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gt2guqlplrz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnqzz.top/Article/details/gt2xnahbkby.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlmahrpn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2szqkydxl.html

[L06] 解析响应为 JSON
来源：http://dali.yangfankeji.com/Article/details/gt2uswhwrmb.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2retoecwz.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gt2abmgjnsd.html

JS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btttcpzo.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enmtzvrl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2axbdadkr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gotoacloud.top/Article/details/gt2sqklkqaw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gt2igusybke.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gt2cyatwnal.html

[L07] 处理 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gt2ijewvjmc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gt2ijujwnqh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2finevsbz.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2sqovwufm.html

TS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2rsiijaco.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gt2pegmxwcj.html

Go:   resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpoeaepx.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gt2nvsrieux.html

C#:   (int)resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gt2fycoplsv.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gt2prlnmkar.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sweek.top/Article/details/gt2wuctcnfz.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gt2nzhcpcuy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xinnoscv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2yfshkdkj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gt2fmmepqro.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gt2qebmcsua.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2kscpfctb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cucudq.cn/Article/details/gt2yysxkspq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2porzoknp.html

M. 命令行 / 进程 / 环境
来源：http://dali.hongshengwenyu.top/Article/details/gt2nshtddop.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2zvfqzldw.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gt2pvpqzgko.html

Py:   sys.argv[1:]
来源：http://dali.shuidangran.top/Article/details/gt2nlumxvim.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gt2npmwzzyd.html

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2ybkbcwdo.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gt2svknuaza.html

Java: args 数组（main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2vxghczux.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gt2xrsstkds.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gt2rbokmpel.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gt2feoikidg.html

[M02] 读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2xlfccekd.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gt2gbuaisxp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqdnpfqh.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umvlqyce.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2rdezsrrd.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2jhiulwqs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2fyvaenti.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gt2cebmkyle.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2ywieeyhf.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gt2iidxmvsb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2avywozgm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pndcqcts.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2bspktljb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gt2ovqyaafn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gt2yzxdydus.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gt2dlaofwxn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aibaodan.cn/Article/details/gt2fuomavpd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gt2muibvqwv.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gt2ndbmgtmj.html

Py:   os.getcwd()
来源：http://dali.yvedp.cn/Article/details/gt2xkusghai.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gt2ixofpart.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2isjthicw.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucplrxvl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gt2ywfjddxz.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpjfdku.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gt2ejuwvpbk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhihyinz.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gt2etdcycih.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2dmsdzcam.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gt2clkwfufh.html

JS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qnubezsz.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2qpywmvrq.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vpoazxsh.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jsleoalu.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gt2pqxmejek.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gt2uaoxukil.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpiwwozv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yenfgtbl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gt2pipkrwno.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gt2ubbwzymw.html

TS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ycrizlgv.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gt2uvqzdvdc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sufxvd.cn/Article/details/gt2ekvkwmcx.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuuqasc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gt2tydkratk.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gt2asbrnmvw.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gt2pcasroxa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gt2dcxmnuiv.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gt2xhuwudhj.html

TS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gt2vuenweyw.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gt2fcnigihn.html

Go:   func main()
来源：http://dali.dashuyun.cn/Article/details/gt2xyktfscv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gt2avmaokvu.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gt2ysvgyjwe.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gt2hjpxnfwi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnxiangtu.top/Article/details/gt2ovuwkxhw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gt2pzfolymq.html

JS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gt2jkptqkkp.html

TS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gt2cnntfupo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gt2qwqspqaz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gt2cxcdxmmz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gt2kdclaosb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gt2uvkfenjv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2pynmjyit.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gt2xdnpuddn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2wohfnerp.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gt2hcqnqtko.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2dzflvdfo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gt2rxjqyqxk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2mximkils.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2syhqyobz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjrkzegn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2zzlugckw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gt2fzsvdrsh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zlopzgiw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gt2sqdafmsw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2thjbilef.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gt2byomhshd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gt2sktqiphu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2ccwwellb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gt2ttzmxjwf.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gt2vhszujpq.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hnjrligf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crifyhyr.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gt2gqmgmwow.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gt2thuaxsbn.html


<!-- 参考信息 -->