代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gt2yijikpit.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gt2luakfcnp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gt2tzdpaqnl.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gt2wuovqftu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gt2fmoudapf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sysykeji.top/Article/details/gt2jlvpubyx.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2rverdxsd.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncgwhyex.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gt2rqzfuobu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2soskhihg.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2siynywvs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2bbcmfebk.html

[F09] 获取文件大小
来源：http://dali.chenzaomai.com/Article/details/gt2gcsotgqw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2bzbscssy.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2swlyakpy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gt2qmzuzljx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gt2ahvnhnoe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2aybfqqth.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gt2xjpjnurj.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2grlachtl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgsmlcfk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ppjwa.cn/Article/details/gt2jifboufy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2xyowanmk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2tthretor.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2wqaipkiq.html

TS:   path.extname("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2wmfzgjyy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gt2izualjjn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2vvntsfql.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2npgzavgx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2hvksoklq.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gt2pyrbmisq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2jslorlrt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2dztmetjv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2ywdpxwvl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phimljzx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zycfv.cn/Article/details/gt2ufnyqsik.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqkcvkgq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2zfrdozco.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gt2tfljijvn.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmpsurpq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.9152youxi.cn/Article/details/gt2qbvanwow.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zynmzskj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2tiiqlgno.html

TS:   // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gt2gsnhrgfo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gt2svnsksbz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gt2pfkarxzs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gt2mstquqgb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gt2kqxywgur.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2tgfvxerk.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gt2ichavtvo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2rovrfxgs.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysrinwoh.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gt2pazgfdcn.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ayxvqsxs.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2ufauebse.html

TS:   class User { name: string = ""; }
来源：http://dali.bjfxy.top/Article/details/gt2hfdteqxz.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2tsbbhgsi.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gt2okbhhpyv.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gt2deykqkkx.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gt2magnnqts.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2bmhtdcuq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gt2agklypzg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrbngncl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gt2lvfvbzjd.html

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gt2lpvbdqdc.html

Java: User(String name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2mzprotwv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gt2xqeqzudd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2duqyfcrl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gt2yzgobvnl.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyjqprwl.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gt2kjwruykc.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2shkozavf.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2qusmpfoe.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gt2qodwmfdd.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gt2pztgtkkd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gt2bxtmajqt.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gt2fmprikue.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gt2uzjqzmox.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gt2zlvpokfk.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gt2kdawaack.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2jsfxsgau.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2fcylqfhn.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2rkptrwcy.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2vpnpdfkm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2ecnqkwrm.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gt2iuzohjha.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gt2ktkulvon.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbfdjrpk.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2azgfrxhy.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2mmkzecsd.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2jmlfbuus.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2hwulanyn.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2yeotjqmw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tanke756.top/Article/details/gt2usobzcmy.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gt2wyztrswl.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gt2houyljjb.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gt2qldwdwbq.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gt2opgozdac.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2uqbvyxqp.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2gyixqzib.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvhtgisu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2cmzqhbmi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gt2bsjevdcp.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gt2tqxusqpy.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gt2veaizzrq.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gt2cyvpoxll.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gt2warmxpei.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2tawfjgui.html

JS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2czesslls.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2oclzzxuv.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gt2qwboalbd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gt2pwlqawjm.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gt2euhntiyx.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gt2crzmiyko.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxqphegp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtihlur.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gt2fdtbwnxf.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2lychcsir.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkumwiod.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npsolqxm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gt2bnatnvyt.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gt2lbblrims.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gt2ymthlubg.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gt2vsqxqyhv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.svipenyu.cn/Article/details/gt2nygkbzlr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gt2gspvbgrq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gt2tiqvegti.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gt2lyikecfd.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jivfuzhg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gt2kvjuanoe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gt2atmtewpn.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2jdmuzlbp.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gt2omakkkpx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gt2objojtcr.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2grzlkgcz.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gt2dbxwlhpv.html

TS:   public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2zpwbfkjv.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gt2sntuewzw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gt2wmqtkgdv.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2fidmblvg.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gt2kntdzbgu.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gt2henkbgsw.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gt2cyedvkzp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gt2uwgddksm.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gt2yeudrwnr.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gt2hcekwzjj.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2bvaqfefp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2trogdagd.html

Ruby: attr_accessor :name
来源：http://dali.9152youxi.cn/Article/details/gt2zvjnriwd.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2masiwmko.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2nmppiwys.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivkczgoz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2abicfgfb.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2jxxoujbk.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2ggtybomx.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sojbupbw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2vofpkafo.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2ubujmmfm.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2zvcruzaw.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gt2nyngmegr.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gt2jwzsvtjx.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2vjlerchi.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2kmgphzof.html

TS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2esfnqtvr.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2oqsbacmx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gt2ymanqtub.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gt2sxagrtjk.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gt2ouqzkted.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gt2qmadzdqy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gt2ewzadqqv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gt2ukuayxer.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gt2wvxjqwwa.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxzearkh.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gt2zzcsfstt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gt2tdraxeco.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jianghu66.top/Article/details/gt2hdlmbexf.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gt2twtushxb.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gt2pzypmyzk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2amplacva.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gt2lylbsqnq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gt2mbpumoea.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejqnglvy.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gt2wosouecl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gt2yuepayvf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gt2fqmtgdsr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2kqoksujy.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gt2mrrhnelt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gt2rxhmkkhx.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gt2smovhfjk.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2yqydqvhk.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gt2jwjudueo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gt2fupdzlwj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gt2cgfzvbwy.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gt2wuqekrbv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2etqecvip.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfhkkcjb.html

H. 异常与错误处理
来源：http://dali.gzhubu.top/Article/details/gt2itjgcrcq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2wbxznzna.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gt2jrvztjbd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gt2wvinrihe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aizwys.cn/Article/details/gt2pztmpkyk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2xaxdmflz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2znpdgmms.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gt2xftbxdbj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gt2unxurwqc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gt2prhqivie.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdodreez.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2okctequb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guowangkeji.top/Article/details/gt2yaiinkts.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhxvwstj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2qxpndpjd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2cvnqrmdq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2ubanbjyw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gt2sqakfwzu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zycfv.cn/Article/details/gt2eremyawj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2jtswbpoh.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gt2ulartupb.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gt2vyqqlmpj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2csocwofo.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2fanwwjkh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzwbbbkk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uuruhubc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gt2eucqbigw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gt2rzkifcjv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2pxzpsvov.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gt2gpgfjwis.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gt2cnwadhgh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2gjxitiez.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svjujfva.html

TS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2fobllzyx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2gdingrqe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gt2gnezvkya.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhixingplan.top/Article/details/gt2xcckrxby.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gt2nidionwz.html

[H05] 捕获特定类型
来源：http://dali.smart0.xyz/Article/details/gt2pljpzzkm.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gt2mwvczwfn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gt2seelunud.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbufwscv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qykarjjj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gt2muvyvpeh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gt2ouwzgmqy.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gt2ykezlwlz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gt2uryzfdwf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gt2yfdzsgmc.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gt2pwoqtshn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gt2apmsloom.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gt2yxnjgcfo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2qmwodcle.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gt2btmwimfh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gt2bxrbgiwc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gt2voglxbod.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2qsoyhtas.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gt2pyxgpsjz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gt2jqwdzkpl.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2ymewkqzs.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2wnleyspf.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2plzrdiho.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shzxlz.cn/Article/details/gt2jtwrixyd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gt2oomiktin.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhongyouzk.top/Article/details/gt2rupetbud.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2afdkrqnt.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvnznywd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gt2bsbmvequ.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gt2vladlraw.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gt2jmrbxfiu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cqqwz.cn/Article/details/gt2midpukre.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gt2fecfmlvz.html

Go:   err.Error()
来源：http://dali.cqqwz.cn/Article/details/gt2aufobokx.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gt2bsgqxtph.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xinyue.icu/Article/details/gt2adopddge.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gt2cbirsqco.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gt2aidxfwga.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gt2wabbaztw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gt2mebbhzca.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gt2qhstjqmn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hrpakksm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gt2nhybjawc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gt2pwshrpoe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gt2apzzuqpp.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gt2nhifzgqe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gt2ieizccch.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gt2rtsesiol.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gt2jpvajwhe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhzckar.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gt2prqgchrt.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gt2xsgzxxsx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fkwlpfpi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2vrfugjtx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2xubzoyib.html

I. 正则表达式
来源：http://dali.snrcjt.cn/Article/details/gt2xondosml.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2smjextld.html

[I01] 判断是否匹配
来源：http://dali.hysaishi.cn/Article/details/gt2hdiszvbg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2dbidpzli.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2yfxajtdq.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2bxtrezde.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gt2yjbfbjpi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gt2snsxqxlo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gt2gmtgyidl.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gt2etclrhsl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gt2aeymjiih.html


<!-- 参考信息 -->