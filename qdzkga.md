代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gtbmpuoecx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtezjhukxg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtdbcrmjbm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gtjbwkttox.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrbemwyt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gtfijafbpy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.snrcjt.cn/Article/details/gtjgabeavk.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gtnufymveg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gtosduotuq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtusoscqko.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtremoifnc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtolwwberd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtsqgcefwd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gtbyfiaueq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gttbtbvjgu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtrtgvgyxk.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtdupnoskg.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gtwgcredbp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtpinaisby.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtvgsdxxza.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gthkndgrqj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtcxvmhnyt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtljjprvwf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gtiprjiosn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtsrumfxye.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gtsahlirhd.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtqttzoopi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtindabhac.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtthjkfnnv.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtlbvvvabl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtoefrxhcc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gtxburximx.html

Ruby: class MyError < StandardError; end
来源：http://dali.hfpthk.cn/Article/details/gtnesincah.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrevfilyh.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gtbrwvseoa.html

Py:   except ValueError as e:
来源：http://dali.gaohongyu789.top/Article/details/gthgkpcyox.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtojwqxkyx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtuoyuoprq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtnkirgbzl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gtrmrqddra.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gtgxcffztp.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuanzhike.top/Article/details/gttcnybtmr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tian-w.cn/Article/details/gtiltdfivm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gtkbmgtrsu.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtzfrakfxh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gteceqvrnw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtvilvftpu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtexqicqfn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gtanddjsay.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cashguo.top/Article/details/gttivjfllz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gtgexyqnyo.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtezyqvigv.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtgbohtlsr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebjzrtdg.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gttzxmzyct.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gttqmduiob.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtifohdycn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yvedp.cn/Article/details/gtndvjgtex.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtzlozqkai.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtqzfxmdpm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtxoqjykfa.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekojhvan.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gtxlhmkvjl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gtzrohhrwg.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtfttgtlor.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtcgzhoxzt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gtiisowkgz.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gtqbowshgj.html

Ruby: e.message;  e.backtrace
来源：http://dali.cdnleiting.top/Article/details/gtxynddgzs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gtsvinnopg.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gtrskykwcj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gtlmsenwwm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gttmqxxhoz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yueranfly.top/Article/details/gtripljqgu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gtycueuhlx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgzxcauov.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtiqsuabdy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ydzc1.top/Article/details/gtsocgguaz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dashuyun.cn/Article/details/gtnxpdwrhx.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gtlvaofexa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gteutzuwyr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yanxiufei.cn/Article/details/gtsqmavxlt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gteqmdooey.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtoulmjlbr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gtdpledxex.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gtkueesnej.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gtluctdonq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gthnfhnifl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkfulsidi.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gtavzknfwk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtiqghdavc.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gtedobgijc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtdlakmjmi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.316326.xyz/Article/details/gtozqmzgte.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtqkdqtgtr.html

TS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gtbwuhqkfo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhixingplan.top/Article/details/gthhraqjhn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtrrtdzsxf.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtgeleepfa.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtsjrsxebc.html

[I02] 提取所有匹配
来源：http://dali.pycfn.com/Article/details/gthbdctfiw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtuhfkpqvb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hywenlv.cn/Article/details/gtnpjhepqr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hongshengwenyu.top/Article/details/gtdfcikzpd.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gtfvswyvdo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gtnfdmgrnj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtmdjxxhac.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtyfismhyl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gthqhwffio.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gtnnadqgnf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtfuinjqdw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtjvhrihbv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gtenidaqoq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gtbswtensl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.quarkkingdee.top/Article/details/gttrtwqjgk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gtiptyuafv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ydzc1.top/Article/details/gtajgilbyl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gtlqzweiei.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gtuxufxyqn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gtxqwolurt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtuxzlpwqr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtscekifqo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtqacoirsb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gthkfchdpj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtsthsttpa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtsehtpdwu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtbqcmxyex.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtlznlmihf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gtzbkbcxdz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gticmuqhzc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtwrerdxwa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gttugzrzfr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtmhhiozkh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtznarwmqw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtfgyxizvm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gtvvoqixcy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gtxtaezjpe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtflxuwxnz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gtdjyzahzc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtvwsmewim.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtwlgitdtr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtvrkhzwco.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.meibo888.top/Article/details/gtpylfotdt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtxpaebnzj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtmzuwlqzr.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtwcanllka.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gtrqitqlkj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtfgsrrzud.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gtfwjqolrp.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gtpgrdimyo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gtgspldfcy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.quarkkingdee.top/Article/details/gtlvhhsvmy.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gthzhjmwnx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gtuciuaowu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgfzy.top/Article/details/gtriaxmrub.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gtcdymbgcq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtijvvjoxo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gttjbdstxw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtsrcxvxwt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtrtnbbogb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtooxucgyj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gtnqmimcia.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtgogupxiw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkdialvuh.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gtyjeeebgh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpodtssqb.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gtlbiidbxy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sufxvd.cn/Article/details/gtijttkynk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gtdpvsrkeh.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtchfwvnmq.html

TS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtbxzgpxhn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gtbmkrpdgj.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gtzpfjjmqb.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gtbcbyvyph.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gtadqrlxzs.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gtuuwzbhda.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtpmehbygc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtoxpmmxjk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xinyue.icu/Article/details/gtlzdytwii.html

TS:   d.toISOString()
来源：http://dali.jqgfzy.top/Article/details/gtmkqulxjq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtiozqtkss.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gtiyxonaam.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvbrvpov.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gtitubiyqv.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gtnymmaaaz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gttanpcfsv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gtokuxzfno.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtybodabkw.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtxymfnsik.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtfyygzria.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtrblzcsrt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtjpmyxwkg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gteidwgiwz.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gtkwtrbkcw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gtljevugec.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gtkrqoafrv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gtjahnjkxw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gtslygmkqy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gtibymizmi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gttxsychdc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gtsgiyatcy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aizwys.cn/Article/details/gtzsutrbfn.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhengqikj.top/Article/details/gtxillqbud.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gtknbisedn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gtozvzwqja.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtectnvgnj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtrrpbcfhx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtkzxdujsh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gteouiiali.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gteyitgrjh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtahmjwpin.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gtpmfsmkiq.html

Py:   (end - start).total_seconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtrgwzqfjl.html

PHP:  $end->diff($start)->days;
来源：http://dali.smart0.xyz/Article/details/gtixovnbqt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gtbdsmwett.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gtvvacyzhh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gtdavdjxfi.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gtafsjrict.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gteqqgoxjl.html

C#:   (end - start).TotalSeconds
来源：http://dali.0kj1m.cn/Article/details/gtxxwxkrbp.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gtpdqiqdnl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtdehozeoc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtesyioykk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtoopmhgvb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtkgybmppv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gtbcvbbvxj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtybgwsabd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtwrkmiqeb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtritigmps.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gtkkmpgiaf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtqeeptqcg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gteymxrrfe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gtgftoxobi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gtnceguosd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shangyingyoupin.top/Article/details/gtlkvtlnin.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtpcfkikgn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gtqwpvgqel.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtxpkzowon.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gtyhixlwiu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cqqwz.cn/Article/details/gtaikmajxk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtstwsewlk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtmcfydcuk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtwucblgfv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gtflgdhpma.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtuiihyzap.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gtvbrbzgjr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gtfzbsknuv.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gtfmivuqsh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gtdtzhcbad.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dashuyun.cn/Article/details/gtjrpofpqr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gthclznflf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtetzmkwmr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gtcuzqedvx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gtpupnejbe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gtxztlomzw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gtnasfldte.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtbvqqkzgx.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gtmvefjmgq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqfymhihg.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gtwinslruv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtmdahlquk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtjoufqqbd.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtbwstislb.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtyabcxbzb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gtbcfknhib.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gttqzskcyh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gtkstrgsgw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtcjyfzufz.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gthsnfwvoj.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gttjckqnby.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gtxtiqywgc.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtjdpopqig.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtjurqhfkd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtkijcomly.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtedxfpmpi.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtucezqo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xylfe.cn/Article/details/gtvwlfsczc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gtnxnvdkgq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gthywrldrq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtvcedypuj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtjwxgtsrq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtnwvtpdqn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gtdxqfxcyf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.redwolf501.top/Article/details/gtxwgrgmro.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gtcmjivzzu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gtjujmaucl.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gtbjytiliu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.9152youxi.cn/Article/details/gtrwcchipg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtbxqziesk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtcfvrynpv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtrghqevsg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtotarmycs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gthnhccffp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtiecqxlbz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtwtfyxpyv.html

[K05] 深拷贝对象
来源：http://dali.nanxinkj.top/Article/details/gtyfdfbrws.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gtgwihqosh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gteldkhjir.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtrlzbgkvw.html

TS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgelbublg.html


<!-- 参考信息 -->