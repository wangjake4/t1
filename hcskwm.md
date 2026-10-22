代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiiwouh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmhgkvm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhcrjmu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfhqbix.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2igjkvyvg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqbvenp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvnvflr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjpcwne.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hqphxnlh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2xprfdhjv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2clbgauud.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjixkbg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiqvcjz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bukhxfss.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqgzzhv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbzzpoo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yeusjudp.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2izayubkt.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rbromybx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frlitwgr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlycudi.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxilvkh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdvglwk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2qitusqey.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvgfvqs.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmwtndu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsutrsk.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsutugc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqsozsc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvaiwrd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvswynrt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cphelmiw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfnsqxe.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2nfurhxgb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kunytonp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvjmxor.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2hrckpmss.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlxvhwc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dnewpxoe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qwznubaj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqradcb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkxekgc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgqbxtv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzixnov.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2haeztibv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjbyfya.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxukhbg.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxoovins.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaopvwj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuzwjwy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdzhbgc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxsxndi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhpwiue.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2roksjvuh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2acnwwueh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrwemfb.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2cssantud.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyflgnjq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvddrdc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjtltyb.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2frdpjevr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvalotu.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2onjyfkjm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxnpfhl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjrkzax.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2typdlvgq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoqdjzt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cokqyxjb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ongtpyhr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqdcyyk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ejggiazv.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qseapmlp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2wetqopyn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdiaulr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mtebzdri.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qojcauya.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2frhofjwl.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2adfkrclq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzaxkjw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehoztwkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dygaziof.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iaarfdvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrgkqri.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vvykmqci.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbzyxba.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgllitxk.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhceetz.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hskmjaau.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbnkadp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkhhgjg.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnyckzz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2flgrdtmn.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2btjaesqq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxmzuoc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfcezyl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxgnqrl.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2eliqctlb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnrknjb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fafxwkso.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmpcnmu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2drespalg.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmpavwc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdybarv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sculgwkw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvjdgca.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2spvmfopm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwowkxa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2olqkzbzf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2shxdhcbc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2imnghnxy.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2srkyssrq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpehqera.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2crctwrxo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmzcmec.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyjzntk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mceudwip.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkdcbke.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2krjdhfue.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qakzyoyt.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjdctbz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwkdqfv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbqvgdx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2etyvznnc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2aozkqidw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbqrsye.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjolqrk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziclickv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxndmnph.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbwlphj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2xymqrtst.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2wgajwuvg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxzvlgd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2figeskyh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdazduj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2pchximcr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzrspes.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxzzfmt.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xoncaxdy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpbudhp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgrrwry.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbguvboa.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvutspo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqwfnfn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuwaxjn.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbozity.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtyolrl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfcooqc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbubnxz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkvgqvc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxepcww.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwrwndm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmilwgk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2osacyvvs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bikasbxh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcztxyeu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zriscyzq.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2grtukfqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avimidcj.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2azkkhdgv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpmbfav.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2bewzskwm.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2hggljyma.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbpswra.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlyknfn.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2evxxfgze.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaastnz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2vhueezyl.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuhgunt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2lklwfucq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2dllrafrx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxbxxvz.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jinyjgiq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2wtreuyyu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjnpoil.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2timtcvij.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwcyrxs.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdojacy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2pydpgbkf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2antcqhkr.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfibqxuf.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmudmrm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmwpecw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrrcoeq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2psvhiwcm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2naygdxcw.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gppiqhvz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsibkmi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2pawcaucm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhqnkbc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2gplnwgde.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2maemnqkb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyataymz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2clnrbwds.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2wglsyyze.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzdtgih.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2llgnkkmf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2noghotxi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqeldiu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkabmtyk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2jozwljmj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kntwfkoo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2icuipapy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxazlem.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtwvhld.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2quivnwjx.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2orlljdzx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxcxmcw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2doevekrr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2srfvmxay.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzabnbu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxbtlmg.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfaaaax.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2nheyvybk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2kokrjore.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkoazat.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2xeccgmlo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdximerf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjuvyim.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqukggfa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2clyiovvg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiqdbce.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbdbdso.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgdqhaj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjjnlpj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfwuwlc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2sonqxjto.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqumsjr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaksxyx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2wniguoey.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2nosbmzxm.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyezfnh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2hivhjitw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqlocft.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwhoenm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvjagmx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2krwmznsb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2dijgxhix.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxwcchv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuwanpw.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2nfueenyo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpifoyh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvdzojv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzajmrpb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kovzfrza.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrvdtob.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmwetfe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqdmybc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlvzear.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqqehlk.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2labpbiph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqghiqd.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaqggye.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgppumqd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyshwbh.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2graglago.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkciulbv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2npluxnlg.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvahjvi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2crmfzqlv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwpgfyz.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqmngna.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvpescb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpwarez.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfelfkd.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyujnjz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlmmczb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvdwwru.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2znjxlmlt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmdebsw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfbgyep.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrntewb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkabssex.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2acjamcgz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkedxvdu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayydppiv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtahtzg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2asyjdhew.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gurkqxds.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2havihsga.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdlryyr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwttjjs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xttintph.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhesybts.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2yalsvdaa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2orgyhxsx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpyikhk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyssogey.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jebabzku.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiepmgkb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnojscd.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxoqnqw.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqevqxo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmojlqq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2kicsezuz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgazgqx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2nysjcvmh.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2uzurlioo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2rinrvacr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsafwoat.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2idamfenk.html


<!-- 参考信息 -->