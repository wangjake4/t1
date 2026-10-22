代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtpxtjeytg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtulohfvjn.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gtadqgsdqw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtrnosgktr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aibaodan.cn/Article/details/gtmcnzfhvw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtcmqsxnzb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtbrsjfcaq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gtduucoiqr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gtmauiixrv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gtrdnlfzxg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258.top/Article/details/gtopyayeuu.html

[F08] 遍历目录
来源：http://dali.0kj1m.cn/Article/details/gtvqiqadmd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.feifeiyinyue.top/Article/details/gtabovhlvc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gtqfilhmca.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtzkzgoqyg.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtaobrmpkn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtaifdlffm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gtyoawwiul.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtxbzeubmt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gtvomksqpi.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gtmbdcgjrf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gtoewujmcr.html

PHP:  filesize("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtcixgsfxo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtenjkqhhm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtkaspmylz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtugwblymh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gtoxdhfpkc.html

Ruby: File.size("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtxkcdfspd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gtqmgbpywx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gtxokpxmzb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtdewfgyku.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.redwolf501.top/Article/details/gtlqklfrbt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtoilbentg.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258888.top/Article/details/gthjgcayxo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gtrkzjfaql.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtuehtemfq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtmojqxvga.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtnucehmel.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gtzvadugpz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtuiljvwgo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtyrfclsjl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtfrrnyxfb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtgjbiwdne.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gtsytrdorj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gtbnldzjgi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtxpdkqwpy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gtjvamjvra.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gtcrbeqgws.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gtafwojsgx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gtovxhrppc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gtupebpyec.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtuxzvgesp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gtzjogktal.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtbiwbyoli.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cashguo.top/Article/details/gtnzlceepc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtuwhgkouy.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtaptpmuan.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gtxyonpknn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtarakxsax.html

[G01] 定义类
来源：http://dali.ivvv.top/Article/details/gtpujyaxhp.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtobisiafg.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtlocvqxfp.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gttmtivvgg.html

TS:   class User { name: string = ""; }
来源：http://dali.sysykeji.top/Article/details/gthwvsiwif.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtmdktlflc.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gtbfiztkeg.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gtfcrqmyaq.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gthjmkbrhl.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gtorfjuifk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtczdwskep.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tanke756.top/Article/details/gtowurbxwd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtnlvyqlrc.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gtsuwmgkri.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtlqubarig.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gtwxfdgdfd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtuanisehz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtmrvpmhge.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gttiwfgcuj.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtnawqbcpt.html

PHP:  public string $name = "x";
来源：http://dali.sweek.top/Article/details/gtdqcebkjn.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtcnrwztze.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtbwldgxra.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gtgebwbraz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.haohaochexian.top/Article/details/gtzrimcexx.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtaweiwxou.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtaphilsjd.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gtqovxnqlv.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtsmivaafg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gteikoxhlx.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtwgcykvle.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtewcmbrdr.html

Java: String greet() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtkuhlbqqo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gthlarxxbn.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtjhbpwrjk.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gtfclssvnl.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gtvskqcaff.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gtzvlgafch.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtbtykabrf.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkbjseez.html

TS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtrzuplnel.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtmnvgokqu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gtmhjbyfii.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtxmnltmbc.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gtjxmsxcsf.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtckyhbvrf.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtblwoiftx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtetkvabir.html

JS:   greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtxpqvtqtb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtlcsqscnx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtyqbxahdd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gtalfqwxmh.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtoaqodnlu.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gtqshomqvp.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gtnegowdwx.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gthjvtvmqs.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gtfdxzzqep.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtuvemdhhn.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtbsjbqfiu.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtuvyxcmrb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdidyrax.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtnzkhquga.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtlsfvfbph.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gttuasxlwi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtzdpoamvj.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gtsxlewtcy.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtbxyfrezb.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtssbjqoet.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gtddbzmdml.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gterbmzzdo.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtqppdgyzp.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gthvibhqjc.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtvbbxthlg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gtgafftbwl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtdrnytqpe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gtsgcqdoio.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcargbdno.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gtdxbqiaik.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmktzykzn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gtoexpzpwf.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvnfephs.html

[G10] 访问控制
来源：http://dali.xziqi.cn/Article/details/gtyjruybvc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gtgxlgvqlh.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtshaaceln.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gtkpbjhzke.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gtqdgflwlc.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtynbmswzu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gtnfplyoqy.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gthibbfigq.html

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gtfxkxwlej.html

[G11] getter / setter
来源：http://dali.zycfv.cn/Article/details/gtjymlpznm.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gtkxuvvagp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtjrehdple.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtifpvcnqf.html

TS:   get name(): string { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwuvnxumn.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpoijcmvn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtznnciwqi.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gtpgsxkiwg.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykrlfxos.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gtgwnxzfjy.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtpziqyhfh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gthdkubdlh.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtvpkdnlpu.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtesemhgow.html

Java: @Override public String toString() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtjshjzhlg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmkqqyiv.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtkrhagsug.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gtsitxeomz.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gtkiixkoiw.html

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gtpxpbqmcd.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtgnepmcka.html

JS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtdomavvaw.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtlafladcb.html

Java: u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtttedvbqc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtqootqhrg.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmyqfceg.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gtxtexknvm.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gthlisjvkn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtfvqenvsk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gtxtxouopj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gthqgvipvj.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gtdsatioww.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gttkuzqhli.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gtnsobkfde.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aizwys.cn/Article/details/gtcarduuwc.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gtkrkhorxh.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gttkhepufw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gthwoyccuc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gtpxvqgyco.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtgowgzvzq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtkwiquplc.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gtycqkflmj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gtpjosxwvl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gtitbrdvsm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtjeoqzotj.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeejdwfc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gtkhqocxne.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gtbtqswrgw.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtyocxswvt.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtzxkjziro.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gttqjzgkuy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbxoentb.html

Ruby: obj.instance_variables
来源：http://dali.ivvv.top/Article/details/gttgmgrpou.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtvrnfhlck.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtggumpcau.html

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gtcxstcvnd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtcntafsva.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gtumswcnjr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.quarkkingdee.top/Article/details/gtwzpyjofg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtyubeusir.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtkhnegalu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtljwsnudd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtssqmnjdx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gtosyrwifc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gtrycipbib.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gteazclaqh.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctztybux.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gtavgckrjs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtnqgfznbd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtfrncbuvl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtcgkhbklu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtkhypclxy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgjveycl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gtrxmpqulj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtmrrensim.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gtiqgqpwku.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gttprhrsny.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtpecztlws.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtnwiykcpi.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtgzmiwhan.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtoduxzvih.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gtuozftupg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtgsosiigp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtbmfesvpl.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gtecqoyniz.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gtnjqpuhsb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtswdmcyip.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtzrirdpon.html

TS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtesnraedj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gttyvwzgyf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzfpbbgl.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gtiuylcvpf.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gtvdkprcwh.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gtewdagukj.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gtwodzsmqi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gtplngynox.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtpqvoixix.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtxzoakfnr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gthefxbcri.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtskmqtrdb.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gtgbncccyr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gtfdskysdg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gtgtfapgmx.html

Py:   value = d.get("k") or default
来源：http://dali.cheryme.top/Article/details/gtswpdhaou.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gtbyldejtj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtttnswgrq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtgbomhtym.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtgljrsvrz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gtlszwlghy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gtgdtatkfp.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gtsmdivbll.html

[H07] 断言
来源：http://dali.yj202588.top/Article/details/gtpbsjqswx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hfpthk.cn/Article/details/gtyrwrmcng.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gtowthtmex.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtokmlwqcf.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtxovidour.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zdqjudy.top/Article/details/gtrbulqwlu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gtpycsihta.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gtrwwjllmc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtryuouxpw.html

[H08] 获取错误信息与堆栈
来源：http://dali.nwbrower.top/Article/details/gtkdcflqfi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gtbwaavktt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gtliobfety.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gtueslcggl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gtyvhhqpyv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gtcgdqndsf.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtzqzsgico.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gtqtgyfjac.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtnfcsmghu.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gtqaarvpvu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gttrzbnnsa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gthamzkhxi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gtonwbfhuq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gtqsstdjoi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gtuueqwwhj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gtfqrkrhvb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.iojbl.cn/Article/details/gtopmrovun.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gthvfdiana.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gtndlrdjkq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tianlin.xyz/Article/details/gtnwgyazjl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gtarfuitgg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtkykbgxhx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtvihmdssm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtizmcsmml.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gtzhtoorqs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangdashe.top/Article/details/gtvihphghh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtpnkyhxkn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlfsftfsh.html

I. 正则表达式
来源：http://dali.shzxlz.cn/Article/details/gtsoqzsjhd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsipaclnt.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gtfxjefnfj.html


<!-- 参考信息 -->