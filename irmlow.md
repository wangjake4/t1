代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2wzwaltsd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzrikqvf.html

[F07] 创建目录（含多级）
来源：http://dali.gogol.net.cn/Article/details/gt2jnkvyodl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gt2fujdwooc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrxjemfm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2lsdywgwd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gt2hxouapxn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gt2dsyxebjt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gt2ofndzjnu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gt2wmqcmadr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gt2kmfgellx.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gt2mkyeprit.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gt2plaqelsk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gt2ojghjajv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2dhisoxjf.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2azmxsldw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gt2vddnzjpo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2dhqkbtdx.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2psqsxxkb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gt2tkgmussr.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gt2wjkcnlxj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2gbplkaxl.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2knjldkfi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2taaaxila.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gt2hywlaabi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2xnjnbhro.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.0kj1m.cn/Article/details/gt2plkobpme.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2vpdtahun.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gt2dxcxlufu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gt2xmufzbli.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2pomivzyv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2gydrglci.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2eifdnqke.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2stclhcyy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gt2bccdwcbt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2qchjfblt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2otzyazus.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2fyljaghg.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gt2wygsipaa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2ejxolzrz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2bcidvwhj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2kcqdxwde.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2zpemdnqf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gt2aqrfxueg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.mhx1999.top/Article/details/gt2avdyvncp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ynukthpq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gt2rtbziwaj.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gt2wiefiows.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzfejdzj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gt2ffiocpfs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gt2xjphefdn.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gt2zzqlmdab.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gt2vsnttkkn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gt2sdkkhmim.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gt2aawremhp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gt2qmczqvcd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2crtvtdlt.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gt2pwufpxjq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2jrvywtcf.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gt2jcfkkabd.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvfitlfr.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2twrncdzf.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2phzekvlp.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gt2utymddoi.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gt2kefaatcb.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gt2jgmbdqnj.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gt2dmwbrxce.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbhvqxul.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gt2umlgotvb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gt2mgcousri.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gt2seubmabo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2swbzlgzb.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gt2ehzzazww.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2ypowveph.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gt2gxzrtftc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2hmzwrwkj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2pdupayoh.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nndlrydo.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2xxfiegoq.html

PHP:  public string $name = "x";
来源：http://dali.xylfe.cn/Article/details/gt2wpkesgxn.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2jqkqacnq.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gt2nbeeyvej.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gt2kjqjoekx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gt2qwdumvpt.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gt2iquivqhy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gt2lgipzsvj.html

[G04] 定义方法
来源：http://dali.hysaishi.cn/Article/details/gt2ltjhiwbg.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gt2xfxmglyl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2yxzxtkfn.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hrbkvpiy.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2ozcypaiy.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2rmgbeyea.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gt2pzkzarja.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2bucecwsf.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gt2qwdiodtc.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gt2hrmgsznx.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2maxesgzj.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2zrzsizfc.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2aqvjpmuh.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2beisbmnm.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2klxdmayv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gt2ujhzjrly.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gt2xdprsobq.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gt2xvtqukxf.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gt2kmsnuyux.html

Py:   def greet(self): return "admin"
来源：http://dali.c1oappe.top/Article/details/gt2sobrnwyz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2yqdlvgbh.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzuafxxy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2pydjgmab.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2kjywzgcx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gt2osilwgpe.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gt2oiijqxdc.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gt2qvdjvunn.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gt2shcxorgj.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gt2iuvlmyzd.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gt2hcupxant.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2qtqkexrj.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2wihcjcvf.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2vflisjxk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gt2sggfyygp.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gt2fojdhest.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gt2esyhljhd.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gt2otkjvlmx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gt2xherngzd.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gt2mvfoshrq.html

JS:   static f() {}
来源：http://dali.tianlin.xyz/Article/details/gt2kukldndi.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gt2pziatefl.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gt2nrwsreod.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gt2kmfmeoxl.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gt2ykryfcab.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpwnaefd.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gt2woxxivnp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gt2xwajzidd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gt2voknjxyd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gt2pnsceiqr.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gt2zbkcathd.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ufpaimmy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gt2aqvbzkrd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jaelujzi.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gt2nbvpliin.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrsiontt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gt2bwnznwtn.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2upalntjm.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gt2opkltnlu.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2tshridrh.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gt2vwqonjwh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gt2dbwgpeba.html

Ruby: public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2ddfuowom.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2oddwonwp.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gt2kvgwsitk.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gt2qfniuaxg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2aiualwym.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2daoqhpuu.html

TS:   get name(): string { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gt2ctmecxcd.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2ggnsnnzy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2hlfgzufu.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gt2awjorlfg.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gt2elbmobkc.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2hlabccsj.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2nefidzec.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfbbizas.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2salcrfvu.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ghimmhru.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2mlbstuzq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gt2rhrlcvfg.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gt2ggxetadx.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2cuahqxcl.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gt2rnflgqkm.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gt2kgnziyqz.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2pxhmhpmq.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2yphzfoqb.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2royeqldl.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2hjiqjjqa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqgvdvts.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gt2xvkkgxnu.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gt2ucwclkmc.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gt2hznciavs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gt2dvbgsdyv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gt2tbrcliet.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gt2xerrxpci.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gt2njukuppk.html

Java: record User(String name, int age) {}
来源：http://dali.tian-w.cn/Article/details/gt2zwfmqsnc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gt2odqnazll.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gt2troukrdf.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgqnifpu.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gt2jibrtgbu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gt2dfncljkt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shzxlz.cn/Article/details/gt2fxcvvxwv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gt2jscrrrsv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2rnkbtrzw.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gt2jyyqikvp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gt2ennfvlgt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gt2ayuhetxt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzibxugd.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gt2wmqhyywz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gt2ehdblqsa.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gt2btvvaaku.html

JS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2incnaaed.html

TS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gt2mlumfccg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gt2nahghfvx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gt2fqakjzfs.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gt2mwufpnhv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2vohirwur.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2bmicrago.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gt2mofbtvex.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ygdkyoes.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gt2nxaqgfpd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gt2fpbtxxwa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gt2xallokhs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vezjgbhs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2xemusjgz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fzhhl.top/Article/details/gt2klhizxgk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gt2yegaclih.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gt2wvzfdsdb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxinkj.top/Article/details/gt2lhgbjwln.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gt2supzejqc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gt2wolxedew.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2pfrpebfc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2lrxvnwer.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2okuezswm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2qdydvvuu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gt2swhdmhjn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gt2umbebkue.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2oplwulwu.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gt2nwvlsfmk.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gt2aoavawfe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2vilwjvlk.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2slyxgdxv.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zreneebt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2wrzylwyp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gt2ekjqhknr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gt2iipmfhee.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2lzwzcqcm.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gt2mzbehrde.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2kpuopsxp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gt2zkkrbzia.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gt2gyniejqn.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2vkypfawa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gt2yhndspok.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangdashe.top/Article/details/gt2cvtmbkae.html

Ruby: class MyError < StandardError; end
来源：http://dali.yangfankeji.com/Article/details/gt2plfvrwfc.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gt2csixtjzr.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gt2dfmvfkyy.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gt2suvnfobx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gt2lecppdxm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gt2svxbukaz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gt2rvdrczgp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gt2vcgtllob.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gogol.net.cn/Article/details/gt2nzjowtjx.html

Ruby: rescue ArgumentError => e
来源：http://dali.0kj1m.cn/Article/details/gt2qzqnjjpo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2lnzgviwa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gt2etmwcccg.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gt2truyqnxp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gt2pvvhdnig.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2mlpywcsi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gt2vzlcmgzn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wyziyljc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gt2cnhohuok.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gt2hchhshgn.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gt2odggeicb.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gt2rhzwjvpv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jiagoushi.top/Article/details/gt2jydfgydv.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2ntwdlriy.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gt2vsmpuamk.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2myrnfeir.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gt2eznsmtjz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gt2neldpqki.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gt2qrcodhbi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2rmsqddjd.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gt2hssuwtpo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdferkcq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gt2elzieqhs.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gt2czsoeipu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gt2bjjafcwh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gt2tsvfhzgv.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gt2eeuwzvua.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbygvnfs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gt2qrzeqkhy.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxspawqr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gt2sztvbllo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gt2ouydusqt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gt2fnvczonb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gt2onzoixkm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gt2lahygtac.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gt2ufyhlqcq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gt2vxvmnzzc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gt2fmdyswat.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gt2zjjuxrhp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gt2dmhtpwxd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhvtumyo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gt2bxnwftha.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gt2gffzaphx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gt2rpbosmfu.html

Go:   defer f.Close()
来源：http://dali.kuanghao11.cn/Article/details/gt2hqpcznlf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rpbhhajf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2sdevazij.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2prhlvmpu.html

I. 正则表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2urageyib.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2actgsdeh.html

[I01] 判断是否匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2dogfuccw.html


<!-- 参考信息 -->