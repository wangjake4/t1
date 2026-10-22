代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gtwmaqkgtn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtipavpyvf.html

TS:   if (s === "") {}
来源：http://dali.yangfankeji.com/Article/details/gtpainqiyk.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtmoathjzc.html

Go:   if s == "" {}
来源：http://dali.wangdashe.top/Article/details/gtnyyehsjo.html

Ruby: if s.empty?
来源：http://dali.shzxlz.cn/Article/details/gttktysblm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtgzgremiq.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gtmgrbykgx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gttvgfzedd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtefrllqpl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtwtiigshb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtmhvnhmzg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtwlgoyypb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxirkowpl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gttimxqxye.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtmazdkoqo.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gtbwkowohb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gtfwcrwdgx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtodkyifji.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtpkarfubx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtfbfbkndg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gtozscczrc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gtjeuvujsr.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gtcvpxmbjy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gttldjhzch.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoztyjsjq.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gtbghuxcmt.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtengnuhaa.html

[F01] 读取整个文件
来源：http://dali.yj202588.top/Article/details/gtcjwfjpuf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gtzrmkiods.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sysykeji.top/Article/details/gttnkxrqkz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gtkpgvwfmr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtjpwjdnpz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtfeefgvqk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtruocqsdt.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtgkrbucgb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtjbjxupwf.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtkczkcius.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gtbhfwpmuw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtgugpdgqa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gtauxpwadr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtwhaqwjfc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtvibebian.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gtazplnysq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gtmfaxswiy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczqzjqsa.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gtjtrrghkb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xinyue.icu/Article/details/gtkjhlxlki.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtkustkjrv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtkujkwipl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtojwyawmz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gttuzwyubs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gtmlqftrix.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gtydjhyrqy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtrtsmmsrg.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gthxmbbmmb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gttpkcqowm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gtnslfmwrp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtshqvwbms.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtombsvhlt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtffkznikp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtzbxatria.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gtbsaozjcu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuzycohl.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gtpzgrqvob.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtpcsnhvcw.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtivhrxavu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtiblcnfgl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtfehufqua.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtxrbdnzci.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gtwsjmpheb.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwflmzbzm.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gthvhzvlsa.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorponfec.html

Py:   os.remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtifvhifyc.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gtmkpccgil.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtrfhphque.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdqtdxtzz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gttpczqmmm.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtgjgbjefl.html

Ruby: File.delete("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtvmsimmhr.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gtglkgjhyn.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklkikatr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtjiljyjxm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gtzvpbqdve.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtcqmhnfdb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtlpftsoou.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gthswbtent.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gtvjmfvbpg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtocttxief.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hongshengwenyu.top/Article/details/gthnfwbuic.html

[F08] 遍历目录
来源：http://dali.iojbl.cn/Article/details/gtmgbfgmuv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gtijfhsclk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtlhnvwlyi.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtyqrzgapl.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtreuvchiw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtkqhrrdwy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gtgrdrespn.html

Ruby: Dir.children("dir")
来源：http://dali.yongpay.top/Article/details/gtmrggrjgh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtircgiidy.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gthtcsdxuf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtyivkyted.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gtjlgotzki.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwbcqdju.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtbqnzjbqu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtfinkygtk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gtsoyqzshi.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtbnlzifjn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtnilmnnbc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhiwuduotai.top/Article/details/gtcglliele.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtdywmxcxj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtehzokhdi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtoaxbvxkd.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqzhvchaf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gaohongyu789.top/Article/details/gtuyuxupbm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtvwgaiiqh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtwrsylkgn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtjwufjcul.html

[F11] 复制与移动文件
来源：http://dali.jinqigufen.top/Article/details/gtnoymgwxo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtuaoikimq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gtwehllkgs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtxjivvelg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtnwirtljg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtuajustky.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtplvdwrnf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtiqkiiyeb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gtnnnbvuve.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtdwwckgvu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gtdyfugswl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ivvv.top/Article/details/gtmtqxaiwj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gtwrwpixei.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gticfoasuy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gtfxefzlfm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gtvjwnxzbx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtetqpafnl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtnmsvzeod.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtjqmxvwfe.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtzqagwjhg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtdluzcspg.html

[G01] 定义类
来源：http://dali.dianchejie.cn/Article/details/gtgkjqnche.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gtqykbnklr.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gtvhczqvsw.html

JS:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtidodychl.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gtxjayewci.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtqfdalhgq.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtganssvbo.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gtdokqrjgx.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtmquqbszo.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtnjegzmlb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gtlmtmmclk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gtgwpypysh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtfmhquwpe.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gtrozrnkln.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtxqqosctr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gtzgikhxpv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvwjmagl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gteyvemhxy.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtgfhenmql.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtklboyxbk.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtikvcovuc.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtprzzysib.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gtpextnhwj.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcaaklab.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gtnrtjnqqg.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtnfumytms.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gzhubu.top/Article/details/gtzoyobvqf.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gthjrjujvm.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtjqponntw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtttoxwapi.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtotkudueb.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtlxbrcfqx.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtjneckgef.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbyuddkn.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtjzsxxxyc.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtjwurowpd.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gtosotnkph.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gtfddaodvk.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtwxrfxtnl.html

JS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtuktpxdow.html

TS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtjqqtpcou.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtqocqilgi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdztrjzw.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtwjqnkbwa.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjcpesdg.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gtwpjxxvff.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtwzpdfsnr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gthwjtpyqt.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gttdfliksb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtfimlvhdq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtbunavybd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xziqi.cn/Article/details/gtprxbucik.html

Ruby: def greet; "admin"; end
来源：http://dali.xuetiantiany.cn/Article/details/gtwntrkibs.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtpfwehryb.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gtahenzifg.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtbvwmrhof.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gtmbiurowb.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtytpwrvor.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gttysgjnxo.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtakbkjocb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtvmuegjnk.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtkcskzqkb.html

C#:   base.Greet();
来源：http://dali.yj20258888.top/Article/details/gtkgwsryvf.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtslaovsha.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtlmudbjel.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtgplpttju.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gtesewjrai.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gtdwaempjc.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gtyshzvbyf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtczelbbis.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gtaxkkrvzr.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijpgcgpt.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gtdquknjpy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gtdwhlfmtg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtqzkktolg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gtgpjpuqak.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtvsrpsjep.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtfyiqmgds.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gtrgdwqwbe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gtevnzvwqs.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gtdfcgxyvz.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtnopkapbb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gtksykrixx.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtgeyepukt.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gtaolzljjy.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtrnwgeepx.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gtuydbbpjm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiopoofb.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gtsducachf.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gtvdnklgku.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gtsiotujag.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gteotzztqn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtuyyfakmn.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtbsvgdnda.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtwyahskhs.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtsegvxgqp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwawghhvx.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtcsylgfyq.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gtzqoguhye.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gtgcwwyemr.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtrwiprthy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtekswtajm.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtkmuhrnxl.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtjkqkittn.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gthqpgpzjc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtjtpzwehn.html

Ruby: def to_s; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtiafbgkzx.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguadkmej.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gtfcgviwaq.html

Py:   isinstance(u, User)
来源：http://dali.dashuyun.cn/Article/details/gtprwthfnr.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gthzzsoqhu.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtqpnvhubw.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtwhucqoeo.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gteswkidsm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.feifeiyinyue.top/Article/details/gtcxxyekas.html

Ruby: u.is_a?(User)
来源：http://dali.mhx1999.top/Article/details/gthnlaqaaf.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gtrrivtynq.html

[G14] 数据类 / record
来源：http://dali.cdnleiting.top/Article/details/gtvilfekya.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtmeugxazc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtuddhrlsg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gtvsllisdf.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gtghgvneuk.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtctxrniux.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gtbfzhankg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gtvqzixaco.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gtwblvamti.html

[G15] 枚举
来源：http://dali.jqgfzy.top/Article/details/gtjuzuamda.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtovumhbku.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gtkejaptdu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhengqikj.top/Article/details/gtetzmowie.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtttbgxnft.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gtpdedzdqm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtypzljrfh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtaofjjrcp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtacfqtmgx.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtvkozxpgv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gtbniyjjby.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gthgsmxbcq.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtijdfanmb.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gthunfgivh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gttvmcvpcj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtdjqwibqy.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gtzhcsiapp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gttijcbmta.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtmitjhxax.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gtcaoladmw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtcvmqqxty.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gtgekuanjm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gtqhkghioo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gtqycybfxe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtziqxuckc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtonkffxpa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigufen.top/Article/details/gtpehgktkh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hywenlv.cn/Article/details/gtkfvphzqf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gtzsakktbz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gtnzctpifs.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gticvtnjfw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gtgbsosfwe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtkdopviku.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtucgkrrlj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gthudygfwh.html


<!-- 参考信息 -->