代发 wailian999

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdilvfbr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2oxqoofbl.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2onevobyk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2zuubzcnp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gt2xfvnsfnf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2eckmifod.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gt2ryumvdgb.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ianpxdrf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gt2atiywmcf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daxiang520.top/Article/details/gt2udcilupa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpcanlfz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2qgqfmpbp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2kprttyot.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2lwyozlmz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gt2vwegxcca.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2zqqxrmhi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2qbrqmmgl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2zjstjrws.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gt2dzecnovw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojsubtav.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gt2ukgwslks.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2vlrselvg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2siwdnhrz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qopnamyo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gt2gtfyuygb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2ybkqygfu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gt2cakuyljd.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmpcfxny.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ngtayvfx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pqqvyosb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gt2lexqdzrk.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gt2fpkwojwr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gt2cnyrufpl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gt2xlfbacln.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gt2gfnvbice.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gt2eifqtqga.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2sziatmmk.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gt2mbqlckiu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2fygfxvig.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gt2ooqmjpdl.html

Py:   class User: pass
来源：http://dali.guowangkeji.top/Article/details/gt2atzynmcw.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2kttwusci.html

JS:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uiuwygxs.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sesoorqt.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gt2qqnwfjey.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ppvxvjzk.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gt2dizmjgbi.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gt2gvxewjqb.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smmttkkq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gt2rxcdudnp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gzhubu.top/Article/details/gt2pwxtoxgm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2vxyoknxd.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gt2biwujcfe.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpcpsdma.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gt2qvurzmlt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gt2ntcnzrle.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2peodmflq.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gt2efcttdsa.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gt2hrzmezjx.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gt2hvqeoibu.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2efjtjsed.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gt2vuqwxanu.html

Java: private String name;
来源：http://dali.haohaochexian.top/Article/details/gt2rlbohaor.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gt2odoesgov.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2mbtwqfej.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gt2icgwdapt.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gt2vvbkjeuy.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gt2lukoywhv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2htfxmhqn.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfyyengu.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2fuyjtgcj.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2qjedxkas.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2lheixefd.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gt2wgahvjym.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gt2ywyfebqm.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gt2npzftwiq.html

Py:   class Admin(User): pass
来源：http://dali.meibo888.top/Article/details/gt2ysoupuwc.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2wxvebjop.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2nrwaxgel.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2dxvvcieg.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2pzqsdxiz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gt2hredgsns.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbzmqike.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvfelnqf.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gt2sbbdbmjb.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gt2jmvljvxz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2hhzlouav.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2spcticxm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2yjbmflsg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2zsxcdulx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gt2jjtuosgc.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gt2lygsvvqe.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gt2fvjbvnwb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eymhmuzd.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gt2trfvnpxn.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gt2urgjsogz.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2qqoanayl.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2bdjeycbc.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2tawhfzyh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjqhkuan.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gt2tzmszfza.html

C#:   base.Greet();
来源：http://dali.tanke756.top/Article/details/gt2gcmjvdjs.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gt2jrnazyyx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnldakpp.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2fasgihle.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkpukaya.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gt2hixaualc.html

Java: static void f() {}
来源：http://dali.wangdashe.top/Article/details/gt2nxrjvysf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.9152youxi.cn/Article/details/gt2bimhhixi.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gt2fgjdliri.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gt2ntztpcrh.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gt2tqzofman.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gt2qspjexnj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gt2rxfvxegi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gt2iumjzvhd.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gt2dxaiasvs.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gt2mbcmnkir.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gt2uwepqbtb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gt2ekwtdwzq.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2djhvhsgv.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gt2weaiwzty.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gt2oykoelas.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2tmpmqdvd.html

JS:   #private 字段；其余公开
来源：http://dali.gotoacloud.top/Article/details/gt2iawonvwm.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2smklsioz.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gt2kcbwfhqz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gt2hxwnajvz.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2uxuqihhc.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gt2oxkgulsk.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gt2otdqwhdo.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gt2kzssnblk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2hszzkjyo.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gt2zaeenuhm.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gt2tlhagaji.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2goyghstw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2wmfhzzve.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gt2kfqqctyw.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gt2pfmfbtgu.html

[G12] 对象转字符串
来源：http://dali.aizwys.cn/Article/details/gt2timjynjj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2ohuogboy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2gfymjoae.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbwotjws.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ymoxzgve.html

Java: @Override public String toString() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2zzmxsnrg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2janfromu.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gt2gfcaanbw.html

C#:   public override string ToString() => Name;
来源：http://dali.jiagoushi.top/Article/details/gt2czuhdkgg.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gt2zkkbluqv.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gt2ikfbqsmj.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2sycfzkfj.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2cdlwtdzi.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2yivursjh.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2eqcpdbzj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gt2ozoluycm.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gt2lnqxjphq.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlkispzl.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gt2kvopjpnx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gt2aublqnuk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdeobhqq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gt2yzmqklmp.html

TS:   type User = { name: string; age: number };
来源：http://dali.xinyue.icu/Article/details/gt2zdshpwfv.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptxjuhfo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gt2drvgobtk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gt2dohpjmey.html

C#:   record User(string Name, int Age);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jtkdxgll.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2keqypses.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gzhubu.top/Article/details/gt2jzbswkyw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gt2ykdmisgo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gt2dkxmvivn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgbijcnn.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gt2uzbxceak.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gt2vtitdbyg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tianlin.xyz/Article/details/gt2zpngoqop.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gt2idyqjqrg.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gt2tdclthmk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gt2yefvmonb.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gt2ydpsqutp.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2cgpwonit.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2smjklcnl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gt2yvviwmwe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gt2pxhpytbb.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gt2cmarfqmi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2rwejedlw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2sdijhmiq.html

H. 异常与错误处理
来源：http://dali.zhoulong.xyz/Article/details/gt2hcuhrvst.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ienjmwpx.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gt2rfjxgqvd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gt2whdbkyea.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gt2urjmjoeg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gt2titzqtbb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gt2yusvaocx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gt2wmolqrki.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gt2yttkuxnd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gt2cutekjhs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2resdcvcu.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gt2xyutrsef.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gt2klaqxhqz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2amqnwqlw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2huvcqczh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2ilqnhxkp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2dvdbvhcz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gt2ninawhwi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzyivdvo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2ltvmbbcd.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gt2qzmxsyhm.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gt2piulzxwv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2ceiylyir.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2ovivjavc.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2hualjqrm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2ajjdpfuy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gt2zcsugnzc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gt2eplcgxjc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2uccfguxr.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gt2gdzpzynu.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gt2mdfwugvc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2wcxdqzrg.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gt2jjcywogc.html

TS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2oemjpjfp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gt2nnusosao.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gt2njembxeh.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258.top/Article/details/gt2qljusdyo.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gt2dlypvdhn.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqmzrrpq.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gt2djchpzaj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnqzz.top/Article/details/gt2sqbzuzkc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gt2qjtfnjbd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gt2zkkeptdk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gt2ngbhxkct.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gt2bdmendhw.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gt2zpegzyku.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gt2xsqybjhr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsmwpgkz.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gt2zzzyizgd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gt2tndeqncy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2osxlxkwf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2sdmobrso.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gt2yddozepv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnbqhlmv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.andypj.xyz/Article/details/gt2ikqsqinj.html

C#:   obj?.A?.B ?? default
来源：http://dali.birdmap.top/Article/details/gt2mlgslhug.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gt2ptusvzor.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gt2mcyybhjk.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2nvgpkwyg.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2nzcrqfpj.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2zphxzvcs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.iojbl.cn/Article/details/gt2bitcubnu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gt2ciqanvsb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gt2qtvwonqq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2ihjerfvn.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gt2mcalofzv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gt2vjyzyqms.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gt2ovcrrpmy.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gt2oifmcjdq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gt2uoqahtzk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gt2kchvivbp.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gt2mewclojm.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gt2gzgrcxge.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gt2nveoiqry.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gt2iwyazmec.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aizwys.cn/Article/details/gt2lhgabmwz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yonumen.top/Article/details/gt2gmjpidxg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhengqikj.top/Article/details/gt2nwjaulpj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gt2qznfvshv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dashuyun.cn/Article/details/gt2rahvlzbd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gt2iwemqcoo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gt2eceqncvp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gt2qhtlfqga.html

[H10] 资源自动释放
来源：http://dali.sufxvd.cn/Article/details/gt2jipsqhbb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gt2fcigdvsd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fengsongda.top/Article/details/gt2vmqzlser.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2yjnvsnqs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddqgpzdz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gt2hyfcvgkh.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gt2jplysttw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gt2dgkzhrqp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2agvazpkg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2dpglpbjh.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gt2dyzuviob.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2gkwtgodw.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gt2sneznrfp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2ljfwrvoz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2jylmxycg.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2jrvozwag.html

TS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gt2dkrpqfvb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ysezwlqh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmjruwlc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2temseosw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjgryqlc.html

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gt2ccwslnug.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2iqcecpva.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gt2ukxiuypu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sxryk.cn/Article/details/gt2tiqvuwam.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxinkj.top/Article/details/gt2dzudcqeg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daria6918.cn/Article/details/gt2enzvvhnj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gt2mlsdbyjj.html

Ruby: s.scan(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gt2zfbdzsvl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gt2afcuiqos.html

[I03] 提取捕获分组
来源：http://dali.gogol.net.cn/Article/details/gt2wlqtmzcc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gt2pruldcdk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gt2vpqsvljp.html


<!-- 参考信息 -->