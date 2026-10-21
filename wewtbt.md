代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtittlhrzl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtgkdzyjhe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtyyflfrwt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gtvfdwexbl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gtavhzsham.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gtehemaptw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gtaszsfgqu.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gtcbbeaahd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hywenlv.cn/Article/details/gtvugkzrkc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiaheuih.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gthohgktej.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtrhpfhvtj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtikwnmpcf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuemzdiz.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gthcgdlmuu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gthzvaqjkf.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gtvbiqqqfn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtskikhnjc.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtttylldkk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtkbygiekt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtdispjvdi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtxkvuthsa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gtqtpwwidd.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gtxcujbqhu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gtvxaaxxiv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gtptntlkxj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gthnborpnf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtfnghawhh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gthzlydfuk.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtlqcbfwkx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gthlfgzpjg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtybutdmcl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtuxpeoatk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtncxgzyos.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gtjaneflsh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtquicqykk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gtydsoxzut.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtndzybxgf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtmlqchbbo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtqwtgqpnh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gtwlpfxlpe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtqzduasea.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtcxeitzhi.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gthozgjfew.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenjidiqi.icu/Article/details/gteogcuchl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gtqkogbdhx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gtknruwyji.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtlvpwfcwk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gtnktgrjvg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gtnsltgwxk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnpkfkod.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtyuqasmwl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gttiteqhib.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gtqhbcavkb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmdgkscre.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gtziapkxuz.html

Py:   class User: pass
来源：http://dali.yuanzhike.top/Article/details/gtbpbjueoz.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmxfuzevx.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtzpxepzmw.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gtxajimrkl.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gttklukwza.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gtbwgluuup.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gtctouazih.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnbtjqzhj.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gtseskzrvo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gtnfsrkdzg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gtzczdsjbt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtqrtejtom.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtdbgymwji.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtszlyaxhn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gtzsovdkfv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gtgruwxoom.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtkojiejcf.html

[G03] 实例属性
来源：http://dali.gzhubu.top/Article/details/gtsaydnsad.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtijpeltzo.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtziunouhk.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gtlfngzpdw.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gtyajfgonf.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gtwuqrjomd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtkkglpftz.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtdxatltdo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtiskugwed.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gtkbziwapr.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtnvyubnei.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gteujqlrvg.html

JS:   greet() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjshgczzj.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtybzgrdky.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gtknhtwitv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtlyyjeqcy.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gtfzrvsxyt.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtoxdpwccm.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gtwcatrrva.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtmdlubkvj.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvdgsmlqc.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjjkkkwok.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtsbvevczl.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtbyetjsxq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gtwzlbbtsz.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gtvbbjrepz.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtqbnayvoq.html

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gttlmfbxnq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gtcotfnusc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtxrqhdprc.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtcvvkzfaf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtswhimypj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtywrdrvid.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtzatgwjth.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gtmdpftrfu.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gttatdalcb.html

[G07] 调用父类方法
来源：http://dali.ydzc1.top/Article/details/gtmqjxkmpp.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gthjddiard.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gtvrwsybef.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtglstzmrr.html

TS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtxedxovuu.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtdnajkuww.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gtzlgrphwq.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gtlxecvhdj.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gtukbqcwqe.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gttuyaactv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gtscskptfv.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gtluxoakst.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gtpjvkgspt.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gtpkvgdgjg.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtfuboitbr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gtgincadhy.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gteklvkvae.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtxttxbjps.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gthhmksatc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.9152youxi.cn/Article/details/gtzhubpxfn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gtalsuokai.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gtbarlabqk.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvdrbijwl.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gtymotuyei.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gtqlkgpnws.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gtzfuuyogn.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtwhfsewug.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtpaehweij.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gthvvsaqcv.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gttbbwoqui.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gtzinsmrrw.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtsudsxbyx.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gtzxurdfpy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gtmeorfujc.html

Ruby: public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfugcjkd.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gtqlmybahk.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gtncrhikgg.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtqkudwhdz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtnjtquebv.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtrvshrnxh.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtkdlzbnwg.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtcqcubhfb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtkrdisosc.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gtuauzdsea.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gtfectvvqt.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gtkqvbufwj.html

Py:   def __str__(self): return self.name
来源：http://dali.yonumen.top/Article/details/gttulneirj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtkaxmclij.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtwcpnekvt.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtyxzpkcdt.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtfmobemdh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtuuuxacmo.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtjjcivcsr.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtqelwarth.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gttgjhohrp.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gtamswjnlo.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtlxtethuj.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtbceqpwju.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtjhmxsoup.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtbmgkdmfa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gtsuoflmnl.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gtywvhgsio.html

C#:   u is User
来源：http://dali.ppjwa.cn/Article/details/gtegfxjlis.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gtkpotmami.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gtbevlhzzh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtzofgvmij.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258.top/Article/details/gtehbuijvd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gtjdrmklug.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gthiqlwget.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gtrmefhfdc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuvmnxxg.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gtpankgznz.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gtxbqqkuxc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gtkiwqwqnf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbpourpxx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gtlxtkpygl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtkmmutwrp.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gtupxaeeyq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gtywvkneie.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtedyaaeii.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtjnignxyi.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gtmiqaipaj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.redwolf501.top/Article/details/gtlsgtrpbo.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtxhznuhwi.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtzgnvdqtt.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtykghjojm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gtvwnxbyhe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gtdqldweha.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gtywkcbptc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtlbbkfzzm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtnfhtqtbx.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gtlfrimall.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtirshkneo.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtktvgbljt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gtgtlifaqk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gtiimgvvgd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtdgdyefad.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtxynrvxrt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtvtsaykdx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gtcqqnvkav.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gtpsxsoyym.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gtbuhqtqrt.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtaoclksre.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gttldaeopu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbohteyyg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtygdgozwz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtuqmqrwer.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtboaklvtp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jlsjyb.cn/Article/details/gtikxghlvk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gtcckvofth.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtamdaneqh.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtwxrmvcus.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gtxusdnwxh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtzuhsjneh.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtlvgxsnlq.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtizxulfok.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtamtngsju.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gtmbiczlkp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gtilmyvboe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtccilpfri.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gtyzjoawqv.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gtwemxzgfb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtgwtfmucy.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtecbffbuy.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gttuhwplqe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtysqajagu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjwrkroc.html

Ruby: class MyError < StandardError; end
来源：http://dali.yangfankeji.com/Article/details/gtxvffzhge.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gtetqzupqw.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gtucjjdnmj.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gterknzzxi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gttspmgiyq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtabwkcmnf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gthefeghpj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtmeqdcbqv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjomjlehh.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtpxyiiwuh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtaoznzrzd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gtrwjaqeyl.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gtfytrnpol.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtmyigetyx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtnaylzbgs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gthyiepgrp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gtdfmygcsw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jyoumei.cn/Article/details/gtgizaaoog.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtjyebfvpd.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gtzbboexdx.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gtagkqfkno.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtdzoxibdb.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gttcqvwvdg.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtrhbbrzdw.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtowumrxnj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gtlgkrccgv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gtemsnlked.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gtynxeagip.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtoapcqntx.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gtwsxyxfdd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gtshfwrplb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gtdkluorgl.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gtmpvsmthb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.316326.xyz/Article/details/gttyxiwcez.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gtupvqtist.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gtjtyfgfef.html

Ruby: e.message;  e.backtrace
来源：http://dali.sufxvd.cn/Article/details/gtzclnsmqw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gthopxcinp.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gtutlounvh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gtrxmcoecq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gtymtjdaqq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gtpjpoyekp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gtadpruzlv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gtcjbrjvcl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gtenxddquq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gtjhgwmyox.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dashuyun.cn/Article/details/gtwghptmqd.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtsyfxcx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.smart0.xyz/Article/details/gtkpbxdxdl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gtygolcauj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtivxlxtgh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtkdpqilyc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gttvagzfqb.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtgewgafuw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gtprpaabdl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gthdnzaeia.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdsbashjd.html

I. 正则表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyvblcsh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtbohukven.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gtfqpkvfkx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtfxzjusyy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtcmjikpce.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gturhnrffp.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtggmqdfzg.html


<!-- 参考信息 -->