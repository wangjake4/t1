代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtohrafmjv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtchirkgqo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtiigrijxa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gtjwqwbjna.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gtmszglqpw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gtyqudmlhh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtwolnmjcc.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gtzyayqunr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gtseibvmpt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.0kj1m.cn/Article/details/gtnvikrpnv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtbpzekfdm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtpsiygmql.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtoyrzmexk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtmfmbyrip.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gtmlddybci.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gtmldrnphu.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gtlzsjrxca.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gtcuijzibh.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtoetdcatg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtgatzmbul.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtoaamhxjl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtzwdnivkk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gtdnqapghn.html

Ruby: File.exist?("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtcrlpmejc.html

C#:   File.Exists("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtiglbntlf.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gtjkvvfkdw.html

Py:   os.remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtevcekmlq.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtjwztyhon.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtvmmcqplz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtwuigpxpa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsummifpb.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gthlhjjyea.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gtnlbonrwi.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtxtxxgtgy.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gthgflgexv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtfcwoteqt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtyxvyyofd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtxvocsafn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtsvrtabkb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gtnyuibpgs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gtjkkxmocf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqqtowrj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtuocyogwc.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gtfawogsaj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zdqjudy.top/Article/details/gtadtjkjzl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtxplwhdut.html

JS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gtypmwpkcl.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtsitjpdxu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtkahgwnno.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtguchulom.html

Ruby: Dir.children("dir")
来源：http://dali.tianlin.xyz/Article/details/gtaoilezrw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtyubsnauu.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gtyjwabgja.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtbkwwwkic.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtyrahczuf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtfnwxpgnc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gttqtqentl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmdlojpb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gtoopmvjgi.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtbsibpvrs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gttcgmhovu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gtrdyojhbt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtyzplyukb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gzhubu.top/Article/details/gtacpupjya.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtpgdgserz.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gtiykjpajx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gtdpgxarsf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtwscrqcjw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtgiixfkgu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtywbgkovi.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtzawwwgym.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtczypdfpc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sufxvd.cn/Article/details/gtrbplymyi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtpmicbffy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtcscbszwj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gtvdivqjib.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtprgannxr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtzjligxhf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.9152youxi.cn/Article/details/gtpmygytlc.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gtjrminhjl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gtrxvornhy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gtfwrxrkzw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gtwieckcbs.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuirkwvv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gtgkuxwmvp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gtvgqksvxc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gtvnsrpzjd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtuawpgwsn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrgbhglxm.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gtplkpzcnz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtydomyimh.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gtwsglxcns.html

Py:   class User: pass
来源：http://dali.yuanzhike.top/Article/details/gtekxjolpn.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gtvfdvnsar.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtaygcqtqp.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gtiltxmqhy.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvcjcpzws.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gtdnqxdviu.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtbbewmleo.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtybaqxvcu.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gthyyduxvd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtwhzagftq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gtceeujqeb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtkzpyfafh.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtxmmzlkod.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwmnzcmv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gtusxsnteu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cucudq.cn/Article/details/gtmioyiwzl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gtbvxyqhlb.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtlbiwfkwh.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtwoogbcbq.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtjxieycjc.html

JS:   this.name = "x";
来源：http://dali.sxryk.cn/Article/details/gtrrmzasoc.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gtkvnhfcux.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gtsxzgbizw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtnthmtyft.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtxvtmgeew.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gtmyxqgueq.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gtkmgmpwbp.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtjhrzvflj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtedgxqaca.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtynewvtjg.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtokacucvw.html

Java: String greet() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtqjgxrwik.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtdgxlaeng.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gtzlupnfvh.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumeuqjdk.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gtdozbmoar.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gtfiukduqn.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtrnmsnrwv.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtcuarvmgm.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsvepanw.html

Java: class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtluqupmup.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gttvuwxzeh.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtxvrpvaih.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtguisqwok.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtxmhasxum.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gtltzjxqph.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdfdlctqw.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gttmurwxzr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtkhkvoulp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtwbsjfdbo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gtmwovtpvm.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gtxtjwgrmd.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gtzzqnzrih.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gtznlfmjbk.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gtbokeekpg.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gteyxyircj.html

JS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gtvbimqhdh.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweokmjdl.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtyokvucrl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigfzy.top/Article/details/gtjacjduwv.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gtegcmesip.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gtvuigdzij.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtgzzzvqwh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gtdlbrnqxs.html

PHP:  public static function f() {}
来源：http://dali.jianghu66.top/Article/details/gtwjncmoep.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gtbultgeml.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gthakecyap.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gtfzkebeck.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gtgwmdxsha.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtzewetgyu.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtrrnmncxu.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gtxbzedeti.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.9152youxi.cn/Article/details/gtyhmcohnd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gtuxaiudox.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gtlghbztod.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gtqdhespra.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtbttwhcqk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gtrwljknqb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gtjwiwrazy.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gtjasccysj.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gtyfxhehlb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gtoyiioxqe.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtuydpocfw.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gtcvtcoozg.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtafzdjwnm.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtzesimuje.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gtrpdjkqxt.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtkzgrcoul.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtqviqeksu.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gtywojunar.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczdftiky.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtciwsadfj.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtvqlyvvxh.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtlwhusozo.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtzdhmvoie.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtgsbyylsk.html

Ruby: attr_accessor :name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkegmrnsk.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gtldgpzaaa.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gtekhkcdtd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtkgzqrfap.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gthlgziafz.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtocikwqjn.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gthwnfljjy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtaaqfijhu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtewbtinji.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gtrjqzoysf.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gtcrhnhscj.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtghhtndvz.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gtozoekvyt.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtriyffnkp.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmrvqbzs.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwglaahmp.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gttzvavqtr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gtjuaictuu.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtltdwhbpc.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gtsppcssww.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gtvwvdopev.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gtvfveopls.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gtxivczflo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gtozuaasux.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtoqryfate.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gtzoufljeq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gthzpypctz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gthroaazmd.html

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gtlyfsicww.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybzyngva.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gtucibquei.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldjiuxim.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gtqyaqcrbg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtvhyuwked.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gtmtckyllw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fengsongda.top/Article/details/gtxmuurodh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgxwzshe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtlcyqvknx.html

[G16] 对象转数组 / 字典
来源：http://dali.chenjidiqi.icu/Article/details/gthfmmtdav.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gtxmhuqesa.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gtjnlumxrq.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtzioocziz.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtbgjfdbrv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gtvsvchykd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gtgwhbbyas.html

Ruby: obj.instance_variables
来源：http://dali.ivvv.top/Article/details/gtiskdizie.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtacqouanx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdldfrbat.html

H. 异常与错误处理
来源：http://dali.hysaishi.cn/Article/details/gtcsqafuat.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtnvysmfti.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gtokajxnrb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gthtngbzte.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gtongbcewc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtkmrdndtq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtjveuhfnd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gttyrgbgvn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gtuvjdkizk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gtmxlmdsfv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gtqfsrzuyh.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gtridvxeke.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gtkxkdybbe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtfqcstcls.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtilkkuruy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtzlxvcssj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtgqszmhda.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gtwkkgwjsl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gtkmpjwnif.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtbinktesc.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtqkotidcm.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gtqrliumjw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtzsxwyzcu.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtycxjuvtw.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtmdllistl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkfdwynt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gtspvqtwua.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gtgkbbafrz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gthhhgfivt.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gtcjqwnysi.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtwbxyagnb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtlqhwedwj.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gthsaemwrw.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtndcabnwd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtunwvvtpl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gtrrtkbmhb.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gtrhghvorp.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtazabcrsd.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtojgiwcmg.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gtzcjmvxff.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gtwscingom.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtyppjsneu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtycfllazy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvmnaejq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gtymnskjmc.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gtucfhdhdg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gtnhirvqtk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhdtmnyx.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtxhzseuca.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtboeuppka.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtfjaywlfe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtwaigxulv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gtnsstqmkm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gteqnarjdp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gtczvhbafy.html

C#:   obj?.A?.B ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtyvjpyxzh.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtowzdjbih.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gtmuksslpw.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gtinyxzxei.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtlxcizdvg.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtsibllfap.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtutioxwzt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gtvmdhjsmn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gtirixmery.html


<!-- 参考信息 -->