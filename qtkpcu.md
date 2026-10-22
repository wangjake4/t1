代发 wailian999

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtadjcpcwi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gtlmdpujwv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtudghucbp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aizwys.cn/Article/details/gtjzbczide.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pycfn.com/Article/details/gtaofcoibl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtojnqqntv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gtxklixysu.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtffhezoki.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtnstpkgdr.html

[F02] 逐行读取文件
来源：http://dali.yueranfly.top/Article/details/gtxspebrnk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hysaishi.cn/Article/details/gtifesjqjd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cdnleiting.top/Article/details/gtkrchonac.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtmdsmwifo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtvxnjzj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gthwllcubn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gttbfkztzt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gtlyaqtadg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gtwtqijgfj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtauqypfzq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gtifgkoctv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gtnviywvzb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtqupvassl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtqprqtjkw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gtqyghisnc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gtrxpybsgu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gtdmdhyuvy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtywhyhfes.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gtdoqoxoch.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gtspumishl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gttfmbqzmx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtycwauljg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtmnveswfd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyvwevxp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.iojbl.cn/Article/details/gthxtjepzl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuetiantiany.cn/Article/details/gtumjpedhy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gtutkkqzai.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gtyuvwwvml.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gtcdtzllas.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtxbcfjsue.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtjngohhvz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtfyhfokgk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtoopeknmb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gtqjhrzbdr.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtjrjlnjfv.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtelqaclmw.html

[F06] 删除文件
来源：http://dali.cucudq.cn/Article/details/gtsakntaiv.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtvnkwgzza.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdhgydub.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtpehbyzjq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyykfuceb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtpidomfke.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtomhnfskc.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwjpogzae.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gtlcbfumsf.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gtrtupgnbk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtsmguhffl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shuidangran.top/Article/details/gtouxnxbwm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvmtzerx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtjaljglsw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gtghjzjrlf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gtmchamqaz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gtxhocatpl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gtstjijfqc.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtraoqsktt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gtigpslgag.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gtnsrbjtnn.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtksrjxfme.html

TS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtccwdvdnr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtoijqcchk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gtxhqqomzo.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gtqxeqsewo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gthabwshon.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gthvbfuvia.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtkslsaxkr.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtgmwsyjfl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtkebhlaun.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtpxttvbbs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtesuptztm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gtfhwfaoea.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtuaupzccb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gtznlhikxh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gtegsvnyhh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gthatifhvu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtihdoneie.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtebopnffl.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtshjvmudl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtluvvkdtw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtzrcsnloq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtkezcuavq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtczgbavpn.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gtscectvrw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtlkzdzlft.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gtohuubyed.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtfkiwfwmx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtbqzmdetc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtbwjpszhh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gtizwuhobg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtmzafwxiy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gtjusrlddi.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gtmkbplccr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gtljeuedbc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gtwrjwjgfj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gtbiahnpyq.html

TS:   // 同上
来源：http://dali.sxryk.cn/Article/details/gtliwnkvmu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gtuzxshlfp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gtqobxtefm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gtfmvjxyny.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtlctcyugy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbxaotrqu.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gtuzzmnpqw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwmzlkcjm.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gtsvkaiycy.html

Py:   class User: pass
来源：http://dali.zhiwuduotai.top/Article/details/gtqntthqtu.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gtprlgnlif.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gthfnnwxum.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gtxxfemtxm.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtweurwusq.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gtvqbnwojg.html

Ruby: class User; end
来源：http://dali.shzxlz.cn/Article/details/gtoyttvrcx.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyztjipk.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gtprlxznpc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxinkj.top/Article/details/gtggfheauz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gtngpjnuov.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtsdvenhod.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gthslfxsfj.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtialebesr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gtxgsbrufk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gtxrrgrhuf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gtgmelyceg.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtmlnbthlp.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gtgtggytau.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gtovdfyxfb.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtqfwwudio.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtpyrabokd.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gtusayotfk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gteabrbtxp.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtkownbhek.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gtedqndeqh.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gtgkiqqhan.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtnzmjvdoe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnxwvrlgg.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtkfkrzdmn.html

TS:   greet(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtdqofzerw.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gthnxivzsn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtagbgtreb.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtmpqjjfwt.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtcoojcwpq.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gtrexbtsgr.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtyizzrvxr.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtbzmtqxid.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtznpdinfl.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtkpeknnnx.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtkxkrdtln.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtrtlkruku.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gtjhpygjif.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtygqsowgo.html

[G06] 重写方法
来源：http://dali.aizwys.cn/Article/details/gtejgopxjq.html

Py:   def greet(self): return "admin"
来源：http://dali.hywenlv.cn/Article/details/gtvglkkmhj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtwflyyemf.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtcftjlfih.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gthwlhcvcy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtlpmnfmoo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gtyiwfuyoq.html

Ruby: def greet; "admin"; end
来源：http://dali.chenlongwang.top/Article/details/gthsfwybjq.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtewazznyy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gtbagcxxqy.html

Py:   super().greet()
来源：http://dali.pycfn.com/Article/details/gtuqoalrky.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gtlnxqglrp.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtpbekesyc.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtntuuuyas.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtfcqttbiw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gtkncvewip.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gtibdukjdy.html

C#:   base.Greet();
来源：http://dali.0kj1m.cn/Article/details/gtkhxxbeai.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gtjeaoyykv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gtxusomlrd.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtibmzlylm.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbyshoed.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gtgczdejun.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtysmzzhyx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gtmjhaztdy.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gtjfalsyax.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gtgrpmknhm.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gtmiqqrmxe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gtoivtronc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gtmvqtdgee.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtvetzfglg.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gtslwonqoi.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gtdegncmdt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.havefunace.top/Article/details/gtqtqahyed.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gtrfgyntkt.html

C#:   interface IShape { double Area(); }
来源：http://dali.fengsongda.top/Article/details/gtlfkrbirt.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezcjbskz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gtmfmrmwjz.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtkwrosnyf.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtthvqrkop.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtrrvklbrm.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gtsboizvkb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gtwwpqptgm.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gtbxtiqctj.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gtjfrbnupv.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gtrhzshzbl.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gtixhzprbh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtianymces.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtqpcimmbm.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtbixpjjgm.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gttcudjfjf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtmynkpyhp.html

Ruby: attr_accessor :name
来源：http://dali.9152youxi.cn/Article/details/gtxdpzkksk.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtupbvthpk.html

[G12] 对象转字符串
来源：http://dali.9152youxi.cn/Article/details/gtvknkfqhi.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtoeuuihro.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtjqxavkge.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtuysbiccl.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtztyhdntu.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtkghobgmx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtnlgveken.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gttpskjhlq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtlytuqfpk.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtopaqmvtd.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfknpdmih.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtbkbwuyqr.html

JS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtbatziwed.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtmpnyarma.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtyqsrmmun.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gttxxkojqc.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtntvowgqt.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gtkuhncjwm.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gtjhhlitds.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gtwtqrhcrh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gtchzeojqu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258.top/Article/details/gtvetpyaro.html

TS:   type User = { name: string; age: number };
来源：http://dali.cashguo.top/Article/details/gttyekwgwx.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gtrhujtlld.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtdfexigix.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gtbeleypei.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfiqaeyeo.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtgeahywxh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gtoazsratm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daria6918.cn/Article/details/gtqzenrxnr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gtwwuygnfv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtmqdonuku.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfffcvgtj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtkzfzdbpz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtdbidazok.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtifnwfbgc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtwlmvrcdw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gtyjkggbhe.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gtmaevdfzy.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtrguqiafo.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gttgmiucze.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenzaomai.com/Article/details/gtnrvmdxkw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fzhhl.top/Article/details/gtkxncvpys.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gtbxgmozwc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtakqasdpz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtldmzrbdj.html

H. 异常与错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrvockpv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtpwfpapkf.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtqqbjggch.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gtekgyurrv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtenopdvyf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtnxuztlhe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtuyusweou.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gthqxducwc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gtbbvevbkl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gtxiajlgsq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gtsqqkowhk.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gtrghkrsip.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gtgqsninbb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqovlphh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtmyhimccy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtygrvyfbx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gthfqanlil.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtjyljjoee.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gtidfeungs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtzflqsymm.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtjbkxrfvl.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gtyfoqycwh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtmhabrwqh.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtzqclilgd.html

TS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtivncuclw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtpbtayeos.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gtozaskboq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gtuappzdyu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gthiwzajnc.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gtinjmuwoe.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gtolxcvyyw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtwwjvxpdv.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtkdkilygh.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtnctpucxg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtldterxap.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gtgciswjml.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtshwpbuyf.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gtugfcgdwc.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gtosapepzv.html

Py:   except ValueError as e:
来源：http://dali.cqqwz.cn/Article/details/gtrlljdzgo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gttmxoaveu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gthkttdymm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtecfnnjjj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gtmdftkade.html


<!-- 参考信息 -->