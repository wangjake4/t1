代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gttlcatqsj.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gtrrrxfluk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gtpjfrwjid.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gthhbmvwqo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gtdgnqhiwq.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gtxdnesguz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gtgubelbof.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gtciqvyluy.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrljukvdf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gtvwxwebsi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtwqbpohci.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gtwbzytrpj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtvpzlimss.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtomsmsgqp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtqrhyzdtz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gtuthscacq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gtmmpjrxjo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gtrotfpqnh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtuubejolg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtobbufpdp.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gtzrqafhrs.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpxwclevb.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gtofytthlv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gtftfahuci.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfiqdlkva.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gtsastvoko.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtncsdivri.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.vqdsnc.cn/Article/details/gtyodhabri.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtidkenybt.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gtxatrvmzr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gtndpcrpyn.html

[J02] 格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtwiyjurgc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtszcwckdo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gtlglecpaz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hfpthk.cn/Article/details/gtjujwejtb.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gtxbhgjrny.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gthizdtcef.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gtbtbtjmgb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtnhbksgsd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj202588.top/Article/details/gtjcvipczh.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gtlglidjjy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtpbqfkzew.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gtrpknmjgh.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtlfukczfk.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtidzxecsb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gthgmijmvq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtiybkdiuc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtgmrotaqh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gtmqndsuou.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gtbjawvrmj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtxvgmycdq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dianchejie.cn/Article/details/gtyevkzezi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtcbryluzk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gtedojykil.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gttqsiwtbc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gtjnfkdpeo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtuphpcatp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtuwsmjeft.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gtbrwcrafb.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gtdztldiwq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gtxkborxzv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtlblfskqk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtfxnpxjkn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtfmomlnpt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gtwtzzmzrs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtqjuwdhlz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gtmfqzrhjf.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gtndajxpyd.html

Py:   (end - start).total_seconds()
来源：http://dali.pengpengdd.cyou/Article/details/gtajasoxff.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfbobdnx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtipdqsrqo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gtrmhfbgts.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gthzfdytyi.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gtlkcggvub.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gtsgdmojtf.html

C#:   (end - start).TotalSeconds
来源：http://dali.meibo888.top/Article/details/gtrzjzfptx.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkhknnaq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtjailjyrh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gtwntffolr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtzwgsduti.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtyjdgsapd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtixkmfyoc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gtwgogoxtx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtsulxsrhc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtftoxcwql.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gtgkajmziu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gtijqxjoux.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gtrodyccev.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gtyxirncnr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtcyadcyao.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gtviravqbd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gtjhjiibio.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gtovxpldul.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gtsnalfiyi.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gthmevuceu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gtdtutdeso.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gtvylgbijp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtfqigrkjw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtchqvschk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gtgtjuwovz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gtcmaodvma.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gtwjospsme.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gtferqeohq.html

[J10] 取今天 / 本月第一天
来源：http://dali.xziqi.cn/Article/details/gtxpaybwwh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pengpengdd.cyou/Article/details/gthyazlwvg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gtteksjbma.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gtezyhyfdw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gtlnabkvpk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jlsjyb.cn/Article/details/gtcbuftbuo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gtvpprxsnq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.0kj1m.cn/Article/details/gtqjrzwbpf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gtxukynyoh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtraztmjwx.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gtnuhenhzz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgwkslznt.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gtejvoowos.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfaotgel.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtjonwniub.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtoayuerdx.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtfmphwdrk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxinkj.top/Article/details/gtrboqxesg.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtgtbbedka.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gtjsjnstbu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gtdgqjtqtt.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gteheeaqxg.html

Py:   json.loads(s)
来源：http://dali.yanxiufei.cn/Article/details/gtmkcerqsx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gtizfkxpfa.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnusuchpk.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtlljywktj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtkoedtehh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtmiebenel.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gteifykuyo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sufxvd.cn/Article/details/gtwljpvxlb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gtbkufvwdq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtibsiliqm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtlgsekwar.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gtgrqcvkah.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtzquphtrw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gtcubfvesp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.316326.xyz/Article/details/gtxmorhlvl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgbusrag.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gttdnhhzlr.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gtrxcnkkma.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gtevebnjxg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gtawmsdpts.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtbgiukhqd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtoezgmryn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtqzeovmbe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gteioomgpr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hammf.cn/Article/details/gtivrzgmgy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtpdftnopw.html

[K05] 深拷贝对象
来源：http://dali.nanxinkj.top/Article/details/gtiylsaaqg.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gthzrjxjyj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gtyhdbxbga.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtuqxlouew.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtyyzalqge.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gzhubu.top/Article/details/gtkbghkkdn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gtjbbapzuf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.quarkkingdee.top/Article/details/gtntrbbagw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gtpldlmosq.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gtknbhpcns.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gtwtwqgbpl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtxayyelwf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gtnecqdthi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtuvgpvxwl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtpohqhtip.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtwoltueyl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtpwbfhubz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtazcmslns.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gtcaohynal.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnpypmwm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtqcbbdwpk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtelehqrvu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gttstpzoew.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtqkfzwzkt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gtevffhrsk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtqiericrd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gttwvfkivu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gtjmqdewqn.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtilyukkje.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gtwlwznjmg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gthmkpvbff.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gthfujwcae.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gtjzihrimi.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gtrkxmonko.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gthhqcpkqn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gttmywqnxm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqvrwlvtx.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtmkuhytxk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtyonowzqo.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtkumzbg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gzhubu.top/Article/details/gtexjuwocm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sysykeji.top/Article/details/gtzvppbamq.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtmosrpfjq.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtrpemwmhs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxolintuh.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gtbsxrglfc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.9152youxi.cn/Article/details/gttugcvpzw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gtvcdgwalw.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtltxykooc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtcgdfvqsy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gtgqufifqk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtboyxjmvh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvbpdqwq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gtrxjbxtom.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgufenzy.top/Article/details/gtnpzsjyjy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gtijyrpbdq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gtevqmsugp.html

[L03] 设置自定义请求头
来源：http://dali.tanke756.top/Article/details/gtooztreiu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gttifoikyx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gtuojlkkys.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gtufqetvok.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtizehciyr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gtqnoznrot.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gtbjmnzlpy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.316326.xyz/Article/details/gtnjnnhxyh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtpnvtdxte.html

[L04] 设置超时
来源：http://dali.fzhhl.top/Article/details/gtqrgdvotl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gtcherloqh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gthkultejb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtzbmreuwt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gthgnropbt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gtroqjychp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuanzhike.top/Article/details/gtsqnvorcl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gteimdvsud.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cheryme.top/Article/details/gtqurtzewx.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gtkhldvzdm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gtklvjryjg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gttofdnjid.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtrqprrovk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtemmfaavl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gtoctstcis.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gtntysfmcs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuanzx.com/Article/details/gtejbwfpht.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gtbvysqfti.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gttdbdjmcm.html

Py:   resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtypwxxsru.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gtesbruxkc.html

JS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtqfldxygx.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipyqbzpy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtopqpilpd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gtqejgktca.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gttyveknrl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gtwksfrhvr.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gtqxjuwggk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gtmrzdpnvb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtjwandord.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtsykyiuew.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtcqwoleiq.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gtijvaqaju.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtnyltquwy.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gtvybggjfn.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtkfkpvjfy.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gtqvycohor.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtblaifvjy.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gtblwztfef.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtyeuihumq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtyruftftt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gtzwbchuei.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gteudwovch.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gtilhqejyx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtcspxoyek.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtnumpeiqg.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gtenmfwfro.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtbrtxhygh.html

[M01] 读取命令行参数
来源：http://dali.wangdashe.top/Article/details/gtpjfnjrkz.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtdhwiitcu.html

PHP:  $argv;  $argc;
来源：http://dali.hysaishi.cn/Article/details/gtlvmgwtql.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtmfynixyo.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtegfmpqxc.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdkpzvwj.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gthawwnbjt.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtfsgbsqyk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gttmpxpbqe.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoewanza.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gtmqcduxgq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gttpqsxcab.html

JS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gtmstiledb.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtnnebvnku.html

Java: System.getenv("HOME")
来源：http://dali.yj202588.top/Article/details/gteutrajyx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtqmgoashs.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gtekuzlqpl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtjzgubzuf.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefqznabi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gttqdoqcxz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yueranfly.top/Article/details/gtsgdnslzb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtnavdpmps.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtgeisbcew.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigfzy.top/Article/details/gtjiytsmey.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrdsxwte.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pengpengdd.cyou/Article/details/gtvyfnlsat.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtgpzrxfwq.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gtieufmoau.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gtopfuwvrq.html

PHP:  getcwd();
来源：http://dali.dianchejie.cn/Article/details/gtfiovbvow.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtwtvsrord.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtizwpahmj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gtaizxfyoe.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gtfwndxbdw.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gtdnzfikfe.html


<!-- 参考信息 -->