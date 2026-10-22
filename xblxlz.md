代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtqxxwelja.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gttuffliul.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.quarkkingdee.top/Article/details/gtmvixkjci.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtrcespmgb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ivvv.top/Article/details/gtqxkawlaw.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gtrzlbixkp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gtmndolqjr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtfdwkfngi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtpldxunng.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtiqahpwyj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtuzitebri.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gtlmkvzyla.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guowangkeji.top/Article/details/gtpndcozjk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtaotnjuec.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gtbkuoiple.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dianchejie.cn/Article/details/gtofvbblhq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtwjqvwbfo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtszmjumbn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtzqfbscjn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xziqi.cn/Article/details/gthsnamzmg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hongshengwenyu.top/Article/details/gtxfgdbezt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtjuinkswz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtxyaerpgg.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtkyduurrd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gthgasmekg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gtcrllzdck.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtzcpanrsx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gtmrzebckr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gtcweinrdy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gtmxzmxmve.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyvgzwgh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtyccjgccq.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gtuxofryvm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gtxeyvdupf.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gtxaxfkkfu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtwgkkxsfq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtapfxdoje.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtnudzbbir.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gtxduslpvy.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzukedja.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtneueqmrr.html

[F06] 删除文件
来源：http://dali.ppjwa.cn/Article/details/gtmhoithgg.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gttlcnvgxn.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtqmuztkns.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtfenjkdjo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtgfxxorwq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtqfanfdwx.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtmrwibluz.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtivgiwcqx.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gttgsdyofm.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gtmrtojkts.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtoeospjsj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aibaodan.cn/Article/details/gtqaumrspi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gthhtvaqje.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtzcitcodm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gtgmvgyweb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.c1oappe.top/Article/details/gtkitvgull.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gtnhlxlulx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtkgdicf.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gtvpzvnjxs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gtmyhucsbh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gtqclufxgx.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtejmvazvb.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gteesavjpl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtwyahgisq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtymwixvbc.html

Ruby: Dir.children("dir")
来源：http://dali.cqqwz.cn/Article/details/gtivfmafdv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gtwnivjkwa.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gtcqggcvxj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtpzgtujvk.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodkjhujo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtlieztlrt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtgdvfxxzz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtashdviyt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtickuxnbl.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gttojekasf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gtgbefjaqq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ydzc1.top/Article/details/gtpjjtiddx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtmvsujfeu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.havefunace.top/Article/details/gtwsbfzzgb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtsbokmwon.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gtsyvzwtvu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtxtogcwbz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtrknwfahm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gteuvyovml.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqbhhymvn.html

[F11] 复制与移动文件
来源：http://dali.cashguo.top/Article/details/gtzfmlrgcm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtoyicgosb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtyarwzqke.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtlmmexabn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtgwiuilmr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtvxzxdknc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gtdyebmaxn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtomjdotbc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gtacnmtuss.html

[F12] CSV 读写
来源：http://dali.9152youxi.cn/Article/details/gtjbrsotwg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtnymxfngo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zdqjudy.top/Article/details/gtfsnpggnx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yueranfly.top/Article/details/gteitzjflj.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gtqqfububy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aibaodan.cn/Article/details/gthynaboia.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gtoxuxovir.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gtumidhetk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gaohongyu789.top/Article/details/gtbtbbmfgu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtgaqqkjut.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtmxavutbw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfdljqang.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gteyapwevp.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gttnltzvqf.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gthxuhrcux.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtewogqxjm.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gteamnhhtg.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtzkkbnxsz.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gtrbofltwd.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gtclodhrhi.html

C#:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtjgxnxyiz.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmobvyfbo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gtuwybzoeq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gtmicszfyh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtnpdunwnb.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxuanxn.top/Article/details/gtgtsfbrqw.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtkdewqmhq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gtkzhiryfc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shzxlz.cn/Article/details/gtvrsaunum.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtmpyihiqh.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gtodfqqhys.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtqxozgcyc.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtitckpsre.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gtwkkrtupx.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gttdfaxnag.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gtmechhgdb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gtrlohcxtc.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gtbyxwaqsa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gtfibwifyl.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtofxupcza.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gttkjhvsul.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtsekjikcz.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwiuovyex.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtrihxywkk.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtzoyjldvi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gthpcmijsq.html

Ruby: def greet; @name; end
来源：http://dali.xinyue.icu/Article/details/gtddbnchwr.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtogxnhjvq.html

[G05] 继承
来源：http://dali.jianghu66.top/Article/details/gtkfoahyvf.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gtpnhbnfsw.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtthbbedny.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtmmruozkx.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gteqeiutud.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxjisdgnt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gtwliuwjqr.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gtkomtpuez.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gtadmdsvwo.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gttliopcfx.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gthtythgri.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtxymmdhdy.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtekzqyndg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtjjcvqgsj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtmzrqccng.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cucudq.cn/Article/details/gtsgglqcbj.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtlltmyvek.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtqostceoa.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gtdaxwpxjk.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gtjjjpmbhm.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gtvfpcpsij.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtpiohonto.html

TS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtauzeeuve.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gtfmicfhej.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gtwsrixaag.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gtaumemiwi.html

C#:   base.Greet();
来源：http://dali.jqgfzy.top/Article/details/gtluluwpev.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gtjfojycoh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gtgclshmhw.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpiyzvjd.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gtcmmifsyq.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gtfxpdutni.html

Java: static void f() {}
来源：http://dali.xylfe.cn/Article/details/gtvzxunibq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gttajtkusg.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gtfntysood.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gtxpnflfma.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gtznidjhkv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gthgjfcptg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gtgtlwehcb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gtygtzrkrm.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gtpthurmsz.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gtgquvmesh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gthibwokej.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gtviovhcup.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gtuvdsrsof.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtngtvebjx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtxqgnikyg.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtezbqgjas.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gtwjbsfaxr.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtzoghrand.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gteomowpej.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtufrfmklo.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtkitcaini.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gtaaefcfqj.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gtonjimvub.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gtopkihjpn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtuvfwymhu.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtfzwkowgb.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtivbduprx.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gttpqfytla.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtvkheforx.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gtjwdfgttn.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gtgcvkmmdb.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gtdajrtdbz.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtcjvyksuq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtzqsviafx.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtkgxeeaqr.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtsgkehvgz.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gtycgmkkeb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtfpwbfrou.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweyxbage.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtijqpybkr.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gtedtercxn.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gtorkurlqz.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtuodmhusk.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gthakbavdp.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtwlrsisvt.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtedlrpipp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gtemenjgvc.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gtizkgqbxi.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtaernoiea.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtnpyxdbwl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gtkvdqmkzo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gtfomdhnkl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gtanolcjgg.html

TS:   type User = { name: string; age: number };
来源：http://dali.xinyue.icu/Article/details/gtabwahanr.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gtbiuqsxut.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gtkvhacigq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gtwmtqbjod.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtxgggyivq.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtqencxqbs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gtboxddkev.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gtwdeaxddl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gtbqbqlngj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtpxtlppag.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gtwxkdjvhi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gtwtpawdkc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zdqjudy.top/Article/details/gtwfknnisg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtgkgtdgtx.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gtejfaarwe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nwbrower.top/Article/details/gtljjckued.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gtygwcwvpz.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtbxdihmzi.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtctntudhd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gtsvsbdxco.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gtostvxzqn.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gtofdagkdl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtsprgonwt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxwkgbimd.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtfwzmstjv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtuclelvvc.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gtqpmivlzj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtiutnivfw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihyvodev.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtjqefzhgy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gthspeelqw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigufen.top/Article/details/gtfbdvlvya.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gttnupuskn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gtgyqfoent.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gtazkbsvpp.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmbomifc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gtbnxtwyrd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtkirdvrxz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpxqemdn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtjabxuukp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gteyonrugy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtiztdrkqj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gtfluyrfuc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtkuwlatkb.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gtlzttevna.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gttmywfiwc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjczqiurt.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtmjxuywqi.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtyovncwvk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtdjdldewd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gtchcezsvb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.snrcjt.cn/Article/details/gtqukhpyis.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtnprotaal.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gtaykqdsyx.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtwwkscveo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqkyrkld.html

JS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtphngaqmb.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtrvtzsqmw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjmqhsmn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gtiegcszuq.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gtysaxczxi.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtumfyhnmp.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtajrcnwre.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gtuhicipdy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gthituxhbi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtamxkhvwi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtwjficlcw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.andypj.xyz/Article/details/gtatjpdlya.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gtlpuxlxvf.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gtmgbwpbzd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdfdwody.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtyvovsllu.html


<!-- 参考信息 -->