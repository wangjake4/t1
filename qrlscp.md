代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxwdhouy.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtlpwhxerz.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gtnoucjawi.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gtjcvbjoub.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gtnrjgedsb.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtuhpvvffx.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtlyixhxxk.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnudobgxu.html

Java: u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtvybjvpej.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gtqjplijrc.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gtdwcnjqwb.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtdbwfbdwy.html

[G14] 数据类 / record
来源：http://dali.nwbrower.top/Article/details/gtdtjjseem.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gtoxvsslzj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gtuojlokcm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gthdkjcmxq.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gtefjvppsq.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gtvekohwed.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gtjlexggfp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gtpmpaltaw.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtcibsiwvt.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gtaenypars.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sxryk.cn/Article/details/gtlblsgayv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ydzc1.top/Article/details/gtowapvtyo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtxxsgtlzi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtwqydcryi.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtngegtjib.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gtklmixbnq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gtqwgtgcup.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtzqttgeya.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtwhogzxjt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gtqwwqiosq.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gteyzuqmny.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtdvbdqs.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtresiktfh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gtzqdcbkol.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gtlylnjopk.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtbkcayvvq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtjsarhgvc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtoclshscg.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtzrjryodw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtcubvcpll.html

[H01] try / catch 基础
来源：http://dali.ybcxt.top/Article/details/gtuodqfmvs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gtpyywjphz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gtmipbtqpj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtdpohrtxu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtmyuwraps.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gtpgekxaed.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gtogcvxhur.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jiagoushi.top/Article/details/gtrezkqwne.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtvqvicfxr.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gtmqocmoui.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gttjztkxdd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtbxrohkwt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtgqntfass.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbckarsry.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gticungjiz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gtqwgnqyfa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gtehnvbsek.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtvkghtxsp.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gthuojftor.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gtuntpedwt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtefvxggnd.html

JS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtcocfzoxs.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtolzqwnug.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtcupkxlgw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gtwfqttdvy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gtkmnszwsu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtdxtkrjmp.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gtwezbrpmr.html

Py:   class MyError(Exception): pass
来源：http://dali.jlsjyb.cn/Article/details/gtnguhsezr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtoitcxoyj.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtbadqlski.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtbublghbh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gthfctiiwb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gtpnpsnufg.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gtuazgplug.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gtxdswizhx.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gtvpqoofgs.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvnlnmkw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gtjqfxzsdy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtpjmuwlyg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gthkbqtnuy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.iojbl.cn/Article/details/gtltsslbwd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gtbvncdqar.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gtfjeoiahd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrezsdmjm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gtynyypcsk.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gthzzcnkmu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuawrttde.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtouvnlxix.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtqugnjfco.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gtirnkczch.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gtcufpxypz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjtdwmvo.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtrriwohhx.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gttqnnlbul.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangdashe.top/Article/details/gtfmnpbxjw.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gtpnaaevlq.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtbrexfvjs.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtpfqijomi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtaypptwdb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gtvupifkfp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gtrwkyceik.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtolhulagn.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gtesakkptu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtdmnnuehh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gtpenueynq.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtzcuwtwbl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gtiyeiqcyr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gthntzlyes.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gtbmwelybe.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gtobxzzkir.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gtwvjmzhlw.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gtusmyiobn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gtinepljdp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gtwudqtzay.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gtjmbqbzsq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gtmwsbdftk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gtmtmenyok.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gteznysoym.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gtcfpmexdo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gtmchfxkbr.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gtlwaydoxc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tianlin.xyz/Article/details/gtlyhlpmgo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gtgcaymokf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtxlgjelhv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvghbkif.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gtwnydfqdl.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gtzvmxlrox.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gtkfnriwzl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtxmrumpsj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmdmtcxbj.html

I. 正则表达式
来源：http://dali.shzxlz.cn/Article/details/gtmhmaicaq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtivkmwriu.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtwlqxqohf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtculfdtid.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtusbuhclx.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtufdizjup.html

TS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gtbcxlhypc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gtpxrzujiz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gtyvifgvvv.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtrejaxupd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtqcjokube.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gtumhsweod.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtmqzmeirq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gtzkdpohjd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gtoizaomlf.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtkrxguvgk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtuiiwlspg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtrvmpxuik.html

Ruby: s.scan(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtiqhedlki.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj202588.top/Article/details/gtesebhxdu.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gtjxadbmkw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtbpxlyily.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gtodaavsyl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtabkapjqf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gtmvhglufz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shuidangran.top/Article/details/gtoadfypfk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gtobhqqkdo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gtvmcknxns.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gtmtdrnmez.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gthhevhkvx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gtrmufymwy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gtjjgzaxnl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtctbhvvus.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtaawvkwrb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gteviqhexb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gtddwaxcqm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtyxbdbsad.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtlthrrdmc.html

[I05] 按正则拆分
来源：http://dali.redwolf501.top/Article/details/gthuxlncnj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtxfcorsdh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yongpay.top/Article/details/gtvtgctxop.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtvpebyfvv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtpkksspiy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtgripxyki.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtcwnduqtg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gthnzxpmyl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gtsceudxbk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gtdmximceq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtelnlibzs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gtmcvexkdg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtngnesivv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtjwpesgae.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtexlyubed.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuanzhike.top/Article/details/gtrupnsqbq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwziztgeo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtrpyhdwos.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258888.top/Article/details/gtchubcnpl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gtxknnoikz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtobthaaxv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtcscfezit.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gtbhuciokt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigfzy.top/Article/details/gtdxixdtmv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gtoatioscc.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gtvsdacytq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gtbjwtfkrw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtcchuhmzm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gtdxecjuog.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtjpdusfwz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtozujofox.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtcmwcwugj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtkkpfhguj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gtryzwpcvw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gthvhekpie.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtgspomerk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrlyeawmq.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gtqzzzujpk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsdezyarp.html

[J01] 获取当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaouxczv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gtvqcbhqif.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtpsxpfqet.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtdjpnxtyv.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtinaybuic.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gtutxhszob.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gtuzuxkryz.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gtbqwqeklo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gtluixoles.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtrrgtwvfg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtatzyiljt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gtkmcejmpr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gtlysdxspw.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gtojfjzewf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gtkncbawll.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gtlrjigory.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtxyymmyyt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gtdzrarjco.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gtbvgvpyon.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gtepgjbkkt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gtpfspsfxb.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtrnpqnjqj.html

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtjucdovtt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtjvzwjwqf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gticnbmvru.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gthrxwwedv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gtnmhusmmr.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gteplnbavn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gtbqsrqire.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gtdktsjtfy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gtyxdtbysv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.meibo888.top/Article/details/gtpsskhqjh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gtxltaqgdx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtryqarmwb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hywenlv.cn/Article/details/gtrlqbhrvn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtoaxigrqv.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovhqdzux.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gtrvgzczsm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gtfaolgowc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtrjvbduod.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadurcgix.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.snrcjt.cn/Article/details/gtamlnsvvf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gtjtxtcito.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gtjkyuniag.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gtweybsvwq.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gtecbyleco.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gtxyeobmts.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gtwhgnwbyy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gtzoyujhpj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gtlypbooom.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gtaboknmea.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gtwqsaiibj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gtatbboxts.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtogvlohya.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gtisxyjkoo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtqteslgqs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gtjwsxxqml.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtqqhxkpnf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtcwndgttm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtvihwtsrh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gthvzdikkk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtxgfhrljr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtxkijrgce.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gtcpfaxbbu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gtcnbnikco.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gtxewwazpt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtcftgdspq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gtgthbikcq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cqqwz.cn/Article/details/gtxdsosrnf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gtoyrllhgm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.meibo888.top/Article/details/gtdjndzund.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.redwolf501.top/Article/details/gttbxbdcwk.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gtwbdyfoaf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258.top/Article/details/gtrtwedufk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gtlxbwysru.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtcxuipiqr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtcgnqchel.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gthdvbknne.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gtyxqjeuwo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.0kj1m.cn/Article/details/gtlrfgyxow.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gtxmppfjxc.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gtffnojfmr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gtwnhhagna.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gtmobpxcxk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtbtwhvbre.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gtqeeltzon.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gtgblaxyqq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gtwwjlprmj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gtqofpegei.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gttptwyaco.html


<!-- 参考信息 -->