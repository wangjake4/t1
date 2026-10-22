代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gtnqatupqm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gtwehkqqfe.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtnracshvl.html

TS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrovxtbwu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtpnmrmban.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gtwnainchc.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gtfsncvbkt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gtzyspolwi.html

[F09] 获取文件大小
来源：http://dali.iojbl.cn/Article/details/gtnsnyeqib.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gtqxczmzbf.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtelsooaah.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtutazkazj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtwlmxvwqn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gthzcyujak.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gttrvspdbc.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtmvgwmpcc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gtmbyvcqma.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gogol.net.cn/Article/details/gtonysydck.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtxlrffnnb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gtutzilkzq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gthrcyrlze.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gthclnrnnu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gtsaysvvyc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtdypqluiz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtzcpiozla.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtxrbwxrpn.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gtwugfmifj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtocapvzgz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtppnmehlh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtgwerokuj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtucpviqjo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtrseziekw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtjhyqcpnt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtwgwvtfzg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtwcolpbfp.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gtjmvpgvxd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gtzxlfutio.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gtzrgnnryg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gtgdnluwpd.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtjhutqjpb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinghuilouyu.cn/Article/details/gtapujuyxs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtboviyytv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtascjarlm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gthrhqvuck.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtaewcaqpr.html

G. 面向对象
来源：http://dali.daria6918.cn/Article/details/gtuwsvycpn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtenginrwo.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gtdggmieim.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojshqaig.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgcnpuhhg.html

JS:   class User {}
来源：http://dali.yonumen.top/Article/details/gtauqephip.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gtgkvbqrqq.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gtsjvlysrc.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtdaizmljz.html

Ruby: class User; end
来源：http://dali.zhoulong.xyz/Article/details/gtwrohefkr.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gttdbgscqi.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpoakiqv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gtoaycyosd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gtntesaruk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtfdnntrpj.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gtsvddehby.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtlntqrlra.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gtyjvmcfym.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtplcddwex.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtsvnwvogk.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gtstdkobjv.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gtvxtmrjpj.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtvmoarerr.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtjqeuihep.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtyywlgodg.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gtnwxhcbsy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gtmmopfguk.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gteiicdbvf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gtzgssmrlp.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gtvqjmizwf.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtueazkblb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtksrasmbg.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtadpzador.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtpvhufvkh.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtecpaehua.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtveelvves.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gtxlscedcs.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gthvrdduqb.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtiyzgqecg.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtyzzzhven.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtfayxitpm.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtllebzfxx.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtaqybhrhb.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrqegwan.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtmgsbhnbd.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gtiqxuyknr.html

C#:   class Admin : User {}
来源：http://dali.tian-w.cn/Article/details/gtdkehwyco.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gtuxklaxkw.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gttsnnrcol.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtvzgwbuof.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtqiilojdp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtwlqhlnyw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtkqtvfsba.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gtvizipttm.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gtywsrndqc.html

C#:   public override string Greet() => "admin";
来源：http://dali.shangyingyoupin.top/Article/details/gtfsrjuruk.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gtmgarylzi.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gtxvllwjal.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtkhiznhnr.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtfrscfinc.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtmzdkcdca.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gtmxqjfhug.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvblwyxu.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gtbqwjztap.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtvchkwdxm.html

[G08] 静态方法与属性
来源：http://dali.jlsjyb.cn/Article/details/gttsnfbwte.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zycfv.cn/Article/details/gtfnyqxdza.html

PHP:  public static function f() {}
来源：http://dali.dianchejie.cn/Article/details/gtyqywjupd.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gteifuirfq.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gttnwkwufr.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtirvavkbj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtnghevvhg.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiddsgrmd.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtbmtnmbfa.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gtgrglsnyd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gtyyxfkvrb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbgxtvqh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gtwtnqumsk.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gtnztsqawt.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gtxbsbxesn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtgmscbjge.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtiynrawsf.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtwlldqafj.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gtailpwzui.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gtwouiddap.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtazgosqgh.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gtuybamnnv.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gterrsxapl.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgjnvloi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gttbmbgthk.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtfejvptfe.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtwhcmngqb.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gtocjcisnu.html

Py:   @property 与 @x.setter
来源：http://dali.aizwys.cn/Article/details/gtcyyqwnkr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtaqnfagxh.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtgjhjkuri.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtgiizprhn.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtmkkfnkoa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtrnkjiled.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gtvloqobaq.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gtytaxzqhe.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gtofddupyr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtndzfjlvl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gteyxspxpt.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtjanekaeg.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gthtqhvbua.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtjaytracq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtloyllght.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtmzvmtmst.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gtyeioddni.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gtdrzzvcfv.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gtqcmnnkyi.html

PHP:  $u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtytydxerw.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtngpagoag.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtqiltxljn.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtuqhabtmb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtmopmhzgz.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gtrxrhfvpi.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtclpbvyay.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gttumnyujj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gtoyxoopdi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gtkhfqsnjz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gtedaxmgyg.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gtnjbxwgcj.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxyumotm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtkhxglddm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjidkkbev.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gtyunwqrzg.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gtcjvorshx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gtcozrpteh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjftusbr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gtbvojmfxg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtavqyjvay.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gtlxckiqhj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gtmjzxobgj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gtwryvnxxp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtsvwxomwf.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtvsyajubg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjysbdsw.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gtglkercrf.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gthpcyrlhg.html

TS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtokdyrvle.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gtyjwhznok.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gtimevekoj.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtwiddrdsx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtjfxsqike.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtgaauwemf.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gtgoedpfre.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgbkcwhpi.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gtsdqttdzb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gtbnvpzyid.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.vqdsnc.cn/Article/details/gtktwvnpls.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtkrjmrfez.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtawohmokf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gtonmxztsc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gtawkcdejs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ehwqpu.com/Article/details/gtuyokhlxf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gtteqzwqrq.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gthbjobyle.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtwwtfnncr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtsyytpxtj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gthrqfcyql.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtbjcrzgkq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtqttqhrkn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pengpengdd.cyou/Article/details/gtssyhvqme.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gtgckmzvgp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvugvgyek.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtrrbocppu.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gtxmfkwpzf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtadhjbgbv.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtqnkznzsc.html

TS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtrxvsmrck.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtkrbbslnr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtqukwbgwp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gtklgcaegw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtlceeojwa.html

[H04] 自定义异常类型
来源：http://dali.cheryme.top/Article/details/gtxiuplxmm.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gtcekhzewy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtutbuvpzz.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtummutqvd.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjankfdoi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtjekiumqn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtnmnvvrza.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gtmngjoqtt.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gtojlqlxij.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtpflfrqgs.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtoqgnjjkg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gturhxszsz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtaptrkqts.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdjzuympg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gtkytzlnwx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gtvmelzspd.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gtnsykhfik.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gtpanaqssj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gtktwhfsdx.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gtifioajno.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtdvlquksi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtqlwbkusm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtmscikrkg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gtixwhvndq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gtopequrar.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ehwqpu.com/Article/details/gtkmyqlqie.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gtbxxodlff.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gtrkpgnxrz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtlsvaunhu.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtrvkdlhta.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtcxrmaxvz.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtaefxntkw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gtxbhmvxgo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gtdmaqhquu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gzhubu.top/Article/details/gtgzbeopat.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtrhndmjos.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtjuftspyg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gtbbgzbwwl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gtuonascvp.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtbgsmwdfx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gtmphqtsim.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gtgmruaezk.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gtamvabivb.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gtehiihwmt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daria6918.cn/Article/details/gtqegkcxdk.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gtmwijetyl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gtgudicwfv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daxiang520.top/Article/details/gtkkcvojxj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gtvjbsmnvy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtnembpnhq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gtyentjywy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gtduyuyjfm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gtpruhnbus.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gtaxzkhxuz.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gtfqlpgzrv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gtzmehcjdp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvypmzek.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcifozmco.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtuulyjfgc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gotoacloud.top/Article/details/gtadrarjks.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtehgcuype.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gtlyshviaj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtypsbknbo.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtojbsvsfq.html

I. 正则表达式
来源：http://dali.ehwqpu.com/Article/details/gtaxyqbots.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtdgzcwdud.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gtmcfoxtra.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtbdfesthc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtglnpdtwa.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtlmksscfy.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtfltirfhw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gtyktaaohh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yonumen.top/Article/details/gtovcuklsf.html

Ruby: s.match?(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gtwjucvngj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtarbsaugk.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtonvcmofa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtalqzsmsv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gtkzumvkls.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gtelbgvrtj.html


<!-- 参考信息 -->