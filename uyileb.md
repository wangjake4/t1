代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtghjyvrwp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gthmxamtoc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrhydovl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gtevigixmm.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcjtbwoyi.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gtfkbatzdd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbwhnzfws.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtmhfmsqrm.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtqzrrqboa.html

PHP:  class User {}
来源：http://dali.yj202588.top/Article/details/gtjydbzlrq.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtdpanjern.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gtfzyrlocx.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtnkznbisd.html

Go:   type User struct { Name string }
来源：http://dali.yuanzhike.top/Article/details/gtvlcicrig.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gtkivawxjx.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtdpktxzhq.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gtqfhamyac.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gtghunqnbc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfujnryjp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtlygfmwea.html

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gtjfhujhjw.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtvqrpmtia.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gtnxqonble.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gtdaosqxdd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtmqzvvbrt.html

[G03] 实例属性
来源：http://dali.dashuyun.cn/Article/details/gtuvqthpfg.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtqklpujzs.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtysjryptk.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtqisucwgr.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gttrkplukz.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gtkzegjkzj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gtyspobzyg.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtrxiqbugl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczmmfmvt.html

[G04] 定义方法
来源：http://dali.zhengqikj.top/Article/details/gtqchllsvm.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtmiqhctgd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtmsmwenwm.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsrjqsti.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtqjoxbjkn.html

Java: String greet() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtuzioqcto.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtlquviffq.html

Ruby: def greet; @name; end
来源：http://dali.wangdashe.top/Article/details/gtqrfnbbyz.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gtjcpikewp.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gtpjjopdnt.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtphxdwocq.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkxzcgzak.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtdkbynyte.html

TS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtsvecierh.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtnlmfausv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gtedvbqgkh.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtuuaouxyv.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfmvvqze.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gtjfgtvsql.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gtqcpbsdak.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzicpdirh.html

JS:   greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbinxsmu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtgesfxkof.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtcxnjhxpw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqjhnuzm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gtdvpaaqhj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gtztqtmldv.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gtygouieqy.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gtqgtckigw.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gthfcsxpqj.html

JS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtdwwecqqw.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtczeqetzr.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gtookymzyh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtvbfsxhem.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gtlzzldeyd.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gtnysilkga.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gtlzsqxlqm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtfbvkwvnh.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztovmaef.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gtkhxruhyz.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gtaalshhgn.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtxiwzszal.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtfneazytd.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtaivizgwf.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gtxqmkmdie.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gtxausxqlk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtrrkwvofd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gtzjjgnjnl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gtjheblisd.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gtkyzkqvfc.html

Java: interface Shape { double area(); }
来源：http://dali.guannengcc.top/Article/details/gtcaeyhtau.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.snrcjt.cn/Article/details/gtjqbudhjw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gtyhwsvdvf.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtyzdghomu.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtmrkfysbi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gtbgxyuuzd.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihlqtibj.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtrtxilvmm.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtpcwbysci.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gtzbazmvkt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gthzzavxjn.html

Ruby: public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtwiskdomp.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gtkhewtxop.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gtggdpuuev.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gtolypawpe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtfwsjoopp.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gthgldlxqh.html

TS:   get name(): string { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtnoxsvayu.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtuwomyvrf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtjtyzoeei.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtqweaahpg.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gtbqdetren.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtjcecnnyw.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtaoheqkyw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtiljktjta.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtdslgqpdb.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtoeccmwpn.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtukvmdxzv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtdlimhplr.html

Ruby: def to_s; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtscnduega.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gtzkygszye.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gtwmspnwlu.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gthrsjcwgm.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtuyniwnuw.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtuwldfvgh.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtfeghbqgx.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gthnguwqnu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.feifeiyinyue.top/Article/details/gtkhkwvkus.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gtzwhjcimv.html

C#:   u is User
来源：http://dali.aibaodan.cn/Article/details/gtlpfyraxg.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gtjhiwshzn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gtxrchnega.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sweek.top/Article/details/gtsczyaqbj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gtuhfubqao.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtjnijimna.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gtizzvfvgl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gtagurieur.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcmlcfld.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gtjyhmgimf.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gttnehsktw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gttgshkwty.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gtfmiqlceu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gtdtjbczbq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtghsqwcuh.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gtjpemxpdm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtgdatgjra.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtkggftbjd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gttvkyscrm.html

[G16] 对象转数组 / 字典
来源：http://dali.yuanzhike.top/Article/details/gtijsejyny.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shangyingyoupin.top/Article/details/gtypmvuizj.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gtfycngcdi.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtocmpjrdr.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzerwqng.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtooaqnugm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtztdojjic.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtzpubsbey.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtjcihagsx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzlyxtrin.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gtzfeyeojn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtinqqdwlx.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gtxchirflg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtcnexpwhf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtbwdhveoo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxlolbhr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtoiaifrwd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gtowpztikw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yueranfly.top/Article/details/gttxcjzrhr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gtozxmwrrz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gtfgpwrluj.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gtetyhgwle.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtathzcxzr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtnudnplfb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtjivwtoff.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtxorfjzbe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtgymfidfr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gteheoykwd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gtiqfvbntg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtydedmfkh.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gtswaadndb.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtzftvpupj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqspfzvb.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtqmjlullh.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtioaihics.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtdurqzvbx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gttlwmcwkq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfdujmqm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtfztusaty.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gthuzxpqug.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtdvejeyic.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtcfkkphsg.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtotadppqm.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtsnpmljns.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtyaoquftd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtjzkxfyvd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtqloxqpby.html

C#:   class MyException : Exception {}
来源：http://dali.gzhubu.top/Article/details/gtiqaasfcm.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gtqyogdagm.html

Py:   except ValueError as e:
来源：http://dali.ydzc1.top/Article/details/gtgulkozhd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gtvvgmfrhq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtbsppzhww.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtmmdkdcxj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gtvpxwzhfx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gtonkjmdao.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gtzyknkkbx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhixingplan.top/Article/details/gtaszwkxdw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gtestxsuui.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtjaggwuaw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gthrbrxvdn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtqwmdxuwm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gteetpdfvg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gthmdznsob.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gtbkmscweg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtcmyhmjgo.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtgvqmtreq.html

[H07] 断言
来源：http://dali.zdqjudy.top/Article/details/gtngbtrrfd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtowyerffk.html

PHP:  assert($x > 0);
来源：http://dali.hnqzz.top/Article/details/gtiupfarys.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtswoaxjwa.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtwzzjsayg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtvatbbprk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gtervjdmmp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtxkwphuwx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtcopowxzy.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtzfpdkwyc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmazampt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gtyyulhffh.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gtocpjyuiu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gtqyolyhua.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gtjauejrav.html

Go:   err.Error()
来源：http://dali.shuidangran.top/Article/details/gtrxdbymmz.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcyvfeqk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gtacesgjcj.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmatckvlr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtasucpfnn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gtrdnsklua.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gtvymkilfw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gthcmktano.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtbtfevtah.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gtsglxbjwv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gtxbarcfux.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gtfshdphic.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gtakkxxwat.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gtyobixyvp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.havefunace.top/Article/details/gttybzdwgn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtgbhllbst.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtmzmglezj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.meibo888.top/Article/details/gtzlrrumyq.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gtuglqhkqr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gtzhnqibpf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtjjrbvjij.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwtgkwspe.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gtvooswgva.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtsqtbcvfr.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaddvzsno.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtpgukziat.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikeqmthf.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtjadqoqoa.html

TS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtjeyeytzp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gtxftuiigm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gteniasacg.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzavoisqo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yueranfly.top/Article/details/gtdzowaocm.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gtvfxbilme.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtqbtibnuk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gtjzywrqno.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nwbrower.top/Article/details/gtnzrlhoxm.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtmlckauji.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gtuaorshhs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtusngjzst.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gtlrjyjhut.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtmfzqdueo.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gtljywmhum.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtshoabwul.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gtljwgpgyq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtlbexzxrb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gtxodcayhq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gtwedbvoby.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gtobpemocj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gtojxtpujr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.haohaochexian.top/Article/details/gtoaozeukn.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gtfcjkbauv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gtnxsbwaiz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gtvuaapuoz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtmjxayhuq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtgxqdszkg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtapckfakh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gtujrdhouj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtgniftpgb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtduzxfakj.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gtphcxvxlq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtgwixfwnu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttvkyeyv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtkwmghdxv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtfqritval.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtfgzwdtxh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gttmcpgngi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtnicxolcz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gotoacloud.top/Article/details/gttjeuqyff.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gtpkzpgubz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtrweecmzw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtfkrsvznv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtkrupfnxh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtmozhsmnl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtdmzujceo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxuanxn.top/Article/details/gthutvprih.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dashuyun.cn/Article/details/gtrcwewylm.html


<!-- 参考信息 -->