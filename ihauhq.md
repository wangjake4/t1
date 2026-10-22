代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtithekkra.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtmhagfqkg.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtbogebhgc.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtyypxqsqp.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtfdhgbvlw.html

TS:   name: string = "x";
来源：http://dali.dianchejie.cn/Article/details/gtbcsfxhnz.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gtghukphqc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtocdndpjx.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gtudfdggem.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtqakhksao.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gttdsnyyxg.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtmyjhjnjt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtuxjzhxtp.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtiksruwol.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtqtxhzwcw.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtnrvizkjy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtdcniufff.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtlevzajtj.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtxvduptmu.html

[G05] 继承
来源：http://dali.ehwqpu.com/Article/details/gtaizbujpd.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gtyqbjdmqe.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gthlpfbept.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtyejmenhn.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtmoyyaxuq.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtukycjrqd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gteytjvlsy.html

Ruby: class Admin < User; end
来源：http://dali.meibo888.top/Article/details/gtreqkubsz.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtaspepkme.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gtpmtwqoay.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gtyubzltsr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtjugrtswl.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtgcwteacm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gthelhupdz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtwctxoeda.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gtmmmgyelt.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtqktigiau.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtubdznmyl.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtejifhgah.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtpeisocty.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpjwmhdu.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtjwpwquvz.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtltmkzcli.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gtpumowjtx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gtrjgrtinf.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gtylzeauxz.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnjxuxyb.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gtlizwkurp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtbjxyaqkz.html

PHP:  public static function f() {}
来源：http://dali.ydzc1.top/Article/details/gttswqmzyh.html

JS:   static f() {}
来源：http://dali.redwolf501.top/Article/details/gtqdsvzexz.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gtfngjamjm.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtygpxbuhx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gtecvontru.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtgicgndzm.html

C#:   public static void F() {}
来源：http://dali.kuanghao11.cn/Article/details/gtdethdkqs.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gtohogknii.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtggwtanau.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gtrystvkby.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmyojkkg.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtglbiqsdc.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtxmhegbix.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gtnsiyurhh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gtxkwtmvod.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gtockgabwk.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gttcwiebna.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gtlzwupmsu.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtxszwecwx.html

JS:   #private 字段；其余公开
来源：http://dali.zdqjudy.top/Article/details/gticfhtnoz.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gteembkagz.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gtlnyoezhm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.meibo888.top/Article/details/gtzzgbljho.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtnkzyhtaq.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtyvfigljl.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabxnjrlh.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gtaqfkwxax.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtajvoniej.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtpnrgavzm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gttsmdwkit.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtdilrggcl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtrvmyddpa.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtofhvcpho.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gtvozjlshr.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gteoragiob.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtauqttcyt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtdtwfhwyb.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtimkdjqxs.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtpyhkkbzs.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtzqctkjhj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtrmltgbfd.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtloedhruq.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gttcbdkuxg.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gtmkbeixit.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtmmrkebrz.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtemenckmo.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkrgharv.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtfouwtqfl.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gtfilcjxav.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gtwayxwamo.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gtwxfjnztq.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gtvfdtpmjr.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gtzgqfflyl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gttienpkar.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xinyue.icu/Article/details/gtgbwczeee.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwrgwfde.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gteihzisqm.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gttloogowg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gtbjwxypce.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtkxbabefg.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gtxkilomdh.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsylhbvtp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gtqmppuoki.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gtkiysuxqw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtxevajsom.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtzujjwaam.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gtpnaibupa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gthmpaaake.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gteggdaknf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtceuhswjk.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gtrqngieyz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtlhzqdshu.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtwvnflroi.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtoqvatjoc.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtfteuplwe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtbcwotvls.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gtxamffdur.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtbrovdcdf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtxusfxfxk.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtjzosbpog.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtrllqkogz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfdbpvgdb.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtoxwjdirb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jiagoushi.top/Article/details/gtewuondvt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhpyzfbv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtoapprsle.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtnjscprvp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjrhhdip.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yueranfly.top/Article/details/gtdkotnugd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.feifeiyinyue.top/Article/details/gtkyacsmla.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzmabfen.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gtnfenagez.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gtlplinwmx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtgmjzsbsb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtwdkxgvxi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtxpobvfhd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtrbevmufo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gtnddwapmw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtffetdrtn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtcirehshb.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtlfmkvyzi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtbvkobqba.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtpyeoyjrg.html

JS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtcylmhlag.html

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtcckndkor.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtvojbfron.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gtqbvljhsk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gtaqshcdrm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtaiybdaar.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gtjvozniop.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtotcgyzmz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtmciqobvs.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtolcfyajo.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gtzhwogqgb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gthslcieli.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gtgigtqewh.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtyhuhoyjw.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gtsbwkprbf.html

[H05] 捕获特定类型
来源：http://dali.chenzaomai.com/Article/details/gtclortgxc.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtszdmcsoy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gtfzesewoq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtyrkccsgd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtbbuvsibi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgufenzy.top/Article/details/gtmvoagqon.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gttpptgxbg.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gtozmjthfi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtavwmwsae.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gtoawtzygi.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gtaculmpdr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gtlgbfrkvi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gthsurjfug.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gttqwosnuu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gtvbbswazq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gtkymybkjf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gtpqmcrqdc.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gtkzbvwjks.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gtbbfdpbwm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gttvigylbi.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtjxrzzafc.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytadmhjp.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtefqksbcb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gtriancbbh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gtlfzgpzev.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gtdcsyovoy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtkgudojar.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gtvwhktnfl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoatgozaj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gtiqamabap.html

JS:   e.message;  e.stack
来源：http://dali.havefunace.top/Article/details/gtecfklkgu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gttksuqocl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigufen.top/Article/details/gtctkgqdwt.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gtkvekeixl.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gtbagasxpk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shangyingyoupin.top/Article/details/gtlgagzpgm.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gthvnqsuzd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gtjmjawtkv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtziaqxkgz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.havefunace.top/Article/details/gtlyzsxhfq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhoulong.xyz/Article/details/gtvxbcnuwv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrwgzxzj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gtijzrnfjr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shangyingyoupin.top/Article/details/gtngdgnjel.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gtcjfnpqjl.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gttlskwduh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guowangkeji.top/Article/details/gtnszaqlol.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gtdwswbybq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtlnzbrtgg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtdlgxdmkt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gtbstyfumb.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gtiijvgqat.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gtbdxsjwrw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtlblawaww.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbkognbvq.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gtebikalym.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtoslcexcm.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtfwvwgijg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtraizlwqx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtiobtusyh.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtoywxjwla.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtodgjvatp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gtdvnuivmv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtbsbkmzeq.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtxablknsv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.snrcjt.cn/Article/details/gtjfomhgld.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gtghzxczja.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtdmwjiktu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gtudkiokii.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sxryk.cn/Article/details/gtmufvngqr.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gtfhhvvqjj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gtgukkxgbs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtwohxznnv.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gthmrtutvn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ivvv.top/Article/details/gtqfeqiagb.html

[I03] 提取捕获分组
来源：http://dali.meibo888.top/Article/details/gtsmvuguvg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dianchejie.cn/Article/details/gthzglhhly.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtddivdgnc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtmrmvtwcd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gtelbifndw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gtwrdeztpv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gtlarqdyug.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gtxbflqvad.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gtrgpbnjds.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gtfsudmqhw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gtogngbgbm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gtzkxqaktl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtyywoqmbf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtszbiyvtb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtjuckpcxk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gtpgohhllr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gtnlemggyv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtvfijqmqe.html

[I05] 按正则拆分
来源：http://dali.bjfxy.top/Article/details/gtqervywww.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sweek.top/Article/details/gtthwcctdf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegpohmpy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtpnnfjppx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtbleuixuf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gtqyelrfvi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtrdhgldjd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtipkdkctn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daxiang520.top/Article/details/gtyeksuwbf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtikxzmvqf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtggjqhoob.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gtpjfkqpwo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtrcxfizpt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtgsztxcif.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtttmvlyva.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gteaqbdmdx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gtkgmwxmee.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtmpnjweqk.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnxiangtu.top/Article/details/gtkcutvzkl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gthpkqtodh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtwnlozhdh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuxming.cn/Article/details/gtgmrfydrt.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gtrpucwuvu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gtwlbcytso.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gtbgzzmocw.html

Ruby: s.scan(/error/i)
来源：http://dali.hywenlv.cn/Article/details/gtlhsohezx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gtvgwoquna.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtltklcfoe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gtpgxljiqt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gttwhryvrv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtdllffqlv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gteeknbzwd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gtcbsukops.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtuvuwfxlk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gtubzdeqdu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtvofqmucq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrnooikyv.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gtmvmqxfyf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtnlwrpdmi.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gtwbwgfwnd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pengpengdd.cyou/Article/details/gtajoffijm.html


<!-- 参考信息 -->