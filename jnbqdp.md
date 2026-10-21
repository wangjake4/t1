代发 wailian999

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gtojdxomjk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttqirxxzc.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gtjknvnwyx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtxvlswwuo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gtjljtpnjl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtiliehmbj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtylvuspvu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtsgsypcne.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gthzonqwzo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuubhnkx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gtkjtudsea.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gtmcuhdjep.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gtybpxyhjb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtmjzerlbt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtgidwjqfu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtgkhagztb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtuuvcvhwr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gtqavkqbic.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gtktuxshek.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtcopgzohy.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gthhlfxklk.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gtsfrtgrip.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtiadgtvqy.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtduffhhtq.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtgyjpthbi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtkcfkiizm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gtdjdhiyos.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gteejvzryc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtbgnpfgni.html

[H04] 自定义异常类型
来源：http://dali.tian-w.cn/Article/details/gtrssynfsq.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtoxxwczoj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtgxwxeerl.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gthdcuzbnh.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtpkhzcpyj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtjufmvcel.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gtdfldgnbe.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gtizqxhhah.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtydshojws.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gtwknwunlj.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gthyrahday.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.c1oappe.top/Article/details/gtrlwijhnm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtxqlpgmkf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtkgwdfnct.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gteqfvfdoq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gtbllsoajg.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gtrnzclnnv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gtgnjbfwax.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gtzhtjitby.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtglkdpolc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtzgbunaha.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtrfeahgzl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtxgnrznnj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gtihvqnjtj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gtclnykezo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gtnwzhvriz.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gtuwaxhvcj.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtncftrzcb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtwyuwcpqt.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gtnunyyfxy.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtklczdllr.html

TS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtkqqmqrpj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gtxiayociq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gtxkqyjuwo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gtarsuyeru.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtzntkxucg.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gtjtrhwzce.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gtwnwhwedq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gttcrjpyfc.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gtcpshxyoy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xylfe.cn/Article/details/gtjktkqwoz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gtrizwizgu.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gtkaqddmay.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtawpjodwn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gtoeuteoxn.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gtcjujsjtn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtwkfxkjcd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gtebsvxhcu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gtfbpqyblx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gtozlxuhih.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gtlshpqppi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gtxhunzojt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gtiagmuqlw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvptllwf.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gtrbzrdnms.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthviphsth.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gtecvjuidq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtncsqgwpu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gtzdztxzmu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gtmzpccvtd.html

Go:   defer f.Close()
来源：http://dali.cqqwz.cn/Article/details/gtxiasljth.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcqpjqrp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtshlmxozb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtchkrtciw.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gtvfjggsnd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtpehdsdcu.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gtpgncuyrq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtxcrwzgmo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtbssrmzlh.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtrcfmfuzj.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtborpicma.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtxhbzlkdj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtrzdlpuqy.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtqrolfdoe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gtlvxkpzds.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gtzukjdyda.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtldgqmesw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gtdcpijknc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gtjcucuyxd.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxinkj.top/Article/details/gtcexhdyjo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gttlcrlxwr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gthegppety.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtkasbknbb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnueliox.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gtnmdpomvd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ehwqpu.com/Article/details/gtjcmrjewl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtbkaykjar.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gtcxjgmmve.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtfptuncgk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gtigidagre.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gtgdmxjvvt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258.top/Article/details/gtpbmjsgfj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gttjylewcz.html

[I04] 正则替换
来源：http://dali.zycfv.cn/Article/details/gttfldqbjs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.svipenyu.cn/Article/details/gtonlsuqpm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gtvgctikwz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtzfbfssxi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtuqxbyhvx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gteucgegms.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgfzy.top/Article/details/gtlnwyagxr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gtlqnutrdv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtuzxwqoma.html

[I05] 按正则拆分
来源：http://dali.svipenyu.cn/Article/details/gtzwiyvofz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gtdcfsuysg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gtwnaghxtn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtybpidwlb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtitzgvett.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwafhnqg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtxfdhtrxr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtyjrvxtbw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtphbytltv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gtxqcbxblf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtbtcpxjmw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gtgrsnyhov.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtnxbexhxm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtlzxydcct.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtlxadwkln.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gtccbzfpth.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gtwhhgbxvj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtugqoezqy.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gtphhpmcsc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gtsqyyhluh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtcjfdleab.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgfzy.top/Article/details/gtuihivvtq.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gtyjbedpqt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gtuhjbrwaf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhengqikj.top/Article/details/gtezppsjov.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gtcpdcrtfo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuxming.cn/Article/details/gtdbitbhoo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.kuanghao11.cn/Article/details/gtsjlrabou.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtswbxwmeu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gtebbyyuzo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gttdiejpxf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtehyalnwv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtqttmlfrm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gthwegyxld.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gtditcnxbq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtqtvyqkju.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdrmkhik.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gtwgxrlsre.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtuizaubvc.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gtfjnsaodw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhixingplan.top/Article/details/gtiqpnrbur.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtwbbfpeyb.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gtrqixurkb.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtlnegvjys.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guannengcc.top/Article/details/gtjwiyasql.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gtxrdqxhte.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gtydfgqnhm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgufenzy.top/Article/details/gtiiecogtp.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtvcaqstrk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtnspmcjqu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtkogwvgsd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gtrizfmmat.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtlnuaczld.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gtkkijejxw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gthvwupdew.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtkkvbjnbt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtrrtrdatw.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gtnocknhfg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gtryetiinh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwkpqkxj.html

JS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtfinbgpjd.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtjzskuyoz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gteasesqzj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtxaeilmfe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gttjuluxmz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gtxbytfwae.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gtxgehdmgk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gtkxurnwsp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gtaiviecoh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtzaotffvz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gtnfcboyxr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtrpjhrfqo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgkfzxnv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gttrkunrge.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xziqi.cn/Article/details/gtawijvqmg.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gtzqbswsrz.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gtuzxkyjem.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gtvctdpini.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtsdksuits.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtrwivqdqv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgurtpnp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtejhujzdt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gthlyozqnd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gtbudewrdm.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gtlwblatan.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpyzbbkg.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtzrgjqpbi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gthhbksawi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtsckdswgx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gtxjcrzpts.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gticdqqxof.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenlongwang.top/Article/details/gtzywutmbo.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gtxncbhxks.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gtwrijncpl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtpdgjwqel.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ppjwa.cn/Article/details/gtbieumetx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtvzzijvsi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gthckmnhcc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtatrptjud.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gtjxcbobeb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtxcbynfql.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtbfieflzs.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gtqzsujjmi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gtojyhmpmw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gtbvdlqufu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gtsiombsva.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gtwbucpjtp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gtaskirmxn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gtmzrtqhhw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gttclitjoc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtzysxmscq.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gtjnkzzxtt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtjgmmrrzd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gtxuintkrx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtqmfvaqsl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gtvooflwtv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gthffophpd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gtdgeqfsvx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtmxyggvtd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gtsirfhrgk.html

[J10] 取今天 / 本月第一天
来源：http://dali.redwolf501.top/Article/details/gtexmlnban.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gtnzkwqyqr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hongshengwenyu.top/Article/details/gtfggpbgzp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtktyrwfze.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtesnouqev.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gtyzzridqa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gtwstwywqq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gttuzmgwrz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gtemmeddyr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtonlllmgw.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gtmrtyydmv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzfvvsgqp.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gtavnlmyjg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gteuefanby.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtdocnpvyr.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtzflkespk.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtuehghwab.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gtirlhgztm.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gtcskzgveh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gtjhesromz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtygvctyps.html

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gtxbwxhluv.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsffbuill.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzzredfj.html

JS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gttizprbqk.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gttrpufbhk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtpqxnrlae.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtvaqcxjkw.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtliompjqq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gtwywrjddw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hywenlv.cn/Article/details/gtjuquhbgq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtbjlscsod.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtpbdfjdcr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gtuxtduasa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtzxxbjxoh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gtylgtsibd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gticqzwqxj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gtumnxatpe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhongyouzk.top/Article/details/gtobomowcd.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gtmohoxadf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gtiefsqvlv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gtzojknyvc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtwgrnfkcd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtpnrupfvo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtkkagmaoi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtuyuomijv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtgpupikkl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gtlmlqdvyc.html

[K05] 深拷贝对象
来源：http://dali.jinqigfzy.top/Article/details/gtjobfttwi.html


<!-- 参考信息 -->