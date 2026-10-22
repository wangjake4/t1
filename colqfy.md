代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gt2ddcugjtn.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gt2zyarmgll.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.iojbl.cn/Article/details/gt2csnyjlhe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqpbcctw.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjtykxvf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenzaomai.com/Article/details/gt2xutzrjgl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gt2bnejbynh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gt2odiomwte.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2uhqwpsih.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2tpmtfpjf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqnhuqdk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gt2xtlebygo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gt2votqafjh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gt2mlvamshv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gt2rkkdpiwz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2bekbgacn.html

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gt2rbfliqbk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2csatmeks.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gt2ofuhbkkn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gt2dbfsxqsu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gt2lpamcvgk.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2kquuwrrc.html

TS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gt2zgqypvpd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2ikqfybzz.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kenzpxfg.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gt2jlrjqitx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gt2qovrwjsi.html

[J02] 格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gt2rsmkhbqh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gt2rrzamzyc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gt2xhtsqoac.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tekikasd.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gt2rckwafyg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gt2teumkhwu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gt2mwtkkngi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gt2gjvulfer.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxinkj.top/Article/details/gt2fqrkvgfs.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtcbledg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gt2csarwldm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gotoacloud.top/Article/details/gt2nkmiyljo.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2oydbfmfo.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2nvxtdjfp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2zqoigihs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2widkcuxy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2xxrwpwei.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gt2fascjlyp.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gt2eejhspvk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gt2qfvqvcue.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gt2drmwbhnu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgfzy.top/Article/details/gt2twqypzjm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2nnjddnsi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2neszwpxc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gt2vfoenrut.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tanke756.top/Article/details/gt2mtzzndso.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2tsckyrvz.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gt2vwmkeush.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gt2nzblzawy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gt2ibndxrbd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gt2lnidowfz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gt2qaxljroe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gt2hadvrlfg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hysaishi.cn/Article/details/gt2egvdjctx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gt2szdapsax.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.316326.xyz/Article/details/gt2ierwngla.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gt2wxqewvfq.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gt2zrhpuswh.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gt2lbhmgrdf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tanke756.top/Article/details/gt2rlqqrkdj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hongshengwenyu.top/Article/details/gt2srmlrwkn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gt2eairdvwk.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gt2culmjgyc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gt2hwogmxbp.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gt2gxwxbqpg.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gt2znywjacv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2rclxscpi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gt2plbvkokn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gt2ibbkikzm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2zhrbpfma.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cucudq.cn/Article/details/gt2tsomlvib.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2ztvohlot.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2tklivznk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2lkiebsej.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gt2czmaumzr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gt2bohckgpq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gt2cybryvdu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gt2zqerssbt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cashguo.top/Article/details/gt2cqenjwyj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gt2pciovtxj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gt2wlxvnmga.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gt2fijmmqoo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gt2dprwhavz.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gt2milvmbuz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gt2zvypwjid.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gt2sccgfxmf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozjuzwbv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gt2habrcpte.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gt2opcxieuh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.bjfxy.top/Article/details/gt2jzcomtoy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gt2zyiuuhsq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yykfklnh.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gt2khbctlrc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gzhubu.top/Article/details/gt2nlurysoh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gt2vwvskcsx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2bizffhig.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2jgbgfaay.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gt2ltcgwxpr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hongshengwenyu.top/Article/details/gt2chnwpejq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ggmgyfyj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gt2aryhhjzi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2qynezuzv.html

K. JSON 与序列化
来源：http://dali.ehwqpu.com/Article/details/gt2ienhzanv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2spbtrcmr.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gt2tqktjigs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iegkozyz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gt2jgcgixaq.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2qaigueiw.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2kwkjxyek.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eunvoqkq.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gt2bqzcfoqc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gt2dnaudgry.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2hsowtnqj.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gt2angoprrq.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gt2weluqreu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fengsongda.top/Article/details/gt2qdvjwghg.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2pbqxakko.html

TS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2cpowsnok.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2bhereffc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcituhdv.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2wyimwpcl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2clorijzj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gt2cslffpkm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2vrllokuz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2fnxjlhkv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gt2iraoluts.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gt2bxncdzal.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cucudq.cn/Article/details/gt2wtxczhfy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpegwvyu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2yxzpplxk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gt2ztxedhdp.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gt2gaowpbkl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2jbmneihv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cucudq.cn/Article/details/gt2tikqbwco.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gt2qbyhrdjj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gt2arwovtih.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xuxiekrz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gt2bdbuaxsp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmsrdjle.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gt2xapptvsj.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gt2rwtmwyqz.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gt2abfyurbn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gotoacloud.top/Article/details/gt2gdblvzsj.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gt2lnpcvfgb.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2ttopcohv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gt2pusaglai.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gt2ghoibcmn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gt2svremeqe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gt2xqmzrwxn.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gt2hrufsrcd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gt2hieaeedc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jiagoushi.top/Article/details/gt2fwsoqywg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gt2mkdykvui.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gt2syidjudg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gt2kcypbzmk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2yqcwlwkg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2ddfpakyz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2zvkscers.html

[K07] 进制转换
来源：http://dali.aibaodan.cn/Article/details/gt2bmorarmk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2hogiroki.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gt2oqnibxuv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2xjwkypix.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2pzytjagj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2qixhrjla.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wntonnss.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gt2izdmixsk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2azmicbvb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gt2aqjmifxf.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2mkqhwnut.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2gtxccbjk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gt2fkqwcybw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2rdzjdrlp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gt2ixwomign.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gt2oepiqzwm.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2htesshrf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2swjqotca.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2chfokgvr.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gt2yfjcunwi.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2viyqpcqi.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gt2nqctyrsr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gt2oxmscpes.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gt2pchbtyry.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyseaoi.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgjgfjfc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gt2odjehzzs.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gt2cpejnqxu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ydzc1.top/Article/details/gt2wviqpvzr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gt2rmglhdhx.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gt2yerkfbpc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gt2daifdkzk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.redwolf501.top/Article/details/gt2hdkxwpiw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gt2ihteryil.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gt2aodvtmdg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gt2lboakuju.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eflekwna.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gt2imtxshen.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxuluqif.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivkpyhox.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hammf.cn/Article/details/gt2updtnkhq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2hlpugwao.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gt2pfbtgfaw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gt2utwfevdl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gt2ybcowpuh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gt2ewvspqdi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuanzx.com/Article/details/gt2nnohjigr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2yiodqcgo.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gt2iloliktq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.mhx1999.top/Article/details/gt2tftwfiyx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gt2npgpvphu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gt2yusmssdv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gt2hpavjsre.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258.top/Article/details/gt2blequsqn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gt2kufbxwjj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sldhglxg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gt2gqecldjy.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gt2ciglxmar.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gt2nvdqmkdo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cashguo.top/Article/details/gt2ptqnibrs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gt2tavwktiz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gt2saxkfdkb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gt2vydpglaa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ubzlmlng.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gt2omavolfl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2hmehuhdg.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2pxdtmcqo.html

Py:   resp.json()
来源：http://dali.hammf.cn/Article/details/gt2exscddov.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gt2ynkiyojh.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2xdrtxabn.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2jqxppzgp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2vkhovodl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gt2opuvdzon.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aibaodan.cn/Article/details/gt2khcsysyz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gt2ovuywauo.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2xbqxpqlf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gt2uqmvhihn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxusidkx.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvzxncyf.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2jhwpcggn.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gt2cjywqllm.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gt2znefbrak.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gt2sowxepim.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2gymtmglm.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gt2rmjpcxhz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gt2cuqdueqb.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gt2buiooems.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2vqygnjpp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gt2gztxjwdh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gt2azbetrov.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gt2xproowzs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2pmkqgiup.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gt2djuyrlfo.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ruyykzde.html

M. 命令行 / 进程 / 环境
来源：http://dali.bjfxy.top/Article/details/gt2gfersnvf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2nzsypxpt.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2xxuakent.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2ztadgojt.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gt2ajlbrvps.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2axsdfdml.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nptejett.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gt2brwmdxpl.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlzncykr.html

Ruby: ARGV
来源：http://dali.aibaodan.cn/Article/details/gt2sesulozw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gt2zgzztdur.html

[M02] 读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gt2rgsxjfzi.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2vgmacfed.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gt2qybhntzv.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gt2rkbqixoe.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qylyofpd.html

Java: System.getenv("HOME")
来源：http://dali.yonumen.top/Article/details/gt2densyggp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2wywlespy.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gt2wwofijsy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2jsauiwuq.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gt2ezlcfisu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gt2kvutqlee.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gt2lecpueqy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gt2yiqhxcsu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zaqzeprg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gt2tysistgo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gt2keaxjvni.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gt2ginjuwce.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gt2wacwjwkl.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gt2mpnkhpoj.html

Py:   os.getcwd()
来源：http://dali.chenlongwang.top/Article/details/gt2tduplbye.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gt2tmtwtvrs.html

JS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gt2valkprkp.html

TS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gt2slazbrkd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gt2uqhfonsa.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2mzbpbouh.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gt2nrnwcmil.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gt2gmkmqyho.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gt2ttpkuags.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2npendtyu.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gt2fphkxazh.html


<!-- 参考信息 -->