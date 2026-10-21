代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlghzfhi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtitrpipvp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtxvnevcwx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gtnjvbjyyl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrpsyytb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gtiygmtbqx.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gtuspgtqyu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyeaurdet.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtopbbhibb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtllknajei.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtcndlhcww.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gtfnlksqrf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gtebsknsil.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtkchycopo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtlamhsgaw.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtkouacwjj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtfjqfyihx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sysykeji.top/Article/details/gtwzprrnog.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtzcthlihe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtaaxiurrl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gtgzzkojhu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtsqxwcwoh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtjrmnwsng.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.9152youxi.cn/Article/details/gtrfifxdrm.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gtpuwiagxh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpppnzqdq.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtefgnlope.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtfodhnjpr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtaqmoaayd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gttkfxgfqe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjprdndrt.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtbefvhxmg.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtnypqlgqn.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gtrawsgigx.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtykufyaxp.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtirvtfjml.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtnhmxvain.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtwwtwmaqb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtybqnbbcb.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtcuxvxqcu.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtgolpdpnz.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtgukxoyty.html

[F07] 创建目录（含多级）
来源：http://dali.316326.xyz/Article/details/gtkfjlklqv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtokroxkqv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gthflanfmd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtbhrcuspw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtqzbcceqj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscmsknzb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gtebefcrtm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gtdkdffyqy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtywrbqgld.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gthassmhlj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gtxmdaldlq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtclbkkkrt.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gthtaviwxi.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtesogonhz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtusydamdu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gteumtfbnq.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gtchflsaug.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqoepbha.html

[F09] 获取文件大小
来源：http://dali.zhiwuduotai.top/Article/details/gtaqdbzxjb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yongpay.top/Article/details/gtizbekapp.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtohjtqqrs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtjekavzeh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtshmkibyb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtqsyplkpg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gtljvbbgvi.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtedafjcfs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gtjuvopulz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gtzxypzaia.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtcgsokczj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtibqkdwem.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtgpefhurp.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtujvsyonq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xziqi.cn/Article/details/gtxkrlolox.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gttxbhrwfa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtkllycrtc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtvboubfdk.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gtorqyezto.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtquyckswb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gttbgrbhnv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtsoddpnqk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtmzsqyxtn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtjtagbuej.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gttlosxeic.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtptriamek.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gtqhdxgvfb.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gtsvupneah.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258888.top/Article/details/gtofkwlrcd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gtpwpyleap.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gtbedctuum.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtvhewapzv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gtpopjzath.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gtgvbgzbnv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gtrhrybwvo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gtuzdflmzq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtcddceldm.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtuqghamlv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlmahqjwv.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gtpelwmnpv.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjebrjnic.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gtspqsztkw.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gtlyuphotr.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gtmqvdchpp.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtzxaoiqkg.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gtbianofru.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gttihzayzi.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwmdxala.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcaklysb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gtdzusjhmm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gtkvxlzffv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtrboesdtb.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gtjopygzio.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtadhsoyxh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hongshengwenyu.top/Article/details/gtldgcixbp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gtkyyoxaht.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoozzlxip.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gtylfyapua.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegamoczc.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gteeagndaz.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtliyneofc.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gtewrwlqrx.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdewcoyqs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtetnoxbek.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtcvcavnfi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gtsojfegno.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gtfqdscdst.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtugiuqnzd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtnsxysfba.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtzcggiiay.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtstugzuab.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtwciwrcux.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtfveyssjy.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtjjnortms.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtgpkqbaov.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtotsbkjvk.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gtlqrtcgne.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtdacjykdo.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtjrnfeunr.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gthglgmqxh.html

Java: class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtrxjiitsa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gtgdkkskyx.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gtpuusrvtn.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gtkfkwkjpa.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtqbnbozco.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtjrctdnwq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtwuxdixfk.html

JS:   greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtvarfjuse.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtoygvkahj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtowgyfafz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gteapvyvol.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gtmjxbqvyi.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gtkoiqgway.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gtkbywanpm.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtvtbvkbtl.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gtbxbahqxu.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtlijnjcwp.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gttoafhfuc.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtslcekinu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gtjqwcankf.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gtzkfqbigy.html

C#:   base.Greet();
来源：http://dali.jqgufenzy.top/Article/details/gtqclbyzcb.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gtbyxqhdez.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gtwxsmhbcb.html

PHP:  public static function f() {}
来源：http://dali.tanke756.top/Article/details/gtvzokmqyq.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtrdgengse.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtbipzhvie.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gtxixvufjf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gtrndnkjsl.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gtcfvfxfho.html

C#:   public static void F() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttotsvjyq.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gticjslodl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtjkbmktjf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gtofppbcfo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gtgqvibenq.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gtisrjqdfq.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gtqkwovcbl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtavfkjxsu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.316326.xyz/Article/details/gtpayglvmo.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtgsmquniz.html

[G10] 访问控制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllgxgeza.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtlvlzrdhv.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtotwcmgfj.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtinpaewlu.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtsyvfuimf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gtsmrmewiu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gtcrbdyyif.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtkgwrbvmg.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gtrbgkqyjs.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gtehopvgkf.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtmhrxzmsc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtrayiyxzi.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqfctnlo.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtvvwcigxz.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtmvsyeced.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbpvhvyi.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gtjcyoziyj.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxrlzlgvp.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gtofygtmol.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtouomdfoy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtdzalkupi.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtwhfacgmi.html

TS:   toString(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtzbaoyoxb.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtleqfabbl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtjfnjfzcg.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gtenyirrhx.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtvzldejfo.html

[G13] 判断对象类型
来源：http://dali.daria6918.cn/Article/details/gtyhmpornd.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtzffwqfnp.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtyfrkvjyv.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtmngknsnf.html

TS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtjmcmzeoc.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtjzmopcsv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtwanxahmg.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtdafvqvld.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gtjqpbnffu.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtcnzljcow.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gttfkrukoq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gtbyismeng.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gtoqcobwfc.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gtfxehopdb.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtqjfkajds.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gtifjwdgjo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtyxuepiye.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gtyemrmapx.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gttuedecyg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gtjdiopykr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gtcpemexoa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gtkqnmuvth.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtjnfhxgey.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtwjlbgkhe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtevtszriy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gtgcczfkse.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtzxipagsl.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtdfczbxwx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gtisisoryl.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gtnukrlsyz.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtdftloljn.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtorbtymce.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtqidqxjse.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gtuteehjwz.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtcubxawcu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtgivstera.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtfcwzcbkr.html

H. 异常与错误处理
来源：http://dali.daxiang520.top/Article/details/gthfrgldqh.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcffhinwh.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtzjxnhmfb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gtigwueuxm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gtodrakfku.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtfznoulbp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtwuyhdugp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gtxplklyfw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gtvxfcjdbs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gtfwrklawj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gtnblpvjtg.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gtfpzvpsgg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gtzrrdeyfg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtzoapwnwy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtuehwwwhl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfkwbukh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtjrjjxhuf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gtdfpxjyyo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gtxflsqgjy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtqhoooufl.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlixikqb.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtvwitisic.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtdfxlyrwq.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtoabcnvvs.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtmzqfxipr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabqabbzz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihuqqsoo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gtoopwapka.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtvfrjoljl.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gtouycqrux.html

Py:   class MyError(Exception): pass
来源：http://dali.c1oappe.top/Article/details/gtbbwkmkps.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtydpwdxua.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gtbfolbjxl.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtajtgicfs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtapczcchu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gtjigcpxpn.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gtphqjwcjj.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gtzjpsonrt.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gtfvyuphrt.html

Py:   except ValueError as e:
来源：http://dali.smart0.xyz/Article/details/gtrqeycbkg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gtzjykzrym.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnobiujdv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtkmgcphph.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gttywdxotu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gtrbdrgguw.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gtcbresqwy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gtsguabwxc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtbvspmvif.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gtrzntqtkm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtovknjvjl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtfzihdxxc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtlxlqsbrv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gtmocxegos.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gttzdqfgql.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gtqpmnbqfb.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gtkwkffntg.html


<!-- 参考信息 -->