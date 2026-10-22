代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.dianchejie.cn/Article/details/gt2ttjwaccd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gt2jofhzrdo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zdqjudy.top/Article/details/gt2dhhnqgzk.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvjvifuj.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2vyvnafhx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2yddprvub.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2mcyweztq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajruxgdu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gt2oarzvunq.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gt2cpprgcno.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjlsyekn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gt2cjtijorm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gt2jakygqgj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gt2acpgsahl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gt2hiqmubec.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gt2nqtwismy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2vomvemvz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.birdmap.top/Article/details/gt2evjkwhrs.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gt2ipjaehuk.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gt2rkspturt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtrudibu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwkguvmg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qezmvzle.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2powuiizi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2thbconly.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jlsjyb.cn/Article/details/gt2mpvkxxko.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gt2tzerzeje.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gt2kaayvoru.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2vszshjew.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxinkj.top/Article/details/gt2busthwcf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gt2jbllubic.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gt2uqxwdiqk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pycfn.com/Article/details/gt2xvhhrcfq.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxinkj.top/Article/details/gt2abwtlesp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gt2ibixrxpu.html

C#:   (end - start).TotalSeconds
来源：http://dali.ybcxt.top/Article/details/gt2mxyqcrir.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gt2htbawoga.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2brltnkws.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gt2jgdsiwbw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gt2iiyohaqr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gt2cookkfed.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gt2dhlrmccx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gt2wgbazraw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gt2esetbpqx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2pystgsws.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gt2yvayisib.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gt2obvsxkuu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gt2hgdtokjm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gt2awjvmfaf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gt2smjcfuzy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gt2sgxameve.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gt2ycrgveeg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gt2fsccyuuy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gt2cwztrimm.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gt2zenoeyyw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gt2kblgmlxz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xylfe.cn/Article/details/gt2aojyrvtl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2exasmpra.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gt2rajimqhr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gt2kcngnrwn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gt2ipyehuzn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2syhbpmuu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gt2gaqcspdn.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvlfbtfq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugnymvwk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gt2kxmhrrcf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hywenlv.cn/Article/details/gt2lleuhcfc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2injywbxk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gt2tucjbutg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gt2alotpnrs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.birdmap.top/Article/details/gt2xejpokii.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wllkwfta.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2nyazhnhv.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gt2faghjmqf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2lmplxjsy.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gt2gbbqwfvp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcjzbzcs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2rpvgxnkv.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2saerljub.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtznwebq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guannengcc.top/Article/details/gt2iqfahbgz.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xnnrarry.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuanzx.com/Article/details/gt2bpmtopdo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2vukthlnt.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gt2yflomjtp.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gt2hktcdftm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqcetbpa.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2tcmfpkyr.html

TS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2vuokjhbw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gt2ccsjtpgw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2rammwfkr.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2hxaxagbw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gt2yzdebbbl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gt2hnqesctb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gt2oapoffqj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2htezrwxg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2xdrjlvhf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2vvbrbucf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gt2vijdllpb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gt2rpnebppg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2jceuvdot.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjutbaqa.html

[K04] 读取 JSON 文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfypahbi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gt2dzequxuj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gt2stoemwcr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2ihczqhpl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2nfdkiwnm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gt2hkvegguu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imeqmaoi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2xndrfrds.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cashguo.top/Article/details/gt2wjiynwif.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gt2xpakvbfa.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2oqqtsumm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gt2dealktas.html

JS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnqcltpl.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2epjvibwf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gt2kitneiok.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gt2puvzazln.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shfbrvfa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xcriosha.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gt2yjdyqpbq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gt2vwtwpvxo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gt2qiphjpsk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjcxmekd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2fbaanohr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gt2fmnslqck.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2fierhdle.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2ywgwbgbe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2ckcgeajo.html

[K07] 进制转换
来源：http://dali.dashuyun.cn/Article/details/gt2qlhqigvd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2ghpvvxbb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.svipenyu.cn/Article/details/gt2kdwjoiyz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2axfhfuph.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2boschvvm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2bogpgfry.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gt2yebivcbl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuanzhike.top/Article/details/gt2hytidioe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2wcmohlre.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gt2rzcwugfw.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2obcnktno.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gt2akdxxdrk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gt2agelxula.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2qsewytrw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gt2twkbkzfk.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvvfvxcc.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gt2gstimwnb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2ausfcark.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2cfqcedmq.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gt2pijzbioj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ftphjifp.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gt2htlosjjs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhpmikoa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuanzx.com/Article/details/gt2yziaktsx.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2xifwtzzy.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gt2hsojgudj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gt2rfbxtfyg.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2uuxkbkiu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gt2xaqkpscz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gt2kjcijcqt.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2dwhnegsi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ficntsyr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgufenzy.top/Article/details/gt2jyazeqzk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gt2nxujlwvx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxbyqxgk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gt2fwoazplt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gt2jizoplua.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gt2fkeznhnh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gt2iydxewmn.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gt2oiygqvmd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gt2xrhbzkua.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gt2ysyjtisn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gt2efxqblcn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvnfjnp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gt2pfvouokz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vksxlzvm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hfpthk.cn/Article/details/gt2ivmymnjj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwxwguzd.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gt2ztjzjhfb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gt2izlskajz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yvedp.cn/Article/details/gt2mamwbxaz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gt2zekcdomy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gt2kwehewmq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2qfzoczgx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gt2jykwzpym.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gt2yolbbxon.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gt2gndnpsoc.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gt2ihfvjenl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gt2sqjynfqh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gogol.net.cn/Article/details/gt2bvudlmsa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pggiwzjf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2luwkcisv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gt2sicyamcm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daxiang520.top/Article/details/gt2bmrbkhbb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqzwhlnt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gt2jfzbkvyy.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gt2pukecrdv.html

Py:   resp.json()
来源：http://dali.cheryme.top/Article/details/gt2oilpqpjg.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqrjdxh.html

JS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gt2kxusfdue.html

TS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2pdcbwxnz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2jvkdavme.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gt2fqjyukyw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gt2ubxbwemr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gt2gpqblcff.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gt2oidgieij.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.andypj.xyz/Article/details/gt2gnwsleam.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbetfhqf.html

JS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gt2bzmitbgj.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2tlglhyfr.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gt2uluswixp.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gt2nxjcnogb.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gt2aoljnkfe.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfwnsste.html

[L08] 并发请求多个地址
来源：http://dali.ehwqpu.com/Article/details/gt2cdrigyij.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhongyouzk.top/Article/details/gt2olfflkgh.html

PHP:  curl_multi_init() 系列
来源：http://dali.ydzc1.top/Article/details/gt2wptkyzsh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knjduuuf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2alcdhwis.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gt2pqpfhwqt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gt2fuulwowd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omryktvm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2kcjkuqiw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2cawakvyc.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gt2ubvhdqfn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2fzsnhhnv.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gt2vdjmepcn.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gt2ooorbtot.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gt2vcjehwoa.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gt2qwtuscfo.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iozwllby.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gt2dqgivxnn.html

Go:   os.Args[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2azgdpevu.html

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gt2hmnxdglo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gt2mvgrzelr.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gt2fwoqiffr.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2qyayalyn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2kkacfblv.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gt2opmgxdka.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gt2wmvvfzgk.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2jldqfplh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2sqepfmrk.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gt2dawlamxi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gt2jqbtvdyk.html

[M03] 执行外部命令
来源：http://dali.pycfn.com/Article/details/gt2kcnngadh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gt2ubucvupj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gt2sudynjrh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gt2imafzxhn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2tvbotdej.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gt2alzoirvy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gt2mvtgaswf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gt2zaockjhf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gt2wlzaalit.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gt2gfdunyqh.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oosnretx.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2slptoedy.html

JS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gt2dnxnmqgc.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gt2ncxanxel.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gt2ufkuxome.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gt2gewurubh.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vygdwhjl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufczhioz.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gt2onltgnrq.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2mshrvrfj.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gt2olysgzer.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2ucugvrzt.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2xadeggda.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2ypneharg.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2ssxjcsod.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gt2cycezrbi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gt2yjuqziud.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrgfhcmo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gt2moyndtkr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gt2joufaglm.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gt2sbzttqbs.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gt2werxkhao.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2ejmamzof.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tanke756.top/Article/details/gt2cvnnzfsn.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gt2itclshmy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ivvv.top/Article/details/gt2ermthdfk.html

[M07] 判断是否为主入口
来源：http://dali.mhx1999.top/Article/details/gt2fapmfary.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gt2aesvgbxb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gt2ebuimxdu.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gt2kgqjkgde.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gt2lrdkhijq.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gt2xwqpmpkx.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gt2ofldhkvh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gt2aqdkdtny.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gt2ocvycsnt.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdwljuqb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gt2drdxmyae.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gt2qydvkgxd.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gt2khvbhjdy.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gt2kgnoqazb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gt2zfzpwlws.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gt2lluovsyb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gt2snwrkrcf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daxiang520.top/Article/details/gt2xtgeafqw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2aqkkffee.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gt2jarlbwzj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2fbouihvw.html


<!-- 参考信息 -->