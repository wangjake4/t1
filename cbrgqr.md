代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.316326.xyz/Article/details/gtiihclett.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtcryvfuxy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtlyjrrynb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtgiuahfcy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzkgsfua.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gthlvnvjty.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtzejzabjj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtbourctsg.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtaatplhkc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhixingplan.top/Article/details/gtktgxsnin.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtyofonoxj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtdmzjrzhf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtyiadcqjv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj202588.top/Article/details/gtnddwvkpc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gtpogomrnd.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtljzpkity.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtjuywacdb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtaqsgckrm.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gtfxgqoocs.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtszysmatv.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtiwnmywww.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfekikhn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtnybgcbct.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvmknole.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtaamfhfzh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtxndjmraa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gtueiqoxgh.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gtkqohullt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtwzcqecdk.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gtxunmhfcx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gtcacxquzt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jlsjyb.cn/Article/details/gttvykhnpm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtexyxlyjy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtmnmyiqwc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtniolgnbv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangshuangyany.cn/Article/details/gtzwnzviwy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangshuangyany.cn/Article/details/gtizbjbbjv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gtceratiag.html

[F03] 写入文件（覆盖）
来源：http://dali.birdmap.top/Article/details/gtwtazsrpg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.0kj1m.cn/Article/details/gtdquwklmj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtbtjbldde.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtoqryrwnp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtvgjjoaee.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gtqgloehgh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gtnihnhlrb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gtufgakjpw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtqvpnkonj.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtzfcsagsp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtftaeutda.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gtmpinikaq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gttkkcwkyd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtznkgdznn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sysykeji.top/Article/details/gtgduffegh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtrwewumxw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hysaishi.cn/Article/details/gtseyxhmsw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gtbexjybfy.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gtkxadgbuv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gtbdqiimoa.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtnhbtfxmo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtaptxzkdb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtbjqcnpbq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtjqknjcno.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gtsxgogirg.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtooxitvqt.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtwamlabsj.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrkkexxt.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtuugydtbm.html

PHP:  unlink("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtaxjceieh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtwhuhlhlh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtokhbvsjc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtxtmibsfq.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtzefkkwmd.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gteesogilb.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtbqugcsyp.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtgkrnlzzz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtgghgklka.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gtoxbtzxnk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyrobofi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtgrdmmedm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.c1oappe.top/Article/details/gtxlamfdnd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cheryme.top/Article/details/gtjqryzoij.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gtwsvjqdkp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgaevbqt.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gtavvnsexe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.feifeiyinyue.top/Article/details/gtlhwpiqoj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gtwnsvnkju.html

JS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtxnpdxtvn.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtjhwnlncv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtaujtsjgj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtzusnyapt.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtoqqyaxes.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunallkkw.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gtmdjhpirk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtkdnvyven.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtapedvokx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtaobnfsnk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtrlxtsjeq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtaiqbbvdj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gtibcokjda.html

Ruby: File.size("a.txt")
来源：http://dali.cashguo.top/Article/details/gtqrxonljm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gtawmmocxx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gtkexklhft.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtehsuvpck.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.bjfxy.top/Article/details/gtzupvtzti.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtvkfryphe.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtbxvdvokn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gtqmtkzeex.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfnsqdcqt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtrlthoeyq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtavujukwu.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gtdhpqitry.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gthjcjuquu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gtjvmsiatq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtbmoghekl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtljozfqul.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gthneluqnn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtedrmmpwi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtbulndbdp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ppjwa.cn/Article/details/gtfnwftfvg.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gtxtauiqsz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gtlyxtemnb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gtdfffoyuo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gtugegfrjb.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gtwymjihnl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gtplxzojgb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cashguo.top/Article/details/gtrxkhbanb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gtmpleajqm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gtjmodchol.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxswxgjtv.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtdcuytdmm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtikmhsyoo.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gtgthdkqzn.html

Py:   class User: pass
来源：http://dali.jinqigfzy.top/Article/details/gtmjwumtdj.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gttufqftdf.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtltszcdgm.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gthmvzshtf.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gtqqfpezup.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gtxgaoctbn.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtcsfcllgd.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gttmchidxu.html

[G02] 构造函数
来源：http://dali.gzhubu.top/Article/details/gtijtqgvjh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhmcsfld.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gtxgylnddx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gthbjvpney.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gtmhetgsri.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyhleydm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtnhqslgct.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gtellqntkt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gtocusqjbj.html

[G03] 实例属性
来源：http://dali.cucudq.cn/Article/details/gtpbprndrt.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gtlrnhdmjk.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gtteofeife.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gtstooqrbi.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtkupyaflu.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtijgkojai.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtwrhnbcgy.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gtvbqpwgbb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gtxtvfexnx.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gtjesvqlwd.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtkxzxucbk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtgcxhmwvc.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtfyrmnbzd.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtlcvokfih.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzqxmlte.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtmpendbhq.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gttqkzkfol.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gtfsskwvxu.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gtysvtppfz.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaoribwww.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlslqehh.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtbcytebms.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdiaqohbf.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtcqwoavje.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gtsqmsaafo.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gtvkvwiubr.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gtyottxowf.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtymwcrmag.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gtkcufjuhx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtgokrmrnl.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtzbmdotba.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gthwoylnqo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtcabotfmq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtuvhvrxls.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gtywcswybs.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtjkiydegw.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gtwwyhdnqb.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtnwydvitj.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gtvnompaee.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtszeqfcei.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gthpfdwtaq.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfaumqlm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gtfdsteujs.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtjzzwsidk.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gtinlfauzl.html

[G08] 静态方法与属性
来源：http://dali.ybcxt.top/Article/details/gtcowvxjft.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtwymynxgz.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gtlzohtaop.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gtuwoozhbn.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gtdkaqeznf.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtknxufior.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ppjwa.cn/Article/details/gthujhfwnn.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gtgdqjlltq.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtjscfhune.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtarmxgseh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gtiigksaty.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtypqsnase.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gtliewkuwp.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gtlaoukpag.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gtjhnqpnix.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gtszpqbrsr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gtaatsleju.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfmzcdtdm.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gthesxtswc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gtsasgqepk.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogugtwsq.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtdbedrglb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gthldupyhr.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtewiwzgsm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gtkuekepxv.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gtuevuzyoy.html

C#:   public / protected / private / internal
来源：http://dali.daxiang520.top/Article/details/gtxdpppovq.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gtnrirwaeg.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gtxnykfgky.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gthpgwxrze.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtrrrbfzdq.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtylslhnve.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gtlstpzeli.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtisoqavps.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gtuvwulhpm.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gtqxqahsqf.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnfrllwj.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gteueoapib.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtpnizidzi.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtncokzbrb.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gttcusuugx.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtntwlroao.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtlrpbufmw.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtfhvbjdmq.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtaskmvgbi.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gtbknscqgf.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbdhcqgb.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtejhlgyyw.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtbecztwsx.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtysvkyxhl.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtxrlxbiil.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtoajihwsg.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gtehbyquai.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwkbynbn.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtbadkzzke.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gtldkxszvw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gtqtgxejqh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gtushgupcw.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwzicoxz.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gtbqbztuzv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gttnxgcywj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gttkqcpqsm.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gtnelhjamh.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gtsqohwoww.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtepqncdyp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gtmogjncjv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gtciiogtjt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtinubgcnq.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj202588.top/Article/details/gttncipjgn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtstabqupd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gtoidhelii.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtzuicxgnq.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtimkqadqd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gtqircgzuy.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzhnsqgg.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtynqsjttv.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtjuybpozc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.0kj1m.cn/Article/details/gtipgbjfxj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jianghu66.top/Article/details/gtogijufpa.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gtygoiargu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtjazkslry.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtlplmjzkd.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtfiyyxnfd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyvuvcepw.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtfwwahpqc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gtisrinize.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gtndemaixq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtgipqitvg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtpxeamtjr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtfbgrrmsq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gthhfvpyyc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gtyjnyvncy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gtxtnkvfhw.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gtafpvpkiu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gtvyxljzjj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtfluyijqj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgkuvbwt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtjsccnszd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtfarprrct.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtmyoqakht.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gtwmzybmel.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtemvjgjfx.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gtfyagyxxm.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gtkhvyepop.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtkywdyeev.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtuthtyuca.html


<!-- 参考信息 -->