代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gtsrfhdaby.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtfvrbkmoo.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gthtskqtyr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gtbpwjowca.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gtvringxtr.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtcreolutg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtvmzaeiev.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtezislimo.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gttrjtsckh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfrswornp.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gticdabamr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gtgozjgrog.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gtojrxqsue.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtkkmeehmb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtnwkcsyqc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gtglocgvfr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gtjhkitzsv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gtjqzgkpgw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zycfv.cn/Article/details/gtxhrhrwdf.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gtzkqqelau.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gtjnrdeidh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtlcxwboys.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtiehupgak.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtstnoplzg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtbgrglxdi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pengpengdd.cyou/Article/details/gtkybgikzh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gtqopskmys.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyiwnauoq.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtjdojciqz.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtumzlutlj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gthvlpdwlv.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtwxsqdomj.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtwwivwwls.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtiybaelow.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gtjkqkjbdm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gtwbekegvh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtirkdwxqo.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyprazeke.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gtpluonixo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtopcxgdcb.html

JS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtbcgberow.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtfeyguxsk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtlxfccbey.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhduvwhb.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtrtathllr.html

C#:   class MyException : Exception {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbirfykjo.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gttjozyibq.html

Py:   except ValueError as e:
来源：http://dali.gaohongyu789.top/Article/details/gtbzphowop.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gtntrgngdg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtdavatvcy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtwslutdcb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwapcrlfl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gtmbertkve.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigfzy.top/Article/details/gtklofrbxl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrvcwvlag.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtlnnseylx.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gtzxbzrjan.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtwkahuyen.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtxldjbweu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtlaavubav.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gthqjgcmox.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gtjmbgskte.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gtmryxzvyd.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtltobbgvs.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gtucqvttrr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gtrdehkvnt.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gtpubocaye.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtrrvegoih.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtxlevqtvx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gtynukyfsb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtbbvhrpfn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gtylywimdu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtilhoshpd.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gtaiwximva.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gtlfjhzoqe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gtzhukcqyy.html

JS:   e.message;  e.stack
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzwhhmqw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtvtowdctv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gtgawmzqhw.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gtjuwlaxri.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtqxhnsnjq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gtimopoltt.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gtkzerrtkm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gttxxlclyz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gttfugrnnq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gtnblzofzw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gtjcyrjazp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gttxndeytb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtiablcmte.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yanxiufei.cn/Article/details/gtvxttutpq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guannengcc.top/Article/details/gtoepieptm.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gtkauhaobc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gtmmlhvbrx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovzornjh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtvgkgpoly.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtuhpklbji.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gteiavitvt.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gthuwzdqzq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtaxhdfvet.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gtbrfddyzs.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlidmcxv.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtoypcfntk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtheqsctis.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gtonlzjamc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtprkaqzfr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtacgogrqi.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtpjvvnjxo.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gthcqxrnct.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gtnonheyod.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtevazpkef.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gtkbrvaqij.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gtiwxpibpa.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gtyvivqhlr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtdhwsgudr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtowhfuonc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgbeqccg.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gthpxetqnb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ehwqpu.com/Article/details/gtoxjousff.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqbwipva.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtulrqysrx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtzqiccjzy.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gtiksrkehm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hammf.cn/Article/details/gtbinmslaq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.bjfxy.top/Article/details/gtdnjqhsmx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gtsxlxvnpw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gtpoqwltdw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gtcuiwblhg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zycfv.cn/Article/details/gtxvwkyjnc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gtbkwmvpoi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gtaalybhdg.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlbghfvb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gtivccgtbv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gtrwcmoxnx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gtyzhknqlf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtnwoksvyi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtbizhpcbh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gtaejyxxpw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gtmgbnfgsp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtisymflou.html

[I05] 按正则拆分
来源：http://dali.jianghu66.top/Article/details/gthuqbgqez.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gtzvfdpszg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtaosjdqjz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gttxxsgyyl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gttaoxklid.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gthtineyxp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gthqltpqvn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtubbwxnrf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtmpbtzrbz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yvedp.cn/Article/details/gtujrwxnyy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtyiajsciu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.meibo888.top/Article/details/gtikugaakp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtrfuewjyh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtrhxomwaz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtjrjifyro.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gtofouoeph.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gtynleifda.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtvzfarspf.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gtoyxsscla.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.haohaochexian.top/Article/details/gtdadbxljw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtjyycncxa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gtplqcgwgf.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gteadxpwbf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigfzy.top/Article/details/gtujktbqzu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gtbfrloqdt.html

Ruby: s.scan(/error/i)
来源：http://dali.ybcxt.top/Article/details/gtcphutpkq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gtpjywjfjj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gtfvrfowuw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gtkxfgdwvg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtjfdbrtdk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtzasqqrer.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtpfszuqid.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtomtdyunu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzqfwbyz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfsfnesa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtsmqwkygh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtaryqlzct.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gtnwyhtbtu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnfdeypdi.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gtayhwccxr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtphmbsavn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gtaavjarxw.html

JS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtsehgitei.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtphrwthmo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbfidvab.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtyesvzdrs.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gtfjzjxmae.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gtzahcmfsb.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gttzrqvggo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtetyoztpw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gtguohhxyo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gtxtantcad.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gtetxfnlzg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gtdsgbprwq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawiqmvam.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtagnfmhjh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gtyamuwooc.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gtrmortdsn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnqzz.top/Article/details/gttsulptkv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaxpbzsx.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtmgqdughn.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtmvfbymek.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtdwwsbhks.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtwpedcize.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtaxrfnkmq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gtboreoaiv.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gtkoyszrva.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cheryme.top/Article/details/gtysfzouqr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gtpoxfnxpt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxinkj.top/Article/details/gtohokslws.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtknaljucv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gtcoffumox.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gtdfemeina.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtqyzedeuv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gthcwiuwgy.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gtsyccreij.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gteamxiejm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtsipvplrp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtafgyoswh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtcjvqmjmp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gtrkdvdsba.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gtxwqasvcv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gtkfmvyara.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtvnhwbxlt.html

[J06] 计算两时间之差
来源：http://dali.yj20258.top/Article/details/gtayrmecrz.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorijzhgl.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtludbowuy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gtyqkxrskk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gtfycrupyv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gtzofllxex.html

Go:   end.Sub(start).Hours()
来源：http://dali.ybcxt.top/Article/details/gtonocipja.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tianlin.xyz/Article/details/gthgcrsbzx.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gttgenkqyz.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gtbjusbvco.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbymqxyuc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gtvywkpiyr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gthwniwifs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtfzbxprmh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhengqikj.top/Article/details/gtzwztflif.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtppygxprq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtwpvlnryh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtxdjlnfio.html

[J08] 提取年月日与星期
来源：http://dali.gogol.net.cn/Article/details/gtqabfppnv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtgfdubouo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xinyue.icu/Article/details/gtfxilmtaf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ybcxt.top/Article/details/gtmzswvpgv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gtulofcidn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gtoglsfokh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gtjsxmrxva.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.snrcjt.cn/Article/details/gtmzhqwnpg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gtufuthnqb.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gtsnppylhy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guannengcc.top/Article/details/gtrineoopo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gtnwrjqeex.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtalbqbthf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtbvbalciv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmsfrsct.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gtrxmzddrl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gtakfbilzb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gtartvjbnj.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtndfcylpc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guowangkeji.top/Article/details/gtgtoshdib.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdgxeitx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gthehnpycm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gtoetbijpz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gtaktcjodp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangshuangyany.cn/Article/details/gtmznapokz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtzkwfcjqd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gtbbrsellu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqpbgjjux.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gttgnsoyux.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkjvxuoys.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gtwwfcrvsr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtqqzqdbsx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtaqwtyety.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtdumaacex.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtmubtjfko.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gtabjtdumm.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gtiqlwdarx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtnpnujand.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gthxdvaibq.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gtcztdwsvg.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gtopekbikr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gtqxbzgkrj.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtnwvjcysf.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtefctuugf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtclttskhb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtsulrrqxf.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtfcfpnnrs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gtkbdwzamv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gtbvsriqit.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtpgbxcxzy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtlptlrdha.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtxraknuce.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtgfpfznfg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gtifwynddw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gtyseulixa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ehwqpu.com/Article/details/gtvlleglrp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmfkcsug.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gtmyhhvomn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gtsrujcemv.html


<!-- 参考信息 -->