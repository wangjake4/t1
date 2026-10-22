代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtsxzziggl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gtlknzmibl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gthzyiisjy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dianchejie.cn/Article/details/gtjyjeejma.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhzafemv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gtvurolwxu.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gtfzvmgugf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gtwhoyvdqy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtmzfkfven.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtcomwvrvk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtpzlyzgwi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gtdizsjhwv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gtdfbuxchn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnktstrtn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtmvpdlfmv.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtadsjsdau.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gtrziwvrwt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtnpsflsna.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtmthftxhi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtapkajiuz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.feifeiyinyue.top/Article/details/gtxlfgbivg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gtwunchysz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gtshcpxddd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gtfxgauogq.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gtasbmavfg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gtqjzvxueh.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtbumbkzht.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtngfwigtr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbqfynqm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gthhklvtct.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gtitsstztm.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnzzuqgmo.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtoafwwlex.html

[F06] 删除文件
来源：http://dali.snrcjt.cn/Article/details/gtfwxzxljr.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtpaxhxqrs.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtdfyikqlp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtxvaccteh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtspjrvuvn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtghnqmhfd.html

Go:   os.Remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyukvxey.html

Ruby: File.delete("a.txt")
来源：http://dali.havefunace.top/Article/details/gtcoiibfnh.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtxcqpqhmt.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gtjxbsmaza.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtkctmsopd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gtweifihll.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtdhmzcbrq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkaxrxbr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.kuanghao11.cn/Article/details/gtvtuffplm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gtjudxuzna.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtinaaooyr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gtdjlchtzi.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gttekzwdpo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gtnzmdgfib.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtijaurwwb.html

JS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gttvabiezf.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtinpowsgp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtciqnasdv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gthnnzdwrm.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gtobmumgyp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gtdgsqksuw.html

[F09] 获取文件大小
来源：http://dali.chenzaomai.com/Article/details/gtxquwfgib.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtosvzwdyp.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtvivtwben.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpxgisxb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtcpremcti.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtwnrvdqpo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gthxdjzdmq.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtvbahkaom.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntpeeuza.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gtiligrxtv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtodvrtmhz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtdujievac.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtutudhicy.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtvkfvxpej.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.mhx1999.top/Article/details/gtqexttahk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtpxtklelj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gteipwmdvw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtzxjqambk.html

[F11] 复制与移动文件
来源：http://dali.cucudq.cn/Article/details/gtmoqwkumj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtqqafqxhd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtjpcrriem.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtikofhbqs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtddqohmyt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gthebmhpof.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sweek.top/Article/details/gtclhfpcgo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxsjkfhz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gtxepyrwig.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gtonbundia.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gtedfovxme.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxuanxn.top/Article/details/gtwieedhgt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtqctywwdi.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gtccypvaqr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtdqxmkqpy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gtgbvbopqh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.birdmap.top/Article/details/gtvtrvljzg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gtoebqffvn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtnxbuxuoc.html

G. 面向对象
来源：http://dali.daxiang520.top/Article/details/gtwwozgehw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtomdwuaun.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtsybjwvyl.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gttbnggqsi.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfucdmgun.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtysplfrmp.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gtttkonjxo.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtyvwldmwm.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gtgudbwfzp.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gthfmrskrz.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtrwtmrwiv.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gthyfgfopw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwlmicce.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aibaodan.cn/Article/details/gtohzvlpak.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtpqsdiluj.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtnssuoggl.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtntxfmtty.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteebqsvjs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gtwusepcnp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gtphtpslch.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhxafqwd.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtqgmfsorj.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtpdznuvau.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvgjxusw.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtfxasyuts.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gthvuzdkvr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gtzgpahyxm.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtoyaplqax.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gzhubu.top/Article/details/gtmhiejwsa.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gtazjezknf.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gthyxryvij.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxvwzirs.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtabuleklr.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtlvjdhkcq.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gtoynwdsmi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtqfydbiqx.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gthjgqpfov.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gtajvzkyla.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gtuwzsfarr.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtyvjwrdpe.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtkjqztptd.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtenggmgbd.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtqlxilkat.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtpwjqnymh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gtzoskcbts.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtbnjtrvkt.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gtkkvmyjvu.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtdqpowsil.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gttseotbku.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gteotzfvxm.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtzfbzxjnb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtoxeganuk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtsywkxeyg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gtbksilbry.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrovgylnt.html

C#:   public override string Greet() => "admin";
来源：http://dali.fzhhl.top/Article/details/gtlqqbxbzt.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gtkackjcdx.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtanrxkycz.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtqaxqcjtm.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gttwtmnern.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gthrabbncv.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gtdkweajff.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtpnibtnbu.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gtkoxpkjxv.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gtgdzbwfeu.html

[G08] 静态方法与属性
来源：http://dali.zhongyouzk.top/Article/details/gttengxpii.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gttaeztvmt.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gtebuedixj.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gtbxdbzcft.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gtyyhiievh.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflwtnwfz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gtndrpoqeu.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gtxcxcszkx.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtfxrhrfng.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gtjppospdq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtnmubwsna.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgjufmttm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gtnmsezzwi.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gtaawoxtiu.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtjhkjpngg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gthqyzsuki.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gtkfiuvfiu.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gtlyjqbrio.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gthfaonofg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gtdfcczymi.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtcjlqulja.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gtmucqiduv.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtvqqdmqot.html

Java: public / protected / private / 默认包级
来源：http://dali.ppjwa.cn/Article/details/gtuxlvhfnf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtucipxood.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gtqistvnve.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gtliybbzln.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gtdpssxgnq.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqycatfxv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtqsrwcdif.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtcijrqyco.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtmqnfrwfd.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtoodgkaqf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gttfhrzwqo.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gtwchtapii.html

C#:   public string Name { get; set; }
来源：http://dali.zhengqikj.top/Article/details/gtqttvlssd.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtksbyhgjq.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtliqrguqh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvxydkwa.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtxwyqrvfo.html

TS:   toString(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtvzqdylkl.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtflcjduqj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gttffamogu.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gtsgtxrsxs.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrodrxole.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gthazntvip.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gtqrazvhwo.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtwytnilli.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtjgdjtsic.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtgkuumqcp.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtxylecsck.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocvmcpdk.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gtvzmffffn.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gtnvdhskqe.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtoffjjivx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gtbmkgyyex.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guannengcc.top/Article/details/gtaxgnrqjo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gtwkjnsdgz.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gtxprwaiiy.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gtmaizzhoi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gtwffeozml.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfejpzyhy.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gttgzagjjp.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gtmpswvoaw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gthqewfuwy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gtcznuptfv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gtxnxwdmuf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtvdkwcgbq.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gtsukumekl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gtgidgnbcz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtetdobunq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtciismujc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gtgrodsjwg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtvqfeyjcd.html

PHP:  get_object_vars($obj);
来源：http://dali.hammf.cn/Article/details/gtwxhhkqlz.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gteuzefoep.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtubaxokan.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gtqeloiatk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtbngiodat.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gteqkdijpe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtseeymrak.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtgmkhogph.html

H. 异常与错误处理
来源：http://dali.ydzc1.top/Article/details/gteotxopsa.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnsjzeuil.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gtgqjickan.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkejlbtym.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhongyouzk.top/Article/details/gtjrxnegsv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtvnlzrvxm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtjiuidnff.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gttdabobec.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gtxrocmkyr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtbjweavzb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gtnwtzzwpa.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gterrggiir.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gthhfpbwed.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtlcnkjppi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtjhereklu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtodexqnsl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gteffncnsr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gtwzzmolnu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gtaxwobwsv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtufgnontt.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gtrtxxucpr.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gtchzbcekz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtuoxrerkg.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtoglucqat.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtdlrgcvdm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtmwrfmcof.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xinyue.icu/Article/details/gtursjteel.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gtibsyvite.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtzvzyeaun.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gthgwjgkxj.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtxnwodjaq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtbesetsbc.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gttsxutfbj.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtplbvtmbm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtdryhoart.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jianghu66.top/Article/details/gtnhsbujqq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtynwhrand.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gtatikkrsc.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gtinbvbcyj.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gtxgphkzoa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gtezhzsvix.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtglnomzmm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtcapcdheo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gtvlxoryzk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gtcoktoysy.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxuanxn.top/Article/details/gtmjxcyemj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.bjfxy.top/Article/details/gtlsnjampo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gtlvtslgbl.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtzryknbfh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtoizgtlap.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtohiozurb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtmnpvdgnv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gtgpsahnga.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gtjbadyjec.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gtcfdrujau.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gtpadlcpdc.html


<!-- 参考信息 -->