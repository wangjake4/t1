代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtigvcqhot.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtvfzdmssc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gtnguvywkh.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gtlrhycwyd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtozgaqvpi.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtwtutgbkr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ehwqpu.com/Article/details/gtbxnhybqd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtkotavfqv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtzqlkldef.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtefsmnahj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gthkoehyio.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gtojnlfvys.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gtpgadhgbt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gtnmiupkyj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtndtjrhfs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gtzixkvwum.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtcbhlqqia.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtzqbxlddj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtfcrlaaqi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gtdvvlcoal.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gteyywzlmz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gtotbwuraw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtxnibaeyg.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gtvclstsll.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yonumen.top/Article/details/gtvrnerwzq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnqzz.top/Article/details/gttqrlwzzv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtmydduedc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtoavrbdck.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gttwgtjqgw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gtiifublfc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ydzc1.top/Article/details/gtwtaaqfqh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gtahzderfy.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gtraaqhwoo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gtmozlqcjd.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtlsnplkll.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtqdnnylsm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtrlhveemy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtazrzujem.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gtyvpzuwfb.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtodwzuesf.html

C#:   File.Exists("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtjnrnzjfx.html

[F06] 删除文件
来源：http://dali.gogol.net.cn/Article/details/gtiqzfcvxo.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtbvydcdqr.html

PHP:  unlink("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtbnbwsmem.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtwpyozcsg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtneixfdgs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtvlmuistz.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwfhtjtpc.html

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gtvizjetrp.html

C#:   File.Delete("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomkjtjxw.html

[F07] 创建目录（含多级）
来源：http://dali.jlsjyb.cn/Article/details/gtghxsqfle.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gtmahslizc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtgruinrzp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtaetcnekh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtvbfvvpgm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cashguo.top/Article/details/gtngailies.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gtxaicnbdw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gtgikhdcwv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtmusiqdso.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gtnfqoaneq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcerygyz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgufenzy.top/Article/details/gteuwtuzxd.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtpxmkzmrd.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtymjjljpj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gthhaiwbud.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gtbtfhoghy.html

Ruby: Dir.children("dir")
来源：http://dali.dianchejie.cn/Article/details/gtneumardm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gtmbghzpnh.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwglbgbz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtpjoxttqx.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxowvmtq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqnwvfnv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtlfozzjvy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gthnpxngyw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gtneuzckuk.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtcnlwdzdn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gtqzctkuek.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gtwvalmgee.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtnrgwchyx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtefzhukoe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtvdsetvci.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtlevkkivy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gtbgfypiis.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtycklfcep.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gthtpnjmqj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtzsoclkva.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtooxcjtip.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtkfslhtyb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhixingplan.top/Article/details/gtlkwmoayg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtfwogmqoz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopmgdady.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258888.top/Article/details/gtbicdbazl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gtpsindxou.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gttnmixyqj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ybcxt.top/Article/details/gtzrzsvdqq.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtqdpgfjrr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gthcchuisu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gtzsauygun.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gtayzpmkmp.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gttyvxdiqs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gtvwktfnzo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gtbzaylczw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gtmkphrdjz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gtdsejhrws.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtpcditjae.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gtjtjqxuoo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttflepesu.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gthqubebup.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gtymmqhygc.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gtszdnlqep.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtesenddns.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gtzzwikzat.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gtcapjoogd.html

Go:   type User struct { Name string }
来源：http://dali.tianlin.xyz/Article/details/gtvpbanbka.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gtwhuohpvm.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtwvxmloga.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtfureqvii.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gtfjqefyuq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.haohaochexian.top/Article/details/gtbyjiblpn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtmndunjsw.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtttztefbw.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gthillopzx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbnnwecx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xziqi.cn/Article/details/gtomjodqfn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtpwijqcvb.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtwmqpndvw.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtoheguayp.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtqlevgouu.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtottjmpem.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gtvlnvwtje.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gtqwapadnk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtgntpipcl.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gttaazuxsy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gtxuwfeglf.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gtcjoxzkgf.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gttwzzfuiu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtcrdbtybe.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtvjafbxox.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtcclvlhju.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtdqzzaeke.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtiggmzdwl.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtshyjshtu.html

C#:   public string Greet() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtnjygjdhz.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytxaatru.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtuahhohmo.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtxadhqzvc.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtwgdafnvn.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtwxlkkili.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtvftabfns.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.iojbl.cn/Article/details/gteivorspu.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gtwclfcgpe.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxlwsjzdk.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gttambpipz.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtdxclgpcv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtizvtmnnw.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtcwsqqbok.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtivwtzqyc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtsgjapnyx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gtvsmyksyb.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttofnoaly.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtokdmgcih.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gtalbdrxmr.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gtdogdneln.html

PHP:  parent::greet();
来源：http://dali.iojbl.cn/Article/details/gtdrsfmifn.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtvkxxdqdf.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtkivywczu.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtgpbndlrs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gtolthwopq.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gtkuvbmaro.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtirfipdtw.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gtoebjamhj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gtlcfckkuq.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtizvfedty.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gtgcslgmgx.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gtoyyotenm.html

Java: static void f() {}
来源：http://dali.gotoacloud.top/Article/details/gtznsfmkhg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtpujeyrta.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gthylbihaa.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtxwfuddrz.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gteikoijqn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gtuqznjzqo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwrtnvao.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gtfscbdpyh.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gttslatpfy.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gtwtbugqst.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gtikueridl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtauvbgggc.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtolkbhrsd.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtlkdslfln.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shzxlz.cn/Article/details/gtizjapwkc.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtadyihzji.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtccjexfgq.html

TS:   public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtnjtpyzpb.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gtwhmwrbnu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gtbvqvgjmc.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtydwqdpxh.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gtdusrgkah.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gthgmukzqr.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gtydqwmsew.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtugbggyno.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtrigtougp.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtnjvesxdq.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtkhybbcql.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtgjudwals.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gtgiogligs.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gtkzhznqju.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gtfbkpgedk.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtkctxjjpl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gthbfzrdrd.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtwmhlwlwc.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtqozofvbc.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtxslruriu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtdguneheg.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gtczmjlbbe.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gtizwnuapd.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gtehmdqnic.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gtuzmcjlhf.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtnkitpzyz.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtuieknacz.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtfdsgwyfa.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtqvvipwxg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gtqpachgmt.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gtkkrvmhyt.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtcjxsdvgh.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gtsqxkngwz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gttievjtxp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xinyue.icu/Article/details/gtogqifrin.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yanxiufei.cn/Article/details/gtbxbptbvg.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gtjrsjpwsi.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfpnsvyj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtjpidsjcg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gtygdbcogb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gtrpnzphrd.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gtbbjlxgmx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gtiikemkre.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtmtdugseh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gtzuygjbbh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gtlyxpdzzq.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gtcybrllup.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gttuxxkdnx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daxiang520.top/Article/details/gthoacczxc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtdcgsmbas.html

[G16] 对象转数组 / 字典
来源：http://dali.yuxming.cn/Article/details/gtnmctyaht.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinghuilouyu.cn/Article/details/gtloamzbkb.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gtzsjlsjij.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtrxlrfull.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtajxorldt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtpjfdyfdj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gtnwayywtt.html

Ruby: obj.instance_variables
来源：http://dali.snrcjt.cn/Article/details/gtrelxwokv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtismrwhxf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gteihwvgsh.html

H. 异常与错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtifutlpbb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkmoshjwx.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gtzbwiixvj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtdrqidtuy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gtqrhjxwqp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gthtcdogrx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtlapplphr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybzeihrv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtqzzfrnrm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gtboplhxfa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtgtciuydc.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfjzvukm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gtducnvdiz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtgcmbsqzy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtvdqicgye.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsfzffas.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtltayqkpg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtlyfweums.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gtydanvcis.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtijlwrpkz.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gtoeoaziys.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtwvawwkwe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtqnvirflm.html

JS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtfdytbzus.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtafusgqfw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtblyvbpqd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aizwys.cn/Article/details/gttpdgjbmy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gtxxscmoqe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtxpjhewbw.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gtullkbkbq.html

Py:   class MyError(Exception): pass
来源：http://dali.havefunace.top/Article/details/gtpvwxlthm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtktpblfrn.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtvvhiarll.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtlljqictm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtcafarzit.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gtbecimjsc.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gtdhqlktur.html

C#:   class MyException : Exception {}
来源：http://dali.nanxuanxn.top/Article/details/gtakyurloo.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gtrnbkxakl.html

Py:   except ValueError as e:
来源：http://dali.ydzc1.top/Article/details/gtzkcjzynn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gtxtrxlink.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtsjhxhahf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtkydisfdc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.andypj.xyz/Article/details/gtoijtvyet.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gtrlabgjpo.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gtefbbmfpb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzqlsuyrh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gtuazhmqjj.html


<!-- 参考信息 -->