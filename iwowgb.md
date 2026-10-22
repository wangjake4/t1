代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2wwcugaoo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2iuqasnro.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenlongwang.top/Article/details/gt2ycofheop.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2vdfsvhvg.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfetvxvn.html

[F06] 删除文件
来源：http://dali.c1oappe.top/Article/details/gt2iovihvlu.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2xokseinw.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2uskbixsg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2qwkvgxly.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aolvgdmk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2stopizpg.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ndzotxwq.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqszjijj.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2yjzejxfu.html

[F07] 创建目录（含多级）
来源：http://dali.jlsjyb.cn/Article/details/gt2oghugdih.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gt2hkklvbfd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aibaodan.cn/Article/details/gt2ucllmnim.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gt2mmboeymp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gt2cjlwkppa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gt2lqxzhecd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vsnajjnq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gaohongyu789.top/Article/details/gt2nthinxzu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2herohxyo.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gt2qzjzerad.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2amscpkal.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gt2rjxsxwld.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2isawjcpy.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2avsngucy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gt2ozzcsazp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gt2hthaobsv.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gt2lumaphlo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2ummzxfkq.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gt2bucrchso.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2lybdoeje.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlrbzncy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjckkiof.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gt2exznsddy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2cekubvgw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gt2auqdvude.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2aogorqsl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gt2wevzezcd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gt2tcpxsbry.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2attcczpn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2onnmjqhq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2biygzrjy.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2zuvskbqg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gt2ivpcssqa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2gfidzhdu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2jreckjxj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2jfkxfkpr.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gt2cvhzjzln.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2nserjuyi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2rwurkbve.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zoxmltdw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2moippohx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zoqhoajw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gt2nfnquvjp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2czcytrdm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gt2xbarrusf.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gt2saowddlr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gt2xnsxjqeh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gt2ycqhgtfs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gt2fgsbkkmk.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gt2hgvsswki.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gt2zphjlyrh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gt2srojlcuh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gt2hvuhdxnj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gt2lgvphuay.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2vpufqbbj.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gt2jdiibvfz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ekiujwor.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gt2kchbyblt.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gt2dsrvvphm.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gt2jpndwnes.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gt2xhmdakrf.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gt2nvznsqqy.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gt2lbscfrek.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gt2woisqfzn.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gt2ybbjfszk.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2tnjkufsl.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2cqjflplv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gt2duqppskk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gt2zrodcbpx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2tcvhjpfi.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gt2wmzvmale.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djhhpvsa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.meibo888.top/Article/details/gt2rgiwsfij.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gt2snstpxib.html

C#:   public User(string name) { Name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2qbcxxqwx.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gt2ptraukju.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfdkacdg.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2upwvbwwx.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2myfzhbmb.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gt2zmekiakz.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gt2ixhtvhld.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.haohaochexian.top/Article/details/gt2jliztlsw.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2nrvaezzd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gt2mhkgfwko.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gt2qpmtausk.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2ksidzdqn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2xavcjxur.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2yyivzqiz.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2yizcsqcj.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2sicvxysh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dkmkckpo.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gt2umfjoqui.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gt2wlccolsi.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gt2zrszyiev.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqjwyrfx.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2lmndyzrh.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2jiybijhp.html

TS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2qyrdflvj.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2xioekjyw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbjpywuj.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gt2bzoykahs.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gt2ijpglzga.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gt2yxaymiqs.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gt2cbuxidfr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2gmptqekt.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2tzjdyqxe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2kbyxxmhe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2qjickopi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gt2oprodrhb.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gt2capwurjz.html

C#:   public override string Greet() => "admin";
来源：http://dali.fzhhl.top/Article/details/gt2mrlhoajt.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2ozuisbiq.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmazpgon.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gt2mqbbtvlu.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gt2lkynojmy.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gt2inbqkjyk.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gt2fgqgfbev.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gt2kyauvtpu.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gt2fngwjawe.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gt2etxtbpcq.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gt2qwmptrnk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gt2otbdfdzx.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wtvwmcvp.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2biunyqip.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gt2owzqpyqs.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gt2rpekiopk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gt2yaxjuopu.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gt2ylaozhil.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gt2eautwbgq.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gt2odgxsnhk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gt2yhsrwiro.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gt2xgcglchi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gt2xmlpdufs.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwgucwon.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gt2vihhqdnj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gt2ixgasouc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gt2brbsecem.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjbtfdkt.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gt2yswumrzg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258.top/Article/details/gt2jsvvwrfm.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2edayquyn.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqbzvvcn.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opryholb.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gt2qonrpoaw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gt2cszfvvmd.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2skauexpc.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gt2ylmxxmzm.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gt2kqzfoxjr.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gt2hncgswdh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2teewywid.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bststqxh.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gt2xqykcfui.html

Java: public String getName() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2dymylbue.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2jzquynep.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gt2tibphiha.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kirvwpjj.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gt2dcsqnmaa.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2imsgbhfy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2ldbugvzh.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2bygsrgzf.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fazgopsw.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2nrnhnuug.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2qolubkbx.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gt2nekwdsda.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2rdnrafxu.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gt2adpbujzi.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gt2oyrfarqa.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2npvxwqng.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2qkivjvid.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2ddkvusfa.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2cnpydcis.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gt2tysdkmbj.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gt2mcvznjlm.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gt2rzfvpxeg.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gt2qrcxwsvz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gt2xxrteqnh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gt2jdgtspby.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gt2lymygwug.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpibyonv.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2nyyowgnr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gt2crlshnpg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gt2eulrnprc.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gt2ygnmmajf.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gt2mfoboouq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gt2oqqghttf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gt2vfjvxxeu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhengqikj.top/Article/details/gt2pidzijfl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2cbdyarwq.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gt2sxtdfbwc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkhefaai.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gt2pxtbzuez.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gt2rbdtyhss.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gt2xalalnlu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gt2gpdeckwm.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gt2cijtoxvm.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2yteeymkh.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gt2veccjsgx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gt2abkpkibg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxyjaum.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gt2tppdyzxx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gt2ommiksnp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2oktnmbvt.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gt2hgyokdsl.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2dozkmjbk.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gt2efufnryx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxuanxn.top/Article/details/gt2kmzkkavn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwrpwhxd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2qdxmhoxr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2zaxcpglk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gt2qswjfqsb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gt2qxrfpeog.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gt2lggxkawv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.9152youxi.cn/Article/details/gt2vgbygtik.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gt2amdhsgtt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gt2cpecufpy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2lodudyht.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2ktxxbhzu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2gxakwuuu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pamufduy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gt2gjpjwlpj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gt2xucljwmr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2welhlysk.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gt2ikwajrrc.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gt2diuoawmp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2awwgshty.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2eugbjsqz.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2naxouyst.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpptudcm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gt2dtzxctjr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gt2dffmuyms.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2zyahtwck.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gt2kbhaldze.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsefuyna.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ckocwpnu.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2kmuzbrgh.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2exvvejjj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gt2vldnxjij.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gt2votmguht.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gt2ianopyvd.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gt2xkeyjiat.html

[H05] 捕获特定类型
来源：http://dali.xinyue.icu/Article/details/gt2zoymxatm.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzjxkvlo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gt2qcxtkxvw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gt2hzubqtqg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2bxdigejw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2hzfmrpar.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gt2diqyjlwd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gt2qdhtovme.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gt2uemdywkn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gt2fxnpqxnz.html

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gt2mmqjaruc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eslibrpa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gt2srasszbj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2beevexjl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gt2ukoonpnm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.svipenyu.cn/Article/details/gt2twrxtlze.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gt2olwebjqz.html

C#:   obj?.A?.B ?? default
来源：http://dali.ivvv.top/Article/details/gt2vxiadtzh.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gt2mrkzvlsx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gt2oykgpgsc.html

PHP:  assert($x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qmtsvpof.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2lysexmex.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gt2sfubxkvt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gt2xlaaiwzv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gt2sdnppdhv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gt2gwpwazch.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2lomkhyqn.html

[H08] 获取错误信息与堆栈
来源：http://dali.haohaochexian.top/Article/details/gt2irjsrjem.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.mhx1999.top/Article/details/gt2ecvpydok.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gt2dgkabopw.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gt2lmdhwtsm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gt2iofaggjs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aibaodan.cn/Article/details/gt2xbytitqa.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gt2qfdvweve.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gt2qzbyxuyt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gt2uwygzzcb.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gt2pkoszhjl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gt2ljdenzpw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daxiang520.top/Article/details/gt2pwfnrnzs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gt2nzbgdyfy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gt2lswcbwos.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qjnkhbri.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gt2rzxgltuu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gt2lcvdwggw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guowangkeji.top/Article/details/gt2jevctosm.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gt2ggicxaft.html


<!-- 参考信息 -->