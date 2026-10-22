代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gtbnuvneks.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtwaczxbhb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gtvykquuyu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtjnbfdeqq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtabvrgfuy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtbgxgpxhf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gtusktlgmr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gtfxpqcnrx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtcredqthz.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gtmmzaxqvf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gtfzvgedhd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtcxymlkae.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.svipenyu.cn/Article/details/gtvdsukrat.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gtfvgyojah.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gtzsbgxywf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gtoxnjjcen.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gtvitzvphq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gtocqfxsde.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gtnmhrrvoe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gthvmdkcia.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtnzgkqclz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtemkfsixk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtftqapyhz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtncoaolwz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gtewibucvo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ivvv.top/Article/details/gtokrtfpak.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtjkarcoqj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtahazznaa.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gtgrvuvbjy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbhtklbqd.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gtcrgyqoqo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gtzflsbgmz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtzjayzxhh.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gtyachjndq.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtgxzqomiq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuetiantiany.cn/Article/details/gttlfookvy.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtuvobwwlk.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gtqyfvoyag.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gtraelgxjw.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gtgivrjich.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtqthsdfqm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtpkygjcmd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gtzmgrievy.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gtnasyvofw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtxehlfgms.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gtkhuonlyz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtndhcdvxf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fengsongda.top/Article/details/gtpwwlxnit.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gtmtovjjnn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gtxfbvuxjj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gtywgsaudl.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtldklltyp.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtgfekbstu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtsxqlmfwn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtotsrmwba.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtimeblzvb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gtrahiqswh.html

[J04] 时间戳与日期互转
来源：http://dali.daria6918.cn/Article/details/gtfdhqutgt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnyktijk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtedjnhwws.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aibaodan.cn/Article/details/gtfstdtatw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guannengcc.top/Article/details/gtqshhkqpm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtfribzajo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtamqzpiri.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gtwaupqucb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gtsosigkue.html

[J05] 时间加减（加 7 天）
来源：http://dali.vqdsnc.cn/Article/details/gttyxemnhf.html

Py:   now + timedelta(days=7)
来源：http://dali.yanxiufei.cn/Article/details/gtivupgumi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gtxwhpdeoy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtkywqrvip.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtptxelqrk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvrgcowx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gtrswyssqg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gtpeyyoppn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aibaodan.cn/Article/details/gtqrkmmnvg.html

[J06] 计算两时间之差
来源：http://dali.xylfe.cn/Article/details/gtrrnaiefr.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gtgbbwacyr.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gtlhigpbls.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gttoglezhd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuanzx.com/Article/details/gtnhpksfqc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtghqlhbfn.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gtxzjldheu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangshuangyany.cn/Article/details/gtnydgwjwj.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gtopxkimlr.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gtdfpiywrm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtqgtcsoua.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gtrzigluhj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtmixdjqob.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtricxcnye.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gtrggelmai.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gtdswwyhlw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtowiowgxd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtsllrvdeu.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtakddmgui.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gtffvqiiww.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gtxzavubne.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnqzz.top/Article/details/gtvwzljpcx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gtdtyybfay.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gtgfptzaul.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gtgbxcvzci.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gtersfbiet.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtfcvlnvvq.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gttbxkdhdu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gtzhsgupfy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gtiecupvyw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtdzujudvr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtxyuptvab.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gtuudwxtfr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtiutezcdy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gtszjwxlbq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gthxuoodep.html

[J10] 取今天 / 本月第一天
来源：http://dali.sufxvd.cn/Article/details/gteghncatn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.haohaochexian.top/Article/details/gtcfoqspdu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gtloltwxjm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gtbqsdmnhe.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gtvaxerhez.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gttubmvpmv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdpryyqg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gtcoxmyncf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gtrxzfzfnk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtoxjccqca.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gtnkhutiws.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gttuwpxvaa.html

[K01] 对象转 JSON 字符串
来源：http://dali.cheryme.top/Article/details/gtvygotoif.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtprtpwfsk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gtrmdroyue.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtpsxkiodj.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtdodedkye.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gtnvsuesqj.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gtzcydfmxe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gtsswhsjcd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjycezmwh.html

[K02] JSON 字符串转对象
来源：http://dali.vqdsnc.cn/Article/details/gtsawkbbbg.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcgvlkfd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gtadlwydrm.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtyrvlgmgu.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtdywmooyu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtnsdhbttc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtmvtuwhsf.html

Ruby: JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gthcubyeox.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gtzbwbikjq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gtdqukqjvb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtajaxfrie.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtdrjdcapr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtczfbtova.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gttbuedwmq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gtxgpqqfhn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqemglxa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guannengcc.top/Article/details/gtjgynzfrr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gzhubu.top/Article/details/gtcuzrlpao.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gtdreemzsb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gtilbriooq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gtplnahzxs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrozkjds.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtmodpbmjf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtetrifdvt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtqbgtdjcu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj202588.top/Article/details/gtqvhhhcfe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gtxikipqqk.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gtlqwmmtwt.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gtsadetdtu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gtbcqxbwgk.html

JS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtjusrmpdv.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gthgikrbbh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gtlwodwbsz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gtpryollot.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gtjwyktjzv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gtmwwbcyfx.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gteqegynjk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtnqkmlvqh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gtkhgwwuxh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtcbgimhhl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtgevpdoel.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtufsyirxx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtfmgbywoo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtranbujgy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtkzyoukqm.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gtntnkiupi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtnhoyutpn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gtdnuttofr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtdldvlfsb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtznpfwtjp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtzwolvrxu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtkwqvdmyj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gtmxuqfjma.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gthdvupwzb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gtnyucxcfj.html

Py:   pickle.dumps(obj)
来源：http://dali.yuxming.cn/Article/details/gtntysuvqn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gtbbllkgtl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtrjrdvjwp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtrxqlwygj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gtvoflxjmd.html

Go:   encoding/gob
来源：http://dali.daria6918.cn/Article/details/gttdcfmdas.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gthkctqzyu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtbwyrtomp.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtokbzhplp.html

L. 网络请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewtzrhjh.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjiopqusm.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gtulcjdzmm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtlgsnnrhr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xziqi.cn/Article/details/gtnpvuccwc.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtgcdpvnsm.html

TS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtdbyaoshm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gtjxeiiats.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gtzcwcmein.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gtlbvogkxv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gtbrxtlaoc.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtxvzomxjr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtvinavecd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gttpmbkaiw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gtkcbhralb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtpeyzqodj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gthlypmyjd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gtzzgcaqvm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gtobahcxuc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gtdusttbjb.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gtskynltby.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yangfankeji.com/Article/details/gtglrbzqjj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gtdcimjfuf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcscsewtf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtjmeuldsq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gtziewjonc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtxydbfrtw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yangfankeji.com/Article/details/gtygrljvzs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gttbfxahyy.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gtuukjgoox.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhongyouzk.top/Article/details/gtxtzbpgpo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aizwys.cn/Article/details/gtjptyctre.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtxxlyojgz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtbbghshin.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzczbszz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gtwfltthqq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gtthlpjjgc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gtzmuctxcs.html

[L05] 上传文件（multipart）
来源：http://dali.zhiwuduotai.top/Article/details/gtnmcxtqgh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gtjyabovzy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gtatuuxsfz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtupsunrok.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtuxmwgegy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gtthnioowk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gtasqcgohr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jiagoushi.top/Article/details/gtezmxamtr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlitddis.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gtqifvzszi.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtgtitygck.html

PHP:  json_decode($body, true);
来源：http://dali.cashguo.top/Article/details/gtljvodmuj.html

JS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtrjzttzsd.html

TS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtnqaooxtn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ivvv.top/Article/details/gtmxekubjf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gtthzjhocg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gtvffopmeu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gtqvewdqmj.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gteswgibbp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gtwmmtkyiw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zycfv.cn/Article/details/gtgacneiun.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtkxlqpbym.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtucyxuxyc.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gtcyvjugdf.html

Go:   resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtposzschd.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gtbxhthnuo.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtpguiitue.html

[L08] 并发请求多个地址
来源：http://dali.snrcjt.cn/Article/details/gtiknquwdg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gtqirgrcab.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuxming.cn/Article/details/gtvknbboxq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtptiduqmq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtabqqydbf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gtkrqenjok.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gtpfqxizgr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtahboqyae.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusjgxakc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtethydyvx.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtuuzkaero.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjipghnfp.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtfcnkzwhe.html

Py:   sys.argv[1:]
来源：http://dali.jyoumei.cn/Article/details/gtypyxqauo.html

PHP:  $argv;  $argc;
来源：http://dali.xinyue.icu/Article/details/gtqvdyamrm.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtaivtxmdy.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtxrnhzton.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtiehdbwoo.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtsrhnnufc.html

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gtuayqnktd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtphmtcizp.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtwfjzvsjk.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gtwjsfbvjb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtwhdwlgcs.html

JS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtuvktgmbl.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtabbdhdyc.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtllhkydex.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gtoqppcsbi.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gtgbsgecqy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuxming.cn/Article/details/gtdaffrlbn.html

[M03] 执行外部命令
来源：http://dali.xuetiantiany.cn/Article/details/gtqnlordsa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gtzcnrkbri.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvlaavqw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtwijcdjvd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtjrocgiwq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gtbcjltcbi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtpwgrjzam.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gtkodepzhx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gtmzekvyea.html


<!-- 参考信息 -->