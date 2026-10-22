代发 wailian999

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llbrmllk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdmqajkh.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2gdomrnko.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gt2lalhahyt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2emjgfbwn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2wtbwzbqy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ouwwbkuw.html

Ruby: File.size("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2lhavowpq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gt2iiesbosj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gt2pztshyhq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2pdsdvfns.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gt2meudxqas.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2xoxnrdxg.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2opexagtn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gt2uvleqxfw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2allucvly.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2pqtwdsuf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2raaapbfh.html

[F11] 复制与移动文件
来源：http://dali.sysykeji.top/Article/details/gt2wdjhhpju.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2ojawobfc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmgxbilv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2wiqurgqk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2phdihkpz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xinyue.icu/Article/details/gt2ugrmnvqn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gt2xjmtkxwk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2xktaxtrr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gt2geszdosd.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gt2zaumcknd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gt2babdyrfu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gt2qsklskum.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gt2loihxoru.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gt2bvykefvg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gt2llzkwxqb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gt2hcnudhlg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.birdmap.top/Article/details/gt2imdxodcj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gt2mztbhnxh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2dlyzmfiz.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gt2rldmdinw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2htqseizi.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdutxiah.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gt2fawytjgw.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gt2gstpltrs.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gt2nmdgravk.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gt2kfmrkweq.html

Java: class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2pnqfjvra.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gt2moikhioh.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gt2kjmayorv.html

C#:   class User {}
来源：http://dali.xinyue.icu/Article/details/gt2vcagebxo.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzxvgrba.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gt2qxcfoesl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gt2vfjhvmlr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2wfjatuic.html

TS:   constructor(public name: string) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vceajetj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2kbinyfaj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gt2nelakzny.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gt2jkdwiwue.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffupfjda.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gt2dnishzhz.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2ahfjewvp.html

PHP:  public string $name = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2jsgtdudn.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2kmyicurz.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2grweuogh.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gt2hlwrxejw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gt2hyfsjnop.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2aglfdety.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2mafxbdmf.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gt2jkkchepb.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gt2rbylexbd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ntemjnnv.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2uzxisizj.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2tnanzxci.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2kecuauhp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2osqixapn.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2origyalf.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2gobviwod.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gt2urokbbmp.html

Py:   class Admin(User): pass
来源：http://dali.cucudq.cn/Article/details/gt2zvrpdybq.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2xesnuryh.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vlbxscds.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2eighnokb.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2dkbapgqf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gt2ofpojksp.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gt2vldflchj.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqieubdd.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gt2gmyvnwkm.html

Py:   def greet(self): return "admin"
来源：http://dali.havefunace.top/Article/details/gt2kbditzif.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ekybuumk.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2ciwprndu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jeeibbdn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2ktshqpzy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gt2wrvstgwp.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gt2gokihjsj.html

C#:   public override string Greet() => "admin";
来源：http://dali.birdmap.top/Article/details/gt2vzvkriie.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gt2xibkqfet.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gt2zidkxagi.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gt2akesixsp.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bpllifop.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2pwgaqiuu.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gt2qucqwtsx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gt2nreblehf.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gt2nljaixmt.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gt2fzhrpbbq.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gt2echyfmtl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipwftbac.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2fylavryo.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gt2iuirkzlf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlckwpyn.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2xkunonqf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gt2zxzerqwn.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gt2iwmalgvk.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gt2dainxayk.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gt2yxqbbtkd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvjcwqqz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gt2tywoqbco.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gt2ndwlcwfr.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2aambowym.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gt2suhrqvfj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gt2fqzazkya.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gt2adjnvkjq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2oyyagznj.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gt2ejhfznnu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izdqbgqm.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2vkzvbagn.html

JS:   #private 字段；其余公开
来源：http://dali.gotoacloud.top/Article/details/gt2wrppyxnm.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2uaqncoku.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gt2hxrxqyld.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eenxhpgs.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2moxgjlmb.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gt2tonknrix.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gt2ztifepbv.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvxhewjr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2cvdywijd.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2gjdknvza.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gt2sxxawpmu.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2gvvcuktz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zybvhhaf.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gt2lujxavja.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gt2yqrkwlta.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2wdbwallz.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2ysyzxgqw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2kqebrxhx.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2ghoejnij.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2txhfcghp.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2zqbzxnjj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2icleakqu.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogapokqu.html

C#:   public override string ToString() => Name;
来源：http://dali.fengsongda.top/Article/details/gt2fktolckp.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gt2zfhiyooo.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnjgyfou.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2qlqsjqqq.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvjjmtgt.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2xkcydhjp.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dntofqqu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gt2piwzrudw.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gt2wprjncmg.html

C#:   u is User
来源：http://dali.aibaodan.cn/Article/details/gt2guxeqhhf.html

[G14] 数据类 / record
来源：http://dali.hywenlv.cn/Article/details/gt2ndxfmfau.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gt2nurduwms.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gt2takjqusy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gt2regxyond.html

TS:   type User = { name: string; age: number };
来源：http://dali.cucudq.cn/Article/details/gt2hmnanbpb.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gt2cxhcvhfu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gt2wgefhgoi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gt2jsrfufrx.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2soawgbav.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gt2qlrltzef.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gt2vqhizcgo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gt2bpjsacjt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gt2myquydnk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gt2hxfcswpp.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oxtnosog.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zivtxoma.html

Ruby: Color = %i[red green].freeze
来源：http://dali.birdmap.top/Article/details/gt2knkbhogz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2jpcpvnmc.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gt2dymdrqrj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gt2ptttgajd.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gt2meqbabdk.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2cpcpwjcx.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uavnuadb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrdisaee.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gt2xuqabeau.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gt2xgsyhppn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gt2fyffzizf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2nixtrlxs.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2tkvmkzah.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2siqxqprs.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfxvtmtq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gt2zsjtonox.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gt2amhbigzk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2ockfbsar.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gt2axweieby.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gt2dxxjavxh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gt2rqdqhjel.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gt2ndhkehiv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gt2wxktkkci.html

[H02] finally / ensure 收尾
来源：http://dali.mhx1999.top/Article/details/gt2nqlbxjle.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gt2vupupqcm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2isznmlcu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2ytxsbtph.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2eskeyzba.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2rgwaprgu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gt2canleufw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gt2wvgjkhta.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2gdzvfeap.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gt2nbgpvhay.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlwvsgdj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2scsvqqee.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2vwqolhra.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2tfcdaest.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2pyyonieu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gt2ekqncldz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gt2nphuytcv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2bfqkcyyf.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gt2ciijkcqy.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gt2zywgvtmg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2ihnjrgnh.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gt2vinweele.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2wdibizsy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2azxbltja.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhiwuduotai.top/Article/details/gt2buhfazcg.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzvrmuyy.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gt2ehejxdee.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gt2mnvasoex.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gt2dluwbhjk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gt2olleuhcm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2yyeftigc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gt2lgumvovj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gt2frebpooh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gt2xfmkgxxy.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvudqjvo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gt2zitcclie.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gt2joimbads.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gt2mswyzyod.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gt2fdzjuuhr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gt2eclyfqzt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gt2ffyqukfg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gt2ctcqgprn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gt2jitsmnyj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gt2omokfuzq.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2luhptjlz.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gt2ghvquswf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gt2pyywamws.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2ocaxyclt.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2ehfksigu.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2kngtgmqh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gt2pwcqbouv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gt2colslgyv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gt2nigehjrk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2aourslwh.html

[H08] 获取错误信息与堆栈
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkeuatjy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daria6918.cn/Article/details/gt2hktmegzw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xylfe.cn/Article/details/gt2cljkwjqn.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gt2aqdvagnb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.snrcjt.cn/Article/details/gt2pxcqzaxa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gt2dokwbhtl.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gt2imyvunit.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gt2ywlldjks.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqqblxyr.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gt2atxxohqm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gt2dkfqvsxi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gt2hywppuwy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gt2kcigmaih.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gt2pcetjmdu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idfnialr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gt2ynhhltrw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gt2ivetwwjk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yongpay.top/Article/details/gt2mtudhxtw.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gt2jgwitxxx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gt2olgtttdk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2qejgrasc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gt2esarcdek.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gt2vopvubca.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nwbrower.top/Article/details/gt2mfeonlqs.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gt2slzmjdxw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gt2qzhhwxfl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdeenabw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2zbctuohy.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gt2ruhlrrvf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2eraxhcts.html

[I01] 判断是否匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfwkhggd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rabyidjh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iitoatll.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2cqaccupo.html

TS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2ygzyhatu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gt2opogegat.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2knmwqpgs.html

Ruby: s.match?(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxltvsmd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gt2cbmuuoud.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gt2yvbsuzhg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmktwygj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gt2byebqyiu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmwwpunt.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gt2czxihmuc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2rsvsmars.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gt2qngxwdpa.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gt2hhtwwkrg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2lmpuwxxq.html

[I03] 提取捕获分组
来源：http://dali.jyoumei.cn/Article/details/gt2bshzsgjc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jyoumei.cn/Article/details/gt2swsrifqd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiyculz.html


<!-- 参考信息 -->