代发 wailian999

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gt2rasyjlvo.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2pwmskqlf.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gt2icdiiheq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gt2hfwvwyux.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gt2hnnxrmwl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gt2ckciwdqh.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gt2kixorryq.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkyorhvi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2npdyvlmh.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2pdpxclci.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2odcrvaji.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2jtakpqtu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2fmapaqrf.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylzqdpmg.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gt2zzceltxz.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gt2jgqwfrov.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gt2xjltesit.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2uttuvsqp.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2yvhntknv.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2jgdelxsl.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2dcdeotkk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gt2slhrirxk.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gt2jpxpueni.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gt2pqhvjtdk.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gt2hyilrnjf.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2myabkejb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2jelmurvu.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2xqpktvhd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgbwhemm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2ryidlvaz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gt2jbgyhxqy.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gt2fuevtqjs.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gt2ggpreldn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lxryertu.html

Py:   super().greet()
来源：http://dali.zdqjudy.top/Article/details/gt2ilbnkfvr.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gt2tupfkocw.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2apttmmge.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2pmyxqpts.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2ccpwugbv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gt2lvsawral.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gt2iwkcqjxp.html

C#:   base.Greet();
来源：http://dali.ydzc1.top/Article/details/gt2xoholscd.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gt2bmyxsoiy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gt2cjwreqwj.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gt2rwldsihr.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gt2xcbbzkgg.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovzaztva.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gt2vhbntoli.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gt2wjfizepu.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gt2acbtsbqa.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gt2hatfnhuq.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gt2ldlbfmep.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnqzz.top/Article/details/gt2uietrmnr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gt2kjhoklal.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gt2vruganpw.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gt2icdfhnyj.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gt2lnfiyxfa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gt2daglckrq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gt2ksbzvhhj.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2lkchsjco.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gt2ijjwwwsc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gt2cdposaxn.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2ngalapfs.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gt2nydthayj.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gt2mzcfdnsf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljwzjtea.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gt2rojwitqn.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2mgwyhnlx.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gt2dpocdnod.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gt2klgunozr.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gt2ivvdkqll.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2nonqgkzo.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqipdpov.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gt2zwsjrczn.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2shzyjhov.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2rhdvdtxe.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gt2dohthlwy.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gt2yvebinrx.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2xfzcehfj.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2pccdjpis.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcrufrnf.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yagugpys.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2vvghalpp.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2xzxaghsl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gt2jjmcdbqv.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gt2eujlutwy.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gt2xkacbcnp.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gt2paoircyq.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gt2ifphhkwi.html

PHP:  $u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2ucuprcdr.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2tupwtefa.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krlbtpan.html

Java: u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2wvbnubes.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gt2uljsstlk.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gt2dyyibhgf.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gt2ozgbukbr.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gt2fdwgevyg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jiagoushi.top/Article/details/gt2qqerlqoi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gt2lqlaxyoo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gt2hhxlmura.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gt2iopaiwde.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gt2nipwiimj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gt2jxmyeppu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gt2wmovntfe.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gt2uehjfgwm.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gt2hpgrflxc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nwbrower.top/Article/details/gt2aisspnpj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gt2ehhzkibh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gt2zkaviirw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeqffhe.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gt2gjwiqiqz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigfzy.top/Article/details/gt2vgktibog.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gt2jnzcbfab.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2xdcyrcrl.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqbawxqo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gt2tbmsnfun.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gt2ujkvvxik.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gt2srsciwje.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gt2qsnlwlex.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gt2ejfmzfek.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gt2nrchftzf.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gt2hhrsnzbt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2uwlpdxnw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2uadnghxq.html

H. 异常与错误处理
来源：http://dali.yj20258888.top/Article/details/gt2fmxwgfem.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2tkrkyrdl.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gt2fkewfwpb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gt2potimgtd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2itizpqxn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gt2phenfeup.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2szmchckr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gt2yifbxmgt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gt2gtumujhb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hywenlv.cn/Article/details/gt2dreikdeo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.snrcjt.cn/Article/details/gt2sgxigbvs.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gt2vjsmnuop.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gt2cjpwacmx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2vzrumpcb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2mohcxkrk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2jeylvaei.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2lqqgegrx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gt2tpkxejja.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbmbvjpe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2vjmkmyaz.html

[H03] 主动抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gt2gvdapecu.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gt2prmbslmu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2wvtlivla.html

JS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2dwgbzhcc.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2mounodap.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2zlwjvdfq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sufxvd.cn/Article/details/gt2zjbnuxml.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnkpkoda.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2spfpdubn.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gt2xgisbmmr.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gt2orkfjahv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gt2mlcopyhs.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2asbzoloh.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2igonubam.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2dinbzast.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2islmyave.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gt2tksztbxw.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erzmywdh.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gt2wueidiji.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gt2lerqeamw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gt2kbdzyoer.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gt2hzztsyjh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2srnopvso.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gt2nriuxarc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gt2uybhzhvt.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gt2pgynivxe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2fpnkprso.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gt2ybukaggx.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gt2xukffigt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gt2ifssrago.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2ilpfsjzt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2cqkeblaz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gt2ypkbsexy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gt2csfbvewb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gt2sbzqbuki.html

C#:   obj?.A?.B ?? default
来源：http://dali.daria6918.cn/Article/details/gt2egaponjx.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gt2bojwpoij.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gt2wphfgszf.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2uuttiwoz.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2ycenavee.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2hwojelpq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gt2dpykurbt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gt2vjoonfzy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gt2mjhprxmf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2rjkmziyo.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gt2pilrrakd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gt2ttyegivu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gt2fadsxotc.html

JS:   e.message;  e.stack
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygirbknm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gt2iauwqtaw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gt2xwgcbase.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gt2sgjddost.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gt2jmkjbkqr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gt2unqaotmt.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gt2flvlsaaq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gt2lvmglclb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gt2ptamrfnj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzxkfhjd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gt2pplzifcv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ojqoqfpj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gt2vmeluvhz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gt2ookgiwzh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cdnleiting.top/Article/details/gt2jorvxede.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gt2lclahfjx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hyhfwfzm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gt2hzlromlp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2moopbpkb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gt2uxsxsxyq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gt2qtsdtyai.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gt2otbuaeij.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangdashe.top/Article/details/gt2ivvvxgcp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2uykwzpyz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2beeogxsz.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpxsacps.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2wohiowii.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gt2pirbnjbh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2epuzusby.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2ylzmyuaa.html

JS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gt2uieugrjy.html

TS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gt2dqhuswyd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmjfilhe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2gpklmbel.html

Ruby: s.match?(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gt2bbytixgc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhixingplan.top/Article/details/gt2rrmirnci.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gt2pictvocr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2kednivmn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gt2lxawjgsu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nwbrower.top/Article/details/gt2mtvqxewo.html

TS:   s.match(/\d+/g)
来源：http://dali.shuidangran.top/Article/details/gt2icvvknmc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gt2ddepwlik.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2imiqjllm.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2sozxcmvv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozpdrbyd.html

[I03] 提取捕获分组
来源：http://dali.yanxiufei.cn/Article/details/gt2kckyziiq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yangfankeji.com/Article/details/gt2wulazrte.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjtltxfr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2sngtbuvw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gt2hppcnzjc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gt2kosspbnt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gt2whkulpng.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gt2anvzfvxp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gt2nxrqxqbr.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gt2ucbprukm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gt2iadcselh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gt2tnzzmxwz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gt2xzuzvnqc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gt2tsywyibt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gt2zdkuryvd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gt2ydbqsvwx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2aleihsvz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2edgrjuyn.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mptswjjy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uogwrbbx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2uhiolttf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2woxtdgey.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2rdjgxeta.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ivvv.top/Article/details/gt2wqnegqzh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fompbomd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2acbrcnix.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuanzhike.top/Article/details/gt2ljwhrzcb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgufenzy.top/Article/details/gt2dlnhigep.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2aqfcuosv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxuanxn.top/Article/details/gt2dhbimvbs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gt2ovprhtdm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gt2qgaicihu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2efponhvk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gt2qhjmireq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yueranfly.top/Article/details/gt2kfeiwyyc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2nsljgboo.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gt2pdvwsejw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gt2azvmvdqy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gt2qbugkuth.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hammf.cn/Article/details/gt2cmrytgap.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gt2dzguueth.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gt2jduvwang.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uglhvglx.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdckqroh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gt2chvgfzow.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gt2aidqhyrb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgwuswc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gt2qwuzvqtx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2chhyfbfg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gt2aivtqchz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2psyemmji.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gt2rgtqqcar.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gt2txhpbmuf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2ieylbyra.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2wvhztcyn.html

J. 日期与时间
来源：http://dali.shuidangran.top/Article/details/gt2jhxttpuw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2eoqpdyzx.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gt2javdmabo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gt2hjutmvie.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gt2bfskjdzv.html

JS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gt2wlsvqhyh.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gt2sglmaulk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwddfkcs.html


<!-- 参考信息 -->