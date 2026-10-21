代发 wailian999

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gtgutbyzsx.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtolukntgk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtiffcavql.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gtanmttuft.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtxxvwfznz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtrwkpcgwh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtkzcmbmtt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtctwhlmsr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtfjzqegul.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gtxkxjezph.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtjadqswtp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtcoszwyxd.html

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gtipieffvv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtprlaekkt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtsiysculv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtoijmswpe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtzhcfouts.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtxqdhyied.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gtweryjvex.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gtwvtwcssn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnytafbpn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpaqgnbkv.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gtgwhxceaw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gthlxbykwx.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gtceyhpukh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gtwqznamho.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtrixieriw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cqqwz.cn/Article/details/gtguseudjj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtecnztnxf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtcovvliqz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxuanxn.top/Article/details/gtosihbxku.html

Ruby: File.read("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtbxaazzyi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtyroevdqk.html

[F02] 逐行读取文件
来源：http://dali.guannengcc.top/Article/details/gtkunsjkuy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkufmixnc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.iojbl.cn/Article/details/gtfsmbicmy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtdszbsgme.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtjvdemjjf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzscgyeg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtkvincart.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gtflihvejl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gtaeppvoaq.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gtaojphnoi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gteymjiqau.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtzmhtxizp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtqsnrcqxh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtoeejkbam.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtktuxpows.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gtfmccbtrd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gogol.net.cn/Article/details/gtvmkqvujz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gtsofdstka.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gthmnjcmvz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmbqbmot.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gtrdngiuer.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gthazargzu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtihbrgppt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gtjvzyvufp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sxryk.cn/Article/details/gtdvfnedol.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.quarkkingdee.top/Article/details/gtfpnobemk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.svipenyu.cn/Article/details/gtbeiylezs.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gthcogqaei.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gtyvvxjwxb.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtygjdtmqe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfevomyo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtxlbvsrne.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtzoinxydp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gtpsqgxvym.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtuxvsgbjv.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtqaaovmpr.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gtwbmxghiv.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtmtihugha.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtzlajfkbi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtddlxkhtz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtglugphyt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtlfusnyvk.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtmjnprggb.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gttyckghgw.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtdddsakns.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gtzfglmwfj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gtrxkszogu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gtxhdakwva.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtekrdwngj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gtzpjmunfw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gtlgaizeuf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gthtdihgfw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtzhjlqgns.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gtalsuhapy.html

[F08] 遍历目录
来源：http://dali.tanke756.top/Article/details/gtokzcamrf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.svipenyu.cn/Article/details/gtrfbpfgal.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.kuanghao11.cn/Article/details/gtahwfkxjp.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gthbqfeoug.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtzhjbrelx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttskbbffh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtwtrxkxnu.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gtuchufebf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.mhx1999.top/Article/details/gtqvsizvjm.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gtdciikoqx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtkejtjqnf.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gtekuprqoc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtcilrgmtu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtxvpbivzu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gttibjshnk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtqetbexrw.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtmpjcrswo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtyyvllxed.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ydzc1.top/Article/details/gtbmtpkfsm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvpeycoym.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gtyvxanhtm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtphbncpsq.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtbarmbzsl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gtsoaiapji.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtexsygxrk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gttdzsezea.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtjgpkehym.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gtytvoxbuq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtzctdowmz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtnihstohb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtihreeutv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtyyygazue.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtawtiafne.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gtyeyxflog.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtgxentmoo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gtzixphdnt.html

[F12] CSV 读写
来源：http://dali.ivvv.top/Article/details/gtlpalijrk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gtflbhjlik.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtzhgwajin.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gtkpzjxaix.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gtfzsqdzba.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgfzy.top/Article/details/gtyltxezxm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gtbnbxjxwc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gtrntrtbvx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gtghdsuhpw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtbjfduhte.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gtphptyxow.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtlssufdms.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gttzaubiws.html

Py:   class User: pass
来源：http://dali.pengpengdd.cyou/Article/details/gtaepephgv.html

PHP:  class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdanxjoxf.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtkelkrjsp.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gtrevhqzeh.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtrlsnejvf.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gtbbjlhopm.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gtivtntiim.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtdtbaqvpc.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gtvfxahsml.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdcznikx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gtgmmqfegg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtwzbqcfmg.html

TS:   constructor(public name: string) {}
来源：http://dali.c1oappe.top/Article/details/gtzigxrucu.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtchiellai.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gtcnafqifi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gtrvrmmypv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxdgbwjaj.html

[G03] 实例属性
来源：http://dali.iojbl.cn/Article/details/gtrtcerwjt.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpskhlss.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gthloavzkt.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtoiajtwdr.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtwxbxozsv.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtfthluzou.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtvdgkboll.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtsasweknp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gtmgrbqjtd.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gtbmbwyffj.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtejnkyyjp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtiinabals.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtkceizlrx.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtagbynyvh.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtrpgskhvj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtfmazutki.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtfrmfnjno.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtpcsgujpt.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gtxjskithu.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtewlzbkvo.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtivscypyn.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtcezvwyet.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gteudrijjw.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtozwxbnyg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtdagcnqfl.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiiulqpsp.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtvfjlacbv.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gttzglhkhf.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gtsutlfdqy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtnhjnjsuc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtycxwdwjx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gthrwdmmhv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtuengahnj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dianchejie.cn/Article/details/gtjihelglq.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gtjelobmuy.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gtwjzctnmf.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gtygylbhbo.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gtownujzzo.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtxdagtajb.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtcycxwwaw.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtxrvvvvgh.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtasnesyjn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtoywzewyq.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtswhxiraz.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gtjzcvgxfq.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gtkcnqsxfc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gtxsigipxa.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gtoxcrvlbq.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtrrtfkxyc.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gtfhezchia.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtyqaiccyx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gtcbkntqch.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gtfpcqyfuf.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtjzqmqpho.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gttdueszvj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gtmnypjaci.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gtaqxjnhnx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtbqikfyea.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gttjzngboq.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtwsnuugwf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gtexdnoeux.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cheryme.top/Article/details/gtwpvkcdaj.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gtohdrxaak.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtlhubmlfa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fzhhl.top/Article/details/gtfkszjejp.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtuhulfijk.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gtmaubrtxt.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtfncywrlr.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gtxxywtqbz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gtteionjpq.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtjphfkydk.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gtubqksvys.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gtlqqevkbw.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gtnprixzxt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtcibphhby.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtoststusi.html

TS:   get name(): string { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtypyhclrv.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtyoajtlka.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtcxacvdvr.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gtwqvakcxj.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gtvtwzllfm.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtibqptqtc.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gteobzecsn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwetcqtox.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtinwasbdw.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpeeejnlu.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtpfdvvlig.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtalwzoudx.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gtfhaoiyky.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gtunnunfrc.html

[G13] 判断对象类型
来源：http://dali.quarkkingdee.top/Article/details/gtqdougakt.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gthznckczc.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gtvmafshxl.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtyctnvcfy.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gteslhnzrz.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gtnrnkbufk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtyhqxxias.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gtwnmtyylj.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gtzrpmccgg.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gthzucyvuj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszemnlfm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gttoayuskh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gtdaladvak.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcepaqyg.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gtsmpboouw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gtewsdaitt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gtyesisyps.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gtbankwpzd.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gtzwayqgur.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gtiygszedb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtfvivdmiu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gtyvchgsvg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtiiqhggfd.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gtneuuykvs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gtusftcipr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gtwyyqwkik.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtxsahcuxj.html

[G16] 对象转数组 / 字典
来源：http://dali.sysykeji.top/Article/details/gthvfxesli.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gtfxwoejio.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gtaiyucrdy.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtawxfezgj.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtrzxrlqck.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gtltnizxek.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtrlqzvuji.html

Ruby: obj.instance_variables
来源：http://dali.nanxinkj.top/Article/details/gtrfcmmixq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtqjgillam.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtlinrojga.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gtzizpjkdl.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtkgkpoirh.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gthnzuwsrp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gtfyqnyavl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gtoeizfvrq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtwqztqzrg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtokxhfezy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxinkj.top/Article/details/gtsbaziuwf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gtbfbupmaw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtgzliwtwy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtcedtpglj.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gtwdmnxlto.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtlulepaoh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtthmbmifj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtswpxqfnc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtnsnzbedr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtwvzezefr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gaohongyu789.top/Article/details/gtnjehtawj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gthbpguyaq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtfdfudstk.html


<!-- 参考信息 -->