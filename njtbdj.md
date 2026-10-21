代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtxesreeww.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtqfkcyffc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gtmlxyihtq.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtyvkizweh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gtxfaxzeia.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtsmxtoedv.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtwipfsayu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthbysokpg.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gtfkfqakam.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.316326.xyz/Article/details/gtiorbrbxs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtqhonjgwh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gtfmrjnonk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtpekkstby.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtyvnmvnoy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.mhx1999.top/Article/details/gtckjuecgy.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtoxqqwvtn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gtcjzljxoa.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtlqwksnde.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gtjsdyvhve.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gttzuquqmv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenivqsbf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtwltwbejs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtkagnxfde.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gturabufvo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gtwddelbaa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gtslirgits.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gtmsyglidv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gtmzaxoapi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gttnadcjsy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtgovtbqex.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtprxnxwmz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtkrrhdnpt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gtscbvysgu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gtfhvoeksn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtpekeates.html

[F04] 追加写入文件
来源：http://dali.jqgfzy.top/Article/details/gtpvpxlpuu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtmmasepyt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtwozkbibw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gtigojybgk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtqxcsydml.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gtasilxcdb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gtlbxfqago.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gtlzcxrogc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gtwkzoblri.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gtxzzfupkf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtanruoirn.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gteeymebis.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtmfayxkvw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtkulocsvy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtvlcakppe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gtfwuyfjuy.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtzbhvgztj.html

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtjkleehec.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gtvzizhgwa.html

Py:   os.remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtcbfemjie.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtsskeyjxu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtzrhyrwqh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtitcdxysb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtivfvzopf.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gttgupbldy.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtnnekpjax.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtkudymnxb.html

[F07] 创建目录（含多级）
来源：http://dali.jlsjyb.cn/Article/details/gtzpxstcgs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtruhgorrb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gtuqqtplag.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtcpqvdvqu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gthccqirhp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cashguo.top/Article/details/gtgcgjrwci.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangdashe.top/Article/details/gtcltvmdri.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gtaoawdroe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daria6918.cn/Article/details/gtjdcjigwk.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gtqrbbxhvp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtuhgrjrog.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gtxienmfdn.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gteswncgox.html

TS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtcdlqinps.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtdedrumga.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtbhlwdago.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtgidghjvy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jiagoushi.top/Article/details/gtjgsdmxhf.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gtudzfwjzc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtjlicjbay.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtfdjnuhxf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtodopfevj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtycudkkqw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxmxyxip.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gtafxrllyu.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtwhdrdbju.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gtponxyxec.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtgpryjoti.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtgzgtqoxe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gtbemvsskc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmcotveo.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtydalrman.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gtqncwmiej.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gttrfegpli.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtzklxhnch.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtlxgwjhrj.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gtrmpsaayt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gttlkheqip.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gthkprmenm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtmnezslvk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtdjocqkfj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtbsolqmtz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gtvdtpoolv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtwryrcjfi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zycfv.cn/Article/details/gtgfjpmabt.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gtgqfnrbmy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gthwmgprwm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gthvmrrbhh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtdivnljxf.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gttqfibsdf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gtxrdpsspm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gtwjccovrp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjfbxapn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gtkbsrkyqe.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtohztuohs.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gtqykosese.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvwjxwbh.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gtwloiebmr.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gtdmjgsycf.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gtbklopmjp.html

JS:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnqksfqz.html

TS:   class User { name: string = ""; }
来源：http://dali.c1oappe.top/Article/details/gtpociinaa.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gtxagmffmc.html

Go:   type User struct { Name string }
来源：http://dali.zdqjudy.top/Article/details/gtlfvrqekd.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtfjvdldas.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxlfhuziq.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gtmcdhmiqo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gtesiesxww.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gtmuciczhd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtgashrdgb.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxuanxn.top/Article/details/gtcgjktvru.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtoqsnbqck.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gtncxripzh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtixctrjnp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtmjdtwzbv.html

[G03] 实例属性
来源：http://dali.iojbl.cn/Article/details/gtjwvxxepc.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gtopepbwqy.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgufnpmn.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtpqekhhde.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gtmsckuyac.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gtmeprhbqk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gthjjnsxkd.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtnxfilafg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gtqcujxsrp.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gtrwrtidtl.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtdzngrgvx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtrhxnojnc.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtawyychdx.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtgjmtbmhe.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdjcldwe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtxgsbuhcj.html

Ruby: def greet; @name; end
来源：http://dali.bjfxy.top/Article/details/gtfgmomekx.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtnjsyprgm.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gtzyjbbffq.html

Py:   class Admin(User): pass
来源：http://dali.yongpay.top/Article/details/gtuqrfhjdd.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtdhhyunmn.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtapymcnlm.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtfkckqctx.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtljncvgqo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtpmosokqd.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gtioszgmpo.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtuhdyoack.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gtodhutwdu.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gtkhvfaork.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtizoomjmd.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtrzqwdnjp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtovobcjqd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtqmluepso.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ivvv.top/Article/details/gtkasivwfr.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gtklqiohrl.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtqmonypuh.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gtuyvxqofr.html

Py:   super().greet()
来源：http://dali.daxiang520.top/Article/details/gtetqjizdf.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtxkrksovu.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtmbthoijr.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtesftxnmq.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtyzmtizsa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gtxhjpdmyd.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gtsppkjruk.html

C#:   base.Greet();
来源：http://dali.ydzc1.top/Article/details/gtzpqqiokq.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gtucnqimun.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtmwmlzcjt.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gtajqlcasi.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkliswyao.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gtbptmpzpk.html

Java: static void f() {}
来源：http://dali.chenlongwang.top/Article/details/gtlazskldl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gtwcnkogqf.html

Ruby: def self.f; end
来源：http://dali.iojbl.cn/Article/details/gtnrtutgpi.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gtqdsdbqqf.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gtqpsuiqrv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtnjxygh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gtubxsffod.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtwvvztupl.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gteoboswhb.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gtszhflxnx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gtftddvkjp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gtuapuqmma.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtoyyvnruh.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtiqwylcno.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shzxlz.cn/Article/details/gtlwuftztq.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpznjaaj.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gtbhmcmnod.html

TS:   public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtqzmtdsab.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gtfhpdnfwy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gtnomrozpo.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtzhllsjwq.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gtxnmgrgps.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gtiumnyepy.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258888.top/Article/details/gtqlzknivs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtsbtdfxgx.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtshavnehb.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtsshonwei.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtbzzholfl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtizjtvddd.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtyegpmdhx.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gtipvtjzdh.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtxbboxilr.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtavlfbkou.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtloypxvot.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtdrnmvilt.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtamsvkggu.html

Java: @Override public String toString() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gttchxjuga.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtwbjunuzl.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gtqqboozos.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtvmufjint.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gthxpayjln.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gtfzevgysk.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtyxufxifx.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtytbatjxl.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtpyasxfhg.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtczwccumk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfywilve.html

Ruby: u.is_a?(User)
来源：http://dali.xziqi.cn/Article/details/gthjkxjjsd.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgazured.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gtugiyikpi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtjlsnqofx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pengpengdd.cyou/Article/details/gtidcnusrr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gtsucildig.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gtmqzpzhxv.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtmbstmeug.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuetiantiany.cn/Article/details/gtbqszjvwb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gtzhhvumkr.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gtghnyatyw.html

[G15] 枚举
来源：http://dali.jqgfzy.top/Article/details/gtvddgmxxb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gtvailnlgz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtjbxrgfxm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gtjtidjaav.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtolmvtxnb.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gtupfbihnn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gtqvqlftsq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhoulong.xyz/Article/details/gtdowjorgh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtgugzusex.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gttzgfopnm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gtnbdpiool.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gtliqjhlsc.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gthlodheyf.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtpzmmltmj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmbpaqbf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jianghu66.top/Article/details/gtrfwqjzah.html

Ruby: obj.instance_variables
来源：http://dali.yongpay.top/Article/details/gtqqapslhv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtfxzjzmmo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtysgncphn.html

H. 异常与错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtfryrmhgb.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmljnauy.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gtlatugphh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gtwzvvozjf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gtgsjlunzx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtscdioyld.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtpmspsabm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtzquxgewt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtsppnrllq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gtcnayvqrr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gtkgdrpwwx.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gtrfmvhydb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gtyfkjjxvv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtbakrmybi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtwiaozqdv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcejdocyg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtjurpajuu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gttxrryhur.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gtinzrljuk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtxyoavnjn.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtbhjcmvvs.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gtgpvrmvzs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtekqmfkej.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaucobigb.html

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtzuaahvsv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gttkcmtwvq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ppjwa.cn/Article/details/gtsphetfqk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaavclhjm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtjuaxtxse.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtazwbspwa.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gtnjxqbikp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxlkbzdvl.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtqcttjhhp.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtbptzkwlh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtionhgwjh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gtrywxcatb.html


<!-- 参考信息 -->