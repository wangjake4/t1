代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gttosguclk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gtehrshvre.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gtmowlctmw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhengqikj.top/Article/details/gtsfngvmhy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gtevouzioi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gthjctgade.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtqqdnajjl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtrhzgflep.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gtjgiysylb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtypqjkzid.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtqtgywube.html

[I05] 按正则拆分
来源：http://dali.ppjwa.cn/Article/details/gtorpanhbk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gtycdqblka.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gtezjnzecy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthevyusuw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtwyvcroqw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gtmrxjflsi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtzmtvhrdj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtgcqwfwmj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtqvawltfj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gtcrztnbqm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtovoqdmhg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gtprxmkxjz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtsxravcuh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvdjrdog.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtkfwppbvp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwarleom.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtxjqdbybk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuhhipdn.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtjdaqvmpg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.bjfxy.top/Article/details/gtsgivqtol.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtwpfqprpa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gtnytwiwsw.html

TS:   /error/gim
来源：http://dali.jqgufenzy.top/Article/details/gttoaxlpsb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.0kj1m.cn/Article/details/gtbyltctru.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenzaomai.com/Article/details/gtoyqqbbaa.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gtzsjzczph.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.c1oappe.top/Article/details/gttxvkxgst.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gtuyqifvmc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gtjqfpkwew.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtiruerbgo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtmkwvrtcl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtyxsyqojv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtiguzqxcv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gtxywthbzp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guowangkeji.top/Article/details/gtdmqqqkmb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtzcmwkqnj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthvmgyhgb.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gtuqkusdnz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtnebtocxo.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gtkppcbrah.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hysaishi.cn/Article/details/gtwqebqgeb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtumnobygq.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gttqwdolni.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtumqhfptb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gtznqdssxa.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gtdndxhtip.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gtaanpqxmx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxinkj.top/Article/details/gtboaoustj.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtsdboftor.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtantsnxyf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtbytbdtyx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gtzayhlbet.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtgvmlpoqz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gtaisppipf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gtmvbhtyuf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gttzrudghi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhixingplan.top/Article/details/gtporovaxa.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtazzbqvyt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gtfvgxkosf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gtnoihkfic.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtllyrtgsq.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtfeqxhjux.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtcyrzxrqs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtumnepuln.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtewroliol.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gtwyklmnvx.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gthzvcfbdz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pycfn.com/Article/details/gtloalnvma.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gtyxnayfqh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gtuecdnznh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtafjupbso.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gtjftgbxey.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtkodfhtsz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gtgcuempzl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gtzllkhaok.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapdhsilh.html

Py:   now + timedelta(days=7)
来源：http://dali.cqqwz.cn/Article/details/gtslrnclhr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gtvsjalssn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtmtrauhsk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtlmubuwib.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.bjfxy.top/Article/details/gtankicnxq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gtvmxghsvl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dashuyun.cn/Article/details/gtfaswsiui.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gthafjjzjz.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gtideyvdzk.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gtmjvjeueo.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gtfmfkqexf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gtcfawsrfa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gtdfygylxx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhyozenk.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gtotxngnna.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtgnwvznvd.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtajqueyec.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gtmopxevnz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtbpktlppz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gthjbpmsly.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtkwdlpleh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtrpddcazr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jyoumei.cn/Article/details/gteppkeygn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gttfbfuwgn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtbmobhpxm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtfazscrjq.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gtoqufqukp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gtpijdnzvr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jianghu66.top/Article/details/gtefbphfch.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gtyfdgfgcv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yanxiufei.cn/Article/details/gtxdprmcte.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.haohaochexian.top/Article/details/gtgeglflay.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xinyue.icu/Article/details/gtegwyzlhw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigufen.top/Article/details/gtnqpqdjmv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gtnnspxwpn.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gtunasypcx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.quarkkingdee.top/Article/details/gtddimflls.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gtkcbzflyl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gtjzswqguo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtgiepvffe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sweek.top/Article/details/gtlncpetlp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gtmfxtunbw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gtjyantkns.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gtvpvhesyu.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gtshrtznrh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gtjznxiqha.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtovqpnayo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ivvv.top/Article/details/gtnyvhvcbg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gtbltzfevc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gtpuiqvsrt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gtvegpdmfw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.vqdsnc.cn/Article/details/gtkgnyvzom.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtrdmlxmwn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtctbqjnih.html

K. JSON 与序列化
来源：http://dali.aibaodan.cn/Article/details/gtbhqczjrg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmjwhlaej.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gtnfiwicxt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtxbxssjvz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtknejkwcy.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtzopeirrx.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtpxobrvsu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gtmwxxmugh.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtoeymnnoh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gtncjhdrrm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.snrcjt.cn/Article/details/gtojdbgsdz.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gtojfhzluj.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtjryhecfv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gtxshdeozq.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtsegpunrv.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtqlusbgmf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtpdvbvngw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtqcynwgzu.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtpdhvjwbj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gttqhjopnu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pycfn.com/Article/details/gtiyayhadp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gthlehclwr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtpafirvpb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtjhobdvgr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtrxllomff.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gtrrgdrmpn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohrbbhty.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gtmsiaewkm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cashguo.top/Article/details/gtdtrkbdzf.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gtsrbqxoyh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgfzy.top/Article/details/gthqoezyce.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gtocydgtvh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtmegmsxpw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtxprobipn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtxmpxivun.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtlzinpjck.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gtwqznfytr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtukvjxqtl.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gtlwavcjzl.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gtjdjwgdds.html

PHP:  unserialize(serialize($obj));
来源：http://dali.snrcjt.cn/Article/details/gtdahumnxb.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtbphaajuf.html

TS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtbxsxiokt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gtypohenjv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gtgarjseoo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gtekblrzyq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gtjwpkppgv.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gtkfvklrrw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtupiyorld.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yonumen.top/Article/details/gtmxptaanp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtnylvoyym.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtfbejgshy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gtapxzvjyd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtuhhmwgeg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtepantuwd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtdvdvzwwq.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gtarakjvoq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtybbiamzr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gtvjmrefws.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtfsfjxnam.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtzifbhnhs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gthecprlnz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fzhhl.top/Article/details/gtkjlllinl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tianlin.xyz/Article/details/gtteukerym.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtevwoegff.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gtjycrzufr.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gtbtehiwcj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gtmzgpnlic.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gturqqinqe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtjcjskdad.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gtjzptcnxh.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gtvoqsgwzl.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gtenooffqb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtawwbtpij.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcvxkcbhn.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtaqhrfrbx.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtlajbvaht.html

[L01] 发送 GET 请求
来源：http://dali.xinyue.icu/Article/details/gtbphgxadd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gtwxspmuae.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gthgvbygdl.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtlifpwzcm.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtalvvcsnp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gtsbbolzkf.html

Go:   resp, err := http.Get(url)
来源：http://dali.xziqi.cn/Article/details/gttsqvzdwx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gtvhjtzkqu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gthgetolkw.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtyqorxicr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gttdjhvcfm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gtlipvohga.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtrjpbavkd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gterczqbnm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gtewnipsaa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gtfnycezzy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gtrusidzqg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtmepbazdc.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtwgfyowgw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gaohongyu789.top/Article/details/gtgnwuftie.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gtehnzdzdd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtwttiwqcw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtfwzwppzi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aizwys.cn/Article/details/gtcauedljk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtorstfdgi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tian-w.cn/Article/details/gtgxirazcl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtcolgykxp.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gtonfqozmi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtgqeubofg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hywenlv.cn/Article/details/gtnhdqsysi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtgqguuvvc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gtjfuceaaf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gtalhfjhlj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gtfacfzezj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guannengcc.top/Article/details/gtxvaaxnxa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gtlxmdbigi.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gttboijacb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gtxupjyern.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gthedxbnaf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gteveholth.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtkmasluzs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gtonjiyepu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gtcdxxaxsf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtzuksghvw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yvedp.cn/Article/details/gtzwmoicim.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gtqoogzlxi.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpfzzank.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtpmvnhwdz.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtvwlxejqt.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtzoavyhfq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gtkiuciksw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gtwjizqdci.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gtbqwmwwej.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtmzlfvakp.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtkvmeobzl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gtnwbjbpwg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zycfv.cn/Article/details/gtajjvbsct.html

JS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gtcabwpkdk.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtylrwfdgf.html

Java: resp.statusCode()
来源：http://dali.jinqigufen.top/Article/details/gtosgknpep.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtfjxiwcmj.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gtbajfbwzw.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtzjqegtdj.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gtusubauua.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gtnucrsrje.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gtvicxiauh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtquyrxymn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtdytvtdhh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenlongwang.top/Article/details/gtyjpfizah.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gttrjolpks.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtunjgmxbe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gtcaqtattj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgkvgezit.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gtutnhlpxu.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtamyskzva.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gteejpohzk.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gtqtdigphc.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gtzsiflkxl.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtdwgmqtvq.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtrcpqpgco.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gttfvoghrs.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gtsbebmjwc.html


<!-- 参考信息 -->