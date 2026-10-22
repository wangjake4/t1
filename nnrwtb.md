代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2eeydfjun.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2qigzxfex.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2vfaliufi.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2cclckxkx.html

Ruby: File.delete("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbpbdxvo.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2nkwfyyjn.html

[F07] 创建目录（含多级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnhfribm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gt2telgogeo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gt2vnqpkzvf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffemgqmc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2wvhkzvwx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gt2qqthmabl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxzakysp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gt2asaaifvs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqfhdcfx.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gt2uskfmnyn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnqzz.top/Article/details/gt2ptjldzqa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gt2nhufmnwq.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2cugpxplf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjckgjdc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2oijwxcse.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gt2gxzdqklh.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gt2slcbqlnb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhuhuur.html

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gt2rfrugfib.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2wezcbpqu.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2tfplvseu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gt2jdhqihmh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gt2lskyluzl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2kvikisla.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gt2drmknsvb.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2kauqcony.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gt2kprzpztp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gt2mhmnubyt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2mpnqjith.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2wetweosu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2iknrqnsj.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2rxwohzzo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxinkj.top/Article/details/gt2ehodpbmy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2eavwxeer.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2nczefnpb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zgldiopd.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gt2wszkwosf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2woqypoku.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gt2pbhvajde.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2scllaqvx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2pqujbkvf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2fwdhseak.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gt2qbkmmojr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2whxkrrgo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ckqwizvh.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gt2wivdssjv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gt2rqavsbug.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gt2ubegpbgp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gt2owwoouvq.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2trvmevxf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gt2mruwpwjl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxwfmabe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gt2czkczzeu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gt2yixdclih.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ucbksssa.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gt2ygxpzvho.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2cotveuhc.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gt2tebcapqj.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gt2cgxbxqkd.html

PHP:  class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2lsnovrqu.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2iujpfpuv.html

TS:   class User { name: string = ""; }
来源：http://dali.hfpthk.cn/Article/details/gt2zoerbocp.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gt2hjjdywiu.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gt2yrgxdthu.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gt2andvkrez.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2ugfldilx.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agqjqdfr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gt2nbqiprqs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gt2vnpamtbt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zoqkcext.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gt2nqtsfybw.html

Java: User(String name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gt2vvabhsvz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gt2vormqbtw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gt2yvkagear.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gt2eiwlfdjy.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gt2hozpcftt.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssvwmdks.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2ubpofgmv.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2wqhiwdmf.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2byntmwyk.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvxsiimp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gt2svmxemmv.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gt2nwwntpwx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gt2wmhintfu.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gt2pdrdexzh.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gt2qmwodbdn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2uopdymgs.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2dclqolne.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2kptafpcs.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2cppqncog.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2zpztvscq.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gt2kihfzgfn.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovlxiskl.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gt2zwxsllnp.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gt2bgmtmdrk.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2acnfahpw.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2vzqrtwsp.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2uucgfjed.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmehhktz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gt2yacqlcqj.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gt2kamjipka.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ikqhacjp.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gt2wofrwvwd.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gt2uykorghl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2sigliiqh.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2rlbtxizt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qympgrzj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2zlwncrsn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gt2gqxjsqhe.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gt2pfiryfwq.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gt2cfkquchq.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gt2xzkiinfz.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gt2cmzuaunh.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gt2gjnvrgbw.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gt2lgrqdjgc.html

TS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2amgatihl.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gt2uhrpjzha.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gt2nyooqcug.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gt2jmnirpwx.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gt2hoouddnx.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gt2jxsifqut.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gt2aqikanve.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tijzwpfs.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2ssgpgbxv.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gt2iiyzjbej.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2utpopgfx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gt2xnoymtuk.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gt2bsgwbass.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gt2tkguxohc.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gt2kdhaixdb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuanzhike.top/Article/details/gt2ysctsizf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gt2nwamknfb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gt2ofmnizwn.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gt2nrgmfbjn.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2oihsmvtr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wttohlai.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gt2mqhkpkpq.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2wrulodxg.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gt2azjeyegz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfmcwyua.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2wsdqbadm.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gt2xqediqrf.html

TS:   public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gt2saikwvvy.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gt2sncnffda.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gt2yzolmibj.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2mezsvmqe.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gt2trszefkl.html

[G11] getter / setter
来源：http://dali.nwbrower.top/Article/details/gt2airfssfk.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gt2iantiaut.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2akcvztgx.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2mmmtomys.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gt2yzdavdbv.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kijmadlh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gt2aywesank.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gt2uyfgntts.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gt2tmaaxelq.html

[G12] 对象转字符串
来源：http://dali.meibo888.top/Article/details/gt2jofvqcaz.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2oexqdxqq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2xdxclfiw.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2nkoikxph.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2tqobpidt.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2dpntcclb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2yeviuzod.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gt2qmzttbhe.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2ylkpdccx.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gt2jjbvkfts.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gt2fxongmwa.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2wjsnsbah.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2hgpwirhp.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2idzjiymq.html

Java: u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2qmltmayt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gt2ywqjgxis.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gt2oazaohlb.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gt2olpqrkax.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gt2tavnngpg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gt2dcqvffug.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxqptpdz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gt2jpsukcaj.html

TS:   type User = { name: string; age: number };
来源：http://dali.yueranfly.top/Article/details/gt2pkkdthec.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gt2gaxxkwjf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gt2cptnzmge.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gt2laiojnqk.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gt2zaztxise.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2chvrboel.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gt2uuohkdqd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gt2nffuulji.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gt2bvecrscx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gt2psmwlfxd.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gt2tbtaucaq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlyzxrjx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gt2yfqrrunw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gt2lpwmbqgj.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gt2djnshnox.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gt2vvwmrbfg.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gt2ivthydyy.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2kuxkdwqq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuajrjro.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gt2kgqchkor.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gt2rnodpeov.html

Ruby: obj.instance_variables
来源：http://dali.yuxming.cn/Article/details/gt2royifqoj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2ommeibhh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2qgegmigi.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yoprgynw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2heeelmjo.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gt2ysfnwncm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gt2gafmypko.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gt2jfojnuzr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gt2xdiimxdm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdifzppo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gt2oggcetqc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gt2vxgptasl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gt2rfeqmrvk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zycfv.cn/Article/details/gt2ozcgjbfj.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbrwbkkx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gt2piqnapss.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2bplsxjgz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2nkjqrsfe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2emqwhunp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2uslwripj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gt2flesyayh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gt2urysjgas.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2rezdibab.html

[H03] 主动抛出异常
来源：http://dali.chenlongwang.top/Article/details/gt2rkzzqril.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gt2tfrknepo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2gjbebbwq.html

JS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2ltvckpgd.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2mouqnrhx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2vnmdmcyq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ddenfjxf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gt2afkujpda.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2qgdtqfwz.html

[H04] 自定义异常类型
来源：http://dali.yangfankeji.com/Article/details/gt2gkxyrhvk.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gt2aojbgipa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gt2fvakmggl.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2duepfnma.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2djuxocbg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2oerfxvdk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gt2mvrkhnuw.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gt2zucttivc.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gt2mwkwohrj.html

[H05] 捕获特定类型
来源：http://dali.daria6918.cn/Article/details/gt2mhrdmbch.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gt2dcfeweyt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gt2dfqtzjtm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gt2ppohwyxw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gt2zuagyhng.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gt2qoojfcax.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gt2locvvtja.html

Ruby: rescue ArgumentError => e
来源：http://dali.sysykeji.top/Article/details/gt2quvyuqyv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ylqitpau.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gt2lgeyyayy.html

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gt2cmfslnuf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gt2chkceurq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2ujpyvkrv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2bfjtbxkh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gt2etlhkvzx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gt2xellwyrm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gt2gfvfmqeu.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gt2yzwuvkli.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofnltrmv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gt2muqbogxi.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gt2hbxbtwff.html

JS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qflkmhav.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2hpllqpwl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gt2lguwzayp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gt2ggzzrlbq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gt2pjadksqc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkespuzg.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gt2sxkugfay.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gt2jfebkife.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gt2otbtyysu.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gt2rmnfnmad.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gt2lkynegdo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gt2aunlspaf.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gt2jkbglfgo.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gt2yukezyeh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gt2kylupnif.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgjqscr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kklmaoep.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwqhgwnx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gt2vjxzumar.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gt2qqlblxtg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gt2emtkdiql.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gt2izwvjeyx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gt2fccrlamp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cashguo.top/Article/details/gt2ribjtpuq.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gt2syqofzyi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dianchejie.cn/Article/details/gt2uonhshyf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2irhqomei.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gt2wpsivgni.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2rqvdlukd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gt2lxufilwh.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrkfhtw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gt2gipulmhd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2srhhhvly.html


<!-- 参考信息 -->