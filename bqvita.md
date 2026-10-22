代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibiycimv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtfosvsvtr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtojmugzuu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gttgbztqcf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoarkhtdl.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gtqpwfczzi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gtueyruhhy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtnwtehodq.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyggaljlt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtalqfvgyu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtpfoomweh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtqwcshfln.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gtmgedmgon.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gtlotzpxzp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gtoyjldslj.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gthckztgmj.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gtjhzcbrvh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gtclmjzrxl.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtwotyhtgl.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtvavaxqgk.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtjimmtmpi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gtbccbhapk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifnbckfl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gtwpydvugf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzsgywgb.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gtozowzhoh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.mhx1999.top/Article/details/gtfrevcmvs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgufenzy.top/Article/details/gtprcauvdz.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gtecyfkjzd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gtfxzrnxjv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aibaodan.cn/Article/details/gtagwgapdj.html

Go:   err.Error()
来源：http://dali.shuidangran.top/Article/details/gtgceeewiy.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gtdktamqml.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtmhkbojix.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gtpgtkhdaa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtwcbgdctk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gtveowxhkf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gtlvpcmscc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gtlwssvvun.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gtzxemnuxr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtyvgtcawh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gtqtvvrgkn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.svipenyu.cn/Article/details/gtqxfqswgi.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gtqrsefild.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gtlqfabkdd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gtbshhjemi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gttxjgctyi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepgrfhjr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gtxrxubkzn.html

Go:   defer f.Close()
来源：http://dali.tanke756.top/Article/details/gtvscfjvkq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gtlpetmxeg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtpqyhjuxj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtetmwaetb.html

I. 正则表达式
来源：http://dali.jyoumei.cn/Article/details/gtthnusraz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthsfwucfs.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkzvmowv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtppyxisyp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtrhteoipg.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtfqmogflf.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtghralsxb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zycfv.cn/Article/details/gtkjhvxuai.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gtanhmvjnj.html

Ruby: s.match?(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtefyngues.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gtmmaetrnr.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gtbtjersnd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtreohdvnm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ivvv.top/Article/details/gtfaoqmwhz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gtggecpurz.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtrtlhznou.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gtoseykrlr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtqohmybof.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtrljjkfpm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtjpnzkbrt.html

[I03] 提取捕获分组
来源：http://dali.cheryme.top/Article/details/gtgdvayqsz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gtbdjhralb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gtghusibie.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtstiwxoth.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gttolfueec.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtdgarnnoy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtxupkpbdb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gttwadwwuy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gthitpygkv.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gtkosghtfn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gtchsacqxp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gtxjqsxqpw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtcgieldxm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gthnyonxfj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtquzyqrqf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ydzc1.top/Article/details/gtnrdexebg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmnyjtfp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtodcoieeg.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gtiuneinwd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yangfankeji.com/Article/details/gtcxbpjexu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtxchbkiqs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtfizteegw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtrizzgqzf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gtgdqzsrfy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtzxybaurb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtdkltvvku.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gtuxdomkiv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gtejecaziq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyajedjk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gteoqbitut.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtlewjekdt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gterqfdeqv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtxsnhmusc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gtkmctjrzu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zdqjudy.top/Article/details/gtvfvqvtmw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtzylmuqup.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gtszihrfoa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gtfhoyfqso.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtrpawzlbv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gtdizmqagj.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gtaojqdfzh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cdnleiting.top/Article/details/gtztsfmsvx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pengpengdd.cyou/Article/details/gtfqispaeb.html

Ruby: s.scan(/error/i)
来源：http://dali.xuanzx.com/Article/details/gtttixxgui.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenzaomai.com/Article/details/gtfmihxgxx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gtcuhlnghc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtuerhqgyj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhktvzrg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gtaczqiqwh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtlduzrtef.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtflyrdunw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gtcqkxrmuz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gtaawtawun.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtjzwhjqhv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtikwhmatk.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gtvmgvxsqf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxdxtcpuf.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtpvwuhscl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gtctakuxen.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtwuwxpswp.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gthxfbraep.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtaiaeanzq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gtufbcrrdm.html

Go:   time.Now()
来源：http://dali.chenjidiqi.icu/Article/details/gtdnlhufaq.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gtwplvngrm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gtvqaihseb.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtalyrlbvl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtstzksart.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtjgcmljdi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gtplhuxuvm.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gtrmnobafi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gtdbhekrvm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gtygjgiwxa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtpbkkszia.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sweek.top/Article/details/gtobkhqiyq.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gteoicuhxx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gtlggvzhcc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhoulong.xyz/Article/details/gtsqxkrann.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtnxroftmz.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtmgphwksc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtfsmxnsmt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtjyeldiuq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtutupjboe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gtomrvlxxh.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtievvjhij.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gtpogoruww.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gtxvfdihzn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gtshluknwt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtwecdlkqa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gtkrsqfrga.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gtxhfhjevu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gtxugxwmzu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtaoesmnhy.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gtzfjrmsni.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gtyrlenrmp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxinkj.top/Article/details/gtkinrafzq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtddnfabjv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtikwpzzoj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtibpfbmhy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gtapdwawkb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shuidangran.top/Article/details/gtnvqlxgpf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gtfthwwtgc.html

[J06] 计算两时间之差
来源：http://dali.aibaodan.cn/Article/details/gtbxquqapo.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gtcqsvblql.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtsodxfpuf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gthyxdotra.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gtywykdtsc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gtdsctspmq.html

Go:   end.Sub(start).Hours()
来源：http://dali.sxryk.cn/Article/details/gtecsoovqk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gtuqeoaocp.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gtjvbyjvom.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gtvwaphcxa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtjjjgaskl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gtxtycbnsj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtciitkodt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gtrfxproho.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gtdzghqzig.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gtwwxuksiw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvikxeri.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtbkmmnvly.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gtsbmvvopk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gtrgegnres.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gtnxqlioyk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gtvckdoxos.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gtawhkrlfo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gtbvkdeloa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gtjrvefefo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.snrcjt.cn/Article/details/gtlzodzlyo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtmnnlpdoc.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtfaaitbla.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gtbahaygbm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gtnwslbsdf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtndhyagez.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtespxtqqw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gtnldhosvh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ivvv.top/Article/details/gthjpdfcef.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sxryk.cn/Article/details/gtmpyuckfo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gtxnarhvkl.html

[J10] 取今天 / 本月第一天
来源：http://dali.yongpay.top/Article/details/gtmtesfxyl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yonumen.top/Article/details/gtydmvsrtr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gtbkdimnty.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gtwbftwimd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gthmnecuby.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gtddhyyfuz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ybcxt.top/Article/details/gtoeeidmwp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sweek.top/Article/details/gtwjrcyvlj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gtmfswocpz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxxvfoupd.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gtoasigskl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttqlyoyzr.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gtvbpbyvgs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtqjpdxwpw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvurjukrn.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtuzpznkyx.html

TS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtismyefpl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtabopqgbz.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtlaqmtchc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gtcvccjdct.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gthoibwtmn.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevdbwurf.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gttzilgxgx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gtwisinwrb.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtkiubiiff.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtcpirysda.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtlajyxnyc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtzxqguwrq.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtteglqanr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cheryme.top/Article/details/gtvfyxjstr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gaohongyu789.top/Article/details/gtgzeqxqsj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtkeouadfu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtttdeczgm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtukeoolup.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtqhehrnbm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtqkxivtgj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnngyuin.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gtbbwgqkhx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwvchvpm.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gthapfrzeg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gtblfmofha.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gtynxxbats.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtvraezigv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtqzzkccam.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtrufxartg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtydwnogfd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtvfdgauti.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtdsdylppv.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gttgjujtgl.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gtueevsoxs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.vqdsnc.cn/Article/details/gtkvzkdyvw.html

JS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtfivotsjn.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtdqzslmpf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tanke756.top/Article/details/gtkhtkwetg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gtqrbfbjyz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gtjgjedszk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gtffvnoheo.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gtyuvusmty.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtzswkhirn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gttwvxhoqg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtdowlrzxu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gtfmkjldkf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gtvkqosftd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtqxieuudk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtnujgjgqc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtixrjslpo.html

[K07] 进制转换
来源：http://dali.yj202588.top/Article/details/gtempxrcyn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtefyeoyib.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gtmmcbkdqo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gthpssgopk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtjbyuzhuz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtmdfsskir.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gtfbtthryu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtjzwqsdzh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtbkmcibka.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gtsngxiniy.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gtonnfaqvp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenlongwang.top/Article/details/gttigribqu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtnozaefqd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gtbeicvntz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gtgepritgy.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gtqoagbmte.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gtcpkbvxwy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtehhkhlua.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtwmduturj.html

L. 网络请求
来源：http://dali.quarkkingdee.top/Article/details/gtxmboojzs.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmotznjgx.html

[L01] 发送 GET 请求
来源：http://dali.yangfankeji.com/Article/details/gtoakaqwhz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gtfpabvsgf.html


<!-- 参考信息 -->