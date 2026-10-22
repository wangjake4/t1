代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtxzredpyl.html

C#:   File.Delete("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtvjuzzfxu.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gtdyjkdluf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gtdtlzfhsu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gtawwgwuvs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtwskbrpts.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtzxqohphv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fengsongda.top/Article/details/gtzclbibiw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangdashe.top/Article/details/gtwgoqwhzw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gtnzfbvbsz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhiwuduotai.top/Article/details/gtpimkaevm.html

[F08] 遍历目录
来源：http://dali.pengpengdd.cyou/Article/details/gtmwgjxseq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gtbsomzfdi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hfpthk.cn/Article/details/gthoulabns.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtvbfzjqim.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtdjhxadvr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtewovbizk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtdwxfwzas.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gtstiwgsms.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ydzc1.top/Article/details/gtiyjlklmj.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gtdbxalzgk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtfcgfflgh.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtemrypkqm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gteuujvfkf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtwkawzvfk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gturfsbmkr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtbtqetbsf.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtwgonxxbb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtnvflyqts.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtrqjnzlhe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtftiyibsj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gtzaqcnziy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtaubzxvzq.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtltpsrude.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtxeulojbc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtszpyugnn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtvhgotoue.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtcfxezsru.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtcnwhgjtw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtbdsrkrnv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gthmxjvkdf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjxaqdgu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtimhpmqss.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gtsrvknytj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gttqzdwvsi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtrfujbota.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtwezrgkcq.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gtgxerqxsm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gtkrexbdpu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gthiqxgcme.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gtadxbhjqm.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gttumjjmas.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yongpay.top/Article/details/gtwylxfguz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yonumen.top/Article/details/gtcmwybxpy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gtbdmjfnpd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gthqawince.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtargfkzas.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gtohywfkba.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtaaiknfxo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gtelcxlsna.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gthclbbowh.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gtddhrasdo.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtazrloeds.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gtkmeevtlf.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtorecqnlj.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmuogaeo.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gtvdvlmrxv.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtddwimtvi.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gthxnkiwty.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gtcbujcqor.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gthacmculs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtlbiuxlki.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gtwrwboajr.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtqjodumax.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gtyngupgot.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gtgsjsuovd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gthcdjbwqw.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gtbonogrid.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtrfcmtdmq.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gtvlpqoqfs.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtcipliflb.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gtvqjurivz.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gtfysvspjv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gtwbguztgz.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gtnvzyskqt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtzgdiqjmj.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfdxxsrg.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtohkjuqag.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtplcvftxa.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtkksafvfp.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtfixmebzo.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtczfjuypt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtqgdkisxt.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtgktlqzgn.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gthkmgkmcq.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gtgutwlhex.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gtqlfyjsmi.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtkgqsqorw.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gteuykvfbd.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtqmpgtaey.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtjypkntzu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.mhx1999.top/Article/details/gtvhnfnbic.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gthkxvewbz.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtuietlpve.html

[G06] 重写方法
来源：http://dali.yj202588.top/Article/details/gteavyornb.html

Py:   def greet(self): return "admin"
来源：http://dali.birdmap.top/Article/details/gtgchgeqxf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtordgyqtq.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gteyxrydht.html

TS:   greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtwuuockkg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtdulacrxk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gtmgvewpia.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gtlcviygbm.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtlzmwckrd.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gtvtvmurje.html

Py:   super().greet()
来源：http://dali.pycfn.com/Article/details/gtkfbhzyle.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gtgpahxfrv.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtfvmdlidr.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtilzjzzwe.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gtuyfcmktt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cdnleiting.top/Article/details/gtjthtpxap.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gtgtavczlf.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gtrmpsjyxr.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gtoczhkiss.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gttyapcuyn.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtwomblzeu.html

JS:   static f() {}
来源：http://dali.quarkkingdee.top/Article/details/gttowbkhaw.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtmzgkxuol.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmucehmmr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gthqwpvazu.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gtrckzqbnp.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gtqdjjimru.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gtwxzvpwbx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtlrvdrkyf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzdxpgdeg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gtjisvykov.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gtozkpwaze.html

Java: interface Shape { double area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtnvbxwxpe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gtzzzceytq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gtojbrbsiu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zycfv.cn/Article/details/gtsfkrllrw.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtgxjmkpmn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyrrdhyq.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtgiqobijh.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gtfsxkddwc.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtakorsibq.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gtuhhhudol.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtnsypkgii.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtwtdgaggl.html

C#:   public / protected / private / internal
来源：http://dali.yueranfly.top/Article/details/gtcwaabbfg.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gtbrqndpnb.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gtrglrdcpj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gthtkugvxi.html

JS:   get name() { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtmlohdqzo.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gttairuiya.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtaeekoxyo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtxikaltdd.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtlolqfyjo.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gtmmgnciuy.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gthmjvfapk.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtbxraditn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtkocbqatj.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtxufixmlt.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtcfhxbrcj.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtybibsarv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtxohzjwwx.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gtnjisoacr.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gtmyhqceky.html

[G13] 判断对象类型
来源：http://dali.hammf.cn/Article/details/gtywubnpbn.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gtsmvxdgqj.html

PHP:  $u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtzuwyvpni.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtauguduwo.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gternmusnw.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gtorbmqtll.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gtfiaqjzle.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gtqfbstrhj.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtvjduevko.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gttmsdwmcw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.smart0.xyz/Article/details/gtibubmmay.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gtzzwzgdov.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gttqxojiht.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gtejqyjizy.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtwhpykklq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtsmciwggs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtxzijbvrf.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gtbcyyxuqx.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gtidskeyfx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gtjgwscybf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtggugvnxw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gtiiriupfj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtuwczcxct.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gtxuxtmrzw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtccqtonls.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtmxlbvhzh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtsshbnlsx.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtjklplkyj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gtgjglyhph.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtanwgeeop.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtakonqxxn.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtlhkkzoso.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sxryk.cn/Article/details/gtkauojxck.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtrrqhvsmt.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gtgieflulr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gthgwubiui.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkfzwdlpw.html

H. 异常与错误处理
来源：http://dali.andypj.xyz/Article/details/gtxpqjuejx.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtkybdtriv.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gtvodnlymq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtfmxzoemq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtqlaeawpk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtwfuhbyip.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtpuxucwke.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gtqzvmeeqw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtoyvqejtb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gtqberhrss.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gtaqcvohak.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcimxrdcw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gthpnjzkwj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtebxakxoo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtmmhkgqlg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtuevyacvf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtgvujxcec.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtwrxgvpwv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtxouavrcw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtlqtjlnsz.html

[H03] 主动抛出异常
来源：http://dali.cashguo.top/Article/details/gtxzdoohmz.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtocldnmlm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtattgztir.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtepgbhggj.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtejmogkwz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtxtwccxlm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gtkxatamcp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtkxypppko.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtkxwafcrk.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebmwxdgm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlijfehu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtsawjulcq.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtooqqpstj.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtrdnmjdek.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtbafsizjp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gtjhwsjswp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gtifpwrruo.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gttxogfkoz.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcblistvl.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gtcoctqipt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guannengcc.top/Article/details/gtfuuskxvl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtimygzmda.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtlqxnhill.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gtlqmfeaha.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gtpvydiahf.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gtwrycnulg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtunvxtaom.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gtjxshsbok.html

Py:   value = d.get("k") or default
来源：http://dali.hnqzz.top/Article/details/gtpbbnrqwa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtwrghbwjf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtxmkszdyk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtzvkzyqcd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gtwqiohyjn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gtdloqpowv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbkluwxb.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtuhalucdv.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gtpxchkulw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gtyjzgapho.html

PHP:  assert($x > 0);
来源：http://dali.xuanzx.com/Article/details/gtrtayitst.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtdlchuncx.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtqkcwuxab.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gtfjjoxczx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gtcgozvcsm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtikoikorx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtnwpcrppj.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjglgcixw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gtsijimsvd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gteltnbsqx.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gttlqaglry.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtsdjhjwub.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gtscrsqncf.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gtncpqgery.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gtcmngqhhk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gtupvfyfcz.html

[H09] 带错误码的异常
来源：http://dali.9152youxi.cn/Article/details/gtfmxqxada.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.smart0.xyz/Article/details/gtgyzljicf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gtqgxfvyuk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuxming.cn/Article/details/gtqdmmanop.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gteomlswbe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.snrcjt.cn/Article/details/gtkacpnaeo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gthkeulnza.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gtlhbvnrkt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gturgvwtmy.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gtfemnzwbl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gtvnxlzusp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gtpquprufb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtfufcemjm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtjnlekdeo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjjswiey.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gtqejxkdub.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangdashe.top/Article/details/gtvkperkxl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtkptdqrrq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxmznbwzh.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gtovroonyn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtjvwnsqyw.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gttgnsmanp.html


<!-- 参考信息 -->