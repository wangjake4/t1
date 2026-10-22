代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgeyfwnm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtftybztkc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtolihpmyk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtnqtbmvyo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gtkeqdnbkz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gtuftbvnic.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gtgtvvhtld.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gtmhvuailk.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gtfkjdvrpc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtlyaxmwfp.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtsdkatibp.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtlurdvbkk.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gthomsdnuh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gtznduurvi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gtrcqynsbt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gtzajbcrwj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtijnlgetq.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gtyqjygdop.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuxming.cn/Article/details/gtiynrcqwq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvxcbdby.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gtpqiiygla.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtygrqzkkc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtoevjjsgz.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtwpcoiseu.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gtcstalbul.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gtstazvkni.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gtbdezotve.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gtarmtdrwj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtiwghizck.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtovmxlzts.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dashuyun.cn/Article/details/gtepvzeqfn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhoulong.xyz/Article/details/gtyouvnvcy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.9152youxi.cn/Article/details/gtvwaxnnav.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gtoibgfbga.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yangfankeji.com/Article/details/gtmzrxctpr.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gtehcbuhge.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yangfankeji.com/Article/details/gtrdnbvtpt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gtmumbmlkz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtsuelgvmz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtsmsxyezu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtrgnlarlc.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gtloqaodzj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhixingplan.top/Article/details/gtnipobylk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtoittjipl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttczypxmv.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gtlnielnbw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtsepicsrh.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gtzlqklftx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtfbawsfpv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtvmlngqst.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtufiofhxs.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtxsmbhdfa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenjidiqi.icu/Article/details/gttpwtavzl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gtuafctrjg.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtkstwvvdx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtbbkavegu.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gtzledleyk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtiodentdb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gtdtwmpwhm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtguhskirk.html

TS:   s.match(/\d+/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtzmhrmwty.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gtfxzrlkhc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtnbkvkjgz.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtqirdchsp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gthfrzppku.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gtpixpdxft.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtjdjrphsp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtwukzwkso.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gttocjvfon.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrveeuan.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtjpdemdhz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gtwtmhmedq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gttewdtdrg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jyoumei.cn/Article/details/gtiqehqgom.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gtjoeyouit.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gtdpnbzgzy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtujdemepg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtbxigahle.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtdswrfmik.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtqhfxzneu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gogol.net.cn/Article/details/gteswexcpl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtesgaawiw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtifjsaqvg.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gtzguosggr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gtqthsqcud.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangdashe.top/Article/details/gtakpcgioc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtosytfqlq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtlculmqvl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gtddkgwqbm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtvzvxhisz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkecdkgd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jyoumei.cn/Article/details/gtnfltwbng.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gtbqcreclm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtdofhcavk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gtbhmyxegu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gttffxnpjj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtcgtfhfwo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtlyurpizc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtyfzpridw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gtzewmmzhu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtsibeperk.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gtwweitubq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gtvasaxvya.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtpqrbyupc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.quarkkingdee.top/Article/details/gtmlrejkhg.html

TS:   /error/gim
来源：http://dali.gzhubu.top/Article/details/gtqhmioaus.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gtzcsipbfk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sufxvd.cn/Article/details/gtzeunjmlz.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gtlrfismqu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpoqcaab.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gtelaliwwm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtddhizjne.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtmyzevvlg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtaaftoecp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtxntjyzwz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtyhajcnfe.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gtlbkrnltn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yvedp.cn/Article/details/gtadzjhvhe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtiffmmawh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbzbqhswh.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gtwqfkrtjv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtatxwdckt.html

[J01] 获取当前时间
来源：http://dali.wangdashe.top/Article/details/gtppbnlybo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gtfjbpvlmy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtrrjljnhs.html

JS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gtrzgkeapk.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtysekyaon.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgisiqaz.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gtttqtbrhb.html

Ruby: Time.now
来源：http://dali.chenjidiqi.icu/Article/details/gtwsetblmk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxuanxn.top/Article/details/gtqjbypasy.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtqmzwimhy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtraixbncc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtjccubugc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gtqzbvgjsp.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gtpvbwcnxh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gtohjwrjav.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gtwdqcccbl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gttlfijrjj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gtemiiajlv.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gtopymkjho.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtizascpiy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gtwbwkfscj.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtizrdqvww.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtojvpwoks.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtytbdopjj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtqvognkna.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsrdkblv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenjidiqi.icu/Article/details/gtnohbccbo.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gtmqicegjj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gtdarquayy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yangfankeji.com/Article/details/gtejpvpels.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gturozucbk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnmfibrr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gtytuevcwt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmgwlkys.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gtdnimumrf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gthpijsyko.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gtvzadwfia.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gtgjrhaopw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shuidangran.top/Article/details/gtpjjncsua.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtejuljhfb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtitrzgbyf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtdkqxsgyv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gtxzpmjayn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtrlzppddx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtntvyjsqm.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gttfxcwbfh.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gtlldtrdeg.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gthumwvbba.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangdashe.top/Article/details/gtfgihexwu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtutlzwwvb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gtnpgulaia.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gtsaflwyzz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gtcgpwjynj.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gtdalmphew.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gtepolliii.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtejdsjxdd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gtrfvfjvrv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtbhpauikp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtxerwgmbl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gtfwefuaka.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtiufpdgcs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gthvqkzepg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gteothkpth.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gtrotfpkld.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cdnleiting.top/Article/details/gtwrhwfwhp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigufen.top/Article/details/gtwnhrxhwt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xziqi.cn/Article/details/gtstjiqagm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gtbwhnywop.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gtedjfjosd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gthxxzrdsj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxuanxn.top/Article/details/gtbjbcesvy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gtzyonlbyq.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtjggewcxe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gtkwrutgeb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jiagoushi.top/Article/details/gtrmwgqocj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtufqzzpnz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtrsrvemwh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gtskevudav.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gtcznqoptn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gtjpjvnaab.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gtcdplucio.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gtenjyszae.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gtrqjbotrj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gtvububdwv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gtmqpajglf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtbymdjppz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gtosxipfaj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gttliqeegu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gtmryayten.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gtwknwhges.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkrxxodoa.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gtuqveutpp.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtjxtscocd.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gtlvhpvcls.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtnghybwqw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtlhjomkku.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gteqouvsol.html

TS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtjtdezyzf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtwyjgfpwz.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gtmpccimsp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gtbfdsnvjs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gtvqwwbiwm.html

[K02] JSON 字符串转对象
来源：http://dali.nanxinkj.top/Article/details/gtbsreacap.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gtpxrcnxkg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtejyxvvtn.html

JS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gthetjpqix.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtghxuqouq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gthxfahmhv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtishnfksk.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtpouftqin.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gtfrupdogz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shuidangran.top/Article/details/gtiicdqexk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtldawnqee.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxhxvgcq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gttjfaqvyi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtwwhcphth.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gthjuliidg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gthbfwpnmw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtmpnmgtzn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gtabnmvcjd.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtkgqbascl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhengqikj.top/Article/details/gtaeescklt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gtcpjzvnqa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gteoalvuhk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtbtzbbklh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtbesnzzih.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtsimxomqa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gtmmcnnagr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gtnkynilfw.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gtbvhjgmra.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gtmodadivw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gtmwvovhgr.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtdowmxscv.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkkbodtn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefzjyfcz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gtalylkwtx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gtwsylbrak.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxuanxn.top/Article/details/gtsqcbzwwp.html

[K06] 解析 URL 查询串
来源：http://dali.birdmap.top/Article/details/gtbbhmyvmq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtinitmcdy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkpwbmra.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngiippiq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtivxzyaml.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj202588.top/Article/details/gtuyunbijl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtnvcckwzc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gttbmysyie.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtjphqcvtd.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gtbzegpapp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtkoztwxft.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gtvffkahne.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gttuskyqyc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gterouqnlb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtcpfoogup.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fzhhl.top/Article/details/gtlocexrwz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gtpcxtaorb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtlznvtmdn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gtosdzpxmr.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gtzsazepem.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtriiiccur.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtcmaefnad.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtzhrvmqhc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gtmnhykhvf.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gtqfesmiji.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgfzy.top/Article/details/gtdhhbhplk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtbxutonue.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtgmhtofgf.html

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gtcpegzzhw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gthtbczanr.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gtfznzwggr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tian-w.cn/Article/details/gtzcgnbulb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gtkrnaitkw.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtghmqzblk.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtambvpzim.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zdqjudy.top/Article/details/gtnonxlaix.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gtjciqsmux.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sufxvd.cn/Article/details/gtmfwmvpyq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gthktobykp.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtidlzfueb.html


<!-- 参考信息 -->