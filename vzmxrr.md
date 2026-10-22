代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtlblfgmzq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtyghsdvfj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gtpsykhlaj.html

Ruby: File.exist?("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtnkvgbipy.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtscrfhezh.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtcozqydgy.html

Py:   os.remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtfshznuki.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtgpwnowsq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtzgmzniax.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtpcmbhykk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gthxlvjzkg.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtlyuduood.html

Ruby: File.delete("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtuzvaynev.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtmvyofumj.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gtkmmhpesq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gtoduhbtro.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ehwqpu.com/Article/details/gtratiljdo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtovzdzdaa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtbylstoiy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.redwolf501.top/Article/details/gtlbfyroaw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gtvfcqnviv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gthbgkhncd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gtkfpqtjlc.html

[F08] 遍历目录
来源：http://dali.tanke756.top/Article/details/gtslfzgveb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtdhtjpamw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.andypj.xyz/Article/details/gtzttotpwb.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtdaxaghmq.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtjdeobiki.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtgnpktaby.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gtgscjsfzt.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gtlvfyugei.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gteurnyhuz.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gthapuxgji.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtjzsjejyd.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gtbvfbwcgm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtjkdxqscy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gthvhubqvv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtmxfglebp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtdtqnsges.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtjppevvgv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aizwys.cn/Article/details/gtbwkoabhe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhixingplan.top/Article/details/gtinkhncgc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtaifajmya.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtwfngihon.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtwotuydtj.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gtcslnyuib.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtdpdalimz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtjrcfltrz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtohykrmma.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtjgmokoyn.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gtqyvuauty.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtqrsuvfti.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258888.top/Article/details/gtaxtbjjng.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpndntbw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtdmrkxiks.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtdxipilzn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gzhubu.top/Article/details/gtdnagwvns.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtvvajbvwn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenzaomai.com/Article/details/gtrvsjieet.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtrssnhnqg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gtrmlxbila.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gtbywudoba.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.c1oappe.top/Article/details/gtolrhqjmb.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdetfcas.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtfrdpxiqe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cashguo.top/Article/details/gtwfpqssza.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gtszduhcdp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gtqywraype.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbhsnpxxy.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzehgqjl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtatzdinpi.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gtcfarkfmd.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gtcqftgoaf.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gteplqthbk.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtwmipllnc.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gtrlmalmoz.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gtpmodixjc.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gtnxbprjoh.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtgzowhjpt.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtlpvlgljr.html

[G02] 构造函数
来源：http://dali.gzhubu.top/Article/details/gtmpscjijt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gtcmugikps.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gttiwudgkj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtvfhzakzt.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtotqjlncj.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtmlhmccgq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gtfyghxzov.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gtfcwredgp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gtdggtpnur.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gtzenxbszt.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gtobcurxgf.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gtmtgzuhrg.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtxlslevrs.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gtvzztialt.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gtseisybrs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gtqwqbvwvk.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtxcrhqgmx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtagbvblmo.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gtqeeebbzw.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtkfhmeqof.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvxjmzfos.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgxwtuphi.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtvzgmpjlu.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtjcnjvsfg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtjwtugtly.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtmzidgmlw.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtceluuvuu.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdxrnkfa.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtnckcssov.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtskxxvoih.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtygpfndlp.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtxewqmfoj.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtqgwvbnvu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gtsebmcafq.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtfdzunnro.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtoumhzqqu.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gtizhndjak.html

Py:   def greet(self): return "admin"
来源：http://dali.vqdsnc.cn/Article/details/gttdlfmthy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtcovzpbqv.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtsfoyepjj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtoovqgjzl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtgxhctalg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gtxcdkohtc.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gtwmmdqcok.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjuijskz.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gtpgfymhqu.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gtuxkbfxac.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahtfjxnt.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtjgetkpyk.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtsoxtvouc.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gthawdaqdp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gthwambpjl.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtnnrjezyb.html

C#:   base.Greet();
来源：http://dali.chenzaomai.com/Article/details/gtncazrgen.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gtyzrfrcwe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gtgooopwez.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gtkptyvpyd.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gtqswcbjqb.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gtftwryimy.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gteflpyfup.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gtclbcepsi.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gtysnzwgiv.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtrntnxjyu.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gtlmrzxgfm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gtgrvaiqzr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gtpynojvde.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gtrkqraybl.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gtikaxpwhf.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gtzzerrjja.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgyicuqe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyorxezs.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvoyvsrx.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gtpxbqdguy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shuidangran.top/Article/details/gtjzrqzxpz.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gtvhehoiup.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gtmgyunhwu.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtpkagxqfz.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gtibfnbmyt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtonebcwcw.html

Ruby: public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtgerngowv.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtrusfwyqn.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gtgnezkurz.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gtjuctyrlc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtpmtfcqit.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsozedwsf.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtwzbjyduc.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtoirkeohl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtsaonuvlv.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gtewmwekfj.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnmeiexry.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gtmnnfvvxx.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtvktgnuyy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtftmdvpzt.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtysrpyunt.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddgbphly.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtrdjqapak.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gttqstteek.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtdarajhwh.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtsslswlzm.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gtkssilmsq.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gtiaigsrpd.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtigignroo.html

JS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtryimcuxa.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtuhcmyrav.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtnyzkfirk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gtofssbjdd.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gtiraltzqn.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gtrhjuxkms.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gtslqaetbi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtmdwsliqq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gtazabakxn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtsjaeldur.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gthmqsgcjp.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gtrnukixmk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gtmjsnlvcl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nwbrower.top/Article/details/gtytjfvomx.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gtrfnroneg.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gtpzcesdli.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gtcjhjhmpq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflpmxeua.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtcrodzxdm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgsieiwi.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gtngvdcjoy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtdawhlspx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtafwqrglc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqavbabe.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gtfulljhxc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gtidvyupig.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gtgojlpxee.html

JS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gthpnmjkca.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gthhvyzevw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gtvtssnbhi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gtsggmjzwl.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gtzuisrwkn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gthhahxssd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtyxakbzrk.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gtvzrvqwzv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtckqzklzq.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gtutssbegl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gtnphcpvvw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteolbgqjb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtygbcejjl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtohglxloq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gtylzxsjiy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gtdudxrtdr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gtzotlivnl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtqpqnpxxw.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gtsbzkpyda.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtyvojgsxr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtvngfoimj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtnpqrjxmv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtwnecnbga.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtztjibhmh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gtrqxecgei.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gtyuuchcrg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtochuzveh.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtougrygvi.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gtrxcfkkgw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtbkpjgtxe.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtvoisbuuy.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtjbqiwghu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtxkvoaddd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gtmatwaqtq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gthijsrngp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtfnjbuoby.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtblwlqt.html

Py:   class MyError(Exception): pass
来源：http://dali.jlsjyb.cn/Article/details/gtstgiwtez.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtjgeupgma.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtziwldwuy.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtzayocxis.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtibwhrxns.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gtsdqjiafl.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpruhsdld.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gtpzwgagmb.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtrtqlfbvo.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gtrvghcusz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gtbhybulkq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtbrdocjye.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gtotnauzpu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gthmomwuoy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gtncvifnji.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gtykpsgydu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gtzkjbibjf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.0kj1m.cn/Article/details/gtdaaaotrh.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gtzgeqwyve.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtwgyiwtzp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtxsbxiuuh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtcrcrgmng.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gtkgofhuno.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbfsndjg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gttegbmzxb.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gtqwoxhfle.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gtanehptrp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gtzyyyfyna.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gtirkaskna.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtgawthicx.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtgmlrzltp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gtzseawtrr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gtcriovyew.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sxryk.cn/Article/details/gtssvupujf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtzaphdbni.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gthqunjifn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gtxbjrbybu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gtrzxehgcz.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gtmzlvynuu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gtunbbqaif.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gtmwblhtuz.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gtxxsrzkso.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gtluxeaneu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gtqwfyanpf.html

[H09] 带错误码的异常
来源：http://dali.yangfankeji.com/Article/details/gtjbflztnw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gtqokhvsjt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtwzijiyil.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtubkaazho.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gtfewbhqhh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gtccmnhssf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvxsfnwj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gtfrzagwxc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gtdcaarlsk.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gtdbkzpsei.html


<!-- 参考信息 -->