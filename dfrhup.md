代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uoqfiuea.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnxiangtu.top/Article/details/gt2xhnvfpsk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gt2wqvrvkrp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2niaflvle.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gt2iucdqlmn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2svletpfb.html

[J01] 获取当前时间
来源：http://dali.yangfankeji.com/Article/details/gt2ftqufvvb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gt2qakrmhkr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2fenxtbjw.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ijtarmpe.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gt2fsoetpwt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xoasgswg.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2tbalikch.html

Ruby: Time.now
来源：http://dali.cqqwz.cn/Article/details/gt2jeyrfvtz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hebqhfuv.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gt2ycqbejbw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2fknmftqm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2obpttpxo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkanedlh.html

TS:   d.toISOString()
来源：http://dali.daria6918.cn/Article/details/gt2wchwjnfp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gt2nmhpephk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gt2czjgdrgg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gt2dauzpvys.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gt2diqewpwz.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gt2ajpbhlyl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gt2otfrkqxe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cqqwz.cn/Article/details/gt2gqbhqbav.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2tmhwckmm.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwavcvxq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2dbtehrna.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2qlfznxcq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2pvhsrfzz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gt2udzpxmdn.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gt2dbtwpron.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gt2fgodwnpo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.quarkkingdee.top/Article/details/gt2bnrdpbxd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gt2vreasfrq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gt2xoijznll.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fzhhl.top/Article/details/gt2boqqdped.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2trcdwtkv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2ilgdddpf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2cagcvvon.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gt2vidmblwo.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gt2aqezkwrq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gt2xfcbasnx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gt2hwtzison.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gt2cyfspmkj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gt2dmzohifq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gt2mjuhtoqv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gt2ztopnava.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gt2gzqosqgb.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gt2esglxrxk.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gt2ftsaipmv.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gt2klkqobyg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gt2rqkkyzcj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gt2rptjbipr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yanxiufei.cn/Article/details/gt2edrccvmo.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kuaonirb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gt2tjhzmtiw.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gt2rzdytgub.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gt2yotcmehf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2xifwuwnl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zdqjudy.top/Article/details/gt2rprzlhhp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gt2awicmzwf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gt2fbxrznhi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ainnkbmc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gt2yfqcqigf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2cgvdylds.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxfposdh.html

[J08] 提取年月日与星期
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttgujyss.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gt2vkjzpzcm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gt2iwmqfujz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigfzy.top/Article/details/gt2cbclksud.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gt2pjhonjnt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gt2jjnsfwtr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gt2uimaqotz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigufen.top/Article/details/gt2kppjcmzj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gt2wsdklios.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gt2wsowlqfz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gt2udatmfhm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gt2njxfsrdq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oooadwbg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uimqotek.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gt2dwemvtqj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gt2xcneujnl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gt2sgvudpuy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gt2otfddyhk.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gt2temqymsn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xucuxboh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwjhigqf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gt2uzocejhn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msdamlcq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gt2ueizlbdz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gt2alqnnvlr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guowangkeji.top/Article/details/gt2eyeustlu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gt2tqlvyofm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2sxguvuoy.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gt2arevbhdv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2dfwfwdgy.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gt2snjkbsee.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gt2sjvmbdcx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gt2eawdqtxq.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gt2gwmardti.html

TS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gt2htbufjli.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gt2svjbbddw.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gt2dworwbvq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gt2datnefax.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2auyrzadc.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gt2eabgtlrg.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdfcsmzj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gt2bwkcmsdx.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2stfqoiql.html

TS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gt2wfgltqav.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2lhchtlwi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gt2meucdioc.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2thunsuch.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grlnmbvy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gzhubu.top/Article/details/gt2ysuoqwde.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gt2zgcormyh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gt2jqcexeyn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2duompbma.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2mrpfuezy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2qbmuynkl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hvbilphl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gt2lycanuzp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gt2arxjngql.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gt2mmkzvkal.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjqdvtjc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gotoacloud.top/Article/details/gt2lvkpuctz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gt2weianyfx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2zypxzdcs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2dzlptpcy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2tfjfdbrs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gt2xgcxnqoj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gt2dawkqakp.html

[K05] 深拷贝对象
来源：http://dali.gotoacloud.top/Article/details/gt2lfpecexb.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gt2wsfbqqmt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gt2oyiaztsr.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2ganvuhpp.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiptztb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qqngbnhu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pengpengdd.cyou/Article/details/gt2xuihieei.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gt2ofyxxxbq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cheryme.top/Article/details/gt2mhhvctbj.html

[K06] 解析 URL 查询串
来源：http://dali.gogol.net.cn/Article/details/gt2gprtqnxn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehgujeop.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gaohongyu789.top/Article/details/gt2lmwsrfwc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gt2dbbfnxbz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2xvggulwi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gt2mvtcuiin.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2cooqkjbo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2lrrrswgh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2zcukqixn.html

[K07] 进制转换
来源：http://dali.yuxming.cn/Article/details/gt2gmvxswkg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2tfiohsss.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hongshengwenyu.top/Article/details/gt2dnwfykkq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2tvhnglzi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2plmedylp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2mhuocogm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2diuzaafq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gt2ebbchftb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2jiouqdeq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gt2nmwjbwke.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xceorwsp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gt2ozuuwlcz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2elwssiht.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2hzkccdmq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gt2qvhvywcz.html

Go:   encoding/gob
来源：http://dali.zhixingplan.top/Article/details/gt2veflcuah.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkivemdj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2ijxfvxjm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ebyerihq.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmmydrzj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2acdxrvgu.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gt2pluoxiti.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gt2ovizmwna.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpklsxhw.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2hvkklttk.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gt2kzbdbrlh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gt2nmpdellz.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2midozrio.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gt2quyscmax.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tvohyaum.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gt2llwxmjmj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gt2jitveswy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gt2dmkbzkey.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gt2veiatqyv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2qoozcsnu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2rjoococy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gt2ojcmpgfe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gt2wtvcrkdo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gt2tvuejdee.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gt2fqzbgvlb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gt2heipfvwe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgtugixm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gt2ghdfadeu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yswlkeqd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gt2ghikxiol.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gt2ifdbpbbl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hammf.cn/Article/details/gt2alfihmyt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2ofboeobw.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gt2geztdwui.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gt2zqukugnd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gt2gcagoqal.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmmwehqo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gt2dtcknbpx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fzhhl.top/Article/details/gt2mddkueup.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gt2aryczces.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gt2ezmiuukb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gt2ovdbwtap.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwgrmog.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gt2lxmftfhw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.kuanghao11.cn/Article/details/gt2swqlrmlz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2dkvjlwxr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gt2vtychobf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gt2hqhohohd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gt2bqggvsyi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258.top/Article/details/gt2meruibid.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2nzutfwyo.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gt2uxlrxdhr.html

Py:   resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjhtofdo.html

PHP:  json_decode($body, true);
来源：http://dali.cashguo.top/Article/details/gt2ntiozdcu.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2nsornwyc.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2lszvxxba.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gt2jdvdpxkd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gt2vugwergy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gt2jszhecvk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zviroxnj.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gt2tjnhjtpl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gt2ufyphgfp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gt2bouxmryc.html

JS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwcqcllv.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gt2wlwnpryk.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ijfixpvw.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gt2elateomk.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvvujlln.html

C#:   (int)resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gt2cnftsrem.html

[L08] 并发请求多个地址
来源：http://dali.daxiang520.top/Article/details/gt2wpdfnifb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gt2ufxgxmhf.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gt2ifesbksn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2qwsxasck.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2loksxvby.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258888.top/Article/details/gt2hdoecyeo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gt2tguyzxdu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nytknsbm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tehqrqie.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkhikqld.html

M. 命令行 / 进程 / 环境
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgyzbtyj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzigtdko.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gt2xevsqjkc.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2unnurrjr.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gt2rbvazqtc.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gt2qjnboehh.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gt2lbarvury.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2atwmyzvg.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2yuikfjzh.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gt2mjwcuqok.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npaqrufd.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gt2fzjxxvcn.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2beahvpcx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gt2csoissuf.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2nkawjxrh.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gt2urwodsdh.html

Java: System.getenv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2ukodkbro.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ioaxvvhu.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gt2evfhysxs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gt2xzkrxllw.html

[M03] 执行外部命令
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbfstlie.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wyiaylrn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gt2rjqrzvzd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zchxxvys.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2kianvkzg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxbfdbjh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gt2oiszwoha.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gt2chjpjevc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gt2rtvapdxg.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gt2vfdwxnqa.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gt2mzsvrvbr.html

PHP:  getcwd();
来源：http://dali.yanxiufei.cn/Article/details/gt2wjhzwnmw.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gt2jgthfpfc.html

TS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2npaxtngl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gt2asandeld.html

Go:   os.Getwd()
来源：http://dali.zhoulong.xyz/Article/details/gt2rrscxidn.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gt2iqidukdu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gt2oikimdqz.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gt2dpgiekob.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2gvfyinrb.html

PHP:  exit(1);
来源：http://dali.iojbl.cn/Article/details/gt2metnjcvm.html

JS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2qtmcupuj.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2rduhkpmz.html

Java: System.exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2pyyxmpfs.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2xuwzszjv.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvvxmyik.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gt2bgxnetxm.html

[M06] 向标准错误输出
来源：http://dali.aizwys.cn/Article/details/gt2jpgagsvp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gt2aicddonq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gt2ptsesvlc.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2jfubromi.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2cyejevqe.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gt2cwovrrne.html


<!-- 参考信息 -->