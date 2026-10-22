代发 wailian999

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdebyzc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwxqkun.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvuxily.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2inhhboqx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoqzlua.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dccgoncm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsciojpz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2vczltobh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rulztuwg.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuoyryo.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpggoho.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyvqcov.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcctfin.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iujsplki.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkikxhs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjblkde.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yejmcdcq.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmkeucd.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oypioxre.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkyytah.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yqojdjdo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdldizwb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wquuyyxg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeuljxf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyijehav.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2dntzewqe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snftgvuh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2unmcmtnn.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vokoezvf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqfvpoc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jrodzsjx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsttvoo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsubiqx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfippzza.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iigmdqes.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgxixsm.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mehugsrj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqlghto.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qurvcdpc.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkansgvb.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2worrtwja.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tknydhuj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jybqafsi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vocqrbgm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2urtxdpfu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2iapfrgax.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2opvvziqc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2qbevgjva.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2qencecno.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ossfmlbc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbmgsqi.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuebbdlf.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2oqujclav.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2voovcbqc.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2btbvztil.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2deehuslg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzizafnx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdbtsyf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlmatlh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grfgwvoo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aehzevru.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilysbawg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfsgjlm.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2aczspolp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohndnctl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2jauohial.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxbcuur.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdjlhay.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2bcduudbm.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyqrall.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2stwicmos.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwbmimx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvovqar.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqnybtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plvdxgjs.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dnipvbgx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2homhwgrm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuuetsb.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbotwfam.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnnummr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2tloummoz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2msavsdjd.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsyjcil.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjnhhju.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdalzaj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhfqpmf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gcadrcwy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzzvcbe.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvcxzda.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnttkbng.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2psrarhck.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxvpxya.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyjondz.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zyveqkdg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wubbleex.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ommkdgrk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cycylgix.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkbzpsh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sczbzslg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkccoky.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxxjovh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2lojspyiq.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2npqjjfvc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iycolfoq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tocoaxrb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnowaaut.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueprprhq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2iffzlayz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuvnqst.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2egdvzcvc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2alxgmqwh.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2atqkmbqq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwjrzbm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tluhvctq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vagaazqb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iflnkmal.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2heamwfnw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdrtqev.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrqjgcq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjczlhhw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2gycdcgwl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvivechc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvpchgm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2zokevyqw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnphugd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlxppvp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuztiem.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjbjmdj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2uccuztwx.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdwresv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwbelep.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2zukdutsw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzjwvik.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxparbn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqweivuj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnufiej.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnwrvcu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrgmumu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnthdnb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqcxbkr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrmttly.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2wysliyzg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzesvemw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxqvijd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2jgytdneb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvnawsd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzqhxmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mifcfguh.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2druoelzl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tegfoxsa.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tfawszsf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnsqscd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnosnlj.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2fycrriuu.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2kglnsupr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozerbidq.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2klaeqlgh.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2fepwahuw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyvhzky.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cakhlbss.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzziqpqt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmpymcu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyudwchi.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqalnbyx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgyietu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2iigouuxm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzssihqe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoggjhza.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2vehmkafs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpbbyop.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2coyzhstz.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2trwgbjdu.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvmfsme.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkedihi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzecger.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiifwvw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvshrtmu.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fqphjdtn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2opphgnhg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2mwivjizf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjgobnh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvfyuee.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgllxnpb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyvhisc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzzkiho.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehogzncs.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkasknqq.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2iybbdpgf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2crpnxcvk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2othyastg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjadnywx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lboasghx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjdmzgz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwemljq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzglhfkt.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2naudswmg.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzddanko.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2qitpmzyy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsefekc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzjomal.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2eedcihes.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqkjmlj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2vggqmwsv.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwwbfsi.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2vongxbwp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfasgxd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sicicheh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2plzggros.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgusqwjc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bghezppf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2clvdafcw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2obbwofxb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjqgwtw.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2xsndbplk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqokvqkm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdcnbfj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2daajucpc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmhdtuy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxalplbn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqfmvtl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2tnumlnmz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfvunwx.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdfbzis.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqxutsr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2civppuoo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2uywtjxlk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbowzqtp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwcrmof.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2hirenjod.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgretqxx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2utrutxwd.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2oikqigvd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjuhazp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbehmws.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwlnksn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wydaofrk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajipmyxm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2tryuhivm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2ihohqakc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbojakva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ookculyj.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsvuyyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjjvulf.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lafyrhkz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkkphxl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrtiimq.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsjxgtx.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wswvhoaf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmslajz.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqzqkau.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtmzpah.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnavtzn.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2iopaqidp.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ostogqvk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rwibrdpd.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzynwmdj.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfuwotp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2octilmxq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzsesxz.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvomfuyz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmanskwq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjmiabd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhaodnn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkpwfzq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ullncrkc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmwrxel.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2snpmrqqt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkvowna.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dexcurcu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrncwxd.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdumursr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2axaymlek.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpurngwd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzvfnog.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2etfknnpo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxbikui.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxyfdmv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2imrzfhcw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvyhgow.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgrjmuu.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqoflkn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuxydkg.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvvugyu.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpsiuqs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfwyfbv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2toynhvsq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsqjwyr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsjdzti.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhukdrn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlhuzdd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2etmhvkot.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2svizkhud.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxtmhzs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtvvvwj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjldlxe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvatvtc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mckmrkuq.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhmgahb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2krmjcuzb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2tukftojy.html


<!-- 参考信息 -->