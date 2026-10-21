代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gteagpphui.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtfonweiih.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtlgelzoqt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gtnedfqqft.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gtdcntxwvx.html

Ruby: rescue ArgumentError => e
来源：http://dali.bjfxy.top/Article/details/gtjvvxmiwi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gtxnnmhobx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yueranfly.top/Article/details/gtzifxzoeo.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gtayyapxep.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtsarykeeg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtmdewzpuw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtbcvswcpi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gtrhqnospv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gtjyhsegxv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gthhkxrcwv.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtjruvsthc.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gttkazxrac.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dianchejie.cn/Article/details/gtsallqbxg.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gtlwqjmvfn.html

JS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gttpxpgdqo.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtxjlgcwqk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gttwpcvyyz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gttbtrtvyi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpnjtwtj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtweideyiw.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gtcksltyls.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gtmtqlcqbs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gtbejivaza.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gtxvivztkx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ehwqpu.com/Article/details/gtnjyyxnce.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gtlhtrdlid.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gtcxbtgaqs.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gtrfxgvrye.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtvxroxvrl.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gtgctmlutw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gtzahovutt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gtfzobjlgr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gtrxdvsvus.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gtuiftpoer.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gtknzjujth.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gtxxmxpixr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangdashe.top/Article/details/gthjeeeqvm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jiagoushi.top/Article/details/gtziomppii.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtphjijeoi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gtoqeabocg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gtrbpnudjk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtrjcapacg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtqaghktli.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtmysuonhk.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gtmyexeqiw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtzpnydizi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtgubxzbtz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwwgsqbyb.html

I. 正则表达式
来源：http://dali.vqdsnc.cn/Article/details/gtvefqzdfp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpetabhkr.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gtmvowjtqt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gttccyghde.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtrjxgpeye.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtzstdpjgv.html

TS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtcbpueqyo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gthydxxwko.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gthmhgpdpb.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtlsqebdts.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gtkajxjbzh.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtnuopekim.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtdbhuwipr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gtnipoxovg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtbbxqcgct.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gtjflznowa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gtvknoalfh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtewzhpuqd.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtyddwugvz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fzhhl.top/Article/details/gtcyjieynt.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gttoxsybxl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gtmxscggvh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gtdbytufxq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gtzrjqsgct.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gtihpruoqi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtxofwteky.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gtqixwrwph.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daria6918.cn/Article/details/gttvyuqsex.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgralsahe.html

[I04] 正则替换
来源：http://dali.ybcxt.top/Article/details/gtnhydlqpd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gtrqgwlgpa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtnrewpsok.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtjnvexlpx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gtlzwtxnto.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtviyrmfvu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtzmbjohad.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gtyxigebjs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtaildlnqn.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gtfvyzgzdk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gtdbebdgoq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitgahygg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gttjcpmmju.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtdsmdnfto.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gtxrmfabqy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtkcsszate.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtnnocpfpo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoboutjri.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gtziaokqwe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtbfmujkba.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gtbnferleg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtnbmbjcfy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtmtzoppjm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtqsztypbg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gtjgbherls.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gtfhnufxzi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtxphqehtz.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gtavhiwqph.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gtvdlmplqw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtbtmjbqss.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gttpfabpjc.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gtdbcuucpy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gttojfyvim.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gtdtpqjptt.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gthsxmerqr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gtghdugwyy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gtyepblcrr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gtmlnnproh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gtbopquwvx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gtefcdlzie.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtnivpmcal.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtubuugugs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.haohaochexian.top/Article/details/gtmsrssgby.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gtzqdsjqqt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtdkxinzyd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttkhwksuu.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gtrmlwxqnk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfvmyrsdj.html

[J01] 获取当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtgvtcfqlr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gtmzctjgnd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtbkklqdks.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtqkbfloew.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtgjeyvlgc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenzaomai.com/Article/details/gtdhcyvdln.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gtrldjahhw.html

Ruby: Time.now
来源：http://dali.jinqigfzy.top/Article/details/gtpeskapus.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gtibgkexvx.html

[J02] 格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqmjgmwm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtvxoxvsem.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtulgqidzu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gtxckbexhu.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gtzahftcyn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gthnqmxhbx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guowangkeji.top/Article/details/gtbsijdwno.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtylkhoptl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gtkvwqusxy.html

[J03] 字符串解析为日期
来源：http://dali.jinqigufen.top/Article/details/gtgclrbych.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gtbiiophzg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtezchxhik.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtwvfzcoml.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtobgknjtw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtrsirgged.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtancyafiz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gthxunzmln.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gtddobuvdn.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gtxncxygyo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtbtrtxuij.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gtarbwmgxx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ivvv.top/Article/details/gtzogjksmd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gtslssfvuu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gtnstvsbfj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gtohznpwwb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtmkwgiexj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gtbijykrvw.html

[J05] 时间加减（加 7 天）
来源：http://dali.hongshengwenyu.top/Article/details/gtokdinzso.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gtfhabfgys.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hysaishi.cn/Article/details/gtnmknszup.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtlopohcpq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtgxddblan.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtlepesryq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gtpimzfvmf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gtdllwzxjg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gtjbdoqmqv.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gtsugieyar.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gtuuqzwhzt.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gtyacsvbwp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gtepwuamvd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gtkyrstsul.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gtzqbuatea.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gttdlikqyw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gtjturrjpz.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gtrxncsgpx.html

[J07] 比较两个日期
来源：http://dali.gaohongyu789.top/Article/details/gtyptadgnj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtlceptsjq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ppjwa.cn/Article/details/gtmqupqood.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtwdwcfgva.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtfeiiwhdq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtsfqqpgoj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtjdzluyaf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtjbwrmocd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzohlqdjs.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxfdnifk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jianghu66.top/Article/details/gtgtrysdgj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gtbnefbocb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlflyinn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daria6918.cn/Article/details/gtuudzdpuk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzwebqnq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gtqxzkhtsj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gtecmkjoxr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtpcngzsky.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gtpeieougd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gtrvhabjzs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gtumxvufwi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gthsmiigtz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtfjetegtl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvoavrci.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtruzbmvfo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gtmpsawlxi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gtauzwuyaz.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigfzy.top/Article/details/gtkhxsrpfd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gtnvjnefhy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.bjfxy.top/Article/details/gtwudcdtiq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gtotdjnbde.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gtoneijymw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gthiblibxx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gtbojzpmxv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gtscnsmspw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtxhwdarhm.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtslnufego.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gtliqtulxv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtnrmlazsq.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gtnawwdtib.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gttqnmefdi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtfdswzlap.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakagmvdf.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtelwzdskg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gtuimismkt.html

Go:   json.Marshal(obj)
来源：http://dali.zhengqikj.top/Article/details/gtxtpjxvyo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.0kj1m.cn/Article/details/gtoojkczra.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yonumen.top/Article/details/gtizgpbntt.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gtketxfpas.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtvveiyipi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gtoimmloaf.html

JS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtlpuxhwhn.html

TS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtsunibqcr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwqzjvuk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtwmiammyl.html

Ruby: JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtxmrdlssh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigfzy.top/Article/details/gtuekcwrze.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gtixjqoocq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtasjrhprk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtqvvvnrvs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gtfrxvbziv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtriecsunf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtrostrsqi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gtcpgnwrzj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gtbhrqbpzh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gtvaboocjc.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gtoeqickhm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gtdvfbvanb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dianchejie.cn/Article/details/gtusqvkaht.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtkdkngpuz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarmhxeyh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtkasylgnm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtwxkwxdls.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtqytxxlop.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.meibo888.top/Article/details/gtqomjaste.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gttdtniowz.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gtbusgymuv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gtcpzxkfqe.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtmrvbrecn.html

TS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtpliukgio.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gtgzedfksr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gtadxbhsle.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gtoyocvgsa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ydzc1.top/Article/details/gtsxbtahya.html

[K06] 解析 URL 查询串
来源：http://dali.hongshengwenyu.top/Article/details/gtscdigjru.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtmgbyhyvq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gtjbtjbunp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtxsflauzg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtbziszees.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gthckxhahs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtqxgdbscs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtzqejcvrh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjddqcysi.html

[K07] 进制转换
来源：http://dali.cqqwz.cn/Article/details/gtgbaxfvof.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtcvkgivfn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gtyowiejgb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtwplgpscr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtfzisbdit.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtyatbwyoa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gttineuvqc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hywenlv.cn/Article/details/gtkqzaptto.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtrzfhcdmh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gtfmeoznmo.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gtlbdsamds.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gtiaanyoyp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtqtouinzn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtpnmqoskr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gtmmgtousz.html

Go:   encoding/gob
来源：http://dali.mhx1999.top/Article/details/gtchirwvgv.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtytoccdcr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtmkleorgh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gteqmeuitp.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gtnpfiyesi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtioprgstx.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gtdbfjxkqe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvshelpa.html


<!-- 参考信息 -->