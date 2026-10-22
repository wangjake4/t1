代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gthsynuxhy.html

[F06] 删除文件
来源：http://dali.redwolf501.top/Article/details/gtvrtrduoz.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtiaejpclm.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtmxwvfhax.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gthzdbinlg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtajhrrbde.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtvdzaerpp.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtwmhzsbvu.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtzewbprel.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtbactxyav.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gtyklupxis.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gtichujhod.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gtqexcvcxj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtdaefcqje.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gteqkqtdnh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guowangkeji.top/Article/details/gtyyinogat.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojokwlbb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shzxlz.cn/Article/details/gtksmakwmb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fzhhl.top/Article/details/gtnwhpkype.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gtsnfgprwh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gtxnrbaxvh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcqovswor.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtoxcpqdaj.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtjrgsrorl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtrwannmpz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.birdmap.top/Article/details/gtgbhcdjqe.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gttsjhhbag.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gtglrgdemw.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtculzvcpj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtwdmarxty.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtlmmrwvzn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtneqbvueg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtasmobzxh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtczkmrpyi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtsgeivhha.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtdxgajrxr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtqpemukso.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkncttmp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtrxrvmgao.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zdqjudy.top/Article/details/gthddinxdm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtolyfkuzn.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtkvebtnrb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gtdymzxdte.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtrzkgprms.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtvfogpfpw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtnzkbgdfq.html

[F11] 复制与移动文件
来源：http://dali.chenlongwang.top/Article/details/gtchttdbhn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtzwrnpwvm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtwuqxrfqn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtrlvhsayx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtjdgzicnb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyglskavs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtoixxctjk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtgdjmixih.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gtolkrjllz.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gtzdruntmk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtwnibkziz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gtgoevbwlh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtbbkemdos.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtukfzbkbh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cucudq.cn/Article/details/gtiumahfwr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gtyxoodjwv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxldweyzt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.snrcjt.cn/Article/details/gtexczawsy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtoneviatx.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtbpptcaph.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtaxwxuxvg.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gtmivepiyf.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtosdicnjg.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtbixaizjn.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gtmsjebklg.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttepuapje.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gtxsfuzxcz.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gtduonggqj.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gtqetibdpf.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxlvcksnj.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gttlvottme.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gthtolwiaq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cqqwz.cn/Article/details/gtuutycwyj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtldnlyrqp.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gtxlvedzow.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtstniavpz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtwlcgsqko.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gtclslrxho.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtuodcwbqj.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtxkycpswb.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtazlnoume.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtsmkbueoq.html

JS:   this.name = "x";
来源：http://dali.andypj.xyz/Article/details/gtnmdqoywx.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlgzwrey.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gtiqgbjnin.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gtgqwvopxb.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtdgckswfx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gtfsxtsfbu.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gtfkpmipyn.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtmazbynah.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtepcyywet.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtqspxajzv.html

TS:   greet(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtnanmhbjx.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gtvlsfglaq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtoqqtuyxe.html

Ruby: def greet; @name; end
来源：http://dali.mhx1999.top/Article/details/gtxmpztbii.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gtelkyzvtf.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gtayhetelx.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtwnlqmsqu.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtsfwlelrt.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtaanbgfox.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtsxhbftix.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtsphhjwtu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gtyxrgqlmo.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfaufkdeu.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gtcdhksfiy.html

[G06] 重写方法
来源：http://dali.jinqigfzy.top/Article/details/gthduqlkjk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gtdoewidxu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvtbmrmya.html

JS:   greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtlcyynano.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtquqryqhy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtusxgpcoz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuxming.cn/Article/details/gtwcbwhpkb.html

Ruby: def greet; "admin"; end
来源：http://dali.ybcxt.top/Article/details/gtcnswqqiu.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gtnawvlofc.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gtiiocvzge.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtrmcoaigk.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtwjwawyex.html

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtctfouzqh.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtgqszsliy.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtlqgcpzjd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtqailfngn.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtsydurzrn.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtgehfaybb.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gtquzbywoq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gthaabuvcy.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gthhwsgske.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gtjbzainfj.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gtlwgcksza.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtiabuhehk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gtbotzulda.html

Ruby: def self.f; end
来源：http://dali.iojbl.cn/Article/details/gtpeuyzbhh.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gtlhmokryx.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gtmsfyalqc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shangyingyoupin.top/Article/details/gtwlysnebp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gtsphkgosq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jiagoushi.top/Article/details/gtyzddmoky.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gtsodsoxsg.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gtlcgzzdjg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gtjgftjbmu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtbfldcsxu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtpzuusnzp.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gttczpdcla.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtjzkpeqla.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtvbfilrmz.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtrhgoelod.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gtcmmjkkcr.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtaxhprcmr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtudnfskbi.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtwkfauiog.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gtbejjufmc.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtybikiuuk.html

Py:   @property 与 @x.setter
来源：http://dali.9152youxi.cn/Article/details/gtrkbzniom.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtsxxhzxts.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtqjsjdiej.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtwpcfwjuj.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsaoxpcdr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtgwziproh.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gtkarswsdo.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmaelkgix.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtfdcaquol.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtjvvomfzr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtjjinnrsn.html

JS:   toString() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtbcvvxobm.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtwdgvhmvu.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtheeffnuw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtyhaaunoj.html

Ruby: def to_s; @name; end
来源：http://dali.cheryme.top/Article/details/gtxklifskc.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtzfquzomd.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gtexiljwvp.html

Py:   isinstance(u, User)
来源：http://dali.jianghu66.top/Article/details/gtzgyvffyd.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtfjowbrjq.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtpylkdkla.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtybgtjmae.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtcxejhnub.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gtapttcgno.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gtjlvuzdjf.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtvvzhuxan.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gtxbspxohe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtupnsgsoj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gtptvpepga.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpebwvlrc.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gtbkxsbqqt.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gtuaiozvss.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmlgqlxg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtwlyxjvfi.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gtnfebqfga.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gtxufegypa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtzgyctbha.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtmrbvaaxi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.redwolf501.top/Article/details/gtwhgsgbyx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtwsuikuon.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gtqplanrod.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gtqrmolnif.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gtolzqyagv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtaiuzwsno.html

[G16] 对象转数组 / 字典
来源：http://dali.tanke756.top/Article/details/gtevlkoxjv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtdkpaigjf.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gtvutomojg.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtzzorgebu.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtqmtlbeqp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gtfekftgbc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gtaziheyfh.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gtheyqkbzb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtqqknvsqg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtpabglchf.html

H. 异常与错误处理
来源：http://dali.vqdsnc.cn/Article/details/gtkpjedamk.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtoiipsfsd.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gtubcvzmmi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gtlxprffan.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gtssdjwles.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtwddfabsq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gttjztggma.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gtqvscybzt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gtvgcmtexa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gtclqvpzen.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gtpwxtjnaa.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gtvdntzwji.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtwxvcrzau.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtpkdrmeuu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtzcyuphwg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtamxefffz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtctcbolpm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gtfrsahqef.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gtbootsjek.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtgwmezbrw.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtwowljjli.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsiraljkw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhyxkrpa.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtsfgkdnrw.html

TS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtdqvdzbzl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtbplbzofk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xylfe.cn/Article/details/gtcqzwnbwd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guannengcc.top/Article/details/gtcqycsdeo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtbitejifx.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gtqjcfnivc.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gtlrbwzcps.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtxawghxhr.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtejmicbnl.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gthzkorutn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtvndbvjna.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gtakdefkba.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gturixazfb.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtineizphq.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtsoxxgvbz.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gtrkylfwpi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gtmaldoqpf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtppnvsaas.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtcrbvztvx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.snrcjt.cn/Article/details/gtuxyrsheq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtrjxxrjqb.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gtrtokytge.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gturhjmitn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sufxvd.cn/Article/details/gtnagkwibc.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gtmjybznne.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtuxjgcoat.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtqomrhvbn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtzhtvzkmu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtwjqzugyo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gtbbrzlylt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtrrpwutym.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gtvridnfhu.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gtghkmduzw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjewwkfix.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtctwuaaan.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtgliofkjg.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtlgnpvqxb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hongshengwenyu.top/Article/details/gteguaultt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtmixkpwus.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gtxmqrgtov.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtceyqatqj.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gtslgkmqjx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gtmuogbhar.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gtnqlmlxrp.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gtmzcmggji.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gtgpdtdhiu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gtyhitscxl.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gtnhmhfxvt.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gtovwhuhlh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ybcxt.top/Article/details/gteaotxxte.html

[H09] 带错误码的异常
来源：http://dali.gaohongyu789.top/Article/details/gtmdntbzmz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgfzy.top/Article/details/gtqyqgjxhp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gtadagzwok.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gttjxmejrf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtyfzqcjaa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gtpqhorxze.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtcuyljsig.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtqqlnaenm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gtpljmmwvq.html

[H10] 资源自动释放
来源：http://dali.sufxvd.cn/Article/details/gtmrmlgbbh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.vqdsnc.cn/Article/details/gtmsclfabf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gtnsvzzgsj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gtthwtrshw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtstlqwrtq.html


<!-- 参考信息 -->