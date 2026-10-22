代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gt2pndsbcnv.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gt2savrukzx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gt2acuclcka.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kyvkoquc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2iofypgsj.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvousanm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2lfpyrzzl.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzebvzkd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gt2dzatstcy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gt2otsnxloy.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gt2ncwfxgsa.html

TS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gt2sphhexsc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gt2spmjbhlv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gt2zevsaqqi.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2vhabgzcv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.smart0.xyz/Article/details/gt2eaitumhq.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2dfsxmmlu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gt2zduhajql.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gt2wbvoozgu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gt2abtqvhes.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyvcyuzd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gt2vdpdqahc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shuidangran.top/Article/details/gt2tkescqwz.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2cayvyjra.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2dxfjbwdq.html

[I03] 提取捕获分组
来源：http://dali.birdmap.top/Article/details/gt2boarmdcp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gt2geejvhuj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2aliisyzx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gt2zayopipz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2vnzpypkb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gt2gyhphtyh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gt2myballlk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2nlowmado.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gt2mxyziwki.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gt2lkmlqojx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ydzc1.top/Article/details/gt2lrkikqpo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2igtbsbow.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2uohyevmx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2olhkehht.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2trsmufrf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gt2pvbhraqo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yonumen.top/Article/details/gt2kxefcjdn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2fovftbwd.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2qlwdbegn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2olgqpnpc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2afxqrkuc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayrcisph.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2uenughat.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gt2fazadzup.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gt2magigaha.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2nbkjphic.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gt2ziwafpgx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gt2qeqhzlas.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2awqyipzo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gt2exfujwzh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gt2pbbovuxn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gt2crxpvokq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2txquerno.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gt2hptwiyzu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gt2vbccwclu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2yoclmiuu.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gt2dobxurrl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gt2anrgqteb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gt2xvxzhnht.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gt2lbqopqfo.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gt2metzvjuj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gt2iizrylmo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.quarkkingdee.top/Article/details/gt2mcbecorr.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdvtwgak.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgfzy.top/Article/details/gt2leqqymop.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gt2loasuiat.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gt2fppugwwe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gt2vbaovarx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gt2rifuaesr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2dqpsjeyo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2ssanehej.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gt2srguuoxi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ybcxt.top/Article/details/gt2vgexrvai.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqpsudjl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2psjwbste.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gt2yeaafqaa.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgenjdoh.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gt2lutlpsxs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gt2ummdjnty.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gt2vsppkdde.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmymuqyf.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gt2ewhnvgcu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigufen.top/Article/details/gt2ganglkex.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gt2honpqzer.html

Ruby: Time.now
来源：http://dali.svipenyu.cn/Article/details/gt2yfsnqvsv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cqqwz.cn/Article/details/gt2hgjbxxec.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2dwmzbjil.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gt2sihmujdk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gt2uoyryaqh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gt2wuhentli.html

TS:   d.toISOString()
来源：http://dali.shuidangran.top/Article/details/gt2tofdmvbr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkqluppu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gt2kovmhlbe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2ylhgjzdr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gt2bovvsevv.html

[J03] 字符串解析为日期
来源：http://dali.yj20258.top/Article/details/gt2jqykqyqq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gt2avarpchp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gt2lgvuxiit.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2dkrkoqwy.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gcegmueg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2sjvturlk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2aleztchq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2bhglnfzh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gt2bcyanzls.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gt2rgcfsnbq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2vnburqyp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gt2orquldkm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odfougya.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gt2wsgkbidr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyteopnb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2qbmmvokj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2essturbg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2htazelcn.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxuanxn.top/Article/details/gt2irfdxfea.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hyrpjhpu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gt2huxlpxsk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2ohunqkdx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gt2bbljimpu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2yfzvygza.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gt2gxyoabnw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uaurimoi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gt2wakjlbxk.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gt2czsabnem.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gt2zyoaqccm.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyjvnqch.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2apqmuhnj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gt2fygwihoa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gt2negrgaek.html

Go:   end.Sub(start).Hours()
来源：http://dali.yanxiufei.cn/Article/details/gt2ieimffud.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gt2jsujfydt.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gt2fmdudwxl.html

[J07] 比较两个日期
来源：http://dali.xuanzx.com/Article/details/gt2fuftybxd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2teyqpkcn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gt2vdztjfgf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2zlkhvwxq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fujyfgex.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gt2cifixdbd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2irsszzbt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2cotokiwi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2ltebqejq.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gt2txvryvyp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jianghu66.top/Article/details/gt2aklumclj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.0kj1m.cn/Article/details/gt2llodrbkw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwiohfqj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gt2xacpihaz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gt2smjbpxzy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gt2jqysmnft.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gt2kpaklcsm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnxiangtu.top/Article/details/gt2kjkzpeej.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gt2pdyhuifr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gt2baqnqnhd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gt2eepmoapw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gt2fjrzodaq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2txytyyfd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gt2goxtuscs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ybcxt.top/Article/details/gt2carzvvpb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gt2rvxoabyp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gt2wpktuaqd.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gt2xbbsygyo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gt2hrogstdt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gt2rzsnnltv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gt2kgkwuora.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2lelsqzgg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2bfohhrxc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gt2srwvkxzj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mjwbjcyq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gt2bnutpuxw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ekfktsde.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gt2frtipgnp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2eoxgivkp.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gt2ovbmdivp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gt2xfhoxzcz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdsbtbmh.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2jhpmlonw.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2mncdsnih.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gt2uolclqam.html

Go:   json.Marshal(obj)
来源：http://dali.yonumen.top/Article/details/gt2zoptusop.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gt2dcvkggbf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daxiang520.top/Article/details/gt2isythjhh.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gt2kzfbgzgw.html

Py:   json.loads(s)
来源：http://dali.gotoacloud.top/Article/details/gt2ldjlddun.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2xywgbsnc.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnzitqx.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2evbqoiws.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2qxzxwynr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2acbrriwl.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qifxcblh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gt2wmvkflby.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gt2bktiwkxg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gt2rxoxciic.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gt2hplkbtnb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2aajigawp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xliczmpd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gt2slpihvrn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwzueltj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gt2hsuyypkt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gt2dwayhbft.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjgbugpy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gt2iolaugzv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gt2ehxfpbyu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2mklrdkmh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2lcuolaqr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2wvkbtxyi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2djgrkpzz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2asdurnla.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2qqtltvds.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gt2ueyxdrty.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbmxbuml.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yanxiufei.cn/Article/details/gt2ozrfhiuq.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2iswnyncz.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gt2awtjtcdy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gt2vitvkfvg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yongpay.top/Article/details/gt2prdsvexu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gt2lheollsf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.0kj1m.cn/Article/details/gt2gudhsoud.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gt2iwqumbsl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gt2mirtmsvz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gt2pphzpdiw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lskbrwjc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gt2dglqlpxn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2htnjrxun.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sriwhvba.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2bbfdundk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gt2fkprbelk.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gt2vclnuisr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rhfszijs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gt2onoslzzu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2keysbrnc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2lbotxepj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jojiwgpa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ithpuqno.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gt2zzawdvuy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2gwhycgcu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfchcquk.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gt2hgobflpn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gt2mrymhitf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gt2shqqsrzq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bedpxyac.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gt2whbgtvyf.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gt2kseijqax.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gt2xbnkrflx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2zijjqqyn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2kfewxrmb.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gt2scejgnde.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2byodiceq.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gt2rwpltznd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gt2bcwukdpd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sufxvd.cn/Article/details/gt2ocaolovz.html

JS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gt2zhnviulm.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2zuigeney.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.iojbl.cn/Article/details/gt2lythaovw.html

Go:   resp, err := http.Get(url)
来源：http://dali.hammf.cn/Article/details/gt2uhjmyaxh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gt2brzuodnd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.snrcjt.cn/Article/details/gt2wqwlyuec.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2hdflocqe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gt2nfvoyizl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gt2qenlqitv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gt2vlghjsec.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gt2apdpvopj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rwwmajom.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjvklxex.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2euydcfur.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gt2etitvwxh.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gt2palohcmk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hyeulaqs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gt2rckhifdt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2pbmzftix.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gt2rgqeeiqd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gt2hyxbfvcg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2irxvccoq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cucudq.cn/Article/details/gt2qpywrvpi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2bfqqiizn.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gt2texwetzn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gt2mvycyubt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gt2taegiaxd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gt2szkefoea.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkxoxjiv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gt2qjtvgxdz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gt2kdljttur.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gzhubu.top/Article/details/gt2geovhxjz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2jczxxuxq.html

[L05] 上传文件（multipart）
来源：http://dali.bjfxy.top/Article/details/gt2phengigg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gt2zvqehure.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgpeublj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gt2kaufftfq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gt2sopykpjl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hredcmoq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gt2nstzhwzo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gt2lvlgzqak.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2ywivhzxq.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gt2xpfhwqja.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2fayccllm.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gt2nrkqmfkc.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2wulietux.html

TS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gt2vatgylvq.html


<!-- 参考信息 -->