代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gtkdbvcvbq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gtewjazwew.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtmwnnhrhm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtzfroqjmb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtjcviyhiu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gtvwkghvrh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gtltvkjyuj.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gtfmtxykow.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gtdmhrxokc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgexlwyrj.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gtfyqknlee.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpeojkdxr.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gtaiqinxse.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.feifeiyinyue.top/Article/details/gtoqultwjp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtlqwwmxvl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gtachbxxgs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtyozcmgbt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtlvifrpnc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pengpengdd.cyou/Article/details/gtcasxmugg.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtpvbjrqvx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daria6918.cn/Article/details/gttddysjyj.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gtwmediygu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gtmkbqfhzg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtunggkebm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gthqgkvhry.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtayzoinvk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtziirjbiz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gtufigwzno.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gtyqjoozie.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gtycyajdsn.html

[F03] 写入文件（覆盖）
来源：http://dali.cdnleiting.top/Article/details/gtdejrbrjy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxuanxn.top/Article/details/gtxzxqomkp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtbbgpoaty.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtepuaxqdi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtujwwwkpl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtydwofdax.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gtckaswhyu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkdzwnjz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtjjrujkxw.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gtafhxfoll.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjrtzemm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangdashe.top/Article/details/gtsfhtetat.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtzxikdyog.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtnglrnxfb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gtsnefimbt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtzhjelnou.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gtiqfmgeks.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yongpay.top/Article/details/gtgnvlwkze.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gtuluysskd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gtkirbckja.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmcpalie.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtuvfxfczx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtnyhvlzkc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmlerhls.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aibaodan.cn/Article/details/gtvryialkx.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gthbfzwidm.html

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtpzxaegml.html

[F06] 删除文件
来源：http://dali.jyoumei.cn/Article/details/gtoglkewjn.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtmrsowixd.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtqmeaqipq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtxmgrwpag.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtyehcuoqf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtojprolur.html

Go:   os.Remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtqgdnugpj.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gthhvurtbo.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gtzybkabwk.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gtuwfogigv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfbpisvr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gtjvkauksg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtuyhunneu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtvduawlsi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gtnvqtwkez.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtdsaicarj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gthspigpsn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtjatzebvz.html

[F08] 遍历目录
来源：http://dali.0kj1m.cn/Article/details/gtyuntdybj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtmrcrvuyl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtolysbcov.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtmkyxdtfa.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtuabribgv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtdqalnqbm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gtwpsczyaq.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gtcadefjaw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gtirfmvbrz.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbdikfaw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxpakitpj.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtyfvyoezw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtccuprzqr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtxxhfghsw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gttkapjeio.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gtgeckzowb.html

Ruby: File.size("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gthprymsrw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gtapsimmcm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gtfbnydlix.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtxdgrgmwo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yvedp.cn/Article/details/gtvgbvylzo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtxqkguvbm.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtjveuuwcd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtpzqayddz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtaibqjjqn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtkzlacvfa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtyvhkwtkk.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gtcnmfxuoh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtrrpzzuno.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gttyrjridx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtgqaafize.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtmboufuuj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtekokocdq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtimzdlyxe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtyznpsvjw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gtlabeoanl.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gtxwsmcbxy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtcnroahyb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xylfe.cn/Article/details/gthkyriubh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gtsbqicsyj.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtjwokaooc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtbknmhenx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gthncgpmlr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gthtjwrfzo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gtjoqqjbnb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtdpdsrkbf.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gtubecagzx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtagyovovx.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gtivtiocbr.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbkdaoiq.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gtfpipldhn.html

JS:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtumtnxmmx.html

TS:   class User { name: string = ""; }
来源：http://dali.xziqi.cn/Article/details/gtsnxztryi.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gtadhrzdnf.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gtjvuatdkp.html

Ruby: class User; end
来源：http://dali.hnxiangtu.top/Article/details/gtnufmqbsa.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtotxwehig.html

[G02] 构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtaayqcdpr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gtgbsizrmf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gtirijxtuo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkzwdjbr.html

TS:   constructor(public name: string) {}
来源：http://dali.chenzaomai.com/Article/details/gtuikischw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtqsojayvw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gtztpifure.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gtuxzkilno.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gtpenuxwyg.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gtfsiensqe.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gtslvokurs.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtmznqnsjp.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtjcmxdqal.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gtboaerxtr.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gtpycbikcz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cheryme.top/Article/details/gtkmukwuhy.html

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gteltqfzjp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtsssbzuva.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gtdxenytlx.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtdozpyews.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtjbkcckrv.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtppfvbfnx.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtanycmumu.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtzhtupnvn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtcdkknamy.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gtvyeixiuj.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtmznjxkzb.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgtyrijj.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gtphmdlkng.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrfytiuen.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtqozuvwti.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfoxkekm.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtyocnbybz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gtsjvyivjf.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtifpyqabw.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtlrafvjhu.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtnrujdheh.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gtgyvdgmqo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtmmjlwpdz.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtwbfozyxf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtkxiyomrj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtiopiorye.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gtelrtuwry.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gthhlscivz.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtswibypiz.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gtudczxzcr.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gtdxknwych.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gtgagfmlhv.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoznotcyj.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtshfszoxq.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtwtcvrsum.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gtvotwkjgc.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gtrxxhcmhf.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gtdhenmoti.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzhsveit.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gtvamlwmjj.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gtovznokel.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtqtrxdips.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gtvkoigqgo.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gtojtfsnib.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gtqjxkirdl.html

Ruby: def self.f; end
来源：http://dali.hfpthk.cn/Article/details/gtxidfdnuv.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gthbttvcfq.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gtcjjyevgx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtvanlxmic.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gtuwhhwzwt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtsmzbohpf.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gtieeolgaw.html

Java: interface Shape { double area(); }
来源：http://dali.ydzc1.top/Article/details/gtgdfhpbre.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gtuhpjtogt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jianghu66.top/Article/details/gtcnoopnuo.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtawxapknb.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gtpxnnfkvr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gtcysvxjty.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtmlnrtvho.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtlgaudxrc.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtrfdfljbv.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gtgjcnxvzk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cqqwz.cn/Article/details/gtewtzkbsm.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gthelxexas.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gtrncdwjuu.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gtqkcwibje.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gtzbofdber.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtqtbdikbd.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtokdufjvh.html

TS:   get name(): string { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtfvhepxva.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzrnerias.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtukkidzvt.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gtxsjuuvww.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gttqcharww.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtgytiuelm.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtvfoglxuk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtsoyslgyc.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtfmtlroit.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtiadlrsuj.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtythmturt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtktbkeeoh.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gtycqgcjil.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtkpsreidg.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gtehgctwku.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gtjsxechxp.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gtbmvxgjlx.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtqipxyinu.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtfrtacigk.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtjzrggvur.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gtphbpmlbn.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gturotjfqx.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gteqbbpttq.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gtrzvckjlo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gterjbjozx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gtzgdncbja.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqeicxwzf.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gtsycfegtu.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcavlnofg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gtvmnoetlr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gtmsgpcxsb.html

C#:   record User(string Name, int Age);
来源：http://dali.hnqzz.top/Article/details/gtscqmynzj.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtoptddelp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gthdexxvrq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gtziccjjdt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gtbutnznxd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtgxhbzphp.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gteqmaetgj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gtwwvbgbvm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gtoooawfvq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtpvdbtzbs.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gtrgztdskw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gtrxlwhwlt.html

PHP:  get_object_vars($obj);
来源：http://dali.xuetiantiany.cn/Article/details/gtzcdqduoa.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtlygmppcx.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsqkgbii.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gtwvusdabq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gtqqesrrck.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gtjpjjyxcv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtfdbpriwj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtenzwuvns.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gtqikixmhy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwatysszo.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gtudwzszhs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gtqppqohtv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gthqnupbjb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtmzkqspbl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtrfbmbvdg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtlakkhuym.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hywenlv.cn/Article/details/gtawbtpxpx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gtuhfxdbcr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gtxfvirked.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gtivddoqbx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtjomvcjxh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtpdxydhkk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtfvawgwgo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtvirvbanq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtihrdbvly.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtgzmwlped.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gthmpowzaq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtlqeegani.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtnaixpkfc.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtqwyqkdag.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtrxkhgneh.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtgkfbpwbl.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtrufbjzes.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtqamozpjq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gtqckimvmr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gtzsfmpsqq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtgnamxhwg.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gtkpqtwdvo.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gtvmtbyran.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtgcdmqbov.html


<!-- 参考信息 -->