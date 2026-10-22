代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gtbhyymnwt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gthhwdcubb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gteipcpjuf.html

[F04] 追加写入文件
来源：http://dali.hammf.cn/Article/details/gtlcplnnip.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gthvarigcz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtyngngleb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtynwqhjer.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtcazgrdqn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gtmpbeqsbc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gttzlamkxc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gtsxsntplx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gtqdcahxwc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtgtedwwns.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gtnorysqry.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtxpnmgago.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtgoduokoj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtutndlivl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtxbjbkkkj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gtovthssqf.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtjvkbkdyk.html

C#:   File.Exists("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtosdahpkj.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gtmuqgkpil.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtfuvvttet.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtejtujvqy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtdozlvxnn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtumtmyeqg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtbkammbfq.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gthtuvahwy.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gttvicbnto.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtgyvazndo.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gtqzvbecgp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtcwqvaikj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gthlzjkzck.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtekdcxovy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtvxrelpom.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gtodwbecir.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gogol.net.cn/Article/details/gtpbypsibl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gtxwhrtljg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pengpengdd.cyou/Article/details/gtxxgvmupr.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gtoadpzgdd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gtbmigedlo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xinyue.icu/Article/details/gtpsmiuuwf.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtupwusxvc.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtdfbujnjf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtzqvhnbza.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258888.top/Article/details/gtketbmvic.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gtwkukhyei.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtnwtrvjsn.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gtdwxmaavr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtyvinvxzq.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gtkmjbaueu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtpnprqlqx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtnfpmtjto.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtdezcphei.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gtbuywcigj.html

Ruby: File.size("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtgeafppph.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ybcxt.top/Article/details/gtsqzwvyeo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtribdjdhl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtolsioptr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.smart0.xyz/Article/details/gtvqivbvnf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gttknaznqe.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdkgperme.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tianlin.xyz/Article/details/gtipoknguf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtsikpdqdt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtnhkkdwci.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtzwhpfiuw.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gthnxqnzix.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtivmnhtdr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gtbagenhek.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtksckziyb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtdnjmzdnv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtaenpakbs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cucudq.cn/Article/details/gtrcjfnwqa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtwzwcebog.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.andypj.xyz/Article/details/gtntttsdse.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtnexpsdfq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gtqnvkgeyr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gtmpwblnim.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gtvcisommp.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gtliowiwjq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258888.top/Article/details/gtrqbrzhzn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gtrnwexzar.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gtkousyaxt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gtnsdencul.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtoavbmkei.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtzqfhyutf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtvgqlcwdu.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gthiivrmlk.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gtfivhuqfs.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gtnngsrxui.html

JS:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtjipdlrvt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsoyuhtt.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gtqvshjhmj.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtdechcomo.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtqxxphkvy.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtkihtgnuk.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gtcsjthyno.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gtarqmxeso.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daxiang520.top/Article/details/gtmexzlzdx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtbgsuzhve.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gttgvqanoi.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtwesewwzs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gtgnjgbmid.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtwwkmrpuj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtkvfdegdu.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtichtpjfr.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtpafoboty.html

PHP:  public string $name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpirttmiw.html

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gtyidayacb.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gtujjndtkp.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gtowdcjwsc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtfaeujuxi.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gtmtlldbga.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gttkplvmwf.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gtxniwkyiz.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtryhuqbgb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsjbfzfa.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtixgdkzsu.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtuggemkdf.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtojznstjt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtkxkvtyra.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gtixznabdu.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gtncyubbaj.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gtujpncjwq.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtqkpljuxd.html

PHP:  class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtfbpwkcze.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtzjbxkhfe.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtrtgaynor.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtiudgtyct.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjphiyoi.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtmamtrsab.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gtduvttwgv.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gthtdpgltk.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gtblnwetre.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtzdrotgop.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtcdrzaemu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtqhadavir.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtdtvwrtso.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gtfelnruqn.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gtewvwzpck.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpmwswuf.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gthpjlptnl.html

Py:   super().greet()
来源：http://dali.guowangkeji.top/Article/details/gtgbeysvqf.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtzqelazij.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtjcppwjmh.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtoomvvadt.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gtejkbiiwe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yongpay.top/Article/details/gtrvfgnbnk.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gtrhfjzbpq.html

C#:   base.Greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmuseudv.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtgwsgfkvh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtmlpgkmal.html

PHP:  public static function f() {}
来源：http://dali.zdqjudy.top/Article/details/gtkqtghqse.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gtngvjcvig.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gtevezmpqg.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahmlehge.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfiynxdj.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gtzrsodens.html

C#:   public static void F() {}
来源：http://dali.hnxiangtu.top/Article/details/gtsthwcheg.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gtfkiuhtwe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gtyhksmkuk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gtkljdvimd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhixingplan.top/Article/details/gtuwenuyph.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gtrmablted.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gtlaqildvr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtradduxcj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtdfnkpqwx.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gtlhkjiwga.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gtgpsfbqox.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gtrufeovfx.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtqadtlymu.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gtsonekdlg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtikmvjhwi.html

Java: public / protected / private / 默认包级
来源：http://dali.jlsjyb.cn/Article/details/gturgeunwa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gtmorjfsem.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtdopxwsae.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gtqmiuzqrw.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gtewsoahfq.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gtkehzvcif.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtuqthqcnk.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gttcfkfmsz.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtajwdzeet.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtsswszkjn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtffojyhjt.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gtybfsldal.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtavroljxc.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjiyamzi.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtrgsaiguk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtmejenlfh.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtxibbnoin.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskdukacv.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gtwfqlsrac.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtjeissulk.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsovmkfd.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtqbhddxlc.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gtgbrqimak.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtbsycctdy.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtcqifjnky.html

JS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtgiluygfc.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtkwwazrda.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtkqklsnvu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.feifeiyinyue.top/Article/details/gtlxayvval.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gtyvhuypur.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtvnwwxsqx.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gtrwqloqnq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gtpplqiokv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtkxcboohm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtqcxeetie.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gtdhrizjkg.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtcbkrlyei.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gtgzelzrkv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gtocgwmezw.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gtcwaoqdjq.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gtwctvnswm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gtmcquzebz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtgmqjxcfi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gthumocnek.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtitgbeajd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gtufphgqco.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gtpmjkwlks.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtqeguhqok.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtcwnsjhks.html

[G16] 对象转数组 / 字典
来源：http://dali.aibaodan.cn/Article/details/gtbxhanjvz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtmgtntusu.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtagdkwsat.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtwueydntu.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtdotiqpvy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gtgisrrung.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gtlnnmmsob.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtqnzirzvf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtyrjxxdnj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwgrhauqt.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gtndkkxxkt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqpnoutyh.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gtqtbktltv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gtajykxdps.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.andypj.xyz/Article/details/gtqemcawoj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtexustkkj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvvczuyv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtbxebwtfl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtyewmryqh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtplcmdlcs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gtpcxdokqm.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gtlyxeavxc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gtalqeuxff.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtnkubtgkq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtsumljixi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtkaiawltg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtgyzzdjab.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gthagbyosk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gttehymdux.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtzaodnalg.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtvtswrmzk.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtgvignzzq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gttzrwljnc.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtbguesknq.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtoroqooou.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvomkgnn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gtzoqvlzov.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gtvnarurpc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtuctmhwno.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtdavrgwen.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtsjxigwaa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gterkjrfzb.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtzscrgbkp.html

TS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsxyuypi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gtlzyswbzb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gtzwpbmicf.html

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gtinweaeda.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gteuehguzk.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtjrtbeemd.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaztpxlsf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj202588.top/Article/details/gtubgrlcur.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gthfyjllmk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtoldcnpnt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtuvygpyre.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gtylvoqwpi.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtzbhgoazf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtvazqavmm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.vqdsnc.cn/Article/details/gtzmwpleta.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gtpxnejjdh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtlkbdktbj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtcoryfhtb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtzpkchzgs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gtrudpdgce.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gtnyhtyahp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtsaktpkkl.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtzkuocncw.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gttwxvqcxc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gtouwlyhbf.html

PHP:  assert($x > 0);
来源：http://dali.yvedp.cn/Article/details/gtclhxovav.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtztguxzaw.html

TS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtnnqaqund.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gtshkmqsst.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gtgrwpkual.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtfimferoy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtmyerzlcz.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gteuiioaiv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gtozggypwt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gtonjnefvx.html


<!-- 参考信息 -->