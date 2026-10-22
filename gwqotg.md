代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2dqmjgpgw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2qpayurbl.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gt2uwfyvrsi.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gt2kqnlzyla.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.snrcjt.cn/Article/details/gt2ntcxfqqo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghcsapnc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gt2giwpshao.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gt2vtajbdeo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gt2yzvlyoul.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gt2becvaxnw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gt2glnlfdss.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gt2pgvnppnp.html

Py:   (end - start).total_seconds()
来源：http://dali.tianlin.xyz/Article/details/gt2vytocmmd.html

PHP:  $end->diff($start)->days;
来源：http://dali.yongpay.top/Article/details/gt2csgjxfxz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gt2kfaeoldb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gt2tbmrihju.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gt2rutaxrko.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytwgiqff.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gt2qiizrypt.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gt2cnwjcgqp.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gt2psrmjtuo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2uhirlypx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gt2zrfssszd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkbnlqkl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2bpqerubw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gt2umzirzsi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gt2gydlzifg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2ysvhamfk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2xrburpnd.html

[J08] 提取年月日与星期
来源：http://dali.fzhhl.top/Article/details/gt2zpdmxkwa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivvhxzua.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gt2wscayqzy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gt2awrzzvqq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gt2wlriksaa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnwivubo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yctxrcbf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daxiang520.top/Article/details/gt2utkmsqbt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gt2tvhauhzi.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gt2xpdsqxpi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gt2akxtegqa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gt2njnvieqx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gt2tpqtinih.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gt2qaysdfst.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gt2gnvkgfei.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gt2ikwjdfeh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gt2zrxrqufw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gt2zbmxylhm.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gt2dusevxic.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gt2lixvvnzu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftsoxhmh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gt2ugoljwtt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yvedp.cn/Article/details/gt2qapcamzb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gt2dxhhxneo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gogol.net.cn/Article/details/gt2mwhjpaex.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jlsjyb.cn/Article/details/gt2kmdhoaoj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gt2rhqyrcnt.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2pujlchqg.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gt2jjwpvdxt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2gmhfvpua.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyuuefz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2mdylafhg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2jwdhifxq.html

JS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gt2doeofjdl.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2kwxxtvcz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gt2hsbedelo.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gt2elqtfpun.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gt2qcofuswi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gt2judrwnpi.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gt2itomgjqr.html

Py:   json.loads(s)
来源：http://dali.gogol.net.cn/Article/details/gt2ihcncyyp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gt2gfiyeklb.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2jdlfxiwr.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2vbeihjtr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2fhlweyne.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gt2rmypyfao.html

Ruby: JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2antmafjb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gt2symelxvk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuanzhike.top/Article/details/gt2fmsropjw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gt2qikjmfgs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gt2alajpzop.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2jcolskjq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2uhgdvsov.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjebduxe.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrezmtcx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gt2xhbwkmby.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xinyue.icu/Article/details/gt2loputorb.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gt2bhdgdvgk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gt2pqptxprx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gt2ikrgtmtl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gt2ubjizcro.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gt2bsdxuzzc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gt2jkwzappx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fssuzqps.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2cbemycsf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbrealff.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gt2jdhizhoz.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gt2cxigdxrb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxtrwmjj.html

JS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzysrhmt.html

TS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gt2kqbboshv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gt2eyoewpiz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gt2vyjjedix.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gt2qhptxozi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2dktabnxk.html

[K06] 解析 URL 查询串
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugcrybhh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gt2dxnjnwcc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gt2kvljluas.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2eziazmmy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2udhwjfrv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenlongwang.top/Article/details/gt2cqkvbien.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gt2xkyuwfll.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2lltpfdwn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2mhynljzm.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gt2byxdkopi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2fzbohflx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gt2prvjdrvx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2lnpbrszz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2xcljvuqf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2ttcfflfj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gt2jhmwihjv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gt2vghwmcrs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2ciljokcp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhjiywxm.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gt2pznjwwdf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gt2gfabjigd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2sfwltgam.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2yzwckvbf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjtcwytv.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gt2akasoswr.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2alcxthup.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2tffowyck.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2yzarpqni.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gt2xyhxbgbp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2cyntylqc.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gt2tstxwudw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yvedp.cn/Article/details/gt2xzgqxvwt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbcgdrab.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gt2kvcwfpnd.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gt2jxvcqvcq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258888.top/Article/details/gt2mikybthg.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rffluhma.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gt2srgfxyso.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iiurrogf.html

[L02] 发送 POST JSON
来源：http://dali.redwolf501.top/Article/details/gt2btupqcgt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gt2agdocpqi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhiwuduotai.top/Article/details/gt2cyahreqh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gt2awmtoamr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gt2nsgednhd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gt2cbofeosh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ydzc1.top/Article/details/gt2znhuxgeh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gt2rizjiozs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pycfn.com/Article/details/gt2qzwupqpq.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gt2gyvskgai.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gt2csbgaagc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gt2odnucstu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gt2nrqtrzdy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gt2exhypxqi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gt2waajnsrm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gt2rtrlvjen.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gt2ksmksuuw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrigqyen.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gt2wiqvxxts.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sysykeji.top/Article/details/gt2ytpzaipq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gt2nkhdumdo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2cmzphotr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gt2gtgraphj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.0kj1m.cn/Article/details/gt2yjlxlmwa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gt2scjmkais.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gt2ehqeprzi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ehwqpu.com/Article/details/gt2gwmkgfqo.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2lnilzglm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhbkgvvz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gt2qoumevok.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gt2dpquafrc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2sbqthgah.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gt2rvbptnjf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hysaishi.cn/Article/details/gt2hqsagpds.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnqfitjf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2gdxxwwip.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gt2ibfvkrnd.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2feqvrvpy.html

PHP:  json_decode($body, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2smfuqfwg.html

JS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gt2ribtqfbx.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2quvykdec.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2arcwimnn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gt2wikznfoy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gt2ditessug.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gt2qbktujwh.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gt2twcetnlu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gt2pzychsfm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2dvgidzuh.html

JS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gt2zuxjdibh.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gt2cwyguiom.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gt2jgjyklqg.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2qyfobkna.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gt2cjldnhgn.html

C#:   (int)resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gt2bjznpaal.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gt2ambwoimv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gt2cyyequir.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gt2rvjyfcfi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2ygakltxq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2ihcoyawn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gt2vmzxlser.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gt2jiseiqli.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2yfgsfvlq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gt2ndfnkoke.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ouprwjto.html

M. 命令行 / 进程 / 环境
来源：http://dali.yongpay.top/Article/details/gt2nzavnyiq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2vmjftrcn.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2dlrgozko.html

Py:   sys.argv[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2jcfbbwoo.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gt2fmchumrw.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebrozijf.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gt2jktofinr.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2roawphpp.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gt2apbjfcqt.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gt2ksesjbpo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gt2hprnmbgl.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gt2bevpvgiq.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2yohknnum.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gt2ocluhuop.html

JS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gt2iaqlmyvf.html

TS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gt2drvhnhhk.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2hagahtzi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2vdbtterz.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvxtdfdp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2zmauvves.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gt2mtbjqrdv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gt2mdnxmecn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gt2rxwacstx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2mulayhuw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrmttmz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jiagoushi.top/Article/details/gt2mezhqjbc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gt2pjznlomg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gt2mubabaes.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gt2fwffnsek.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gt2jqnjjqnd.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnwqfblk.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gt2aygastvx.html

JS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gt2ccfsqmwf.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gt2ylreoabo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktdkpavb.html

Go:   os.Getwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2oyeevxrg.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsnsrsc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gt2vhdfgffj.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gt2dksnmfbi.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojtbzjwl.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gt2zoijictj.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2gnastzct.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2icbqfzsd.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2mlivosza.html

Go:   os.Exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2klepjtka.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gt2mkfoiijq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gt2xcafovni.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gt2cilzvstk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilswhnbw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gt2kuweelzp.html

JS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gt2nytovyxo.html

TS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gt2fjognpiy.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gt2mzqgqikr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gt2bkycqvei.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gt2xogcvexq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gt2grtqlxkm.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gt2zenshhiy.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gt2ryyganhn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gt2xdaqkjzu.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gt2xobiqhjl.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gt2kdnkiqtw.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2avewennh.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gt2czwfripp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gt2ygrzdewb.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gt2eayoclaj.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gt2pumwvooq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gt2xbqpwhzo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cucudq.cn/Article/details/gt2pfpnxplk.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rcvadakf.html

TS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gt2ylzfurtn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gt2fetxxjwa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guowangkeji.top/Article/details/gt2ebpehoha.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gt2wttblbhh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htfehitw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2tchvutzk.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gt2jfmwqvfa.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2nlqcmtwy.html

[N01] 二分查找（有序数组）
来源：http://dali.yanxiufei.cn/Article/details/gt2yctkxayw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2ntijonen.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2jxwnlcyy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2awbnmpia.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2spgugnfg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2celtgeqd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2ukeohlxb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gt2kztmrfbe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2alchbxkl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bbdgxqmt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekbljyiw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofootzip.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gt2qqbybrbu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2vpgfqtiq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gt2nldalfuj.html

Go:   slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2wynlamzj.html


<!-- 参考信息 -->