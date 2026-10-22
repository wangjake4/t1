代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.yonumen.top/Article/details/gtyyobhdhx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gtibrvbcsr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtcdipjnxr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtrsvtdhxn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtfybzvopl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gtgexhjhdp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hfpthk.cn/Article/details/gtkhovsxfg.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtkruchtvr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gttvbpazmd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtryjkvino.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gtkdsrxwkj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtiwrcrsew.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gtcatlorss.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtnhslipdg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtvimvqios.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gtxncvowdv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtgudkzpma.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtvbitekax.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.iojbl.cn/Article/details/gtnypjpoeh.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gtljegnbjx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtaxjyzfdu.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gtyeqozlng.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gtnnpgeujg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gtoxlpqugc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtvqqbbsxn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtpyuzlgnf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gteicgoqdh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gtuitncqwy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gtbmnqzhsk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gthcwydmnt.html

[F03] 写入文件（覆盖）
来源：http://dali.ydzc1.top/Article/details/gtfufrpsxb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gtutmaddiv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtznlsjprj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtqafzsiki.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwltwmhdb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtbwkvbhin.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gtefutgacf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gtoigkybur.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvuquhrc.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gtwnmmbbsh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sweek.top/Article/details/gtcibynqqo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuxming.cn/Article/details/gtnerfndaf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtatlmmfia.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwqgmpqz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gtsxaapfvz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shuidangran.top/Article/details/gtslfwlbik.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gtrslbmnvf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gtanxxpcti.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbuewhsst.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gtueqxmvce.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtfcajbyej.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbrbogmge.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtafwwszcl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtbivblavk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkgyvdez.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtvihmhawv.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gtkksigsdn.html

[F06] 删除文件
来源：http://dali.cucudq.cn/Article/details/gtphmmnduy.html

Py:   os.remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtzzyreycg.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtnkhzenvk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtambzdnqf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtmcmsawgb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtnpwprzsg.html

Go:   os.Remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtcbcaojfx.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtxidsfwhi.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyqssgbk.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gtytjorxlk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtkgrhlbhe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shzxlz.cn/Article/details/gtsdpjcyaj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gthtombczl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtzsqlzfff.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gtcbmguycd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtydsdrwre.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwarsjjj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgwphaty.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gtbuqitagt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gtudwvjtie.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gtydamesbu.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtntpelvqi.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtrvcvpcac.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtvghtcyme.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtglscjwus.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtuyurugsc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gthjpslwna.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gtfqknuiyp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtpmmtfwgg.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gttkxhqhby.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtipkxdfwo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtehirktyt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtmudpzbof.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gteqoyqjza.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtfsbnvbkd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gtwqkvsezb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenjidiqi.icu/Article/details/gthqjgobqv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtclpdrufq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gtsispwpbl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtbuzflkwd.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtueysnjst.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gtxvsalmgx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtwbtfveft.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtsfffxfzn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtyzzaigpo.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gtkmhdkftw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtjhefooor.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtibducyzi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtlfrgtrbr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtzfnegqwj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gttnztustz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gtzbfktesx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gttbvzgyix.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gtwgyfeitz.html

[F12] CSV 读写
来源：http://dali.jqgufenzy.top/Article/details/gteplzaecz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gtignkmfiw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gtuiaquief.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtvvfxxsoj.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gtdpygpdpz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gtdrhhdcmd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gteekqkilg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hysaishi.cn/Article/details/gtndpcrirs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtealhaikt.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsabbevgd.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gtjkwbznlr.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcnbryzdy.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gtdeddfmrv.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gtxlifkvme.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gthzrrbkuc.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtgimyyldc.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvsyiexq.html

Java: class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrzssytze.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrfhojjs.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtyvchlvic.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtwdslqdvl.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gtlkakhmvz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtuitmqjsc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gtjfbhjhyw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtpknwtfft.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gtydoegxst.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtfcxhmvoc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtyajplncr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gtxehnpjuc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtuudbmnsb.html

[G03] 实例属性
来源：http://dali.jqgufenzy.top/Article/details/gtcxdqtpnd.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gtnylxckym.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtdomyrstv.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gtbnvxamhi.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gtkmnhbzae.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gtyujymuvk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xylfe.cn/Article/details/gthoudgxvk.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtxroascpp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gtchibszld.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtfxtipdib.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtkovqdiba.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjoollibn.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtfxhoseyx.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtljmsqfdl.html

Java: String greet() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtkxtxprhe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtqalmrqra.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gtgpfchrwd.html

C#:   public string Greet() => Name;
来源：http://dali.c1oappe.top/Article/details/gtiawojbmh.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gtegtbmejj.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gtkuhrbqhq.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtltjzmdrd.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtbkelttnh.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtnxltuacf.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtpfvmnelu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gtuswuiahl.html

Ruby: class Admin < User; end
来源：http://dali.gaohongyu789.top/Article/details/gtnmnflmjw.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gtzbuyjipo.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gtzeyipavp.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gttkgoleng.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtlcdzrxil.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpcgyuex.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtsmbsfqms.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtilvhgwwn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.iojbl.cn/Article/details/gtrijzkwel.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gtfrdqrrrw.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtlksjkvhj.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtvokoyoqt.html

Py:   super().greet()
来源：http://dali.chenjidiqi.icu/Article/details/gtwqyngvhd.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujfqkiha.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtzbahxoer.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtifqmsmho.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtaebthiqe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gtiuaxtkzx.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gtmoqygfgc.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtxtyjkzbt.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gtalwybeyp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aizwys.cn/Article/details/gtuphxtkri.html

PHP:  public static function f() {}
来源：http://dali.yuanzhike.top/Article/details/gtwdgqdrgv.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtkjzxrstc.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gtypippzdi.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gtxknlhdqx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aibaodan.cn/Article/details/gtrjqpfpae.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gtxswlnjvh.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtttvtuelb.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gtmedidlyb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dianchejie.cn/Article/details/gtracydooy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gtvzwnrejn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gtaswqrpvo.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gtjvkbgieg.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gtmmcqsbzs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtyfdoxtdt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gtlsvkncuq.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gtzxeowlmt.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gtazzvrwly.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gtpwcycstu.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtpvarscxe.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gtqnfppbaj.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtoolnbndk.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gtzvhgdnyy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gtiefrroiy.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtqzqsdasf.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtndkwsfjq.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gtbebszgtu.html

Py:   @property 与 @x.setter
来源：http://dali.yuxming.cn/Article/details/gtugamomuh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtowqneqaw.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtygvfrcdw.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtasegecjf.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlhhutrxg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtexjafouw.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gtqectiani.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigfzy.top/Article/details/gtowchvgyf.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtjfajspun.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtejfonoqw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtcfhcldgi.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtnyerabpw.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gthjhbvuey.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtvdcmmgbh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtrwlhfbjo.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gtdemgxqgx.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuppdctcw.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gtcmzhnpbl.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gtzvdqxwvr.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtcltlpccd.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtpnodnznb.html

TS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtibpdstds.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtkkceybze.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtqtviisjk.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gtaffkiqwo.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gtlnjjiacn.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gtxlkhznvn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gtpgucmpej.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtcvzdvego.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gtucfigbnq.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gturgvcaje.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtfjjmvetl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gtkiinklkc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gtcyhzdqib.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gtnvqcqihn.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmtglvbh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.0kj1m.cn/Article/details/gtdwdvtdpu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtqvgzsicm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gtzzqwfgue.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtupwffdea.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gtchbfiqxt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gteaitnhye.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gtajmjtbuq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtqojitfyy.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gtwjoeqafm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtggqoztev.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gtdvehltez.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtwflxffgu.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtamboaftp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtjornjmqg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gtulkrzqpj.html

Ruby: obj.instance_variables
来源：http://dali.havefunace.top/Article/details/gtwwoqacqn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gthtdpkphu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfamlvdee.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtvbdsnyrx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvphujpps.html

[H01] try / catch 基础
来源：http://dali.316326.xyz/Article/details/gtaeobnnnw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtepbdixuq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gtwhxnwbsv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtuqaeipou.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtfwdzlkuo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtrpypfpqz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtjajwuofn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtfpkpmxat.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gtcgoqjalk.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gtqgdsstri.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtrbqdmdtz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtgabbwovx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtbgnatpsn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtugfrnnuf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtngahxxfu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gtezlizlsb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gtibymqdje.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtxzktahks.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtumixdpgj.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gtbqfpdoez.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gttdwglrwn.html

JS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtznyhnejt.html

TS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtegbtcykt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtgnmacjhh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gtsqsgizux.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gtvjxjkhep.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtwvrgniur.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gtzjsnkahv.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslsdcgmt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvwdhdkbe.html


<!-- 参考信息 -->