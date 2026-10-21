代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtgzmmsqfm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtosnkzvwq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtkduwyuqi.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtslgoknuu.html

Ruby: File.delete("a.txt")
来源：http://dali.hammf.cn/Article/details/gtobggicou.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtivykasvt.html

[F07] 创建目录（含多级）
来源：http://dali.kuanghao11.cn/Article/details/gtfqhipmsq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtkvzrnrcn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtgnkrybui.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtxwpgmasf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gthoqwskzn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gtejhumxrs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtulhjocyi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gtpynrjzoh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtzbruksqg.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gtxnizxmpc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gtolerdfea.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gtcmjbzxvq.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtkmpnixns.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtrjnxovjj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtntkcvokj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fengsongda.top/Article/details/gtqpwlmduo.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gtwumskmrd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gtssavivuz.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtlwygleht.html

Py:   os.path.getsize("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtvfalgqxt.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtapfltkfh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtbcfpmepp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtxgkklify.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtgscbhvmh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtqpfgtudv.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtjsmehqwk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtroidlsbh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ppjwa.cn/Article/details/gtlmnzzibw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtdxwzthhl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtbgdeaxgz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtduqldcmj.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtbmqmujan.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gtwfsghhvm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtcqbtqpza.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtlxdurmrz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtazfycjns.html

[F11] 复制与移动文件
来源：http://dali.chenjidiqi.icu/Article/details/gttgeabhxi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtjkfopqsi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gtqtjwsidh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtrkujwfkc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtahydhoxc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj202588.top/Article/details/gtemtafimn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gtnferfuhv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtvyujamsl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gtbhentjuq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gtuihfiaqh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cdnleiting.top/Article/details/gtkefywfqi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gtepvgbqam.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtitomxoxq.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtvldtvsoe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gtdxkkrbaj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gtkaiydfjm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gtamsrnvwu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gterxembhc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtyxczyiho.html

G. 面向对象
来源：http://dali.chenjidiqi.icu/Article/details/gtnzfxcoil.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttwwfswsl.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gthazmuxxo.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtgdcjttbj.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtiqgjbwti.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gteufbuvtm.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqgzjaeec.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gtvuozyatg.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gthatwvzsx.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gttxgrymvo.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwmknsop.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gtdqnhqeub.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gtwrnczeul.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gtsazocomn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtwtrrlfmu.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkvbowup.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgafzqahk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xinyue.icu/Article/details/gtzswudajt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yonumen.top/Article/details/gtpvgzhbog.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtvqwwjpno.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdrbrnkq.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtocdolacq.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gtixxkkaps.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtvcmqsimz.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gtqbcfcpjb.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gtlugrlgay.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gtgchhnfyb.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtskloqymx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtumkochxa.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtfdimzbwp.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtcmtqjbvu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtoihmifla.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtvkunosnp.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gthfrkydhp.html

Java: String greet() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtwlzadmwy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtwobapfrk.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gtguljzsiy.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtsenxftgm.html

[G05] 继承
来源：http://dali.jianghu66.top/Article/details/gtexgizkxg.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gtlghgzayi.html

PHP:  class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtkadltzqa.html

JS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtpdfwbrru.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtgjrkhgnj.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtkcyaeg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gtnqanljgm.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtschbuujd.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgywaqykc.html

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gtfxespvbz.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gtdrswufrv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtyfyvhfmg.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtuusndxmz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtukahziov.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gttdfnrpzi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfwwdixe.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gttjjepdfl.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtyxjfwbij.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gtfnqkesxl.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gtxirrfptr.html

PHP:  parent::greet();
来源：http://dali.iojbl.cn/Article/details/gtgoqnycyv.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtvadhqhuu.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtzvgixdlj.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gttnoybqbv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gthlhlywmg.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtmecbdetr.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gtkspmjqjg.html

[G08] 静态方法与属性
来源：http://dali.chenlongwang.top/Article/details/gtmwoffplp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gtjnbgcnbt.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gtlhszjfwi.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtlhvqkdqt.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gticcfsoqz.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtnzzuurgl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gtzatlvrzh.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gtloqwfchx.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtxyjxlimw.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtouqkkdrx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gtptkdmycj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gtphzdrsuc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gtpuoqrkwk.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gtnhtmbnvg.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gtffrfdnpc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gtawdbvknp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gtkverxxit.html

C#:   interface IShape { double Area(); }
来源：http://dali.aizwys.cn/Article/details/gtkubyssfs.html

[G10] 访问控制
来源：http://dali.hongshengwenyu.top/Article/details/gtrfwrwpsz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtstoxgbzt.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtntgkyboz.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtqepipznx.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtxwakstiv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gtfiwmpckc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gtbndojkxg.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gtovkrlvtc.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gtfyovlncl.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtzbinkjlb.html

Py:   @property 与 @x.setter
来源：http://dali.jiagoushi.top/Article/details/gtonvhwdxg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtponblqrj.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtfnnqcjob.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtsieexxls.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtgwtxtstk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtsfddfevs.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtrvcnhhwu.html

C#:   public string Name { get; set; }
来源：http://dali.jiagoushi.top/Article/details/gtyuvcimhk.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gtqfluuvlc.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtibqxbxzj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtojuatzkk.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtvzhugdnx.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwrhvfzlt.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtshexczyl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtzzwybizf.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtfbtrjyxs.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtdqlasgob.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtzcuiekta.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gtorptouyl.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvcjhgnz.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtvkpqvlps.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruxefuic.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtbyoczqkp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gtwaljaqpg.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gtygfpufnj.html

C#:   u is User
来源：http://dali.aibaodan.cn/Article/details/gtemudnrvi.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtlltjsagw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gtwjfkqyip.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gtftoahehr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtngezlohj.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gtlzxmkiph.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gtctczjhgk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtesyteugb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gtbhcduqvh.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqednoep.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtctntgqvj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gtcmydlpmc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtvixqlpno.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtjvrstlas.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtclkysbjc.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gtnlzwwyoi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gtgjffpnjz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pengpengdd.cyou/Article/details/gtgsgtiful.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtshgaynnc.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gthkhyhkzc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gtwefbihmy.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gtiavkamuf.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtqwtxycmg.html

TS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtipaqasky.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sxryk.cn/Article/details/gtkdnaavzf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gtabqdwqyn.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gtrxjfebth.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtrmjqizsv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfbgycrfh.html

H. 异常与错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxdnrdpw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvndzevjn.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gtzlgxthsl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjeoigfo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gtiruojdie.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtgqzwxmxo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtwibulwgt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jianghu66.top/Article/details/gtnldwfmxg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gtvagolldr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtygesldvb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yongpay.top/Article/details/gtwmnueane.html

[H02] finally / ensure 收尾
来源：http://dali.zhixingplan.top/Article/details/gtqjnhsgqb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtpkglvimx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtqkvfmpgw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtfpsdixkh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtgdtcrese.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gteotbrsll.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gtbrvxbgmm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtnhkyemdm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtwcasrsib.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gtzhydxthn.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gtwyaevqjr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnufoxni.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtpodixivo.html

TS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtlhnpkpza.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtwyrqwxet.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtmjxscryt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtpqsodjer.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtjhwvfjjm.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gtaftkpujs.html

Py:   class MyError(Exception): pass
来源：http://dali.ppjwa.cn/Article/details/gtsnatagkq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtttxpybda.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtiwdleuwc.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtltfjhtkc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtzkrorlyb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gtwithemei.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuetiantiany.cn/Article/details/gtazpjjjpf.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gtwmsynece.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gtqpbuvpgi.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtddtqxnvr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ppjwa.cn/Article/details/gtrzezjbjq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtpjgtuezt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtxvzyvcrt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtzhnifuar.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtcqgxmxse.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemhsuurd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gtpqyrurcg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gtwtdyvogz.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gtvbolvfjg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtthhhpzsu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtechtvexu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtmpwdlfcg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gtnlwsabcb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gtvcfxhgaz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gtpkouetjh.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gthhbciahz.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gtbmftmmxh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gthdvvvqzj.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtvnccolet.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gttoeusnxq.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtiwmfbvxx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcykgalqn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gthjhiiosm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj202588.top/Article/details/gtphyvqecw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtjdtkdfhn.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gtldwfybol.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtdicceqaw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gtdjbforci.html

JS:   e.message;  e.stack
来源：http://dali.jiagoushi.top/Article/details/gtuybdpjtn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gtdhemfskx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gtnhbhqtpt.html

Go:   err.Error()
来源：http://dali.xziqi.cn/Article/details/gtemkhflnv.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gtmnhegcbm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gtasybvqpu.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gtktjoeucg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtdtkazmkj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cashguo.top/Article/details/gtlvtjxedd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gtkgakldaz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gtkqfihdsh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gteymcgand.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.andypj.xyz/Article/details/gtkvvukhbk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gteaxdaeve.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gtmfmemlyf.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gtklabuxhs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gtlvpainpb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtojoolaqq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtpyadbgve.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtwqjrzzdz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cqqwz.cn/Article/details/gtbqzmknfl.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gtbsnjtcec.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gtjnbonxrq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtmoemmplf.html


<!-- 参考信息 -->