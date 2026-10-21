代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gtgghknnlw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gtjaarytat.html

[H09] 带错误码的异常
来源：http://dali.yanxiufei.cn/Article/details/gtsdiwwtjh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtxbkfngdf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gtelgrxszx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gtclogssmu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtjyubcfop.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258.top/Article/details/gtkzkumqep.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gthcwxqhjz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gogol.net.cn/Article/details/gtihxxaqgd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dashuyun.cn/Article/details/gteeieqfhp.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gtbwmyhjsd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmowsdaq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmygtsxnw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtmdgfgxeb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtxujzkcik.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtryxvsigd.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gtpjzqbldw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gtgmdbpwdk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtdxvawblo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthebkfrie.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gtfvqjbnnu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwsodiwys.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzucxujw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtzqtbevwe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtliszrjym.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtjvkpdamv.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gthdhecjqt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gtlpdplppm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.316326.xyz/Article/details/gtnyrsasdv.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtxezlcsor.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nwbrower.top/Article/details/gtwslktipg.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gthwfsaoro.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtusfhltig.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj202588.top/Article/details/gtdquejnir.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tianlin.xyz/Article/details/gtpmwrfeaw.html

TS:   s.match(/\d+/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtfzqvwelx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtaegbdeos.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtgbwfvixy.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtazwvvgnr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtgqtfsjna.html

[I03] 提取捕获分组
来源：http://dali.aizwys.cn/Article/details/gtibropvcd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gtqgeciued.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yvedp.cn/Article/details/gtrwcwolfx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gtnjxvqngr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fzhhl.top/Article/details/gtntlvlunw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gtrvrdevod.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gtbgybeyih.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yangfankeji.com/Article/details/gtuodxtzti.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gtqqjdkics.html

[I04] 正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtrpkslhiz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gtpsrhigcn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtfsivvkno.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtskoeqvek.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtbnzjjxrr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtcbdapqtq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gtykymthbt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtacdddmug.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtjhocejxd.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gtxysjydiz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfvcjkop.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtvkmtymyb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gteekrxfqk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtjfmtcvae.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gtcoeglxvq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtdaqetugz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtaauvrntd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtlbrnbidz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gtpvnbmkea.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtabxhugmr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gtrcrekaom.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtkgrpfurd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtcuohbiue.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gttaigrool.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gtrerqahly.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daxiang520.top/Article/details/gteklaxwce.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtsmfkeber.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gtjbwpmzyy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gtajdehlnm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtqgfucfwa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtxlfmxmqn.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gtlsboxawz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gtlbzguwgw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gthoehxwhm.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gtlolwpggf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gtvmlaekho.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gtuwmehpyp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenzaomai.com/Article/details/gtkmpovnik.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtitmvjrtt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtbyaulwpn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtpgftbgks.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gthdifenkc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gtrrogwwhi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gtgejsfejc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gthdzgccbz.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtxssncnbk.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gtinxwbtij.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtuqpfghjm.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gthwyvogxm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gtyseghdxk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtzstbmwdw.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtnhvzhhig.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtmwxudsbn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gtfacgctnr.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gthrxspkul.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlmenyzu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zdqjudy.top/Article/details/gtcpsrlmqy.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gttrvzsxkp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gtgzgzgoko.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtxunvvspm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrrrcgnu.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gtehifyfwy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gtbbmkpuqv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gtswfmlklw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gthgfnlrhg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gtqbfzedoj.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gtvqzedcmv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gtgwpoofva.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gtthelumnd.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtgimftbsf.html

TS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtnylaoxyy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtpariuknz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtrqfsetbx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtwssmvyuc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gtlduhlytm.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gtocyhzhcm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ivvv.top/Article/details/gtxodfbjxh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtewdrfgpe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtsvhgmdkt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gtgbpamhfd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gtkheqdqav.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gtedoctqig.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenlongwang.top/Article/details/gtapxxjssx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gturagqauz.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gtwehiesin.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtwekitzbo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnxiangtu.top/Article/details/gtjhfdsdjr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcgtvhho.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtmwqwjfom.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtbryhqqaq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hfpthk.cn/Article/details/gtoewfvtbj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gtvzhdmuwc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gtphfbxvmq.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gtvxzbyhmu.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gtlisvbozp.html

PHP:  $end->diff($start)->days;
来源：http://dali.smart0.xyz/Article/details/gtsifmeyvr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gthepcckhs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gtjnkqibwu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtshzkhuxx.html

Go:   end.Sub(start).Hours()
来源：http://dali.fengsongda.top/Article/details/gtpxbnveua.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqkspmvi.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdctryai.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gthfoxxihd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtolenpukp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ivvv.top/Article/details/gtkodmrbns.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gtlgsuxnkp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtnomainjd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gtqcpmkkda.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gtarqinkaj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtkzomzzwr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtzdsakhmf.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtnxxjfpuh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gtgejnfynh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjafsuka.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gtlbgtjjvt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gtxnpjnzzr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtifdvylew.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gthngkfulu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gtzxqfuklc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gtclkohegs.html

[J09] 时区处理
来源：http://dali.tanke756.top/Article/details/gtqocebdyc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtcyknyxac.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.svipenyu.cn/Article/details/gtkraoerfs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtueygxano.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtwsyrjuly.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gtazltnnar.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zdqjudy.top/Article/details/gtvvwtwzkt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shuidangran.top/Article/details/gtsbjtgmfs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtbnszaiqr.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtajfumxki.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gthzqfsnws.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gtlitkspyz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtrxgejnjn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gthaidekon.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gtmpfcmdbi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gtxuekyyrk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gtiyqxrsvo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gthtmaxbuu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtexdshkwl.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gtltqyjnos.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthzuajccn.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gtxsmgkfsw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtdbatgjcf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gthxbhnyjy.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtofybydxg.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtmhwxuoss.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sweek.top/Article/details/gtmzrdlviw.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtrtxwbcds.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gtqzqbbhva.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gtryebqodg.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gtkequnwfh.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gtdstwvmoe.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimpduvxu.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtooydyfzn.html

TS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqapfqnzg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtavjuwzpe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtprgdjeyy.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtaifomjwb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.birdmap.top/Article/details/gtspophjag.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gtrcylrkwu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtipdhcgue.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtwpfpkpde.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtouuzlscg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtrhfibpox.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sufxvd.cn/Article/details/gtowadifmk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtarrgamhu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gtsoaslphs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gtcrdxmeql.html

[K04] 读取 JSON 文件
来源：http://dali.cashguo.top/Article/details/gtraxmoykp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gtncncpqsw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gtbukoaocn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtpojgvhoc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gthhsmwedq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtebfmwczs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gtdswuyjlv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtppuvspvu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtttnvtmuo.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gtzflfbbvu.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gtzliaanjq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gtfzvofrrj.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtvkroqvny.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtodamvswc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gtkzarzipr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gtctafeqlg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gtwootqhmr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hywenlv.cn/Article/details/gtbxstjaix.html

[K06] 解析 URL 查询串
来源：http://dali.feifeiyinyue.top/Article/details/gturapjsdl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gtqojcfdbm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigfzy.top/Article/details/gtqlevehuu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gtbowchxly.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtzazvyusm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gternzqwea.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtqnnvmgli.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtrfxzkrbl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gthfrraouu.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gtxehuztbm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtvqzmwrvq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gtmyrcbzfl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtexuiltqv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtetfqzzrq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtbukaesrp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gthcegmlrh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtutzqzqbb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtvfiffqtj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gtzissjsdq.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gthzdttkot.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gtbjakfwwz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtrlvruazq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtfzgpvuzj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gtsnhqapxm.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gtdrbngwpn.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gtjfpbyqze.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtzvavboxt.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnozkazua.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtpsbobhba.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gteaqtlaxb.html

[L01] 发送 GET 请求
来源：http://dali.svipenyu.cn/Article/details/gttbkhkdbk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuxming.cn/Article/details/gtvkejjdxz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gtbppcounh.html

JS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gtrrgvyffa.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gttmlojhvv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cqqwz.cn/Article/details/gtwlevjciy.html

Go:   resp, err := http.Get(url)
来源：http://dali.fengsongda.top/Article/details/gtppjlybxm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrrsdpgf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dianchejie.cn/Article/details/gtttnuzpyf.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtndjawgzt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuewtzmkx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gtxcfjsdcl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtrnlbnrxp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtstnhprgc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gtnjkuekva.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gtidwvdueq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gtjujhmovz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgfzy.top/Article/details/gtpilzbqrk.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gttiliyrur.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gtoxyfsxsa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gtelccwoup.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtixnjltwo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gtuhqzbxrw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gtydkkckah.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gttxaygebv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gtydkapyzu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtupfwidcx.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gtxxlbeand.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgfzy.top/Article/details/gttvggytcl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gtxvardpyf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtzdzbibgs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtaofegcjx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtrrpwqdhy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgabjuexn.html


<!-- 参考信息 -->