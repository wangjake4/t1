代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtkepxlfrf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtbcgzjnsb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pengpengdd.cyou/Article/details/gtitiwdxxw.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gteoeenybm.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtjuyufrpg.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gtcdxwegrs.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtpdetqnwd.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtovizphjc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtqcgpvaac.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtcufjblbd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtohpariib.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gthnkzmykd.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtpvcnxwxd.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtafskxffz.html

[F07] 创建目录（含多级）
来源：http://dali.yangfankeji.com/Article/details/gtlmncolze.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtjmwxethm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ehwqpu.com/Article/details/gtvfucxoim.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtigybflcd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtystxfphv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gtgcveknza.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtrifndbca.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gtiqhhozqm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gthfljlnrv.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gtphfyxiaj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gttqyvlhgi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gtqelbxrjb.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtmctcvmor.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtlfdeobab.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtkwnziexs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtoagjgtrn.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtymtpzjog.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtgiqskblx.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gtoxoqszud.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gttxgifvyc.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtvgdvzbsy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtfjmxpliv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtitryziko.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtkjmgoket.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtugqkwlot.html

Ruby: File.size("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtzkaaktoc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gtnkovnnoc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gtndgrktsd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtdscdhyxg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.birdmap.top/Article/details/gtcqfnboqe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtaxdwtsoh.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtpijpthag.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tianlin.xyz/Article/details/gtzcusbudh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtbzpxgajs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtsdssptfx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtrjugfvzt.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gtkczdsxvh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtygmndmsz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gtjettcncl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtriisrcbs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtetkygaaz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtkmxpnhcw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gtyfbuihwg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtsjeugmkx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gtfjanqibt.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gtudxclpbw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.9152youxi.cn/Article/details/gtpxwexcjt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sysykeji.top/Article/details/gtmzskoeui.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtjtdsltfs.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrawqxuox.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gtvieocxdk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtuwffmpen.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gtdfqcoxld.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gtlvqxkxbf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmlgkdlca.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gtbmkiyvvs.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtixvlhgab.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gtpiylzqre.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtkvfduplf.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtduwhrrvx.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gttsiajxfm.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gtgkzxblcb.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtnrnzllmi.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gtmanmwjqk.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gtyutsmnof.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtpofqobfa.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtyeuinrhl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gtlolnfbsm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gtkyabuqae.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtgpzdlqfj.html

TS:   constructor(public name: string) {}
来源：http://dali.wangdashe.top/Article/details/gtisjbmyup.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtpovdzjle.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtnokwebks.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gtbrobvmvr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gtitbzwjyb.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gtghzlxvsn.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtooeiyzxx.html

PHP:  public string $name = "x";
来源：http://dali.sweek.top/Article/details/gtizzigiko.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbotfnoc.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtagqweekv.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtysdaqfbf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gtwupilezh.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gtsgwrymfa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gtochotcle.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gtxwzinhit.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtvxjzpxhw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtvvlrjudi.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtnkrkfivq.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhkmxpfj.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtuikuikna.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtekzdrerl.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtqesapybp.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtqaliapaw.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwnplqqm.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gtkjuywinl.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtovjjxbaa.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtpreekahx.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtsukgahez.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtjnepbpvr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gthhavqlmv.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdeqfysqm.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtgjqwqbvo.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gtpmkrkkfx.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gtggajucru.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gttocnbpua.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtvcswvstp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtkzmtglqd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtkhlinzvx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturhbcwes.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gtaxkzkzyz.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gtftbkxwuq.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gtzdjkjfpm.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtvdmasmnw.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gtoepazwvc.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlqdlhpi.html

TS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtikteszei.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtwfaftnql.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrutthfmv.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gtoohaomiw.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gtqwdozlvx.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gthxzizfqz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gtrucoufty.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtnwmdgshh.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtabtndeqm.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gtcfzkttfg.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtfmpupcgv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gtawhnoedf.html

Ruby: def self.f; end
来源：http://dali.chenjidiqi.icu/Article/details/gtjnhwopli.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gtjrbvjrrv.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gtyiestwcw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gtzkpekqqh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gtlsgmgdmr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtspahgtmw.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtcoqosolo.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gtbqslpzvo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gtwueuxdii.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gtoizzjjrv.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gtjmfpxaak.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gtaejcbffz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gtdtmuidfs.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gthkflwsez.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gtadvhgwzf.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtngafezka.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrvunljl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gtfccneicg.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtahgvtmsq.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gtbsfjardp.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gteneoqfum.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gtvmecbkge.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtxyebjqbq.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtpzdifbjh.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvlmvvuuz.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtaworbjyc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtifmgakvc.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtoiifomte.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gtmrmfujwz.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gtkyoxqxbp.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtierjtxrv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtgzgcdqsk.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtfopyxubt.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzdguegpi.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtpejndvxs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtsrrbrdmf.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gtwgppukki.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gthyvenfll.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gtukmqdtxa.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gtmlkusskf.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtergntybx.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtofvqgwzc.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtpyrbnwnr.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtuarruroc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtthsoekeb.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gtfebcwklq.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtkjyxsvdc.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gtfsmyhhwl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gtsfgfmvnd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtwkqvriti.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gtybbjibqn.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gtxgjtquto.html

Java: record User(String name, int age) {}
来源：http://dali.yvedp.cn/Article/details/gtkhfjrbkq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.0kj1m.cn/Article/details/gtmkzvoofc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gtxeysucxp.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gtsnwynywl.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gtbryonmnp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtjovdvbmf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gtzabcnvdv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gtryybhggk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtweqwirnm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrckoxqkw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtjhckayly.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqyhnlho.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtegainvtr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gtdtdgbxna.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtlfuhlemu.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gtsbdwhvtm.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtyrbqvars.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtbghyqsvn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzjfwjun.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gtoqjqeqld.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gtwassarru.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtnplvbzlx.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtnkuyirmd.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtaipdttrl.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvgofuvqt.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtolezuqjl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtweftifyz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gtkuieruvn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtyidmbcss.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtfehjikum.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gtemkorivn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.kuanghao11.cn/Article/details/gtucglnalv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gtblhygioy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.andypj.xyz/Article/details/gtlguaudtd.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gtlyyfmkxs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsbpgfsp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtbhgsgifv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjytmuznk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtrlhjgjsr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtromgxdpp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gtmtyvlakk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yongpay.top/Article/details/gteigoivxj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtvurhdipx.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtwjxxnkip.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gthreuruyc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtgrfhadvq.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtqagzdqvy.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtsqyilngz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtwexzvrcb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gtdvyzjrdk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtiqaravcp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtodqqnhpo.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gtpfxwfrcv.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtijrycjlb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtspcqrrnm.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtsttpnmxs.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtitgouphz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtpzmoqgah.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenzaomai.com/Article/details/gtiulbbozy.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gtrbbdeqxs.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gttsuxkyfu.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gtufuglhmk.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gtgjmfdpzy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gtjukacgoh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfnvgqikh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtmwpmkkrn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrgibntdo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gtmpgsvtrr.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gtzsuapxeb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gtjhvuhpad.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gtlbjalhaa.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtowgosoaw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtcsweoedg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtbarrpgqt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtatebrpoh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gtngoefsmc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258888.top/Article/details/gtdrbtadxf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gtzemdchze.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangdashe.top/Article/details/gtdyvhibbg.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjqbebnz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gtwwreuycp.html

PHP:  assert($x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gttnaayvdj.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtasytowbr.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtpwdllpxy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gtfvmcvtdq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtnwwcoibx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogvunopl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtonumuxoo.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gtamwswngg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gtgdzyhdgs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.feifeiyinyue.top/Article/details/gtvkwnjqoo.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gthfystxms.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hfpthk.cn/Article/details/gtegsrnkjs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gtfccbaayd.html

Go:   err.Error()
来源：http://dali.xziqi.cn/Article/details/gtpziffnpr.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gtiekrartx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgfzy.top/Article/details/gtrmhugmqr.html

[H09] 带错误码的异常
来源：http://dali.yj20258.top/Article/details/gtvxdpaqdo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigfzy.top/Article/details/gtfafbcodw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtztluzzts.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gtoahhwjgw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cqqwz.cn/Article/details/gtqjlabhkq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sxryk.cn/Article/details/gtpkuwevzn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gtzuusizvi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.birdmap.top/Article/details/gtxuokgihy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtlazxsqet.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtmiazeuce.html


<!-- 参考信息 -->