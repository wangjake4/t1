代发 wailian999

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gtmggojzov.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtoimaufti.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gtxwhdwpch.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtqxdshjjz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtbqalegfr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtpswslbax.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhengqikj.top/Article/details/gtbyriddut.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gtiugekzhb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gtkyuceuxa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gtalhgrwto.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtqqsjcwkz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtsafmknyy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtzqqhpadn.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtboqwnkvy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgfzy.top/Article/details/gtnripvezo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtdweqmvnt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtcoejvkeo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtenmbvpic.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtitqdhpjm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtbauutpxx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtopsghuca.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnldirmcl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtxrsnzzij.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlphoqhbz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmdsanav.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gteelshwxo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gtboylmorz.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gtsktjuavz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gtnbkdyuko.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gtzgznwttt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gthlcevfwo.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtmwzkpdqx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtzohhal.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpisaetlj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgufenzy.top/Article/details/gtvusuimdx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtehdljqjv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtyphfgycu.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gtnzrtdlfs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtgnzzcfpo.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gtxxuastja.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtdnfoimyj.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gtwbtwaoyj.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtyytdohtm.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gtgzjtnxgk.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtnhiplcxw.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gtyydqktbr.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtanivvvwy.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtrhuqeyrs.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gtsxlpammi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gtqhlitwph.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gtdgwoxvql.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gthkrerexn.html

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gtssbpzhza.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtdilypidz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gtvumectac.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gtmmmtnfsx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtuzxognwr.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gtdmqxaeih.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gtbftxuvmu.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gtkpgucyfw.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtpwbqxonl.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gtrxmsxudv.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gtxqflgdej.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gtamggdtjq.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gtxughycto.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtbokquqkx.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gtcenvmhxz.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtqsmywxei.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtunoltvnw.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtuedgrbhm.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gthpnwdzdp.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnojlprzd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtfsholgje.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtfnwezzsv.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtiiilnjip.html

[G05] 继承
来源：http://dali.xuanzx.com/Article/details/gtqrtbjiaj.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gtvqvtysby.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtryshxjat.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtdvrfnbkz.html

TS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtjfzcfwpw.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtsnkfluiv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtnctceqpc.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gtxuxsyenf.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtgofotsiv.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtaswavydg.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtvprcfgts.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtyshwkpur.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gthdtryfyb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdxcvceec.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtulyiyzxl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtzmkfkmfo.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gtzkikljpv.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtonnngmyo.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gtwszrevbl.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gtycnbzedp.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gteufeusuk.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtxbyznbkk.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gthyzsqsno.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtrmwcabhe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzoxyqggs.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gtoibugmdb.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gtzcgvqell.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gtssmbpika.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gtgyterlca.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gtfvrvjjjy.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtsajspbyw.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gtfqtycugy.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtymyfoltf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gtayldytkz.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gtsngqxzju.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gtklniqflb.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gtdpyvhzwx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtfoprizlx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pycfn.com/Article/details/gthtrugoao.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gteamjnkzs.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gtfouqybds.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gtlgfjcybo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gtaybmeqjn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gtwxefrsqm.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtpmgpxesn.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gtxanriemo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gtdxcyshcz.html

PHP:  public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtnhpcirms.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gtmzmnltjl.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gtvtcewhec.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gtnlyagjwr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gtcizpqepf.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtbtomrszq.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gticvmswbk.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gtwbqnwjrq.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtvdzzwtuq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtorgnodji.html

JS:   get name() { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtmisxqxgg.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtsqiscybp.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtkeyciawx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gteqxilcjn.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtokrlfouh.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gttezjbzll.html

[G12] 对象转字符串
来源：http://dali.9152youxi.cn/Article/details/gtwzgdwjjz.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtetjetful.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpoinyqff.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtmeietcsc.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtklengzbm.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtktunkzbt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtljccffmt.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtpaxaaipp.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gtxywmounp.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gtihhavvah.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gtrdfpzref.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gttdfogyod.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtnrvrfnod.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtfhdjytoq.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtrjyzbanc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtbehotxir.html

Ruby: u.is_a?(User)
来源：http://dali.yueranfly.top/Article/details/gtslhsgptp.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gtaerlsvsm.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gtblzjdhga.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtbewmegpo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gtcuukhdko.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gtrvcajvlz.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gtthkdiroc.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gtayaoxzcd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gtmzorbgou.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulmttsqf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gtpddyelza.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtoeywaqda.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gtiighteep.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtyicmxokq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gtwvnunqev.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gttalqeywl.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gtmsehyoyv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gtukqqmusc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtnjsxixvg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtnzahejom.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gtbnaezqlw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtxutprlml.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gtryoadigi.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaobpund.html

TS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtjnxepmvo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gtilthfrvx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtdahlircq.html

Ruby: obj.instance_variables
来源：http://dali.yongpay.top/Article/details/gtynvxnujp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtthirxcnk.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdjtxihks.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gtrvnrtvpt.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmhlwxdsq.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gtzdyhwpma.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gtqtvjzjfk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtqeamkomc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtsbzikfqv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtslzzhnzn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gtvsuvrlsg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtilqwvhow.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenlongwang.top/Article/details/gtwjfibiwm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gtpgtwetce.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gtkmkdhcpq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.meibo888.top/Article/details/gtruawdzvf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxylvycds.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtppkhvkgk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtvsgddzxb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtsveoxbtz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtrlaqrdfu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtwlunoimw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gtavubnsfr.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtktafnois.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwotqcxm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtbblcvvoy.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtlmjexuau.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtmfrzwefp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtkhqkwyoj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tanke756.top/Article/details/gtwprqxcmk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gtueonqafy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtpuxqlrjx.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtsbgepeih.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gtmhiibbhz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrithkcf.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtwumwqawi.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthppzwrsq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtpptzwfya.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gtkeqynqta.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gtfxqjwkau.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gtdkhfyqkn.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gtayefyphn.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtfoifvirw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gtthyyvujk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtpkptxfsu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtimzqnurt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtrhecljwm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gthgzqrvqr.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtktefjdat.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gtkqvywcxe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gtswbgdecr.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gtnycljlux.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtjtriozxy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtsydatnky.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtuqrcakrj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gtgqzwapmj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtgvvhrcyh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtzybfwgdo.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gthzodrxdq.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtggsizydb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gtfplwrwfk.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtwdhbjrby.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtdrifoxdh.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gthcmyjcoa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gtpfgzfduu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtzaprlymp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gtpiepnuhj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtnjtykhlx.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gtmypgxtqp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gtnpvopbpu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gtalhbnmsy.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gtrbpeqwip.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gtmxqiojhj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gtgiskectr.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gtvgmyovez.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gtmymyfniw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gtkhagjzwc.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gthqjajuci.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gtxmipaoyh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gtiexcwxka.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gtlumrcwkw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gtqmkidsqw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbcnsiccm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gtzewifcit.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.redwolf501.top/Article/details/gtvwsyczxe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gtqizbdkvz.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gtesdjwark.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gtslxhrsxq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtpkmmmoii.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtiwpgziva.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gthrkmgtcx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtddcnxonk.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtcuvdtgpz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvbqzjbc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gtqninopyd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtyuqqrcbr.html

I. 正则表达式
来源：http://dali.iojbl.cn/Article/details/gtlggkemet.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtmnjtgjmd.html

[I01] 判断是否匹配
来源：http://dali.smart0.xyz/Article/details/gtayzmjpyp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtrwrzmzhq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtonzbhwds.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gtxyxgvdbf.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtlyworzss.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gtgcjawfag.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aizwys.cn/Article/details/gtlxumhpnf.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gthnagvrkp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtrjcmvhvv.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtfgnkvnig.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtghnssbbl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gtwopogkna.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yanxiufei.cn/Article/details/gtsiuuvldu.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gtjnfzeajv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gtazvycwzi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtgbouvepe.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtkmrpdobj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gtlblqdhqk.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gtxyzfirht.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gtdogwdorq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gtfdemduqd.html


<!-- 参考信息 -->