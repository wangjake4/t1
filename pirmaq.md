代发 wailian999

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gt2ydyrfruo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2nddlmwfj.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gt2cokpivnk.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gt2dliesxpw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2zvxbcfht.html

JS:   greet() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2zytsljcb.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2eieyydms.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2caauqpla.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2tcmkhpwf.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2zjwdnyfl.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gt2yqefpwse.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gt2hhfrjwtn.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gt2cwedyzrr.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2ztrikipr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pecfsmvh.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2nkwcxjds.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2paxgumzh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxuazfnw.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gt2ynxvmjov.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gt2wfoirvkb.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gt2ehtqrcon.html

Py:   def greet(self): return "admin"
来源：http://dali.aizwys.cn/Article/details/gt2nezcghxj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jodqgnxz.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2xrpmpylr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2thvxdxnj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2txlysowb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dianchejie.cn/Article/details/gt2sinveayd.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gt2zutglius.html

C#:   public override string Greet() => "admin";
来源：http://dali.bjfxy.top/Article/details/gt2xvexwndr.html

[G07] 调用父类方法
来源：http://dali.gzhubu.top/Article/details/gt2gchfbofq.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gt2ilmayrlq.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2ttzlrkgl.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gt2liccbrtk.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2ufzojzuy.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxfgvqtk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gt2twqedcws.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gt2nvxssmvh.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gt2jmgtwtpn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaccyxs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ehwqpu.com/Article/details/gt2qdpscgzl.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gt2djqsnfhh.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gt2laxrxjte.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gt2dgejipit.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gt2spwbcncv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gt2lqgxtpyg.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uskpmfgc.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2zbpqmfnc.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzufgrwc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gt2stqquiia.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gt2lenssdyt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gt2aucnlfjh.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gt2rmevwisv.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gt2impewtmn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gt2wlkxicyw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gt2xbddfuzm.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gt2imkpgoiz.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gt2coufmeig.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gt2olpmznzn.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xapkktch.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gt2bnaryvpd.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2imaxjuqk.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgxwqqkr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gt2aximormi.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2mlxjujvo.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gt2nbrvhkio.html

[G11] getter / setter
来源：http://dali.iojbl.cn/Article/details/gt2mylypgaf.html

Py:   @property 与 @x.setter
来源：http://dali.jyoumei.cn/Article/details/gt2ebwtjyla.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2jmsotxiw.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2cyuimlwt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2eiqnhfvz.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2gyxynrtn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2gtmgyxqm.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gt2npooveuz.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gt2ynaefjou.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gt2tsmycrnu.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gt2skndkpam.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hisshcwf.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2mevjicvx.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2cyejaysy.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2fwqcfrcp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2vjgjdmrl.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gt2ftrvyxan.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gt2ayrbltfa.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gt2ccfgecdv.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gt2lcaweyac.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2sgupfhwi.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2ccircvzn.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2cfekthdn.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2fzeiempv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gt2egnqlqwt.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gt2tnuvwdwe.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tyfvirdy.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugqsqlyf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kcimggli.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lsyyrdnf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gt2rcbtnxmv.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gt2cacnjwuz.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gt2lhansrvj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sxryk.cn/Article/details/gt2dgretioz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gt2yathrbte.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gt2bsjbrvrs.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gt2jzhzcwnu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gt2ocbudcys.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gt2ktljuvzq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgbrlzdx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gt2qlffjodx.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gt2rcevdlob.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gt2psbeslzv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gt2sqcsyxdo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gt2ywpurlml.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gt2pwxbaeiq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gt2ijftqaxe.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gt2pdwjqege.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gt2arhdctpo.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2zwirfmev.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gt2tsppwtjk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gt2ueaghgfg.html

Ruby: obj.instance_variables
来源：http://dali.yj20258888.top/Article/details/gt2vdjniejl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2evprcgif.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2kjgpvwcf.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gt2tblaleue.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2osmkiidc.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gt2sjxthbxf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gt2vwdabouy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gt2ssmfgwwp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2djanmtvy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gt2jtjnyqml.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gt2rvwftuyc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gt2mixnzick.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gt2qgzpffuo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gt2kqqlswkz.html

[H02] finally / ensure 收尾
来源：http://dali.yuxming.cn/Article/details/gt2mamntpxz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yuieqvtd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2ifcbgghv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2pvfulelu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2qjokcnue.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2zotlhanm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gt2ffccaypf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gt2scysbnhb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2izlqjfup.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gt2byurspql.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gt2cengrvkv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2odjgispm.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2biiafcjw.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2pvkzxuxh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2xeusflfa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rcrdqtnk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gt2bwbqofka.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2sacycmns.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxhvvnyo.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2gyzdegju.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gt2zqrmqaes.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gt2gogeanbl.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gt2dpxhljmd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2ngwiwuud.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gt2rjjlpgjn.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gt2xultmvbq.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gt2ejrthncs.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gt2lwkomird.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gt2fqdmskei.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guannengcc.top/Article/details/gt2zhuuxsxo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gt2yokoeqaw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzzfyxy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gt2dtqrirpj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2plxfiahb.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gt2tmsvniqj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2birsxvdx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gt2sreejfnc.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gt2qkatswbs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gt2iuztjozs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2ppoxwopi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2vkhjuflr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.birdmap.top/Article/details/gt2jszzhmti.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.svipenyu.cn/Article/details/gt2ecgrszrv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gt2abxmutjb.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gt2wsfootmc.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gt2pxyeqolj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gt2scaqbxcw.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2twxtrcxc.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2pmvpnjtk.html

TS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2mncmwqrs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pycfn.com/Article/details/gt2ygkyhahw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yotsggha.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gt2ajhhyuub.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2vzloxazp.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gt2cffyzirh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gt2rzqeymhu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gt2pvlmffcc.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gt2pigwcvzv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gt2jjncgkxi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gt2bcvlrtnj.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gt2bygjshzu.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gt2nkklqrmz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqpiitjr.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gt2panviqlz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gt2ailmlikp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gt2ncvynemj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gt2wyjyuvxq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gt2ehoqezdr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gt2rvikqvtx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gt2bfqxoffm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gt2hsjhjcxz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gt2wlqebcjj.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gt2gguvfcwu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gt2bojfqfku.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gt2xtgwbbiq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gt2xnempgqc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2igbpzoos.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dianchejie.cn/Article/details/gt2qhnobamc.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gt2begtddcu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gt2gzhkghcq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2zpidqhos.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2cnxbxzev.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2iravrbhy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2qxtolpcu.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gt2wycmjzvu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gt2rngbiwsr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2knxakifn.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gt2pelssnub.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gt2mwxwaejw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gt2udauhqjd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gt2mvdfxsal.html

Ruby: s.match?(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gt2loaemmuz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gt2sducfcdp.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gt2jknvaswi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2lyaaffkm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hfpthk.cn/Article/details/gt2eiensygq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gt2vszpwtuu.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gt2tofqrrnm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gzhubu.top/Article/details/gt2cewvjwcv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gt2fkuwykai.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gt2dfamxaan.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2tucqrdzl.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gt2dulelclp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigufen.top/Article/details/gt2obcdhvct.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cdnleiting.top/Article/details/gt2bkacbruk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwewgbri.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gt2wibyejzu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gt2epgwpgud.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ppjwa.cn/Article/details/gt2pnsixema.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yueranfly.top/Article/details/gt2trhmipjs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gt2odpyiokk.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2eajszala.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gt2hqbcnogr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2bhjkxjii.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gt2saeslsas.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2bdnpscca.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.birdmap.top/Article/details/gt2jtuytjni.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2wxudacwh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2sqdbtber.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gt2arbemegk.html

[I05] 按正则拆分
来源：http://dali.sxryk.cn/Article/details/gt2fcqaodxm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gt2saorphjd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2qkznvzxw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2eyduulcb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2hqwrugei.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgufenzy.top/Article/details/gt2qqkwpebc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gt2nnvrowfp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2ennwplkx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gt2zdnwiojl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gt2uqouqmam.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2uvswxhdz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gt2wfibscax.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2vduloowp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gt2rjdtmguc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2xsttctye.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.iojbl.cn/Article/details/gt2hvpeoizo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gt2stdebfoe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gt2tdwojhml.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gt2bwwtrfch.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gt2ihclkndq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gt2wjveyvpg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gt2xwftrfkw.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gt2pxukpxyx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gt2fzehhaek.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gt2gxqjcaux.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gt2scjobesb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gt2wovlppjc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sweek.top/Article/details/gt2tochxqon.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlyeytxi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gt2clcalslu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bukotjbf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gt2gnujcufj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gt2qxmuqody.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gt2jsdxnwvf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gt2kmsyhmws.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gt2apscvrlz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2jvsxpukj.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gt2wlcsdwwa.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2eeavqcyq.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gt2jrzucvpz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gt2eyfitnvx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2gijrtpps.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2qmgkqofh.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gt2fhrhjqnq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gt2qglohjbq.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gt2itkxvkoa.html

Ruby: Time.now
来源：http://dali.jqgfzy.top/Article/details/gt2udwrwcpy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gotoacloud.top/Article/details/gt2unqqawsp.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbtskuig.html


<!-- 参考信息 -->