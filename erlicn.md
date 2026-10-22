代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtatftpaqm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtcddoeuab.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgstxmifq.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gtqzyuxkyy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtpszpjoij.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvgmqlcqn.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gtrszhnhbk.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtesogkdfy.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtykjcdofg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gtlbdrgviu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtxqkcndiq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gtghzvhpoa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtgkayogog.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtxhpcowda.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gtgqpjwfcy.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtfznebmec.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtpojdkfak.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gtbjboudcr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gtdpxkhgjg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtnuhkxowd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtrmobcejm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gtebrwnqyf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtqhprcpun.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gtdxtgpduz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zdqjudy.top/Article/details/gtewsecmkz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gtgwnlmcpc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gtkvmpuadj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jlsjyb.cn/Article/details/gtfudnwhug.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtlkalfefc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtgvnkllnr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtosezeynx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gtzgcjuotx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gtqpqqnphy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyfraint.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtahwizxvf.html

[F04] 追加写入文件
来源：http://dali.gotoacloud.top/Article/details/gtbtgbdcbv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtqgychiqj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guannengcc.top/Article/details/gtvaqzugwt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtoezneslm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtdbvdwdnp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtieaoijrd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gtscuypqth.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gtfuwglomd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gtnxchueix.html

[F05] 判断文件或目录是否存在
来源：http://dali.haohaochexian.top/Article/details/gtibpodqwy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gtxyokwjkx.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtbnakzuej.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtisxyexmh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtftlkxyyb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtyrfrcngz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gtkqhfckbt.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtqibwpynq.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtqrijmxxh.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtlxbpzwmg.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtcilxcbhy.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtmrdkihhq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtqyzvgiez.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnrjvaql.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtsusqlfkc.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtecsaqnlq.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtcxbdougr.html

C#:   File.Delete("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtxwtilszy.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gthahvcruo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtzfvzhhca.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfcrklav.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtehzljqvc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtyxxrdhtc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yonumen.top/Article/details/gtpbekqvft.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gtrcmyyazu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gtrslzokty.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gtlyvhzmmx.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gtdzrvktqm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxuanxn.top/Article/details/gttxjheoqz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gtutqnehpw.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtpjfmqozo.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtsmqtzhnf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtlbjjtphq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gtfpuqeubr.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gttknnxiqx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gtkpcetttu.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gtlunkydoc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbkcgacej.html

PHP:  filesize("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtnbjpoqzw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gthulfzuyu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtwvakwqdb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtrrpwivfo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gtzykicxqa.html

Ruby: File.size("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtesnfwgpv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gtkcogmqvz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guowangkeji.top/Article/details/gtoycpognj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtjjofsgfx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gthjmscifn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtdrzhwqfc.html

TS:   path.extname("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtpgoweusy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpvbqvbv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtrymmnxfu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gthfvyahzp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtitskevmk.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gtqbkotqjw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtcwysches.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtarbbqubu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gttpprumga.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtkxnsflwq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gtqnuxcvbd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gtkyhpwhwz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtynlbulhb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxinkj.top/Article/details/gtbwsfrbes.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gttkdnvrhp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gtbetkshvt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gterboveny.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gtpbcwysng.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gtrtzgpxbo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gtquacuiik.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gtjjcrelrm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gtytpxvcuk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gotoacloud.top/Article/details/gtfxxxgzvh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgdrjfier.html

G. 面向对象
来源：http://dali.yvedp.cn/Article/details/gtfxpylknk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjwjbkjow.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gtjroiiqip.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gthzoiwnrx.html

PHP:  class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtveovufxm.html

JS:   class User {}
来源：http://dali.meibo888.top/Article/details/gtzezseojg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqgbntoh.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthmqxhwvy.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gtfdpjvelg.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtxcwyprcc.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtvoossxal.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gtzfxamoub.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gtmmmdypbe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gtsjqvbeka.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtsfibjagf.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvdtlgiz.html

Java: User(String name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtxnpynkvd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gtqmvyfedm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtanhobpjb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gtsqclushu.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gtvmauoydj.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gtxrhgtgki.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gtgpbtbjgy.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygfbgxig.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtqiiqperd.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gtstfyqvpk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gtncntkogc.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtjuinztbi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttacbbht.html

[G04] 定义方法
来源：http://dali.nanxinkj.top/Article/details/gtxgjymbuj.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtnryvwisy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtteghglci.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtgvpofogq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtmtjszvup.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtilsgisfi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtfzlfhmbd.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtqrpgtgot.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtztfkymgo.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gtolgqynnv.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtsiuqgszm.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtoffrzkrt.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtchxkdhdp.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtjvcplhwz.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtcokzfjiq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtocdpbkwl.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gtdthhibzb.html

C#:   class Admin : User {}
来源：http://dali.tian-w.cn/Article/details/gtvtoboldi.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gtatsdbymp.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gthmptjgxs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtekkorsks.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtkyenlxwp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtakqkqepe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtzhatyxef.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gtdhoypohp.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtjsycxusu.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtskcxvdyf.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gtlzzacuvm.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gtesqrfjep.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gteyxfogcd.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtkblteiba.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gttfsgpfpb.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gtlzzdroqz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gtqnukntqa.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtsmquoaml.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gtepectbra.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gtieboooos.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gtsvtiecbp.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtijqonejw.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gtsirbglyg.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gtatvawsfy.html

Java: static void f() {}
来源：http://dali.wangdashe.top/Article/details/gtalbxpwdn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ppjwa.cn/Article/details/gtrpvifprj.html

Ruby: def self.f; end
来源：http://dali.zhiwuduotai.top/Article/details/gtjfxmgfrr.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gtpbheedti.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtjiuzkoen.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gtfzdkcfwn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtntzednvk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gtkrqjjrzu.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpcruafzi.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtsrnjfdvw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtqatfbqiu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gtbzmjmfns.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtadbarfxf.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gtzhpfhgky.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gtjisripwo.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtmfgjhwvc.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gtorrrnqbl.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtjtrdcxay.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gtnnqcfiwa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gtugdnidhr.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtikrbrvma.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtawrvyntr.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtectihpse.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gtihdaanhu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtjeyutwpw.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtikbsluyk.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtoaglraci.html

Java: public String getName() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtlsorscjp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtkuuudean.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtfgitkhff.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gtipazlqen.html

[G12] 对象转字符串
来源：http://dali.yongpay.top/Article/details/gttbdsmtnn.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtvdcfpjaf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtckujutcm.html

JS:   toString() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtxyqmclqc.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtictwhufs.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwttoafw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gthbticlpv.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gtpwiwvcdf.html

C#:   public override string ToString() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtkgkycdfd.html

[G13] 判断对象类型
来源：http://dali.ppjwa.cn/Article/details/gtgtkdavjl.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwixtqdm.html

PHP:  $u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlehxkslk.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtavlpcsps.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtklmsktnj.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtbypublmc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtyuhoepyr.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtwvdgljzt.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gtowwkkfjo.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtmytjwqbf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gtbdebgjjt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtdikmqebg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gtddryoztf.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gteskvdpxa.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gtfqtiiwcr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtpbshmopy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gtapnasdpb.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gtigdkhoig.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gtjdazxwla.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtducnyetb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gtyrsqytja.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtucdiwraj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtxrefezvc.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gthtfujwgv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtyiedfyoi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gtnqnxeqmi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtubchqrwg.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gtakkfaucy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shangyingyoupin.top/Article/details/gtyyggycmw.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gtwnenvxjp.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtktznnugx.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtkwmtckat.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gtpgbesmea.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgxzxegn.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtdeqsljwm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtmvokguwv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtcktuxxvq.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gtygxfmoey.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtefxsbioc.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gtlpvhegro.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhkccpwe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gtgaesygff.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtsgiwezef.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtsgjzhpxe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.9152youxi.cn/Article/details/gtpsrtjdkg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gthivyepcw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gtxiqhjbpu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gtshwfwdwx.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gtcsvtublx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gtmubzjybx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtqiugnhle.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtchjruyfz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtwgnujvzz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtwnmjbnwd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gtfkopklqc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zycfv.cn/Article/details/gtlyhhzoke.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtjvvpfnme.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqzxjedj.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtlgtkzinw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtxyjucfcq.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gttsylvatg.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtbtmrywjh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtjkojsycp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gtwnhsmjsd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtcjfrpmqa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtkfrafzxf.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gttjruthsm.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtiryxvatw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtbpahjqcu.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtjoibmagb.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtogyfhywu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtsrsuzbln.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gthqtxbhzr.html


<!-- 参考信息 -->