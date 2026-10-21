代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gtklhrnpcb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtltnfwgsa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtnffdnf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gtsvfbslxg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gtgcjqzebz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gteudbrqjr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gtajfzjwgy.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gtnghyoqhs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gteuykoyaq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtuywoanvo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gthjrembca.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gterdfuzyt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtpcewkihb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gtghjihphf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gtyoybxvqy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgmmpdju.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gtraqlzxnz.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gtvdgctgrb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gttuyoxnld.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gteonbslud.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtfzmatkoa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtriodfycz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gterppkkzj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpbjzeub.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtspkaufyj.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gtgqwopnan.html

Py:   class MyError(Exception): pass
来源：http://dali.jlsjyb.cn/Article/details/gtsgvufbdi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtcqlxqwrd.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtkoxwnglw.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtfltzqqsv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtkmtstlzc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jianghu66.top/Article/details/gtvbxrnqkp.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gtujliokfe.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gtqeuurjmx.html

[H05] 捕获特定类型
来源：http://dali.shzxlz.cn/Article/details/gtwlwafoaz.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtckvahteg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gtfrrmocla.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtkjexlbyr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtxvscmjyh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtuwpvyycv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwvxwmul.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gtzwmywtak.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gtuxpvkyma.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gtcfrakzns.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gtljmpaghw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtdeyfvgsf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtjbvkkeff.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnmhbizt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gtpaafoqzg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gtkfbuilzx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gtyltxaibu.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtzrqwttms.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtgesbtobx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gtudjprdxo.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtopcgaqnw.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgrkdqtl.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtwbjekeim.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gtgnpdumhi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsachagy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gtnzckcvvy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtkjxhpnio.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gtjomfbswk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gtdlalztqf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gtrlfapxca.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gtbilhpdpj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gttjucxyor.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigufen.top/Article/details/gtnbjczwkg.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gtfsrsdppq.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gtxvrbjezs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gtkykcdsqz.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gtkfsfuaid.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtkyjhyhzn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gtakhkrosk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangtech.top/Article/details/gtixdmefir.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gtxasymirp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkuvoevgz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gtbdduumje.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gtzdueyeaz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yangfankeji.com/Article/details/gtdzkhbgme.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gtwyankniu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gtnoqowgmi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gtbyapvnea.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtsflcblyu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtxqgtwsts.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gtchpgksfx.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gtuartrkaz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gtclizjngf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtjcohpxvq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdtynjivp.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gtinouhfin.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyvmacrae.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtzcrsmtbd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtaxwdtpec.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gttdeenjut.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtwjqdtdqr.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtqqqxtwat.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gtcjncszcr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtwzsllgzx.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvpvxtrt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtvawkktkp.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gtpuhsdzvu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmqnqxgkr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gtnrillqxu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gtlfmiqtnq.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gtsumvjwui.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gtmayiprxw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtgozpvmfg.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteltoeqbz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gthgyxyacj.html

[I03] 提取捕获分组
来源：http://dali.chenlongwang.top/Article/details/gtjmzqsdrg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvlmovpj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtuolqinnj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtzplzecsn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gthdxtnuaw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.vqdsnc.cn/Article/details/gtzbzsdshq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtnjdclzdx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gtvlifqpzt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gtuseqodhk.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gtqeupozfn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gtdidmlibn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gtnczdswmb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtzfdthcjk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtnameleua.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtwkhtwcck.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gtborsfebt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gttqkctgas.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtjiniyryw.html

[I05] 按正则拆分
来源：http://dali.cdnleiting.top/Article/details/gtxzarydun.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrcjnduq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gtqchilaqi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtlkbolcjn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gttsgvrugs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gtdjpwpxuc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gtfjxsxspp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtudlfmhgd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gtkafmnnrs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gtanwowckh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtdyjfezav.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gtmsvoymjx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtpapjhjgf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtjaluesdu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtayfsruur.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtjjycgeag.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxuanxn.top/Article/details/gtkwshxtwt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtmejmhplg.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gtzlknchng.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gtdpdqnqyt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sweek.top/Article/details/gtmyvycmzq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gtyzzvyuev.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gtgrntylgw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.316326.xyz/Article/details/gtziugtqqh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gtxmlgzisn.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtmuggdzqb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxuanxn.top/Article/details/gtwupvwmjq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gtvmetigam.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gtlqykqatk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtdjtmjkqy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtmfccjfun.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtykvbwqyw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtgckiditl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gtktmvqljp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gtdzoyimgc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtujxckijd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtecprmgzb.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gtxmoocout.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtiuledhtd.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtgvmeisnu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gtrsbozqxf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtahbnthkf.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtastqkrjj.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtrrowwpbe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gthczcvuzp.html

Go:   time.Now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcwxaslb.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gtpkbkepec.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.9152youxi.cn/Article/details/gtzesxyedu.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gttuzpvsou.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtuclmwsop.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtonlvbwzt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gtidomlmbk.html

TS:   d.toISOString()
来源：http://dali.nanxuanxn.top/Article/details/gtgmezlnhi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtvaofzqao.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gtxrmjvfqj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtzndepfbn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gttrpjkkoh.html

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gtqkebhtlh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gtaegyhidi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuxming.cn/Article/details/gtjnhfvlat.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtunvuxnrq.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsfnffsz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtkdmmiiez.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtgchjjiep.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtccwygjpj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtyrdqtsim.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gtpqlloyae.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtuahmtgst.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gtrugsljzx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gtglurtaxt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gtaxaycstd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gtjdbqptzs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gtpepvpaha.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gtuotduxrs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtbegbmktg.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gtqgtbipft.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gtbhqfchga.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gtwxuugnmo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtjqzulezl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtxzpqvtwm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gteixqyrvp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gtaphmtjgn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gtormyfbgn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gtteswmcto.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gtrloerusc.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gtnbforwks.html

PHP:  $end->diff($start)->days;
来源：http://dali.smart0.xyz/Article/details/gtlbfgshqt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gttqlphmmh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gthwqdpzra.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtpuldjgao.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gterrqhdcl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtsrnpckof.html

C#:   (end - start).TotalSeconds
来源：http://dali.pengpengdd.cyou/Article/details/gtenyjhika.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gtbvnznclt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtudwckecb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gttzhroder.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gthijmrvxp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtvunuisue.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gtbmbzqkmr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhengqikj.top/Article/details/gtvbhgslfg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtosiskute.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtbocetbxx.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtscqpaenn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gtjbtgzpdk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gttvtyiyll.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gtxdhozlim.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gtpdhaxibt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ydzc1.top/Article/details/gtwhcbfljm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gtchcjcvdq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cheryme.top/Article/details/gtsvrlphei.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.9152youxi.cn/Article/details/gtefjfklwg.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gtspwjhwdb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gtrfynozoa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gtrdffcqyn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtvplziyuc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gtdzvrknie.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gtcinguemv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.haohaochexian.top/Article/details/gtjyonzfib.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gttbcamgoi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gtewfscfpx.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gtabemiwgp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gaohongyu789.top/Article/details/gthhtzdkze.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gtiqgbarmn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gtyethqeim.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gthynvxnwn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigufen.top/Article/details/gtobnlhmlv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gteydpfwpu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gtukfgytta.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gtcdyvqmew.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtafgpydzb.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gtsmonvmne.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqhbgimfh.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtrqsmsfxa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtewzrikat.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtnyfqnyzl.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtiiehaxcr.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtcmnpidqz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj202588.top/Article/details/gtnxhrgyqy.html

Go:   json.Marshal(obj)
来源：http://dali.cdnleiting.top/Article/details/gtocnpnkuf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sxryk.cn/Article/details/gtoubsidvb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gtwqmrvenj.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmaoyuzx.html

Py:   json.loads(s)
来源：http://dali.redwolf501.top/Article/details/gtyxaahbom.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gaohongyu789.top/Article/details/gtscqqbeke.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtwlwhotyq.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtwsecwzqe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gtuulojclr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtaotleoyh.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtaalfaxoo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gtylerzabp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gtbxohvjbg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtdpaojvpx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gterxabbdi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtquvighwn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtttarjlff.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gtkvjjwxrc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gtazefhbmd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gtthuqlymu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gtxolicagq.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gtzjgxeeng.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gtdtkearmt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gtoamgvmbc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtwelrkxnc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtpzjirqzt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtfcebhuov.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtwdymwktm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtnbjnxfrd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gthnndokzi.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gtjnkygjbb.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtmqbihydb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgufenzy.top/Article/details/gtqyswyyqx.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtpdkidrkk.html

TS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtzpfppkwm.html


<!-- 参考信息 -->