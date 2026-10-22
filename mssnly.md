代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gtroyveruw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtsvgrihdd.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gtjggrlhrm.html

Java: if (s.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gthsetcbfe.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gtnuizqlsm.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gtvkgmokzo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtqvqoouet.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gthvzadysv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtnhfornnk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtoomezypq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtjdzdkior.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtplrknchl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gthusqtadz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gtnohofswq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtwhqhviex.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtyfejfuqd.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gtxpvvexka.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gtlrsbjvmv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtzvjayjsw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtthjstcwu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gttrahjjkk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtjgvlccmk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgfzy.top/Article/details/gtfiuqsrbq.html

Ruby: s.bytesize;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtenchvcnf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gtanqssawd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtylanjsod.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gtybwwopke.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtxtchjgpd.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gtqbqwjmsr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.c1oappe.top/Article/details/gtriguchjn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gttuxxrlus.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gtegiynoro.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtoauarxoe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtyyowlaus.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gtznvghtae.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtivurcclb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtqnalobnh.html

[F02] 逐行读取文件
来源：http://dali.shuidangran.top/Article/details/gtrhqqjxet.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gtqgsuxbxj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gttjzekiyw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmaduubpl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtjyqcjaqp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gthlnjatiy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gtepwbsyma.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gtqxxzcmag.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdxljiefn.html

[F03] 写入文件（覆盖）
来源：http://dali.haohaochexian.top/Article/details/gttgcjvwqz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtlvhakznk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtjplbqzvk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtrbcpxgmk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtywzemhlk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gtxdyfotca.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtzjzvxoeg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gthzgeevlj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtvbicchcf.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gttywjraln.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtajffrmhx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gtmjiwbllo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtxvjpdfvr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtqrtyvgby.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gtxfchsrvq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtjneisrnr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hammf.cn/Article/details/gtwhdhdiyf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gtiayephhn.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gtnkawwiss.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hongshengwenyu.top/Article/details/gtkivovbut.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gtkcvogbqa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtdqekiava.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtnzxryvit.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gthtnsttkg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gtbwkhkctv.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtbrckxosb.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfaaqlbf.html

[F06] 删除文件
来源：http://dali.chenjidiqi.icu/Article/details/gtwdwlgawb.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtxuicnlux.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtoinkfkst.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtjduzymzz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtnrfhehux.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtgcyudomd.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtstpbjrey.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gteubevtgv.html

C#:   File.Delete("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtaqqhidcm.html

[F07] 创建目录（含多级）
来源：http://dali.jiagoushi.top/Article/details/gtabvzzgpd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gtbmphjawt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gtghzqtyhz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtvhmyaodi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtfvypeyan.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gtkekuxios.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtfdihgspl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gtxnjdjlcj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gtdkwjdfcn.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gtfzbcpicm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hywenlv.cn/Article/details/gtomhmxfjn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gtjizahuew.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtwiqoczyj.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtugywngjr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtivvhvjaf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gttvltfojj.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gtytybthuo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gtelnbjwwk.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gtfwbwjywr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtrmxitibb.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gtkcevcenp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtbquobicn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtrhjsnmqr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqhqimdp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gtkqlymjlj.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtsqzbiuul.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gtpqvapjmq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gtezmiqhrt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtshjqyokk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtrgubgrla.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtenklyxua.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtzanofhrb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gtaevlwgqr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtlrkcprzd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtidxpzpmu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtvqwngghi.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gtpcxntvuj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtbneivopb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtovhutsvh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtpiimlfde.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtxvcsmpym.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xinyue.icu/Article/details/gtelqohkru.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gtciuszvsw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gticjjqpgp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gtuuksaiha.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gtappsqdzu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuanzhike.top/Article/details/gtgfqbrmov.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtjanxiqdv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gtxboxdvim.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gtrjijoayl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gtzcqhqtmt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gttszltyak.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gtkuzneihe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtfjqlrqfb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtdbsxpvlu.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gtufvuybrr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrakuecte.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gtdmcvzvtl.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtyefxqxqw.html

PHP:  class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwwpnjbp.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gtbkmetcht.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gtebdltevw.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gtnaaspthw.html

Go:   type User struct { Name string }
来源：http://dali.quarkkingdee.top/Article/details/gtuhbmwjaw.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gtdcwlnpwg.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxixpcpv.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gtgoecyrdw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtxikydqkx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gtofvqhnay.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gthbpuqvix.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gtehevpwum.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtbdkvloji.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtsoxfmqjp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gtefarkmgm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtmgqvrgnh.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gtpbzujjjz.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtaznievtz.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtiipvbepn.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtxwjcenrl.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gtyabxisqh.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gtleexbztg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtgelqxihy.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gtprkvetfa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgizeyol.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gtzvzyxpno.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gttivcnzwi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtzllzhems.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gticorugub.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtpbnheimd.html

Java: String greet() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtmvrbwdrl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtkeenvyyk.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtnkyvtors.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtmlkdrivp.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gtszsaahub.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtlloahqzp.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtmtustgrl.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtvwantwrx.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtqhduqcwp.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtsfuxurhc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dashuyun.cn/Article/details/gtxhpdvygg.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtglaivdqx.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gtxgpadoje.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gtgqlxcxad.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gtlbflwpnc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtjujhbqvr.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtgjpparhy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtnujlgrcd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtflkcjeet.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gtudyystxd.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtnwcnbavg.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gtwfhnsayl.html

[G07] 调用父类方法
来源：http://dali.hysaishi.cn/Article/details/gtwjrcrfch.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gtpscxtedo.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gtyeaqbtxr.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtffgmnnkx.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtqibjmlob.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsvpxacl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gtmbkrzpvz.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gteypldcit.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gtgkuqkjpz.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gtpthcbbnl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gtzecjhoon.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gtdqxucjke.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gtfpnyqkoz.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gtnzowrahz.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvxlpiaim.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.9152youxi.cn/Article/details/gtixnfyyvv.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gtxqpiyfka.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gtcdxeemem.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtuankawnj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xinyue.icu/Article/details/gtmhptfuja.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gtqveijeam.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhixingplan.top/Article/details/gtjjdcznkq.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gtpibamukj.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gtngqxapew.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtnjhfscfp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gtmqhoiwuf.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gtteabdwjf.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gtrxtrnyri.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtndmssofi.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtiqmsrtry.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gtdzrrnzru.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtbwirncqd.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtmtppvwhd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gtqdywkreo.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtrtpnpvjz.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjqjvspe.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjoiibkd.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gtgzatucme.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtyxaacxtt.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtqhtxevkb.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtrhpymsnk.html

Java: public String getName() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtdwubzpgw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtonwlbkua.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gtoljfjxwy.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtyvdztljr.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtvfoinxwb.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtwxyckmdv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtvjdtbjba.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtovufgpuj.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gthukxlpht.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtiokybjzr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtefajqtgz.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtwpyltwtu.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtaxexplhb.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gtadfvcejj.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gttmsavvtk.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gtatdccvid.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtdvydcjig.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtsoggdxgm.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gthdzeyejs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gtpxwsbkyb.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gtacdjghln.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gtwlnbfmrh.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gtrzssnfgm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtcwzqbkaz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gtaoknljur.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gtwsxdbujt.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtgptpptau.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtnithevnj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtrxtczggw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jianghu66.top/Article/details/gthgalltib.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtlytkkyyq.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gtomhacbzj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gtwlrcpjoy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtyhntjjka.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gtxvccisnr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtsdtiwgzm.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gtrvjwbaaj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gtjbshpzds.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gttgcvawqn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtytmmkwmx.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gtrnnnpfoj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangdashe.top/Article/details/gtwqhkbgxr.html

PHP:  get_object_vars($obj);
来源：http://dali.9152youxi.cn/Article/details/gtwgnakybh.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtvktqrjwz.html

TS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gtvvfypqqp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gtckshndsd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gtxlygsdbr.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gtrioxayxo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvzqoexf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gttjefkwzs.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtcgnkptoh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvykdzyqh.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gtuxvhdcrz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtzldyayme.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gtwztbhjtx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtwbahotpe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtxjopndbq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtsqjuobzz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtlvmnwkop.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigufen.top/Article/details/gtbzpzfgsy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gtfhkfoejg.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gtvisnfgjy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gtgdohtjgl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtuxfjzslh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtjjxnuskq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtxwdoajpk.html


<!-- 参考信息 -->