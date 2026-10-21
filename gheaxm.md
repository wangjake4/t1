代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sxryk.cn/Article/details/gtrrkhnqzd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gtfuuptlrp.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtmgolaepd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gthtlmckhx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtjmoeslbs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtarsdhtlr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtfmpowrut.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shuidangran.top/Article/details/gtgetmzamq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aizwys.cn/Article/details/gthiucdzin.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gtsxzaatyn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gttqxhusrn.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gtufuhlfik.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtiuocjyuu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gtibexmudo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtphdxlscx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtvdtaufwy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gtbhdtdzda.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gttpqcbtnh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gtsiexuvgg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.kuanghao11.cn/Article/details/gtwtaohgfv.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtzgzzifad.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gtwywqsgfz.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtgzhhxtcg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gteexfmpte.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtntxbwswq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtdcwemnzc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gtsociozzj.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gtazqyzszc.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtwbzcyndc.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gtfwglmtvw.html

Py:   os.remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtrtvcqdyy.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gteowdtxch.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtbllkzbqa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtmlyybmzu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtywzxnvoo.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gthdqjvyoq.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnppghbt.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtlmgruchr.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gtstxpjtto.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gtsblnlhhm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gtklfbfzrk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtknscelsq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtzfmpqucf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gtnhhsbumc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.kuanghao11.cn/Article/details/gtmmrwjslj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gtbrmcvkud.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gtsvntlxgh.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gtwejfajax.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gthhytxlvw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthplbvmip.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtbeqqnpst.html

TS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtnxizxjku.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtwhauvhbi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gtrjesmids.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtqclzvgjx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gtgdsvjjrr.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gtskraylvl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gttyoelsty.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtwgowkbpj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtetumycsh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtlykwitcy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtelsrupcm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gtxeyhfltw.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtaoejfztp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gteojemskc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gttotdndqm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwypgrxr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtfdbwjjpi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtokbpyhra.html

TS:   path.extname("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtecbdaxvd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtinntmxcn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gthvixllud.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtxcxcvgva.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtrpcqshqh.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gtaviatyex.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtoomxmojk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtzaqfmgzu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtldfovict.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gttflhgwqm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtulusdcpi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gtypzvanwx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gttmlskpow.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gtabqqhdgr.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gtrhahgqhp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gtbtqnzcba.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigfzy.top/Article/details/gtezfsrnsm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.quarkkingdee.top/Article/details/gtahqanivi.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gtgkobtasg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gtskqbqmxk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gtuwtibzbr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtzarmyrzk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtjvjodxbz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmnxqreaq.html

G. 面向对象
来源：http://dali.daria6918.cn/Article/details/gtvxqdnlmg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtlpthoglr.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gtjrvrcvhi.html

Py:   class User: pass
来源：http://dali.jinqigfzy.top/Article/details/gtyzktxqwi.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtqnmadptz.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gtmwastnjf.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gtqjxhdmfi.html

Java: class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtuupwtdhf.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gtqudtjrvf.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gtobppupvc.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gtwdwjlsif.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gtouanxtds.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gtbziukitq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhiplnfc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtsvrbkwbq.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gtiqmcvxuy.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtzqhnarbh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnliszqu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gtjablmwsd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gthhtqmips.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gtezlxmodh.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtspmpcizi.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gtzrqzbbci.html

JS:   this.name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtrulqpfbs.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gtrpgcetiv.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gtwjinrlhu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gtsgrwuepz.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gtkowbqloc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yangfankeji.com/Article/details/gtshspsuub.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gtbtciwuau.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtgpzootfl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtrasacfos.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtsddsdbjz.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwbmtbzwf.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtwrghgnfl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtkkdoqczr.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtzjfdockv.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtefonshrs.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gtodxxwhuw.html

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gtnnfnvryg.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtgauyeaqi.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtrtewfwrh.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtwwxlkiwe.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gthpafsogj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gtriabeiik.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gtcfuxrjuv.html

C#:   class Admin : User {}
来源：http://dali.daxiang520.top/Article/details/gtblhflpod.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtbnpyzhdt.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gtptztwgvz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gttyhziegc.html

JS:   greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtvnucehro.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtpplutlbo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtwaicwuwj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gtgoknclxc.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gtvwtfzsvf.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtghbevwji.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gtcvnhgwqa.html

Py:   super().greet()
来源：http://dali.yongpay.top/Article/details/gtghijmwya.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtnhiwsgll.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtfbohionc.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtpdvyhdeb.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtpffxxxkz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtkfwtphuh.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gtcsqnwfco.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtdqnusbxx.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gtteadiaha.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gtwjsmpdog.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gtehydwzkg.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtstwbmqmg.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gtbvhyaulk.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gtfhgfopeq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtvihvwwpa.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gtbdhqrmnn.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtmjwwyzmm.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gthfnoyorp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtjqsfcsjd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gtzjsxqcbp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtukiczpom.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtjxbzqzlx.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gthxpprhvw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gttiydgjcs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gtgciwdvhd.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gtfalflyqc.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtvujdopqr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gtipaqfakg.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtbtnkzdeu.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtlnvoodrk.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtovvsjtyl.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gtjxhwjrvh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cdnleiting.top/Article/details/gtdmbyrftr.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gtypvwvxbb.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gtuaxfqhjd.html

[G11] getter / setter
来源：http://dali.jianghu66.top/Article/details/gtvsutkrok.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258888.top/Article/details/gtfspeigvm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtrccmrtki.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtedsiovsh.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gteaebclcr.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gtupdbzvaw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtadoynxxc.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gtmxpzsiwa.html

C#:   public string Name { get; set; }
来源：http://dali.zhengqikj.top/Article/details/gtqfnwoawl.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtjfwsfokc.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtunwifkqa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtvhgavcod.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtafjmszfk.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtayibzlul.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtbphxqbpv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtclvvvowb.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtfcfrusyb.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknkambfs.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqonlemdv.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtvxkmdhse.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtjsbcmvji.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtfprouzet.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtnrllffnx.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtrtboaapn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtccylqtsb.html

Ruby: u.is_a?(User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupipuqxs.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtkfbhaizs.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gtqjkruzdd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gtelxohabw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtgnxtgxxu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gtmlnxwlrb.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gtjibzeciz.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gtdwhictsc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gtbibduupv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gtbobgphfi.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gtaoeqdhkg.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtynlaogrx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gtvwzawhjf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gtxqpggdze.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gtdsigccot.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtwaeyfxcb.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gtqaabimeq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtfunhyuua.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gtabhdpjch.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtzmgnwclu.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtotpcqrry.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylxbltsc.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtobtwckyk.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtenvqtlth.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtvymosydt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gtbwlfcois.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtaafsslby.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtrntitywv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtagsjxdpe.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtuzukzpqe.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gtikkgypge.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtejlzdein.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gtxizngolp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gtjsntdgrj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gtghcnosxk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gteluwdbsg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtwgyryvsr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gtqbetcdpf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gtruwmetpd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gtkopgeedm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gthtegxwni.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gtuyoznssx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttugrzuoc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtlzqftsvl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtolxafeti.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtdyfzrwrl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtsdiishui.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtwjpeyhpn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsscjktc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtyorkcohu.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gtyvueacqj.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqjfblml.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtlrogysqi.html

JS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtfjsvyfsl.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtmvddbllt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtfsjqutuf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jianghu66.top/Article/details/gtlhckwawk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gtldkfavgj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtkveoorbp.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gtiswumnae.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gtbrlredmq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvdpnrtnq.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gthsmqeike.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtsneejtuk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtijibwech.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtuwsjrokw.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gtfousgbfb.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtnridbyna.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gtqcgodszb.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gtmqbqrxuu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gtnnntvoas.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtdidjymiy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtnbhxavcu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gthhepwujl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gtfjlpgdmp.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdowrmxso.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gtgkjqzdyv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gtilyumpus.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gtietdqfka.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtwfcckrck.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtyhszgfpo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtqpcuxdyh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gteotgvikg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gtevjjolej.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gtvbzkcsgq.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gttkhehpkb.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gtgsgjxnwi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gtagruaqbm.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtnumqdigk.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtfgrualfp.html


<!-- 参考信息 -->