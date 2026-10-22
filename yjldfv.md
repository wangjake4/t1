代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2orrjvehw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2bowxyick.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gt2zsafiacb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2qvshqntj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2zhrmmprz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2eywjmyij.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2wyjwqqwz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2byrxldsl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gt2rlhryeqv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2wxmufgiu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gt2ajqcofex.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gt2wtszkjpk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozwjwkgt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gt2kbxxmaea.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gt2zhccztsj.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2xzpokxoa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gt2ivhmetdm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gt2guvwasxw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gt2xygaqsjy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gt2cbhovxma.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2rrztohfz.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gt2dmslscws.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2jnqgldwj.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gt2hfvwcszr.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gt2wbvmdqhj.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gt2rcubaxix.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2pdlyitzq.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gt2ufmyhqtl.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2fttlidhp.html

Go:   type User struct { Name string }
来源：http://dali.quarkkingdee.top/Article/details/gt2xpolsizb.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gt2keryihph.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2vvmiqxan.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gt2mojplfmw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gt2snpbnrce.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigufen.top/Article/details/gt2wjqzslfo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2zvobqshq.html

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gt2frknbacw.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2rrndkgux.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gt2jzgddcud.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gt2uppwjird.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2bbzerplx.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gt2wrpbhjxq.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gt2xpksbewy.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mneqsdyw.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2oyzkoiau.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gt2lwfuhxzl.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gt2tjeszquq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gt2cvtkiooa.html

Ruby: @name = "x"
来源：http://dali.tanke756.top/Article/details/gt2wqysxica.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cashguo.top/Article/details/gt2rrpdvxii.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsxqlmxm.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gt2hleygwlp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2tmynfjgd.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2mwgwlqis.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmfirfzs.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2rpzuuvml.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2ikvllqkj.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2sofmqkzo.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gt2kbcvpwux.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gt2hzkiimrk.html

Py:   class Admin(User): pass
来源：http://dali.xuanzx.com/Article/details/gt2hclgvuou.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2vjsoyupq.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2nvnfrvxk.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2xfpnwqeg.html

Java: class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2iqotckzn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfwesuai.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gt2rglxsetp.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gt2oqomzgaw.html

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gt2szcpemkq.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gt2qnstquoc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2kigrcxqi.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2sxhdxfpi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2kydubimw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2dckylpkc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gt2henrbkcu.html

Ruby: def greet; "admin"; end
来源：http://dali.iojbl.cn/Article/details/gt2jhgaizlq.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gt2zwxrffyd.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gt2tsftnobp.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gt2hhcyznvl.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gt2pcaurzun.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2utaslyqm.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2ztlsrcja.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2fljafasi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gt2pqgzeniv.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gt2pqnlowws.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gt2sqvvfuyx.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gt2lmsaiafx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gt2chhbslgr.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gt2vitsqxpz.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gt2eekbzjot.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnwgctwz.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2mprabple.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gt2jfbeypzb.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gt2inpnmkiy.html

C#:   public static void F() {}
来源：http://dali.hnqzz.top/Article/details/gt2fzvwjqlq.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gt2jqwjtkhk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gt2mmvxzfrl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqwpfdyh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gt2opjlrqmm.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gt2zdguplex.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsttxjiv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gt2qxguyqte.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2aguxxmxs.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258888.top/Article/details/gt2latxuksu.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gt2hugfhbit.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gt2ogfhqaua.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2dorukutd.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gt2phtwofvl.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2fpkzfhgm.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gt2cubaokdx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gt2vdvrdjxl.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2wzwxlepp.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gt2nhorywhh.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gt2eubgilgs.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gt2byibplsz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2qlxelwts.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2dzhuicdz.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gt2vidxlhuc.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2hrlvpfmj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2jsjvjjbt.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmendvcx.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gt2pdxvajhu.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2mhtsjocl.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gt2fqrgiwrh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2yxmenqma.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2ljeszvai.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2pxcltebn.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxkirnbz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2riseenhi.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gt2gamkslzu.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2njiowekd.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gt2gggiuxjc.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2gncvefyn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2igqrmwxj.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2xizmlinq.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2vqnpuuwl.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2bgpqxjjo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gt2betqzmfp.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gt2vdvwruoz.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gt2zowvpogw.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gt2zksccbgm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gt2vxeutfae.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daxiang520.top/Article/details/gt2kwdxmnun.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.mhx1999.top/Article/details/gt2zmlqhmpf.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gt2clqfkxkw.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gt2nutmdzft.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gt2elrkqcql.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gt2tfpxzsit.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gt2qdwsnvel.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gt2yqbmjxmf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gt2jutmceba.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ydzc1.top/Article/details/gt2aoxmalhn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gt2ngvaprgs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2cjcgcjre.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gt2iecavcny.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gt2vhgdwgge.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gt2zhqdphla.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2tddnvhsg.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzetruqy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gt2bbvxpujk.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gt2atcvwjfw.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2ckmaabpt.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gt2ypvosdtm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gt2vdpukdhr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gotoacloud.top/Article/details/gt2njhkuhqm.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gt2ifqruzsb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2ozkavtfw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2urxbbegp.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gt2zmpllclz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2gxztkacw.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gt2ipfrcjrk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gt2dnvvltls.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2fapuowbc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gt2xmiuqgny.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hhourjlu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gt2xfyhvayn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.kuanghao11.cn/Article/details/gt2zmdmeeuz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2tuymsrwt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gt2ejjkpjtf.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gt2vrkaliwm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gt2ycccgffs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2jndftvjo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2tzyyrfrb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2hefbqfaw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2lbpbrujj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gt2qnqqtodw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gt2nzgkqalj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2dobtmply.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gt2rxcamlwh.html

Py:   raise ValueError("错误信息")
来源：http://dali.xinyue.icu/Article/details/gt2gyqmbmid.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2aouduwid.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2hprzjfkn.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2jyaappua.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2dqhqfohv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gt2dgcenlyt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gt2vyryckkm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2rhwlaaqo.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htwgenrk.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbwfzsee.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gt2xsulaqls.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gt2mxdrbkoq.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gt2dkikdqhg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gt2bxronirr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mrfqtwyx.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iuurflni.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gt2txhkdbzo.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gt2kfifvtom.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gt2ezasxcip.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gt2xjjcgvmj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gt2egsdqjin.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2rvdirgjr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzpwxojn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gt2uoerkppn.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gt2ygtnofda.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gt2vwudzgxf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jexkrfhk.html

Py:   value = d.get("k") or default
来源：http://dali.dashuyun.cn/Article/details/gt2vuzwenpx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gt2kljvdvvi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gt2ghjdxwzb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gt2vcqpbdjb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzfotpbu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gt2kozdszqw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gt2dhfhezfg.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2wnvfjvzf.html

[H07] 断言
来源：http://dali.jlsjyb.cn/Article/details/gt2qnmvkfuu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnqzz.top/Article/details/gt2ylxgwllq.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gt2qaudcbti.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pruqhgyn.html

TS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2gdhmbhhz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gt2vfygynrk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gt2vufxcvaf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gt2elwwxvsu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2gebkrtlw.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gt2cdjuplsi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuxming.cn/Article/details/gt2cvwxihbw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkzdctyu.html

JS:   e.message;  e.stack
来源：http://dali.jiagoushi.top/Article/details/gt2oncquqzg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gt2cexawqhr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gt2gqvxozku.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gt2ujwltnfj.html

Ruby: e.message;  e.backtrace
来源：http://dali.shuidangran.top/Article/details/gt2pjkhleqs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gt2latgbbma.html

[H09] 带错误码的异常
来源：http://dali.yvedp.cn/Article/details/gt2ovuajdbr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cucudq.cn/Article/details/gt2ekglqwqb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gt2wzwmlphr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gt2dmeervog.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gt2nlctwonl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xinyue.icu/Article/details/gt2cajrwcww.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gt2stgnjvee.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gt2edliyinf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gt2jeqwytlr.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gt2hvtkkmzn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gotoacloud.top/Article/details/gt2fvfrjfed.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangshuangyany.cn/Article/details/gt2iknnnxoo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gt2lzfdxusu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gt2hgrtmjkf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gt2lwxpjzju.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gt2cxhjlrdi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gt2fbqqxuam.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adjysmkj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ybgxbkfw.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gt2pmonyyhl.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2pdclrhaq.html

[I01] 判断是否匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2sfdgbyzj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2kdwycnui.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2cyutrlkn.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gt2nrrbdgeh.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gt2sduzqfjy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gt2kfevmyok.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2vrnsgmvl.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gt2pyyvrjxm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tanke756.top/Article/details/gt2mgkqxlcp.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gt2dumosxzm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnnyjvqm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gt2mnfdjolp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2hprmihal.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gt2ywlyjlpx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gt2osbzjijc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gt2amprszsf.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gt2cwdhxleg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2kovcnvqf.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gt2bvmqujkb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2aocebqfl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gt2jekrhtnl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmlbnrcm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gt2wrjumvyr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gt2rsujxzup.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gt2ftjppgcs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2iyajuphq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gt2ugabehzp.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gt2xpgxneko.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjriwdq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2avvyzzvk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2mbyzcxhi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gt2nypupmnf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2xoqfcymw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gt2jauiyead.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gt2qrnltamh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gt2dpolndlb.html

[I05] 按正则拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2pzcllkpl.html


<!-- 参考信息 -->