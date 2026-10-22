代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtlfjbriaz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hysaishi.cn/Article/details/gtzeqpmqqh.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gtkzsmxsxc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gtfruqekxg.html

[F09] 获取文件大小
来源：http://dali.tanke756.top/Article/details/gtkdujbwcd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtwziwuhib.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtsyzprwvm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtrsopmgbg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtscqueruh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtnvtcshes.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gtmfwisfic.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtypnlrgfi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtcpzglabd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gtdyleagow.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtkxfsfsmg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowhwodqg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtkfivyvnw.html

TS:   path.extname("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtnbdwsbxz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gtlxmgfiij.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtdbqbqwxg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtiuwchvmu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtkmawaxnu.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtbhrlhhcs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtrzwkndjn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdhohpdu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtciixiajd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtvwxxkttv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtjvdjicrw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yueranfly.top/Article/details/gtypsjykqd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtdicxttex.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztfobiwd.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gtqcijuhin.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gthzfuruda.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gtzygeignf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gtlclhmxsc.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gtehjsoach.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gtntpdlbxs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dashuyun.cn/Article/details/gtcxddjjpx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtuatdxjpk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbqaemsg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtjzbfieyh.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gtnsvmedrw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtxzqururx.html

[G01] 定义类
来源：http://dali.jinghuilouyu.cn/Article/details/gthzyadrfe.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtlcmwamrn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtncemsoee.html

JS:   class User {}
来源：http://dali.meibo888.top/Article/details/gtrdgihkia.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteitseiiz.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gtvxluvmms.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gteztmqzfg.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gtxcyjssax.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gtglvhwbpz.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gtswlsbgvt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.kuanghao11.cn/Article/details/gtuwoovefu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gtlzcymzew.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpugxzduv.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtikqxjohz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtrbhpnaso.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gtqhmhhbtr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gtaeyhbspw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtbfkwhkdu.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtygytlcgk.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtvlviekyk.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtlkdovbtt.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtvxfbaaos.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gtegvgpjtl.html

Java: private String name;
来源：http://dali.daxiang520.top/Article/details/gtmjolitto.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gtzcikqdtl.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gtgkmpmyyh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zdqjudy.top/Article/details/gtwmzxbynl.html

[G04] 定义方法
来源：http://dali.aizwys.cn/Article/details/gtxpqtiuvz.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtqqmqfnfd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtikujvdqj.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtwrtnooij.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtgtkdnmoc.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtjttdglms.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtrpvncbgk.html

Ruby: def greet; @name; end
来源：http://dali.bjfxy.top/Article/details/gtwcjahcbl.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gtimcxtvjj.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gtzojwycav.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gteuwlyizc.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtzakeisbw.html

JS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtumqspdob.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtxbkbloqs.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtyjegiapl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gthfwlspdd.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gtygacaguw.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gtptjenbdh.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gtwoxvinia.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtawiwaqqg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtfltmtury.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gttvqqbhml.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtsmcawmui.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtkajgitrw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtthyweiyc.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gtlmtaamyr.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gtplydmsus.html

[G07] 调用父类方法
来源：http://dali.zhiwuduotai.top/Article/details/gtxcjkqfln.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtnvsuiigp.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gtrmpubqii.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtshewvmbq.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtipmuywug.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gtukvqdgcr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gtcgsqayza.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gtqbdtormv.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtdnwuymxw.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gtgpakuszo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gteiusapfz.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gtzlwfcozi.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdhzsrezo.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gtvooswwel.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gtmagngdxw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gtijbvlpii.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gtitnnippe.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gttbamuioh.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gtjtphtmyw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dianchejie.cn/Article/details/gtkojhpsgu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gtqwitmurx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.haohaochexian.top/Article/details/gtpnmgpuyf.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gtagusnaop.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gttgtxcrfl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shuidangran.top/Article/details/gtqfqxexff.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtmvkoafup.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gtpqazfwng.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gtnleiijum.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gtnulpwmku.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtigyzixhp.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gtewhfcicl.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtqdkmjism.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gtjzlisuso.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gtpcqxxbtl.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtefesjnny.html

C#:   public / protected / private / internal
来源：http://dali.zycfv.cn/Article/details/gtfupulosd.html

[G11] getter / setter
来源：http://dali.guannengcc.top/Article/details/gtbzdnfzhn.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtuswgagtt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtpklhpmom.html

JS:   get name() { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtiujtzzhj.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtasiprakp.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtkclbpdgj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtmhwlllpu.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gtrbfqpvcy.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gtxcsutgar.html

[G12] 对象转字符串
来源：http://dali.shzxlz.cn/Article/details/gtjtguevsm.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtobmqmbiz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtotkpgoel.html

JS:   toString() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtavnzwpwb.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtwbqffvoa.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtcglerprp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtyzdwqcxs.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtntliwdfy.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtvocrxwup.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gtsxltlipl.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtyxxmioua.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtrlltfiit.html

JS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gttvlqeslo.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtakkwevmc.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtqxnybnmo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gtniyimjeg.html

Ruby: u.is_a?(User)
来源：http://dali.chenlongwang.top/Article/details/gtqjwlrwiv.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgnlzysi.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gtermsfvvy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gtgzejycpp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gtqyzetdol.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtasmfiffm.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtlzqlvphr.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gtpkcsjtrj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.andypj.xyz/Article/details/gtfhboobvx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtwlmgpwnm.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gtztzqenmg.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gthmnjokxh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gtwxuzvmza.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnvdjupv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yonumen.top/Article/details/gtzowfjgpi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtsmzibjwu.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gtuqkzzriw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gtmeqrcjin.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtjtnkqirr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtrgloyhlq.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gtocwbtjqz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gtsperouqa.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtxzrcutho.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtddrezmho.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gtdalwpces.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtfypacuxl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gtblwbopgo.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gtoklhmlsi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgobitct.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvxzmxdze.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gtnqhqdzch.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqseszrwt.html

[H01] try / catch 基础
来源：http://dali.ybcxt.top/Article/details/gtxmwniwai.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtspwmfyqt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gtsmtinqak.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtqncopmbt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtoawborch.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dashuyun.cn/Article/details/gtjrgdtckx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gtirmkamud.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtmckvpkmv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtoybjmpdk.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gtjyjfnuob.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gtawmevwku.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtrqdxlydk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyqtkzji.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtudkuclbq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtgtthqpzu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gtmruiqbgt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gtakdvbwnr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtnhilnsln.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtcpbshsdn.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gtjzpryykf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtmsgaelbd.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtvshnkahz.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtjuyjhkvg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtwnzeatco.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtemighuzs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gtrmjkudxk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtuovxyfxc.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtyrkzhntq.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtiskacokk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjnglamz.html

JS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtfpwkvpiz.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtmhjdhnvd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtkzcnltwj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gtxprjpuul.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gtvjhdsdpn.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtyezgphcm.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfoibpde.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gtsrflwkxx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gtbnvuvfai.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtazofnqdi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtfskygsuo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gtqilvzseb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gttwgqfdup.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gtcfknaxny.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gtpsjlrvrv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gtdbwlaeil.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gtlwzwkdtp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtfxocokar.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gturdkwjvr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtyfnlrooc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtjhzrfsgw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gtbfowljnl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gtvdqrezep.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtnvwkluba.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gtvabumdce.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtcvxaqlpp.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtoxouslnq.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtinwusaiz.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtscascbic.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gtecmemvab.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gtwnzayttc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtjgbeknlc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtjnmihwbx.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtqlgjglan.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gtcrirxcac.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gtwrofmqod.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gtzesupzbs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtzstwyqvg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gtzwerrqlc.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtrgeuyzeb.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gteypyatar.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gtnfdvsaes.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gtduuqwncl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gtqdugobzc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.iojbl.cn/Article/details/gtfwwgmnao.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gtiipbygvu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gtkmxyksvm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gtqsvoigdw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtarkmobca.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gtwmmwgppl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aibaodan.cn/Article/details/gtmwwrfcpp.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtbcnhxiqk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gtdnmwosyb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gteuppflbd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtpmljtxiq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtnrjurrxq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gtmwhuugyg.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gtueyvizax.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gtxdylwepn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtnegrfqza.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtglpipdce.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gthvqjjzbe.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtldfroiic.html

[I01] 判断是否匹配
来源：http://dali.zhoulong.xyz/Article/details/gtlceazruu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtrzudbgpi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fengsongda.top/Article/details/gthayqbqex.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gthzogysqr.html

TS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtlvneaipd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gtlofnwyba.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gtjzvdmqws.html

Ruby: s.match?(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gtqzprnhrv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gtgreljpcw.html

[I02] 提取所有匹配
来源：http://dali.yueranfly.top/Article/details/gtlcqnaimf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gttkabasqg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtchbozbii.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.9152youxi.cn/Article/details/gtaueyqavl.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gtptfzfuvz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtqeeqhogg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtcqsqioul.html

Ruby: s.scan(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtpkoctqgf.html


<!-- 参考信息 -->