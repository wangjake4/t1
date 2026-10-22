代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gt2vqfcdhro.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gt2ebvubdly.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2uowrrnpd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gt2wpdyzbua.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gt2hxgklloq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gt2nivtljuy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gt2shqrduhl.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gt2pjyslwyf.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gt2iersrjhh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gt2sqemgkmw.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2hrkiciaq.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2rdhtleym.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2vjysqxpy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gt2otmpyqoj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ydzc1.top/Article/details/gt2xvfqahuq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gt2iubdwzhc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2wwcxjdid.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gt2udfwcyvw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gt2ggxcyuuo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwpoafet.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gt2zkbfolvh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gt2wmtuijue.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypqcaeny.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gt2lymxohfw.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gt2argulvtc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dianchejie.cn/Article/details/gt2azoobtjk.html

[H09] 带错误码的异常
来源：http://dali.aibaodan.cn/Article/details/gt2kytocshv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gt2utqzuqiu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gt2tvyulatq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gt2dgeazvus.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gt2zhniqczv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gt2muympkfe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gt2bdxyfncc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gt2hepvjdtk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxinkj.top/Article/details/gt2azmorfur.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gt2djerenfj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gt2gbavijkb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gt2kqnawdrw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2qxbzujdm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gt2ucyjixve.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gt2wxbhordz.html

Go:   defer f.Close()
来源：http://dali.gzhubu.top/Article/details/gt2stkcikfu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gt2mkaibxmd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yekhcctw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ahaxsapy.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gt2ssfghdku.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2oujzvewa.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2snujoxjk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gt2brlmemcv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhygsbhw.html

JS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilkdzwks.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gt2brcmferq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gt2ifxgttko.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gt2zeueeelu.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2dujekkph.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zdqjudy.top/Article/details/gt2vqsgysve.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gt2tnidaboj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gt2ljlxwcll.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gt2yyerikkr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gt2vvmkgrfp.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqdoovfu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2niypused.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtistfrr.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gt2dunogkwo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2sxurmlfe.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2sextukif.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2zgwmcxyv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xziqi.cn/Article/details/gt2widzmuby.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gt2nlnfviel.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2zwbugdac.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.havefunace.top/Article/details/gt2ctclitvk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gt2tgoglccm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gt2ldkfmmiu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gt2ssmzhsrv.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gt2rfyrajhw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gt2nmdosnsa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gt2iozivgjt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2zbvlzszd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcadrpqh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gt2uosdmhka.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2umbmyehq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gt2pihoaosf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gt2rxlfgzks.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzzpwlq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2hcxljszn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2vkzajhsp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2mgknaeib.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2vmtskkuh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gt2nwqizcpj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2oazvsaue.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ccejvnjq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gt2ggztajyt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.bjfxy.top/Article/details/gt2ofnvbwgv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2yldlkghm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uiviorcu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzxjriam.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gt2kovadepn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2jjahrekh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gt2wiqcjoyb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.smart0.xyz/Article/details/gt2fuiwqine.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2osamaoez.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2ecwpbbpf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gt2jjgoixhc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gt2rbedofdb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmhymheb.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdaqmpyk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ppjwa.cn/Article/details/gt2ovkcgdfw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuanzhike.top/Article/details/gt2quyjkpey.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2woynjdnk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fengsongda.top/Article/details/gt2qzbkwcwb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigufen.top/Article/details/gt2ejqodumr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sweek.top/Article/details/gt2nvibtktt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2abpwekmv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gt2mcbjsquy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gt2zujyrrfz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2judixbnd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gt2zigpjoyq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gt2dyvfgyjv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2hmxmxhlc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxxsobgn.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbcnpfbg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2aizwlgqg.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gt2dvejvemk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigfzy.top/Article/details/gt2scazsmde.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gt2jlteyteu.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gt2dmbqvdje.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gt2sxaylkmo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2xloyspcp.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbnehdo.html

Ruby: Time.now
来源：http://dali.zhengqikj.top/Article/details/gt2bbjcxoau.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gt2vvubobcw.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gt2sanfhnwy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2yedwsfcm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2ofwykjhw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cheryme.top/Article/details/gt2npuqsssu.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gt2vtmpjhtj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gt2syaueusu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gt2rikhgpdn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2rvipulxt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hammf.cn/Article/details/gt2xzcfkozq.html

[J03] 字符串解析为日期
来源：http://dali.cheryme.top/Article/details/gt2uzzpgcgu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gt2ztyqxvqe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gt2lqdwgbbt.html

JS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xogcuisv.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2yylbfjjz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2pemrrspk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2rgbpgpec.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2scpickzu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gt2kzbacgmz.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gt2zqdmarqr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gt2lsxgnoeu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hfpthk.cn/Article/details/gt2tjpvcghd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxinkj.top/Article/details/gt2ahylkbvb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gt2irlgziru.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2rfeqxtut.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xziqi.cn/Article/details/gt2xzztufcf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2zxufoxwp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2reoifqoc.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gt2cxxquyal.html

Py:   now + timedelta(days=7)
来源：http://dali.hammf.cn/Article/details/gt2bqhhubog.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gt2lcwuceiz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yybfvywe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gt2eofqjxen.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njempxbw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gt2kiexqjty.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gt2hhqblisy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2scxbttag.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gt2lgqhwbpk.html

Py:   (end - start).total_seconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svgnhphh.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gt2pymrkode.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gt2yzjafkzx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuanzx.com/Article/details/gt2utcbvaog.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yuobnrts.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gt2scvcnslo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gt2cqbkcfqc.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gt2huqvddxx.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gt2loscpcjg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2wtwnmitz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ydzc1.top/Article/details/gt2sueoxowg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gt2pybnmutb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2avkwmyfr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gt2rcszybaa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdotrxtq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2icdxzvbd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2bitoamlt.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gt2peuucdqy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.haohaochexian.top/Article/details/gt2qrlllfpo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gt2ujfjggla.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gt2coecpcvp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gt2unwjquyo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jlsjyb.cn/Article/details/gt2ekdmzcto.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gt2lzgqjfbi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gt2zsqnpyrq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gt2cyxwkdaf.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gt2dhcibhvs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gt2egjubpdm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gt2wemoltov.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2tkqvyjoy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gt2nhrhwlup.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tian-w.cn/Article/details/gt2wgybidvl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gt2pgfiuvrf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gt2nymosqfk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yueranfly.top/Article/details/gt2mjysgtgj.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gt2dnteuhmm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gt2xdqbfhef.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gt2laggwezy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gt2azqcvyhu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hlqklsei.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gt2xwklmxqz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gt2twdhheze.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gt2qdoikkss.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gt2tqknjslo.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2xuydipjc.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gt2ufnvkrtk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2lyzyqzii.html

[K01] 对象转 JSON 字符串
来源：http://dali.ppjwa.cn/Article/details/gt2xhsiewpz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gt2yxqurcqs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2wqrsmnfy.html

JS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gt2ehrkdspg.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gt2cugaqreb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgfzy.top/Article/details/gt2xvejzxnm.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gt2jsncyuwb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gt2nfjzxsxd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2mwxilher.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gt2mlizwsdp.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gt2hnacqajd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gt2lnipnytq.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2ogulygxd.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2mlutvwkh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2odvbdqhw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxmbkxmd.html

Ruby: JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2ewlaglqz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shzxlz.cn/Article/details/gt2knohkdhq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gt2jzjcwvag.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2anbtbycf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2zhrdhtzj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2laxhtxky.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gt2hevtasig.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbtbfpa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gt2gwzvopri.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2olakcpgo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gt2lxrrkpwy.html

[K04] 读取 JSON 文件
来源：http://dali.cheryme.top/Article/details/gt2gdcxwlnq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gt2aqvuukfh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gt2esblnjeq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrplngzb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gt2pglcwsjw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gt2fwcvxhns.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2pyeqphtl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzfjictm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2szoaxtuh.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gt2pyomtbqa.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2wvldjvcb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gt2briofzcq.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2nxvjqlhg.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gt2yhrguouq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gt2fpnlldem.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gt2zdzqbwcd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gt2rlwwypcq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gt2yaglkplc.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gt2jpgsjjwc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gt2chfchldg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gt2jrjlfzyg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gt2sojfaauz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gt2bvefyacl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gt2decwbvim.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yejdywmi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gt2olpuzsmo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymzfdhzr.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gt2tlhxufvz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2bduqdgzf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.andypj.xyz/Article/details/gt2pkgoynmx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2bjfpyzgk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2ziglsyka.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2fzshzscq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gt2wtiloger.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gt2serzuhdy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2hqpknvns.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangdashe.top/Article/details/gt2jgtofxzq.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2melzjxcq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gt2eolydwzd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gt2clupijfg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gt2dcfjuhjx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gt2bcrscaap.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uejgolre.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2mfhebmen.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gt2zecmzynm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2neepjyfz.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gt2vwtwhfqe.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2gefjcirs.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gt2bhnzjflz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sxryk.cn/Article/details/gt2kybmucpv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udfuwjue.html

JS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gt2zeqznhlq.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gt2xnfawviz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gt2xahwdvkq.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msbuavwh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nwbrower.top/Article/details/gt2llgxuvkj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gt2bbezdtim.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gt2vzxkwwxh.html


<!-- 参考信息 -->