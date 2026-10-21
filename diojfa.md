代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtadvabazq.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gtzmyhoczq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gteqjhighh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gtcqoiccrq.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtzpnhryel.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gtfrqcjdxp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gtjbafzmdx.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gtocvtnjrw.html

Ruby: e.message;  e.backtrace
来源：http://dali.hfpthk.cn/Article/details/gtsbdxmyjl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gtehjwwkbe.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gtifidsyiz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gtekqcbaeg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunekrurd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gtbuqskkrq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gtmhrzfoig.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxndmemqo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtpnijiizd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gtuuikeawd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gttbktqxpf.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gtezkseiyo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtuunsoqxa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.redwolf501.top/Article/details/gtfwycbbzx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtbrvexpnk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtpjrgqkuv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtxmdkosoi.html

Go:   defer f.Close()
来源：http://dali.sweek.top/Article/details/gtvxfzplsn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gteshahary.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtkhlqdxjn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwrgkderf.html

I. 正则表达式
来源：http://dali.yueranfly.top/Article/details/gtspmgrtfe.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtytnmlfkv.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gtbdeiizxq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtuhabtizm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtthzycmrq.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtylqmskmy.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gterratbmd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gtgehzobtw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gtadvkrnkc.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtaouljygx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.smart0.xyz/Article/details/gtueinshti.html

[I02] 提取所有匹配
来源：http://dali.0kj1m.cn/Article/details/gtdexcoqbs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtmxykomdz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxinkj.top/Article/details/gtbedwoilq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.9152youxi.cn/Article/details/gtopggbopu.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gtmzwfmptt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtwnvxgxpe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtqrfxoasp.html

Ruby: s.scan(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtkgtqrvjv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtdfdsrbrt.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gtipjzvmmv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gtjqctkgrh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nwbrower.top/Article/details/gtmhculajb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daxiang520.top/Article/details/gtsiishehq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gtjfifeegd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gtegtcgghg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gtheoeyssh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jianghu66.top/Article/details/gtvrugvepb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gtobiuozaq.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gteoctaxxw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gterdngqpl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtlmrkozdz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkhazzvz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gtoswvclmw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtboxpllhx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtawxevdji.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gtttqglnls.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gthhoxrjiz.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gttprcwsbb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtvkfdqaed.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtemkhzghs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtnwosgina.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtagsvicku.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gtobxqltwr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtznkuubme.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gthgxkeljg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtwgmhphgi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtbluefz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtjulayzob.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhoulong.xyz/Article/details/gthsfbrqvv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtrtasveko.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtiugqljsd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtxtoiyfjc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gttjjihlxh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.quarkkingdee.top/Article/details/gtefpudmrh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtzfgzkrtu.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gthkegrwqw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gtcgqsylig.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtnjhpktlc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gtcqiqpitq.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gtdsfwpfgw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jiagoushi.top/Article/details/gtcvnrfvve.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhengqikj.top/Article/details/gtuikkxbea.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gtnmxffacz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gtbhhuccwi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gttrzylbhb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gtwwuazpoc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtzsqboflm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtzdotxvvn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtvvrobett.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtfnbecgkr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gttdzxyxlv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xziqi.cn/Article/details/gtkhcvaopk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtulcocvii.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfrfyofwb.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gtcsixgmqy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtllrxfsod.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gtjzmgcudo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gtqkfcynyj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtjvkoitwc.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtuyvvqhqh.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gtzwrygmbz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtqlzygrsm.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gtddywypia.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gtyyxwjjhd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldeysgqi.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqzsydbu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtroatsaoh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtugnpsijx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gtvegzpmzr.html

TS:   d.toISOString()
来源：http://dali.nanxuanxn.top/Article/details/gtvrvspuya.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtpsnrkszq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gttbfslmeb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtfiiwxnzv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gtfpidmcac.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gtyunaximk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.redwolf501.top/Article/details/gtncncmbld.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gteesjmpma.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtwycnwgtv.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gthkaiycav.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gteyootlzl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtkjrrthpk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtglvdgmqn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gtnbrgzhjd.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gtkxdqvbre.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtxshzgzsq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.svipenyu.cn/Article/details/gtzbdfjnti.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gtpcqqtsti.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbagvary.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gtbmmcmotj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gttzenvplo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gtmpkbcxcz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtupsuawis.html

[J05] 时间加减（加 7 天）
来源：http://dali.zycfv.cn/Article/details/gtjuwymbvt.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gtxkskidhc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gtvvvppnij.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtqfgbxdnv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtosjwbqkk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gtmebjdvfe.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shuidangran.top/Article/details/gtmzvuuknc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gtyehshotm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsefvrtj.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gtudqqaktn.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gtmnvazldr.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gtkuzwcfqf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtiiamvggt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gtkhgqwiag.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gtajmsluau.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gtmmlgchzg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gtenwwufvx.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gtuznnwfhw.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gtxcslsaso.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtahiomdos.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtylubvmdk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtcuqqgfrh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtdqxmpvnf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtajwnjiwk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gtvuuzobdc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtrffsqfko.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtylpguhnd.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gtkzwmidyk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gtoftdjddf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gtdnvtcwfp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yongpay.top/Article/details/gthyjsziqv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gthodxhsvk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gtzyotugns.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ppjwa.cn/Article/details/gtchoepyci.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gtmlfinyyj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gthbabhwkk.html

[J09] 时区处理
来源：http://dali.sxryk.cn/Article/details/gtetoajjmp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gtayrtgbtj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gthgcnvgjn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtekugadea.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtlxgmmrmq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gthdwwrmov.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sweek.top/Article/details/gtwhwpllkz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.meibo888.top/Article/details/gteaqlgqit.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gtltdnfzlc.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gtejkhobbc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.haohaochexian.top/Article/details/gtjlycvabw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gtlmkfdysd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gtnkrygkjb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtuxvkmcno.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.quarkkingdee.top/Article/details/gtljjjtsqe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangshuangyany.cn/Article/details/gtoaqcwdny.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gtfmpqbulg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtixmfrraw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqbkezwez.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gthvjckrhu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthnhuskcp.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtdnitsbng.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gtrieesnig.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtecfovqsu.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtnqixffza.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtnmqhcset.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gtfesgxgpl.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtghuiejps.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gtxewnrbyi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gtnikqtgon.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gtxuswxgyy.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gttwpeokzg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqbxbfqa.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtbutyisql.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtmjkqvpma.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gtfnselfxp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtkhxiceck.html

Ruby: JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqahgowu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gttsknrnyb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbitpgcyf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtubljhqkh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtxqaesbsb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtwvkseyhf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gticdlcwtp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gtqtbyqmfl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gtdhjdoeqy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuanzx.com/Article/details/gtpxeiyzfo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gtwwzqfuhl.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gtfigrpree.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gtujqwurnb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gtsrufljnb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtvdkfsjwq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtaiwbzpcz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtzyjfovsd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtrtfvvydi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtuygejpod.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtzmtbvbtj.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gtyrqruyoo.html

Py:   copy.deepcopy(obj)
来源：http://dali.redwolf501.top/Article/details/gtamfrlpep.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtkzwjuadx.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtjxiibjxs.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtzopudjyf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gtnuzootju.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cheryme.top/Article/details/gtxgmktbkl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtybbojkkw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhengqikj.top/Article/details/gtfdtxsvem.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gtumvfpjps.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtubsmdfkx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gtaoblhhjo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtqnrrfdws.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtwvesbehh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gtjlvpqefq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtdtsefscd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtlnnluaad.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtjycrmpai.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gtjhxnwivi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtuinaqszf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gtfdykvpil.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtksfswjws.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtdqpcnjzn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtvhiowtwg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigfzy.top/Article/details/gttvmkvcyj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gtxrenudvg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtkxfgtevv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gtodqoadzz.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gtmxpxmfac.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gttmrdkvby.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtqcdqchfn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtmbrercqw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xylfe.cn/Article/details/gtxeszqbhd.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gthbghuspo.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtalokqrwj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtgqejnlof.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttfnwobow.html

L. 网络请求
来源：http://dali.hnqzz.top/Article/details/gtmlaqifqy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmlipxser.html

[L01] 发送 GET 请求
来源：http://dali.svipenyu.cn/Article/details/gtoebscwrh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenjidiqi.icu/Article/details/gteicylxqp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.iojbl.cn/Article/details/gtjdqsyoit.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtamwrttvp.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtzlrgbpzq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nwbrower.top/Article/details/gtxugugzfu.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gtlsmtrjuz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gtcadqacef.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gtbhakeybv.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpcqehus.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gtadamnhnx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gtwilvxthd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtwdbyyhdk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtggdiiehz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtolrorvps.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgufenzy.top/Article/details/gttakgnhvy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tian-w.cn/Article/details/gtzcgerlke.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gtwbertmud.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gtvnyhjscg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daxiang520.top/Article/details/gtlobqbser.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtyrferphg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtvngbyjhm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gtieznlnlk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtkrpnuuii.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtrcditwuo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gtxytebpga.html


<!-- 参考信息 -->