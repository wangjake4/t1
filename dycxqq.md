代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtygapnlxx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gtemkorijx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzzwdxku.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gtrgpmhwtt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gtnjalmuhs.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtyqqsjbwv.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gtyfurijlk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwlsfmtya.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtavmiwmgd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.haohaochexian.top/Article/details/gtvmhnulby.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwclqcyg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenjidiqi.icu/Article/details/gtfhjgeqsd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtgojyeyql.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtbmkegpgy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrvnsfcw.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjeezhqnc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtzgwwnckj.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtigymstcp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gtwxfoocsl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtnzlzdhrl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtsoaagcom.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtpclfbxqx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtavigaaza.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gtzskqvbor.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jlsjyb.cn/Article/details/gtlrioqxsl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtteqoulrl.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gthbvzytrn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.andypj.xyz/Article/details/gtsztggidt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtgkplsqsd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtzjbgvcoo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtifwobkuj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuanzhike.top/Article/details/gtwwpainjv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gtejaotjbn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.svipenyu.cn/Article/details/gtxfdfcwxu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtfkhrzpen.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gtvqphugum.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gtelgpubwa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkyeugwm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtlubexisl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtpkwsmeyf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gtmcwgphtl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gtmhywxaxn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtoyvdqsra.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gtugsmxqbx.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtlvcguvrb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gtnohtbxyw.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtjftxpobp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gthpfyxodd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtzzkeovjd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtasixlxqx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gtmuglyrkr.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtzehyvrle.html

C#:   File.Exists("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtiyqaiasa.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gtujxkqqee.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtuaqcfbom.html

PHP:  unlink("a.txt");
来源：http://dali.meibo888.top/Article/details/gtwaikabaj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtreewzsbq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtkrnrpmlb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtxupjqrhv.html

Go:   os.Remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtkucwowfb.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtnbabbtlt.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtocuvlssk.html

[F07] 创建目录（含多级）
来源：http://dali.zhiwuduotai.top/Article/details/gtdtnfkfyt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gtqilhgvgn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gtecqnhubk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtkrsfpscn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtskybeldi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gtjkzzwdvb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gtzxqljgwj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yonumen.top/Article/details/gtocoblzbx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gtcimowxoi.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gtqwzjdqnm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gtzpwmoopg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenlongwang.top/Article/details/gtoyzoayyg.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtoyhhflwg.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtgfpgvusa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtycoroxpv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gtsbnipcgu.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtnsistmvv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gttvkxabiu.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gtunteggao.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gthuabgkvk.html

PHP:  filesize("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtqqhfcshk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtekdohbwh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtummcauke.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtfduupjtf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhoulong.xyz/Article/details/gtsqhnldji.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrqtlnsk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dianchejie.cn/Article/details/gtodnejxmu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gtdpldzvga.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gteihazuri.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gthxeevtij.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtzxxbzzzu.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtkmirchhn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gttqzrkqop.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtzjutpgzk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtqblkzguz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtgsbikwem.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtwhclbrok.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gthctkrhbk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtsgcikllb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtjqiowhnf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtvprvbzoo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtygwoqfoy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwmmprxq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gttzzclxqg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtaqddurfk.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gtimohpenf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gtsvrcsbaw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctljauuc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtsqlrcnga.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gtvkcyzrfa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtgnliayxa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.vqdsnc.cn/Article/details/gtvbldinxf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtiwsfxaum.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gthkrlthqc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqhncmgeg.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gtuiyzfxzz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtizqvqfww.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gtaecpavkc.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtlevcciwx.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gtemxctqdj.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtbowifkzj.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gtluxuoikc.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gtajlyhyjv.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlefujdq.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtjpakqlec.html

C#:   class User {}
来源：http://dali.cheryme.top/Article/details/gtkjwiikwt.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gtrqpmtvvp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gtiynhjpvu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgotyhnqo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtdeegbvoj.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gtaagdacwo.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtryajmtcn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gtklfevkyr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.mhx1999.top/Article/details/gttsdkzokb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gthrsiczfe.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtbfphogdh.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtblyhkqrk.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtjsntsifx.html

JS:   this.name = "x";
来源：http://dali.yongpay.top/Article/details/gtefmdhntb.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtqmkctaba.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtsircuawx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtlpfnqmgq.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gtclnyveis.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gtomesaldx.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gtkneaxsmb.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtrkkqwkla.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtbtaxyqfq.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtvkbnrpiq.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gttiummshc.html

Java: String greet() { return name; }
来源：http://dali.havefunace.top/Article/details/gtciqmthne.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdalctank.html

Ruby: def greet; @name; end
来源：http://dali.sufxvd.cn/Article/details/gthibxdjtd.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtqxtwlyjt.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gtigqgogcp.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gtioklmefw.html

PHP:  class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtqeouuzwl.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtpurokuma.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gthvphmckg.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gthzhdsdph.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkqttagl.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtzmwqdklw.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gtzswrvwtl.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtgrjlkhzj.html

Py:   def greet(self): return "admin"
来源：http://dali.daxiang520.top/Article/details/gtirjevezh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gttuqeevgv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjnrpdplr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtbgrpxurw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtniffkljj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gtspxmprif.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtfihqylmr.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gtraxvftsm.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gtajidzyzm.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrrrjahi.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gtxewboefn.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtcvoyvqow.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtcnvixtxd.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwiaynck.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzobwatlx.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtchyyigtg.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gtupvehjhd.html

[G08] 静态方法与属性
来源：http://dali.zhongyouzk.top/Article/details/gtgepmidfv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtcalewmqa.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gtywbghnoq.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gtkrsayqar.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gtydkzvreq.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtltpwuepf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gtnmfdqnpx.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtfxujqodb.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtcturvguw.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gtftycyvop.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtzqvqiqdb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gthycntgaf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gtzqzelkiz.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuurkhord.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gtnjiioexd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gtqxlzxkjf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gtudwjqswa.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtwpgzxlbr.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gtwyvxbgdx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gthjrlvwit.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtbghafete.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gtkizzzeju.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gtzmonrunb.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gtatmzubgw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gtmlalzhmx.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtzpuptshd.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbncvvhv.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gtezpmqmtd.html

Py:   @property 与 @x.setter
来源：http://dali.ehwqpu.com/Article/details/gtualbfkty.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtllkhdwty.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtlzdzzvdf.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtthfyhrkr.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwfielho.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtriwkgidl.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gtnkvfbxhy.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gtbcwtixzd.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gtasgdvkml.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtrquocmwq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtqkkiwqll.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtjmdrwfcv.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtqpwcojjp.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtxxugprle.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtgcoavvfy.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtnuiufjgm.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtzszwzzpc.html

[G13] 判断对象类型
来源：http://dali.yj20258888.top/Article/details/gtneewggto.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtrxceiwrr.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtbucfsega.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtsprfbnfm.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtdzcxsovo.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtmkzcnwbr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gtkpuoaury.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gtjdocsgxe.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gtnyjvlldn.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gtnshwxpwr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gtzihxybli.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gtoimftdnm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtccjvqytm.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gthwikbcbo.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gtefsgxkvp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gtzokacvjo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.mhx1999.top/Article/details/gtxhcilivf.html

C#:   record User(string Name, int Age);
来源：http://dali.aizwys.cn/Article/details/gtjecxqrzn.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtojipgfsh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtbawkvqtb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gtpprmwcht.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gtqeciuezb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtrwjdwvhz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gteapfrqqc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gtinqwydah.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtgwmnnddu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtygstvrgs.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gtnyzuarjh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gttbsdhgka.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gtzznffjwo.html

JS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtppveubke.html

TS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gttiwinbmv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gtousvnbfe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gtoluvndco.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtmggcrlru.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtmtgtaqol.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxcgdrony.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gtkqkjiowd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtsjhfysxd.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtsdvlhmzb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuanzx.com/Article/details/gttrhdchzt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gtkwmknswv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtlmglmaww.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtlfxgvanf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hysaishi.cn/Article/details/gtgahfnlwx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gtkmelrrky.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtrbuhioqp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gtrosrtccn.html

[H02] finally / ensure 收尾
来源：http://dali.hnxiangtu.top/Article/details/gtefvudflp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gtnfldaupj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtnkfmwdje.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtxjzvtuqr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtoigcqrkp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gthkmkbqwj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.mhx1999.top/Article/details/gtrxskxcgo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gtenrukayf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtbqqpbssi.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gtmsffxkmr.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtdtirjqjt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtculmgoek.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtcbueoghz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtmczqgkkt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtkrlwrbse.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gtfjoqmokp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gtnacgcqub.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gthliehmhs.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gtuicokwze.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gtglkktojx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gtruczvejf.html

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtpcmzpxlk.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gttbxqgkms.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtxafjlcks.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gthuewyfwb.html


<!-- 参考信息 -->