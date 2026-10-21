代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtjvlzwwiw.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gttcgutbdf.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gtzbqbyosy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtluxuywsn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gtdoylnvym.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtxbyzlxpb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsxiqlxe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hongshengwenyu.top/Article/details/gtrhsissed.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gtjlkrnofk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gttahmbqku.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hongshengwenyu.top/Article/details/gtfxocrhcr.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gtxcfivpxz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.bjfxy.top/Article/details/gtlzuaimvf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gtqfdcgqot.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtrlucnngv.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtnuqbnwxp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtjpbdlfev.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gtauqaqejb.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gtbjubtgxb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtxvjzmmnd.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gtlwemmvam.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtherwaava.html

PHP:  filesize("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtttvdzoop.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtjhxxddif.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtdzbzvlro.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtfoaehgjg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gtzyxnandy.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtgjkrinmc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gtetphwgko.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dianchejie.cn/Article/details/gtstgtedjj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtdvzzsnzk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.birdmap.top/Article/details/gtkjtcklsz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtveufhjii.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtavdnsvzf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.quarkkingdee.top/Article/details/gtrncfwais.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtivdcvvxw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtrtrzhxla.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtiawcavxm.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcgdhlxm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtmlubruog.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gtaxpjuqga.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqopzdgla.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtoidpsmzx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gtumccfydz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gtojtwbvcs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtturhkzai.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gtowcujnrg.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gtrppkfyvh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tian-w.cn/Article/details/gtwvevjovy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gtpchbixpy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gtvishyhcs.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtdeooirwx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljwrpcmh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvblpbbs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtakgpdqgq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtsayzbdxn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpncbupz.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujdjnwwt.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtsgzyebzr.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gttgnatsid.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gtgsphwjpc.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtcrtoocoy.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtsixwscup.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gtqjmptpnm.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gtlkzkzlha.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gtebpevyry.html

Ruby: class User; end
来源：http://dali.gaohongyu789.top/Article/details/gthnodonvp.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtrpryrrft.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gtsjmjhxkw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtebpvhugo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yangfankeji.com/Article/details/gtwdxhmlek.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtsdgppzop.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gtibqsiihw.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtmnkcgyka.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gtzipwidqe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gthansnptl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtaznzkoji.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gtarvwfxrq.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gthtsdfcdp.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gthegpsjql.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtowpcrrql.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtauzexgla.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gtgypvhnhw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtrokcywgj.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtslhgloha.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtfyuilhnb.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gtopjyrhkq.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtzbstotds.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtiyyxqmic.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtwxotbnbo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtcbhdcoyv.html

Java: String greet() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtnnjnkrkc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtpgzgvmbe.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtviptnkxq.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtsorewfly.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtmjndmwxi.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gtarkxuqra.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtpwfxyxxu.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtxznewamw.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtvivrrzaz.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtotvgurwq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gtvkgnolgk.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtxejytzeh.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gtoojkkomo.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gteuzuztma.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtdkqmhkiw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtjwpkrakw.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqhfjdyfb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtdbaeoiqa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtnrswutgs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtbpdijerz.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtwakmistj.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtucvzwifv.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gtjehprakc.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtaierwcro.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gtuovbgnds.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtqbjfhkfe.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtqqzcvquq.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffwbsrtl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gtoffduius.html

Ruby: super
来源：http://dali.ydzc1.top/Article/details/gtmmfnxput.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtguiaxvoj.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gtqvjeeygb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtwppluhrd.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtnebzdeza.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtzwsilsis.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gtgqgojvnm.html

Java: static void f() {}
来源：http://dali.wangdashe.top/Article/details/gtqrgwsdiw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gtjbxieeed.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gtmttejjju.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gtmkownqte.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtvmbbsemv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtxjxpqbjb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtoyyedvno.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gtfizawkcs.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtgrbxcvkj.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gtsprxrcbo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtdhtkvqfm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gttrtktfrn.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtjqmsvskq.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtgudyhpir.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyexucwq.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrktkbvg.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtnyuetopa.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtbmyoyniq.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gtjdmahcqj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gtallkwmud.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtcnhfnook.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmnpngjk.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gtqqkwlzbk.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gtmylbpjrm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtuycsifwn.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gthkedsldt.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtouhnyiic.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtosyizlpf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtoyfqruqx.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtbdkewucz.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gthsqsnkek.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gtkmtbibby.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtgkmuidht.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkhobhquj.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gteblpjzaw.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtvevpdyth.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtbykicpfh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtvvgisrie.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gtjlkmeegj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtxqbxpjpn.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtqhkkrvhf.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtpyoyrong.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtutkkyvpm.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtophvjpir.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtgugkpaix.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtrfifhjzk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gtrtnmjghl.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gtpflzingl.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gtxbkqptsp.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtwwkndhkd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gtctqbjlyd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sxryk.cn/Article/details/gtrbggrvat.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gtblokucbq.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gtrsyxewhi.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gtbyluleap.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtcguqbyck.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gteazrxxud.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gtoxhehzce.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gtxvwaouvq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtbuhmmmqq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gtdvspbwfr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gtlespsxgv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhqksnpj.html

Java: enum Color { RED, GREEN }
来源：http://dali.shzxlz.cn/Article/details/gtoqkmvehj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gtzthdrxub.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtsrwuydep.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtwqyguibf.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gtnsfxsdak.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gtkpzhjfbp.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gtxfeajxbe.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtbqwbsink.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtbuqsjfux.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gtigismhcu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtdyshydyy.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtkkcetvss.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtzvfnefnt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtcbigsclt.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtuuiohpli.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtydcxcpvd.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gtolzklzcp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gtpmqidhsf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gtqrovyspa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtsvvpipfp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtggwnofqz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzqsixpa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gtpwunftoi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yonumen.top/Article/details/gtihibdvrr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gtzibbfjya.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtqnrppjhc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gtsnitvknd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtrhaeeocg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtehoesngq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfwoxsdr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtcgzurzgi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gtoykpsssh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gtemhortih.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtgdjmlcvz.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gtvullhmee.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gtegviyllw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtyqhpxytz.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtgiihazte.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtsuddqabx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtghdplfvl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gtfsyvlzdz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gtxztqypxm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtjzimuxrx.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gttbmhxmkn.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtuchwsmny.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtrosdpvcf.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulcauwzf.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gttfwhreed.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtztdgvrll.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gtiizzygba.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gtaqkbjasw.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtngjlvibw.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtenltugoo.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gtevwmxnqz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gtzuiupmli.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtxxttmrht.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgvlruhaz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.birdmap.top/Article/details/gtpjhlwwfb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtpbaqqeyf.html

Ruby: rescue ArgumentError => e
来源：http://dali.cdnleiting.top/Article/details/gtrnsrmtoa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnxqulyxb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gtcfsazerp.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gtbwmvtngs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtfhlpbwsn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtxhgbztjm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtjgifrmqs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gtpdigogwj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gtdfolkvix.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ppjwa.cn/Article/details/gtkvqbblzu.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhqyupkp.html

[H07] 断言
来源：http://dali.yueranfly.top/Article/details/gturulyhhv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gtbxgtlasr.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmiyewxjw.html

JS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtktmponwj.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtdqcgxqkh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gtssvsmpoh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gtkuxqvnbg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gtjirzsret.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtobdrvtsc.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gtuejvoufg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gtpeshzsxl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tian-w.cn/Article/details/gtxnwkgukr.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gtusshghyn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gtzcrodjvn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtrzdkmzog.html

Go:   err.Error()
来源：http://dali.daxiang520.top/Article/details/gtjqrlqaux.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gtoxnruhiw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gogol.net.cn/Article/details/gtyotyhtnb.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gtyzpjzojl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gtprxvetyf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtjepdujia.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gtvznphpai.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gtogmtqxco.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxhzabzc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtecsmderf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gtsirjbvso.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtyvtcgimu.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gtmzfnxzsb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gtimieaynu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdkbdqjm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtvlicpwsp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gttnqemlgj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gtwshapvgs.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gtwgwypzcn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.iojbl.cn/Article/details/gtjxsyuxof.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtttrickfq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxjzjdcvk.html

I. 正则表达式
来源：http://dali.birdmap.top/Article/details/gtbhamuirz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtukifxkhc.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gtgqisxjce.html


<!-- 参考信息 -->