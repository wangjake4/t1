代发 wailian999

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtduidfbgp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtiubuiznn.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtgonfulzj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtzekbzsse.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtmjixlkak.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtzmudrhod.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ppjwa.cn/Article/details/gtnvtrueuk.html

Ruby: File.size("a.txt")
来源：http://dali.daxiang520.top/Article/details/gthwilbway.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gtkknzvptq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gtatjtymzm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtjpaupepl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gtgwjjgrja.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtoypochgz.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqqakudas.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hywenlv.cn/Article/details/gtpgyadzyd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtgxrpuzbr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtmenyinpp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gttcnoeazb.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gtzwxbmkkp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnqospyss.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtuokjvkaf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtaejlmdok.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtbpdnphgn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtzdylktql.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gtgxqwgemn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtcyhbkalh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtkkykspwy.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gtwidrzzsd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gtipoixysr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gtlvsbjdvr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtmmszdxbd.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gtrmocxjbx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxrfeovn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtoxszbdnq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gtbeddtnpu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtdryaoslj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtaudapsie.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvepozjv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtaykqpflp.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtpathsemf.html

Py:   class User: pass
来源：http://dali.guannengcc.top/Article/details/gtzrzavkdz.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtcwmbtwnu.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtasjcprxh.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gtexmgzbes.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtxcjqucya.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gtmluhsyax.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gtpvdcdfpr.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtbpstbuct.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gtvlmpquto.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtdvhzjhno.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gtfohpcdym.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtvviprtfi.html

TS:   constructor(public name: string) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtiadpwofl.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtorcrdreb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gtkyaaupbn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gtjkhwtgcx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjqgxkhj.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gtudrkrqfh.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtjxekxsxi.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtkhnlmtps.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gtglfoycnx.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gtwrlkxteo.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gttjrgahkf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.mhx1999.top/Article/details/gtffitwobz.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtbovnduah.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gtnunkbhsn.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtkwwlsiin.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtumpszhnz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtijmsldco.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtilnhntbf.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gttdinhajx.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gttrqynixb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtqvcfcoxa.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtgtiomctc.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtixpiuvoz.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gtzqjxygnh.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtyfckuhjj.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtyibyujsq.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtoffwngun.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gttxkumnlg.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzpbrggb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gtzvlmvccm.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gtwoxhstdm.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmnfpuibj.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gtbmoadtou.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gteppslwnd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gttusyfalz.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtvaqamjnf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtriqbecnu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtuykyccys.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dianchejie.cn/Article/details/gttuvtfcmh.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtbwqxdhas.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gtyafduefn.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gtjlkkjprx.html

Py:   super().greet()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmthkfed.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvojhnhv.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtekeyruma.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtykkzehnl.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gttfxurfvn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtcevxtvkr.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gtlhwyrbld.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gteeaqazin.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtchptdrrf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gtyyouqyqj.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gtftlernwk.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gtiiyldxrw.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gtotapxhko.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtyowgfhzt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvtafisj.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gtxrxbsmea.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtafnbhwpl.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gtypcuylrl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gtxomubpbf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gtbmmlmohj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gthzpvjvea.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gtebsulqil.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpymhycz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtgyzdsenw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gtgckagjbb.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gtiwtgeand.html

[G10] 访问控制
来源：http://dali.smart0.xyz/Article/details/gtbfsyjbdx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gtredrthun.html

PHP:  public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtarzgsvge.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gtbbywobxb.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtewzywhqj.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gtnpapifig.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gtiomybiyf.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtvmydzjwx.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrqdahsf.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtvavoyzsu.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtxciiorox.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtppqdhqch.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtpygsioll.html

TS:   get name(): string { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmnberbs.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gthtnklnat.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeolptdl.html

Ruby: attr_accessor :name
来源：http://dali.jinyuanbaomall.cn/Article/details/gteemswxjg.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gtkbouohgy.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gtbnujwksg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtyjawjdgs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfjsitrbg.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvkyymnz.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtjscmwugu.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgkqlljgn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtpuepyyus.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtiuiomtoh.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gtllrqpeaq.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gtibnyvihm.html

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gtuynzdzml.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gthdzwqsvd.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewqesrri.html

TS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypipdjik.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtnsjlhifb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gtqntkdzyi.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gtswkbzkrg.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtpglftrjz.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gtnnpqrppb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gtwmyfcpkw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gtgzlmsnjy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gtwrayhscy.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gtfutlwpug.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gtngbnkhbh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gtwshxcpov.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gtctdttdkg.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gthwdaeonv.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gtlezssmgb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gtqpjncnbr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gthgddnsst.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gtucnwozex.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtketqchnw.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxuanxn.top/Article/details/gtswqjynud.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gtwkhdomqw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gtpunlwsis.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezrxfpki.html

[G16] 对象转数组 / 字典
来源：http://dali.fengsongda.top/Article/details/gtvogcydfh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gthitxjycf.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gtoywhqvmr.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtkuinorli.html

TS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtkyariwae.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gtbjrpwoyb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gtrydbvear.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gteosnmvpe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtvncexmru.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzypomrhs.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtwqmmotos.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwsuxbkx.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gtufzohekg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gtqpzrunjb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtoublhjap.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gthbmndnwn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtmasrkltk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gtjamkdenj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gtlooakxmz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtumvzfwco.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtrwznwhgx.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gtfqiotjka.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gtsgwdrgdp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtfjqekpcg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtlqhxqqrf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvfbaeqs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtmspyywej.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.havefunace.top/Article/details/gtuwthwlqi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gtdrshyjsc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gttlhqfvrb.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrroqdjc.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtiotrbfhy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gttpqhbnsa.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gthcdwjspd.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtkczvpfgy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtknbrxspq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xinyue.icu/Article/details/gtdrlcayhn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtjneigeat.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtdtbmxwgx.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtcbgflqss.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gtofqycyss.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjolhajz.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtumqpmmjs.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gttjxsxclb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtbkabvxyt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gtsddgfjvz.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gtqzjpalcx.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gtopusdhbq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtnnqmlqml.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtlffbcwqj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gtpmkpqqrp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtjjftpjqs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtlcywzupd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gtftaiunuo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtrhllhaml.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gtbcenghef.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gtcfmfphvf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywgtnfso.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gtlzngtmck.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtztcnvxml.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtcrxulmqe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtfsugromc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gtflpjccns.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gtyvpvmsam.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gtinfoalnz.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtqpvedjyj.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gtzyfmlotg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gtgznrdwod.html

PHP:  assert($x > 0);
来源：http://dali.sysykeji.top/Article/details/gtlfcpiqil.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtwrlloazs.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtzzhydnfz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtcoxulsqo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gogol.net.cn/Article/details/gtzxrjmwik.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gtgfabjecb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtnfpcqorm.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gtotxqtwtr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gtoaunfnui.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sweek.top/Article/details/gtzdouvmta.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gttbmxqryu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gtxpkjdjcf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gteidrueig.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gthdlbzgit.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gtrjiskikl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtoliimzdq.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gtilakgobe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtwmecrjqe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gtqgexyyvu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtritsddth.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sufxvd.cn/Article/details/gtjduqxiqm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvvsejdx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtcmbmreqo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gtabirczya.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gteimmsbgj.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gtuwtybdjr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gtyltvzdeb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gttyfsqlrl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtmhuafbci.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtmcfztjsb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gtaxfwibkq.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gtgbhbyceb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj202588.top/Article/details/gtebpufxki.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtgecadesz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzqcouogd.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gtnwvbucyi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtawspmqdo.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gtqvttkhes.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtezvryoxh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtmsqzpmof.html

JS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfpiqmal.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtfqtvalur.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gtvcpelusk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gtheczqypv.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjtzqpno.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gtrjbelxqr.html

[I02] 提取所有匹配
来源：http://dali.fengsongda.top/Article/details/gtswumorsv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtooxbwfhs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gtpjofxccr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nwbrower.top/Article/details/gtlxledpul.html

TS:   s.match(/\d+/g)
来源：http://dali.yanxiufei.cn/Article/details/gtehyzjbfh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ydzc1.top/Article/details/gtdxpdxnlf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gteraykous.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtjjrpndkr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gtnaytecam.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gtxmmnbrzm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gtsfrsrbfw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gtksqokvva.html


<!-- 参考信息 -->