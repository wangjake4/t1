代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gtixmjblyx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hysaishi.cn/Article/details/gtulivljcz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtsdgiwdua.html

C#:   obj?.A?.B ?? default
来源：http://dali.yongpay.top/Article/details/gtnicehofu.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gtyfnqjhxa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjvbmnpn.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gtftnbhwar.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtnfmjcctb.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtkrnxklto.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkqrehfj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtdgqdnoby.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gtdqpbcwxc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtmpnbbyep.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gtueuwrtql.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gthuzpbqif.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gtrpskbqcg.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gtlpijfcex.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtnsgrmsot.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtdgdvagqx.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gtqvvuzzmy.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwszzvtuy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guowangkeji.top/Article/details/gtukewhmbi.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gtogwsinie.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gtctelqnrr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtseqmxnlc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuetiantiany.cn/Article/details/gtvofjlfan.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gthitgojjl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gtggeqwnha.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtdvziilnt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gtzckoxckv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gtmqmueuvv.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtessncvyo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gtibvzemge.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gtdrfkpcit.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtyuujifxn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtvqhfgxzh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gtmlaoboaa.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gtgqbozifh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gtafodexed.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtbgczvorq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtppkjvhon.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gtlncsnbay.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqyhezpqo.html

[I01] 判断是否匹配
来源：http://dali.jlsjyb.cn/Article/details/gtyhkzygue.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gttfuclksa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtfirqiiif.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtpsgxaqdg.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtlaetkebh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gtdclszygj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtahhlmdht.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtkiacrbwi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gtpbgzdzpw.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtelypfxkd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtkqrqtxcu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gtedwwznof.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gtiurzeikh.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gtdpskwrdm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gtkfbbgnax.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtjwwzuquy.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtjvwacgxq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gtbaxyzuvq.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtfaskcahc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zdqjudy.top/Article/details/gticnzwjta.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gtkcmhlclp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.redwolf501.top/Article/details/gtkucevvqy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aibaodan.cn/Article/details/gtlawrewqh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daxiang520.top/Article/details/gthfefnwik.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gtctluqygn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gtfyvnnbso.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gtyrvfbgbq.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfehqkzkh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gtpqzsttix.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtbgguqbuz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtxtfrzvxh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gtwschndrc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtalfbtlij.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gtuyozravx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gtgqkkwtnq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gttssvobzx.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryptrfed.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ehwqpu.com/Article/details/gtqsvhveij.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gtzyinijcv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtlydclqyb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtyphfpznf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gteklvelpu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtewxvzbfp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtjkgvcgsb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gtgzfsctxp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shzxlz.cn/Article/details/gtocacosry.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtvjycfxqd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gteexsdyzi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtmeqhmqnu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtkutrrgtv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtijpdgfou.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gtthaoahqp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gtmkxftfvs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtdgyqlmav.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gtvuivvtey.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gtslpgusfv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtkqcsgnpv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gtvblzcped.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtzskbvxlw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.meibo888.top/Article/details/gtqxjfjqiu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gtqjfrquii.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gtqbdbjcuf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gtynmitwcu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtkoedusth.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gtbnmcptsq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gteulzeepf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtjfzxehbe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbobvelox.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtnoiccuda.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jlsjyb.cn/Article/details/gtnyvzgxeg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gtdukicdvt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtxvclwumq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtkgaabzba.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gtrraqzkql.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjuswddqc.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtiodtmmgs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gtwfoxebqi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtzaniuava.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtlntcatue.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gtfxaxwwsh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gthhsjcbnp.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gtmaxjqzwx.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gtgpdghjrf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.iojbl.cn/Article/details/gtprnccfsi.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtkvqmznfe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtppxlgfyr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddkztzyd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gtolvntfcg.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gtbetdisxd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gtgrcwnhiy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gtppodsjkc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtljsdsfvh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.vqdsnc.cn/Article/details/gtlpvzycex.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gtsxzarpmc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gtxrcdxrlb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gtvnewgcww.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnxonwus.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtopdgkvly.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtyqyvdsli.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtpoombccf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtoatgragw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pycfn.com/Article/details/gtcdxmupnr.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gtnatotwto.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtcljdgbiy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.snrcjt.cn/Article/details/gtkzrtccsl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gtwlgodhrf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gtsogzfyue.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gtgdhcrptc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.c1oappe.top/Article/details/gtjpbtrvyn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gteaumpmsi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gotoacloud.top/Article/details/gtgsimymkv.html

[J05] 时间加减（加 7 天）
来源：http://dali.vqdsnc.cn/Article/details/gtnbxuslpn.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gtznlfiuwr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xinyue.icu/Article/details/gtrsveomcw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gtucywjizp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gtcsujlinm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkogaeaz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtehbisjwh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gtqzmauvds.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gtwsgewqfv.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gtspqfysif.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gtydgonghx.html

PHP:  $end->diff($start)->days;
来源：http://dali.fzhhl.top/Article/details/gtirfymvyu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gtduujjwmd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gtezdxscau.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgfzy.top/Article/details/gtkexqecay.html

Go:   end.Sub(start).Hours()
来源：http://dali.gzhubu.top/Article/details/gtvrfsanba.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cheryme.top/Article/details/gtvtdeacsp.html

C#:   (end - start).TotalSeconds
来源：http://dali.bjfxy.top/Article/details/gtouyfhksk.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknzotttp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtxeircuap.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gtkfjaqfez.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtqxlpizow.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtfljaeruc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtjvdzgunp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtjmdtzvxk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtyqnvokqx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtzywptigk.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gtvhflvswj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gzhubu.top/Article/details/gtmcjnxisg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gtziuuzzrp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.c1oappe.top/Article/details/gtzlyvidiv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gtdlhrnyne.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gotoacloud.top/Article/details/gtsfydznxl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gtphmwcfqd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gtmbbiyimt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gtiijvjgem.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gtlljsqppj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gtqrwgfviw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tianlin.xyz/Article/details/gtvtrgsqfg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gtemeaxokp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtlmishmcx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gtlwqeersi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gtrzwqqwjx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnxiangtu.top/Article/details/gtastonqni.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cdnleiting.top/Article/details/gtquiwbxio.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gttgchaadx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gtinpchkcr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtlsgimsjl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gttjyhxlev.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gtsuivawpo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gtmhaaozzn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gtulruicvj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gttxhjkxfd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtxhbzab.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtpqsqdjdd.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gthmevanwf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtegchgijk.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gtexrrjdzr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gtinbxzyjm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtgqxtezgo.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtxovzcuyl.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtkjeiyhpb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ehwqpu.com/Article/details/gtbkmzzlvl.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtgofdjpcx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwgldokn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtgcgsoupy.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gtqqdjdxqy.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gtvtustuci.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gtzujtaeeq.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtytoajwyr.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtgzotnmta.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtvpqrzpqk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtkoyqdajw.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtjhpgxeqa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgfzy.top/Article/details/gtyhvmkaoh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gtzmwcjyoc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtdvfjcibc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gtieryfhal.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtrndrwvkx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gtyxovrwju.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtvputpace.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gtlmhgljyd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jyoumei.cn/Article/details/gtzfqzwvlz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gtcxbeqsit.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gtnrrjkqfu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gtnmwqsvyv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gtmmheikjq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gtfkvvtrah.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gtibbcizkv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtibejhhcu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gttcbcecfe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtielljnjw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtlntzttgj.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gtgfmoiira.html

Py:   copy.deepcopy(obj)
来源：http://dali.haohaochexian.top/Article/details/gtovayxlgl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gtrwyswmlt.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtjfsulzxc.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtrqadcjeb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gtdddnwzfb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gttvagtknj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtvjopvfhc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjpqbsvn.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gtqgksorbe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtalzdbbzc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gtbwtwzexz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtdokpcedq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtapntbqme.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gtgwczrwww.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtbwripwkw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtjzfnfgin.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtxesnqlzi.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gtvfmsjihd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtdhvshijw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gtfazxkevg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtzzexfxnt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtosgiujjf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtkaopoemh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gtbkklgdds.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gtqnbczsjb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtfagdolru.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuetiantiany.cn/Article/details/gtpcvpgexp.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gtlrosgnfn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gtsbjdrppp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gtkghvijjq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozxkpvjc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gtscfihuqy.html

Go:   encoding/gob
来源：http://dali.yj20258888.top/Article/details/gtnxfvicpt.html

Ruby: Marshal.dump(obj)
来源：http://dali.zdqjudy.top/Article/details/gtnbpmbzmq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtwawcyile.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttcqragle.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gtjwhwwrgs.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtofsjbyzj.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gtovlzbopk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtbxmbxlvi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zycfv.cn/Article/details/gtvcctdfnp.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtajectzew.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtjyarznqb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gtdsavvclo.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gtjhicfmyp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gtzwltuysn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sxryk.cn/Article/details/gtuduowfcs.html

[L02] 发送 POST JSON
来源：http://dali.meibo888.top/Article/details/gtmckkxmux.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtlbunwoby.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gtlxejmfmx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtwuhdrrgw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtpctzrcrj.html


<!-- 参考信息 -->