代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.bjfxy.top/Article/details/gtbdwimssi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gtsxqmddvt.html

[F03] 写入文件（覆盖）
来源：http://dali.chenjidiqi.icu/Article/details/gtecmpqiqw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenlongwang.top/Article/details/gtairgbsqt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtfhshnstk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtuctpjecb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtmcejaxik.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yangfankeji.com/Article/details/gtkbehqxcv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gtrjjcgpzp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtystxrnqd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtvedxrhuy.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gtjdblkcyv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.redwolf501.top/Article/details/gtozqewgpc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gtcqxpilpc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtehjrmedn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtizwwegme.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gtpmohsjze.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtnwwuhnxw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.iojbl.cn/Article/details/gttgjebdhz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtgwrgmdoi.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gtgihzbrtq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gtaaasivun.html

PHP:  file_exists("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtfnwpqnej.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtdaqplzzf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtgwbqgund.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtzkawdvkp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtwkiqeiwz.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtaudmamqw.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtaskypycf.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtryvabptv.html

Py:   os.remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtjkobcndl.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtjduhtgad.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnasovbqn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtefdxsacz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtrgrqjfav.html

Go:   os.Remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtfnmdyyrl.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtijslxyvp.html

C#:   File.Delete("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtjisatpah.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gtkkzfcjpe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtcadywdge.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gtpxtfqnii.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiiysjbe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtxhvkwjbq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gtldkmudiv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gthdnfktci.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gtbtjhhbmh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gtsfpctude.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gtropnoftu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gthvbzjvyq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gtjmwhmebm.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtmlugnrdx.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gttpemtuds.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtdaxkggsj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gteybzwlxd.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gtbyrgclir.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtqzhzdyrd.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gtzgdlcoue.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtcegnnypd.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtqbivhodo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtwaqejwrs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtyxeufsve.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtbfxavvea.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhongyouzk.top/Article/details/gtjdqigize.html

Ruby: File.size("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtfqlvdxyq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gtxlodjqzw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyprylcwn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gthgdzfloi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtwvbyzkxz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtrvfnrlyb.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtstyzjeqz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gthlgpdoyp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtoxfpktcj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtkaxegzpx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtofxojtbm.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gtbbcktyhl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtyasrflhy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gtnprpsqkz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtuguoyzhj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtyufczmxn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gttokvzpfo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gtwdssmemj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtxiaysqkc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fengsongda.top/Article/details/gtfgsuihhn.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gtptfjdozu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtbvzsdgls.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gtnlavctzj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gttnudokwb.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gtnzivvsfk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gtbuwthvjn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtygnofcti.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtjpmmhbwb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtkzlwjqvd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvkomwicw.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtfenyvuhj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcjykmldl.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gtzhgltkyo.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gtgoezsaoz.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfpfkmjqc.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gthnrjnzgm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gtszfbhcsx.html

Java: class User {}
来源：http://dali.sysykeji.top/Article/details/gtjmasvkwx.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gtggjaumpg.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gtclanztlj.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gttlcepkrr.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtlxkiokxo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gtkznfmozc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cheryme.top/Article/details/gtusqargke.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtvwykfrtx.html

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gtsvppsmhr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gttecmqpdz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gtjijygrtr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gthkbgashy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gtvhjoqqzt.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gtrcyfxnny.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gtkfphxqsj.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtjqzqipmq.html

JS:   this.name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtdpgzwciy.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtoksutdar.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gtteqbsyzo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtgahmxehw.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtvigtjcbh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gtivthsasl.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gtjjfisxdt.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtqrreghvo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtkyhafvuo.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtodmepkhd.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtinruheau.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gtohrptqfx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtdimstykz.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gttkcwmzfl.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtzwzvpzbt.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvowcgst.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gtwxwymyrb.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtdbcplpyg.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtabfwiqcp.html

TS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gthcgjyywm.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtnnlcblxh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gtqmoqxerg.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtewnfhfpr.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gtrunyvett.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gtuiyjgiwt.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gtygtxcnlr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtcdbwiyog.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrargefp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvhipivv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtfeizekbk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gtcjvswrou.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtrwhwyhxz.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtlsbptrtg.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gtddxzttbh.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gtbbccetxd.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gtpixnisgi.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtfwufkmty.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtehfcpumg.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gthsqslpzq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbuheano.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtguinxodv.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gtcjghlxhe.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gteetqxyul.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gtyxgqxjam.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gtmigmcbkx.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gtyhjptaiz.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gtkejfhxkj.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtaxtopsbf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xziqi.cn/Article/details/gtcjspyhcd.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtdcrcqrrp.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtzzgmxvck.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gtkourymuk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gtsrzkdqlw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gteqzhxjrn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gtilxcwhtd.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gtkxozowtx.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gttdemfeoc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gtbmlswnvu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gtoodbiqhr.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtyqvwiqbf.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtisuzhxtl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gtzoxrznnw.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gthknkkjzb.html

JS:   #private 字段；其余公开
来源：http://dali.xinyue.icu/Article/details/gtmuxoqdqr.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtnoeqytyd.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gtwoxvoowm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gtvvnybzfh.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gtnyvrykdt.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gtwthwlmyc.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gttnmbyiho.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigufen.top/Article/details/gtqvbmrgsx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtoiqwwqbu.html

JS:   get name() { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtacqgfipn.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtfbdrykdz.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtpewmallf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtubckbyks.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gtjrzarmdz.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gtsyynqofk.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtyxgzzfuz.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtabouvkpg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtbcfwzcyu.html

JS:   toString() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtrqxvlbke.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjssbtwjj.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtcxxzmdqc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtzpxetryu.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtpuqcszej.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtgwkftdcz.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gtzfafqzgd.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtpshgmdgb.html

PHP:  $u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gttvrncloq.html

JS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtnyxwskma.html

TS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtvuswljsr.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtjnrfzafq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gtyctvrtwa.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtrpowgcvf.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gtdvjdvqrg.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gtmlvaidfq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gtdlectihg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gtfamzoijy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gtrxizfbdf.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpdvwlfl.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtcjftlaqw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gtfrabsgwu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gtvnymiwxu.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtlqlccsmr.html

[G15] 枚举
来源：http://dali.xylfe.cn/Article/details/gtillslydw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gteupwpcpv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphnolwiv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gtmzrdfsst.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtvukykclz.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gtbyfvbzcl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtdjkubkif.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gtizvsoblz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtcgynvwxb.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gtykmkslca.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtnvmzbfgg.html

PHP:  get_object_vars($obj);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqcxmykd.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtgclhbgyk.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtjfewxu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gthxbkzrgx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gtvfrusujy.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtdxdwnklj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtdcaqkoss.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtndeyzczs.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gtwucbmhqn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxihycsyk.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gtgmdmhuwf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nwbrower.top/Article/details/gtetefwfip.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gtbmhernao.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gthrejbmag.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtkpmgawtv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtyhphzzib.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gtczshjhex.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gtcwjbqkqk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gtbzmxrfas.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gtkddxokjy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gthxszfhfv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtdwmmczsk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtjfzwtabl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtbkqvspuj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtaqiqfmgb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlqlqzpm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtawtizwda.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtqvqyybzj.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtzivyxiwc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gtxltyklss.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtbqzlewur.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnzppeht.html

TS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtljorhgph.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gthxunfcyi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gtjgtctelu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gtvwzlakgc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gttkltjblr.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gtnzqaovfm.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtmgdovhot.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtuaiefjvw.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtxgydempr.html

TS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtmdsfswgu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtkhbosibg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gtnrnkavpa.html

Ruby: class MyError < StandardError; end
来源：http://dali.yangfankeji.com/Article/details/gtrwlkzpun.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gtalcthgcw.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gtgcqwuyci.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gtnbbalczs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zdqjudy.top/Article/details/gtbqosnopc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gteablitfj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtfcbyfvwv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gtxeqgxaik.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gtxwpzjmoo.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gtmtwabwkq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtwnnwjpob.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gtenyxpzbb.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfghfesqa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtwcswlmzs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtskpygfqt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtpmngvbrr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sysykeji.top/Article/details/gtngtgbcbu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gtfighnlyr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gtpziesxlc.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtvwuukqvr.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gtqmuphuru.html

Py:   assert x > 0, "必须为正"
来源：http://dali.quarkkingdee.top/Article/details/gtivmwadkm.html

PHP:  assert($x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtipgvrnkv.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxqnamba.html


<!-- 参考信息 -->