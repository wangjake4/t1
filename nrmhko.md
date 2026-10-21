代发 wailian999

[F09] 获取文件大小
来源：http://dali.daxiang520.top/Article/details/gtvyfsejgw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtkwmbaqxq.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtliboypwy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtouoeuskk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtdrccpvgf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gthgeurlyl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gtheerkxbr.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtgjaemkie.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtefixchhy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlrwkmvl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtsbazlqla.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtlkpmkrsw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtgrfvwyad.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpndrmopw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gtfwookihk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtkmmrfear.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gthtjrbtqb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtlhwdpced.html

[F11] 复制与移动文件
来源：http://dali.jinqigufen.top/Article/details/gtxnhsaunx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gthohbyhaw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtlyiynfhq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwfdfxecx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtrdmyurvb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsougavcu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gtdugspaal.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtuobcfwxc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gtsfpyqprg.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gteruaffkl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenjidiqi.icu/Article/details/gthtbfqefm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gtpmrmlcgj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gtvqkuoojw.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gtnktljjfk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gthyozpulz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gtkircedyi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtnmcmsabk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtloobmzlb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtavknqobc.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gtoqnkqnco.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtzwquvgfj.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gttpzdoppv.html

Py:   class User: pass
来源：http://dali.guowangkeji.top/Article/details/gtnejhqiae.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtkezwtjqc.html

JS:   class User {}
来源：http://dali.yonumen.top/Article/details/gttrywopzf.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgufenzy.top/Article/details/gtuhdcnitg.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gttkbopuxv.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gtvtkgipoe.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gtrvqjqgxu.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gtmcccnpbt.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gthxkjdgze.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxinkj.top/Article/details/gtduqfyfyn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtxjdcvenp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gttvkffnva.html

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gtjmgjcdfu.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtixlhjiwg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gtvrowboyx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtvocclobh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzunruzsw.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gtfzlvjjcp.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtvqmyoczh.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtxvtuuurp.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtvcnucqcy.html

TS:   name: string = "x";
来源：http://dali.cucudq.cn/Article/details/gtlbyehkqs.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gtteoraimb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jyoumei.cn/Article/details/gtzvrdotpm.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gtgpuhwjti.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gtwwsvdsdw.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gtedjyzecd.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtcjiinwwt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtceabkkpc.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtpgvmjvvi.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtuuvphccp.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtmtabhyfx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhtvoxtq.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtmomcqibe.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtnvcdvwop.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gttkwtmqrl.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gtzafsidpq.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtpueoqogb.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtkhtikmmn.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtggkpvzva.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtdtzpscll.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gtjdhayonp.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtffwptupb.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gtzbuiiisp.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gtguaavsek.html

Py:   def greet(self): return "admin"
来源：http://dali.cheryme.top/Article/details/gtvepamfgd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtxohaqrmb.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtuopuprsh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpywjmnaw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtfnmvgbcy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gtqwabopsm.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gtyudtqogr.html

C#:   public override string Greet() => "admin";
来源：http://dali.daria6918.cn/Article/details/gtytnvtmjd.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gtbkmmikeh.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gtpooyrted.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtrnhhtrco.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtfynhqhdi.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtkorllufr.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtatymhpie.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gtdwqlqyqx.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gtzqwtxwsg.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gtiemfqpba.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gtrfxqvpcz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gtxuawholy.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gtjmyarvss.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfnkkmwcy.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gtmwfnkgsv.html

Java: static void f() {}
来源：http://dali.yongpay.top/Article/details/gtrdtjhqfv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gtnmjzkcos.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtcnfjhsma.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gtpjgkhykm.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gtyiiulvhc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtszygnmtj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gtgsvgoqgq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtpsnemffz.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gtiktntmvy.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtwcryczht.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gttbhtdkjp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gtabowlybb.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtfelsdhhs.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gttvcgwosp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gtlsbxuidu.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gttcpmexvi.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gtitemhqqr.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gttnmucoat.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gtgzlcbrge.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtdblxwvsd.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtsonxnkxe.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gteqedaffc.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gtfepnapss.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtojprooxp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtdluuvmma.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtsdwnfpiz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtwnjxzuie.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtwswifnai.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtubmokqvm.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gtdagtvguo.html

C#:   public string Name { get; set; }
来源：http://dali.dianchejie.cn/Article/details/gtwrccsldx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtzwxkaerv.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtrwzxzwuu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtgaeaqlkr.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtkncxfrsw.html

TS:   toString(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtrzrywrzc.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtgaoaicax.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtpvtyxvtv.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gtqjektuwb.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtwwzsviae.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gtsaqpzehr.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gtmuyenwdq.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkwesjow.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtrggvpixx.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtvqdqnryy.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtplttrzrq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenzaomai.com/Article/details/gtofzevhqk.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gttjbbeanx.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gtiywsmmdt.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gteisocxfu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gtzwtlazjt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gtvtgiwwvd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gtpwxnvbvh.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gtukfaqahb.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gtoridiomg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gtdujdiizj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gtyqkrrgzv.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gtxbzqvqbj.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtghzwmgzw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftoaydol.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbbediyvt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gtyolkcgnl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtekeosqdj.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtwaaccvzh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtnknevuop.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gtdzxcfjer.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtfpqweugs.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkigqxzis.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gtgwpifjzo.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gtvlnevtfm.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gthdofexpn.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtjjkzthhu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.smart0.xyz/Article/details/gtvasmsepo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gtkrljttzz.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzbmpxwh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtgmpobilx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgdbeipjo.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtjnaxsvrf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqzyoofdb.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtonwklwbh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gtzlyetcxl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtgrrheavl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtciadhccu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtbvhfybnk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtrrnkpulq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.kuanghao11.cn/Article/details/gtfyhsfmhw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtxoovjngt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gtvabnkpbm.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gtiuqartzm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtqfawxawf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gthpdizlwe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtyiflxvbc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtjtxjrcbw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtucvggvdi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gtmalrsqua.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gtnygdrcnv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtcvcwuanq.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtsmxtztwd.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfsadord.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gthdxvubsb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtyotaabxu.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtqzmdbkvk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gthryaxwkl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gtxufsmswf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xinyue.icu/Article/details/gtaoxeanza.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtouiuzlhe.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtiziylwjx.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtjvztegyr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gttjgdpwnm.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtkxdqkbsl.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfipcesma.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gteniiahuf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gtnqnzknhb.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gtiwwtwiov.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gtasxumvcw.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtkvlqbjja.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gtvgynbqfd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtzkudezzx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtnbukipqs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtvggolduw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yvedp.cn/Article/details/gtkrpkyvev.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gtzpofrzzu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gtnvmuldip.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhixingplan.top/Article/details/gtjzdbionq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gtkpjhrrwr.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtcmgqibyo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtojyzjesc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtfqgjnoao.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtxttjqvmv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gtaxbkjfap.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gttxjdhjce.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gtdyxhtbsg.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtajyktxfe.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gtlmtybfdx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gtyleziswg.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtoayeioxy.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtxfdqlaad.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtquoukjya.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gtwwjxqcjm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.kuanghao11.cn/Article/details/gtwmchboft.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gtuhtsaqxj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtdwezqtde.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtwutpcytk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gtckrmqpdc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gtifhurhka.html

JS:   e.message;  e.stack
来源：http://dali.vqdsnc.cn/Article/details/gtlvmclhpj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gtitdiyvpw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtjalqftgh.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gtuoinfbez.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gtpozicaje.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gtvrrunzuu.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcredgvkb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gtzxraroxm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gtfcpubxph.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gtoyznmsfh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gtwtrjzkqr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gtlogvgcaz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gtrmmaqbbo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gtdaulqwpm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gtpwvoivfm.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gtannfcque.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvrsgbpi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtozsfgnpp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gttltyulbn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtimrpviqv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gtajnncxrh.html

Go:   defer f.Close()
来源：http://dali.iojbl.cn/Article/details/gtujlpuett.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gtpwirouoa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtundqrnta.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtcqarmhoa.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtwdazjtjc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmnzyexgv.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gtafrlfwju.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gthfxlrasn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtwhuiawwv.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gthmcsfbsi.html

TS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtredatpyr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gthdwlfxbs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gtbhqrmvxa.html

Ruby: s.match?(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gtjpycynia.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.snrcjt.cn/Article/details/gtzzlkoesa.html

[I02] 提取所有匹配
来源：http://dali.zhoulong.xyz/Article/details/gtwutcwvas.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtoxilnavv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gtbgixnqcf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtkdxgavps.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtzkjguocc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gtlwzycrif.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvndsbvj.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtzpicsxib.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtxhdazpae.html

[I03] 提取捕获分组
来源：http://dali.zhixingplan.top/Article/details/gtbzwnresy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gtptuyszjz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gthvatyngv.html


<!-- 参考信息 -->