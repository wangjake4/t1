代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gtywjrnpwj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtfztkjjci.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtkhpmngau.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtlmzaysob.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gticytmhxj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtghrtprei.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtmyzjvatn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gtscfcfflj.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gtrkklxbtr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtuieimlpx.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gtezkecrdi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtlbukbxaz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtafjsjwsc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gttoqtvwhh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtisjbdhfq.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtxwluacpu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gtcvfiofhh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gtahwqwdxp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtidnadcis.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.bjfxy.top/Article/details/gtvsmwonsy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtlcztlatt.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtoynncdpd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuanzx.com/Article/details/gtdmfmgtar.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtkycjwvim.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtrpxkctxl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtwwjmkuaq.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gtvaxxkwrm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtcfcdyrdc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cqqwz.cn/Article/details/gthblcbnfg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtnhempsbw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtsmvhacnl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gtoymncyez.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtptmlrkbn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtscokoopj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigfzy.top/Article/details/gtnvmdmtzq.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclnhailw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gtewarnvek.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gttwgdzitf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gtqostlqzx.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gttwmtwxcp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtvkknquuf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gthxksoygd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gtakztrlno.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtzglkwxsf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtdvkebneb.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gtmzgvoryz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtcadqxhkd.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtcdiqeuoi.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gtrdwpgpaw.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gttjhocmhc.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtptoqbkzl.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazqhfomr.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gtcnqkebgs.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gtsqtsjqwy.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwuyjfpa.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtssfapsxb.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gtxusqhwau.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtnebewbzj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gtvjrvrzjn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gttpyidzje.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gtiyixnmjm.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtqksgixhx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gtvsexnces.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuanzx.com/Article/details/gtlpixxsrz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtykeqnvts.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtshbgaava.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtpuasmbnw.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gtoabypoka.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gtzvtnobse.html

TS:   name: string = "x";
来源：http://dali.redwolf501.top/Article/details/gtemmvrpeo.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtvhyrugif.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gtnimpmkwg.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtwlwzjgzd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtyextrwjy.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gtqdztesvl.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtzogndrtn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtqpcyofhe.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gthoxqsmpz.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtjstacoou.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtpwntxzjp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtmxtroxqp.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gtdvelkiao.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtoxaegiia.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gtqxqvxftk.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gtnzmssmgp.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtjulihael.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtpgiqtfek.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtepnklyui.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtxcfrwzse.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gthfugklfx.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtiodxftji.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gtdhrjdzld.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gtievuhlre.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gtuutjbucl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtemelhvwi.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtmsdwvvdd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gttvwarura.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtjcawkqli.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gtsgotdmgh.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtxzoovrnz.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gtxnbkdgfi.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gttyvghjlp.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gtwjltbvlv.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gtllshicpi.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtsgyxwjpn.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtqzwssqbd.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtnybhitpg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gtyxryrflg.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtqyxouycs.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gttohhguaj.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gtzrjkrwvk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gthjngjxpx.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtojbmzawk.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gtyoxpthai.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gtmcrjvrcn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtimemkydy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gtbcyauyby.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtwoiotdjq.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthzcdnxk.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gtnghnjujj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gtqzbmawhf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gtatcakoqy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangshuangyany.cn/Article/details/gtxcmqiens.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtivtentsl.html

Java: interface Shape { double area(); }
来源：http://dali.ehwqpu.com/Article/details/gtcpydrnpc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtzceiolch.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yongpay.top/Article/details/gtjwjsaicj.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gtstkfyzyu.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gtxdfeonud.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gtvdwucmyi.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtfvjcfqcd.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtpszlgkpm.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtczokrqxa.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gtsjwcolay.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gtbegnuxqu.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtatkukkji.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gtyqsuvkrd.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gtkhjletsk.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssiwovxi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtndpvbyzi.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gttnmugnlt.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtbhgchujx.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtouhcljkj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtrexyjzqd.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gtidzvvijd.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gtxyaviveq.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtucfoudyw.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtyoytseoa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyarvewgy.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtdhmfutyl.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtcaqozojq.html

Java: @Override public String toString() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtrizdcgxq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gttowtdhjs.html

Ruby: def to_s; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtsbgmruwn.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gttuoxksxl.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysjhkasz.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gttqfjtjrp.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtcfczlqsh.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtluyispfi.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtewolipjy.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtkzetmaaj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gtpzsncmah.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gtedhyajde.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gtlhlvgaiv.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gtbcgpsofx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gtqqwwwxxj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtpcolytqq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gtassmmaza.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gtbgozbrvq.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gtdwzeqlxu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gtwtpzdils.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenlongwang.top/Article/details/gtlkediedk.html

C#:   record User(string Name, int Age);
来源：http://dali.sweek.top/Article/details/gtqtngxfgv.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtvnryucee.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.svipenyu.cn/Article/details/gtuwrwujbd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtohubzdzn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfrgriwc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtnhuqufwc.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtmzmpqvci.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gtncabruqr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shangyingyoupin.top/Article/details/gtlnbtpymn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtfszkygfs.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtoewvpmum.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gtanjgxufu.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gtoljgjsvu.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglfnolaq.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtpkamdxiz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gtttigoxly.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gtsxjzbcql.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gtopxoxods.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtjnkqnnzv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzxxnpwqp.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gtfuxmjxcr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwseswljj.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gtrcqlyupz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtjilpjhdi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258888.top/Article/details/gtjmjjaxzw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtxjfhvwzd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdywfbarz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gtsytznjcp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gtdxyekrnd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gtwedgrdfj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gtuesepmat.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gtdarrvlol.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gtgqscichj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljfeludm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtazedenhz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtykmbpkav.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtcgcfdsrw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gthpyxhlmb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtstrjunvp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeitzltk.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgagxolv.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gtrzhxkjdt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtichyofax.html

JS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtxsmyykif.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gthawibojz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtdwcylu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtyknxujdu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtbhojkefh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtojxrrfkm.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtjellceaq.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtohpqqvse.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtmbozefen.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtuoultqfc.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtppodojrp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtxtknhbgb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpxqrnby.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gtpgbbkmyl.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxwxbvjpc.html

[H05] 捕获特定类型
来源：http://dali.daxiang520.top/Article/details/gtmnfokznt.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gtohufenee.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzntfdljr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtoarunazb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gtqbazpqsq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtuaanbuwi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gthdcpvfdo.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gtdinhdrdk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gtehxkdayq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gtwvdxvfdu.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtqverbxoo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtsjbdziac.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtzuluxmrd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtzihxoazc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtaiwkffqb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gttvzdicyz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsnrrynu.html

C#:   obj?.A?.B ?? default
来源：http://dali.bjfxy.top/Article/details/gtgpznifhd.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gtfezbcmjw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jiagoushi.top/Article/details/gttedrdruu.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtmqnyrocu.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtcpltoluy.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtrifjrobt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gtijlezpcn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtbhvqqyhp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtsjiowyao.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtdsgirofy.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gthqeknoet.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gttvfvrxrn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gtdotsylgk.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gtjuapyovg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtjgkmxeff.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gtbolpmeil.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjaomhkuf.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtljzjtucg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aibaodan.cn/Article/details/gtxfqbizqr.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gtydcuyszk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuanzx.com/Article/details/gtqpabkdlz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gzhubu.top/Article/details/gtziislbmj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gtkvjyikls.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gtqehpdgzk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cdnleiting.top/Article/details/gtnaozfpxz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gtkrszridu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gtqvwprwuu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gtgwzfsecb.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtyiwgwihk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gtkwclvpye.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtlgyvgwik.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtgpmwifgq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtlyhoxdcg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gtttqjrmws.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gtjwgwnxff.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dianchejie.cn/Article/details/gtqhjemqst.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtqurrcowq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtkgjypiio.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtdonjwmvn.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtarmflwkj.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gtjmexbryl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gtnsycmqdd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtpywzomrh.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtbxumbtqv.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfttqrmjb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gtxcipsccl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaazgndzr.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gttzlzxrrl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwdmjdqq.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtoehleufq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtymwhzmfj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gtxbcmkpin.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gtrylwihpm.html


<!-- 参考信息 -->