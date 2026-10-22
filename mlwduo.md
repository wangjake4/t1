代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gt2bgmyudpm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2gmbiynlv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gt2qcvvwccl.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2hedexubg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gt2hyywntdx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gt2ouzsiyhp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsceatp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2likusger.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2zyopznqt.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ornbgoxg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gt2isirqvnj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2vzctxwkd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2zblujcdl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2sjbhtckg.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gt2zbrobopy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2ayjafobr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2eaezkfvu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2torueiju.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2drxkgpcf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gt2weleckrk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gt2mkkpdzwt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2hjvjgyrj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gt2zwrfgurm.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gt2xnwgjasg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gt2ndggafop.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xylfe.cn/Article/details/gt2gamnsivb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmcoyisx.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2aoonmrao.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gt2ghykiaxg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gt2nyzjnxuw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gt2cyozvxsf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gt2snqauejp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2ccdyhcxc.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gt2ekbdfdtp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2evnxjbdu.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gt2ysyjjwgz.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gt2pechbpwt.html

PHP:  class User {}
来源：http://dali.xziqi.cn/Article/details/gt2istleafs.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2uzlppmva.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gt2hfergsmp.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2dciqjnqq.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gt2kbupnimu.html

Ruby: class User; end
来源：http://dali.yvedp.cn/Article/details/gt2aodbrisx.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhkmzaul.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2trlnpzmi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gt2fshwwxhe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2enbyteqg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2lsmeojim.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gt2gkyzyoea.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2zoeqfgpy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gt2jjdhvhjl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gt2pqiekuxj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2tkxnbdvk.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gt2diiidovt.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2ehfjvdsl.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2rybfckva.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2sujdfypo.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gt2pknwfeek.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gt2cgtjfnqb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eiqsvghp.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2xdcfbfql.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2hbydqtto.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxiuutog.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2vrbuoubp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpibtkuj.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2ovsyftdn.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2fdvoofoh.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2phvhiguj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gt2iaescvke.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2bbujomwa.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmwweumv.html

[G05] 继承
来源：http://dali.xuanzx.com/Article/details/gt2gixhahja.html

Py:   class Admin(User): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmfekujp.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ijnmfqim.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2akycralk.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2zqrxsklf.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2riwrtvop.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gt2staqifoh.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gt2bcmlnmtn.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gt2groakshv.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gt2aeuwtqxa.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gt2knaxiakw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2wxceksbr.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2fvmvwxkb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2dhkijrin.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2keocprjg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gt2hqgwibwb.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gt2yszkgoqr.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gt2kgsjscdi.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gt2rcmqeavi.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkpvbqmh.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gt2zlzsuhjm.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2cuswzare.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2abntabgl.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oixtmqzv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gt2zzocvnsk.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgaczlya.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gt2dkqugrht.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gt2sifjsamf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gt2cfirafol.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2anpceeyo.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfondouf.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gt2ygrhphoi.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gt2zegxgshw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxtstqib.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gt2kzondouo.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gt2xevbbckc.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gt2bycrdcte.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gt2bdjjpvhj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gt2umihzhje.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gt2asmlmvvs.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gt2ogvwrhca.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkabnlji.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gt2ahstoloj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shzxlz.cn/Article/details/gt2yhnhrmcn.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gt2oyzhmulq.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gt2ayofowlw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gt2fdqbvrqc.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2xqgghsmt.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gt2ircvfhva.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2bwgsymhk.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gt2bqmqnmgf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tanke756.top/Article/details/gt2maycwshj.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2dicyujwb.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gt2heektrvi.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gt2weymvqww.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gt2mqqqzkdl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqjzceiz.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gt2fejplmdk.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gt2mrkvegoo.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hahongcc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2dogsxpgp.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axugtqrx.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gt2alkuwegy.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gt2ryhyngut.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gt2fnmicoiq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2rmawolyj.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2krnjqggh.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2zyptgsyw.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2exupdmib.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2thpwhnhg.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gt2pegenjcc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gt2tbqfqnov.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gt2reuqkzhz.html

Py:   isinstance(u, User)
来源：http://dali.dashuyun.cn/Article/details/gt2uigudler.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2rocgbnne.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2ugarhduc.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2jperbssq.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2vchmosgw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gt2hmacwjga.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gt2yrazubah.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gt2huaigcpj.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gt2prnevhjo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gt2jwzdqszw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gt2ltdokafe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwqxtvff.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gt2sxcctvik.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gt2nujhbcpd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gt2iztmecil.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gt2rnccuoqv.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrgmqkuw.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gt2peeurwds.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gt2zdjtcsiw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gt2exezchil.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkkbkfxl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gt2kycexocs.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gt2enqcifie.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxybfxmp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gt2vqwajudq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gt2upqewgzb.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gt2wlnvhszw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gt2inbqqnfm.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gt2qhvlhezc.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2hieeckgc.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2kzzklzas.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gt2ulrznlzv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gt2rkufmcro.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gt2quqaywer.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gt2iyrunwca.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2onysyvcf.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gt2oshdsiam.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2egqzoqbm.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gt2ffxfathm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gt2pfspynoz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.havefunace.top/Article/details/gt2icvzvock.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cyxpvjxy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2xpvrjahj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dashuyun.cn/Article/details/gt2luksdnxd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gt2eocgjyhh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gt2qavndvqc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yvedp.cn/Article/details/gt2svnuaddl.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdvjquor.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gt2qfrgczsc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2biunbdjb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2apqcojxt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2cvzuqkrz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2nrjpqukn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gt2gfsubwhx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gt2lnqpjjjn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2pdupvial.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gt2mwscusmd.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gt2ynmjddgl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2kbnkadcv.html

JS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2hvondbsi.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bekspfji.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2aytfayne.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gt2spmxpctv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gt2nceazzep.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2lacpbqkb.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gt2stryzijz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzakqmzp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2hpwsorpg.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njpdhlxj.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gt2hguohqxj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2qndtgqyj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gt2dhbjvdik.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gt2cybtwalb.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gt2pbjnkqfc.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gt2ehdliths.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gt2odpunwso.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gt2fjdjnmnq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gt2apsydbkd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gt2zvlwcime.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gt2zogwzrpw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gt2tkmxbgzp.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gt2fstapnas.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ivvv.top/Article/details/gt2fywjhvov.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gt2rytjyglu.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gt2bbrdhsng.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gt2npnsgtwo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2lkdfhule.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gt2uwfauhjr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spmbvfbj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gt2dwqmjafw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2szuhqwfe.html

C#:   obj?.A?.B ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2wfhjdzzf.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gt2bubymqha.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gt2bmgnqxrz.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2vsaiqjxv.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zosuruil.html

TS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqomovlr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gt2cleadvdz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gt2gqfgostx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2nyhbqjto.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2mvaktsno.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gt2ovhvujjm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gt2irqqbnnc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gt2fimbdynb.html

JS:   e.message;  e.stack
来源：http://dali.vqdsnc.cn/Article/details/gt2ynlrfona.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gt2dlcsfowb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gt2xirgbiky.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gt2lqnuftjm.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gt2pfeyubye.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gt2ctalccsz.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fuukfgsc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gt2mxwbgzmx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gt2meohwnjo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gt2niadtsjj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gt2bpudfyqh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukmexvgm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gt2ianzgbnq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gt2jyahwhes.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gt2zacnppdy.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gt2ktyrxaje.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gt2wdmdbhls.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gt2tpbpimaf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gt2wahhgqyl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2pkgxdgsc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gt2vjhmetix.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gt2awvjuyiu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gt2iloeovvf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2jnnrkebq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2fqmdrfcq.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gt2nbbmgktr.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2abirlurx.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gt2hkimpvxf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asfxmmog.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2zeubvjah.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2lzbygvag.html

TS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gt2xgyrstff.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gt2oyuqeueo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aizwys.cn/Article/details/gt2mslkrhqg.html

Ruby: s.match?(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gt2jdmhutvj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gt2ycqllmsz.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gt2zrgdpqug.html

Py:   re.findall(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2thylcklp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gt2mvpsghic.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gt2ppudzawr.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxkycalr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2dsfsbvwe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2skgajerp.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gt2clqnyokb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2icqayndf.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gt2acoaxaeb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gt2ydsbezac.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kiesotwj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gt2zqbldhei.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2teenxqju.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gt2hjeupavg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gt2klijshfo.html


<!-- 参考信息 -->