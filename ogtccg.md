代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtkiwhnwdn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtojieuxqd.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtvnhfhmax.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xziqi.cn/Article/details/gtswfohqfg.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnapuyfgp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtbkuwnecy.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtrqwhewun.html

JS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtvlofkfoy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtcbrpuunt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtbhpccoxp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtpstxyjfj.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtixzrmmvh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.meibo888.top/Article/details/gtcyrmrekk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daxiang520.top/Article/details/gtoqayhufy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtegqfkcli.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hammf.cn/Article/details/gtkiormueb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtmegnixnn.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtxcxcljus.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gtlyulmadi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfibbsvdy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtczttdhws.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqxqqtbms.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gtlmwqmvdo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtmrclrekm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtnjfaywyv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwoavtcko.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtqdmbdrgz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtaabsdzwx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gtatqmtxzb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gthjxjmsxh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gtikuzsaat.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gtqmysvwrc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gtjicfvatd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gtylctjvwn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gtrzrosffd.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gtllljnpgy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtmidbadcr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtixvwilmr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cucudq.cn/Article/details/gtvmjzlbcf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gtdykcoeyb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtpwbbrgrh.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gtvkvozley.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkawcisbg.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gtrvvaknlz.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gtxqpchqxq.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gtnrfphkak.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gtycyzffll.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gtxowojwbi.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gtyxbyucff.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtabvyfiws.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gtgoyhcvnh.html

C#:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtoagyknjo.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gtzuipfuua.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gtjevplwdv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gtxzwjazcx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtgftpbzes.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtunijvxxd.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtkvjdecov.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtcltskedm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gtxdhamwas.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbtnvphik.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gtuvonsymv.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gtlftnpxid.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtuuipfili.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfjxfoim.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcrhzqyc.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gttxlqqmmm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtgvwiorkd.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gtpeplqbwd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gtddksomsf.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gtzdakxbtj.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtsjylhyvf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtpqoeplyi.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtjyshmvey.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtbrrsglsl.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gttkgsybej.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtrhbqsjry.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtusxawkkd.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gtzfnszmmg.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtqrtdnyum.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfeficqbx.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtilrhbkel.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbrllezjk.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtcnjdpyml.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtermqqghb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gtpvvuatuy.html

Ruby: class Admin < User; end
来源：http://dali.jqgufenzy.top/Article/details/gtdrrcrnyz.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gtowdjsbgq.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gtftucdnmc.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gttmufihgm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtsbcrzkva.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxaktankr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtaumebtbq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjuljvrin.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jlsjyb.cn/Article/details/gtynwpeino.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gtynyixlpf.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gtslyflott.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtxtemwnmk.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtlracfjyv.html

PHP:  parent::greet();
来源：http://dali.316326.xyz/Article/details/gtyqicjewy.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gtyofehpyf.html

TS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtrxpduere.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gteywnrtbz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtjmqpghvf.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gtguvnmsjt.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gttgoiglat.html

[G08] 静态方法与属性
来源：http://dali.xziqi.cn/Article/details/gttcjwuuul.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gtqqsscuoe.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gtvvhqqsqi.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gtmdxvtcky.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gtuquzutgs.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gtfhhdmbhm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gtxnnaeldr.html

Ruby: def self.f; end
来源：http://dali.cashguo.top/Article/details/gttzxagemq.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gtaibzpdpq.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gtvwnzjvtl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtqfvwxyct.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gtvmekagdq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtknkzpzfe.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gtlscfqonn.html

Java: interface Shape { double area(); }
来源：http://dali.iojbl.cn/Article/details/gtfzynueac.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtrrogvogj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gtrcefarhn.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtpvwnsvob.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfdpgpwx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gtldosyype.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gthfwudzpu.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gtgegpgeir.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtfhqwrtde.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gtctejnoyh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtjnkvkrbl.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtohaenxlu.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gtzviagjax.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gtixswjimw.html

Py:   @property 与 @x.setter
来源：http://dali.0kj1m.cn/Article/details/gtxyrtszqi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtvuhfhkni.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfviqcvyz.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtowrupqyf.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gtoqkqpbox.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtlmyxwavm.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtughqgnza.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gtxsnrhodm.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtwehxyrjg.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gthtbpzwmt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtmszouqcd.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtwutriugu.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtzsjgjqdl.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtgsfdolwt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtwgjvynul.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gtkieqxvjs.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gtwztcqmaj.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gtqcwxmqcg.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxilfdpo.html

PHP:  $u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtplsjcqiv.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtyhetgrio.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtlbbvfggm.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtcepuzvzz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gtzmqtgwlg.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gtcssdhezb.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtowxpokce.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gtwjrifqoy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtcddnvbbn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gtipkjscih.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gtlumbifca.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gtnqmmnifg.html

Java: record User(String name, int age) {}
来源：http://dali.dashuyun.cn/Article/details/gttqljxijk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gtwhnrigdc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gtdrbzjwcw.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gtzgntsrid.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gtsjkgikht.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aizwys.cn/Article/details/gtnueohusc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gtrfdiuwoi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtdazqlffu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtvprcpzak.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtrsusubdm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtigddnvgl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gtdatvygsc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtlsxbzwhf.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtqzgwitxy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gtyycrltzy.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtwullmlna.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtccrycoic.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtwffewbpk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gtmwmmtxgq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gtxdcucxhz.html

Ruby: obj.instance_variables
来源：http://dali.jinqigufen.top/Article/details/gtozyuqdnb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtmssisoae.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtackapajn.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gtqdrnaksd.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdsrwfvkq.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjixgwoq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gtfzxresdg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gtvdbkuerh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvbucqrd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gttdrsedlo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gtzwcojpem.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gtwmryiape.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtecsvzhta.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnlpzfew.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gthjitfceo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gtjuudyeya.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtivosmhhj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtptdshiow.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtjtobfpeu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtrffsqgkw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gtwxuskgbm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gtkrarghkm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtglymjudi.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gtgmafxnoy.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gtddrevvfd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtonmutxxo.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtvejukszj.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdxgeedk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtvhtjaiaf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gtrlcegtze.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gtwvhchvnf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtoefdjysp.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gtneuaqekm.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gtwvemlqrs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gthclsaaae.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtvkbedeik.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtlviadfnq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtonbspljw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gtnpnektgu.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gtaqvrvrng.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gtazjhehxn.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gtysydbtwi.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtahpgkwph.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gtvssegenj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtjmhldzre.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtengchhje.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258888.top/Article/details/gtnuhrszqj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gtxuuxprad.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gtrtwvjmwa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtaaodljye.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gthinpaogf.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtwlwccicu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtgygetwyl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtcbbbyqwg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtbfwkkanb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gtmjiflnjn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuglomuag.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gtntaazhqm.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtjjerbwrg.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gtfgvptlqb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gtcsiehxzp.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooltmibe.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtszdbefhi.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtddmljmvx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gtwhucoifa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gtwninjosr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtvoobdiop.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbwauona.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gtaworspve.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gttaamgdml.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gtqiqemron.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gttjjxxvmk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gtlrrginrz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gttxqrtapc.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gtmxynuxws.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gtviaduboy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvdtdfoe.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gtxklkszfk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gtplnyfvwt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gtzjxpyovd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gtbcdrmuku.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gtjyejasns.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtrhotqtbx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gtcpqvcggr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtfpncbulh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtjzihpqnq.html

[H10] 资源自动释放
来源：http://dali.hnxiangtu.top/Article/details/gtevffllvl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtooobxkiz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gtbeekasvr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtyrildauu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtundmczpz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gtyvwogbct.html

Go:   defer f.Close()
来源：http://dali.sweek.top/Article/details/gtaddhvgoo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yueranfly.top/Article/details/gtsrcujkju.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtreqyscsd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqnyaqbzw.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gtcneyvdex.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtfvjuwlfy.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gtvxdvleys.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtlhfnpoig.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtrhnolbns.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtkybrqoes.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtwgmvzvnl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.vqdsnc.cn/Article/details/gtsutfutfd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gtzroyezuv.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtjiregcrf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gtsugpwpmv.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gtiqefpwuq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtdlhmrelw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxuanxn.top/Article/details/gtcypvsuig.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzzytunf.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gtkqksaxkh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtuunxlhkj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zycfv.cn/Article/details/gturwudotk.html

Ruby: s.scan(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtqkyhwsrt.html


<!-- 参考信息 -->