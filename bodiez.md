代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adoaqjbk.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gt2plimpvic.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2lbyuiyqe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gt2alocmech.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.havefunace.top/Article/details/gt2guzhzime.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnlytijb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2ayoganel.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2heumkjze.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gt2yrzevgni.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gt2giypslgy.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2phaouczl.html

Py:   now + timedelta(days=7)
来源：http://dali.zycfv.cn/Article/details/gt2jsafjwjd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gt2cfvoaayp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqukdnhf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gt2ocwyisak.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yynfnrcf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jianghu66.top/Article/details/gt2qncswivv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gt2btmzbiee.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.316326.xyz/Article/details/gt2xzrhbtva.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aggdllzo.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gt2xyevncta.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gt2jpweauwu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gt2kwmdlzid.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gt2gmfsqiaj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gt2avubvsrw.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gt2jtmqflfb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gt2strgsosq.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gt2tiiwvemk.html

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gt2ltstxfyd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2zymqaymz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gt2dmjhwqgx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gt2xvweawby.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gt2nfgicedq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gt2adfnigne.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gt2exkbiymf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2asairneb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2inexyefd.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gt2nutnryhw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cdnleiting.top/Article/details/gt2jhoyvjay.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gt2sywvzdkm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gt2qdgceudp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gt2vntlvaij.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gt2iqtrqgbg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gt2sqvyzqas.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gt2ashhvdcs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gt2rupzclxc.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gt2fiermeso.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gt2enainygo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gt2cmrcbcuq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2vlwrigkq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2ysdkuttk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gt2pymnkxfy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gt2dzsokols.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmyfzzvz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gt2oaoprrxc.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gt2khtnnlge.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gt2obwxkilm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gt2xhdlwdbs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gt2xeydymhr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gt2hpszmzei.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2afdqckkh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gt2acztlyrn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gt2hnszwvvm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gt2hicnfulr.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2buimioes.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gt2xmddkrrd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2iyexmmoz.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gt2zmarkpxf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gt2syblxrmo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gt2mfqzunwn.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gt2aglomyhv.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2jwodgyse.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gt2ooyctwyb.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gt2vjmnrqtj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gt2njvxicqb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gt2sbwmzhoc.html

[K02] JSON 字符串转对象
来源：http://dali.mhx1999.top/Article/details/gt2gvepnxxh.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2fslcwnui.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gt2znsscvyu.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2bqamywfn.html

TS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2sntuounw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpioqgnd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2qkvjekcv.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2hsflxmxs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nwbrower.top/Article/details/gt2tivzufkz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gt2gvgseaok.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gt2iwldiilp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gt2sjqlcasb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2ukmicohi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2npzybtrf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2ovphbvyy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gt2ltfepcio.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gt2qsonerzg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gt2yrflipsf.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gt2ldtffhph.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gt2frvmpqmn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigfzy.top/Article/details/gt2grgphefj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gt2xkrxkrcj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gt2pnnsijdz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gt2tipgjiis.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gt2fvesjmps.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2rswovjrh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gt2nzyhgkmz.html

[K05] 深拷贝对象
来源：http://dali.ehwqpu.com/Article/details/gt2rosobfwb.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2gmpmessh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yonumen.top/Article/details/gt2ttkrvsgj.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2hgyzwxlu.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2raysfqft.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gt2lqwfjocd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gt2dynesxyj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gt2krgxnrbf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuxming.cn/Article/details/gt2odwrzupp.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gt2srxbvwsq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrjixbcr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfrgkmkt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2cravlsul.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gt2ccduwvxo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gt2jqyeybti.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2uqjwttxc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2pcelmezu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2htqyqlet.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gt2tqtyjasm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2bhosyjrd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgufenzy.top/Article/details/gt2qvjedzwf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2yutxhjnm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nleqslxy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2aikwaivq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gt2lazujlrl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuanzhike.top/Article/details/gt2wfuelxvw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2qaromcyi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gt2dqhozpft.html

Py:   pickle.dumps(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yekzriha.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gt2wdznitqo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gt2qecdepfq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gt2lbxlmsbr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yueranfly.top/Article/details/gt2ogcqebug.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gt2ottdsspj.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2znugcevq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2dzidzrsd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2agcaoxoe.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gt2dgdqkbfv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2zvzcooet.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gt2asevizyk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gt2ntkxqlvw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gt2hjpqwedn.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gt2zuzlozeu.html

TS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gt2lcxckbik.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gt2gopvryyg.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gt2fsgdzyee.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gt2oyxaqbwy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hammf.cn/Article/details/gt2bcubpuwf.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gt2hqsrxwej.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gt2duhebrfn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guowangkeji.top/Article/details/gt2gskoifqd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gt2gywzmjnc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2sojqteur.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gt2lsqbwguz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gt2drqgpfso.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gt2lylmdoxe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gt2jzlxzyzd.html

[L03] 设置自定义请求头
来源：http://dali.pycfn.com/Article/details/gt2uewrlels.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gt2rgsgcjqy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gt2ujwmvypa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gt2tvhkygey.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gt2piagocfd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gt2rluvavmo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gt2gifpwupn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gt2cixjgobv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mctdoryi.html

[L04] 设置超时
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gueqnwwl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gt2ibtnenzc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gt2kicckqql.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfhdfipz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gt2lahutobz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gt2admlfphz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzeskujh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhengqikj.top/Article/details/gt2cxgjrepd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gt2rtzvtoin.html

[L05] 上传文件（multipart）
来源：http://dali.yvedp.cn/Article/details/gt2bqweotaz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gt2melzsyma.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gt2ygclkdey.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gt2tboqdzqn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2igrbkygv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gt2ziecsgxd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cucudq.cn/Article/details/gt2anyablfx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gt2jhpspruk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2snrgloqq.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gt2rtipsivx.html

Py:   resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2lhxuluzv.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogtafngs.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2diufqjiu.html

TS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2uvlukvlr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szhcfuyh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gt2msjcpzra.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gt2uaqefocg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhixingplan.top/Article/details/gt2ycwdpjhl.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gt2pvttkcvo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gt2xhxpsbdb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gt2cqvwaosd.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gt2oehuitip.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydnucsan.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhglsvdk.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gt2vjgztuuh.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gt2vugftutj.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gt2nnzuqtnh.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gt2anlbfdhr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.andypj.xyz/Article/details/gt2yhfwzuzw.html

PHP:  curl_multi_init() 系列
来源：http://dali.sysykeji.top/Article/details/gt2ymrfhgmm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gt2vggizzkn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2mdpygvpy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gt2cdegriri.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yltvwill.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.0kj1m.cn/Article/details/gt2yynzxmdn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2mwmhqkhp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ipadcjob.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gt2edrmglvn.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2hsmdpyov.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gt2ttjdtvto.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gt2kzxvvayo.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gt2jnnmesdq.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2lcbdeyvk.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2rpwtxbih.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2schbjpea.html

Go:   os.Args[1:]
来源：http://dali.haohaochexian.top/Article/details/gt2aaskkjlc.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gt2gbbiwzql.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cashguo.top/Article/details/gt2xtomhmam.html

[M02] 读取环境变量
来源：http://dali.aizwys.cn/Article/details/gt2zvvdhikn.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2eqhhevqc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gt2efkaovgs.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gt2yzxkalal.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gt2lnfwocat.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2wrnqglbt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2rkjjbkbb.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gt2vowpgaoh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2vsvrlffw.html

[M03] 执行外部命令
来源：http://dali.guowangkeji.top/Article/details/gt2vmtpytch.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gt2xuykhgym.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.quarkkingdee.top/Article/details/gt2uxefzjwf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgixkjwh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gt2stvyqane.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gt2wbtnbpwr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gt2kpbhqwru.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gt2zkcbjqdm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gt2qriedhuz.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gt2pqnaeaaa.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gt2zwvabvzo.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nyqhoaom.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gt2ckkqmmeb.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbirvvxi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gt2qcdzedxm.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gt2yxoucegg.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gt2urqczjri.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gt2kjxmrmgm.html

[M05] 设置退出码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2feoicyts.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2xjyvzmkf.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xlfblsci.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2agfkozwx.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2ufzqczca.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2ggzfjhig.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2vdbhpdaz.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gt2rkkhxibi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sphbaiih.html

[M06] 向标准错误输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbmlpegy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2khvliyrm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ervdjpfx.html

JS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2cphunirz.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2drpdssep.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gt2ksyocejx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gt2bxnkeaxt.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gt2qlmofmnf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cyerzgsx.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gt2osjgzweg.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gt2ltnzkfiv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gt2ydvzwzvx.html

JS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gt2qmivuzyb.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gt2vcuzpksk.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gt2pmhplsah.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gt2brwiuwwz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gt2dbdunpfs.html

C#:   static void Main(string[] args)
来源：http://dali.redwolf501.top/Article/details/gt2ujhtyeam.html

[M08] 获取系统与运行时信息
来源：http://dali.yuxming.cn/Article/details/gt2ygqxljpi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.316326.xyz/Article/details/gt2ubroajws.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gt2pumbpsau.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gt2xcuqeaco.html

TS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gt2ehieovhu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guowangkeji.top/Article/details/gt2yoowqzhd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gt2tmmfoett.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhixingplan.top/Article/details/gt2tmancpfb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gt2atmyjaey.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ehactprm.html

N. 数据结构与算法
来源：http://dali.sufxvd.cn/Article/details/gt2orwrqobk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2alksmeiw.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gt2dtecnods.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2sefywlek.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gt2owythulx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gt2cglzxkiq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2eqigjevg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2agbfghbr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2ckfvgxoa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kpgxdozh.html


<!-- 参考信息 -->