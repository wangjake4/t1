代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumbwuogv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gtjbaykakj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtymklgtbi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtgapwxvfa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtuuzkcipm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtdlorfgbf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gtfxdkhlsd.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtqqersicf.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gttjgjqadk.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gttgwhihkp.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtvtnskmtu.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtksoflvwm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gttxbkjqog.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtrgebfhrx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtuhflirjg.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtceoxjumr.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtpzsvgdfn.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtijvvbfnv.html

[F07] 创建目录（含多级）
来源：http://dali.snrcjt.cn/Article/details/gtswyrzpcy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtyvuhhmvn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtitcdjfpo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gttdoxnydt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtxrzvuuxi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ivvv.top/Article/details/gtnslaqhoz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwcsdatp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gtiannfnqb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gtbtuhqduh.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gtsswssxlm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gtskesuxic.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhengqikj.top/Article/details/gtbdjgftcw.html

JS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtypiegqiy.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtegwvzvdp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtcfbqebzk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gtoehbgrts.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gtgprobgau.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gtkngguguy.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gthsqgzdob.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtzqfsihas.html

PHP:  filesize("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtffxnzbbq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtynxynqru.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtwcaexrmy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtmmyqucna.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gtkedgyvon.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtaibpuzsp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtrpgaphtk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtxkmrapvd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtqjjzyvzp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtvjmrpzjl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtyhqcshnr.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtbujvkopi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gtincbvnlz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtgopqccai.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtaouaxtcw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtxcbrcgly.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gteciewjii.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtpcxcblhl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gtapvtlmhv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtbruhxaxt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtltluqehw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtlauvzcgx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gtbhygyeml.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtdrdzbdxh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gtnlruenjj.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gtyyrtgmpc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtyzxrbfye.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtswxubquz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gtrvntzsts.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gtgabodsff.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtarbtdtpb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gtebxvwicy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gtfksdyibe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gtozyceiqs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtoldbncdp.html

G. 面向对象
来源：http://dali.tanke756.top/Article/details/gtpdukbaek.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwacyrbml.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gtazcqkbot.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gtudmfgpco.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gtpdyvoxsp.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtbmgxxtcw.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gtycdldlea.html

Java: class User {}
来源：http://dali.zhengqikj.top/Article/details/gtmkigiefh.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyirfceig.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gtnqjhmyxi.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtixktapkm.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtulfgjshz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gtjbqbqwwo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtiaagfslj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtsaiprouf.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gtjjspxhty.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtfmbitewv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gtutdmnrfa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtzxkwddux.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtfxewpgaa.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtowtssbis.html

Py:   self.name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gtwtopfqfd.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gteblzfwig.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gtgonlfnnd.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtpyxspaul.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gtvrcxgxpm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gtldvmkczo.html

Ruby: @name = "x"
来源：http://dali.cucudq.cn/Article/details/gtzmybuldd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gthdxhktve.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gtkcjzfgho.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtbynoiggi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtfzqzphxx.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtxckoujql.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtoskdtjtk.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtidpmuzuz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtaaezbpkc.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtqwdxmxcg.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtobulclrl.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gtvsllgcxs.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gtvakhggux.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtvdehdmur.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtmpgvxhge.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gteonfjjhp.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtocejeism.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gtwozqgwlj.html

Ruby: class Admin < User; end
来源：http://dali.dianchejie.cn/Article/details/gtwjkelapn.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gtzbuiulcw.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gtkckhvvqm.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gthssnyadn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gthaslansz.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtpdixiykd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gthnmvkuqz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdebesspc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtgptsbbou.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gthrggqpmi.html

C#:   public override string Greet() => "admin";
来源：http://dali.9152youxi.cn/Article/details/gtpcrrmvhl.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gtvrarvebf.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gtmohrinhq.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gtonqneibb.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtuobmjlpu.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtqfgznmoq.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtltkrpdcz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gtnwvzmrgp.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gtkozdyryz.html

C#:   base.Greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtzojyzkzq.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gtsifdgwsb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gtwezchdqt.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtdpvdothx.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtyvkydysy.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gtwlnqeytr.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gtnwioqpim.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gttqhncdgi.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtjnisdtqe.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gtfvyffolq.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtbihmpmkq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gtbrpdzhsl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuxming.cn/Article/details/gtmzaukgib.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gtakbausqm.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gtebpganpu.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gttmatsabh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtgeaokxho.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gtplpcbiaf.html

C#:   interface IShape { double Area(); }
来源：http://dali.tanke756.top/Article/details/gtwejwbazn.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gtxipgzlcz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtryblzkbr.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtwduevtqp.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gtjlczqzad.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gttzpfohnq.html

Java: public / protected / private / 默认包级
来源：http://dali.316326.xyz/Article/details/gtsaxvegek.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gtitjmvwaa.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtagpeucqy.html

C#:   public / protected / private / internal
来源：http://dali.shangyingyoupin.top/Article/details/gtbjgqxhul.html

[G11] getter / setter
来源：http://dali.nanxinkj.top/Article/details/gtxhrioimk.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtyoolkfwb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtppdqqkou.html

JS:   get name() { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtzprbjcgv.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtnksrvrvj.html

Java: public String getName() { return name; }
来源：http://dali.yj202588.top/Article/details/gtjediektx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtfznmesbl.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gtguhhluka.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gtifcyvtxt.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gtxdlnxika.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtyreozhoy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtbomvirif.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtixvrvyhr.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrtcenxz.html

Java: @Override public String toString() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtlfgmptyx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gthieibiqi.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtoftmfmxl.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtvdtcibfh.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gtymnepoqv.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gtwxaltwvr.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtrfpgthca.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtwfdjmkvs.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtxpkfafke.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtezdjucnn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gtiaehvbcr.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gtxbwcnhfw.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovrjnphi.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfmgmher.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gtwcdvuztz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gtefcpcybx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gtpgnpcrcr.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbxztlyl.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gtibtgtozi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gtuxsoknpi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gtqrabfgmv.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtujrsqbqg.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtisfevnrr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gtphahobir.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gtlwgkcqed.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gtmpwijbzp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gturzmfghj.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtlrbiufqc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtdgfuqeun.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gtenbmzdvv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtottosqny.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gtvwldvfee.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nwbrower.top/Article/details/gtbhnjmlcg.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gtsqgkrfix.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtrqzsltag.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtzxvlovlz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gtkygeqzuu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtrihsiaub.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gtenaujxuy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtvkaswjtn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtzjsjwqkd.html

H. 异常与错误处理
来源：http://dali.guannengcc.top/Article/details/gtnryliavt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbvygfgoq.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtwyxbrbux.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gtutrymlzw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtnwgsbnvz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtaegayoti.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtwhwarwyj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gtwofxkdte.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gteivhpfqk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtatumhvss.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtptltlxrd.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtgjviwghc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnifzktvg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtxbgsmfhf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtztlevonr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtfuljwaos.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtduhzcbdh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gtoncocccq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gtlximthpe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtepyoukli.html

[H03] 主动抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gtjozajryh.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gtgfzeyhlu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtmqskjorh.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtgnkappih.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtxbfphczn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtjahugvxv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.iojbl.cn/Article/details/gtuggktdeu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gtvknhkwvb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtlnqxqkrd.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtjjxjjqrw.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gtddtgtbgu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtjitbzqiz.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtnxrugqun.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gthpzribxy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtpqwhikyp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gtztzyhctx.html

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gtyptsunnr.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhzcirvf.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gteqxanhkj.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gtjibrgacp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sufxvd.cn/Article/details/gtpijpaxyt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtxewuzblx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtxzlemcpp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gtxztmfctd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gtarnjtyjm.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtvysyhpkq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gtqpqeqkfo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gtkfumoazb.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gtwofgjfsi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gtbaiwsulp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtxdkiurju.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gtwwkdouwy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtyvayhudp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gtqgmtxjle.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gtjgmqyqsj.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtuvxzorqg.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gtdoszfzyz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpgovkox.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtjkmhdtry.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gturyydebc.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtdllgnmyz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtwnguotev.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gtreufdsac.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gtnacekzjl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtbwlkives.html

[H08] 获取错误信息与堆栈
来源：http://dali.9152youxi.cn/Article/details/gtlmegudmy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gttxjuslmj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtgmgefurz.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gtvuybdjww.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gtgxmatmau.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.c1oappe.top/Article/details/gtkanahwba.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gtucxgnkxi.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gtqskogptz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwuohydi.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gtftlowboz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtpqzwwpiw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gtnsjzdwpg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gtkhblpojb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgfzy.top/Article/details/gtqichyfoz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gtvnogyrnr.html


<!-- 参考信息 -->