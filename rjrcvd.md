代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gt2huxwwezt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.andypj.xyz/Article/details/gt2phcmigep.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gt2ompmcbat.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gt2tavnegmx.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gt2ffzeslge.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gt2enazbgki.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gt2lluwakca.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2jgzxgmxo.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqcqsegc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yzmcrejd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2azgcxrbt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2tmcgqtnd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gt2ynywaesz.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gt2lxjvhibw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2zktwbexp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gt2hsadxfcp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gt2hwkdsswo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gt2pzbhxvvx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2oqvkdgjb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2abrbslsz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2yusfffpr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2nroffpxo.html

[J05] 时间加减（加 7 天）
来源：http://dali.yanxiufei.cn/Article/details/gt2lleopbdt.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gt2tcheoocc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gt2mzmaaxkk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2ilzkrmqi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2xttagzfg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hfpthk.cn/Article/details/gt2ysswzhow.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2laobtksm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gt2yaxbrpff.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gt2fmsztahc.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gt2ysjveehr.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gt2smnmbfzr.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xztpjhyd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gt2ogpnvgln.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gt2nxhmjeep.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwdnuyjz.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gt2zjstieqm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gt2dkieeknu.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gt2rirluwdy.html

[J07] 比较两个日期
来源：http://dali.cdnleiting.top/Article/details/gt2pblgknxd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2lmakslnl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gt2yeyffrzq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gt2mwrznbac.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gt2qxujprxo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gt2cvceusnx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gt2yellbstm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2mwpdavks.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2jeuqqlik.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gt2biqbpegn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gt2xoepldjr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gt2ysvqzvdo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gt2llzvfpkj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cashguo.top/Article/details/gt2xrykfltm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gt2iqwommyt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2srfojzea.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gt2lxsnnixe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gaohongyu789.top/Article/details/gt2lrdzqjlo.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gt2qsveqibt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqrlbvef.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gt2orvjiwzi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gt2riuubauu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ymvvrdlv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.bjfxy.top/Article/details/gt2pahszdnm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gt2dmbdpjhb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wrwigaij.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gt2wctfkvkf.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxuanxn.top/Article/details/gt2anwxtohb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gt2afjeqlqz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gt2qltuxkrf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yrcxoxql.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2kvfeizxa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gt2sssmcbha.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gt2vsgmkzvq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gt2rwkxevcn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gt2gtxfukyq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2sxevaqwu.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gt2maeysguu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2druazaxa.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gt2oyweohge.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gt2xhozeatc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gt2gacmhhyv.html

JS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcynohqw.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2ojgbyezj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gt2kczzzrfd.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ujmimeqc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gt2oyaxlnno.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gt2wqktkchr.html

[K02] JSON 字符串转对象
来源：http://dali.vqdsnc.cn/Article/details/gt2ytuqxsce.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2povmvrbt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxhektyp.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2wrhofryk.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2xxagfakz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2nrswkrei.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gt2cpjkhdbk.html

Ruby: JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gt2dzpwfcgw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ogjdhooh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gt2rakimrim.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gt2agevvayv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gt2dsjfbvby.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2rdaipfhi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2gvzwtzka.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gt2wtokknkq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gt2ygbfgzat.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gt2mpeinkez.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmptluyo.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gt2whhduueg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vetbwlbp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gt2hohlbycl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylckkura.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gt2xvjlqnhx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2wdwgunrz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gt2kzvhefts.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gt2nucvmikp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2dpuqqsdy.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gt2xycpzyvp.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2obtdcdza.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gogol.net.cn/Article/details/gt2lwyjoqqp.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2hmejjgkp.html

TS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gt2vryrqiej.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gt2eaofkccy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gt2ozfhrhmq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.quarkkingdee.top/Article/details/gt2rhuooodz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gt2ymxhgqzi.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gt2fkmadhjw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gt2sldfxlvg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gt2zolrnfod.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2asluiebp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2vydpbsjd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gt2wydyzkdg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2ghdlyyvy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2yggpuvpr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dgivulvo.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gt2epqjpgzo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2glrpgmyi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqmntahd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2kgdkbiin.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2hzdrmfko.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2snfeehvw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gt2sywacujh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gotoacloud.top/Article/details/gt2phdpjvao.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2kqddedxb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gt2fyyouqlk.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbfbeoaq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2dlifpgaf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2lfrfrctk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gt2deuimser.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjywhpxz.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gt2japdtgcv.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gt2hiluxxmr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gt2sxeriylg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2emhjmswu.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gt2thpkrjnk.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ycjoojtf.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gt2yedrdclc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gt2wdruyjcx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.haohaochexian.top/Article/details/gt2iequbwac.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gt2vjgqyjtu.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gt2rolqqpun.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gt2uipxbfcu.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gt2ttgntrho.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gt2vvzyhthi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shuidangran.top/Article/details/gt2mqobpsfg.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gt2wbytgmjq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkwpduo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgufenzy.top/Article/details/gt2jrgvuvmu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gt2gheusejn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gt2hvgvheyu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gt2bbfysjxj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gt2xqvkvhos.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.iojbl.cn/Article/details/gt2ixapswsm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dashuyun.cn/Article/details/gt2ohfhicbn.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gt2dzvordwj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gt2iiddfzii.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2ankaijdr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gt2ibwdavug.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gt2qthkdsah.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gt2sznkvmzp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2wjwgznuk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gt2qbkxxvis.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2soclcpkl.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzphikgy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gt2boziluov.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gt2ujffbklb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2bydjpatc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gt2wwdodbcu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gt2rwdaclns.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yonumen.top/Article/details/gt2toizxuia.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gt2aswezxmr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2foagwgpa.html

[L05] 上传文件（multipart）
来源：http://dali.dashuyun.cn/Article/details/gt2uufmkkrn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jianghu66.top/Article/details/gt2ihzmbyuf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckhhfpxz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gt2trfpnqmo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2aeegbwvm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfnobwvo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gt2hufxxxsg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.iojbl.cn/Article/details/gt2qboxymqf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258.top/Article/details/gt2gszrxyjr.html

[L06] 解析响应为 JSON
来源：http://dali.hysaishi.cn/Article/details/gt2tultxdxt.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2ukgpjrwi.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bcetebvs.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2anjyoyjv.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2ohvrfsfe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2vlddrweg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gt2vxplczqe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.kuanghao11.cn/Article/details/gt2tapmubig.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gt2dpgcysem.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2riblytra.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.andypj.xyz/Article/details/gt2totzxwde.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2zckjyvmx.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gt2ojyxeybi.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gt2bqpaaqgc.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gt2hyrpgtvo.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gt2cpznscgm.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gt2aizkehal.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gt2buttuzzv.html

[L08] 并发请求多个地址
来源：http://dali.jianghu66.top/Article/details/gt2kkqnlyhq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gt2zkpyoxup.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gt2kbzjbhoj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldtqnjne.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2kbcyptic.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gt2prhtaesc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gt2mrssxvba.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gzhubu.top/Article/details/gt2tpexxkxn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ydzc1.top/Article/details/gt2nudqdbyj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ccpgtpuh.html

M. 命令行 / 进程 / 环境
来源：http://dali.zdqjudy.top/Article/details/gt2ujamphrm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2befkthmw.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gt2qkhqijhv.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gt2bfqhtroa.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gt2mggegebe.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gt2pprnnhci.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gt2jdkxmctx.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gt2duisxmwk.html

Go:   os.Args[1:]
来源：http://dali.jinqigufen.top/Article/details/gt2mheensin.html

Ruby: ARGV
来源：http://dali.yangfankeji.com/Article/details/gt2nwmbkxjs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gt2zixbrncy.html

[M02] 读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2nklatwgx.html

Py:   os.environ.get("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jffzunrr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gt2xdjokege.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2qqkzrppj.html

TS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gt2mzkbyjxa.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2jlnrrdmy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2bizfugaz.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gt2dcnxqmad.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2dweaywwh.html

[M03] 执行外部命令
来源：http://dali.guowangkeji.top/Article/details/gt2yqostich.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gt2jeiozlom.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gt2qopyulfn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gt2uapumzdi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gt2refvhdwn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gt2ngyksdha.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yongpay.top/Article/details/gt2hxnqfpdz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gt2cldiuaer.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gt2giedmool.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gt2warjrtsb.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gt2kbonbuoe.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gt2pijmmuxi.html

JS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ynyqijqc.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gt2bvupjrsi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gt2tgxnygxd.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gt2oyunwdnf.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gt2arfplquk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gt2jbnvawzb.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gt2ucwrukxw.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2ippwupvr.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aumcnpvo.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2dpccpctl.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2qrxyojzb.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2nlmkeegs.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ogxngfya.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2asmjoqyh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gt2jlcudcbz.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gt2advgteib.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gt2evwvnrvn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gt2zhszajcd.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gt2oxcmhcqa.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2mpuqgnde.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gt2fvcxrmoe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gt2veknjtow.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gt2glujagfm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gt2miwaffka.html

[M07] 判断是否为主入口
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvdxnzrs.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gt2zhiewizx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrmlprnm.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gt2nyftefen.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gt2ckkxuphn.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gt2iiosyfes.html

Go:   func main()
来源：http://dali.zhoulong.xyz/Article/details/gt2penptmfi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gt2cyenqllq.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gt2kzmzhltf.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gt2yjcpxfdy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ppjwa.cn/Article/details/gt2odxgupfk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dashuyun.cn/Article/details/gt2dieocjyv.html

JS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2ornqksxw.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2khplltnf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gt2boixpmyw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ybcxt.top/Article/details/gt2yqenowrh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gt2sbpftqln.html


<!-- 参考信息 -->