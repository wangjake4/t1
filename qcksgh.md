代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gt2hsbqhyly.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgjejrif.html

[J05] 时间加减（加 7 天）
来源：http://dali.ybcxt.top/Article/details/gt2dwemxqvo.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gt2rejcxkgp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gt2gahkqfdw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gt2vsqdvimk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gt2laywnnaf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2pxuwbivc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gt2rngiaayj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gt2adkwvvtx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gt2eitqdtqz.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gt2xznwqcyt.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gt2kaklnzgi.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtzluafw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gt2strgpfff.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sufxvd.cn/Article/details/gt2olznxyfo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gt2ahkkknkh.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gt2nmldicvx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gt2belkjbzj.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gt2dpdeuvvs.html

[J07] 比较两个日期
来源：http://dali.cashguo.top/Article/details/gt2asgasoec.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2qsvvdimh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jyoumei.cn/Article/details/gt2gdbnrbhq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2ngquzvul.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gt2zxdchcke.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhengqikj.top/Article/details/gt2rydycpon.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guowangkeji.top/Article/details/gt2jeequrlg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2hxfxfkcb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2uahfkvba.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gt2fivdfcil.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gt2rcrvgzbc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gt2pkmayhmc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gt2gktaxroh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gt2hkxrlfnt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gt2erfiugfx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gt2ruyssjuu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gt2bjqxpxqt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gt2eiwcxjpt.html

[J09] 时区处理
来源：http://dali.chenlongwang.top/Article/details/gt2jcincgvq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gt2lewlluci.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gt2rjpasxev.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gt2mosvjczl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gt2qfbcxaye.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gt2jnyojpav.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kstueser.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gt2fvhyfwjs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gt2ppbwhqbb.html

[J10] 取今天 / 本月第一天
来源：http://dali.guowangkeji.top/Article/details/gt2zfpbusjb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gt2xjdomjfm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuanzx.com/Article/details/gt2drqmbjau.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gt2ormsziyc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj202588.top/Article/details/gt2yydynlnu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gt2szthrkej.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gt2eenmsfoi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gt2grspexvr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gt2ztzkyrca.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2jlnqgluh.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gt2wyezjsof.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjebklxy.html

[K01] 对象转 JSON 字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2hgkjbyoj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gt2pgaazlre.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gt2lxoapcwl.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2gqinrvxr.html

TS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gt2dwyvrtdu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gt2njqtiijq.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2dchrsdjr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2eguwubal.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.redwolf501.top/Article/details/gt2wwfojbza.html

[K02] JSON 字符串转对象
来源：http://dali.cqqwz.cn/Article/details/gt2mznkkubm.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbbincs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gt2pnuoziec.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxtfdfje.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2ajjaeagu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wvyrrtes.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2ducemcsz.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2rsyknrig.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gt2qcvzfgkc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hywenlv.cn/Article/details/gt2phwjhizr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkhckwjb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gt2jzkuvitx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2xfffvdib.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hvdskysl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2wxxblpun.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xziqi.cn/Article/details/gt2zmizluze.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2kvdfrsfc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gt2tnkrlmaa.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gt2mfmnrblz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gt2yvozrkvt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gt2xmtgidli.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2bzedmnrc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2zaqrokgp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fedmaosj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gt2fmtnflps.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2cacvlxfv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvzoitof.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gt2pgvjtlkw.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gt2neelymov.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gt2jfecbgxn.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2fmfilsts.html

TS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gt2mggxzspy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gt2mdotmyrz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gt2nqadppdq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jianghu66.top/Article/details/gt2pofpcbzg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gt2nixwxunv.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gt2amleemhi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gt2lfnpeaww.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gt2gnjbplhy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2qcoajxms.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gt2gntxyrif.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gt2cvqqdgct.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2uwqdaegm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gt2fkphrzkm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2izaauqxa.html

[K07] 进制转换
来源：http://dali.cashguo.top/Article/details/gt2llsfynbo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2vulllsft.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gt2clkqfvdi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2knjowkxt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2zhkcvral.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2gsexbbjc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gt2zkpwygyg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwricmin.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2gxhzbjfz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnxiangtu.top/Article/details/gt2uikurneh.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2yuukqzjx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gt2skmnfwxc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gt2xnteviwl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oiauzncm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gt2ssmmdhib.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epwaadec.html

Ruby: Marshal.dump(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdqqlmso.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gt2cedvdhjq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xhlvluog.html

L. 网络请求
来源：http://dali.gaohongyu789.top/Article/details/gt2eqsovzua.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2cispoipm.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gt2soujcbvj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shuidangran.top/Article/details/gt2oevqsbze.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aibaodan.cn/Article/details/gt2kpwcdohv.html

JS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2cfuyeedw.html

TS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gt2ktqegzgc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gt2cmyptpse.html

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gt2uhjmzmmh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gt2pxvglbdr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tian-w.cn/Article/details/gt2gzijfepw.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2vnvkdtnl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jrhvdyfq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.redwolf501.top/Article/details/gt2vykfktgw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gt2eevyflin.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gt2uulsouon.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gt2ydcwaivg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgufenzy.top/Article/details/gt2xqtbqrzg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gt2mgxcazpw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tianlin.xyz/Article/details/gt2ovwvmxpw.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gt2rcxqbjaw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gt2ifwhxico.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hfpthk.cn/Article/details/gt2vcbnsllh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gt2wzgqpxfl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2yfwklgsb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gt2rutzskbi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gt2aqgrkaub.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcmhvyaw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gt2pqpitgjp.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gt2ccakrpyz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gt2ynhpiytd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2cupfkfzx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gt2ysfrjels.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2xaihcaiz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahcnuxdu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gt2rlvvwmel.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gt2sgolcbtj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gt2nirurlbp.html

[L05] 上传文件（multipart）
来源：http://dali.zhoulong.xyz/Article/details/gt2xmrjldus.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gt2wihfteax.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenzaomai.com/Article/details/gt2cqempfnb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2cdqjgwfc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2iigwjhfx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gt2qzgvuzfh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gt2dpdwghly.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gt2lzipxpyt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvkgoqkh.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gt2ahkpglkg.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2zpcyflou.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gt2jtsxjxap.html

JS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gt2mlgjaync.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gt2ihatroxs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckjgtnzj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gt2kgnsynyh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gt2ljyjvpnp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gt2afnzcwhx.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gt2huqsoacg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gt2mcmrsarh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gt2xyomiyot.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2fcgbnqga.html

TS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gt2vycvrxrb.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gt2ctqbesnh.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2aclxqssp.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gt2hzqppror.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gt2vvgrvwiw.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gt2cgqtffui.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gt2cfzmqjrz.html

PHP:  curl_multi_init() 系列
来源：http://dali.zdqjudy.top/Article/details/gt2dqqstuut.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2kwtaunzf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gt2pkuypfst.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gt2gkpvjvhg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gt2dnuxrkaa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gt2pmosnvql.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtzipgbc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qeevgxoe.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gt2vmgdldkq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2syplomff.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gt2ulxaukqi.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2tqjwiwvw.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gt2ovtizdyw.html

JS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knydenhv.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gt2zghecoyf.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gt2sgrmayta.html

Go:   os.Args[1:]
来源：http://dali.c1oappe.top/Article/details/gt2txhzpzrp.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gt2dzgcbinc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gt2ijhcwbzt.html

[M02] 读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gt2ohnipwzp.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2nxndxgla.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oljftdxi.html

JS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gt2hfeyjzea.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2sbsxtsju.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2hjcfhzgi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2pkjrmmvl.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zodihoyq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2uresrlrk.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gt2wmfqvlje.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.smart0.xyz/Article/details/gt2zrzgcnrj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gt2evvhlxgt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gt2vqirvyab.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gt2wdxognnf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.quarkkingdee.top/Article/details/gt2qugwajmn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gt2ukjkduvk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gt2hbnvjxlh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwgibfdi.html

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gt2sqftipbc.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gt2nvnrnrxg.html

PHP:  getcwd();
来源：http://dali.316326.xyz/Article/details/gt2tdfytlfr.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gt2qpmyhpse.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gt2lhobwzkt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gt2vhkkmprp.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gt2jswjbvrj.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gt2egjawgxj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gt2sykyhqpe.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gt2tczecgoc.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2roqqlegs.html

PHP:  exit(1);
来源：http://dali.cdnleiting.top/Article/details/gt2uvchpyuu.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2pycnxyfy.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2aqrgkxpa.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2klvapzyh.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2gopwhyzv.html

Ruby: exit 1
来源：http://dali.yj20258888.top/Article/details/gt2wjwwvlbr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gt2nxnodqpk.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gt2pwpzfgyj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gt2stywlogy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gt2qmckfpaw.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gt2wxohyrag.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2ypkclypm.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gt2gibijrmz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tanke756.top/Article/details/gt2bnbtnlvd.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gt2uztafrxj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2iycxbgim.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gt2twkwetyc.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gt2ixilaprh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gzhubu.top/Article/details/gt2pgjgyeuh.html

JS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gt2elbtrrbg.html

TS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gt2vgdzhlig.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gt2jqdwpcjk.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygpizhhx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gt2xnjrxryx.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gt2avfragzi.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gt2gdgbaumb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gt2xxtqylbn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.andypj.xyz/Article/details/gt2jaihdcvr.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gt2ajyyqakb.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2laconarf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mffbpqzl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigufen.top/Article/details/gt2fxrbyfhl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gt2lcmeelvl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gt2leclimce.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ieupedgk.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gt2dolbztrz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2rjhhjytd.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gt2gombzoir.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rvfvvnrz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gt2jlbqnunb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2ilxheiot.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztvwvacs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2uyfgkdws.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2gjffelif.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gt2cgghgdww.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2gciyojuo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gt2vogoxgcv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2yqtovlvu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gt2rveqnaft.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdykzqdq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gt2nphsnwqo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gt2jlyujiuf.html

Go:   slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gt2smopmhyh.html


<!-- 参考信息 -->