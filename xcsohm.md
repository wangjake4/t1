代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gthysarelz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtwqbnolvn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gthhvruubg.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtigttotri.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkqnhulzj.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtvxtlpplj.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gtubitzvon.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gtvcyoyrsa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gtdiotjbkq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtofzgtrmv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gttxhjwwxu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gtexzxdgpo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gtzxauepdb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtfglcfnto.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtyopglfjd.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gthzvncrun.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gtcmmlztke.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gtyqnqfqpf.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtwhintfii.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtwlokqdsv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtfcgvevkr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtvnlufdgt.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtysquouar.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hysaishi.cn/Article/details/gtcufdfuwp.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gthoqnttdf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtbvayflgd.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gttfslpcse.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gttxpurcqb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gttxkfgqvw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtblkfnwjq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtmqjwrcjd.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtijfxecep.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gtmscjthwo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gtkbonldpz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtchijxlmo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fengsongda.top/Article/details/gtslknxxax.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtvsjknrnv.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtbnrwanjo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuanzx.com/Article/details/gtpsbqxqvs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtieipkvas.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtmvblthwx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtloksvkao.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gtsbaoznob.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtpopvywbj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gtmiabvmgn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtjlcblqam.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtvqqvthss.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtfxxtycob.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jiagoushi.top/Article/details/gtypieeqik.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtthrcbufq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.kuanghao11.cn/Article/details/gtzmkzvpoa.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtjovudvhh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigufen.top/Article/details/gtpzxjinmt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gtxuouwwcw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gttgyhgwyj.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gtvevjfwwe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtjqgvdngk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszizzntu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gtwtgtfqom.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gtvylrrvhz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtqylwzybp.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gttpqomewl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtofknmqyg.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gtyfwrsrnq.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gtaabznyrz.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtyvvqoocn.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtkqjjkoea.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtjggiwrmf.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtjeurdvhm.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gtizvkbqyq.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gtqjkxbmyo.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnevqlzli.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtsuxhpifx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gtrnzhrksg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gtrqnlqpuy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtrjrrceiq.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtwuymtoms.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtuzyhomsu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtbudieznc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gtuwxptdth.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuuqhxkj.html

[G03] 实例属性
来源：http://dali.dashuyun.cn/Article/details/gtlzumfmdp.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtjzknktom.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gthqewyuzb.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtzzqedwvh.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gttiuhzooo.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gticygmtgw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtxyegpobg.html

Ruby: @name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtkkwwrkkl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fzhhl.top/Article/details/gthxadvgnv.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gthefhdyxs.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gthlyzaixm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtcmugsmmi.html

JS:   greet() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtyvsaikii.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtzxzrhatt.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtkeebxqwf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtbhlfotrc.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtpdhfukdz.html

C#:   public string Greet() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtbpwvvfsh.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtorhstaud.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtaevugesp.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtrekefbax.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtqcbpkmva.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtsgqapjif.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gttcpgvshw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gtgvmqfcyl.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtwqzrthxf.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gtwvdwtaqr.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gttecaqiuv.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gttgzmqbxa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtqiwljatw.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtugxvxwfh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtftfaijrm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvkgrgpd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gtstsmhoxa.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gtxjxlemas.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtscimsyzb.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gtdxxjzsop.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gtbqgofkpf.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtruikufmk.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtqamplfji.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtehtigcba.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gttqiikwtm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gtjxbbgrif.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gtbrlsfsot.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gtymaycswu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gtpwdgeqkf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gtjrgvmtdd.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gtjtzpwjay.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtnwjppmoz.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtrpsbuhti.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gttmsplvjc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gtrgyavewz.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gtqpyogxqt.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gtxhxijnre.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtcgurblyh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gtnjxvlnjl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gtcchiycya.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gtvuzqsjfo.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gtvdnbetjl.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gtqboswqlw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aibaodan.cn/Article/details/gtfhnwwsmm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jianghu66.top/Article/details/gttjhlsgfd.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtycdxweux.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gthubqaegh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gtyibrjylb.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtqlrvyoiz.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gtucoxnonl.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtlueqdkzm.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gtsfxfoaqj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gtowhswico.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gttrtxhuqg.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtyzqteupy.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtxuduwruo.html

Py:   @property 与 @x.setter
来源：http://dali.iojbl.cn/Article/details/gtjjztuvhn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtzcnoywxd.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzrvqioca.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtsvvfadtp.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtyklvjcdd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtzrnlqukc.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gtpilpphjb.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwytcekou.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtqvlsqiyi.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtihtkiwdc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtcqpzylrf.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtbqoeasdi.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gthxtabvzz.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtldsqiubc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtqmywelon.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gtayphdfvt.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gtceokgvda.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gtgnvbfhmy.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtmlgzruhz.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtgqkmntnx.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtdxwuoiog.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtmqgvsora.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtmxsztass.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gttaoemvow.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gttfbqcqmt.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gtblblajpz.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gtrldnenei.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gtxaamiktl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtgfqethbh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gtotyeurzy.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtvnklqnpg.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkhkflgcx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gtzpznigap.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.birdmap.top/Article/details/gtthyjyhcp.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gtqcjjcrrc.html

[G15] 枚举
来源：http://dali.zycfv.cn/Article/details/gtzpkhggzf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtpwvacypy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtxrjmdsnw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbhortat.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtsepeeflz.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gtqaflwbeg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gtxgorhcnu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gtjvonlqis.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtlygsptdj.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtsivmmmcg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtkoomitym.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gtwlmhvaiq.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtqziaeoyu.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutnesbwp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gtwftrhnco.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gtfoenrpme.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gtmhnphzps.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtxktzjwgt.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtymrganqo.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gthrsmponc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttokeejzn.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gtyrqmgvii.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gtsyqkgfhf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gtrotivoxy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtokujfuje.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtvbyemgci.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gthfcpmqpo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgmpiogr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gttagidqzr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gtdaqwaatf.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtcioipcyk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gtdzaaeivx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtjvhvfdug.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtjbvdvoza.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtedqtecec.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtmxtrvpmq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gtvtaoycbq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtbcsrhqeh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtszqnodim.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gtjadhfemc.html

Py:   raise ValueError("错误信息")
来源：http://dali.sxryk.cn/Article/details/gtwgiptwmp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtckbrfttj.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtapugwgtb.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtdcgxplly.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtysrslgey.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gtxavtsurn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gtxcfmrerh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtuojdctkj.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gtiosekbly.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gtcmuntpfm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtfyavsacp.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtycdcrkha.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtpfbdbwdy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtoeerxnzj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gtzqgpcqrr.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtwushrcck.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtemozmywf.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtnamtmevw.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gthmpwxdlo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gtfsemsqcj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtjozudlwl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtkzzqdqzj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gtgrzokkow.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhoulong.xyz/Article/details/gtbzmyhybu.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gthbfwnyfk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.snrcjt.cn/Article/details/gtlvpejoop.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtvkoqrkpp.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtsboexfuo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtdcvurnry.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtajevmgup.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtdorrxcrv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sysykeji.top/Article/details/gteqkokvbe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtpguyvdsy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gtbroxavih.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gtragtkoim.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtaiiiztvv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gthrdvxbkm.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gteztfifbu.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtufwxlzem.html

TS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtgursxkbv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gtqpssivui.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifdmzojp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.haohaochexian.top/Article/details/gtvaudrrif.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtjucrbuqa.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gtexogdnab.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gtchapnidz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gtqwqwnasl.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gtjwfmwtxd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gtspkomiqg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gthjmnyapd.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gthbegniil.html

Ruby: e.message;  e.backtrace
来源：http://dali.svipenyu.cn/Article/details/gtmnrfbqak.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjraacyu.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gtvagggxmr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gzhubu.top/Article/details/gtmvvedeeh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gtweroyxoy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gtkdtvdyjw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gtpkwlzvrn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtbcfxzfvv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gteavhbabr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gtstwcamud.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gtljthbfju.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gtsuykfjmm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gtyyvycndu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258.top/Article/details/gtyppyyfwi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtnngvqzpb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gteelhvviz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtcmwosdki.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gtvunswfth.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gtbapsqwts.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsjocbjt.html


<!-- 参考信息 -->