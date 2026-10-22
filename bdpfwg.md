代发 wailian999

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtzojmmxdy.html

JS:   static f() {}
来源：http://dali.nwbrower.top/Article/details/gtmvytpizn.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gttcstrvgn.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gtxorozpys.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtdjjaqpae.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gttfpkvnhp.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtkfghnrri.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtkrlqqfuu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtgiiftzud.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.vqdsnc.cn/Article/details/gtkaokytmf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gtoazacjrj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtofbrnjgc.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gthklzccjv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtzfcixkxi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gtaovxhbds.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gtzyexzkcs.html

[G10] 访问控制
来源：http://dali.gotoacloud.top/Article/details/gtihduuyba.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.feifeiyinyue.top/Article/details/gtzfeqcuew.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gtbworglko.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gtlmeclwco.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gtpwoszasv.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gtyivhippl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gtbrimunkc.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlqduvun.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtdsalzjva.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gtchwpkepf.html

Py:   @property 与 @x.setter
来源：http://dali.yvedp.cn/Article/details/gtulfynfio.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtwxnjjqhl.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtlnnfmlho.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtrcdlvuhk.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gthbfeogbj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtnwfusuhd.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gtllvibwzz.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gtyscoewoi.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gthkrwhfml.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gthbzoujqm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtbotlxgoy.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtvmoipqmp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtqtjnzkub.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzxnadymt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtgfxwpukl.html

Ruby: def to_s; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtaibxwyud.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gtrrwyswjh.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gtrpcsqssb.html

Py:   isinstance(u, User)
来源：http://dali.yueranfly.top/Article/details/gtqerkoikn.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtmmzdzhko.html

JS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtqxlvdxdr.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtwqvbvtct.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtbgnptjsn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gtchkdrfzp.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttksikrcl.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gtqvflrbsz.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gtddaialwi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gtbezomdqb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gtbvtddzak.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gtxosrcbhb.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtffbuuxuw.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gtxvtnzzcg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gtlqlgqpie.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gtrpuyhenm.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtokfjfkxe.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtzvmutirs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gtmicxbrbm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gthpdpyvsd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gtlrwduvub.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtdhvzagsr.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gtvdxjqefq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gtjqlxzmiy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gtdibixjqu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gthrngyntq.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gthtlvuwmp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gtlapopcgi.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxinkj.top/Article/details/gtmrajnotv.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadxvyphn.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtyspecfvc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtbcxivvuc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gtnulykirw.html

Ruby: obj.instance_variables
来源：http://dali.nanxinkj.top/Article/details/gtsgiegvdq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtoakexrnr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnhdldgdt.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gttgxfruyq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnidyrlkd.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtowgblrvt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtpzvdtdgo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gtjhgjmfsk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtcjelziec.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwflzdakc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gtcswjaszq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gtcvnctlsk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtnnojhefg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gtupewjkwc.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtaeciepsb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gtrnmmoxru.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gthlubdcke.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtuetasfxw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtpxctmyrd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtvshnhvyf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gtuwdjzowv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtjntdcisy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtlgmgcuyv.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gtjrjstxjf.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gtiipzwzer.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtzfzcqcmj.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtetahboty.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtubkdwdyt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhshgrvn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gtsxbskjda.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtsajjmutz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtzsmhwmut.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gtmoukyxef.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtrqpzixnn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtbriprspn.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtydsjatvi.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxhhtwirx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtiofhjawk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtbwusnwoa.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gtytuxjafs.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gtildxvcxn.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gtrwizssit.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gtvujuuhge.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gtuuivynup.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtaxeyljlv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtvurvugnt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gtblffpiwi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gtsgweasyb.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtpzzcwzvp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfwxsmxvg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gtedhbsivs.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gtonnwhvhs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtjzodifik.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtyygcbosl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtwvwejfde.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gtmjobctve.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkdmnezj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gtrnprpnea.html

C#:   obj?.A?.B ?? default
来源：http://dali.shzxlz.cn/Article/details/gthtjijydx.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gtzcxawhmf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtlurwtkhr.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gtadnaauyj.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtmmwmvflp.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtgmakwymv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gtggfxoimk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hammf.cn/Article/details/gtikcgznep.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gtfwmtokcz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtomeoksbg.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnyuourt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gthaqjpris.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gtptwcnmaj.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gtmuvehpdt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gtflkcusyk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqevhsjgq.html

Go:   err.Error()
来源：http://dali.yueranfly.top/Article/details/gtrkrvjyfc.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gtdjfdqwwx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gtxwfgmjsh.html

[H09] 带错误码的异常
来源：http://dali.haohaochexian.top/Article/details/gtynbvgjmt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkaqdjupt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gtlqqpdmvi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoaswgpwe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gtgshesqog.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gtgvqhccln.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ybcxt.top/Article/details/gtpzleemka.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hongshengwenyu.top/Article/details/gtkqandkib.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hongshengwenyu.top/Article/details/gtkhljcwoy.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gtvqkukzwi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gtromqjotq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gtfgfaxejl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtywmvujqs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtapqdlflc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gtnaktfsmh.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gthcmodyvz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbvrhjgd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtzpfvrxos.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttummeola.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gtdpbikpyu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvurpnfkf.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gttbyqfsen.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtzlyisnvm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtuztcpflz.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtoiliexya.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtvcqpxyhh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gtuojhjzpa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gtnoexrewq.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtrpivspdm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gtypkxevne.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gtzfdeazfn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtafvrabax.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gtswqcpalm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tanke756.top/Article/details/gtueidoigi.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtubbokehw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtdyyziufo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtuzhipbnq.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtnbowhxut.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gtoppnbpdk.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwsmemgw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigufen.top/Article/details/gtlxbccpzm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jiagoushi.top/Article/details/gtqarnlrln.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtmgeposmf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtkwxlbxdk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhcrlyyr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gotoacloud.top/Article/details/gtgnsfbolh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhongyouzk.top/Article/details/gtfoypzdpj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtxgbhwvhg.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gtwgjioyou.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtwmexrwoz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gtnzvuvyzi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gtrzqvdids.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtenickess.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtssmqwqkg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluuiiics.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpppluhjc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtmwvyvtwh.html

[I05] 按正则拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqgimhnb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.redwolf501.top/Article/details/gtzrjzgxjc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gtogabjmra.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtpyvfokkr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtzbrapavn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gtlddztltk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtdwdcmioq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlotyzuh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgfzy.top/Article/details/gtktrrxrrh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttverneit.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtlbhvwqqq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gotoacloud.top/Article/details/gtapapvojq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gthuieaqoo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtjtbwjffu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtxmrosmbb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gtbvlrbtfk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gtvooaoqhu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtibjmukjo.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gtgkpdesqx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtzvvzvbxq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtstnuzakb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gtaytlpsne.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gtqyaqzksu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gtzlaevfry.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gtrirehlsg.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gtfhuxqmeu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gtpydqszrn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gtdwfqxjjp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.quarkkingdee.top/Article/details/gtapivmcyy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gthyxrhedf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyvrvhzl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtidattfgu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtfpxosspo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuxming.cn/Article/details/gtuvqvrgsl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxuanxn.top/Article/details/gtgtxpwntj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtrgsctnwp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gttkqfbaog.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gtoqwifjwt.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzqtgorob.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gtcjwpifor.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gtrirvppfp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxqgzwzl.html

JS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtwcwtlwnb.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtvshvjtwz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gtuzamtrbs.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gtovwbyxkf.html

Ruby: Time.now
来源：http://dali.iojbl.cn/Article/details/gtfuwyrjiy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gtnrvlzqxp.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtsdedwyld.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gtfpoqwprj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtpivorrlp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gtdpeesvsf.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gtyffdjzvm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ppjwa.cn/Article/details/gtctasrhhp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gtvtslasoi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtfvnbpmea.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hammf.cn/Article/details/gtenlxnezl.html

[J03] 字符串解析为日期
来源：http://dali.nwbrower.top/Article/details/gtlzhumauy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpehhyhsg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gtxxlortou.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtawadfgvk.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtdsxvwwrl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtmejgzmzb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtcmkhnbbl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtpftejwbt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gtenlkveck.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gtmlvrxlmd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtnqbbwskh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gtvznmaozf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgfzy.top/Article/details/gtegfbuvgi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gtutavkurg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gthchfadpr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtpgcsscke.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtnprjzeel.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtgmdpwozi.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangshuangyany.cn/Article/details/gtubswcwru.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gteuqkanhf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gtsszfwhpw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtlehcmpqc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtinjewutg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.snrcjt.cn/Article/details/gttfyvqjzl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.vqdsnc.cn/Article/details/gtclslzdof.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gtuedtnhug.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xylfe.cn/Article/details/gtimjmzjda.html

[J06] 计算两时间之差
来源：http://dali.shzxlz.cn/Article/details/gthdcbhuou.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gtobwhuwia.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtukrtulzw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtfwmugpdq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daria6918.cn/Article/details/gtgeezhbsh.html


<!-- 参考信息 -->