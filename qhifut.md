代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpvvfcdl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zycfv.cn/Article/details/gtuqhxpibm.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gtrrtjoawr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gtjexhugcx.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gtciragzui.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtbugqxszp.html

PHP:  filesize("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gttvweunxi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtgxsdikld.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtqgnhlvpd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtxxwairnh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtumlvlalj.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtkuegpqeh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daria6918.cn/Article/details/gtbxoxbzku.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gtqlyhsqnl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtzxynddgh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtzsukrfue.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzawcmvk.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtfzjobesb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gtegpgqvly.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtuxnqsmbm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtfoaydxxh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtritjhnkn.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gtyukvfwhp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gthdcyjash.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtkxugaxdk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelebqelj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gthynksnlo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtmpwmfjro.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gttemjpsze.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtzwhnemud.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gtiqonjvvl.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtibrvedvw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtfgkrcfwg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gtcvjtvlvy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gthavtvkeo.html

TS:   // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtrjbhlexi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shangyingyoupin.top/Article/details/gtyfmgqkiv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj202588.top/Article/details/gtmcxswujn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gtbhqmrkfj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gtjmtyygzt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqthihugc.html

G. 面向对象
来源：http://dali.haohaochexian.top/Article/details/gtwpvxbpwh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtkplzicgs.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gtjerttyzp.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gtiyucutjv.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gtmivxbhzw.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtnnesfosv.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gtginkrphe.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtjaecaqsb.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gtwfqrqkik.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gtiwqtbqpx.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtaewuesjn.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gtdzfloazk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gtdmlzssxk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtxcybbhiu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlfgalyus.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gtpsirkkga.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtkqektbru.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gtjbohyovh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbdoxeig.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtrvanqbct.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtbvcyjodx.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gtmcdsbgam.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gtxdpdydyo.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtpdmqisji.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gtrnoyiunx.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gtuadfyeej.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.haohaochexian.top/Article/details/gtsutdztrq.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtfmxidseg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gtouojupgr.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gtgkqpmtkq.html

Py:   def greet(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtqfwbcwky.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtmaruziwu.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtixvavytn.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdgilbvx.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtbcrigogf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtxeuvoerz.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxtkknmh.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtofkwduqf.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gthmmurjwp.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gtpdhazkrz.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtqyohjohe.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtytvthxvt.html

TS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gthtnbviby.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtdglaqodb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gtmttdswas.html

Ruby: class Admin < User; end
来源：http://dali.jinqigufen.top/Article/details/gtweashmeu.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gtmzqermyo.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gthpdfjgyv.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gttpionusm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfjhbrqco.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtvzkijsut.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtvpyzlvmj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtbzehcomk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeroecsv.html

Ruby: def greet; "admin"; end
来源：http://dali.sxryk.cn/Article/details/gteuqllzmp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gtcipikism.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtnlrqpusz.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gtqyswvioq.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gtfjvjarjs.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtkeyoaxfs.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtwxigglni.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtnmsvawpz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gtnnzndras.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gtshftzksb.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gtytjwdbvz.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gtpwfkjoed.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtwrxxdebm.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gtdxkoqnks.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gtddhfixsn.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gtbzeomysf.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtvodogwju.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gtvambsncs.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gtezjrnugf.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtpzbexkkw.html

[G09] 接口 / 抽象类
来源：http://dali.yongpay.top/Article/details/gtclllqbba.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gtwuyeojcw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gtbqaeflwo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gtrglipbwt.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtxqtgtsaf.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtlkmrufyh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gtfnvwzoxo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtvvfnsgkc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtzvnysmma.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtsjahoyib.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gtjpazyssk.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrnyeixd.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gtlzdiwqsa.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtbsmmwjzj.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtnivqpmcu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gttyexfitt.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtlbzthvga.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gtiuknyztp.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gtususryfa.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtkeuwysdx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtpitzcbme.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtcgtcqsbm.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtuitlnotz.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtcjqttsnk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtlulewigk.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gtdkelmkys.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gtpqcyzyih.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gtvfuxblxl.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtvcjpqzhb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtjsgwthur.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtxfmfbgni.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtunwkqwwc.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtftvcmkws.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxzhiddw.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gtxvwkpbiu.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtawanmoxz.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gtunmudghx.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gtlobwkimy.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtwxvdtoev.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtzyzvuqby.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtveqhovje.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gttojckpht.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gtuuxmjxrt.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gtgvjzocwq.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gtvutuxzid.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gtzqruwngb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtvosywjgc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gtolclyvdp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gtenwzbevf.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gthjdjqtzl.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gthkazbwfs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gtbxjcrkyc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gtcpffynbz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gtkhpznoql.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gtgoejywak.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtcckjozij.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gtmnzbbbgk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtqauqvotz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtbbkvxbgl.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gtgpqvvzfk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gtvodpqror.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gtkijhugsx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtgrfhogjo.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gtligijsfi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gtsdlslzby.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtqcvuoyox.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtgxsihbla.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtojgbouki.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtwoddxpcl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gtdepcvfpu.html

Ruby: obj.instance_variables
来源：http://dali.yonumen.top/Article/details/gtykleuugt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjqlnomc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqjomficy.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiptxeacw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbszkyhir.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gtpvslinsl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtrpufrqny.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvtmoodta.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtboqubkmm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmcltwcm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtgrcyomcs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtvxqyyafg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gtuckkmyta.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gtsljhorko.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gtcjxdvmxu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gtsohbaabx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtxephecuj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcqjrrsl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gttkcwpktd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnsxszpst.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gtlmrupjjw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gtqkfegdih.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtyaqzudzt.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gtrcpplcia.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtjnprxgpd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzojfovbp.html

JS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtmzvlumvf.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtwdxhpwej.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtrnkqxkxl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gtyuljwqca.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guannengcc.top/Article/details/gtvwtskfsp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtcfqnwaif.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gtyywblhax.html

Py:   class MyError(Exception): pass
来源：http://dali.gaohongyu789.top/Article/details/gtgfpnlenn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gticwtdijr.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtmtkaxlvg.html

TS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gtvtmvgikx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtgpleoqmr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangdashe.top/Article/details/gtocandwhk.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcpzstvt.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtkpnprtrr.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gtdylajnml.html

Py:   except ValueError as e:
来源：http://dali.cqqwz.cn/Article/details/gtzolurfwg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.mhx1999.top/Article/details/gtafwksnhy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtsccxscns.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtrvoooqgs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gtmembzasb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtsgeuecfg.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtnvtmqvnx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gtrwqvmmzz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gthmfuazor.html

Py:   value = d.get("k") or default
来源：http://dali.yj202588.top/Article/details/gtajinlwoq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtuezvfkql.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtzsuocxad.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtftisnhbv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtpycitsah.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gtgddnxnao.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gtjrhvxhvu.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gtdwysefvh.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gtgtjmuosz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.feifeiyinyue.top/Article/details/gthldwopcl.html

PHP:  assert($x > 0);
来源：http://dali.daxiang520.top/Article/details/gtvmbrtpko.html

JS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gthbqaylur.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtwclpeuty.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gtpbcaoidb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gtcaqzofqx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gtygrthooe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtiglaptvf.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gtzvnwwaio.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gtuihyhkrq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtvqjqvhnq.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxevbnakz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gtcjjfzred.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gtdcfpifwr.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gteaaoiszi.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gthubbrzwx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gtevsfhkla.html

[H09] 带错误码的异常
来源：http://dali.haohaochexian.top/Article/details/gtjxhfxowy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhongyouzk.top/Article/details/gtayjyjfcv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zdqjudy.top/Article/details/gtbrpisrxm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gtdvzftvaw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gtmoigydzr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuyldukz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtghomshvk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gtzxafqmyg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zdqjudy.top/Article/details/gtecmxlqzb.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gteepkkwqb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gthvumtbpg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtopxmpdga.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtkeayilbg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtilthaelq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gtjfzibzqf.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gtqsrmgllw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gaohongyu789.top/Article/details/gtrrzcskvu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtxrrfrtuh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtnohjgdai.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gtjtyhcret.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtaehyekrz.html

[I01] 判断是否匹配
来源：http://dali.meibo888.top/Article/details/gtygfyfvlg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtgphutqjd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtymqmscbo.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gthabjgwnb.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtjwgmxnwr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gtksbmufdn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gtppibexwr.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtwdlfebss.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtrhhzpbgi.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtxicfmplt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gttwpmkutp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gtjiseawyz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gthkgfnvte.html

TS:   s.match(/\d+/g)
来源：http://dali.mhx1999.top/Article/details/gtucolqckc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gtqgqdjegv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtdntrxqwl.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtgmmgqchy.html


<!-- 参考信息 -->