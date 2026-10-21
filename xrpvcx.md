代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtsygfjitr.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gtnugfaceb.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtfcfweefl.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtllwbrbva.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtdekahroy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtfwuskmos.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtmhfewqxd.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtsybzeuho.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtfmonjfbm.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtgahwuzho.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gtpxuwhjiu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtbjmmcayl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gtuxdztqpf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtookzcxjd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtdahuidfo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gtaybsdiin.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gtfkttqxzt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gtvjnxnzev.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gtawflhyhd.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gtyfnqwevi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gtgzuyoaym.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gtvhumhguu.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtspmrdbdx.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtjhmraepu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtcuavmuev.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtrjywpole.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gtzphtprfc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtfztceniu.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gtyehtxrmn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gttvhisyvw.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtrcwyjfmy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtprqpjfbv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtrkxsaeuo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gthsjqcbqi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gttxffwfdw.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtbiguabpz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiijlxurs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gtyufoeunc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtjnmdncbc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gtegbkgmde.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtwdayyvzz.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqgjohdhd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gtcaqfimyg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtpfumyxrb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtpvpkfqnq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtqdjxnesl.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gtojivjuop.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gthounyorc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtboaxnmhb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtuvxwyfzj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtrfzgniaq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmevcnph.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gtrblrjfvx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtdycrijfc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtyxbymdct.html

[F12] CSV 读写
来源：http://dali.jinqigfzy.top/Article/details/gtkrhjggdp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtovcpqqlr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gtmjettzwu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gtypxbmesj.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gtzoqxuftb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtknfhvazm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gtlohtvpbk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aibaodan.cn/Article/details/gtxnzeqoiv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gthrrkqnhm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtyztlpttq.html

G. 面向对象
来源：http://dali.zhiwuduotai.top/Article/details/gtbeqemkzv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtywyoknmx.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtcxarzhih.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gtjuezxrin.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gtzxeogdet.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtqmrwvdlw.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtjjwivwtv.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gtfzlgzrnl.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtbpfdjeid.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtbrjznrtu.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtotyygvkw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtqlhbvvpc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gttkjsfoas.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gtgdaqhsaj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtnafpmqym.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gtzlspscwu.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtansgbesa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gtbnlraqha.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.smart0.xyz/Article/details/gtmrlhlmqb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gtdypuwiby.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gtkwioyzbh.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtbzvnztzu.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtwljgcwob.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gtiqfstimp.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gtstebqfbg.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gtgyswnrdw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gtodopvnyw.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gtypnxxpsn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtqayvglze.html

[G04] 定义方法
来源：http://dali.cqqwz.cn/Article/details/gtxkekonud.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtvuaqzfet.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtdqbclbjs.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtltkdxsqz.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtjvucxzop.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtocifyalv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtlrpoquwa.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtivbaioko.html

C#:   public string Greet() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtytxnejuk.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtphkvbeok.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtsesdludv.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtsrfzysuw.html

JS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtisnqxdjt.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtrsrilpuk.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtfzqevibi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtxfkqamfo.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtunwiqlnh.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gtdwycvqrx.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gtqptthqvf.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtwcevhduv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnpgycua.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgmgrhbaq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtaxvypcvt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtcbtpfnbw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gtkzjngney.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gtoncnpgbk.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gtfojfuauh.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gtcvbwcprd.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gtiqaloobu.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gtkstudebw.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gttvflymnr.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtvduavhdy.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gttstizczq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtpchfknwo.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gtceedhpfq.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gtpnjuougx.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gtcjiyhrlz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gtelvzwblh.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gtdygraxub.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtvcrgrojs.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gttafyxpmh.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtusyaxfvu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gtlbhnkmeq.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtjdzcbrce.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtjwjagqsu.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcxueysb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shangyingyoupin.top/Article/details/gtpqkqogqh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gtkfqutvsm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gthzbyppan.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlheubkwe.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gtwhcebtgm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gtobwstkod.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gtozbijubt.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtdohmerjd.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtfmbzliow.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gtccvnqyhb.html

PHP:  public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtfornqlrj.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gtmlelqnxj.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtkbphkrxz.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gtnphgqgys.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gtcqjugaec.html

Ruby: public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtiffjisfh.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtsagmepbr.html

[G11] getter / setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrimgmbob.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gtflfypsps.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtxwlmztil.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtbdhyscuy.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtxghttrpi.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtzuajnplz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gttrrwthig.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gtcwornrdd.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gtnwgfvpip.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gteepuleoi.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtscncjuyc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gthortcatg.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtpgiyyrbb.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtummopzlu.html

Java: @Override public String toString() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtvebqjjxc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtrxryyexa.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtcpyqpvhz.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtcjhzdiyi.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmeytqkq.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gtuiphezcj.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtjpnqryvs.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtloshsylk.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtzmikilag.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtkbmbkiws.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvimgxsi.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtjexlhogs.html

C#:   u is User
来源：http://dali.9152youxi.cn/Article/details/gtdzevawfu.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtguqzlzsf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gtjepigwhm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtrbnvclvk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gtrskpgbre.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gtkwdjggcs.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gtscrlseln.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtsoeycdsr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gtakwhmzau.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gthkabdeav.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gtpkgpcgfp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gtfliqdtav.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotkmpzjq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gtfvrqpltj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxqlgkkd.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gtahzmtfzq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gtcmoetyqx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gtqibbgitl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtntcfdtbl.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gtpihgkjgg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gtihyhdnyw.html

PHP:  get_object_vars($obj);
来源：http://dali.shangyingyoupin.top/Article/details/gtzdshijcs.html

JS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtbtbqunjy.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtuodzjity.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gtztwmhwzw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gtjmqyvill.html

Ruby: obj.instance_variables
来源：http://dali.xziqi.cn/Article/details/gtwueumspp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtkggvkjwo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvfzmtvvi.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdtnzkxm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtlzstrejk.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gtlrqnelwi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtgxjlshvd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtpcbopbgd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gttsocjbud.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqfrkcnf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gthzqrxocu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gtyytfsuvq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gtshihexlq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwovojzaz.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gtltkrdizj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrdmrurh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gthrlbivcb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtugywrgqw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtnkzlbliw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtlcwqowju.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gtxhekhkji.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gtiywfzmea.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtykehsemd.html

[H03] 主动抛出异常
来源：http://dali.xuanzx.com/Article/details/gtbetachyr.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gtktpctklx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtctllrusr.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gthxxrtawf.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtmhhiplmy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtjafokzxs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gtuiqxzvgi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.snrcjt.cn/Article/details/gtfguntprr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtpmnfnolc.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtzcavpsno.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gtabesgukp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtukrgeink.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrycplmm.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtwcjfepsh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtagpbquax.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowrkliql.html

Ruby: class MyError < StandardError; end
来源：http://dali.jiagoushi.top/Article/details/gtikhtizlk.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gtveopdjvu.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtcmpjhzrc.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gtcjnwszxl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gtytsyejeh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtqozdkibr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgypwagtc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gtpjrnjuiw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ppjwa.cn/Article/details/gtwpspcfpk.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfweqvwqx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gtrwvmyxmd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gtwtizhayk.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gtyfkgpimf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtxnynyuml.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gttujtvfnr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtsgymqyak.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuanzx.com/Article/details/gtymszhbqq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gtamngchsz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqwiyrzs.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gtkavuqwth.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gtjjwyukwy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gttywrsmzs.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gthsjwytbk.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyusjnipp.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtxxnwrcud.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xinyue.icu/Article/details/gtsavlufqf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gtiwsijxgl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtxjcbvdot.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtaujgysxn.html

[H08] 获取错误信息与堆栈
来源：http://dali.9152youxi.cn/Article/details/gtzuhktoxf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gtuzrnidki.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gtsumaijxe.html

JS:   e.message;  e.stack
来源：http://dali.tianlin.xyz/Article/details/gtthlumwwz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gtlnrpnkem.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gtnhixriwv.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gtgcuownfj.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gtffipufed.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gtcizoovbi.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gttmoiddjs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gtanabkjkd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gtobynpqfg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuetiantiany.cn/Article/details/gtpnsqutnp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gtmxcpzowk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gtrilyimfv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xziqi.cn/Article/details/gtuzrffoyk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gtfbkjphiv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gtkzovxmpf.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gttigpxlcb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gtvzndkziu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hysaishi.cn/Article/details/gtuosmmhuw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtxljxhsbk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtblxupfbe.html


<!-- 参考信息 -->