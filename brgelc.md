代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtgeclzccp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidbuplft.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtlomqfmvc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtisivjazc.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gtwztbuwxy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gtkmzvrywd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gttqqhsbeu.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtcwzniobx.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtgnezmgyh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtpmtfjzzd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtbtkeikds.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtrbggfafr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgfzy.top/Article/details/gtkwgruiio.html

[J04] 时间戳与日期互转
来源：http://dali.shuidangran.top/Article/details/gtqzzoodbk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtxiwxqrvi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gtehqsjxxs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gtcisplbta.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gtbflispct.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtuahumang.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonkwhfry.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gttdzcgwit.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgfzy.top/Article/details/gthxmfonmo.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gtrkupzviz.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gtlfqvzziu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aizwys.cn/Article/details/gtiskrmlfh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtyyiknzpj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gtrwwqkxhm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtkxetluoy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daria6918.cn/Article/details/gtddqbxtla.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtpokqxbid.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtsyaavbdf.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gtjsesautt.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gtcjyduzjb.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gtwuihbzng.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gtoatcnyap.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gtxtmvprtw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gtbbohaajx.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gtciavvepc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gtfltklzqe.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gtobvkhzbr.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gttkaufozh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtwpnbmafi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqivfihl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gthieuqnzp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtlyanfcdo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gtochieako.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.svipenyu.cn/Article/details/gteqzlicab.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtdjaffawc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtyxocyxdy.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gtcsdoyoae.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gtcyneykxe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gogol.net.cn/Article/details/gtkvjivizi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gogol.net.cn/Article/details/gthatcgudi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gteoetyiin.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gtquqsuysp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gtohbibkxk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtdzvtuhpw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gtlipzpuyr.html

[J09] 时区处理
来源：http://dali.hongshengwenyu.top/Article/details/gtxtdodefs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hfpthk.cn/Article/details/gtkewvgike.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gtguplkcdl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygonwvhd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gthaxxpwxs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtsjcznhth.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jlsjyb.cn/Article/details/gtvxopnufn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gtablytpdq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gtizwxizfp.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtkmljrntf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gtquvbdlxu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yongpay.top/Article/details/gtmlmkksmg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gtpgkhkolo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtrzpmoblf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigfzy.top/Article/details/gtqxcblhfh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangdashe.top/Article/details/gtystarmvu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gtxcmmthul.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtrynvlvam.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtcqvbpqct.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gtvbyhxmpk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqstwfrt.html

[K01] 对象转 JSON 字符串
来源：http://dali.vqdsnc.cn/Article/details/gtsctdffzx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtudycbodu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtuualpmks.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gthkjbnqgj.html

TS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gtamukxuwe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gtkxbgleqk.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gtzlnfjonl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtwzkmhfps.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gturowlqmp.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gtvxpqjmcv.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gtifpmwsbg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ivvv.top/Article/details/gtypncspmk.html

JS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorgggfzp.html

TS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtoyngqqij.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gtuyjujkce.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtjpaagkzi.html

Ruby: JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gttmhwsadu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gtpttleigb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gtzcofztrn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gtinkmyoey.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtehnodywb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtwdqjbesl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtppeisljp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gtyjyyjjnr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvthadtao.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtsuxxdabi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gtrbjynkkz.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtcqxhtbvq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gtqspzamtb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gtossbyqua.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtumdddmdp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtulvjvsqy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gttogtnszl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtbolbfvjc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtfvtghxsl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtgghpzhvy.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gtitnwvyba.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gtbktwmmfu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtbyczpamz.html

JS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtkyiqexws.html

TS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtkjuqeodb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gtiribwdqi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gtixjjwmnq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gtfusxsoai.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtovqaqjei.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gtaedtqoqy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuanzx.com/Article/details/gttapvkzog.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gtxscueomr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtwmwcxhzp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gttdniqgen.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gtwpoczspp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdoufxwyy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgtgoafm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtyfbdxxkz.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gtgxarxesm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtpuyetsbz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gtbvohzwvl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gthpjowefj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtpqccomii.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gthgogxbep.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gtcuuvlpke.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gtkiwgqfjb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtuhylecfb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gthbsatine.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnoplzats.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gtdycltpvn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtixjdykmh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtrduecrrt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnxiangtu.top/Article/details/gtiwpytdyv.html

Go:   encoding/gob
来源：http://dali.cdnleiting.top/Article/details/gtrpdsoryo.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtgqbnpgja.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtbtfzksqk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtcwpezxjd.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gtctyidrwu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnoqoxojs.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszivxbky.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gtnwlwxzjd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gthsqzcgam.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtlbzlgbpc.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtifsgbgsm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gtkajdpnrd.html

Go:   resp, err := http.Get(url)
来源：http://dali.quarkkingdee.top/Article/details/gtgcafsojl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxinkj.top/Article/details/gtjlnutkwq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtkbhztgce.html

[L02] 发送 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtnhpbkuhc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtqkcnkfeb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiensqabp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtajrrvwbj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtomcnvyfm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guannengcc.top/Article/details/gtjkdnbxqd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gtxuuxgurm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gtoqbvawvx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gthorqoxwi.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gtpwnbqffw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gtusgokhzt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gtatwnhndb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtwgjegefx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gttvrpyfdy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gtdjszghnm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gtgnivifka.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gtpulivqou.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtijlgyzdg.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gtsaqmkvjy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pycfn.com/Article/details/gtosrjcurb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gtjmpfzcoh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtshprtrby.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtvynofdjy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gtlceaaiwu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tianlin.xyz/Article/details/gtehwpndaq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gtvqltogob.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gtymqrrxja.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gtouculzmm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxnkukll.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gtihzkxwgd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtxqqkpzof.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtqegsqvyx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gtfxuqvloj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gttiyozpws.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtlzvojysl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtmvbtsbhe.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gtduvhvdkg.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtbgrukmbh.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtkcqrzdbk.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtvmuujzru.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtrkohvorn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtmkzuwnwd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gtfkyzzkju.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gtankqsdbh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gtupttjzqs.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtbzopmyat.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gtdsyensxd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtoeuskgji.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtpkkmwwvl.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtjhniscvr.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gtrdanrdiq.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtozeajypp.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gtfpjccygm.html

C#:   (int)resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtvrypoomn.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gtlmjmsnaj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gtkntcjjln.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gtanxxqbnf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtpotqniiu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtzystjghl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gtsrudycpf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gtrlgvakpj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtnbllsqfh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sxryk.cn/Article/details/gtnezvbkns.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtrotxjgtx.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gttjgmimhh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtywhlsdnx.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gtzxxudgvi.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gtgrprvjcg.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gtnedqktdc.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtfddgdury.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtnmueltws.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtkwvtknhj.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtphlowjgu.html

Ruby: ARGV
来源：http://dali.xuetiantiany.cn/Article/details/gtwkljjwyw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gttnhoklcf.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtlouaezsa.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtoltvqfhs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtgqiiztlv.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtzlgvfvxw.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtwnuvywsy.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtrwafwnzn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtknsxwjtl.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gtwonyihkr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtkgorlqex.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gtwcheupgn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gtnakqhzjh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtvejpmilv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtoucxzoum.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtqnineblr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gthklbfevj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttynewdjq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtocvhxslq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gtesgcalth.html

[M04] 获取当前工作目录
来源：http://dali.yj20258888.top/Article/details/gtqmflmorb.html

Py:   os.getcwd()
来源：http://dali.fengsongda.top/Article/details/gtkvzfbcch.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gtorlzjqbd.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtaljuigsf.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtfbqgwyon.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxaaliaav.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gtnpmxbehx.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gtoqsxwxtv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yvedp.cn/Article/details/gtfgjpchya.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gtvtvwdswi.html

Py:   sys.exit(1)
来源：http://dali.cheryme.top/Article/details/gtzafqkdax.html

PHP:  exit(1);
来源：http://dali.jqgufenzy.top/Article/details/gtbuzlwpht.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdldlnmin.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtxkifdjwf.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtqjjbyowu.html

Go:   os.Exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtmolfxyzu.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gtsdgeemgs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gtnokrowoa.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gtiddxpzux.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gtkslsvoxg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gtmtbkhcre.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtctkcvtfa.html

TS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gthmdrfkie.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtybqgwtyc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guannengcc.top/Article/details/gtafwbhutt.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gtzqhbopno.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dashuyun.cn/Article/details/gteryfyakz.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtipkcfjch.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtvqmkwhas.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.meibo888.top/Article/details/gtfzdapiws.html

JS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtyomcvznm.html

TS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtmqagracr.html

Java: public static void main(String[] args)
来源：http://dali.yonumen.top/Article/details/gtjyekyvrj.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gtnkgxzxmr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gtwwcjopyu.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gtxnblwvmk.html

[M08] 获取系统与运行时信息
来源：http://dali.pengpengdd.cyou/Article/details/gtkjbpzvjc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gtfwnvfbsd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gtkridoltc.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtnvooesbu.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtwfbqjhqc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gtjihsoruq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gtszevdlun.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gtzuukatri.html


<!-- 参考信息 -->