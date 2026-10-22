代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2mujvziaz.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gt2vbwpyhlh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gt2nrvuldzq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2ofzenqjc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gt2veexjucn.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gt2uiuhvpcc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigfzy.top/Article/details/gt2bysdlctb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gt2grilyfxc.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gt2emyrxoip.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gt2hjalsaqi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2ijodkhxe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gt2mdnxrhfa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2gczdmukn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qckknjfi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uubyoldw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gt2ekybgsjx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gt2ibhpgbqg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gt2fepttprz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2tamzlgmk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjxgnxya.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gt2lyrwyvlu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wlbkhvfq.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gt2xmorfcew.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gt2flzelkwl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2ahjundif.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2yewjulyh.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2rztxhics.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gt2vakhkgvr.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gt2qwzfanqp.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gt2zharqtpg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gt2bjdtghxr.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yetxlglh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pfimbuzy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjyvmwgs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gt2sylapxpx.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gt2wllqangw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gt2gxsfhtwe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gt2xjdgcdre.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gt2cvldgpzo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gt2fbsfflrh.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gt2xxncvyan.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guowangkeji.top/Article/details/gt2wrwlmwvf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gt2ynuyyfag.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2ricedvam.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2noqfdqgv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2jtmgbzkx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2klctzadj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2oifitmld.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxuanxn.top/Article/details/gt2iotissac.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gt2hxxvkxpe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cashguo.top/Article/details/gt2fznvivkt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvybsfhb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gt2ncgkjpki.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gt2cdqupeob.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gt2ppjtddjp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xfgjprpc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zycfv.cn/Article/details/gt2dmlveost.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwglxbvn.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gt2qadrhctu.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gt2hfpnutzs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gt2wqomcnfa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gt2tmfbfzal.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2uycbiegd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gt2polvfejh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gt2rsgdflnx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gt2uihkpmdk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gt2prhtblah.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gt2lcstjole.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gt2czvyopud.html

PHP:  $end->diff($start)->days;
来源：http://dali.iojbl.cn/Article/details/gt2zquhfeck.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxuanxn.top/Article/details/gt2auxtcyzy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmzsjnky.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sweek.top/Article/details/gt2iunahend.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenlongwang.top/Article/details/gt2yrgllvtl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.meibo888.top/Article/details/gt2atheaoic.html

C#:   (end - start).TotalSeconds
来源：http://dali.aibaodan.cn/Article/details/gt2gxmwekhd.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gt2crtsnduf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2fqfihmtd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gt2xbyogeuu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gt2rvzsabro.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gt2jscyuodk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gt2dghgvtkg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwxtotak.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2aelyedmu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2wkwaahyh.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gt2cmsmiqvt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gt2lzjhimlg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2noeolylh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gt2hfpqzrkg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gt2etiwnpih.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gt2urzvzxgm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gt2dmbggngo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gt2jjgqnqno.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gt2sltjasye.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gt2dpxqqiva.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gt2uwconixl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gt2ptpubpnv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2ovimhwiw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gt2tbenpycp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gt2eutqrvum.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gt2deyilkih.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gt2ltevqirt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xylfe.cn/Article/details/gt2erzcuwss.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmjcxrxv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gt2icepqxes.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urqatguy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gt2mqlftlxy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2ryqmhmbn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gt2somcenkf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nwbrower.top/Article/details/gt2mppqrfhn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cucudq.cn/Article/details/gt2wtwkcupo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gt2ibycycmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwieuciz.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqvwvjhw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2eqrpblgv.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gt2uxliqxuc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujhdkoon.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gt2moueundl.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2fltnrvbo.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2lnanuxyg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ehwqpu.com/Article/details/gt2rsmksukn.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2dcthgksr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gt2hzljdnrg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2kxstylaa.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xajgpzmk.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2nrnyzecq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.meibo888.top/Article/details/gt2iwgkzlzd.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2frnvpotv.html

TS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2dyptqbij.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gt2vedsqhij.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gt2uuzcdcsd.html

Ruby: JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2jrkexdln.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gt2oadnxsgt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gt2xeckcqnh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gt2sfchfuuc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gt2zsihwico.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2ejnuunew.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2jdedxzfx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gt2zfxkaykp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iydamcwx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gt2ehnyjrri.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubzxveia.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gt2llmhedef.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gt2uqbpwuxy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gt2qbviupaa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gt2xjyatypi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gt2aumawvqn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2cdjlvgmb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2glxuimiz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gt2ajxjttns.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2kjuoswqj.html

[K05] 深拷贝对象
来源：http://dali.hfpthk.cn/Article/details/gt2kfnfbfzr.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gt2colmmcjo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gt2wihrkycw.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gt2xnesuxab.html

TS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnubaoel.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gt2jeijpyfb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gt2khwowxcz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.havefunace.top/Article/details/gt2psngqhus.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqjgsetu.html

[K06] 解析 URL 查询串
来源：http://dali.jlsjyb.cn/Article/details/gt2vdtdbmbc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gt2sabdxoby.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iebyokut.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2wpvuogpp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gt2wtimhkec.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gt2ovhngtts.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2khaupmbc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2qzxbgxtk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2klfwjzxl.html

[K07] 进制转换
来源：http://dali.pycfn.com/Article/details/gt2cztoftye.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2qkctinvz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pycfn.com/Article/details/gt2lykfgmjo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2afmpspjb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxcjfddy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2hgljtqyz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gt2xbwymlvx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjfrzcvw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2kheakzdc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gt2xhfnvrfw.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gt2nqdbrpdf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gt2tjasmhpj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gt2swsdlbgf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2sohpdhhs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gt2bzihrfox.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnfhmawi.html

Ruby: Marshal.dump(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2clihqxpl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzhbdytq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bwhxjmcu.html

L. 网络请求
来源：http://dali.hysaishi.cn/Article/details/gt2xhsegeuq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2pkjbyozs.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gt2lpsxsfcy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gaohongyu789.top/Article/details/gt2rjbxuvdf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gt2aswkkraj.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gt2mjrddpqb.html

TS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gt2dzgqncuh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gt2xkedossp.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gt2qmlcxhyh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gt2ihkbdtxu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gt2gesisraf.html

[L02] 发送 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gt2icujdsol.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gt2trphvjrx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gt2yervbwyt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gt2cdimwqtv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gt2wfqzscvs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fghosvee.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gt2uzxybyvl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmdtinkv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gt2mzyqcryy.html

[L03] 设置自定义请求头
来源：http://dali.zhengqikj.top/Article/details/gt2ijxssjjz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tanke756.top/Article/details/gt2jgihvqpn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hywenlv.cn/Article/details/gt2gwvikmsi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gt2tczmjypr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gt2wktwyhsb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gt2vozjhrwf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gt2qowrnxvr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gt2smmmeozt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gt2rrkvwmeq.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gt2knccmzjc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlkgrcxz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxxrojbi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gt2uesmrzup.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gt2xuwawzbm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gt2nengubrt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gt2oiyeiqcs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2yizfrgur.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gt2eauuzpma.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gt2iyqvtlwh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gt2apqjtvrz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gt2ggpaulyo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gt2usxpuaoy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gt2upfnyhsy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gt2bplavtzo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmihauo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gt2njnmcikr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2pihauyew.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gt2jwocfioz.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gt2duuzqvrx.html

PHP:  json_decode($body, true);
来源：http://dali.cqqwz.cn/Article/details/gt2vzojdroa.html

JS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2lwfmsrkh.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2xfvwxwrh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2omqnjzwm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gt2tzgqjbip.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hsikxwto.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gt2lmcypuig.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gt2ppezipiw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gotoacloud.top/Article/details/gt2yslmlmuq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yanxiufei.cn/Article/details/gt2cdgmoxkb.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2nirxzhpa.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gt2bosesxrv.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gt2ubqiiiow.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gt2lijvvixp.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gt2bqkxkvpc.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gt2lhzzpiox.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gt2wirkqnpj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gt2oqpiyfsc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gt2sabbecqd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gt2aazutzbm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2dtprezuu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gt2pbpqnbfr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gt2vjvoclfm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ouvbecns.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qulkoupt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2fnretssi.html

M. 命令行 / 进程 / 环境
来源：http://dali.yongpay.top/Article/details/gt2gagblrqc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2fngxxobv.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gt2rpwryijy.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2geodgmsl.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2katscvwg.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2ydmiwypq.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gt2dgyoveod.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2obxftzmi.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2zpdxnfns.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gt2gylcpciw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gt2mdbpzfzq.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2foqispas.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2viikoyig.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gt2fujpgllv.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gt2oipsnulv.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gt2bbqioysx.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2dsbeqowm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2aqmymvkh.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gt2cxngbvud.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfssonzw.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gt2dcqtalzs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2saxrigqp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gt2fqwowgvc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzxcxhwn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gt2ilvylxiz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gt2fjwcuzzo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gt2bimfnjne.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gt2flrhcegx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gt2bzrotivk.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gt2wtxcmcjt.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2sjcrozqg.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gt2khpjeebs.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gt2bwavtnrn.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2kaqhitwr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gt2pewopwsa.html

Go:   os.Getwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2omyddgor.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gt2qikunpnl.html


<!-- 参考信息 -->