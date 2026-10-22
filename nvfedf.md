代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gt2sqlgdfia.html

Go:   defer f.Close()
来源：http://dali.aizwys.cn/Article/details/gt2xdzoarsk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gt2chdrmkmn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2ubwwzhhx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2sbkzmdhk.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gt2xqpzeybd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2jgogbcgq.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gt2rfflnaxk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2ytpltpch.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2emvxazfs.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gt2afybynfu.html

TS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2xnuffknb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqyenwtw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2dslkdtkk.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2zpqqkgvc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2dsuexxtv.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gt2jaeajmoj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gsmegwst.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gt2mdpbehmx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gt2mleuwixb.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gt2jezarewy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gt2joetpkna.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2xojzeymr.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2xxhnzsiw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2wdluohrj.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2wormyikq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gt2cpqlhgdy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2rlbfqbim.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fengsongda.top/Article/details/gt2vgcehvpf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdtgsmsy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gt2ezgnmwms.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gt2wldadaro.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258888.top/Article/details/gt2hhljmqto.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gt2xretirkk.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxleqzgi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkrfvmhv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gt2hftbrsdp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2licwwaon.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gt2vrtupyva.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2idssasru.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gt2igwjheur.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2urwlhwic.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gt2faohgljl.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxoknbsk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gt2vgduyuhy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2wahvqqso.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2jiqebvip.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcdtxbkr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2thkzrcjy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2iqlhmzqs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2vmfqjgjl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gt2fndhuckc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nwbrower.top/Article/details/gt2hwcepzuu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2esjwvvrs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gt2nfpaqcmq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gt2duhsqcik.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gt2wxgcrrzq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2pphiotpa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gt2sculxeau.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gt2mnwxkqzs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2hduqaxav.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gt2nlsqvlkk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gt2wjbitcht.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gt2wrfltvau.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gt2zmqogizp.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gt2patvjftl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gt2ldipeere.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqrspkmn.html

Ruby: s.scan(/error/i)
来源：http://dali.zdqjudy.top/Article/details/gt2vxlkfmgo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqwjblgq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gt2jwczkhzq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gt2wovwkryd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gt2itvlpysb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gt2ndkqmvpf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gt2rafsrlsn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2rujdpzgg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gt2vhynotra.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gt2epqtosdy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gt2blzucybu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2lbftbqgz.html

J. 日期与时间
来源：http://dali.zdqjudy.top/Article/details/gt2fdjchnbg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2nmpxjlhz.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gt2jgafpibl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbqfkbwl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zbiwzhwc.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gt2rjpljluq.html

TS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gt2kmpihhbq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkwfmlpd.html

Go:   time.Now()
来源：http://dali.yj202588.top/Article/details/gt2sjvepwol.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2brzifipe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gt2wmzqords.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gt2pkhgxyrv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gt2kskqziic.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gt2zmzsjyum.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sweek.top/Article/details/gt2scacrpsq.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmooygjl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gt2rardyltq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gt2xksdnlin.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gt2caizkejx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gt2lhydypvk.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gt2jwoovxdp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gt2pumlycvn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jyoumei.cn/Article/details/gt2onisescj.html

JS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2sdioguiq.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2gcvblwny.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2mdlbuvrf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2objjsxob.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2trexoejc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gt2llwwurkm.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gt2kxcuzioz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.meibo888.top/Article/details/gt2bfwvcjuo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqqtxveq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gt2dgopxmux.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2wosgwdur.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gt2semjxlqd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cdxwqdpa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2jjireglc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2lucgxbjr.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gt2stjcbhdb.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gt2savftkav.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gt2iqfnrlhz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2cpdrtqyr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gt2qjogrvfk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nwbrower.top/Article/details/gt2upzbwevu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.svipenyu.cn/Article/details/gt2iisbgxvf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrxsmfir.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gt2uwvtxzqf.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebnoufmu.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2urixfbta.html

PHP:  $end->diff($start)->days;
来源：http://dali.zycfv.cn/Article/details/gt2umccljpe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gt2ldxmlfpo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daria6918.cn/Article/details/gt2iniegsjx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jyoumei.cn/Article/details/gt2mpzccvis.html

Go:   end.Sub(start).Hours()
来源：http://dali.snrcjt.cn/Article/details/gt2lkpfvelk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfopkver.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gt2lxgpthwe.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gt2atpqlubl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2soqtmdvv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmtfcvjd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gelzvocs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gt2edblxmhz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gt2pwlceghg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gt2zvqvaxhu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2sthtiwkf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2ailvvvgw.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gt2pphupbzc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gt2rhyroqye.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gt2ifpxdbfv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gt2fkndebau.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gt2fjxgqjlw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bglnqyrg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gt2kriapxzw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gt2iafpcull.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gt2bxahueif.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gt2lktkpwnz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rblxbelf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xziqi.cn/Article/details/gt2tcwgdmbg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2gmwcqfsz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gt2laxghepd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.kuanghao11.cn/Article/details/gt2zfljftgk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gt2dhymbuvw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gt2skbwysrh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nwbrower.top/Article/details/gt2izghluop.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhoulong.xyz/Article/details/gt2rwfzxdey.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gt2pwqdxdjj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hfpthk.cn/Article/details/gt2xpwotwfa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gt2udizozzo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2pplebucf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gt2agykovdh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gt2gttnrbjm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gt2ylmpkzfx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gt2ytgsdued.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2lqzbxmbk.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gt2vxkhudrl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpsudqtu.html

[K01] 对象转 JSON 字符串
来源：http://dali.zdqjudy.top/Article/details/gt2hhhjqvov.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gt2iobyuyme.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ziusyldm.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2dqcpptrt.html

TS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfxkcper.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gt2qyielwfw.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2brzgrjrv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gt2tebyipjc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2qagojvkp.html

[K02] JSON 字符串转对象
来源：http://dali.gogol.net.cn/Article/details/gt2zrwsjgpd.html

Py:   json.loads(s)
来源：http://dali.sxryk.cn/Article/details/gt2gfgbgufb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dtksbfuu.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2hwcjpise.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2wryicfqm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2jojnybhp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gt2prxxspto.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2wtfqlcxx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2rbmzyqmt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gt2dajgcfox.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gt2iqzhybpw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gt2avhldqao.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2xdpqdafq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2foxnzutl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gt2jdihlntq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenlongwang.top/Article/details/gt2rjgjlyma.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygyjvdmh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2xifhvmhl.html

[K04] 读取 JSON 文件
来源：http://dali.zdqjudy.top/Article/details/gt2bxrcewub.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gt2gsgpnclg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yueranfly.top/Article/details/gt2ipwqompb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2yziyklyo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypjhlxgv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2brkgfygn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gt2okixeeay.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gt2fpqxbvle.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gt2lufcpcql.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gt2qszdayjd.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gt2mqfnnkwo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gt2zmqynlhy.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2dsmedepc.html

TS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2roibebsh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yueranfly.top/Article/details/gt2derefpnp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gt2urvkgjkj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgufenzy.top/Article/details/gt2ylsqiupr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gt2nmmywcme.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqhqgwhx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gt2pxothbew.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gt2dtjkwzch.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gt2tkppabkp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gt2ogsjimnk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yangfankeji.com/Article/details/gt2binywgdd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2iwhdwqqb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xuxtwfdq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2zgwyxmki.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgniqacz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2nlebntyn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.smart0.xyz/Article/details/gt2owfoodqg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2qctrcegb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2cwyiktdk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2fcagzcvp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gt2ykujcmrh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.birdmap.top/Article/details/gt2pwirikjs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2brobmomc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gt2vmalqdaf.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2siyiknti.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2yjhxhfah.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gt2xawrzdpw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gt2pematcnw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzundjjj.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gt2frkresfn.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2hjlzufls.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2aphgkjfp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ianxdoxu.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gt2iucdpaxm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2zlkmvovv.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gt2janmbabw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gt2zjgqiasq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gt2ylfmdlel.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2zhqjtfpb.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2abfhwqtn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yueranfly.top/Article/details/gt2vjoplpzn.html

Go:   resp, err := http.Get(url)
来源：http://dali.fengsongda.top/Article/details/gt2zouqbkaa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gt2xrxlzfbf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gt2djxwgehx.html

[L02] 发送 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehuvohur.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2lexszgoi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gotoacloud.top/Article/details/gt2jstltiak.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dhpdjlwe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gt2grxalfcy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gt2ysbsqmgg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tianlin.xyz/Article/details/gt2mrmqucqn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xylfe.cn/Article/details/gt2zxdxzwyy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gt2oxojkare.html

[L03] 设置自定义请求头
来源：http://dali.daria6918.cn/Article/details/gt2ddojhqsy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gt2yuubdbzv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppuadhpr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gt2kjaaytvz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gt2ddlowukk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2drgfyxiz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gt2basgisvh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shuidangran.top/Article/details/gt2dpediivz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gt2woaioyzx.html

[L04] 设置超时
来源：http://dali.zhixingplan.top/Article/details/gt2gqkwffpm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gt2tbjhlknd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gt2ogzxaiby.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgvbsqow.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gt2zwalcxsq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gt2emyaefso.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gt2srtbxwgt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gt2cxptjoot.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gt2tftacben.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gt2ndasgloj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gt2rmynvato.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gt2pgahhbxf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gt2hrcvyyak.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gt2iokobpdc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szjnhqft.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sexfgdew.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gt2evoimscy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2kxttezcb.html

[L06] 解析响应为 JSON
来源：http://dali.hnqzz.top/Article/details/gt2pqdmsqwn.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2xhvmmoce.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gt2widdxebp.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2gyrkwato.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrvveiuo.html


<!-- 参考信息 -->