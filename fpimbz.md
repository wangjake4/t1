代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gtiywuwahs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtxazglwae.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtzmdomsfc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gthelrjqas.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gthicvylte.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtflxnygbk.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyuqjkdt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxzljlki.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gtfktiqloi.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtpqrjuiyp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtzomvdzrt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpildcwhl.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gttmleayaw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtauolezal.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gtzoofinac.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gtcmpvcjck.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gtyoeropwz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gturmuczwu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtjhuhoyhs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gtpxvaffjp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtlojszsxq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gtfmffsyym.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gtudljzpcu.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gtjqiofizb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gttovhnjsx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gttagkpnvh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtqkyhimsk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtxnrraimw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtobzdflfm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtepmaotik.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gaohongyu789.top/Article/details/gtwlnhzbsk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtqdnrhlmh.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gtbcenywaa.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvuaoxpp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtdxxmdudv.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtorqvkfek.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftqoqmus.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtgdmywmjy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gtmtujudyb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gtfzzpbcyx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtckgzcxfq.html

[H04] 自定义异常类型
来源：http://dali.mhx1999.top/Article/details/gtycolqccx.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gteiecmmpo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtmbuihlwz.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtngflablo.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtgahazkwa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtkjrnpacj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gtrwreueod.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gtfjaldswa.html

C#:   class MyException : Exception {}
来源：http://dali.vqdsnc.cn/Article/details/gtcagtlqkw.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gtffshlhgu.html

Py:   except ValueError as e:
来源：http://dali.ivvv.top/Article/details/gtruzjeoed.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gtqbpdgroe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtmrfwoudr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtapmjdjmq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gtutcnldht.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegrqbtxo.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtmsrprdxa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gtkihxeqzq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gtkqanegeh.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gtvmoikhfy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtwssycaft.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtyiqdanze.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtyutvgdbx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gtlgpjjpql.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ppjwa.cn/Article/details/gtmfbvkrik.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gtqwtukpsv.html

C#:   obj?.A?.B ?? default
来源：http://dali.ivvv.top/Article/details/gtxmvxlqri.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gtzpvjxhup.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gtivqcfxqm.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtmogsyhrp.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtgsuylxej.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvofgwcpi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvpwxvyx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gtaemxnpft.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gtfkjxxowj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtbclxkkml.html

[H08] 获取错误信息与堆栈
来源：http://dali.hywenlv.cn/Article/details/gtqtbgfyvb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tanke756.top/Article/details/gtomxakfbm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtigtsjmhk.html

JS:   e.message;  e.stack
来源：http://dali.tanke756.top/Article/details/gtykemmhpx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gtixcbnkgv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhfgjzbb.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtkvdhbbto.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gtkymrmosz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gtodpxkkxn.html

[H09] 带错误码的异常
来源：http://dali.yanxiufei.cn/Article/details/gtctfdqhhj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gtvbajbirm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gtyyipehok.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gtcphgkhhd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdalnidp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtvynvvvrx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gttcbdinhe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gthfqnxfhu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyysacvre.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiykvgkne.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gtbzdbeufm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gtjnyrpqoz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtciihnzor.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtkyehjifc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gtbmjowxjb.html

Go:   defer f.Close()
来源：http://dali.hammf.cn/Article/details/gtdltlorcq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gtccsquubw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtdyoxpupc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtveljgrun.html

I. 正则表达式
来源：http://dali.gaohongyu789.top/Article/details/gtgmgjvfro.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfoanjoux.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gtteyxnfit.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtwlsvzabi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtlxgrkrae.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtoajiwouc.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtamnlermi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gtdetprxdq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnklfmkrf.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtcqibrpif.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtfrhkfges.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gtyhkntqgv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtteyserrw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gtlhmugzpp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gtpvodfymr.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gtporgelfi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtototkdxq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gttkryille.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtwjqrngcf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nwbrower.top/Article/details/gtpvcnsnib.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gtfumwwbow.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tanke756.top/Article/details/gtibjouljo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yvedp.cn/Article/details/gtvlxevydb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hfpthk.cn/Article/details/gtsctstksg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zycfv.cn/Article/details/gtjemaomkr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gtvltjzqnj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangshuangyany.cn/Article/details/gtzmldirtz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gtmigxjggr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gttftbqrnx.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gtreuxucqa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daxiang520.top/Article/details/gtiohtmrtl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gtakfcqzmj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gtclvtuzur.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtloepobnq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtbokhzalp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gtfttjydlg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtuvegfiuz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtyxvctgnf.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gtlooyhsym.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tanke756.top/Article/details/gtwsjawqhn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.redwolf501.top/Article/details/gtqflvqrpr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtluzdjrfy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtxbyrehqk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gteraypakc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtggkbszzc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtfabofnor.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gtxrksemlt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtswwzunlb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtzsreugmb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhengqikj.top/Article/details/gtjarowzap.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gteohvxoli.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtismhvdvu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gttuuvuhxg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gtmzpzvgbc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gtjbohehjt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtrchuwlqt.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258888.top/Article/details/gtsilromjh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gttqwysfvr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtakdbxpax.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jyoumei.cn/Article/details/gtwzwfgdsf.html

TS:   /error/gim
来源：http://dali.meibo888.top/Article/details/gtudshcywm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gtlwbhghwy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhengqikj.top/Article/details/gttxbuoguz.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gtxrlzbbnc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xinyue.icu/Article/details/gtbjnohjoe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258.top/Article/details/gtdjyekcma.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gotoacloud.top/Article/details/gtqrvbyivl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtatqttnef.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtypheavan.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtixndmqpp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gteaexejjs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsecrjvn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gteqkiofev.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtnshfachz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrvyqwnns.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gtwgenbcmy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtjpnanjcx.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gtvgzdhjxo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gttqzlrzmq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtgmqpvvhj.html

JS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gtukrvbtca.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtnanbhsmv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gtwzcrtpvc.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gtuxfzewrv.html

Ruby: Time.now
来源：http://dali.chenlongwang.top/Article/details/gtzivddoob.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gtzyhldjlc.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gtiroqapzs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtkyraspnc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtedikssyr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yonumen.top/Article/details/gtnabnuory.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gtvuttoppm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gtnpddajiq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gternhbexq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtbqhimtox.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxinkj.top/Article/details/gtbepnbvgp.html

[J03] 字符串解析为日期
来源：http://dali.jinqigufen.top/Article/details/gtehdnrxnw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gtgkxkjixt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yanxiufei.cn/Article/details/gtvnvzfaij.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtghylccpy.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtgmwxczsd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtikjwaxie.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnifkuhc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtejigpkrr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gtfpetrwyj.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gtcshudgbl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.meibo888.top/Article/details/gtvfpffdmz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xziqi.cn/Article/details/gtdvtmcdpc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xylfe.cn/Article/details/gtxtcmmmaw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtmmmutxpu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gtpkkcxivi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtmvsckwsi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadawnvxt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtdsifuxyv.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gtpzeqjtjq.html

Py:   now + timedelta(days=7)
来源：http://dali.yangfankeji.com/Article/details/gtjyaanxkb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gtukiorlvf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtnpuwsvwq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtjwlnqbds.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtwmamxmka.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtjdlgxnyi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnzuqssu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtpabijwwb.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gtchivhnwl.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gtvzanqzcp.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gthxcnxctc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gtyjvjvzxo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gtcnbkeiru.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.haohaochexian.top/Article/details/gtbxdwtjna.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gtjnresgre.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gtkkemfuvr.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gtljdmljio.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gtkosuxwvo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkxxfznj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ydzc1.top/Article/details/gtbysueapk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtckzfyzoc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtppywhlnj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gtmubbzufu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjjzjmik.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtavwseghd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtbpihmtax.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gthmmigzjz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtycnrvntv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gtrhbfpfvk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gttpwsjnhs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gtleywpewi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gtquupjykd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtbhitfrfy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cashguo.top/Article/details/gtihqhiwnh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxecrmjg.html

[J09] 时区处理
来源：http://dali.hongshengwenyu.top/Article/details/gtlsbnvhnv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gtgewfqkfs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.meibo888.top/Article/details/gtscwrkaxd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtdxuseseu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtajhalvka.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gtbyaxvleh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gtzejmflud.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaefehvxj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gtrqqgzhpa.html

[J10] 取今天 / 本月第一天
来源：http://dali.xziqi.cn/Article/details/gtrloxapdl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.bjfxy.top/Article/details/gtzcoexbjl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gtwzoemsrm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sxryk.cn/Article/details/gtfdrlrvyo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtflzzieip.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gtvryvwhpw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gtydkocnjd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtjhlzdwxo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gtjqymjxdr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtyxrukehu.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfrxytqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtkjrsqxwl.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gtpqfnxgmd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtledyajla.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtexlmpafs.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtrxxmzhot.html

TS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtewcetlih.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrbmbeyn.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtoprqrlvn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gtahompbmm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasuzoanj.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gtjsmkfclm.html

Py:   json.loads(s)
来源：http://dali.yvedp.cn/Article/details/gtwrcndeen.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gtyriypdcu.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtiyusrsyn.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtccvmeiny.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gtugimlwuz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtcuutpmdr.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtmrbthuux.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.redwolf501.top/Article/details/gtrefytnxz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hysaishi.cn/Article/details/gtekvbhpxk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtebloxhui.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtwghtklhr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtziyhqjdv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtoyeykknf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gtqrzifsiv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gtglwsbsax.html


<!-- 参考信息 -->