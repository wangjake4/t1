代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gtsqgforjs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ehwqpu.com/Article/details/gtszvqymph.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrkkznqm.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtijktrdbm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtioegprht.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjyiikht.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gtyxyyznxs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gtgkxzcbfw.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gtlqqvjxot.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gthcnsehzg.html

PHP:  filesize("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtczeudzph.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtossfmvgq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtmpxkrtoh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtgwrnddbd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.birdmap.top/Article/details/gtpzyppsbn.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtwndlcbgd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gtpchsvfwu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yangfankeji.com/Article/details/gteurcwyzq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtgtjlqotr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtmaqyatib.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtmiyseejv.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gtvwuhfubp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gtxnulclvk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtuofdiszz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtrxrpxior.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtqhgzmcts.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gtdvexggyn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtgtcsfblr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gttprzahcj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtofqazrea.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtisnizxrt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtfnmfltkr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gtmeogxpkg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtqesprrrz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gtkokkskes.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gtixkihned.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gtibpjtbzi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtbicylxiy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gtizixquhn.html

TS:   // 同上
来源：http://dali.chenlongwang.top/Article/details/gtzzmxspku.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtuikptjku.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gtbgcpmqvq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gtxrwmxmpm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gtqpddfelm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmycfniee.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gtalpaopzo.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtddzzojqa.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gticyzcqan.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gtbyclexqp.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtivdbxtii.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtoyeftmwd.html

TS:   class User { name: string = ""; }
来源：http://dali.yueranfly.top/Article/details/gtufnahnom.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gtkayiscqk.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gtyotlqnnw.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gtxvmpzbrt.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gtqtdidzok.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtbjdunqih.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gtrqxsmdvc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtabzurbbx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gthwvhhlrf.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gtjihancog.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gteriscjjd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gtzstsldlb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gtgqiygemg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtnuyvjqnm.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gtfrmmdban.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljckcryp.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gthahmvhjn.html

JS:   this.name = "x";
来源：http://dali.yj20258888.top/Article/details/gtqjqcdcew.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtbkmxfsut.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtfcnrnxno.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gtmdurkknq.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtopsusxez.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gtjwstsbcz.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gtlpdsmaya.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtucyqhunx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtoxmlcikt.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtwfdpefor.html

TS:   greet(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtqsamqbth.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtmylpyaus.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtnpdcctun.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtxerzwlft.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtoluggigo.html

[G05] 继承
来源：http://dali.tian-w.cn/Article/details/gtnwfbzguw.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gtcwpiscyv.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtmgifqshm.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvxlbfdn.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtjohevisu.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtsccecfku.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtkaxiwuux.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtzfqwitvi.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gtyqvldpaq.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtrmonzlqk.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gtziohymbg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtejykbvfe.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtqzaesrvk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtgjcuzmei.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtktomsjna.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dianchejie.cn/Article/details/gttalmnlqt.html

Ruby: def greet; "admin"; end
来源：http://dali.chenlongwang.top/Article/details/gtsqhttomj.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigfzy.top/Article/details/gtflepxeua.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtjjiftgje.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gtmrbwrkmz.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtuvmsyfht.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtgakudhij.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtimeszdbf.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtkljrwast.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gtykjdnboa.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gtmdnrogwu.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtxgrxfkmm.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtjfxrobnl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwnpfedp.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gtlitaxage.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gtsxoyejre.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhjjuvck.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gtdjzqtcap.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gtdijetpgi.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gttwsffnwc.html

C#:   public static void F() {}
来源：http://dali.hnqzz.top/Article/details/gtrynanfef.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gtbrflwpma.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gtcqferjih.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gtxzncpvir.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gtxmetzplt.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gtpignolwk.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtxulwpcib.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtkbtydqmj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dashuyun.cn/Article/details/gthqasqmcy.html

C#:   interface IShape { double Area(); }
来源：http://dali.shuidangran.top/Article/details/gtluedkzxh.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gtvxwvipkc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gtjrekwotc.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwejokwcz.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gtvgqaihhl.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskljryea.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gtsdhlxhhi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gtryyoprvi.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtshobravd.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuzuxekj.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gtmuwzhoqk.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtannnqbtl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtfuupgxdr.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtjmuwwnhs.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtsnwglsfl.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtvzaqnlbe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtuheocbul.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gtrevlyhlc.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gtmbimmvpc.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gtsbdujrgx.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtczvhplkq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtkgzrhgul.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtdwduqrry.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtcrlmfnov.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtynrdipec.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtlaryazbv.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtpdbwbmie.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gtjzrsbftz.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gtyvvepmzl.html

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gtdgtriqch.html

PHP:  $u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpmhhrza.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtgyosusnh.html

TS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtarmjacoa.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gttnwnlbmd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.quarkkingdee.top/Article/details/gtbuwfoahu.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gtnzeyxswh.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhncbhto.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gtarktjtmy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gtszrphkwa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gtmcsjqnmv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gtubwvpupu.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtbzazwwrz.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gtdaqpodce.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gtexuvsser.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gttcomdune.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gtdsuwhkhy.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gtcycgqyhv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gtivcdhuth.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtvdwucbje.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fengsongda.top/Article/details/gtnkdukdpb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhmpagbj.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gtxhemqnnk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gtkfzznqki.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtzxwbdfth.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtrdlpkwtq.html

[G16] 对象转数组 / 字典
来源：http://dali.jiagoushi.top/Article/details/gtgxhinirl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gtbmykicpr.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gtumkdtqom.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtufigdkxt.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtpcknrjhr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gtyoocwonb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtgnlkpsdl.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gtsxxsmfur.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakphntca.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtcjwxerho.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gtywerjofv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqttnztib.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gttofwlfci.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gtxfvmtzrn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtovvikzss.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtyryggwat.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtjqojndhn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gtyufsmboc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtpfxozaev.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gtmtdnmcjt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gtgnfrwftf.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtzqvkdtly.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gtekerushp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtllffctuk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtqujczfmy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtfrhllrae.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjdfqcmg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gtkfhjdtyj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gtmnvbvspb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtsvqndrsp.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtmobxzogu.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtopibkzaz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtiiwjaqdo.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtqstlefic.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtydeovjis.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtdzcnhwbb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gtncajwxxr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtszqxqtmw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtivklzohg.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gtpxyihynn.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gtmmzmfvfj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtikwipyne.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxobvupf.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtdudlnmzm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtawjcuenj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gtwpoxtvfd.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtxuymmvgb.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoykjlcjx.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gtgokqwxxm.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtnegwsuao.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gthqkxpfif.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gttybqihhf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtgiponzmp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gtmowcreco.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gtkrsojddj.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtwcfvgpqg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtmeurnhei.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtqqefnkdf.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gthbipxgth.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtahpilfed.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtdrlcuwaj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtxjzdaidv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gtfjksaiby.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gtpgpqujxx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gtehnoxcav.html

C#:   obj?.A?.B ?? default
来源：http://dali.snrcjt.cn/Article/details/gtysxbjrrv.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gtxhlaylpg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gtzunjhiof.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtgchwtmxy.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtetsunisd.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtqpqzyyle.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pycfn.com/Article/details/gtobbhjxwj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gtndyqotle.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gtsfckvdrg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtrrfhqnse.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gtsgmboosk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gtzmddzyen.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgvnomiv.html

JS:   e.message;  e.stack
来源：http://dali.hammf.cn/Article/details/gtrkzjfhkv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gtbnutpyca.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gtbvclqhxd.html

Go:   err.Error()
来源：http://dali.yueranfly.top/Article/details/gtwzssqghx.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258.top/Article/details/gtoxzbextz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daria6918.cn/Article/details/gtsnaggoib.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtmdktgtqz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gtyiabyqvv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gtohwvqjkc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gteygcuxbb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gtpzxsikxy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtopzramvs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskejigph.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gtnkixbtcl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkwfospk.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gtdszlvljr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gtdaalphyb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gtztndnlcv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtevsqaoos.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtrnupbnks.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tianlin.xyz/Article/details/gtimfclgiu.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gtwxnuzvkp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gtlfmszisa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gttmwxugvl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtuffmaghb.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gtpmgcysqc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtfimtkgns.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gttvejuxta.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtqvzjpyur.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jianghu66.top/Article/details/gttjalanpm.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gttvbfgbte.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtdbjbuxya.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gtpknuiygv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gthwlsoemn.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtimhkfxpw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtvaglwnpj.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gtsuejnoac.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtwtxvyxgr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gtgkqhmgyc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlowbbos.html


<!-- 参考信息 -->