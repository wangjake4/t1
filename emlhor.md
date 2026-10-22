代发 wailian999

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gtqatglmkc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtttqwwjpo.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbnarcaf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtjnrvsbjw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtrksltzid.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtqulgcxpt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gthkcnbkzf.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtnvzsauht.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtrcalnevq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gtywledepn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtknwnefqa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtdznemsuv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtpxqesynu.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtgbcjrutv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gtpkzsobaq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygvuvols.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gthiznzubm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwzlvmpf.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtymqgddrd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtjpnctlvd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtisdfjsvb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gthnptfsuq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtsnakjgqk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gttvbgtxiw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gtzgycobrf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtqurixkqp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gtxtqiulfz.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gtlymqpzct.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgalqllro.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtjpgjdmiy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gthgbvpsti.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gtbiegghcd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtfcpnlknx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gtfxfigiku.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtqlzelnec.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtveknpgot.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gttoyctxuj.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gtnsdvlnll.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtzifijlqv.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gtepveobdc.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gtdjirxrqe.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtzfydimxv.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtaidwudwj.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gtsppntgix.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtdepguavq.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gtubnsroee.html

Ruby: class User; end
来源：http://dali.jlsjyb.cn/Article/details/gtcjwgbxeo.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtaufytzyi.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gtllfgfbrm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtoexpifto.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtpuqpowfm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gttfocuulq.html

TS:   constructor(public name: string) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwppgphsz.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtehdckqth.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gtzxselorw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gtzdhsuzso.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gtdlyrnjbh.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gthddekndf.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gtpgogccph.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtjpyyajip.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtsraxcmhk.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gtsngkgtlp.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gtszifugka.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtoodbjphq.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gteewrjhhn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gtfbryezkp.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gtmipvaaby.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtrwsvqmpt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtqjrkbowm.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlrvhalh.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtmtbezamn.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gtlclxuunn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtetpvzvky.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gtukiytjgk.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtzltdapvz.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtjidkeecd.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gtfcoytklf.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtmmqqonss.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtqzfteosr.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtdjdwsepu.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtdvzpzfho.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmufiqaiq.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gtqhtxfhnu.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gtygnyxtql.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gtfkqbuwyn.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gturnwisvg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtbsdiulen.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtgugvwvcu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gttmltgjnh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtulfavjhf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtlemeclfm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzofdzsmq.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gtdekmrorx.html

[G07] 调用父类方法
来源：http://dali.jinqigufen.top/Article/details/gtkbsoqvtl.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbebzldj.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtejgdukmz.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtrxghfyge.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtrxnrnyax.html

Java: super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtszkoxpdy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.iojbl.cn/Article/details/gtcijchyka.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtjbbbtdjy.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtabinsjip.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gtmtvzinue.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gtyrbvxbhd.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gtgpownkbi.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtqqscnpez.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gtxkldpvpx.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtxgehehja.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtwzjvnpxk.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gtcayrkvaq.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gtwimnhcnz.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gtyxmsbpgr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtyxdwelkl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pycfn.com/Article/details/gtueagwlet.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gtkjgnzgec.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gtcxeajawk.html

Java: interface Shape { double area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmwqbshef.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtyzrnqbsa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtrmxwftgt.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gtuoraomqw.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gtbcwlcexl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtfpfuwqsv.html

PHP:  public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtrdowybfi.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gtrnrhtchd.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtmrwagtkk.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfuvutbf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gtwjvuzgeb.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gthkyuaoaa.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gtqpevvuqo.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtnuoatwop.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtlohdnzdo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtxeicyibk.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtbvszovkc.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtomkvzkyy.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtzehvxtvp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtvptpcsjp.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gtgotvztbp.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtunqmxkmq.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gtbxtknooi.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtrtldrogs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtpnajujbw.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtivtruhya.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbbfshqff.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gthrusnyyp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtwvmvmhhh.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gtpjxgjegt.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gtobbypzle.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gtiwgzbckk.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtvkbowrbw.html

PHP:  $u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtwrsingxx.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtttlxfyyy.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtqbaohvaw.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtsszrqcfa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtfaxkxkfg.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gttrmuvzcc.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gthnasvrfg.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gtufvhuilb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gtlqixxrzf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gtxugcyljs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gtaqcdelyw.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gtekorlylu.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gtwwtwelhw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gtxdipugdp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gthcufycsv.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtonprhcqo.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gtojjanwjh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gtsmqeypat.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjhfbrtm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gtrvbioseq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtaqtfhujs.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gtrcyxntdw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhixingplan.top/Article/details/gtnxjcmcpt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gtucdrcwvm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtgjjunmei.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gtzlozlfmq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtogmjsuup.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtwzugprwh.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtmfxvkxly.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtdabduppd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shangyingyoupin.top/Article/details/gtmuanasrg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gtyslvvwju.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gtknpmnwjh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtucpgncyx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzrptizgj.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtbpkqaaxc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtstagqqbg.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gtsmesxrib.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gttdmrjnzh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gthisodcxk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtfbmtyrrq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtcuahckdk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gtvvswoqsc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gtxtexomcy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gtkylgfrlz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtkdbzxjck.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyrhzfgh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gtryerkvuv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtwqqwautu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gttbhzrxbw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtbvussqmp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtbyxvtzac.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gtzefohuvb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gturayguhk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtaxgoiqkm.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtdxqsiolu.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gtrhjxzbyv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtdyxeqvha.html

JS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtjdnywhdo.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtpoohtxmg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtihryekad.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gterbowzbi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gogol.net.cn/Article/details/gtstaobyzy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtdxhuntna.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtzzyhlwec.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtcfykjgzd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtiwvhrpqe.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtehdcgecb.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtiugslxtk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtpovjctho.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gtvtmvvujh.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gtsirhfpqz.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gthyvgesal.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtsbxyityt.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvhidbub.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gtrlghwlik.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtbnbgslae.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtynoafrft.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gtsptkqllm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gtxtdmasid.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gtammavhlf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gtiwluzkji.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gtellmqtlk.html

Py:   value = d.get("k") or default
来源：http://dali.sxryk.cn/Article/details/gtehkfftpy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtnvbnuhqh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtropafpsk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtefimnjhn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gtwlpwpbjo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tanke756.top/Article/details/gtdxmxevdx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gtjfayezek.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gtzibhjfek.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gtcwgwycbk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gtupgnshxt.html

PHP:  assert($x > 0);
来源：http://dali.xuanzx.com/Article/details/gtkjonrjul.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtwwlmqbrv.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtogepfycp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtqwsltczr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtexomiqem.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gtkktzwtva.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtoiwvojcn.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gtucxpxhhv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuxming.cn/Article/details/gtveiymdbm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gtywsyfwcm.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtlhbsjgrf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gtdtmsktwg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gtkjxaegii.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgpjyyst.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgogxqnbm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gtompxigkr.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gtutdpnkjj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gtbzldqfiv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifxmzvpo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gtsnlgmrod.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gtlljrcoje.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gtuxktjzuv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtpsokixvi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtdawimigx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.smart0.xyz/Article/details/gtzuuzyzhf.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpscfwwp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shzxlz.cn/Article/details/gtqpieywdc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gtsvwzhall.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtekagrxvs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtgwtxwceq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtqinuzvmz.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gtujlsiell.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gtafmswvbe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtkunmuwak.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwiviyrlt.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gtbblmxfkz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqukexsft.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gtczqkrgao.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtxaacrpqa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtvrnverlo.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtkbzigzfs.html

TS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzrdqdcj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aizwys.cn/Article/details/gtjbuwxutb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yvedp.cn/Article/details/gtuowgnjel.html

Ruby: s.match?(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtntqjniho.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gtqkkxoece.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gtosohgtuy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtavumlaza.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.vqdsnc.cn/Article/details/gtjmnuctvh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdejjbex.html

TS:   s.match(/\d+/g)
来源：http://dali.zhoulong.xyz/Article/details/gtnmukzxto.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gteljtvmpt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtuejbhpbt.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtorixleat.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuxming.cn/Article/details/gtdovyplhx.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgezrlqu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cashguo.top/Article/details/gtbolbmgdx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nwbrower.top/Article/details/gthfvnwxck.html


<!-- 参考信息 -->