代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdawzfhb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gteblkfpnw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtathztpwp.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gtryedayeg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gtpwkrmrgw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthpnxonn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtxoqboqji.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtwpcytzvh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtdpctodbo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtlwrjxtuc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtyobjlngc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gtaphuuarn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gtcqkyloql.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gthybqoezs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gtczwhurgu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtovtwxbbt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtcsuclttd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtwicxgvka.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sxryk.cn/Article/details/gthwsdjvzu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gtnblzvypv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gthcthhofh.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gtudbhwkxc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gtggerxvxz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtctagwvlh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gtirhhazfx.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gttjhrcfjw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gtzerunmot.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtjznldthz.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gtizcehhmd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gtpwgpnvjs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gtifsommvv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aibaodan.cn/Article/details/gttxonsitd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtgfqlusiy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtrycwrsgs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtxcanrejw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtphjqdvne.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gtbhygyabo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gtfqeicbnd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpovkfou.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtoniagkcy.html

J. 日期与时间
来源：http://dali.snrcjt.cn/Article/details/gtjiolajws.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtesyxmruk.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtapupmkdy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gtmhqhrdyk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtvcbkohzl.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtwhzbsabf.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtfiscixxi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gtirnapsxr.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gtkkybrcoy.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gtzdgqczrm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.redwolf501.top/Article/details/gtvyalookv.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gthfhxpjaz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwfeosia.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtidzdougp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gtmwjwicbf.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gtgxgvwddh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgyzsebl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gtxrilmycs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtgumwrseo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gtoalzojwb.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmnijcli.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gtuslsmjdm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gtekitaujd.html

JS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtuolqkiuk.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtsfwbmovs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtztueszar.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjxvoyba.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzocweqbg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtbyiojcax.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gtgaepqynx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gtfherqvgr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjhgosni.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gtfashzsfw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtepxrjomd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gtjkncmzoa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtctpjhjcg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gtxeftnfsw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gtffjelzud.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gtkwjayosp.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydyphisf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gtmcaznwvx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtujdjoong.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gtiaxpgqzr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtrefogldq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtnffmwdve.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gtvcnzlsft.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtjxeoexvf.html

[J06] 计算两时间之差
来源：http://dali.daria6918.cn/Article/details/gtxvdtxnqu.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gtuqutjrcx.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gtmxnnvoqq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gtastliaep.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gtzcggauwr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenzaomai.com/Article/details/gthsyapecf.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gtdhlpxnez.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hongshengwenyu.top/Article/details/gthhjispof.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gtykjhhqot.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gtoyahioal.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtaxpwjxqn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gtgsqdhcbl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtkjbkwzjr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtbwzjyklt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gtjpkhjduq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cucudq.cn/Article/details/gtdraovhhp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtkaepfxjf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtzbkdxioi.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gtxgdphjaq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gtsxmxcawb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gtccbmkudv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aibaodan.cn/Article/details/gtnzfmjpkk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gtayhcvnsk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gteqvmlvhp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gthurymmwl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gtfgxyjppi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gtiadjdghs.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gtgzbllosb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fengsongda.top/Article/details/gtlojhmwgx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jiagoushi.top/Article/details/gtmfvssiiv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtmlheuipl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtjhfcvkjy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gtfpvhgolt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gtiqlznecd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shzxlz.cn/Article/details/gtvryeqgsx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gtozwkgjri.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gtcxaumvmz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.bjfxy.top/Article/details/gtztfmgmaf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gteezpmewd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtmahfyqus.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtkzbljize.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gtopcoojot.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gtsrvtoeqo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gtmdjyloit.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gtohikohfs.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtyubxbvng.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtbczcosjo.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtavnyuuzl.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gtfqgitlwe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtqdsvyzpc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjiizapv.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtmltlqexx.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtmpsuffqd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gthdlhtdpr.html

Go:   json.Marshal(obj)
来源：http://dali.hywenlv.cn/Article/details/gtzlaiybjl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sxryk.cn/Article/details/gtxvjaidrq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.svipenyu.cn/Article/details/gthsdzvvvj.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gtnsqmolua.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gtfpznbhtd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gtnkdjyjgw.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtlhufgipw.html

TS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtfsbqxbnv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gtaluylvqf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtmzrbrrrd.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtkuapqnmx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gtcomlwokw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gtycqzmbck.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtuvfbuwzj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtwhvvnkel.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtjiphcgzj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtejpkofvw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gtjqgkoyhj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtuqvfqavb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenlongwang.top/Article/details/gtkmnffgad.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gtfhmxsmnm.html

[K04] 读取 JSON 文件
来源：http://dali.daxiang520.top/Article/details/gtlkxrakwz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gtnrnjjkkz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gtixwfkqyj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gtefohzwsd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtrsamzpjx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtjwzrpgru.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwjtloev.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gturnrzwcl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gttxhudozz.html

[K05] 深拷贝对象
来源：http://dali.xuetiantiany.cn/Article/details/gtkeblxssj.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gtpacekmha.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gtnsknylty.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjjgbbzq.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogcpxyqr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gtvnikjibc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gtkepztlqw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gtqzbmfscy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hysaishi.cn/Article/details/gtwoguvohw.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gtynfkjasb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykhvpttx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gtjdrkvgil.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytnnolab.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtowgbxtxj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xinyue.icu/Article/details/gtkrdatcml.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtyruhdclv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtzszschfe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtgakgobmz.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gtsrzegfgq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gttohpidna.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gtmiycphwh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtpczmmtww.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtgilirnuj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtcqtmezpl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtzdmfofjv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gtjszwnoza.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtckpjbsbm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtaqapbp.html

Py:   pickle.dumps(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtwmdtebwb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gtdogirkia.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtxlmwuffu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtizyeptxn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gtxbhvtuni.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gtcfdjhesl.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gtvqizvfna.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtgnrpgsoe.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpwjeqjnx.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtxbgugtjn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtygglnsvh.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gtkghtohoo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gtqhpohgzf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.c1oappe.top/Article/details/gtyjeeastn.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtpxvudvlo.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtjtnhbyup.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gtoybovoov.html

Go:   resp, err := http.Get(url)
来源：http://dali.c1oappe.top/Article/details/gtismkycem.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gtdxgcgdef.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtnxbhrmqc.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtmcetsghg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtcoduxkav.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtptkizlcc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtvgrxomjb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtivzymlkt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gtpdkcmdeg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aibaodan.cn/Article/details/gtbyoevrle.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gtubftlcuh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtywvmjnad.html

[L03] 设置自定义请求头
来源：http://dali.daria6918.cn/Article/details/gthxwzlulo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gtoraeungg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtbvbxmhwh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtoftwskdx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtarbsajcj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gtgnbtpqni.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gtsozwvvlj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gtkwnodozd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtyquotefw.html

[L04] 设置超时
来源：http://dali.shzxlz.cn/Article/details/gtbtroznpv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gtpiatneau.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gtlqsmxkgs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gtzeorwdps.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtprysivuo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtxntjujjb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gtmyvapqhj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigfzy.top/Article/details/gteejyjhvu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtcaeexrgk.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gtuvyuslff.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzlbuesq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gtswxtpjaj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtzxkdxugg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqvflcbh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gtxtnsapjb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gtwbzskxyd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtehaodjya.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtmaqwiqnx.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gtsdebbuns.html

Py:   resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzjscbhc.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gtsalilqtb.html

JS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtlfrifsoy.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtfhkxllow.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtyiosxcyu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gtcgxgfjzj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.feifeiyinyue.top/Article/details/gtnmsqixkw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gtsybekaxy.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtizzxbxbm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gtsnlkuexx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtawswwyzy.html

JS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtavxlrylh.html

TS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtpiguxecn.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gtkhrnfioa.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtrppdxulk.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gtbohmhsqm.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtymesvhab.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gtstfhspnz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pengpengdd.cyou/Article/details/gtiyfbfqkt.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gtilpoablg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtgxmtfenl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtsqheaywy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shangyingyoupin.top/Article/details/gtrkjqglcp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtvpkzoscn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtdbaxvnsc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gtnsvouzno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtszssexzt.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gtnsubgphj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkxcymhgi.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gthroydidu.html

Py:   sys.argv[1:]
来源：http://dali.cdnleiting.top/Article/details/gtuwczcfow.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gtsdeuhxsc.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtztshwsnt.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtyhdiqjoe.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtjnlhxoou.html

Go:   os.Args[1:]
来源：http://dali.sufxvd.cn/Article/details/gtjiowosls.html

Ruby: ARGV
来源：http://dali.zhixingplan.top/Article/details/gtdmrylely.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtcmqybnwe.html

[M02] 读取环境变量
来源：http://dali.yueranfly.top/Article/details/gtlvhreffv.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gtvaqshnhj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtabmtpnlc.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtyatjlulx.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtcfclakhb.html

Java: System.getenv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtfbsmacqz.html


<!-- 参考信息 -->