代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2qqlitulj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2ebbtavfg.html

[F11] 复制与移动文件
来源：http://dali.quarkkingdee.top/Article/details/gt2bbibkmhz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2rpjdiohh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2rvqimnac.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2hyffldgx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2mcdoqlcm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2fblywppi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gt2rxsoyxxj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2dxhrjkdj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gt2ltcnahqv.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gt2tzwcewlb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jyoumei.cn/Article/details/gt2vpzqyvyk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigfzy.top/Article/details/gt2hucjwodf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gt2rmmwmrci.html

TS:   // 同上
来源：http://dali.jlsjyb.cn/Article/details/gt2rykbuzfw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gt2dmhghujg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gt2vznvyffn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hysaishi.cn/Article/details/gt2uknwcpla.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gt2gwwfngoi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2vghasdds.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubiooouy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2cswrbmcd.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gt2kjfnsqcl.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gt2tpcrrccr.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gt2qqcoynob.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2olrlzset.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gt2icipuzjf.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2opvrzvim.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gt2irhqfqpn.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gt2ipehlfig.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2wmzcsdpt.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gt2uljcbswo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gt2lllwkazg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gt2drkyqgim.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2yxdrkrjj.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gt2xbzykylf.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2jjknjgth.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gt2nobpczvj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cucudq.cn/Article/details/gt2nalkvwho.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gt2nvoqnrib.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gt2kkwsnsze.html

Py:   self.name = "x"
来源：http://dali.c1oappe.top/Article/details/gt2vvdaessj.html

PHP:  public string $name = "x";
来源：http://dali.daria6918.cn/Article/details/gt2mzgnnmlf.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gt2aqalmbku.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkeieohx.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gt2kdodblef.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gt2kqygrzsj.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2yikaskrb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2iwbjsqhe.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gt2hibxdvad.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gt2itjhbuoi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2uiknpjvq.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2azvioptr.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2cglphrla.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2ozwlxvdc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2cqhxgedl.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gt2ppziafrr.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2bytyquqw.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gt2rqlarmom.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gt2kbskyqnw.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2kfbgybuj.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zspiscny.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utekfgog.html

Java: class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2hdessohl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tianlin.xyz/Article/details/gt2ebnfocfr.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gt2tmuoeevu.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gt2htzbcaln.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gt2szjihsjg.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gt2poqjzemk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2wsoetxxy.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2slewuhwi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2cfnroyxn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2eotqxifc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jlsjyb.cn/Article/details/gt2gwpaebwu.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gt2dhimvlrs.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikpqahwe.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gt2sdcjhwcc.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gt2wpcjjiad.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gt2ocsqxipy.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gt2gevhmbxm.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2ngilnebg.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2gtxpifbw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gt2jltytawh.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gt2xhjywvsy.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrmpdxob.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gt2nhpmgbzc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gt2nkhbkliw.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gt2ujxszkyv.html

JS:   static f() {}
来源：http://dali.ybcxt.top/Article/details/gt2plxkfyhn.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gt2hekfrwed.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gt2uklvrwnv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gt2vumlwcvc.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gt2qygzoyuz.html

C#:   public static void F() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2cqfmgohp.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gt2tyucylrj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahwhutvl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jiagoushi.top/Article/details/gt2zhlacfnn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gt2agdrocbh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gt2zhzfuplz.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2dxjqudwj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gt2jrlgqwbv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgfzy.top/Article/details/gt2mgylwlif.html

C#:   interface IShape { double Area(); }
来源：http://dali.hammf.cn/Article/details/gt2nhfoqtoo.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gt2gkeeyxjh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gt2megyiymd.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2vzbhjqdm.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gt2xkcfzwkc.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2hmjuzzza.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gt2tyhdnjlt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gt2dogmeygb.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gt2nreebrco.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gt2fwsakuxt.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gt2quggbrjk.html

Py:   @property 与 @x.setter
来源：http://dali.zhixingplan.top/Article/details/gt2uqlgjbff.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2hebfpzfc.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gt2alglkasa.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gt2xxhgkdhu.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2ilwekbpy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2deiasdft.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gt2ivnfaoof.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hsdmlmss.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gt2nuxtnvwi.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2rjlaunfa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2nuxwhcrw.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2enamupna.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2rgplukzw.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2udlmyrch.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gt2kxquloop.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2cimpihbs.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gt2xomvxeco.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gt2dhgsfljy.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gt2mifkmxtz.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2ifgxcdga.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2vmvfyppb.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvrmasly.html

Java: u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2dncrbqnl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gt2yfvendsg.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fijxvqee.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gt2qcfsnook.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gt2nnzgchgt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gt2ellfxvpz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.c1oappe.top/Article/details/gt2adzcejjh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gt2ozoqriog.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gt2gczizdwj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpruggzm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gt2twhuvjpo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gt2qtbcjkws.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gt2epaslryz.html

[G15] 枚举
来源：http://dali.vqdsnc.cn/Article/details/gt2qlktqthp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gt2aantnmlu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gt2xizoxmgz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gt2nufkcczt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2pjszggjj.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gt2qkcowcfc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gt2wikwlhcx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tianlin.xyz/Article/details/gt2omqtsjug.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gt2yswodqyb.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gt2scjjnkgl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gt2cayodpdl.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gt2aucjbthi.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2mnukjtli.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2vxekldgw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gt2oowsuibx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gt2qigkfajd.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gt2rcdseuha.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yongpay.top/Article/details/gt2jbuyclwm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2tyjgfsgy.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gt2ezpojwts.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2rbekryji.html

[H01] try / catch 基础
来源：http://dali.ehwqpu.com/Article/details/gt2dvnzsofz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjwmfjvj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gt2rndcxqbw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gt2rotmifkq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgkyrsfg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gt2twcbqgyd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gt2wpmiczzv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigufen.top/Article/details/gt2rkhjvgpg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gt2buukkerf.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gt2iijffowf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvpwecqp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2xbwlyeoi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2crlrwvrt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2cbqgfwfa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2zyeytexn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hammf.cn/Article/details/gt2gdjefahu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gt2pyekrlwe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2knahwjza.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2iijhlfjb.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gt2uzzbnuns.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2tmkrnqhs.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2kapwzdwd.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2uwkmfuxo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2haadpyfc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gt2oxapjdrw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jyoumei.cn/Article/details/gt2jmwmtbat.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2xivfwxnd.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gt2uijlmzwy.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtrqcerh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gt2omlmrltk.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gt2jwdvtqfl.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2lwlydnei.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gt2uecyyckh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gt2wsnqvsie.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gt2cunuzzos.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gt2xqxyyutf.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gt2iztoonqc.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gt2waqlbwbk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gt2ajhosdsq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gt2muizfpjv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gt2yfsopwua.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2thjejnlv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gt2slytrjul.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gt2wzyyvrfv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gt2yjqmgity.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gt2bruqggvf.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gt2igeikych.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2xwrmjuxi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2ftrmwpwg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2afqagugp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gt2chbrgvfl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gt2alboepqh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gt2mawqsugm.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gt2clsxoolq.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gt2rhnmwshe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gt2snieskhg.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2iqcvrubb.html

JS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2jefizlpv.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwatbije.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gt2rcnuylkf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gt2rddbcgye.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gt2tbvxxacy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2pljxijym.html

[H08] 获取错误信息与堆栈
来源：http://dali.shzxlz.cn/Article/details/gt2hxivuuhg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gt2torhjttf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gt2jrdabhih.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gt2bwiflvgi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2waponehv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aizwys.cn/Article/details/gt2cdjndeuh.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gt2axabmaid.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gt2htyubhkq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypubmumz.html

[H09] 带错误码的异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gtqafkri.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2ydpqrzwi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gt2tnycykzj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbobqpad.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gt2hrmvfnbi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfzlagwo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gt2uoarqpki.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gaohongyu789.top/Article/details/gt2fhihkakq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shuidangran.top/Article/details/gt2ykseezxl.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gt2lmrupkcq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gt2aapauive.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gt2guroeqgq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nfvhkszx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gt2luygulrv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.meibo888.top/Article/details/gt2qhigyaob.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gt2pextnvzx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awovddde.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2ctfssaml.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2phnbsduh.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnvvaffk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2zsxjbdyf.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gt2usprreum.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2qoclzjzn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gt2mjnbwzmm.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gt2kwfbhzjk.html

TS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gt2zalrrlzr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gt2mwatxozc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gtlncgbd.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gt2eajbkuhj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gt2qoderwkr.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gt2jsjcorxy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gt2wjjzrsmh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gt2hkqismfk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj202588.top/Article/details/gt2rczahnze.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gt2diffcmnw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gt2vwsykofk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2grwotbpp.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fbxizyna.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2smcpevim.html

[I03] 提取捕获分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujswutav.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gt2tvqdojyu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cucudq.cn/Article/details/gt2kkhkynyt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfmmhcvl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gt2xwcpfqho.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gt2acsbmslt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gt2xjksxwke.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gt2blapepzo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gt2drfcxieu.html

[I04] 正则替换
来源：http://dali.snrcjt.cn/Article/details/gt2hptbtyre.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gt2qankqgyb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2gafykhxo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gt2cugwcnfg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2wlnfnlmz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2kkxkyddz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2lwicwljl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2ysbzkcbp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2zwyfnqtf.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rypemjbu.html


<!-- 参考信息 -->