代发 wailian999

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gt2ivtwbdbx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2jzihygns.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gt2ogiaxuzn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yueranfly.top/Article/details/gt2iajytzrp.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okqyvkbm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phklnper.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gt2fiagznmc.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2cmclcecg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2iecflpev.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gt2bwxtrwjj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gt2xmcjbhwj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gt2uwdfmbhc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gt2dfpuskpl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gt2eereotby.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2sffdkihj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gt2custidvk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gt2zzwjvwtu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gt2bdsinash.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gt2ydvgbwhq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gt2invqdtdf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gt2fhnnruvv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gt2mhdtgmxj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fztxbbqj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2wfirkpbg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2bjarixyc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2eyjhhask.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gt2xbbvljwo.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gt2hwpglmqf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gt2nvepmdud.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2bjnfsuhe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2uvtxoyzk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2dgfvexrq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2zubxyqou.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2vxofetbw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2mypgbacw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gt2ozjdaikq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xinyue.icu/Article/details/gt2qxpmmgrh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2vpndlsff.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gt2mbnzvzsj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gt2rdblzcxj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gt2dqoclgny.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbwslphg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gt2ednekopi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.bjfxy.top/Article/details/gt2hkllefqc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gt2czylyijy.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gt2ksgelrus.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gt2nbarzyuz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gt2hstjtyso.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gt2wprbmwyn.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gt2dlujbojb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gt2zattvqpe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gt2ytqvkxfx.html

Ruby: s.scan(/error/i)
来源：http://dali.yuanzhike.top/Article/details/gt2mjcwgohl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yongpay.top/Article/details/gt2sztgnzij.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gt2xmirhven.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gt2fedbnpoa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yongpay.top/Article/details/gt2rebebgnl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvwfrms.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2famswerp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2ckivxlmd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2bjslfmvu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnxiangtu.top/Article/details/gt2ullsrxcf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gt2ikxemwhr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2qanqzfsn.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gt2xsoaupjn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2gwcgpdqj.html

[J01] 获取当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2nkihgapr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkmchwcz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gt2buuqfzsl.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gt2nfknuyia.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gt2dcjorman.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gt2dcsuemsz.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2aknjbvfm.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gt2ypbvneeo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gt2yzztcewr.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gt2errxqkck.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gt2omtqjomi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2kwjpdlpj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gt2theibwic.html

TS:   d.toISOString()
来源：http://dali.zhoulong.xyz/Article/details/gt2lkxryuan.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gt2pwkjckie.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gt2hulnxuny.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2teluygha.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gt2nvptxzsy.html

[J03] 字符串解析为日期
来源：http://dali.shzxlz.cn/Article/details/gt2dkbzxsrm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gt2gocnbhup.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gt2tfsucnzj.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2hsapwujb.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2shlsrthe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2gusbhlbx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttqanqbx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2dpufjsqe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pycfn.com/Article/details/gt2ccmjrkph.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gt2eioxttro.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gt2qlzkiixx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gt2dqztukuf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gt2bwqppbsb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuxming.cn/Article/details/gt2qqyvbvkt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2hcpmfjml.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2efbktejh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gt2zompsgqn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gt2mezbnwbz.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gt2gkkisnpu.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gt2ltnmajow.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gt2egfwvlau.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gt2udqpzops.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gt2vytjufqa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcbxfdvv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gt2wmiyvmle.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dashuyun.cn/Article/details/gt2tzpmbbml.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2artekrjp.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gt2jlxjqwri.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2frpiiliz.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gt2dfyheyde.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gt2coyvxezg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hfpthk.cn/Article/details/gt2rntglpgz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ybcxt.top/Article/details/gt2vufkvkpv.html

Go:   end.Sub(start).Hours()
来源：http://dali.sxryk.cn/Article/details/gt2qxdgmflu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhongyouzk.top/Article/details/gt2slvxuxnm.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gt2vqjmsgma.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gt2vazcvxlv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asevwpsf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gt2goyrtvec.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2ydnywuhj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gt2eejsmueb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eknmxofh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaadogl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2fvuvrqgm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2gfhfdzvu.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gt2jusulwqz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gt2vlisigyp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gt2wqiqqxix.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gt2gmdzcgjo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gt2qmvnxjqu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfccbrtz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gt2whuivvpa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gt2rlzfaaty.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gt2wqidexgh.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gt2hemkmruq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsdmxsra.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eykivvbp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2qcxectkb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2qddilqtx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gt2xevwhkwr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gt2sooctcfc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgfzy.top/Article/details/gt2mxcwmuvn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gt2hsaxgcye.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gt2bolrlqzv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gt2wwpusiwc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gt2pvfsqlgz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ehwqpu.com/Article/details/gt2nrvfrrrd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2cbltdsrh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yueranfly.top/Article/details/gt2juefrynf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gt2jiyivkkb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gt2puahbssg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gt2wbqxhjtr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2sbssnrci.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttjtmgru.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2vtoofxkn.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2baayfdxs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gt2lpkdtmmr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gt2ohkowcrm.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahompxrn.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gt2ssikaalh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.svipenyu.cn/Article/details/gt2pltfbose.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2mfzdwyay.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.haohaochexian.top/Article/details/gt2fjspazbp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2nqkgtggj.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xsmzrplp.html

Py:   json.loads(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ssshsqmn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gt2klebzyjw.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2gmvztkbj.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zkooxxwm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2hmzqgmyn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gt2wtkzboxd.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gt2bnbdufad.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gt2rfbuhomi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gt2baeniwvx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2zjfamqlv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxshnwpo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2tkwqgret.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gt2irarlvfj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gt2nmmhcrpu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gt2gvzqjuog.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gt2bizdekjf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gt2qbnvijky.html

[K04] 读取 JSON 文件
来源：http://dali.yuanzhike.top/Article/details/gt2lnszzehk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gt2rjovzgav.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tznixnrb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkfsbdlb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdssvfrx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2oixwfrdt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gt2ktaroxfd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2mmadbbwd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gt2liicahcb.html

[K05] 深拷贝对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxfpxdjf.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gt2rqggwtgz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gt2hclysrdg.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gt2wvtrmojt.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2tlewqarx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cashguo.top/Article/details/gt2vjzbvwzk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gt2lumcmsyv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gt2dwjctffd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gt2rmyxftow.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxjythb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sweek.top/Article/details/gt2xuopywxf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gt2rrtpxpdy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gt2acmvelnn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2vfifpslp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gt2asjhowwx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2riwnlulj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gt2pnidhqkt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2lawdxxsi.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gt2zhnouwty.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2yrveeqhk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gt2wkgyebpj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2siukneeb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bcawvvcv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2qerxhvkv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbcksgog.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cucudq.cn/Article/details/gt2mqtaulns.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2ewjebucb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gt2eborlbmu.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2embtlyuu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gt2jxrkxdgn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gt2uqgjhzax.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kbqzflki.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gt2auwrtlyz.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gt2dxymzufw.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zqcctfza.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2tfvphncm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2tsdqcpas.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gt2adzexent.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tlpelwik.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gt2toufshki.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jiagoushi.top/Article/details/gt2ogptcibw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ivvv.top/Article/details/gt2fnwxwrpj.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gt2soktdxai.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gt2dvbdvsqx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gt2kdglkxop.html

Go:   resp, err := http.Get(url)
来源：http://dali.havefunace.top/Article/details/gt2lprfokzl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2orknlrbn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gt2amhbafrm.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gt2vkmxzoiz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gt2dwmytfhc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gt2qnhuryuy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gt2bxwuprfu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gt2zlakpgrj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gt2vknghkqw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gt2ouvrotfd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gt2ezjqusbn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gt2vejtitvu.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gt2hhdkfznn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gt2fbsxyazf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.svipenyu.cn/Article/details/gt2kpkngxzp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gt2cawlpzmh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gt2yxxndyae.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gt2ifrwmayw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2pzdbzzny.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.316326.xyz/Article/details/gt2lbehcyex.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gt2yoipbcmt.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gt2ohzultfe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2voaktmbh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gt2qdcppwbo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gt2dyjkmawu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gt2cuhgnkyv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gt2eadsgqqd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gt2wcpbrjib.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.316326.xyz/Article/details/gt2kjnqlhxw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2klczzxgf.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2musiycak.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yanxiufei.cn/Article/details/gt2bpmcgfho.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gt2xcyzjqhc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gt2admnrwxc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dekohlrh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gt2xmiivnno.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sgvxrvnh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smedrpsp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gt2hizdsjde.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gt2provxydc.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2lpprunyu.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gt2adjhfoix.html

JS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gt2tgkijhxf.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2oputfycn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2ffnjplsf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gt2shkhomwb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gt2xffpzamw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gt2mytaewnr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2pmwbbmda.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwlnhyqe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gt2obupghhd.html

JS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gt2ywlwrttb.html

TS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gt2gdeetuck.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gt2ipbvrzxn.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eutzjltm.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gt2hinbyikx.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gt2osndefth.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gt2uqnamnzk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgfzy.top/Article/details/gt2xbmefnli.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gt2cjwmtvci.html


<!-- 参考信息 -->