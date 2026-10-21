代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gthnyrpsly.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtdlsvvnly.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtyfoexhys.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gtcmyttmxd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gtnsulcutg.html

Ruby: obj.instance_variables
来源：http://dali.quarkkingdee.top/Article/details/gtgisjwdzo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtyclzhtqg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkjfxrxt.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtocfpgizk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjllkfkmu.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtlvvnktve.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gtbglacthy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gtbqgicypf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyboiqhi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtimgdbmam.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gtuhrcrbco.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gtcchfvodp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gtgcwzvthr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gtkamsshef.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gtmzfyxrgg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gtlocvdpyn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmllpdlse.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhbegaft.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtlsnizhkp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtypqrevjs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwzriqls.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnskfosh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtzaqzenvp.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gtbmvlyyrc.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gtbbpgswnr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gthzckzgpc.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtemcjurpf.html

TS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtxjobgrgd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtdkykljfl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gtztamiozi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gtjddikcuw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtlfxphdku.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gtuxcaxbwx.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gtfpiarvyq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gttwaqradk.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtesuvwotq.html

TS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gtkgavsvoc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqdhphiia.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gtqlqoybrk.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gtzqmjgddx.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gtcibytwms.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtsrzzmupq.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gtvutjlrsb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gtoavphjge.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfjrhcns.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtqeywjxmg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtcrfzylhj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gtyvenxfwp.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtzlbslcfi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtmoukjwaq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gtnkgftjts.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtnlygsoks.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtzyncdzqh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtlqmzlqhm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtolirjfxj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gtacteqmon.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gtkhdaftyp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtrhkhblfd.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gtaqssnveq.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gtyrzxxrib.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gtbdglmhlr.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gtyuvoacdp.html

JS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtvbpxkost.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtyuvalqdq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gtzgwcrxry.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gtgeoybryl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtnbawjvth.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtvrnxletr.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gtvienxihp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.snrcjt.cn/Article/details/gtazopzxbd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gtqwbhhrvm.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgefvpryj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gtpykebapi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzudtvly.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gtupknxuda.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gtivpgyaok.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gtoazrvegc.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gteihyrhnq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gtgdxvfifq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gtkrjxvveh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.haohaochexian.top/Article/details/gtypwybksy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gtmljethlb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gteqkqzbhg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtfapwswcl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ydzc1.top/Article/details/gtduhrqcve.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gtgfirmzkg.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gtklpsmmjp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtltixxomk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtzoizkrfn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtedwgmrkh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtrvtwgypl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhengqikj.top/Article/details/gteirzuxbx.html

Go:   defer f.Close()
来源：http://dali.fzhhl.top/Article/details/gtqoocpzcr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtmwxdymed.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtmcbgaqxi.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthzxrbpik.html

I. 正则表达式
来源：http://dali.zhoulong.xyz/Article/details/gtxanjmifb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtgawrmibv.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtzixjbsyb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtoctppfet.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gthziulvcy.html

JS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoyofhpo.html

TS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnsnkjxj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gttgphvwab.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtblzkpqcf.html

Ruby: s.match?(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gtxasvrvpk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtmqsojhtx.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gtctrlwrhr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtjgnraebz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gthyukeggg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhiwuduotai.top/Article/details/gtjnfibixu.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gtzsnwkkpe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hywenlv.cn/Article/details/gtwxvuharz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yongpay.top/Article/details/gtyyqhcurc.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtkbplgeog.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gthouamqqj.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtavjplewb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj202588.top/Article/details/gtxlwizlsw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.birdmap.top/Article/details/gtmehyzfgl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sweek.top/Article/details/gtbypandpv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gtptcywquy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxuanxn.top/Article/details/gtvmhhgwkv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gtefihgbdr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gtkmuorvle.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtiytgpihp.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmktjwjg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gtgwtfcaid.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtqqzehhos.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtguphddxj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtqqwtvrln.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtssxtydiv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtczuaflsa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gtyvrbhzsp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtdhrcpvwa.html

[I05] 按正则拆分
来源：http://dali.nwbrower.top/Article/details/gtvigerodg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gtaymavgzw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gtkeumbqbv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtlbtnskfc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvaxtqeu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gttexsoqve.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtqgsocxav.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtpmtncdlv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gttravzrek.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gtlznqwxjf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtxzviygwo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gtkdcoqzjc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtkpsaejaf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtisbtmcnw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtpvpmgjuz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyapcadv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gtorgpwgzc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtrbzqdrij.html

[I07] 忽略大小写与多行模式
来源：http://dali.gotoacloud.top/Article/details/gtcehxcxyo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gtzgwxkptb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtgbfuwpgh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gtcvuhpnyy.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gtddyyfdpy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gtpwmdwjuf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gtwdjokzmj.html

Ruby: s.scan(/error/i)
来源：http://dali.havefunace.top/Article/details/gtxwncqfdk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gtfsqfrfxf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gtpqilzfdf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gtkokujylz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gtnsztojul.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtuhoilego.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gtkfmkqhkm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtmwahvdhg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258888.top/Article/details/gtasdhycgx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gtwyzviicy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtacmcnwdr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtbjktqnfb.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gtuobjkomb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtgjfspzdc.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtujnbixsd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gtxklicefp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtqisipeyc.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtmsxvomzv.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtovmufpsc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gtudxgfkeg.html

Go:   time.Now()
来源：http://dali.9152youxi.cn/Article/details/gtlymxqola.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gtgvmnixrr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gtzovmxpcd.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtfabsendk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbgeuwvz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtpvmlpgap.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgaelhuc.html

TS:   d.toISOString()
来源：http://dali.mhx1999.top/Article/details/gtzizvibzq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gthvranlwt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hfpthk.cn/Article/details/gtacnasdab.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gttxldtcql.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.iojbl.cn/Article/details/gtbhngsrtu.html

[J03] 字符串解析为日期
来源：http://dali.hammf.cn/Article/details/gtvkyyjzvj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gtlksaizes.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gtilwwtlod.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtzbnxllhm.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtldmolgfo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtvpmfffik.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtbopwxgzy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtuhpiduae.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gtjynkifkq.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gtjkewgniw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.meibo888.top/Article/details/gtymgajfro.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gtivhjiytp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zdqjudy.top/Article/details/gtlzrfcetp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gteicznind.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gtveqkreqy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gttyttmxzf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gtplqtqfqw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gtxysgckfz.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gtdkstwrrp.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gtppuvydxs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hysaishi.cn/Article/details/gtspalykpx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtqimjdigj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtvhzkpqgk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zdqjudy.top/Article/details/gtzjizcotx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtkyrbxung.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gtpacvcsqk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtxegcbxjb.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gtwnamqixi.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gtxtbuniqt.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gtopygdknd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gtjrezapte.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gtvzignxpt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtpepdheue.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqclpkxh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gtquxnplwi.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtmzgppzie.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gtpyxhalpw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfivciobc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangdashe.top/Article/details/gtoaagufdj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtlbuhmyyj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtapggffmy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yonumen.top/Article/details/gtisincyyy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gtxcjebazh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtzpxhpfyh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtgjhhgkmn.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrkdghyl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gtyytffqby.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gtsxniqgyo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gogol.net.cn/Article/details/gtufqkmvxz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gtemkfglug.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gteoaetsme.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gtcyffpxjv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gtitpuujxs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gtwabgbtcn.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtfzxylraf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbaamsyv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtzadqthpq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtkqytmelp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gtojlkmyly.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tian-w.cn/Article/details/gtbvlahoya.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtsuvfkgsg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gtrcurgrgn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gtovqsquab.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtxylltalk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gtkkltcqdf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gteuivjwls.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gtsffxnzze.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtcbqpebnz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtvnmjnphz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ybcxt.top/Article/details/gtzspdvscf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxisbnfn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtwqunpouz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtyifjplmh.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gtmmsbqzsc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtpimkpyqj.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gtnsrkcyqp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtwrhwbagc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtloimbsjf.html

JS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtcjtivxhj.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtuugokzsp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtrbfgicoo.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gtossyresw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gtrwwabavi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gtbnmbzqes.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gtbprhollx.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdeihsomu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sweek.top/Article/details/gtrcwkeerd.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtntinewaa.html

TS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gteepvtwwe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.andypj.xyz/Article/details/gtynlhdjxr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtwljlulof.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtjdersszy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gtxazrbpxo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gtxdloffkk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtnowvkdxm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfosykqww.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtjqiuwwhv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtmufdiqdo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gtzigwbkxi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtvbbpctav.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sysykeji.top/Article/details/gtozxqewhw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gtoozqgpsn.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gtyersuluw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gttyxjpbuc.html


<!-- 参考信息 -->