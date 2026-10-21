代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfrwkjip.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtisrepgwf.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gtiamadxgo.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gtjnkmxjpm.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gtfkxvarvm.html

C#:   s.Split('\n')
来源：http://dali.gotoacloud.top/Article/details/gtsexpasng.html

[E20] 判断字符串是否为空
来源：http://dali.yueranfly.top/Article/details/gtdcughvpc.html

Py:   if not s:
来源：http://dali.sweek.top/Article/details/gtnzfdorjo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gtzosgnqkb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gtrtwbwfta.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjgrolbge.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtrmwggjek.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gttoppuyig.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gtwclfzopr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gtkojfdxse.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gtsbpklslp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gtaunteczx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtjpyqtcej.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtcojpkcin.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtcwnyjyzi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtpocopaad.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gtksfhtjaw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtjwvtrtsl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtauxmeckw.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gtxabqivft.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gteyyoeoec.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtqcxzalko.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gttgurjyan.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtlnacsyex.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gtyqmcixrr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yongpay.top/Article/details/gthdtrdhzv.html

Ruby: s.bytesize;  s.length
来源：http://dali.iojbl.cn/Article/details/gtueucuyel.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuxming.cn/Article/details/gtvhqaaqjx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqbsgypdk.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gtsfzcwpqx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtoavzxwdn.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gtqcnwumue.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gtnyaqtloe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtzjbwmbow.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gtuafbggmh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtcoyxlxjn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtfuobxkts.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258.top/Article/details/gtljcovtss.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtegcgumev.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtxrvfvffs.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtqnapaziv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gteuqdrios.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnxiangtu.top/Article/details/gtnpezehqn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvchglukn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtjqyfmchi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtnllvkkbk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daxiang520.top/Article/details/gtuwgstmlx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cheryme.top/Article/details/gtftrdepnr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gtwwvegzrb.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gtnuuzykdt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gtyhkchrku.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtomdwtkob.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtzjygpdkt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtetmagucz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gttierxumd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gttlbzghgh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gtxkjxtarh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtramkcukp.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gtpzzffakv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtwdvmyezr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gtqlvxgryc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gtuteouvsd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtqxgeysxo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gtdvlmosag.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gtzepfbwos.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gtzbskastz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gtfiacxfym.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gtirqfkksb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtghsoryhu.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtlstqfwic.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gteivvsexj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtoupydoyh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtiajbibly.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.andypj.xyz/Article/details/gthpvymmgx.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuxming.cn/Article/details/gttaeqnnvr.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtlkcxvjbi.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gtxyapbxdk.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtkwoexknb.html

PHP:  unlink("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtqptunkkc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtcvfdfkov.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtqbmavkew.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtoczsszus.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtumamtbwg.html

Ruby: File.delete("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtqkicznbc.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtaseuejlk.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gtdspalqcf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtaknrkdjp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gtxeeqesgq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtfbplfevn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtmlxlaptr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gtcjhcffgj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gtvvyoqsyu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hywenlv.cn/Article/details/gttxcuqfnp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtieaeiukg.html

[F08] 遍历目录
来源：http://dali.zhengqikj.top/Article/details/gtshmdauti.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gogol.net.cn/Article/details/gtwkowtpdn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gtagrexkbl.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszzquebo.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtqazsrrqh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtdejbexgm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gtglxgqzwn.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtveixpgbb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gtbgiahqdu.html

[F09] 获取文件大小
来源：http://dali.ppjwa.cn/Article/details/gtwkqwqgxu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtvqzqeycl.html

PHP:  filesize("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtixoqdwfn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtlumyztwz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtrfycjzzr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtupjvwtsr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gtlfwimkec.html

Ruby: File.size("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtflatbfsq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gteoomktpd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gtmcytpqkh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtbmruripi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gtrsquqqud.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gthmrtnlop.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtkrzzeggp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gtkglisprm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtmaciwobt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtcqxdiolh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtrkzaxlss.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gtlpgwftle.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtykqltrrk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cqqwz.cn/Article/details/gtggevvolr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtviqcpsga.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtncqfqumr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtdrsfyhvy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtisjtyzyl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtkayxnfzs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gtmrguzoms.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gtdxkkbqew.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gtyxxinvxn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xylfe.cn/Article/details/gtkjikrtjj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtarvmdouo.html

TS:   // 同上
来源：http://dali.sxryk.cn/Article/details/gtowdraacf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gtnnuzqqtt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gtjdzxjkdt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gtzhawvxxk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gtofqwrdli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjtgijlry.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gtauoknped.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqvehyzgy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gtukusmpac.html

Py:   class User: pass
来源：http://dali.zycfv.cn/Article/details/gtuwjwurex.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gtajpuhend.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtgbdrliie.html

TS:   class User { name: string = ""; }
来源：http://dali.quarkkingdee.top/Article/details/gtyqvwghfj.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkmcfialw.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gtoahlnyqv.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gtmqlolkjv.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtsxohagbh.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gtqsveilth.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gtnwbtxkww.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gtogkgvjch.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtzsqzdwnd.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtvebsjwgo.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtbmdlqnli.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gtdgukjtxk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gtgdffzvot.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtevowzduz.html

[G03] 实例属性
来源：http://dali.iojbl.cn/Article/details/gtffsudpuc.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtbimnawss.html

PHP:  public string $name = "x";
来源：http://dali.sweek.top/Article/details/gtzpvsicwe.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtospnblcr.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtrvsacmca.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtvjdhuedy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuqkutya.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtkgvmfvwg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gtpfkprqii.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrazjbdgr.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtlqzgnuok.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gthsldaedi.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtvtxqffvn.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtmsswlamb.html

Java: String greet() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gthyyijjlm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gttggmtmom.html

Ruby: def greet; @name; end
来源：http://dali.mhx1999.top/Article/details/gtvzmgewil.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtydxjogkm.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtygwixkgz.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtbcputkkd.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtcejawetm.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtfjikgury.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtmerndqpj.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtyoawbych.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gtxauthqjt.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gttuvexdyz.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtfyxqjugm.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gtrrzshadu.html

Py:   def greet(self): return "admin"
来源：http://dali.ydzc1.top/Article/details/gtvhwliytr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtfbdytkyx.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtwbtdgbzz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gttxurwfoi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtetratukv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gtrorskmmo.html

Ruby: def greet; "admin"; end
来源：http://dali.iojbl.cn/Article/details/gtpmzsbabp.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gtixiqiiuq.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtotzaevja.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtnaewzhha.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gtrlwpkwjk.html

JS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtffndcotv.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtdkdltjoe.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtqbpyclnh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtskxhzvch.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gtmwnmzcep.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gtrvfhgltv.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gtuptbfeiu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gtibzyfvxf.html

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gtuquhcpym.html

JS:   static f() {}
来源：http://dali.tianlin.xyz/Article/details/gtkfhfgdqv.html

TS:   static f(): void {}
来源：http://dali.xuanzx.com/Article/details/gtingezjjq.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtwkpmyquu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gttcfgfwha.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtovtnobhg.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gtyvpjvypy.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gtlnftnytq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtbwzbblxi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqpukpdxj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhixingplan.top/Article/details/gtxdvzpmkd.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gtnytneiyi.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gtlemhafhm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbrlxgaw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gtdjwfbwpc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivwyscdk.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtqnvgtpqu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gtrulckaom.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtztidlgqb.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwrvzzvd.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtsrlrzcca.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gtonrksjns.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gtvhyhwzxy.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtuczhelyj.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gtsoxymjgh.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtczlrsbma.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gtubdcchyz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtkwcchxsk.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtyxmkccei.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtetyplycg.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtejpvfvrn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtloeybyee.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gtzhotubbt.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtnhywkmkk.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gtmheozfbr.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtfkjuvmfb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvotdciia.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuwzsofup.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtkgoyazmt.html

Java: @Override public String toString() { return name; }
来源：http://dali.316326.xyz/Article/details/gteqpbaojr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtwspcvvqz.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gtlawhjubk.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxinkj.top/Article/details/gteburwsjc.html

[G13] 判断对象类型
来源：http://dali.gotoacloud.top/Article/details/gtsikgtlrh.html

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gtppvgchkd.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtzgdpdrsq.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtxtqmbora.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtbmhnacmn.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gttvsluqvf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gtzxxxicbt.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtvegfzcvg.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxqhvufe.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gtdvgjazvp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtdbwjppoj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtilzyppjq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.snrcjt.cn/Article/details/gthqegtwdi.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gtwvnvxypy.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gtifulpjqu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayesnpev.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gtupnlxjed.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwksvsao.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtxfajebqh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.0kj1m.cn/Article/details/gtmotfztba.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gtvlmgzehi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtdennfjcw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtgivyiylr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gtfqrzlzcj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtqkobjozm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.birdmap.top/Article/details/gtvsrazugy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtkhvyvztd.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtgskiebpa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gtcghqfwiw.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gtxmhaigjo.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtrnsrmcym.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtoysrtoph.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gtgonhvegr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtsaavirzl.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gtdaunjklb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtffwyfclh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtelluwgey.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gtiqnorfew.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtaeexpabg.html

[H01] try / catch 基础
来源：http://dali.jinqigufen.top/Article/details/gtnbvklxuh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtxqinzygt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtjypnipzb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtxfzomyol.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtddsvigvh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gtzjiuralq.html


<!-- 参考信息 -->