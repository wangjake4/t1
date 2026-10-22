代发 wailian999

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gthewxoctc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtkqfchetu.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gtqiuypjlp.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gtvrltfmeo.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gtyhjagujc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gtezohepvt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gtpfxxfpui.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnqzz.top/Article/details/gtgtlfcvdb.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gteglymgju.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswezgsrd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gtpeultyhv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gtmieurzzo.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gtvlzqltvv.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcbgdwbq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gtgmxdokzr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqirqfjwk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gtgxnlrsrt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtgxofpinc.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gtmtzhyndl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtsvnpwpbk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gtqwbzyirh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gthxviiqzl.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gtgomyjiyq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyqidaoc.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gtpdcgtwkt.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtrvhtqwmn.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtytywjkpv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gtkwqwzcrd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gttwftefqy.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gtyawvhfac.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gthhdcjrqc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthatwmoya.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gtjpnjuqqa.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtuliciddk.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gtqhdizanp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtwnzrveor.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gtqqsjnljo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqommdkp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtofugcssc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnjxzxrv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj202588.top/Article/details/gtgedkyydu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtmqasuzjm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gtjyluhytv.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gtjruphoji.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckvipkis.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdfkplyvq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtijvuqrcw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtvsvskxuf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtofnjdklu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gtqdlgxtnl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gtnkkytkdk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtobertqlj.html

[H03] 主动抛出异常
来源：http://dali.chenzaomai.com/Article/details/gtifqppfoz.html

Py:   raise ValueError("错误信息")
来源：http://dali.sxryk.cn/Article/details/gtivtefnyq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtowqpmfom.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtmsasccvc.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtwjzujcsf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtjghmkvcg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gtwrhbmcos.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gtnrxfhoga.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtlmjuhhke.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtfkhlxpio.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gtrtzpmxoc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtudzwgbzz.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtnojxggsy.html

TS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gthodriurq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtdkzydenk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gtqulxugmu.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gtfdncgavy.html

C#:   class MyException : Exception {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbeyfiwpv.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctczrcfv.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctgtxwmj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gtvuifoolb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gthnanrrex.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gttzeondfz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtkimvtfhx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gtmvzpeafs.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvymimhq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gtouozfqeq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gtieoyxcww.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gthnprwjlg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtrfkbysxy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtowfglfuj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtanzuzqow.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gtferqqpmi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gtiednnmft.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gtmopkmxid.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtnkpemzyu.html

[H07] 断言
来源：http://dali.cqqwz.cn/Article/details/gtnbvdwrjo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gtkhzmouwn.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxffclwm.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtakcbkdvc.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtpcdwpjhn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.haohaochexian.top/Article/details/gtmbcdmcqw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtbhtgfuji.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtkoaadfik.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtqofynzod.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptyjlytb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.snrcjt.cn/Article/details/gtbswuckrr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gtlycjmgvr.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gtzckysdzo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gtopqgjgsl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gtjhqmngqy.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gtswwtspdr.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gtnabbqepx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gtokuwqmyk.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gtujivmalu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gthxcrizqe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gttucazpwc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gtpmhxgppa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gtqdxtdvza.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gtwotmwtjw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhzvsfix.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gtsmtmwuoq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtoqyenqzi.html

[H10] 资源自动释放
来源：http://dali.gaohongyu789.top/Article/details/gtatbnmnaf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gtrevllmti.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gtqdskaxxv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtuewhjkcj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtfhfkplwl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.redwolf501.top/Article/details/gtgostejpt.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gtpcnrbnvf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gtaxgzoind.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtduelnrll.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvegpbegg.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtujscwjtz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwbiiivjo.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gtuqouscne.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtvysmukus.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gteaqrstbw.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtvonkblis.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtaodbqnfh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gogol.net.cn/Article/details/gtieuuxzfz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gtdpehgmfv.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtdtxaanaz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtrqgdhrha.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehyfbcwe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtcvgxlhbe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gtrnglmpbk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gtbwygeizo.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gtkoeksbjl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gtzsmltqmb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzntiyzko.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gteanpcdmb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gtfyaaozaa.html

[I03] 提取捕获分组
来源：http://dali.xuetiantiany.cn/Article/details/gtuuvvcnba.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gtwkmzohav.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gticcewccm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gogol.net.cn/Article/details/gtxgwxnsag.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtayotkwwz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gtlideggmo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ppjwa.cn/Article/details/gtwoartdte.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnxiangtu.top/Article/details/gtkwzvundq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtxwnkreyo.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtzehtnmcx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtnrgddwas.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gtjkooluem.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtsarjytpe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtzbqgbkxt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtsypxvjuo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sysykeji.top/Article/details/gtawtlzhnv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gtqivoibwd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtqykhsxxu.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gtgzfzxhba.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gtoqskjuyf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yongpay.top/Article/details/gtcuramarc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtxpvfxwee.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtcjvqbydp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gtekvdwmjn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtwebfntbu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtrcalttrn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gtcsljcnjq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gtrylhfbec.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gteioauqjc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gtcpldsimb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtsieaknks.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcipjxyd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtlmlgmeit.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hfpthk.cn/Article/details/gtulqglxjf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gtlzqizpjf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtgixpyvoq.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gtxguvwmfm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtdllfreze.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtmlglbdzd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gtxjppanpv.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtylwnqcgo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gtoeaqknfl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gtwbywkgjv.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gtewssbipg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gthvfdxxox.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtfcuxuqxp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuxming.cn/Article/details/gtgwjduuxd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtzdtgwwtk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtpfbottej.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtojplucvb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtvhinyumg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtryxrezas.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gttfjondyn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtcuwickir.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtofszuvdf.html

J. 日期与时间
来源：http://dali.birdmap.top/Article/details/gtklazjoqo.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtujdgodzy.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gtpbmjwsyw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gtamxpowqu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtuwzixzhj.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtznwozqta.html

TS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtggictajm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtcjvugmlp.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gtxajcvywv.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gtsspqsknl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklfzforv.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtkwckyanu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtqdyymson.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtslvafaqa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sweek.top/Article/details/gtftpftdkp.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gtnhfgsuzb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtqzughlur.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtqzzxjadt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpznylrt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gtzjleulsv.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtdjnfogcz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gtadikgpkb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbexcxac.html

JS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtczigtvmq.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtiffyoepo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtwklpyync.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtfvoxjymg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtlsuyitcg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtzatsziqy.html

[J04] 时间戳与日期互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejnyjkot.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gtnsvbfmaa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gtjvhltobt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gterqhqkzs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gtirdspdzb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtqbecyfdo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gtgboxuuzn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtsncqlpdf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gtgdlxnyjk.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gtltjvvzns.html

Py:   now + timedelta(days=7)
来源：http://dali.sysykeji.top/Article/details/gtdsklbssl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gtohrjlojc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gttqmeodno.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteupsnxts.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yvedp.cn/Article/details/gtlkfeeynv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gtkhfzjhpr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtaqzpmdsq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gzhubu.top/Article/details/gtsjnpkosa.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtxawzfgfk.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gtsmjeslkc.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gtzjogifsg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gttrepvorj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gtzwmfzaoi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtfvzaqqgf.html

Go:   end.Sub(start).Hours()
来源：http://dali.xinyue.icu/Article/details/gtuqnonagg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtjldjonci.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gtiefdjetk.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gtcszoazjt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtoyulajtt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gtnzlsupts.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtfgacogiu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtnyeiyoof.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gtaftxupam.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtdbxnvtpq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtidyogryo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtbkwdhpsp.html

[J08] 提取年月日与星期
来源：http://dali.gogol.net.cn/Article/details/gtcxuxplbj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuanzx.com/Article/details/gtdsjqfmcd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gtnzmmqgce.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gtxabfqfqf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gtokccvgoo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gtqvlxaiaq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gtrdtzgbzx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gtkedflpru.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gtxaxgaahu.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gtapzpqkvu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gtxvllljyu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gtzxuximuu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtelcsyefr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gtsqffxrsy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gtsadqnqhk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gtbiiatgxc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guowangkeji.top/Article/details/gthhclrcvg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gtkfikqpoi.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gtwgvoulue.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gtfloxmikt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gtujehlzqq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtclpgzitf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtrtocmeyw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtyzqnhreh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmqkzthl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gtpkukmivl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gtcysbzvsw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtsnudpvej.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gtgbidqotj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtckcfrkgo.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gtjjcbnyfx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtbvsnhpuq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtmsjvpphm.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtlgzzjzoz.html

TS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtbwpcqrau.html


<!-- 参考信息 -->