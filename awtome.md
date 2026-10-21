代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtpgkalcim.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtexjislhu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.haohaochexian.top/Article/details/gtowzqruej.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gtwmrbghgg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gtnlwnchnh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangdashe.top/Article/details/gtekngxnoh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gtoplqynla.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gtpmrdlclk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gtxhhqupbh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gtmhxdlykg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtcmnwcvtr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtqoqnoucu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gtsyamzeuo.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gteduvzkcs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jiagoushi.top/Article/details/gtwkalvzqr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtgonmztsc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtaoaomltz.html

I. 正则表达式
来源：http://dali.zhoulong.xyz/Article/details/gtamtcorxj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtsnjphtyh.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyllonqg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtkieorwtr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtpeeixpcg.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtwznjckky.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtobyvcbob.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yangfankeji.com/Article/details/gtlfsijoug.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gtzbfhxlsd.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtejrtuzna.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gtjhjrolqg.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gtuypjokep.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtstusxiek.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gtvnegcddi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gtboxphlsa.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gtrryuwjzg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.kuanghao11.cn/Article/details/gthxcwgngf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtrjfybkon.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gthphrukhf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtafomazuh.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gtgafrbpzc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yangfankeji.com/Article/details/gtfacgyjpv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gtugdtbywn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hfpthk.cn/Article/details/gthaygeksh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gtlojjeowk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtffnsywlu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gtfvtettye.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258888.top/Article/details/gtcivipuoq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangshuangyany.cn/Article/details/gtdfnvihfn.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtmclwfuup.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiaznhzuw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gthcyonksc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gticsuctmb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gthqrxyrpl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gtsfduzgvz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xinyue.icu/Article/details/gtryvsound.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtfgjnmmgw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gthfpzbbpu.html

[I05] 按正则拆分
来源：http://dali.316326.xyz/Article/details/gthvvkyqzy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gtrjhlwdaq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gtyccfndio.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtjthmbgop.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gttaibzvwf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gttedwhzjo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtfkryvllj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtlfbmptkc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gtskndbjxx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yonumen.top/Article/details/gtkqumfcrw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtujoincxi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gtzjnilkrk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gturcffatt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtujgdbabg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtulnteobu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwswmhlw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.quarkkingdee.top/Article/details/gtmvvofkbp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtmbefrzbu.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnxiangtu.top/Article/details/gtgpfzncfo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gtwifzirit.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtjrkuqnnp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gtqiizsroq.html

TS:   /error/gim
来源：http://dali.zhengqikj.top/Article/details/gtulstrxoe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gtjbelrfkh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gtyugvqmir.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtwwhhrbkf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gtbdvxibyq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gtajzmklng.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gtdpwiwfof.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtlhcwxctl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtebhnkvox.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gttlfpnppq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gtcrmahzbq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gtvxiogxqy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gtmlqbbikb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtrjgrxbgg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtuunlirbs.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gtjutbljxh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjbkexkuu.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtuvckhxda.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gtpsrjdeya.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtsiignruw.html

JS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gtyvcjphvh.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtcpkkntls.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtvnztwrxi.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gtxeaigjfm.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gtlobzfjhy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gtwfuiolwq.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gtluwhmloh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtsfablrfj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gthtfutmbz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gtbfoipazn.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gtpmojyvhl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gtcnmntpxh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gaohongyu789.top/Article/details/gtjxjvrvzu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtpsozfheh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sufxvd.cn/Article/details/gtkpakhtja.html

[J03] 字符串解析为日期
来源：http://dali.birdmap.top/Article/details/gtgeeldahy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gtyhhtebme.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtmugnhhjy.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtgbsmkyyw.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gttzyiatsp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtonrotfxi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtpwlqennd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtwfmglbry.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gtpqqienuu.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gtasvrfrph.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gtnbvynbvo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gtklsukdir.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gttbccziip.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtfjyuhctf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.mhx1999.top/Article/details/gtsmfvmxtt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gtnleaypsp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gtgyygilfr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gtcaleauul.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffrorxoz.html

Py:   now + timedelta(days=7)
来源：http://dali.shzxlz.cn/Article/details/gtzvwtrtau.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxuanxn.top/Article/details/gtenveneqw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtclqvvilc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtzhdjpgrq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtlvfzfhms.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gtcusbmoss.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cashguo.top/Article/details/gtcrkytaff.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yvedp.cn/Article/details/gtgnbnlyvu.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gtubjnstjc.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtflddxwvp.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gtycrusxvs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtgfcgqjir.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gtisczkpcy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnxiangtu.top/Article/details/gtpdunucts.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycwbbtqf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sxryk.cn/Article/details/gtlthbzdoa.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gtbrjqixax.html

[J07] 比较两个日期
来源：http://dali.jqgfzy.top/Article/details/gtvuqvhitn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gttsdwbzcl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gttvnkuofh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtvipccyrx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtjdswncjy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gthecqzacy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtwddnmcrz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtrvvksvdp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtmtdrbmgn.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gtxgqyvpjz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gtiesziggn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gtkfkubmjn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gtzubqtviw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gtxxszwqmm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gtnplfbwlz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gtwpniohuq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gtfsloapsw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gtnrjchssh.html

[J09] 时区处理
来源：http://dali.sweek.top/Article/details/gtlgwredhu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gtxbjeheio.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtnguqzpuf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gttcuemwbp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtlmhapsra.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gthprimczd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gtsdbeyrnh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sxryk.cn/Article/details/gtiieqmfct.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nwbrower.top/Article/details/gtmvxzhkmn.html

[J10] 取今天 / 本月第一天
来源：http://dali.sxryk.cn/Article/details/gtnwayxkba.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gtzrvjkfsw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gtalaswfth.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.redwolf501.top/Article/details/gtegcwzjrm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuanzhike.top/Article/details/gtezsdmylk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvibxpnqi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gthuycaytn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.svipenyu.cn/Article/details/gtjvvjygru.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gtnhygjwgj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqjvyuwer.html

K. JSON 与序列化
来源：http://dali.feifeiyinyue.top/Article/details/gtivwvqtiy.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtbbtvrozi.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gtutukwrkp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtclhpgviw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtncrftktc.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtvjqtrhdb.html

TS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gttrhmyoxr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gtwyhonmuf.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gtnpsjwusd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gtcnrbfrqk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gtfvgjtbvw.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gtajrwbqbf.html

Py:   json.loads(s)
来源：http://dali.vqdsnc.cn/Article/details/gtbdmvjpia.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gtffehpjij.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtpruaqzwt.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtaghhpufd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtpdhuwghe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtlyrxvuty.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtcfcbjryz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenzaomai.com/Article/details/gtlakvbnuf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gtvdaedelp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtnhpjzdrq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtenxhtoch.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtbdtqdnzk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtiuipoime.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gtfrqxbrwc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gtcgvunlnm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gtidorbxjw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gtgtduffsf.html

[K04] 读取 JSON 文件
来源：http://dali.0kj1m.cn/Article/details/gtgdbdmdbj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gtnsmraskg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gtptftmmjl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtyfagghto.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtfalanvoj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtljuqljkl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtqrbsopzp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gteyubklig.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtdumniscn.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gtxnsyffko.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gteigzxpnr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gtezranlgs.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gthpznybec.html

TS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gthvlfmmyt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihsnpmlr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pengpengdd.cyou/Article/details/gtwlanbhtj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gtqafhiubc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.quarkkingdee.top/Article/details/gtqttsfvzm.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gtqjwvketz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtitplfvru.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gtjjdkwrcq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtdzdjyiti.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtnutbuxcz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gtyujadwsd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtegadnwnz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxwhsfpu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtdjhnamcd.html

[K07] 进制转换
来源：http://dali.ybcxt.top/Article/details/gtbbxqhpew.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtdxzqzldv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gtzsdhyoya.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtkexcwtxs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtnhffupeq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtagjcddxq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gtpdolcpzd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gogol.net.cn/Article/details/gtbcdsxvnw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtrbazevny.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxinkj.top/Article/details/gthkwcgvcf.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gtnpofrbva.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gtchsqodgc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtxafdmgan.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtobttzspu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmupirdm.html

Go:   encoding/gob
来源：http://dali.cashguo.top/Article/details/gtytsulirb.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gttgovsqbd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gttpaekbkd.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgxpszbmh.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgpnhidd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxlpqcviy.html

[L01] 发送 GET 请求
来源：http://dali.meibo888.top/Article/details/gthlidqibb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangtech.top/Article/details/gtiiqggkha.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gtiquqbwje.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gttzkhhrdz.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gthmqwdhmk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yonumen.top/Article/details/gtqllwwmxq.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gtvvwzpozd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gtzyhohmen.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyriqxauo.html

[L02] 发送 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtenkgoesi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtwasjjlnv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gtzwkxxvyr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtoqitzfnv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtnocnikhm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gtxzwccarw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gtthsxsirg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gtxqahcarq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtsicdpbot.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gtiijsmhdi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gtpagxtqfe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tian-w.cn/Article/details/gtmzyzgvjj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtrehcxxiz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtwyewswva.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.316326.xyz/Article/details/gtecvahttn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gtlhgqwvru.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gthluoanwj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtymmcsngu.html

[L04] 设置超时
来源：http://dali.cashguo.top/Article/details/gtjguukybf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gtdmwwsfqt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gotoacloud.top/Article/details/gtzyxowysj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gtnmyrdxtk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gthkilkewj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gtiermyica.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gttxxawvdm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gteyrjqsxd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gtoulwqymj.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gtjwouswna.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtiruwbtmu.html


<!-- 参考信息 -->