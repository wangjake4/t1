代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gtrebteywo.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gtuqithejb.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gtgyijzhji.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gtaafbpcxs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gtjieizwah.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtgcgybisq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gtjjkcoayq.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gtmenptqvo.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gtclflyeww.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gtrhurxpiq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gtxzvptoeu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtpyalqhtl.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtjlxxrzoc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gtdodwcozw.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtjeickjgd.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gtejnxpkei.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtbpupafms.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gttiojjtny.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgcxbcvm.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtiwkhbdkf.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgcwvbjd.html

[G11] getter / setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzcmyjqk.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gtrkgrjhxg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtsqwhoymp.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gthagvphzw.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtiklyxnir.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtlulsoyed.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtiticfgtw.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gtwexrfxyo.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gtzjpnxiky.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gtrnplocih.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gttnhylfnc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcatjnzsh.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtwogdwowb.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtgebwtgvd.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtovjmjoyz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtwgrvlicu.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gtmqevcrha.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gtqakbrcxf.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gteymfksmn.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gtsszorjss.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gtmiffombm.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtokshgjjh.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtlqphowxp.html

Java: u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtdojugtjk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gtgutbtkxx.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gtwlppzutr.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gtibvlpdjs.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtkmloyfgf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gtrixlglhc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gtpanuaome.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gtllyvjamc.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gtpmtdpech.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtiezogimy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gtuhgrtamp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gtjgoepwmu.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gtqflwufsb.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gtiqoikekz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtwmhrfuud.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gtjuckfdrs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gtdyydnzmo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtajoddrxl.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtzqdbbgnv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtcafhoqaf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gtevkruzal.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtiojrvilb.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gtlrhpngjv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gtoskmnzjo.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gtptuapoqc.html

JS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtfkxhjpcp.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtmshrmwjv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gthxvvzjyl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gtyxsacsvx.html

Ruby: obj.instance_variables
来源：http://dali.yuanzhike.top/Article/details/gtveyzapnx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtwiqkjthn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtqlwsigam.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtnmyhwzir.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtoyjgynxc.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtkyjigzff.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gtdmcsfnmh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gtctzfzsha.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gttssptluy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtomizeocf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gtayanleik.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtltvciebu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nwbrower.top/Article/details/gtmihieiet.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpgobsxy.html

[H02] finally / ensure 收尾
来源：http://dali.yongpay.top/Article/details/gtgalavkcv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gthiesjnem.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtzjmhphhg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtjsssjtyj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtnrkawlzs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtqbjtjgue.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangdashe.top/Article/details/gtstrrnokc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gtkhlbqmcz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gthhzggqiv.html

[H03] 主动抛出异常
来源：http://dali.xziqi.cn/Article/details/gthxcighck.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtmsmxgrxn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtipfxxuav.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtifkjtwou.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtggmbesqe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtbnribkyd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gtlylpfrri.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gtnqhwtdwn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtnapefbot.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmougpta.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gtfzaofnkj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtigbqbnpy.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtvkwerzdt.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtrermhbvk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtqxqkmhvy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gtrvsdacjt.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gtjckniwty.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gtvidrlalk.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gtpmptvqaw.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gtzhsnljiu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtutqalgzk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtngikgsrq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtuyfnxaoc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gtjwzzvurk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.316326.xyz/Article/details/gtupkmgjwh.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtibqbxnby.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gtzauvjfvd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtyujghide.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gtxportysa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtgcglufrz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtyobgxmtm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtywvyeqxh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gtytljybtc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gtfmtaikof.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtyysujjqr.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtaifngmtp.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gtonfotwqc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtvxwdyhpz.html

PHP:  assert($x > 0);
来源：http://dali.xuanzx.com/Article/details/gtraeedold.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtyzceysrz.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtdehiotee.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gtwrminnal.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtxqvowsmn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gtkysebcun.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtzwnmbgkk.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbiuaxqj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gtnnykdoaw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gtfuzeybff.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gteeruuurk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtcmkuqwvq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gtpdnxhnrl.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtryqprhws.html

Ruby: e.message;  e.backtrace
来源：http://dali.svipenyu.cn/Article/details/gtvhqfulas.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gtenexdzxw.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gtnzckaqxn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gtbvhebapt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtfqjhuqpf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gthcikxbuy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gtxjlyrrje.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gtciorgkps.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtjkrgccao.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gtexdrmtnc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gtwrrpfexq.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gtgpnobpce.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuanzx.com/Article/details/gtrszdwrzt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yanxiufei.cn/Article/details/gteezvbmvi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtfazhiimk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtpbttywgs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gtwgqtytah.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtotffmtpb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pengpengdd.cyou/Article/details/gtjpflycqj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtfvbcxzth.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtobrvhagb.html

I. 正则表达式
来源：http://dali.aibaodan.cn/Article/details/gttdrymqco.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrxqolsyf.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtjxnkxggp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtcihyrcxq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.316326.xyz/Article/details/gtbrvzlhss.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtgvahkseh.html

TS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtdvostdae.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gtuomybipc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gthinjizbu.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtcqcpjvjj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gtichjnshi.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gtllwkondz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtdbalnvgx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tianlin.xyz/Article/details/gtlfixqgfa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gtowzddlwy.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gtilszbxqs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gtybdhhgle.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqybsimmd.html

Ruby: s.scan(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtlyaubxfm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtbvxewrqi.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gtsrqhiskn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.0kj1m.cn/Article/details/gtoqxqpdva.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtjkgvnzbx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gtbszirqth.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gtsqahgecw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gtndpsppht.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxinkj.top/Article/details/gtsomcqmll.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gtxhghsyba.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gtptpccild.html

[I04] 正则替换
来源：http://dali.zhengqikj.top/Article/details/gttkycaoro.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gteueofozt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtpebwyexl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gthrwjrmet.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtgfyevtiz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtjoymjxhy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gtgioxoyjg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gtgyxgdeju.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gthdgbrdlh.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gtotskoqzr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yangfankeji.com/Article/details/gtwtazoiqf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gtjvnomxea.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtxbedldlh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtpwfhzfnl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fengsongda.top/Article/details/gtnomooywh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtzhycriej.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gteopzndei.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gtfwdnkqrn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gtgebvtcfr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtemjteoup.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gtbtblnasl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtfqzvdbbj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtriqfkuag.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtgmjnhfqh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtiolnhieu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gtpbudpwji.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtvczckodg.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gtbhzbsqrf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gtduohlrgq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gttejcecrq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gtwliojaxx.html

TS:   /error/gim
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmbuxnnk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gtwenihteb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gtsiqwrxdw.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gtdkcwqfet.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cashguo.top/Article/details/gtzsucwfbo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gtvakdpnqv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gtfhbhpond.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtfuekymgo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyeawzjyn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtlultnmie.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtroqfkufd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gtutokyuhk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gtmresyeyi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtizgwyizn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtlksnbbuc.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gttivmqwge.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtiybhgogx.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gthxcgozuo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gtzkorbruu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtzutrslqc.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gtmehwoktt.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtvmiovssz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gtobdqgrhw.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gtzbqhlxyp.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gtvihzlyhn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtxrnuhlqb.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtktlodzva.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtizduilgy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtcmldycqp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gtwamciutc.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gtzjzavxsb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtosjcedrn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gtrqbuewyh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtgbbqhbog.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sweek.top/Article/details/gtfjoyphrr.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gteeskgctm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gtgfkbsgqs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhoulong.xyz/Article/details/gtzsosuubf.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtglqamkdw.html

TS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gttsjrvxov.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtuiugjunb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtffhubyke.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtvirzfpso.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gtczlsbavu.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gtmttjxofj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtgnrydxcb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gtedtjftvf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gtnbfxqapz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yonumen.top/Article/details/gtngavclvv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttezaxhed.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtkjvpudma.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gttmuyqexz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gtbtpfnhro.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtuluhlebq.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxuanxn.top/Article/details/gtuezgbczg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gtxavcpmlk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtxyvjzmuh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gttvvketxd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gtsuimaoss.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.svipenyu.cn/Article/details/gtyaxqxvxs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.0kj1m.cn/Article/details/gtlogldbbp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmregmdx.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gtsfxtfesp.html

Py:   (end - start).total_seconds()
来源：http://dali.ydzc1.top/Article/details/gtnfhjjxxm.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinpdrevd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gtvigwfhxh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gthqgndzgf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gthnrxdcjy.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtintgwsim.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gtrljosupj.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gtzluraqng.html


<!-- 参考信息 -->