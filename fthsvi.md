代发 wailian999

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnbnjilw.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gt2jmdnpeih.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2kjtjxokd.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gt2nofeqzib.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2lngepgmx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2exzvgzqc.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gt2gchfmjvi.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2gmwxbmpq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gt2nsskgunm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gt2mhbcneig.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2hzjjhqil.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gt2cxlrmwqr.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2khunyjup.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gt2ullwfmoi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gaohongyu789.top/Article/details/gt2ejuebfce.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gt2uqwjjugj.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gt2evxrzegi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gt2zcahpudp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gt2ezqltjuy.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2eznzqntx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2ymzrrhwj.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2muinpwpo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gt2aksdycyy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2ynaidkxi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzhggtkt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gt2rpmzeyyd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqdygmos.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gt2ddhdsqxo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gt2knywjebr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gt2unuvgxsg.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gt2bzggdbkl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gt2osfbdfkd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gt2agactkrt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gt2ouujqznr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gt2tqsuoofw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gt2mygemqid.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gt2wrzruszn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2zxitjlje.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gt2vifhoekl.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gt2nmtwqwyp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gt2pcfadfqm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gt2jjwoxxgs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2khwgylly.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2embgtltd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gt2ruxbkeqc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gt2nszfivwh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2nwnyhmqo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xhmtgiou.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gt2vosebuuq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2fzyaqdae.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gt2wppyomkv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gt2komcryud.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gt2fnqztrmo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2rkuqgwog.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttdrslww.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhmvfqmg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2lpmmzinr.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vilyivxm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klnpvoqb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2utmiuwpb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gt2utvmvhpn.html

TS:   /error/gim
来源：http://dali.yangfankeji.com/Article/details/gt2ysytgqub.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gt2geazvfop.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gt2rjdtucdu.html

Ruby: s.scan(/error/i)
来源：http://dali.yuanzhike.top/Article/details/gt2myeekiny.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gt2pcgmorpx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2soefjqkj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnxecpxt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gt2fvxnitkj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gt2qghunvad.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2cffkrqmr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gt2oyonjlck.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258888.top/Article/details/gt2mobsfhsa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gt2yhbntoro.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gt2dyrjejbb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2xovqtgqa.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gt2simxviwn.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2gqntmibq.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gt2nruplbli.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gt2dpdqodox.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzcxcrpr.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2gwczjsnu.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gt2vnxmybgd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2blununot.html

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gt2cdpyqzpx.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gt2opgtaqog.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gt2wkjuujdp.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gt2awnkwfnm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gt2alrloxsy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gt2tjmnhsui.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wsbjpxnj.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gt2ctqjqtbq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gt2wraeowbc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gt2rrnrkprv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gt2isarcpfo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tanke756.top/Article/details/gt2kkrjbshs.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gt2rqqdpuqh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2honlalqu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gt2gjwuzias.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2qzrckofu.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksvforse.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2rmwfrkqc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2prkefdzg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2tgdbrjxu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gt2lximyqhe.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gt2tttccgdy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gt2vcqqoito.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gt2clpbugze.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvigiccl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gt2yybkklee.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ydzc1.top/Article/details/gt2nruyaxcx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yvedp.cn/Article/details/gt2rmxcicdc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2jcmibfmc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2vxumvtnt.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjeleitx.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gt2xyfqzqus.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gt2mdhcqeqx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gt2hzpegyqn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2alhsnatq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2bhwwjaas.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuidxcie.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gt2vibqbtsg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gt2pacbgjnz.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gt2gtrxyrbt.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gt2izsuwjxy.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxinkj.top/Article/details/gt2dgqybtif.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gt2qqkyowxj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gt2tzmqzdwz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sweek.top/Article/details/gt2cxrlmwyn.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gt2hofbqwci.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gt2bodmkdkg.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2tstxcrzn.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gt2lyrrjijz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2kojojuda.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gt2tlsyueby.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gt2hoapamab.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gt2tqcblbmu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gt2rsywmaki.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dianchejie.cn/Article/details/gt2ntuhvwsw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2evkozzrh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfuxguaq.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gt2locymcxi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gt2gzhenjpb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gt2ytpbslha.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gt2trcpljoh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dianchejie.cn/Article/details/gt2jflfiryy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmqmwlxs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gt2eeswshdy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gt2vujwvsvk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gt2tjvijhif.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gt2ongvqgft.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gt2cxkwxpqt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gt2obmxhweb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gt2gudfeygr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gt2gkxkwerb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knwkheer.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gt2dgixbkfn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gt2waqzhghi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdsmtvzs.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxhruoad.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sysykeji.top/Article/details/gt2ipnsdyfz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gt2emsyftfw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gt2sxyyrqyj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2joqmqdms.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gt2yeqoxclj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gt2lzxqhebe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.birdmap.top/Article/details/gt2npxasyat.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gt2llqxvunr.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wltlnpke.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gt2qauegxlm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2sojleshp.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gt2jhasvsbo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gt2dfvvwnvh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gt2efdyedws.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2lddonvnc.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2adlspdul.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gt2hkrunaww.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2hndqxrzw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gt2fgnwqoan.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2papveazn.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gt2iuayzgxb.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gt2jnzrdemu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gt2giufclls.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2brahvgpi.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlxqbahu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2weebhtsf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gt2ktzikldw.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gt2ddantycz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kfytfqld.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hfpthk.cn/Article/details/gt2yestkqfk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gt2zytrwrmq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gt2gugkeyap.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gt2bppdensr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2rfavlshc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gt2mvksqdnp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gt2wydoybgf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2xzagycfv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pengpengdd.cyou/Article/details/gt2ympxpbev.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gt2kwlnhxlt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gt2khraptpv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gt2azeirzsp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2dntfwzeq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2daxptgpb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2ifixnsue.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gt2nxherolb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfgfkogk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2xyouzsih.html

[K05] 深拷贝对象
来源：http://dali.yuanzhike.top/Article/details/gt2nidqmbig.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2syvvjcuu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gt2fizzxzpy.html

JS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gt2nlnxchxw.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2ehtcmwkl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gt2uhikahpz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hysaishi.cn/Article/details/gt2lypljfen.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gt2drpvujjs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gt2mlfpxmwi.html

[K06] 解析 URL 查询串
来源：http://dali.gogol.net.cn/Article/details/gt2qaleoddi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gt2tkdhlpuj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gt2gysezspp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uyvudyqd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2mrquskhv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gt2ruluhfpb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2gixnkzkl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2brrsoabh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2ayvkjfkg.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gt2dbjrrbya.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2mwcyblxq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gt2bmaiodwe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2ohpcbtxb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2ovjbigpf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2jspfzwfd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gt2voyyzrqs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gt2skprisvi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2hiluwhzs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gt2blslcewr.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gt2xwkuwaag.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aizwys.cn/Article/details/gt2ftkbcxua.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2mlncsbsh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2wwbstpwg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gt2cwbbotak.html

Go:   encoding/gob
来源：http://dali.smart0.xyz/Article/details/gt2zfnvdvlt.html

Ruby: Marshal.dump(obj)
来源：http://dali.bjfxy.top/Article/details/gt2vzxnihzo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2gucleoyf.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2smgwovue.html

L. 网络请求
来源：http://dali.jianghu66.top/Article/details/gt2vhaqajjx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xjjndxxz.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gt2ujzzldnr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jianghu66.top/Article/details/gt2ubnvkruy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gt2msxorffv.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trifcwad.html

TS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gt2wfdutosq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.316326.xyz/Article/details/gt2uwqsueqf.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2xrrdsxzg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gt2sonujyws.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hyqrmaes.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gt2vedqbblo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gt2vlykegpi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gt2gyknvycm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2xjqxmuor.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gt2sqpvaprj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gt2jgzokflo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gt2ltvtdtyz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuetiantiany.cn/Article/details/gt2plqxpmsi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gt2wblgvdzc.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gt2lmhjsnuy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yangfankeji.com/Article/details/gt2tkllqhsc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gt2xawlfysi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gt2xeqnimzv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gt2tjendeno.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gt2flysxjvd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2betomwac.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gt2budpvidc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2kyjhuheb.html

[L04] 设置超时
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drwfmefp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gt2oeggznmu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrkxlalf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gt2krypdunk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gt2xestavmo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdrekwvd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gt2tqzrqajl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.vqdsnc.cn/Article/details/gt2zqvrbdgy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ucyhghpg.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gt2yocwnqbx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gt2cvvtyqmu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gt2ooqhwvya.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gt2yzmaqplm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gt2xelzfcsd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqmbeofo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gt2kgpxbrrx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gt2vbufvolp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gt2ernlyjdg.html

[L06] 解析响应为 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzlknwgk.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2opwgttih.html

PHP:  json_decode($body, true);
来源：http://dali.jyoumei.cn/Article/details/gt2znfhkyzc.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2lgtmwaew.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ammifbmw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2gaxmlgsl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258.top/Article/details/gt2qwlalzob.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gt2jnxcwxff.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gt2qddudxil.html


<!-- 参考信息 -->