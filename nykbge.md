代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gtltjpqzev.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtcozbikgd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtmynivixk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gtgtycjjuu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtlzlednmm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gtifnopyum.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gtatyjsfwa.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gtstvztvlu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtkkghkxax.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtcxsytzcq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtnwkmebua.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtymvivtmp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmnsqmrii.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gtakchclrm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gtcipwkpbg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtkwqzgaxm.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtrpebxvtt.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcymeqsvu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhyormhz.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtyqcpvqzl.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtjnhnynwc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtwjiguest.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shangyingyoupin.top/Article/details/gtxqizhcbe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gtczvliyws.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtandqcufn.html

[H04] 自定义异常类型
来源：http://dali.shangyingyoupin.top/Article/details/gtevcapzmn.html

Py:   class MyError(Exception): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtyqohactu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gthyyuruol.html

JS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gtoxhdsnwf.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtevnyuyiv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtrovglwuf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gtajevqagk.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gtmgonuaqf.html

C#:   class MyException : Exception {}
来源：http://dali.shuidangran.top/Article/details/gtidjomoyr.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gtfbfxldga.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gtncwrlcfl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gtxgkfyyyp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtdjptdbik.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtwdcpzwwa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxeiwayeu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gtcnmkvfvd.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtqumgcbjy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmnfthbl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gtsokxneso.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtkesrzzum.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnzwkgev.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtkwqdcjik.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtquxbdvsh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gtpcmuztbo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gtsklhctcx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gtogzqtger.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gtfiiegrml.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gtaqnicrhj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gtvktdkebp.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtloihqmoe.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtdmkvlcfp.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtffzwweix.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj202588.top/Article/details/gttmgixbcr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtnpfzldvu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyckkdwty.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtoodivyty.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gtaxhjwwlx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gtbyhmwjvu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtacvfjeao.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gttwxwbjdl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daria6918.cn/Article/details/gtkaccvxrc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gtutgbmiut.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gtakmeheor.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gtxttjrngl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gtrpwximbh.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gthnkevqxv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gtmusxcsyn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhoulong.xyz/Article/details/gtxcjqnjne.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gtjkterdjd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gtmxldqyng.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dashuyun.cn/Article/details/gtlvflonng.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gtodlxgknf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hysaishi.cn/Article/details/gtdfwjliba.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shuidangran.top/Article/details/gtmwrotlcn.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtdfvheupe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gtxnuldaiy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gtfgcgyeyl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtvmfthqdw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtltnkgvla.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtlryozygn.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gtttsdgyek.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gtchhptswb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gthiqtfxhc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrqgsgrtn.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gtcezhylyz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtuwerkuwl.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gtjhmegkbz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtanuenohl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gthbhozdha.html

JS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmeiszwk.html

TS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtzsdtbhdv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gtqdnqagqq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yonumen.top/Article/details/gtjnpyvqae.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtewhypbtr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtxjmoyybh.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gtpfpfugjm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtqzjkzwsu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gtrztktbha.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwjaterh.html

TS:   s.match(/\d+/g)
来源：http://dali.fengsongda.top/Article/details/gtatwigkec.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gtitnmfklz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtlzasqgkd.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtozranspr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tian-w.cn/Article/details/gtfuyvqdcl.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gttpkioicz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtdmixrevo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtatpoidrj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gtpziykrmy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gtuypyuyea.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gtwcepjaok.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gtshfyspfy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtghfxkejf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gtwsabjmhn.html

[I04] 正则替换
来源：http://dali.svipenyu.cn/Article/details/gtoihmkyev.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gtbrdpxpnc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gtvwezjwfh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtkjfkqdxc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtzinmnodm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtvaopfqlt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gtyyadrmia.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gtzqmfuosb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtkdqnhxta.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gtdwavlzhc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gttgtrzsmr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtqgsthlez.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtwbikekwa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtyjgdgftw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258.top/Article/details/gtsebirfda.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtjsgtcqea.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtadzwqaum.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gtqiriczdt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gtxglcpjta.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtqakglaxk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gtymqwazbc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtjjehyjip.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtcgvsrzmg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtjrspxkvu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gtdqccpdaw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtlslzibmw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtfjtcxbek.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gtwsuuaicr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtajxdqlvg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtbcachgrf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gtywtgueqk.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gtbfvgefyt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gtedzvxhpo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gtbixgkqbs.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gtnaqnwvqe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gtncexrykd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gtpumileod.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gtyacgndju.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtmbzjiifj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtpwwmnoai.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtpdwskytb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtdbflyvda.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinghuilouyu.cn/Article/details/gteaxgzrfe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gtkyxeszxu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtntbbaabi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtotpgrptk.html

J. 日期与时间
来源：http://dali.snrcjt.cn/Article/details/gthlisdigy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxkllclzo.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gtxdlrcwia.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gtibjvnthf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtyailwnre.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtjegetrnz.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtwbnuduje.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtzqulkepv.html

Go:   time.Now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdfjpnfk.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gtifcajxfy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gtymxehwdi.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtatmpdrgl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gtvewolkwv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtadoqjvef.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gtgqaiuzmf.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gtqicneobv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gtjsrgfxvq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gtumforfes.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtgvrrypdu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gtgtzvktek.html

[J03] 字符串解析为日期
来源：http://dali.tian-w.cn/Article/details/gtotwcdcyu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gtucypvkxu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gthfeefttx.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtmhiahuhz.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtggijbwzk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtfbecvoyv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gttbtsbuxz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtparqejnp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gtcdehmeaa.html

[J04] 时间戳与日期互转
来源：http://dali.wangdashe.top/Article/details/gtmxvtpmyn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gtfjkiixem.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtjwzmprdk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gtwixzlqkj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yvedp.cn/Article/details/gtdpbzqhau.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtbevcfzuc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxawvrnw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtcpnsqktk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gtuvtmzowg.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gtabdvhvyb.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gtvuesfxdn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangshuangyany.cn/Article/details/gtbkudzngo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gttsgbpclj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtfvchrasg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sweek.top/Article/details/gtmeoauluv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gtcyuvqhtq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtzvpwxnoa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gtebcciedf.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gtwvkihxkr.html

Py:   (end - start).total_seconds()
来源：http://dali.havefunace.top/Article/details/gtxzlqymer.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gtgvvaegjv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aibaodan.cn/Article/details/gtmlkcysrh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xziqi.cn/Article/details/gtzjenfodm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gtnbnovswv.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gtukdadeso.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtcpcbdibq.html

C#:   (end - start).TotalSeconds
来源：http://dali.zycfv.cn/Article/details/gtjtyggnzs.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtpbxvthma.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtzqeyfhgs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gtgiytcooq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtbqxkieao.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtpbljxlwl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuarbzti.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gtkvuonrhn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtpiafkdym.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtorzdcrms.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtlvqjepcq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gtcdzdzapm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gtuabajuur.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gtuzcbeklw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ydzc1.top/Article/details/gtrelidhnp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuetiantiany.cn/Article/details/gturpqrxzg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gtzdjjufsx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gtcdwmudws.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gtvjzeavck.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtzupbjjve.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gtebyrxwvq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.svipenyu.cn/Article/details/gttlnbxwrn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtpgcqnrsv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtljfosofg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gtzvnqllmo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.havefunace.top/Article/details/gtxzzknzpw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.andypj.xyz/Article/details/gthogronfs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgfzy.top/Article/details/gteggsqryo.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gtxhzjclqj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gtiuruvxcj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gtabxjilfi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gtxlfrezwp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtbjzrgwpt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcguudoxx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gtpogfdwkm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gtwbvstwda.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtbtydbzqt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtnusozdxd.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gtpjltkokh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtlcampzlt.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gtnkjsetbx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtjlwxegdt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gttpnvyazd.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtnmimrxge.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtolphclyw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gtoaokimww.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gtjauynpwr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gtjpqdulyc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gtobnlrppq.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gtsyryeqcn.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gtqnvwdmiy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxuanxn.top/Article/details/gtltihzrua.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtsoxitfby.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtjqrynksv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtesxrohnk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtlscijcsb.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtlhqoakaw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.birdmap.top/Article/details/gtmlmwqgdo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cucudq.cn/Article/details/gtnthfthgc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtbfkgunol.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtyhsdjazp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtreijxorf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtasnzmthk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtrzcmtemj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvmjifjb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gthkunmqox.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gtberwqvnl.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gtcgxsagtj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gtgmsfhpar.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtfaxlvjku.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtmjyucmeg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtprtzsbfp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gtcayrnhpp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtmaxrlodm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtpowakxwg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqvmrhdz.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtloapvskk.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gtxgrehzgm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gtkklwsgwt.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtmatxfshb.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtrdklwyod.html


<!-- 参考信息 -->