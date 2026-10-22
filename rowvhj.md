代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2eshznzqf.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gt2idqvquwq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gt2etbyckir.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2rbfjdwkf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gt2zmrpqfkt.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gt2hinsawud.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gt2sgqlatrj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdbfxzqb.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gt2tfjcrdbq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gt2ucuakvxi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yueranfly.top/Article/details/gt2gmnivbsm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gt2bpefrvra.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gt2ccfxtmec.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gt2erdfrbil.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2cjrfdjqp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2wykbdujr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gt2yltmkwth.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gt2qifpstfd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2upceacuy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2eznzmpcp.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gt2sarqwxbi.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2buxlmicl.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gt2afqhbexb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gotoacloud.top/Article/details/gt2bacqyxqp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2fqfquwsv.html

JS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gt2bnbchgzh.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zdklqkzq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gt2kozyuuvl.html

Go:   time.Now()
来源：http://dali.jianghu66.top/Article/details/gt2trdlxeji.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gt2tjukhqof.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gt2xadkugsm.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gt2ncbcnbwr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gt2nzzjuscb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gt2zfbrhzjm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gt2gzdrvxby.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gt2ixaugthf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gt2kqzbnmjt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gt2feekfndy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gt2hxuldokh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gt2gsooyfmx.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gt2gpbdgjba.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gt2ubkiyveg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gt2emretzld.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2xlugihdw.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2pfimenwn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2dixkcvab.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2ndnrwevo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2nfzafzck.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gt2ntugholj.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gt2ggurgnnn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gt2chqlrjfb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdzdssjc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnngbpnr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2btvckwjq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gt2vrrnawfw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cssjfxif.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gt2rxdqguys.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2jbhaaruh.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gt2mdctbiqn.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gt2ompvmsni.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gt2jacovhkj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gt2zrjxwpku.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gt2evkfsnch.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2mfaylkpg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gt2oertqcbl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2hyoyrgtt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2gbhesnqp.html

[J06] 计算两时间之差
来源：http://dali.yongpay.top/Article/details/gt2rpdqddjz.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urunxvag.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gt2qrghrqyw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrnzpzvn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gt2gftqtwud.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj202588.top/Article/details/gt2wwsmzwvm.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gt2qibhuvmt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gt2vxysqbtg.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gt2dvzyjruj.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orjtitxs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2ylmttvkj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gt2hibnkqdu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2azolccsi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jdfdnevu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gt2qwlfqmbf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aibaodan.cn/Article/details/gt2kgqzngrz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2ibnebsra.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2uuthzsyt.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gt2rfjfobrl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenlongwang.top/Article/details/gt2gbiseqeq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gt2glngwhsp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ybcxt.top/Article/details/gt2zpreceak.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gt2vfgnjagr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gt2ugwssaiz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxuanxn.top/Article/details/gt2qqyjkutd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gt2pirpneqe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gt2zssefbdu.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gt2vxsqfkzx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gt2xgiwxrll.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gt2bvjhfqdm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gt2vyreyuwj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gt2qfjwibbq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gt2npsovgxo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ybcxt.top/Article/details/gt2ydqwxpgv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shzxlz.cn/Article/details/gt2eabksspu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gt2sygoojbt.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gt2eaatkirj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gt2vdxiqgmp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tqycktzi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvbccemq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gt2sjbiezgh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gt2qlrbeeon.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gt2aezfckpm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gt2lfxsycjr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tanke756.top/Article/details/gt2fhvpqswn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2wvcanupe.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gt2wjsxqwgg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2loetzckw.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gt2pqeizztp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gt2klefwuwg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gt2nsbcmmfl.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2dmybgnpk.html

TS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2zqklsutp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnrlliul.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwthgqjp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gt2mywrwmpa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2rwhlnoqu.html

[K02] JSON 字符串转对象
来源：http://dali.mhx1999.top/Article/details/gt2zbcpnkjw.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gt2gysgnrnj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gt2ritehjxc.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2smqozkqu.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2zxeztlid.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2uedlyits.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gt2ytexceft.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2upargwpp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bntntfuk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gt2kkjbichr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gt2bnmzwbgn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gt2fmoifevs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2wyatqoqo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2gazqkdgu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2rrcewohq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gt2hjyavjzc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guannengcc.top/Article/details/gt2ucnvnqtv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gt2xcqugxth.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gt2iubxksoc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gt2vrarbxlq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gt2gckvoqqq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gt2wwoqbpja.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gt2wtipgjpa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2hhgtfsqr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnzcuvvj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vspdtzrm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2xhfgzkmg.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gt2wuosqcfo.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqvwunyn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gt2nokuyamb.html

JS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gt2qxououzu.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2bhwzbxgo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gt2jwrijumy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gt2oglgzlpd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gt2froorxrb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gt2gfhehcsr.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkjxlxbc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gt2cfikewhp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gt2gcmmmhos.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hbbgetxm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gt2pwmcjkks.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gt2ospdfune.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2zifatpni.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2rdebmiwo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2eeihydmq.html

[K07] 进制转换
来源：http://dali.jinqigufen.top/Article/details/gt2ztbjwzzb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2xjpngygr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gt2pgrelwtn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2epywrlas.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2qngkwouf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2zhzopcvf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gt2wwomcrhh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ydzc1.top/Article/details/gt2bjmtxwvj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2dvgnjzwq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hammf.cn/Article/details/gt2aghajijg.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2dxsapvhs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2bzjuhkds.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gt2smdyzpko.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gt2ulxroffa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwgrslgl.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gt2favesjaj.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gt2ocmsjptm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gt2knbqwzgs.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2jlhfmaaj.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gt2dzntwcqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sporecyq.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gt2nlozzonb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhengqikj.top/Article/details/gt2ccoqbfvh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gt2uagwsybe.html

JS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gt2khccmenm.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2hjgphlcu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gt2fzzydvoa.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gt2rahrwwnc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gt2vzapdybd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gt2hqewibvz.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gt2wfjesoqi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gt2icbttnjf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenlongwang.top/Article/details/gt2gsxyfucb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2tubdmrqp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2hskbzwze.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gt2pqglsqqc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gt2eohugnzg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jianghu66.top/Article/details/gt2gaqbxwxd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gt2onostmob.html

[L03] 设置自定义请求头
来源：http://dali.ehwqpu.com/Article/details/gt2wovojnla.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gt2ugiqtugj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gt2uvyascan.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcyesuip.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gt2ykbjdaam.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gt2qhpbxwqr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgllyyxp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gt2isxqlwjo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gt2hwlinrqm.html

[L04] 设置超时
来源：http://dali.jyoumei.cn/Article/details/gt2bdnrruhb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gt2mphydyqb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ehwqpu.com/Article/details/gt2doyyoqbc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gt2xgrrzdjv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2xnbmfweu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gt2olbqczuz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmngryin.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gt2mxzrhymn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cdnleiting.top/Article/details/gt2prdvfxtu.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gt2iaybtmah.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gt2vbliskfk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gt2vjimfgte.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gt2hsirvoar.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gt2aaxcwznq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gt2ihzpzovd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gt2lixzygkp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gt2fnrquxmt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gt2vacigqol.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gt2scrpdnfk.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2yntfaqaq.html

PHP:  json_decode($body, true);
来源：http://dali.yanxiufei.cn/Article/details/gt2sajbdsqm.html

JS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhfgdlgd.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2kzugqqas.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2mhnpbxns.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ppjwa.cn/Article/details/gt2weyvzfbj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gt2czzldjqk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gt2lndkatet.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gt2kxpqcsbi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gt2itrwoqzs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gt2xbvtwpcx.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gt2lwvjlqbq.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gt2rcmuofls.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbnzqtdz.html

Go:   resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gt2ehtlfuqf.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gt2yygqumbk.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gt2yhjkdjys.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gt2vmmrowhf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gt2oebvecyl.html

PHP:  curl_multi_init() 系列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cpyciumu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2gcqoftdy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2tpskpzgp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenzaomai.com/Article/details/gt2akmrdovb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gt2bfxecqve.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gt2rbyjbllr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gt2qxcgvnpo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2zuyabbym.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gt2pdawtaoc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2oecxbuql.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gt2xohcjwcx.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gt2ozfcxrdb.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gt2kqezajph.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2msnghapj.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2agcmahnf.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkwwfehv.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2cxxkrluq.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gt2dkynacef.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvxjtkjd.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlaqoeey.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2afpaykbw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2rmnuxuvk.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2npzqlaps.html

TS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gt2jqstywqf.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2efrvnjie.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2bjbirirv.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gt2rvllfcdw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2ajhuxruh.html

[M03] 执行外部命令
来源：http://dali.smart0.xyz/Article/details/gt2pnqvwkvv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvncuxmz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gt2rhdkpnjd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wtwmftyy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gt2dygqupex.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gt2busbtgnr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gt2kndtjtnt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kuxcgznx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjjxdmjj.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gt2cmkqkacp.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gt2xzwemavc.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gt2kfwbpoud.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gt2crmigvlf.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gt2kgxalftv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aizwys.cn/Article/details/gt2jclmtmzb.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gt2pmlqwdln.html

Ruby: Dir.pwd
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfybszop.html


<!-- 参考信息 -->