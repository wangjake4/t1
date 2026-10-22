代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2chbjwcdk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzerbvm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaxtkrb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgumgws.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2hisbryok.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtiraou.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sszbgfoz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcchfxu.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfyopyx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdemaoud.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xydbviyh.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzscums.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcmtmjr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2bangkcjm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfomlzy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2upnohsws.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fohnsizi.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfdcuzf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2szoyufty.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvmphxf.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgsbauz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfgcjpk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2umkgabqq.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcnktnp.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2bmccvwjv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyqjiya.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhdemrb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfwibcw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2betrmxml.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2imdmfwfl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ittdstqt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reuswsnk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2akjzyuos.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvhxnhn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hikvzyso.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jesoibpk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2jducutgr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxhaazn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2rjntkyfp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtfphzl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsfpklp.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjmgwkm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2iirbctzw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdgtbbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bolxxkrk.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qwitvmzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htsxztfr.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqplsnd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdasujur.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnfcxzs.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfgamea.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiholri.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2lichjmsp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2elupktmw.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqkflbk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zujvnorz.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2axaktczj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrosybw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmljxcfj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2owpotpmr.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtrjhak.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdymemoq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbihfrmt.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcqkkgp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjknwnnm.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbnjonv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjayjdx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2igqnlzwr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrlfxqq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsnewps.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2teecdkpo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyduruo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oabexkkv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqctzmu.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zflmxhed.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwmrxtx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbswcyer.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrndmfb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2cszuaxyz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtgocrv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrewnnfl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qftekpoc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jypyacrx.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxxawvm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtqfzmc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhtggpq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wicguruh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpyqyhn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmpiaay.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpgkooc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaxfnrg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulocqwfr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2uixhpmrj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjdxcwx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrccidj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsyehun.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2fikrqgmo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyisonz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuclksp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2awkjiliw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2wovmgfrx.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gfduskhg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvokqqo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2pastlpsk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckttdair.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2ejectixe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2szohxrhf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2cohgxojn.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpoyysq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2clhgtgfb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hnehlphz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2cthghkfc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgfkvsc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiflrvj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcgigwr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2yekrmgfo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqwjktl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2afwmhgjn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaavdakv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2neeylrmi.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bszchylm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtnnmfr.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zznkuicc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2farmbhuf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2fslfqqee.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmgxmov.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2juunutsc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkgivsp.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrkwomw.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2wfukfeef.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2pajgqhfg.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaciwxj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2cenafmky.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsjqpwf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwxsmft.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaamlqu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoiiuuy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2jflfgwhj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpzvbzl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpolbdkh.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2xgausmde.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrefgzmw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkqzlul.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbhsptq.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbgbsek.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtccdha.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoefydlc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2izrftvdj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqodmtwq.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hovhzfbv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2waowhxum.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2unzsgcim.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrilvxt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmacuqc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzpzimz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uisnikvb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2waohlxos.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmposql.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoewmqgl.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kksmhtxy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2nshymmrz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbanzcth.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqvlcma.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxclycyn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhojotv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2ytepzqbi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmowmexz.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2wqomhvfk.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgigekd.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2rusgmpua.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2thglfncm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwcfdlj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2uewgwuth.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdnyebs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdnchwl.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2ywszxpxf.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2tumdkspu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfcmebu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2elgkwlnz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2npujwbmu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2eydszstr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgbljzl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxptgqjf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2slbkmdbc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsmcccc.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2awdmxteo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2xraktbmg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgthzgvw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylidfhen.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyvaanj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhknwoyi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrzzsgb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhkomsu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeauzgt.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsoyifp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2vytjwlvw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2iedbkmmv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2estwydbq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2fovgnwvy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfafhrlm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjlydjs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2fadpnmkw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2dktgcgwl.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2smmmtsbo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoogayig.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeokljo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2acczjfmq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wergvbna.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjwdmcc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyyxdci.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2jyskrhzv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tktvnack.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ragsmeza.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2netndimm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owatarvm.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhlgcpi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2moknzswk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2stkvsbqi.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfezylrw.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2laudchwm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqdghtg.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2thmaecqj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrirposi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2auflsyxo.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ugphvjph.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vesprhyl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qjogswdo.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2epbvouzz.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtmihvn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2eowpufyb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2twbgegwx.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrurrco.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xultucnt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjqotnk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2aubyxcrn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2woismwer.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpfuvgj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzktmpz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmhteqw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vodjofpc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2utcyetzg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfhugds.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfzrxfy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uppcaqfu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvvxndg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iexynplg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjjulfo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2yewfekfk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2earrvbzg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lufhotrs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kblswhcj.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpljehw.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkbzjmx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2exifvvqq.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvsmlek.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzohdsoj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2jtirhrbr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2rddzscfe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmughiak.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2cmioltje.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2dphabatx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzjtwpt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgnfhqm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvjgycu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvbvdnz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2iuntvmoe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dprqyotx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlswpchr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2krqyydmp.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqlxzyz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhixjhvx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkduidh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzudivv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvfhdpg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bowhixmf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2wluukgtq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxozgpb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcmjnwc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdqtdtq.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnynzqn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvguosx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwafiae.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvnvdku.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2wdojvfkc.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2gplszcrd.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2djkltqtz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2agesoepr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrrbemr.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2kdplkutq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwkpdds.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyjzgkk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2wltckrme.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkvbeii.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzrbnvs.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlzhxwz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqxrjee.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwwglos.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpvihnu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyeynsd.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pqejdwhw.html


<!-- 参考信息 -->