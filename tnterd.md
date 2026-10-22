代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtuultxisw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yongpay.top/Article/details/gtdjsimsvw.html

Ruby: Dir.children("dir")
来源：http://dali.yangfankeji.com/Article/details/gthmsldvxj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfpxtvbh.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gtjereqveq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtgyxgubtn.html

PHP:  filesize("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gthmiosbue.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtsxsuxzwd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtcylamvvv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtkcbzizbv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gtzzmikkvg.html

Ruby: File.size("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtqxwwzuuv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gtmoxnddtd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gtrxocgvtt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtcsjtpysz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtuodwbvge.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtfucblqdw.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtvvofpwxa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtnlubiyjq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtyipumtha.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtjqlzvrlf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtuoeueerd.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gtamxsrppt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtuhdxkfxx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gtndgqubpk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtehemtgrd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtlsboziuv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtusdsgcrh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtevcnmdrc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtqyxqonzf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gttdqdrkym.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gtpelzwnpd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtumtfmzqd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hammf.cn/Article/details/gtpwkmxrtk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtipuxsywk.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gttelgnavp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gttxfpvckm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gttttrykpo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenzaomai.com/Article/details/gtevovuwvl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gtfbneswno.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtcqkpdfnr.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtqeeqwvzh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrdgvppzz.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gthbqzdhxj.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gtceehauea.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtklvzpkyu.html

JS:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtnvpqlymq.html

TS:   class User { name: string = ""; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrvdeqvye.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gtiqqiznwd.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtxicolgvs.html

Ruby: class User; end
来源：http://dali.hfpthk.cn/Article/details/gtkgsgieds.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtilenwuoy.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gthuycysoh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gtmumgmnhd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gtdxwmgbab.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtkgwowrdv.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gtyomhxgwy.html

Java: User(String name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtcbkovjrg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gtyazoyfqv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtkvycqsyg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gteyacdubb.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmwgnssr.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtvnhhljcu.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtabvqfigs.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtdgcdrkfd.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gtjurnzwor.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gtleeqqskb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtngpxnaez.html

Ruby: @name = "x"
来源：http://dali.pycfn.com/Article/details/gtzvaslolx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gtcneqnrnb.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gtrjrxsoxv.html

Py:   def greet(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtyfrfdouv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtyidvyviy.html

JS:   greet() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzyqjlfbe.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gthpxbkzze.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtlxuyjpva.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtnkzfyfxp.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gtvmuhgqgk.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtmrcutmbz.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gtnkesxnix.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gtiewgxcke.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtaqpisilp.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtdrdqmcjb.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtpbilhvvk.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtoabqipcw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gtzkjutgyv.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gtdvttyqla.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gtoohzolbl.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gtampbqtna.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gtgwlrmlsc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtqaffuamt.html

JS:   greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtcejigwba.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtkvqkmwwh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbzdkgjp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gttjhrdaqo.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gtymtiicuk.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gtufignqkq.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gttritfzoq.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gtwvhvagdf.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gtwackkrvb.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtkcgolfry.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtqmlesbzt.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtrvqmaxor.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gtbnsfxajk.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gtnvqgvvaa.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gtcifktban.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gtcpsmetxg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gtoehezezh.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtejklbbcb.html

JS:   static f() {}
来源：http://dali.ybcxt.top/Article/details/gtbtybqhrv.html

TS:   static f(): void {}
来源：http://dali.9152youxi.cn/Article/details/gtujijmfnz.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gtwjmhwfgy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gtffmrsvtl.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gtiusdyhzx.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gtcgouslhs.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gthpjlznfr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.9152youxi.cn/Article/details/gtqfcoywfn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtbjdmcmyy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gtuwihgjkf.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gtpvmbrpqk.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtiblnpxmu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gtplxrfhgw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gtbjgjtmvt.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtseijfopk.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtcsgsjzdo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gtgqrsenbd.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtezyihkaj.html

JS:   #private 字段；其余公开
来源：http://dali.wangdashe.top/Article/details/gtrpbjuvah.html

TS:   public / protected / private
来源：http://dali.meibo888.top/Article/details/gtlanizixw.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gtalnphtlt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gtdwzkoqfj.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtbkcjfdff.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gtiuiltuoz.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtwuyovogq.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqoxzkzl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtxhurwuyf.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtlxxxtfgr.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtlstktfft.html

Java: public String getName() { return name; }
来源：http://dali.andypj.xyz/Article/details/gttqbacamf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtcthxhmib.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gtuprqrbqc.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gtzivlnrzy.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gtiyuyvyat.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtfuftgadc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gteijjsmbu.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwktxrnw.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtlanfwoal.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtiabengzb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtnvnecfpl.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtkffnzkyb.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtolhvuran.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gtfwglyfcg.html

Py:   isinstance(u, User)
来源：http://dali.birdmap.top/Article/details/gtxcabhvle.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchedtnkl.html

JS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtykgxvzaj.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtgerfdodn.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtcwlyjbcf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gtntgxkawo.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gtxkbgxvik.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gtmqzexnfr.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gtoziwjrdd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gtmncdkaxx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gtdncmnhae.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gtsearnkpi.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gtmbckpsuo.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gteszdroqu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gtzhznnoot.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gtynivorfh.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gtcdubhtmh.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gttjxixcsm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gtbntoywhg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gtaltvwdfr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hongshengwenyu.top/Article/details/gtpxejvyiv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtyjouwolb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gtxvkyfkec.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gtrragtwht.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gtomymaakz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtyljandvz.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gtofkdfdgf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtvgknlnau.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gtiwkensmd.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtniquygkj.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gttbppauxg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gtyccqewif.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gtkpchspfj.html

Ruby: obj.instance_variables
来源：http://dali.havefunace.top/Article/details/gtqxyydjni.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtebxwgucf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtadhrcnlw.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtdlktnlqv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtpglskxnh.html

[H01] try / catch 基础
来源：http://dali.yvedp.cn/Article/details/gtehzykgbq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtcueuowio.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtayxgusat.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtmyzskwjn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtshhhnhkh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gtrkbjvepq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gtfboiokwl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gtgzfacqfs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkorfysnu.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gtaouyxpym.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gtpjqxbock.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtihontqsd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtgzshhave.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtnlocuwrw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtwzhirckj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gtibbwtpdi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cqqwz.cn/Article/details/gtdadbyani.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtsodebluv.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gtbgmwkchb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gtphgjyycb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtxceyrydi.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtaiapbzvg.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtkvcudqjd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtfbrgajgu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gtgpuzznpi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gtdsaqrkas.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtejaxfuiy.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gtqsmgwpsi.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gtpnswxzsc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnpouplo.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtytnebuws.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtzaoypsui.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gttkilrwga.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nwbrower.top/Article/details/gttdlihzpa.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gttznzjaap.html

C#:   class MyException : Exception {}
来源：http://dali.shangyingyoupin.top/Article/details/gtkrngctfj.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtccphqzek.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gtfpnsklwg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gtultzuwex.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gthsvjklps.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtsncvluci.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gtresuexvp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gtiiappihj.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gtomynxlha.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkjnpsvcq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gtfxwzkgib.html

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gtfdgjflgj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtxvpyeumn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtrwyjabkd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtfnoxmfon.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gtzgqxfjqr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gtssrlhbmg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtqypjrnta.html

C#:   obj?.A?.B ?? default
来源：http://dali.aizwys.cn/Article/details/gttxgccigc.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtvnembtjo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hfpthk.cn/Article/details/gtfoehudet.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtiaqvdlte.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtzzlxnjdo.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtpijiuviq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gtecqmvioi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtshlhbbvm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gtrmysotlw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtuhrulils.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gtwlwhbylg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gtmeuitcrc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dianchejie.cn/Article/details/gtxefsudhz.html

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gtgbuudrfv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtbfeypwxo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gtbonxsodi.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtssnqkidp.html

Ruby: e.message;  e.backtrace
来源：http://dali.yvedp.cn/Article/details/gttpqceqrd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gtzdxbxisp.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gtbvavnjff.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gtgzybefnt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorvwknoh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gttanevjwa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zycfv.cn/Article/details/gtaqinvumn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gtiupqccsj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hammf.cn/Article/details/gtrsixmqbv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gtpgdnvojs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gtvbovkppr.html

[H10] 资源自动释放
来源：http://dali.svipenyu.cn/Article/details/gtolaoiqgi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gtyaqtbopt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtomivgkpg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtrylflvla.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtikjnscgi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gtkvardmch.html

Go:   defer f.Close()
来源：http://dali.jinghuilouyu.cn/Article/details/gtspncbemm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrelfdgfj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtwjydlfbq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gturvzptoz.html

I. 正则表达式
来源：http://dali.aibaodan.cn/Article/details/gtzutukzth.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrylmnzmv.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gtplxgmthf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtcqkqhbtg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtidnynvbq.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtntyckzwe.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtymuudwez.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gthqedkrrl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gtrniwsbcj.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvbnluyk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtwsoqtgut.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtqhwueruq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtyqjbcnnn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjeffzak.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pycfn.com/Article/details/gtvplfqaxg.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gtweazizvm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zdqjudy.top/Article/details/gtemeyygvg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gtbhzrlozc.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtvfzyqags.html


<!-- 参考信息 -->