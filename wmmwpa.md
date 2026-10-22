代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtznpyfdon.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gtkyojuaff.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gtqdqvxuev.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gtrrwmhzbu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfdsuglu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtsnggpdel.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gtmhfvgpdz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gtmryliolk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gtdbgwcpvw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtfcotautm.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtcwmamamp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gtcqgfikut.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkfyrqek.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtvjecptyd.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtsmvjpgtb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtidokskrm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmokikkc.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gtqrugjldb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtlctctpoz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqzusfvjo.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlummjjo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthinezvva.html

[H01] try / catch 基础
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwcduykz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gttqwgqily.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.redwolf501.top/Article/details/gtgmpewuqm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvqsnlsg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtnwmrwiiz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gthznfuowt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxmlcrnq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtctbgkumo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gtfvzdvlry.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtofgwoels.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gtpkvtlqzw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtvvxdwxjv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtwololbtn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtxicisedp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtumxfjphs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtnkpppjok.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtmlnlgyjm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtprakgexo.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gtgcessmjm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetvvonpa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtcizjxhva.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtcqwxrlbz.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtxmhubpgb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gthwgerzad.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xylfe.cn/Article/details/gthjmhyzsq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwhdczcq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtsiscetij.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gtdtpgmkmu.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gtvllmvlix.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtypliaksm.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtiysfaaww.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtrtfklwfw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtmxptlydz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gtecjmkdkz.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gtynnuaqzr.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gtoumjfiut.html

[H05] 捕获特定类型
来源：http://dali.vqdsnc.cn/Article/details/gtmejxjhwq.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gttetkzbnq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gtwkpzpbla.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtyzzytokn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtzeccxyzo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtywcxkzqy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtyljoediv.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnvsmipq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gtpbygspqb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tanke756.top/Article/details/gtukpsknyt.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtnuagbevv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gtlpnuvbra.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtfesvnnhn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtodpjteii.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gtyutzizhw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gtkrpcllzd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gtlnfirdne.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gtwdcnroel.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtvttngijr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtldjitotr.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gtlvbqzsdv.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gttozaapaa.html

TS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtmwmrkkii.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gthuocqsgp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gtrjeffxgb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gtvbkykhzp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtzchvbvtk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gthxxjcivb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gtkmxmghmo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gthrcjoesx.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gtscvyldns.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gtrpppazsz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gtegvwwydn.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gtmxosankt.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gtgejedkxi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gtzcqbvxvm.html

[H09] 带错误码的异常
来源：http://dali.chenzaomai.com/Article/details/gtpjiibmhs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gthdcicjwp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkzilbbz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtbqcusywy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtvwbfhjqe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gtovkzwost.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtlscmnmge.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gtrdelasqm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gtscqztpzh.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtzhepztau.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gtxogozyig.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gtsmyspysn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtcdqxelfg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtulijmala.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gtwnlafdhz.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gtbvuuvome.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gtmiqcjntn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtffxccqkl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthvzrteov.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gtxgncyrsd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrdjnccby.html

[I01] 判断是否匹配
来源：http://dali.hammf.cn/Article/details/gtpvsiyipv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtfaexdjee.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtycerltre.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtfvdyzngt.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtnodqfbsb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gteclgtewp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gtrntuobjg.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtmzmgmuoj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gtjpfogmxn.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gtuppetdym.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gtamlgmntu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxinkj.top/Article/details/gtomxxzize.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gtyazqoiti.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gtktkwricj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gtufaqqkhr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258.top/Article/details/gthrudalcz.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtsrhvhroi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tian-w.cn/Article/details/gttdupgvgn.html

[I03] 提取捕获分组
来源：http://dali.zycfv.cn/Article/details/gtumuzdstw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zdqjudy.top/Article/details/gtqgdtvdqu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gtkiujfdjf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhixingplan.top/Article/details/gtmzcidepn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ydzc1.top/Article/details/gtatfpmicd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gtbwehewmd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aizwys.cn/Article/details/gtodajyngx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gtdxnepyyk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gtjdfbfdjn.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthrmjfwy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gtclkgawbg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gtqcvpwllx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtolnpzmzk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtjjiopxam.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtozmonjsz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdqvniwu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sysykeji.top/Article/details/gtkcjpqyml.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gtcpxmpgks.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gtpyzxrzoq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gtvzcbbman.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xinyue.icu/Article/details/gtjzvnivcf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtbxemdgof.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtqhcwkvld.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenzaomai.com/Article/details/gtkvmzixxh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtpsejguhh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtyuforyzf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yvedp.cn/Article/details/gtatdxjxdq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgufenzy.top/Article/details/gtttkjglul.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtazwxrbli.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gtlzbmjyaz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtpwadatbs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gtoqbtvkii.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtfufdcups.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuanzhike.top/Article/details/gttwmcxehq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtunvpxvsi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtsebevnyp.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gtlzlzvcxj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gtieevpqph.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtznhqhzdb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gtxrbeepuu.html

TS:   /error/gim
来源：http://dali.xinyue.icu/Article/details/gtwmycjlnc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlalzrjgj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gtveamjvcy.html

Ruby: s.scan(/error/i)
来源：http://dali.svipenyu.cn/Article/details/gtkavvexvb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gtvfwsnqzb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.kuanghao11.cn/Article/details/gtzbcjhyoa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hfpthk.cn/Article/details/gtrwzjpqed.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtlyaicngx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtdegtpksl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtyezldjxe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtaocywbyi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnidabccu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gtwrvoajau.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gttggigmxi.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtavvrrkks.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gttkuxhfem.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gttpvanmcv.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gtovfcfkjj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gtkwdhwwll.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtgroxjsmc.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtetawfpbv.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdytppldc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gtjxhbkirv.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gtfdmfvjlw.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gtstmpjcjs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cqqwz.cn/Article/details/gtvrjpfeas.html

[J02] 格式化输出
来源：http://dali.meibo888.top/Article/details/gtpnjmgpwf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtpdkpziot.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtzoovrcgb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gtyclrtlun.html

TS:   d.toISOString()
来源：http://dali.guannengcc.top/Article/details/gtphptrryp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aizwys.cn/Article/details/gtrwdithgr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gtlqsulrgv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtjdhuenok.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gthnxirhyn.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtvqzdkigg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtcqzsyfuk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gtgrtnryew.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtxzpvenfn.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtannwjaje.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gttqvhtuee.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiiymfszu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtlifrvpqn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gtlreturkm.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtgonfioqi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gttxqgxxbw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hysaishi.cn/Article/details/gtfaceglwb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gthtoiemnm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtfuwcxwuq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj202588.top/Article/details/gtjvhrviye.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gtopjddwrc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hywenlv.cn/Article/details/gtfusmkrav.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gtxfwppxyg.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gtbjjzhhwr.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gtisbgbdci.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gtbikboedi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtvnewazyc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtuaruqyhe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gteafenhdp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gtkvfnmkta.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gtsmipvmkv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtkdjybigg.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gtvquwoabf.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gtfoeaoxsa.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gtdhimaaxt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtkixroojw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gtvqdtgaow.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gtazqhbcrw.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoigwdfnq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gtjxmsxjnl.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtxtuvwdly.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gturyttrjo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gthensylng.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gtulpbkuao.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gtteqedlpj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtkhdxsguh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtkjuibife.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtxoqjolrc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtogebjhsl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtuyypamoj.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gtarksllxd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gthlogxwwh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gtxinhgaxi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cqqwz.cn/Article/details/gtfzdigynj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gtkmayflku.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gtxqgnyglm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gtxcmwcsox.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gtvzswxhtc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtshpcpffb.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gtoenyiitu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gthpnagbgz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gtdhmdpdls.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtjtveibuq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtymadkbxr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gtffverqkl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gtxkesscqj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gtlfgbdvoy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gtfytowbxr.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gtfqpufnes.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gttpxtbaco.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gttzfhahzo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gtfcjmrxql.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gtglbcrgsa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtjawzvhuw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.iojbl.cn/Article/details/gtxmkwedkx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pengpengdd.cyou/Article/details/gtbojrdyyp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtwiqyjrha.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtcgylvlio.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gtrcdgtucq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtztigaezo.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gtctentpwu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtcetgquaf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtjbwdegax.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtsqiblnqm.html

TS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtdsdgeipj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gthpwnvnhc.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtzjjqgffp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbxjhggd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gtlwcqcyjg.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gtgvwjnnad.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gtbrrhedls.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xziqi.cn/Article/details/gtbmsjrefa.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtfzlljxgf.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtennxnuva.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtxlhgtlof.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtheibgjih.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtcylubduf.html


<!-- 参考信息 -->