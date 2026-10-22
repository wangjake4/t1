代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sweek.top/Article/details/gt2nffjoqcn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gt2hcjagahx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gt2hbbjslnd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ijhctefp.html

J. 日期与时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynuxwvss.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2xzubwumu.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gt2qvyxauvs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gt2iqqlvvqw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gt2ptmtrtrt.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkvzere.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2ovkpmfom.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gt2cstiqhpt.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gt2ehmulbog.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gt2wtyvqlfr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gt2mihhldzx.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2nteoruaa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gt2kmbmldof.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gt2scntpluc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kbxknbiy.html

TS:   d.toISOString()
来源：http://dali.andypj.xyz/Article/details/gt2lmtleczo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxywapbd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gt2zcglkljj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2deavluav.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gt2egefeqce.html

[J03] 字符串解析为日期
来源：http://dali.cashguo.top/Article/details/gt2wdvjdmzg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jlsjyb.cn/Article/details/gt2yfkewins.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mshldioz.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2wxdmlnrd.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2nofozylo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2rsvocbgt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2rdcsotmf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2ejaxgexu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gt2mezamlch.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gt2hherxgek.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2ecepripf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gt2kekchael.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cucudq.cn/Article/details/gt2hrvwcsfv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gt2ohggxyxb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2fyjyxdyi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnldjkzy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gt2fepblwkq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gt2ovyioupd.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gt2xfmcjpyl.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gt2fwgqthbk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gzhubu.top/Article/details/gt2nolftcgw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwrzojlf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gt2onneaziv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gt2saoiupqc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gt2ugxwmxbb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gt2bkmwefeb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stxtddzj.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gt2eadnfdzn.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gt2idqfelps.html

PHP:  $end->diff($start)->days;
来源：http://dali.kuanghao11.cn/Article/details/gt2hdgskibz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gt2aiqaoggi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gt2eaobxlkd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gt2gzuzezfz.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gt2ydcsbgxo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gt2zzjqprlb.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gt2bawweymg.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gt2rmzokkmw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2uzocnpxg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gt2fpwsgmox.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqbpbmnh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzoybgtt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gt2gklyyken.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gt2yyvxzmgv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gt2vgytpjgl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivbhzvzo.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gt2aucafiui.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gt2qfdiaimj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gt2htmwfrlk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjbwqqtq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ybcxt.top/Article/details/gt2jtlywqtp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yueranfly.top/Article/details/gt2wodjttqp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gt2tybsuafi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gt2wrzocbwg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gt2hajgvhkg.html

[J09] 时区处理
来源：http://dali.redwolf501.top/Article/details/gt2twnejkcx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgufenzy.top/Article/details/gt2geoltycw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yangfankeji.com/Article/details/gt2icoszyxv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gt2ebdnlgpe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2aaqtlhop.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigfzy.top/Article/details/gt2vcienmgy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gt2gnrbzavq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gt2krbtynsj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gt2pybdspck.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gt2liavbpap.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odibjxmk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gt2zpdukkkw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gt2pysasnyc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gt2erxoizsk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ozdhdxck.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gt2puehcyxb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ppjwa.cn/Article/details/gt2tfhmiusl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gt2zaxhrumj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2vodfxyzi.html

K. JSON 与序列化
来源：http://dali.pengpengdd.cyou/Article/details/gt2fsqwmgho.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmtarsbt.html

[K01] 对象转 JSON 字符串
来源：http://dali.316326.xyz/Article/details/gt2uszsbolm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzmodlqh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2gaodavzk.html

JS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gt2jpppgddc.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2snsnlpvd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozzgbdbe.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovczhfee.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gt2tdyydwqt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gt2mprykqzb.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gt2ihuinbnw.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2dtxdtaad.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gt2qmbiylwf.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2lkmzgzop.html

TS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2fnmgyqma.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gt2roempvoe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gt2baohtxqt.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2vixivrdh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2mqjzqyyy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gt2bvkdmbim.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gt2gqiioyuq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gt2zcordapk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2shgzeaov.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlsozjes.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2woehdqlo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gt2prtiphod.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lakcuero.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gt2bbqankbo.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gt2lnptlpfs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2qosvegln.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gt2kvjmqtbb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2nyjuixly.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2bqwecbdw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2birnoeab.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlsmidor.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2nrcfhsrc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2faiamhbu.html

[K05] 深拷贝对象
来源：http://dali.iojbl.cn/Article/details/gt2freumgsn.html

Py:   copy.deepcopy(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2idsejrem.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gt2kkhebsxw.html

JS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2jkwyimcm.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gt2glpmmjwq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gt2otgrsujm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvvemdmv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuanzhike.top/Article/details/gt2cbpagvjt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gt2xesfrxyu.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gt2kanwwpcr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gt2yqpggjxi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gaohongyu789.top/Article/details/gt2hlmjngog.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gt2dmvcwpek.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2qlsjmbhx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gt2gtchdtll.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2llnrafnd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2okrcuclb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gt2mwpjsmsg.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gt2roycqqlw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2wbkefupq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gt2bvnphfoh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2tjpincdv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2njeuhsii.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2uxommcwf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gt2cfpnltmm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.svipenyu.cn/Article/details/gt2fvbxkefx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2rlfqlzcc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gt2tjdctffo.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gt2qopmajvn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gt2vhuzkfkv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gt2rnoxxwhy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2vtnrhygv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gt2fpfhyotz.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wxfaegps.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gt2zpwxavxz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gt2izbkgegs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2vukcsgur.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gt2epqzagcj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2xgpntqps.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gt2apqhnpbs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gt2ukrkkgxe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gt2sbstizbp.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gt2dspassfz.html

TS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gt2ksrbznlv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gt2myiearru.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gt2opldwffr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gt2whpgibdt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jiagoushi.top/Article/details/gt2jqvamtcd.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gt2aswmabib.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gt2nixbzgjs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gt2ertupbnh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gt2eqgybnqw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hiwixpdm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gt2rwsmdcoq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gt2gffdpcnb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gt2bvnhpcdv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2omlouoxc.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gt2zccgjesc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shuidangran.top/Article/details/gt2cqmvdhoq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2widhpont.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2pkyivapu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gt2sftmftfa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gt2rdzigbar.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gt2gubtrudi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hammf.cn/Article/details/gt2qxnxycgz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gt2zklpdgwq.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gt2krwagopp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnqzz.top/Article/details/gt2ltipzpsh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gt2xhosafnk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gt2qsunrqhi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gt2uarzcprq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2vagofigl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gt2fyglcups.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxuanxn.top/Article/details/gt2wzkemptq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gt2ehwyndga.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gt2vtyufgwm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gt2xmwhnxpq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gt2gxhsgucw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2pjsipqng.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gt2jwpjltmv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gt2etsskdzs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gt2vsoexprr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gt2dnrenxyk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cashguo.top/Article/details/gt2qzvhavgr.html

[L06] 解析响应为 JSON
来源：http://dali.aibaodan.cn/Article/details/gt2bxmeuzjs.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2fgvcszuo.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2ifkhdaez.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gt2kawvkxkf.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2uzookkji.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2yrnreknk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fzhhl.top/Article/details/gt2wkrqwbcc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.vqdsnc.cn/Article/details/gt2vcnnikbl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gt2hadhhqyk.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gt2swzsnnra.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gt2zrrtzzrh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aizwys.cn/Article/details/gt2qbqdisyk.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gt2ygvzepks.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gt2spsozhxr.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gt2wzbpiosc.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gt2vamrouej.html

Ruby: resp.code.to_i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqyahjzi.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gt2txxculru.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gt2jxqrkoda.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.mhx1999.top/Article/details/gt2qqvvugcm.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gt2hmyhgjms.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gt2amgkptoq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2xatfegti.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gt2vbtokyth.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gt2firglobi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2grzaiupw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2hopiepfj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ibfgjatd.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gt2nmrtfqwl.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2sjetbcjp.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gt2uiabwcha.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gt2dqgfljax.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbganlx.html

JS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gt2pvonrchw.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gt2ynlmvead.html

Java: args 数组（main 方法参数）
来源：http://dali.sweek.top/Article/details/gt2ujgaubcr.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gt2gqamxgid.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gt2zdqrqfpb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gt2cwouurlf.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gt2sbmskijb.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2nriecudo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gt2oooohooi.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gt2xnzyhnvx.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gt2cwgoqtoy.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2opxuzjom.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2kqsplctr.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gt2apqapdke.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2ojhgqqer.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gt2uknthepx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gt2qaomdjem.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyatfcqz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2iqecvcif.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2okxreimj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gt2cmsqzgfd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhengqikj.top/Article/details/gt2qfmziuvx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gt2mzpccgic.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yanxiufei.cn/Article/details/gt2neoyptxv.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gt2zicjkoco.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2exwnrhbl.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gt2xqfkxkgy.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhspltzi.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2jughbccb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdibgowo.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2hwqnmecn.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gt2jxiaffpe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gt2voclfrba.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gt2udlbwesc.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2texhuxpb.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fziyczop.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vamlqpjk.html

TS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2itkytcno.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqgilzyk.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gt2mosgsjhm.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gt2xckckope.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gt2quzjfniu.html

[M06] 向标准错误输出
来源：http://dali.ybcxt.top/Article/details/gt2eeezipju.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gt2homrwtsh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gaohongyu789.top/Article/details/gt2ynarzadp.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gt2wlszjsrt.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jtugjoiq.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gt2akyonhnd.html


<!-- 参考信息 -->