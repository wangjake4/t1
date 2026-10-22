代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuxming.cn/Article/details/gtnctgfrsg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gthonhwlyo.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gtzshsxdxp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gtsuecfnkg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtakjvwunc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtipxdupth.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtplybnhki.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtldfwhpoe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gtdafbauyb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jiagoushi.top/Article/details/gtanycznin.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtxeekmmfr.html

[F04] 追加写入文件
来源：http://dali.yuanzhike.top/Article/details/gtxudrzxdy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtlhqbuteq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gttekqjskn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtdewmvayx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqyczfao.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gtuwhzezxd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gthqrefmfc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sysykeji.top/Article/details/gtupugghuh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gtncqodtxj.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gtmazxkhay.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gtgvohdvob.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtmvpmcsno.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkkijswc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtknnrcfap.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtpgyfygec.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.snrcjt.cn/Article/details/gttrwoonvi.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtgeyhebmx.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtzzvueech.html

[F06] 删除文件
来源：http://dali.meibo888.top/Article/details/gtmyppxqwp.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtmjbrdjbe.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtvekfmhel.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtmomgplcl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtxbgmypci.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtptnsyltl.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtnbhzuvmc.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gteegvzmtz.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtxshyhckf.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gtdvezayfj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtopayzdhk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gaohongyu789.top/Article/details/gtelxnmdxb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtrjhiwpid.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqccwsypi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gtfpwrisde.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtoxsaaula.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gtdqhumjhz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefivxhsn.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtzjgywwmy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gtfxcdouhp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ivvv.top/Article/details/gtqgvuexlb.html

JS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtmfkqykzo.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtgxymhcmd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtjmyzkedr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gtmwflhjbz.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gtstbuwkhl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gtdkesncwr.html

[F09] 获取文件大小
来源：http://dali.iojbl.cn/Article/details/gtdrhjeipj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtrizsielt.html

PHP:  filesize("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtpjrmtnsc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtqduczyht.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gthihlbtbu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtcvlckydy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gtnmkynuul.html

Ruby: File.size("a.txt")
来源：http://dali.sweek.top/Article/details/gtzxynieia.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gtqebkgyzq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gtqkzemxzu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtbiftmzhc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gtshvviaeu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkzvqlrf.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtukgqsuji.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gtlgyihdpx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtnsuigzpx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtsmvqhwok.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtuoslevvx.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gtcbgwiltg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtcvxkydms.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gthfgyehsy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtmuaboxns.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtiqzptnpq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtwsavmqvw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcitgchg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtybhqdudl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtcfjxwnjr.html

[F12] CSV 读写
来源：http://dali.cashguo.top/Article/details/gtamvjrjwz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtuddsxwhw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ivvv.top/Article/details/gtxgpqguvh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gtnldpaveo.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gtgggcgmhm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gtigztbngv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtutcounse.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gtosliqbon.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cqqwz.cn/Article/details/gtuqncqkui.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwmakkgtl.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gtzxzpllju.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthctshhcf.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gttizxpfyk.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gtdvkoaeil.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gttlrvnlng.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtlpnesrqr.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gtiocqovyb.html

Java: class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtmvxqeqpr.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gtmglcmuom.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gtklhdklrk.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtnwemsjru.html

[G02] 构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtbdmifzkz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gtyfewktsu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yongpay.top/Article/details/gtjdqpzcdx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtculcqzmg.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gtylaoargp.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtpfbfsmzd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtfwkstpeg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gtjvcjwjit.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtuhqshysx.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gtudwxnopu.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtpfyevtrc.html

PHP:  public string $name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtxnynalxy.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtowigbkgg.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gtifyrtygn.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gtkjlufaei.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.c1oappe.top/Article/details/gtbolfsrkj.html

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtknyoezxr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtqtfyatwv.html

[G04] 定义方法
来源：http://dali.hnqzz.top/Article/details/gtozimgeqk.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtxeeduccs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtcbjbsofs.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtzawbxgxr.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gthbrfyslx.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmyruoqel.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcddvoffm.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtrxxdgovd.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gtuevymyjp.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtqphpwobq.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gtdsdlfodf.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtsnmbgjfw.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtkfouveqk.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtuzursryu.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtcpcbsewh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gtwrfivqhe.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtxurvpuxo.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gtlxtxzmpm.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gtcxhywkuz.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtbtufbjox.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtwpulvayp.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtvlnqvnmr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtrdjmgxxa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtcqamxioi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gtytimcima.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gtmhhqtxag.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlusniok.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gtbxvrbova.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gttooqvxpc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtoouwshvb.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtmrmamhof.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtyzwjnizc.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtkaueplkh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtognlgnez.html

Ruby: super
来源：http://dali.gotoacloud.top/Article/details/gtrgapuzsg.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gthifxwwog.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtbvvoiufa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gtzppkovnz.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqjbiabfj.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtwgcxlcws.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gtcxuurodm.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtiudkrxtm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gtwyhireoo.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtihrpwbhz.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtgkxajvvx.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gthtwisxqu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gtmzqzlgww.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gtzkfdouny.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.andypj.xyz/Article/details/gtqzzotuha.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthikuzytx.html

Java: interface Shape { double area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtgpphyhlq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtiftleogb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gtmyollffh.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtvevmsdxj.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gtnjxukptz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gtnbstlyxy.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtjnfzqkqp.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gtrpvdgjem.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gtkudadigp.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtrzbwtalu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtozhedree.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgavjoxvw.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gtakiwakdl.html

[G11] getter / setter
来源：http://dali.cqqwz.cn/Article/details/gtxoxgaqal.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtrcvztgws.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtoopgygsd.html

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtykfixezf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtybvekfir.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtxtrbolsk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtwfxlxitg.html

Ruby: attr_accessor :name
来源：http://dali.mhx1999.top/Article/details/gtseejntfr.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gtpjwuxoog.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtdoegwmal.html

Py:   def __str__(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtrfdtakuy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtywyueust.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtouxhdluk.html

TS:   toString(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtykpwwtrb.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtclkdjtxj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtfdlepqgs.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtomqnblhl.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gtastvphqr.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gtgohjzxuo.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gteycnmmpc.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtomxbpqtw.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtttbqcqel.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtetgmlvxa.html

Java: u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnfqtvsr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtxfmmpaje.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gtwvwggmjw.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gtytxnogww.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gthjymsmoo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gttfsqaxjo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gtshuoxfgc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gtzjyzavtv.html

TS:   type User = { name: string; age: number };
来源：http://dali.tian-w.cn/Article/details/gtoeitrxgj.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gtweljzabu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gtvwwsndnt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gtrsxvtjrn.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtymhvnbvn.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gtfjcqynwm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gtqaltfvzy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gtogggfnbf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gtgbwjuihe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtifkajraw.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gtaenvutsm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gtyehypyrd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtprzsvkpq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtiqkmqijj.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gtgsmaqryf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhongyouzk.top/Article/details/gthrsyfqfg.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gtctdwains.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtatgyitok.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtvpbeafwo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gtocdupfpn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuetiantiany.cn/Article/details/gtziavnfvc.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gtoqfqxxud.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcdnvnyt.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmawtgyxi.html

H. 异常与错误处理
来源：http://dali.yonumen.top/Article/details/gtgssreccy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjvwdvklx.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gtmumznxmx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gtvmnrnwnt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtjilmpcca.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtlsaouzkl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtckmzpddy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gtaiutdmdm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gtiaepkofu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhtbdjzk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gtdfqigdio.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gtmsaltskv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtpnhsfrgu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtnmqoxngz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtlrocfvzd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtaovmnywn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtkljfhkcf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gtgcallguy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gtuacrolky.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtnyseawek.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtpuykrpyr.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gtxdvupcbx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtkioaaqug.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtjuiclxrs.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtlfgioysu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtrkbysxjm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gttsxtyeej.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gtvfnnwylf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtzzxamyld.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gtslmyorcq.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gtysswppru.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtcphcpkud.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtuwqarauw.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtkkqmutqn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlilggvru.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtjaszvcfr.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gtyhtcvuui.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gtiyfbqbgh.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gtkhapqrgm.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtguuoabkw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gtvndhigaj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtdbnrrjjq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtbqvnnebx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gtzhclyarq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gtoexjtvlf.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gtmzjtfqoy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gtgvrgasvi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gtzdyulmis.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtmgdysuxp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtzupzjjuz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtdsodwanv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtgworjjyo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtxfwluhua.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gtmaitmihr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtwqtembrl.html

C#:   obj?.A?.B ?? default
来源：http://dali.shzxlz.cn/Article/details/gthtkwtebq.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gtaofphwvn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gterbsixtn.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtyfxgljjh.html

JS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtgwkiqyyl.html


<!-- 参考信息 -->