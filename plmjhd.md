代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxinkj.top/Article/details/gt2kewrxhzy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gt2jwnrshms.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gt2jfbohtzm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkczmjma.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gt2skywveea.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gt2yerxwnpp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gt2zvscuwzj.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zgaperci.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gt2injolphf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gt2uhltymxi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gt2yrhrpczh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2mpkynhig.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gt2vnnvmgfz.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gt2xklakdxl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gt2gowdftmy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2efkpifse.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2sgopqpgt.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2qpldtpia.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2sovjdrjn.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gt2yqcsndqo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gt2sxzecxhe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2ieslhggr.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2kqeozizz.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2nxtsslrb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gt2mauekgjp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gt2hcxffjxp.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2jkfudmab.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2nhljhfou.html

[I02] 提取所有匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qnycalis.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gt2wgvesysz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gt2xueomfcy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gt2riqopeal.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gt2teyrsgws.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gt2pexxzdvi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gt2ppdygqgj.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2dsvsmsop.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2axelpdtp.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gt2dtlsjixk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gt2ewgjpsfl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gt2ftijawko.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2fqejkhpq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gt2hihirgco.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gt2odiasljr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfssqzd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gt2gchdhkuc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tianlin.xyz/Article/details/gt2lixaxbbj.html

[I04] 正则替换
来源：http://dali.zhengqikj.top/Article/details/gt2gbhkdvtp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gt2vnssqofi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2dnwmfwfg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yrwfkzmi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2qzhaqwyp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gt2ooifevfw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gt2fsswpcig.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2hxsppmbt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gt2detxrmrh.html

[I05] 按正则拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brhzggna.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gt2cgjjneer.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ogwumzsj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2qcigdezu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gt2bygbeuyb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gt2cbnbdxzx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2rhuyyxuv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2ozppyxip.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gt2gtmkngbv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gt2wwqgvwms.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jinbzbdt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gt2ptmqpmrh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gt2tccuaaat.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gt2hrjnyoee.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gt2zupcmwud.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gt2sfucfolj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gt2lntbbaqo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2zfppblcp.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gt2bcvsxawq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gt2tztjofyh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gt2pblcrvfk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.svipenyu.cn/Article/details/gt2tivotrmh.html

TS:   /error/gim
来源：http://dali.jqgufenzy.top/Article/details/gt2vplbjhkv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gtfecabf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gt2dasziwbo.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrwhztcm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gt2yecgljse.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2yslefdeq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gt2likwchds.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2mupnbrrm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gt2fmcgeyhy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gt2acjufwqd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2mklriwgl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gt2qicnznqh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gt2zxbwvpqj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2rrjzjmnw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2juoirewy.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gt2vopoejdd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2emsaettv.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gt2gwhxmgid.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.havefunace.top/Article/details/gt2fowkbfbz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gt2livzsgdc.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gt2liosdpqy.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhlhrvvt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2zzhgkaqg.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gt2tybefwwe.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gt2qapljvil.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gt2yuabwyda.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2ubjuszzt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gt2gsuqklst.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gt2witdyoex.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gt2nefvtftq.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gt2ckvrubxr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gt2mhyumbef.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhjmlcj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2nwqwziuh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhzxqert.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gt2pzpwfmvu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gt2cdpeqkho.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cheryme.top/Article/details/gt2lrbfmjtd.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2juuqmnrc.html

TS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2iydvlwbw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2rctummld.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2xyrfgijm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2rhfdmubu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fzhhl.top/Article/details/gt2clltrlaw.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccsupuuc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.smart0.xyz/Article/details/gt2fizyywty.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gt2oyoumpnh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gt2qsmwdelm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gt2tmsmznou.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pycfn.com/Article/details/gt2uqcotlut.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gt2gxournri.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2hzdwcmwh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2lqltpjun.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gt2ugtqtdot.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gt2wzksmgpz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.9152youxi.cn/Article/details/gt2myhibjgf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efkupvrv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gt2jxpjduuv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gt2krrabvbk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hammf.cn/Article/details/gt2rjosumzk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gt2bgwephcp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gt2zpthckdk.html

[J06] 计算两时间之差
来源：http://dali.gogol.net.cn/Article/details/gt2dbwxlspf.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gt2tfrklmzs.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gt2bzktcilb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gt2ogvcrqwn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gt2gzaitdrf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqfaiind.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gt2egyvoeno.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gt2ticmipij.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gt2uhmxevuk.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gt2lyzbqjid.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2octxogbe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gt2dqczwszi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gt2seyctxxb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gt2kolgtciq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jyoumei.cn/Article/details/gt2nxlgwhwa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gt2tywrhixj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2nfghayrr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2mswyvjwu.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gt2woywcqob.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gt2overanib.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gt2pqjijkri.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gt2wvoabrzj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gt2qsafisah.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gt2prutptbz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gt2rkwdjwmz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gt2jryttswa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gaohongyu789.top/Article/details/gt2xjvurovi.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gt2sxkvbnwf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gt2uijnkojt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yongpay.top/Article/details/gt2cszzccah.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gt2oihblbeu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gt2zjiypnyv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gt2xzjqctvp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gt2bdzjdjkr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gt2lyvznkwu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gt2uynkjcdz.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gt2kcogxurk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gt2xvovxdsx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gt2ipyigxko.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svddrdpm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2cvfipcdx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gt2abzefcpe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gt2qotbbokg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.svipenyu.cn/Article/details/gt2boeeexvx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gt2lvdnanyi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2rkxnsnic.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gt2maykmqqh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ohsyxlgu.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gt2ihffwpfo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gt2elseakdy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2fppdnoia.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2iwcbknik.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gt2qdooxzfh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdovyycv.html

Go:   json.Marshal(obj)
来源：http://dali.xziqi.cn/Article/details/gt2alddihmi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gt2gszqhdmv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2vwbqxdzo.html

[K02] JSON 字符串转对象
来源：http://dali.mhx1999.top/Article/details/gt2sgrpoerw.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2bjcysqfj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258888.top/Article/details/gt2tiqriguf.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2mszhykrs.html

TS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2fbuvponi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gt2salhhcum.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2qawgovtg.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2afqpukcp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gt2hatlutvg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gt2wfxvoxoh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gt2abkphvom.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gt2mvkqovaz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gt2imvkvrkk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2hkyfxigj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2orrgoidy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gt2gbyntdwn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gt2knhstwxl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gt2kcmhqkws.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gt2srhbssot.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gt2suevxkqa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cgcxzgjw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2ezgjqing.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2wzvcyxgf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2hmtzyqqi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gt2pliiynny.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gt2ofiotkgz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gt2cxhmfxxb.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xeezqkga.html

Py:   copy.deepcopy(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2ihuqdwqq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gt2xusdrway.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2marmfnby.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2uqasbzmr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gt2ugjgpskt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.andypj.xyz/Article/details/gt2yoqbwmjz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvbeiuxa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fzhrjmej.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gt2wkwlrkmw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nwbrower.top/Article/details/gt2zkxjwddt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuanzx.com/Article/details/gt2wlopvbny.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gt2dsylbhxq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2ulouxcsh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gt2godkzesv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2qdxhnaiw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2zqdmithv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pfgfxufn.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gt2gfmzqmet.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2xmcwvqii.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.smart0.xyz/Article/details/gt2ooplgqlm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2urdenfns.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2umbatxte.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkivwnoo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xziqi.cn/Article/details/gt2oniyzkht.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gt2byfdnepw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2ourrhywe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuetiantiany.cn/Article/details/gt2gnhoxlio.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2jdkwxdcr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2njixujsj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2fatnjbhz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gt2bqimqyma.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gt2sbuvdhrm.html

Go:   encoding/gob
来源：http://dali.yj20258888.top/Article/details/gt2bsjhxpbb.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gt2gqromwfi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gt2wbocqbve.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2bcskegdi.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gt2wzmclrgy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2weozxysw.html

[L01] 发送 GET 请求
来源：http://dali.smart0.xyz/Article/details/gt2oqkumnjy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gt2yfklinzo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gt2lhthrsdq.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nstvhrup.html

TS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gt2lfyyxlnl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gt2cwipniwo.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zzauwvmd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ydzc1.top/Article/details/gt2qjewgyuy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gt2ajrehlsj.html

[L02] 发送 POST JSON
来源：http://dali.fzhhl.top/Article/details/gt2vheonfvg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjucbxzm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gt2btrahkmr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2gtvzdlfw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2etnyrhxw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gt2jzolzyim.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cqqwz.cn/Article/details/gt2pxjqpcrd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.bjfxy.top/Article/details/gt2qcigvtiw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gt2ftbfzgpz.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gt2hwgramcp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yvedp.cn/Article/details/gt2grjyimjt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gt2uranaihu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gt2lcdcrrmr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gt2txroehlt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zosrdrfv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gt2pysxjjyl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gt2koikidhp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gt2behsqinw.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gt2szmwynux.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gt2tjqxabux.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gt2fexyxoxl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gt2dcwgfbzg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gt2ydukokzi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ydzc1.top/Article/details/gt2vunyeqqr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gt2cuuljcrh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gt2imnmwwcs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gt2fjsmbzbw.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gt2trhmyqdy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2seqwdyvf.html


<!-- 参考信息 -->