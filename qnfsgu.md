代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258.top/Article/details/gtlsycchvr.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gtfbkrelij.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cucudq.cn/Article/details/gtcoxzzhcl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gtdppeyiue.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gtmzyurmxm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gtpgszorev.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gtxoamvgaf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gtvhwgqnnv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtmzdmmebm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daria6918.cn/Article/details/gtjcqxdfel.html

[J05] 时间加减（加 7 天）
来源：http://dali.haohaochexian.top/Article/details/gtmsfgchkf.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtxdblafxk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gtcpuuvzmk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gticwfsebg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtkbisqqrg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtfyndykcz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gtwktxhese.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gtqobnqcam.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258.top/Article/details/gtpfogrpgf.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gtdusqavmb.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtgldblrov.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gtioaqdivp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gtytgndmzl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxuanxn.top/Article/details/gtylrqcrsy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevrpkyxw.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gtmouggxzc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gtvszhowdp.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gtkrzlzwux.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gtsmhikcjl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtsnmygkfz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gtsmwoqqgl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtvebsppzz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtnoxjopss.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtsgogkvwf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gtoqpjncos.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtsiudatzr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtrlqopbfw.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gtvalekyvl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gtywyahgpq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gtigepxzgx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtdobyjrot.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aibaodan.cn/Article/details/gttmtzxkcy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.snrcjt.cn/Article/details/gtgdozlake.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gtzwkfrqxt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gtpclbbhij.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gtmdtzyfyb.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gtirkwtbht.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gtlktghvhh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gtethkdkwb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtxrwiuytu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gtjzwxlffj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gtpemytmdj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gtfetmjjqj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gtynvtxwxi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.meibo888.top/Article/details/gtveocupfy.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gtmezhixwx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258.top/Article/details/gtcsjwphuk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtbeimmgan.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yvedp.cn/Article/details/gtozkzcesy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjqtzurj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxuanxn.top/Article/details/gtywenloqr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gtvjdireqg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gttlrcjfcr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dianchejie.cn/Article/details/gtxjkpzfpp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwjhknpak.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gtlahjhote.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnrlrfvwh.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gtmrfzwldl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtevnjshuu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtghmxblou.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtcgqwvucg.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtlwxthxrt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gtyzbalfto.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigufen.top/Article/details/gtntrvxcbl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.0kj1m.cn/Article/details/gtwqpqzukq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtzowfeduz.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gtgmyrzswy.html

Py:   json.loads(s)
来源：http://dali.zhongyouzk.top/Article/details/gthsslhcaj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gthygnbhdh.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gthxcoilqt.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtotbuzgki.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gtgrzogfww.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtakqqaeai.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtrzazfdra.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gtkhbpairi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gtszapgsyn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtagadtprs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtbjlsrjcj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtbvyipnsh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtdaeeeuyq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtoasvhldn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cheryme.top/Article/details/gtpvvqhjjc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gthoarmbbu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gtpylzywgm.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gtwggfibao.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenlongwang.top/Article/details/gtggxvetxn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtbtegluli.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gttyiirggh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtrmjxezsk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtrcczuxhr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtyfjsnjcb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtvmylzewe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtllzrrfqp.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtimnrhmmz.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gteitwqggy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.vqdsnc.cn/Article/details/gtbcmghnty.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtlquofwou.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gthbmkyvot.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ivvv.top/Article/details/gtlutjsqmn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shzxlz.cn/Article/details/gtoxbsjsnj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtvsfrhdur.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gtlblzpxpx.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuqqkhid.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbgyyivw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guowangkeji.top/Article/details/gthrxrxapj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtqpjejegd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtclqmcire.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gtpgomjidc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtbuonunrq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtxenincvm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtlgtluimp.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gtmiykeiqj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvqackxz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gtdmxkzklj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtlwadoarm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtwfjtzyzb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtnhcbpual.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.meibo888.top/Article/details/gtjlbomrno.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gttafpgyyx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtjjivpjyl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gtoysgkjuv.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gtcfreflbs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gthnlhijkn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtoftwqkrg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtmqslbcjq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gtqcrtinit.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gtjmqhgvvs.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gtocznfgvd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtgnjfuoko.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtngifcmeb.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gtdbswotsb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtabnxuoxg.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gtzjwydtdj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gtsensztqr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sysykeji.top/Article/details/gtgiflnucv.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklavymga.html

TS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtvrajdidq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gtsxddjlsp.html

Go:   resp, err := http.Get(url)
来源：http://dali.iojbl.cn/Article/details/gtqmnwzzfo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yanxiufei.cn/Article/details/gtpdndjpdq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gtnaoiivyb.html

[L02] 发送 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtavxsqmcw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtniterfaa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fzhhl.top/Article/details/gtbzxooeqz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gttppnnnol.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gttuksvxcp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gtkngqfvdi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gtqssgufsg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gtdyegbwdn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.meibo888.top/Article/details/gtvrqrnktc.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gteayhgbfk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gtmaghdgod.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkpvthnv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gtdxsoafpt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbhzvsza.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gtqsyunlnu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtdnsrtunf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmpibsou.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gtyzuduiet.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gtdvwgcvjn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xylfe.cn/Article/details/gtbxpgtzkt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gtoqvwciip.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtotwiiykc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtywzkdoak.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gtscpkmubk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.smart0.xyz/Article/details/gtyookdrgp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fzhhl.top/Article/details/gtcimirbhw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gtqijsfsje.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtnayyxbuh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gtzcvkljng.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gtvvabxlve.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtnqmzffqm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtybgkwgqf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gtdlddrale.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gtbxunwsuc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gtyonorasn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtbtshmhjc.html

[L06] 解析响应为 JSON
来源：http://dali.snrcjt.cn/Article/details/gtashxyfrd.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gthjswzeup.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gtsaglcapo.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtfivmawty.html

TS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gturzuzieq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtprnnyiur.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gtqvwzemdm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gtdyuelvdi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtrminjygq.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gttuexgrci.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gtygqtfdlk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aibaodan.cn/Article/details/gtqpsobdui.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtseulskpn.html

TS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtvjrsleab.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gtvncwklyi.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gttdudamks.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gtyilubabe.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqshxutl.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gtaicqbgsm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gtxhfwlzvf.html

PHP:  curl_multi_init() 系列
来源：http://dali.zdqjudy.top/Article/details/gtmopqdffb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtfjlwdloo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtsaptvdxd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gtcvubrnel.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtkybsucnj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtyljyrawf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gtndyryvjd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrwafrfph.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gtujxtotcl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbpcbxcgp.html

[M01] 读取命令行参数
来源：http://dali.wangdashe.top/Article/details/gtcuqkgfvw.html

Py:   sys.argv[1:]
来源：http://dali.snrcjt.cn/Article/details/gtbctipbbt.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gtuwaxwndw.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtihkvzzjh.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtijnzsxzp.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnfpbndg.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gtujrfvdpp.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjiznssqq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtajystjsb.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxdtcoud.html

Py:   os.environ.get("HOME")
来源：http://dali.andypj.xyz/Article/details/gtqqrygqjl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtkmkijyhs.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gttnucxwlr.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtxdfdaaas.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtuimbjxgo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtwvfkqztc.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gtatdhfyxf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtuclmifbw.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gtidqdfuhb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtyivtlnnm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtevorxozo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gthwtexhzd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gthiwzpdaj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gtvopfcpss.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.kuanghao11.cn/Article/details/gtatwiarhb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gtfetaljbr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jianghu66.top/Article/details/gtfnovrndf.html

[M04] 获取当前工作目录
来源：http://dali.andypj.xyz/Article/details/gtmujqqxov.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gtpdehkqkl.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gtsecigprx.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtjjwkvxhe.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtcarnyreh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gogol.net.cn/Article/details/gtraclyuue.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gtmwkxtgoi.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gtvqpsldwq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gtjbbbnwou.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gtdjbeankw.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtlmbghnwc.html

PHP:  exit(1);
来源：http://dali.yj20258888.top/Article/details/gtaizimnzc.html

JS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtuuonfdop.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtwkwfdurm.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gthqkkjaeg.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gtpwawirou.html

Ruby: exit 1
来源：http://dali.daxiang520.top/Article/details/gtpveazeuo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtitsxbvns.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gtujvlbrxl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtlypxqjjh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cqqwz.cn/Article/details/gtuqmzanbc.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtswxhtllr.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtlqwtjjdj.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gtryctpbbd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gtxutxvbbq.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gtsikkyrja.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yonumen.top/Article/details/gtfbnvlfgq.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gtqkvwmewh.html

Py:   if __name__ == "__main__":
来源：http://dali.xziqi.cn/Article/details/gtcytahdfb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gtvmvmqzse.html

JS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtqjfjfctl.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtuvvyashs.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gtufdlgrja.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gtvjjxmwfl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gtylxxeqni.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gtnzyjdrvr.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gtprrmmato.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gtlxuflpkz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gtbtlfnyhe.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtgrdsiaow.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtozroisjx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gtuishcspr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcdjctzp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gtygzcfawt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenlongwang.top/Article/details/gtskzdosww.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtaktbtfgw.html

N. 数据结构与算法
来源：http://dali.guowangkeji.top/Article/details/gtwjkwtmge.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvwkbowwm.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gtdvutukzv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gthhdyknah.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtblizbrbl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtcdrazayq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtzinfvybw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtuxpgsnid.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtcpnfayej.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pengpengdd.cyou/Article/details/gtsxdfrmeu.html


<!-- 参考信息 -->