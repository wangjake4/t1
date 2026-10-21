代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dashuyun.cn/Article/details/gtphxnltoz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtlycwflit.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gtgbuozzlz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gtxugsrqqu.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gthcdgtnzc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtwwaytdcx.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtyzqjjbxp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtzbeqovbe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gthsghqmoa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtxvyqmnxr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gtvejpjvyl.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gtouuyrwsw.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqofonbuc.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtpkkjyava.html

Py:   os.remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gtbtaqpsld.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtyrpanvup.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtcdzxnmfb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtrunwvlvf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtvptqpmmv.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtakanivea.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtckqemwad.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbcgvlsf.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gtnitvuxzk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gtdxnjzbhk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gtshstqzqj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gtwizufcrb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtjmlmagny.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gtogvvchfy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gtkbmrhota.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtnhvkzydm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gthoywlogv.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gtjgbayxwz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtseibsrcs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gtqucmjqys.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtuwdxmqpd.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gthrpkytcx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtzbtoolyh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtyclewekq.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gtcdobygtw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtxqbyrsly.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gteqjtwtyv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gthncmlnrl.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gtnbsqvqdz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtdwbgsdwy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtateedacy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtrxnoteik.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gterlcoroc.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gthlbkuxso.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsilhojy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtzmkjhwal.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gttkmhjles.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtihkvwkuy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtbfplulty.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtjsjyikss.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gtoyjvemul.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtaqjlfczm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtkfwlgzec.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtoyransqb.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gtfnmflppd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtirnvksax.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtriugsoqw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtcoqqxhks.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtmxffeexe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gtnnxjbryl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gtvkntkhff.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtpoawnqgp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenjidiqi.icu/Article/details/gtijpszxqw.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gtgehqzjtb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigufen.top/Article/details/gtnwabukqr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gtnrqcbdvz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gtsjjrjxlq.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gtgbgreasu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gtctmtfvdh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gtbvabkkfj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gteagricat.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtgjckpauk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtrmqlcctg.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gtxxvrsifm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthrvyitlx.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gtxzckmmmm.html

Py:   class User: pass
来源：http://dali.hfpthk.cn/Article/details/gtqhqzfvnw.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gtnhrawkbs.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtfsmoojqf.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxfbyphtr.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gtvqgasinq.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gtalqasdpa.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtfasauush.html

C#:   class User {}
来源：http://dali.xinyue.icu/Article/details/gtjtoeecxf.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gtqgepeqoa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gtpsyeymlm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigufen.top/Article/details/gtnodqgfdv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtofthuhsw.html

TS:   constructor(public name: string) {}
来源：http://dali.hnqzz.top/Article/details/gtrzxabnwg.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtbqybytau.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gtscaltwhy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gteoqmmnke.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gtmpidrmuv.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gtnwkuvhuu.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gthvpxaweo.html

PHP:  public string $name = "x";
来源：http://dali.ppjwa.cn/Article/details/gteukosyqt.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtbagqtvgt.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gtoeozjlvf.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gttubhaqyj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gtqbccmelo.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtkegcwxyh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtpzwzmgqk.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gttogdutft.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtuttwwvue.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtnsdcaarw.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfalrotay.html

TS:   greet(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtyuthtseu.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtcwkhvdps.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtexweypmp.html

Ruby: def greet; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtqpctinjc.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtgifynnbh.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gtwqapdimp.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtywzirnzx.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gthzgqulaq.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtcskmdlxw.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtripbqlqp.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtynlndfcw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gtrqztrboz.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gtnccmindx.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gttsjqkrfa.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gtairtmlxo.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtpbxtiptk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gttpkygjkj.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtdhbztlwa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhpdzecz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtesgubghe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtextsrskg.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gtqflyabmc.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gtawcknpwn.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gteccllwwx.html

Py:   super().greet()
来源：http://dali.zdqjudy.top/Article/details/gtnhuvluxq.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gtezkvozcf.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtmcjhlbkg.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gthroahkrl.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gtbafxjxsk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gttszikcww.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gtssqmyptn.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gtqspovtwp.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gthczqgpah.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gtphjihduu.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gthcarkdqo.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gtynsxqler.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gtdpgedptf.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtfauzldgn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gtmtyruoel.html

Ruby: def self.f; end
来源：http://dali.0kj1m.cn/Article/details/gtmqmyukbm.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gtrlbfrxhi.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gtymoojbel.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtihvkrlfk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtxoafrzfj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gtnqvlcsem.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gtlouhdpat.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtosqgppbk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shuidangran.top/Article/details/gtdqvfeqyu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gtyfwyjgyi.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gtwczcejrz.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkbbhwxb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtnpwkftds.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtjsaspczm.html

JS:   #private 字段；其余公开
来源：http://dali.0kj1m.cn/Article/details/gtegbacrkc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtxnawjptv.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gtqzxczweo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gtoshiniva.html

Ruby: public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtesuoafle.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtfdnalpds.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gtkjqkhcse.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gtqwbgzcuz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtjfempdlt.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtharycfdd.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtpifwwdmz.html

Java: public String getName() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtdulawxck.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtxpmsbbiv.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gtdfkeepul.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gttnmvbiaq.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtawcukyof.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtwlaasmxo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gthvxmlttc.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtcnqqyheb.html

TS:   toString(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtmwnsqlnq.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtmxvdtvym.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtzlyloymh.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtbqvhjezy.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtxbdveunb.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gtbfrnunls.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gtjmmzqcye.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gttjzhvmrr.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtenjyiczw.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gttpyzuvvc.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtwoqprski.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gtbueyfhfo.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gtpxfmvuyn.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gtvxcscmlp.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gtljfdller.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gtnmbhstbn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gtpidtgvay.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj202588.top/Article/details/gtoztnoygj.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtphpydorf.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gtwvihnble.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gtcsgxijrt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gttedltlbz.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtnbycnyhw.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gtlifopazn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gtyvoguvel.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gttezclxxm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gtkjzfxyaq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrxwaerp.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gtngmthxhl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gtqrwmjnnw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gtqzwqrrzp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtuljyxagc.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gtlyqwwsuc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangtech.top/Article/details/gtetmfgihf.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtezzvmnpd.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gttrjlfkun.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtgonaxxjd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gthddztpfn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtdnkqvqqh.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gtoqsnpkqy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtejflhwow.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtiogscssl.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtodpyputr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwrrwbhzy.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtsuhcfmrp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtveoirovc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.havefunace.top/Article/details/gtuxapmmvn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gttjmpulcb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtvrommzvf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gtxxkiuuwu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gteeehtsmz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gtejikezku.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gtspsaoytc.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gtrwnnmklj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gtvyufdgyv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtqrffxbqv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtwtemmsjc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtvbsmdavm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtvviugngn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.meibo888.top/Article/details/gtddkqlqyd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtwkodwuew.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gthkycdwwo.html

[H03] 主动抛出异常
来源：http://dali.meibo888.top/Article/details/gtzffcujgt.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gteyzfluwa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtjbimxtxk.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkorcttmg.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtxfflgixq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtutcfprwh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gtvxrwtdrr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gtscevoeeh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtemhfbsid.html

[H04] 自定义异常类型
来源：http://dali.snrcjt.cn/Article/details/gtapoogomt.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtpulxpbfh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtphehdyrl.html

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtntzfmnok.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtukwldybl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtyzfnlojp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gttbtocqjc.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gteguvcdca.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlemeqvvv.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gtndqrmxbl.html

Py:   except ValueError as e:
来源：http://dali.dashuyun.cn/Article/details/gtmyofvbuy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gtiicxndfl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfhubqyz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtumzfibui.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gtxuhlgjds.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtywmqygxz.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtgplqpaso.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtsenfacgh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zycfv.cn/Article/details/gtkyzzenwi.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gtabtebnrz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtyrwqmpbw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtwxjrzzir.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbaxfcgc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gthoquhuea.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gtligadmev.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gteiyxupmu.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gtwwylvoqa.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtakymdwtb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gtvxjmawtc.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtieannpty.html

JS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtyokvfjhy.html

TS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtbyhdywsm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gttvviavoq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoctsypsk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gtwiwackie.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtxejvippy.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gtkrncgdcp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gtyoqimnlm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gtvcsfwime.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gtncieqxvh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbputbff.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gtobqzsrfs.html

Go:   err.Error()
来源：http://dali.yueranfly.top/Article/details/gtshizkpbn.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gtnauqgvmd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yonumen.top/Article/details/gtisncnpxm.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gtsqwttgzg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gtnwcatlad.html


<!-- 参考信息 -->