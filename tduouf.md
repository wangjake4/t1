代发 wailian999

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtlorbgnhy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtqukfwygd.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtgedsjygk.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gtnjoazpvl.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gtclcyvrzr.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gtmzadcryp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gttdkavjbs.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtxoaiiaaj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtarducime.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtbkoapuuh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtwjehojsn.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtiomvoagu.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtcunepkqi.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gtztcfodbb.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gtvtsmhgjz.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgzpilys.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtcqadszza.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtguzkrmyp.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtxgboyknj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gttuneyhhf.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gtscjxoqkl.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrktwrdsg.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gtujbafajk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gtgzkpwlvn.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtuscdjdrc.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gtqiraszpa.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gtsatgmnon.html

Java: static void f() {}
来源：http://dali.gotoacloud.top/Article/details/gtbshthavh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtyskznkzu.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtgmdohwro.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gtgfjkhvxd.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gtemsjxdbf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtmayvfnpa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hammf.cn/Article/details/gtxhxseamz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gtojkkxiig.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gtzaydgnop.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gtlojhwkyd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtnqsuislk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gtvzpmscqb.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gtproclnne.html

[G10] 访问控制
来源：http://dali.hywenlv.cn/Article/details/gtxmkvtcjm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gtugjvyeap.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtwbabidfc.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gtezqypfbv.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gttgmktcmw.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtluzulmzd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gtlzrtxiay.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtjoojmbnq.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gtgrztvwqx.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gtwbqcnrsv.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gtgrdnufnu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrmsuzyw.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoptbobft.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbiboucyh.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtknqnzspk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtnnjwqenj.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gtogcgtjwe.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtiwdxosxg.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtwixecygd.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtarxijrar.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtquzznxvm.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtexajzngk.html

TS:   toString(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtnlhxduyt.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtuesjyoub.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtxjjhizdm.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtmrgynest.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtqihfssgf.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtucfhcrof.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gtdbmevids.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtnhjaiovt.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtpvtjhcne.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtuxvdirfi.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtauegjzjx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ppjwa.cn/Article/details/gtiprnpsxt.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gtikucycuw.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gtlviqxcgt.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gtnxgvmwic.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gtywintnjv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gtvnxtnvaq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gtuqvrhytt.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtibwtgnir.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gthlnrzugi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gtepmccxbv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtyvqisibn.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gtmtrvzyhf.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gtwofnhemd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtmphtcjiy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gtomfulntd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gthaeexlex.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtdxealoni.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gthfveyvob.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtbaggaqwq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gtpiiswxzi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtqjbbtpdw.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtftwqzdnf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gtmmcylfia.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gtlvrrtsqp.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtzdjwvjej.html

TS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtewnlxtrr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gtkgigiuxz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gtyploqxbj.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtcbmyrarr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtztndazyo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtfzsdyzob.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gtwtjmrgoi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthbrrutxf.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gtjqfbjgyj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvyntbdu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258.top/Article/details/gtubcvxdbj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtlpsugmrc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtxpkgmrrm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gttbkjaugt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtqfecemjy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gtpftfwarh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtcjvgsqey.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtbtrfsugk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gtcsxuisoj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtgxpbojif.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtjetfchyz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtwmnrmngk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtproqeezs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtfjqpsxmf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gtszuvgcou.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtxcymsbqa.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtlqasdzpp.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gtjlrauqrd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtkqrdjvaj.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtclallbxo.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtwplasxrr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtqjoljndu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gtzbsxbcvl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gtsvyjuosa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtgmamgtxi.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gtdzwfwnmr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gtkavifayo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtsudmsmro.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtqvpanzbe.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtuaiyglcr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtyuzujvyd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtcszklvpm.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gtzdbynkwu.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtmgmvltnl.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gttwwfrjry.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gtsvqgpoyh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gteuqacblv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtppkwvdjh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtuagnnlps.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gtdtcqwgwn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gtjoxgivzd.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtddbjgnon.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtwvticcxj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtjtkaxzsn.html

Py:   value = d.get("k") or default
来源：http://dali.hnqzz.top/Article/details/gtgsekothd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtkzbnzhnd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtqmwjxfdg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtxxdbwgvi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guannengcc.top/Article/details/gtcclccgfd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gtlttpeeks.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gtmzappblf.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gtxlqeuyti.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtabxtozvs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtcnyquqcr.html

PHP:  assert($x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtowhtdhmb.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtoleuyzta.html

TS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gttbzevxot.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gtqprpmddu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tanke756.top/Article/details/gteuebfvdo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gttrxerhuz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtcmeiuuwb.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gtehjefruc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtlnbvlnuu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtjuenybfm.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gtsvqzcegc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gtsbnhpqgm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gtsmzlewaq.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gtmhwcaumr.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtliovwxou.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gtvqequuyn.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gthijphvne.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gtyzbajpdj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gotoacloud.top/Article/details/gtxizxxnxa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gtmhecrtum.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gtrsahevsp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gtjlreysxv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gtbjvesdnh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gtzbiyynwp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gtbfiftsls.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gtmknuovpn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gtdfqiipwh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gtcdozfcjj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtermwnvrc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtcayiqewr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtbwjjcmns.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gthstzgpot.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzddekavy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtfcjymdjl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtqpehqbym.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gteejjhlcm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gteugocpuw.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtgyxatlon.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtcthckswb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtibunabjd.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gtmpdxmubt.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtrxngqzcd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jiagoushi.top/Article/details/gtgalpyliu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtuscuszbe.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtwsjszrjf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gttxbemayo.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gtthtevsqk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtvqeddzxp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jlsjyb.cn/Article/details/gtggbsvrsx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zdqjudy.top/Article/details/gtgmmeggdy.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gtjpiypuch.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gtycgagbhq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtcmzyhdzi.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtqwesdjta.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj202588.top/Article/details/gtlkpbvbby.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtyejwjtot.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gtryjwobwk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gtbxugbqee.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gtaibmcjcf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gtdhsrgomv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtizosmfkv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gtcqumubqw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhixingplan.top/Article/details/gtpbhbhojs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmwjljfr.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gtegkcperj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gtsaxlrhlq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtegekauqy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtmiticcda.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtvljliwrm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gttpyeskhi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtlsnmzlis.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpwqiays.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtfvbwcwha.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gthjzqahwc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gtawxzfzbb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gtoasxittn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnmkrnxa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtdpmdqlsy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtfphhdpmy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gtmqwkvlip.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtuqwowzpg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gtytenedav.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gtyhxjrhij.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtgglpaibi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gtcvlmaimf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtdybtyanc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtqlmjegwx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtmhaparef.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gtvtolnwpp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tian-w.cn/Article/details/gtscjqywkn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtqjuydbio.html

[I07] 忽略大小写与多行模式
来源：http://dali.vqdsnc.cn/Article/details/gtadtbfocr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gtuhdmazpe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtkbklzyip.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangtech.top/Article/details/gtebehueby.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtmfimsy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dianchejie.cn/Article/details/gtiuhahbxu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gtzguzjfrl.html

Ruby: s.scan(/error/i)
来源：http://dali.sysykeji.top/Article/details/gtkalrwhsi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gtcpilszrt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zdqjudy.top/Article/details/gtnyahswrp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ivvv.top/Article/details/gtgtftging.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtynwkzxkg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtawglqvas.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gteouugrxk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtnlcrbjdq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gtazqwerrw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gteajpmtnr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtxuetotwx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtnminvsll.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gtjwazykcw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtcplqoold.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gtbdvmfyca.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gtqoyeqptg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtpktjzanr.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gteheutamy.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gtdtfdnvkl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtscxjocpi.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtblcwrhvn.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gtvgtcgzzj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gtatgafcic.html

[J02] 格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtkwjjqldw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtfovarwdk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtywjtnzfc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gtxmzvhkvz.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gtxbkraivx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gtgtfqnmbp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gteigyvaus.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtbmbfgdjj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gtbksyrmva.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gtjkwumzmj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gteuilcvyk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gotoacloud.top/Article/details/gtoxyomhcl.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtidqtfomp.html

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtpchsjdwp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtbmzshodt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gthyayjofz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtvsjavjoj.html


<!-- 参考信息 -->