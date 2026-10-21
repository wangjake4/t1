代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtztjoawgg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gthwmvwbtu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtylhueozm.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtrsivsbdz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtkepkcfks.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsgbteii.html

F. 文件与目录
来源：http://dali.sxryk.cn/Article/details/gtobrlyxld.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtptgsrrrl.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtjkplpqcx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gtsosopolb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtcbpcufeh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gtmeulljtz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtatmkrpfy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtlamvvhzt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gtlvlzucfv.html

Ruby: File.read("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtynouqwca.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gtnxkpmuwz.html

[F02] 逐行读取文件
来源：http://dali.jlsjyb.cn/Article/details/gtuhigkilf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gtoszuwdba.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gtelomurfa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gthueyznoi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gtnlnvvama.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtzbjhlyiu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnxiangtu.top/Article/details/gtdbpibuan.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuxming.cn/Article/details/gtivyjhbjd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpnvpcwu.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gtowurdzae.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xylfe.cn/Article/details/gtffughavv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtralxaogk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gthzvcifpq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtxaywvgrf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gtvwjgzoaa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnqzz.top/Article/details/gtjnafotlr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gthgfwxrjn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gthgdmeqxs.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gtmrjsdfue.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtcnpvtoci.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gzhubu.top/Article/details/gtydiqcfbm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtlvqlygsy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gthduyauxr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwytaskg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gtwpsrpxqn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gtlkodqoch.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gtvcixhldy.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gtrtwwtefd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gtlyqceyna.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtthhdicqd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gthipdjdsn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtjberjwvq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtxseihzsy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gtujioxgju.html

Ruby: File.exist?("a.txt")
来源：http://dali.daxiang520.top/Article/details/gthcyuczpc.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtsltqlvor.html

[F06] 删除文件
来源：http://dali.snrcjt.cn/Article/details/gtdfpbbbmq.html

Py:   os.remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtygcymqge.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtncvmmpdx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmzqexpbq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtqwpxcggq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtrswseoqx.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtdupevtzg.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxkfkgds.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gtrcsolevs.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gtwycwtayv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwmkhgku.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gtppzxtbvf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gtebqrigcs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtuhgurqiv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gtyxfwfchf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gtskcnwgpx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gtgvzepbdv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gtbijhuupb.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gtyozgnczx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pycfn.com/Article/details/gtxpaccnij.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gtakowposj.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtqfqneita.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtbtswylxz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtwpxrnxwp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258.top/Article/details/gtxylbcoha.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gtwiktfrlt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gtsoxuemjv.html

[F09] 获取文件大小
来源：http://dali.jlsjyb.cn/Article/details/gtxuybsalr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gttedqxcok.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtlrvvexsy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtssjqrbmi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtrfoykqwu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtgfjutksn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gtluoxoqhi.html

Ruby: File.size("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtpzjlqjvk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gtoytjwprq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gtrsjwesqk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtrjhxlzmi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtzkacxwte.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gthfwgasiu.html

TS:   path.extname("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtkazhiqiz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gtgccrneuh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmycoitwq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtfymhttdf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtinrewmro.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtaspdbiag.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnujhhwbw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gtvyabqcak.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtpvzpubfo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbtnckxvy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtwskercxn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gtxnywvbuj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtncdoamti.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxuanxn.top/Article/details/gtjvgdogcb.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gtcyfivafk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gtuturdmyx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gttfbsowvr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gtzplaodse.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gtuzuzykdi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtbcmoovsy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gtjezrpdwa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtxoctpans.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyhwejzo.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtomsxexzw.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gtebafqrfm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtitbuhuvn.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gtqluihynj.html

Py:   class User: pass
来源：http://dali.xziqi.cn/Article/details/gtazoavitr.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gtvlfjndyf.html

JS:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtlibfatyr.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gtptcvmfih.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gtcimxpsci.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gtblysyxce.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gtmxvmhlyz.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtvaxmncce.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtdxkdfxsf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gtemgniffk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtfmeprzdf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqxfffkt.html

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gtrbjfzkbr.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdwpbtjie.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gtimbcnwlr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtffolzwak.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmojkopkd.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtgkjrbkdv.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajnvjfto.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gtgeykmzkq.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqenonsjq.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gtnleczcpo.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gtbsfoyceq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtdfwyfggz.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtnorlpznm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gtjammhzwq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gtvxzhtyhn.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtgukynazz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtkzrwxwdr.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtlprksvqp.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbqzuynn.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtqpdgvgqc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gthbrubsvi.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gtkkvzgxyy.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtfkoojrzn.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gtffwsyutt.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gtlekbmllg.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkransck.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtnlomftix.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtgwbrhxss.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjjkwpcv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtsmxuetip.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtmqjvzcuw.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gtmmvahwkh.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gtbrefdeeb.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gtctbfltwb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtnpfrjhzf.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtlzixkjtu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtctggfzuc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzdqngjts.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gtaxgcnjwp.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gtrwadvcsf.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gtybjsdwlr.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gtbltrmmcc.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gtcpuaqwkb.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gtdgbcxqzf.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqohfvdo.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtewiboktt.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtlvljdobr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gtonpopccz.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonusiijj.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gtmyungrhv.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gtewuwwkxb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gtfjumkcft.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwegjwdxd.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gtrckznktc.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdxynbulm.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtpxcbgwnt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtcvkqmyoa.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtqyiynhoy.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gttrlpwedv.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gtrsiibsmi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmqmzeyp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gtvvioeuab.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaoopubdx.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gtdscmibgv.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gtpleluwpo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtgwvsbsvy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gtqfudcdvz.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvormqrhw.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gtdkulxsrn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gtvyleewaa.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gtuvfbpfyf.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gtcxxzwkat.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtxrwkocqa.html

Java: public / protected / private / 默认包级
来源：http://dali.yuanzhike.top/Article/details/gtwhjlltyl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gtbirthhfo.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtksntehpw.html

C#:   public / protected / private / internal
来源：http://dali.zdqjudy.top/Article/details/gtyqydildm.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gtvuhemtca.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gtuhwmaqyh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtiyosplgr.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtjymdclgc.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtbcoxnvjd.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtwjctqeua.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtyneifjtl.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gthwqehfin.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gtitclydbn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtdicbmamh.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtrcettlse.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtqtzamvvt.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtnyiyolkm.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gttjbevjuy.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gttaucqxno.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtalsglqgo.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gtvyzikbst.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gthnskflhx.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gtjcsysywt.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gtpxiznkrq.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtwmbvbrga.html

JS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtvvzhaizg.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtyabtdmgv.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtjdqolwqn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtmwldytnw.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtbrabkdiv.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtmqtecynp.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gttpnclebg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtqbehnhew.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gtsjqenzou.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtmqedqqmt.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gtsctcqunf.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtlcxpcore.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gtttadyteu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtmlevddfc.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtxhawfmaw.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gthglscdau.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtatbglmgr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqntrlst.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gtlquueiib.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtdnbhxtdr.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gtyulfryyz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuetiantiany.cn/Article/details/gtnnqndrzm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gtotrqjnfd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtghtxskow.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzpfoalk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtdortfpqj.html

PHP:  get_object_vars($obj);
来源：http://dali.bjfxy.top/Article/details/gtcfzmzahb.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtsjqshziu.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtogwnhuzs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gtmijjzqtz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocefwdnc.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gthfsnknke.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtstxhmxds.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrdievkku.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gtkjiysbgk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtpvrfhgex.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gtlkrmlnif.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtmwrlrauj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gtqanldwox.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiagvfuvg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtkwouiyyk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gtaysnwpwj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gtexhahalh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtslwpftyy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gtclmageys.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gtpnnytscv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gtghmpsusa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwjuguhvy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtegbssnug.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gttdqkoesv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtdnpimpja.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gtexleqhef.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gtmgpmsmpm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtkefqwlfe.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gthbhdgdxq.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gtqcfmpgtb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gteekkoarl.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtbarnbibc.html

TS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtjqbfkfuz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdioypnkr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gtunhlpnsr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gtoezfdjch.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtpmejvovd.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gtnedxajut.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gtvjioutpb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtnffnyimj.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtufivtdjf.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtrrsfhluk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtnkhbhrgv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenzaomai.com/Article/details/gtwxfkrcow.html


<!-- 参考信息 -->