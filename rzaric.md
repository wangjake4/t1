代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gtckawfvte.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtxtnoeiku.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gtomzmifid.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gtzexvyizz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtpxovbvos.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuetiantiany.cn/Article/details/gtssqypkhu.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtjzwgfyrp.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtvjxlmlqn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtbnmnssrd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtsgkjywkc.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gtgvjhycbv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gtygxvrfcm.html

[F09] 获取文件大小
来源：http://dali.mhx1999.top/Article/details/gtulifxmvu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtilvvsjvz.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gtrizedwwa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtdlhwkdhq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtkondwdkn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtzmrmgsab.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtlwyoercl.html

Ruby: File.size("a.txt")
来源：http://dali.pycfn.com/Article/details/gtyiovzyri.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtkwacgouh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtsayiefrz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtetiearjp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gtquadpchs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtqtzbdpnx.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtddfnahmj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gtdfgquwvt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtzfvujvji.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtexryjqry.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtainxmyrd.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gtgctqncdt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzduthbqr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gtshwblefa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtwkhhkscl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtvjvelesc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gtejjkyezz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gtswwppilp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gttxkymtuh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtcaqzfcwu.html

[F12] CSV 读写
来源：http://dali.9152youxi.cn/Article/details/gtcpzhywcv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gtbrzbkrcl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gtuleixqjn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gtxskrcfxe.html

TS:   // 同上
来源：http://dali.sxryk.cn/Article/details/gttlfhzfyr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gtrqnbyovm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daria6918.cn/Article/details/gtsxkgvsfu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtdllsnhpy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gtbyefwhju.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtsgvkrpuz.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gtnyzpwutc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqfjwakcw.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gtrofsblyb.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtwjcylecj.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gtwpsfejbp.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtetmaqaxq.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gtlgjsjelm.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtltiwsdng.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtsltfvpcf.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gtdturweva.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtzmmftfvb.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gttheqjwbj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gtkrgigeie.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfqknimmf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gthbedotpk.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gttfnetrai.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtgsianysh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gtlkohnpji.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtxkjusqys.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtshsskakc.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gtysqvarje.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtbreineuq.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtqvifhmxe.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtuctcrxwu.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gtwaupdwrl.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtoaabdzjm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtzhdutdaw.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtnkbxmsjt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtxyhnevms.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gtxtlzucgc.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtvwnritas.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gthcqxgxjl.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtoyltlepi.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtkcbsvvru.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtihqdvaan.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtmbufoobx.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gtxltlvgiq.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gttjbggnao.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gtndhqisbp.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gtvhfslrph.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwqjjqybd.html

JS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtdjrgmvtj.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gttysvtbof.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfziujcra.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiyslpws.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtimuefikf.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gtxlfodolr.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gtvdynogxw.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gtulyczpua.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtryizskfk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfrnfzgjl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtfgvsvtya.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtlmjsscna.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtdywpfuck.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gtifofzrxj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbeqeeuzr.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtqgfzrnmp.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gtdvxnlbkd.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gtjyokqbmn.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtjdozentv.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtsdatmyab.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtzryamyjm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtvgxjeiqb.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtjeytthox.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gthviwzghr.html

[G08] 静态方法与属性
来源：http://dali.gaohongyu789.top/Article/details/gtznenmjsl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gtjvxuawlb.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gtdasxgzpl.html

JS:   static f() {}
来源：http://dali.tianlin.xyz/Article/details/gtihzamjuj.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gttjhbfmrz.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gtkflclfxi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtgtjmtwdv.html

Ruby: def self.f; end
来源：http://dali.chenjidiqi.icu/Article/details/gtlrbxhoyg.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gtnbfixljb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gtbiziqxxa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.svipenyu.cn/Article/details/gtdqiqwmdz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gtinyepozx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gthushundh.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gtmsotmakv.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gtosorzptu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtufdsygjo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtjjgccwke.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtwnlfgpgl.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtzmbkhnah.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gtgbxsgmix.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtkdyusicb.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gtcwzdvigt.html

TS:   public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtwldowrda.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gtcmbfodvm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtlchzfdpr.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtxwhjsmgx.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gtkcehcuey.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gthkelkfeg.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gtermbwftw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtjlkglhfc.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtcnepoxrk.html

TS:   get name(): string { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtxjqzlnyt.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtgsexlvsc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtsyeabgnh.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gtuerxmeio.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtcojiibsu.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtmjthpbxr.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyldgjlb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtnkaqvyhp.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtmohxolpa.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtmxfanodb.html

Java: @Override public String toString() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gthaqeexke.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtvauahbkm.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtcjjzjpll.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtmgraroyf.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gtyrlqvhqh.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjpwtszs.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtuvzoqxya.html

JS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gthubmoqbe.html

TS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtposxcwjp.html

Java: u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtzuarnvjp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gthgumhvuf.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gtywdwkpwt.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtbyyheyil.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gtxqadgkay.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtcuisadqa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gtxlmmvmxa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gtodbvehga.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtaqjrhpen.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtncqnmisa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gtyadcyfia.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtccajsmnr.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gttdltibre.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gtqzqwkxes.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtzooxlbja.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxlkfeoo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtavhkhcza.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtrngfrnvx.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtfmxzglsz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gtdessiyrd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtecncbnzw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtsjgeysof.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gtctljjgqj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gthtjqmsch.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtvetutoph.html

JS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gtlqaodmac.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtfwwxfcsz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.0kj1m.cn/Article/details/gtorehkhfr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrulvqbfw.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gtwsfzpwmx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtcgwetitb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtivvfqjzo.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtdpoxufti.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjryhsbs.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gtovbnkxke.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gthvtweuaf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gtummczoej.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtewwmecuw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtecboqura.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gtmullneao.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtfkysighh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jiagoushi.top/Article/details/gtzayptoob.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gtvnjouunt.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gtvoldphyn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gtowbshcwh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtucffaufi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtcdcpdtjk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtvcshcbvh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtttyulzvs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gtfusqkqec.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gtgaepkwmk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtftmdccnk.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gthceptesu.html

Py:   raise ValueError("错误信息")
来源：http://dali.shzxlz.cn/Article/details/gtwkpvgfpz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtqyxdothw.html

JS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gttbtydnro.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtfuctpjkr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtwwhouyos.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gtwqcxgpfg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cheryme.top/Article/details/gtjlnzfreo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtmndqcesf.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gtegxdakul.html

Py:   class MyError(Exception): pass
来源：http://dali.xziqi.cn/Article/details/gtdecivugr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtepkxdgiu.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtezzeqdcf.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtjbvanmwv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtjtllcnda.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gtzzadenio.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gtdcmgfkrf.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrzoqxkm.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gtegscxiev.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtecsrfyoq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gtvgpuzoav.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtasjrdnwp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gthegkwkke.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gtcmkfwznm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gtpufqahyx.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gtguliqauu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gtllblkhet.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gtemzhkdvj.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gtsfjdvhlc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtceuubwxd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtgeydueks.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtompyyktb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtynwqzuly.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxhfuxql.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gtvbzjqpci.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtriphgujh.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gtfkbqexeq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gtowwjgsua.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtxbwfujlm.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtaphwebix.html

TS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtczpzecln.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtqhykzkcx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtjvahgqwt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gtiazhntsp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtgyxbqipe.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhixingplan.top/Article/details/gtiqnwcbof.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnqzz.top/Article/details/gttqocolja.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jianghu66.top/Article/details/gtsephqltg.html

JS:   e.message;  e.stack
来源：http://dali.jqgfzy.top/Article/details/gtqfxgxazc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtydyxfyah.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gtjqqomybq.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gtljkkuiee.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gtpqydoedf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gtzlcxjjwc.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gtowxhguzi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hongshengwenyu.top/Article/details/gtqmqubdai.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gtfwbyksvs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gtdhxqlfmj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gtforofezy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqwxyvrs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gthuffjhrm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtheomgdiw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gtygrsmfjw.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gtgylguusi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aizwys.cn/Article/details/gtvclbtwsb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtamcpthbq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtnruvdtrx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtskqzrnny.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gthgrxwpqz.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtkhxmrtxd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gtzcfltfbk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.bjfxy.top/Article/details/gthlpukdjw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtboupxwcj.html

I. 正则表达式
来源：http://dali.vqdsnc.cn/Article/details/gtodsvvsyi.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtzqqqmssm.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gtjddunhqb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtaydmimqz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtkygdtqoo.html

JS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvjgltge.html

TS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gthylgqjkc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gtybpmjtuy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gtvprioerz.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtxssdmkbe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtkqpynchn.html


<!-- 参考信息 -->