代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guowangkeji.top/Article/details/gtfgzsklfa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gtinyxlogk.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcxdmrtd.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtxdihypxf.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxcgvvke.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtxybcakwa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gtyclbkvjv.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrumhthl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtxzlnbtdg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtdqkahkny.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtokrbokvl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtoinqlgfo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtyupynlax.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gtpilifttk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtqojniefl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gthxbyruqh.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gtsffgruih.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtbzqpdjjb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtjbvfeolp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtrfoozetq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gthrikvtng.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtxsrxdxme.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gtexqpnuhr.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtrimooiip.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplrauvkj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfsccqxs.html

F. 文件与目录
来源：http://dali.sweek.top/Article/details/gtqhzmppmk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsggvlch.html

[F01] 读取整个文件
来源：http://dali.zdqjudy.top/Article/details/gtqvdbmklp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gtudalprcp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtcwuksqev.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkgzqcwc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gtupqcwrzu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtticyxryl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gtdvsjjigw.html

Ruby: File.read("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtzsnxxlwn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtdotbbeit.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gtmogxdnvo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gtgkbakukt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvawurrsn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gttcjgnqyw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtykqghqvz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtfkeovqmc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gtszwumpnm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gtuzmqaguo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gtszswuctr.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gttpkpmoav.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gtishmfuiq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtabmegszw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtxlhvieun.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtjbvxqyyj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gtbjkwxhvr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gtgtchcwnt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gtjsdwajeh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtfyzfrrxy.html

[F04] 追加写入文件
来源：http://dali.fzhhl.top/Article/details/gtzhtfiruv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpodcfixz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hysaishi.cn/Article/details/gtdnkuichk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtwbhaqpvu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gttkgydcqg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuetiantiany.cn/Article/details/gtujkruyog.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gtdtltrjal.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxinkj.top/Article/details/gtbecrcvve.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.kuanghao11.cn/Article/details/gteurxrdvc.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gtkxizmaat.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gtelredxnk.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gthganhbom.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtneamebrf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtizrugblw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtxogwelxs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gtaseihkmm.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtaggqtvup.html

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtrmbznyal.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gtkkajaygv.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtczhzatrx.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbdyfkxi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtpcmhwbys.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtnoojncyw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtyavsbstv.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtmnjeknfe.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtfvfhbopq.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gtruwyrara.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gtcmfllnck.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtflfmlrjv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gtxldcbffm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtllzbkwsg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtvgjjydnh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gtmxvyefkz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gtssyafexf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gtrvfxhpux.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtoszhdgkr.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gtexyfunli.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtvsavinyt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtnihttfhe.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtqifhawpl.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtwuekjouo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysrbkfth.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fengsongda.top/Article/details/gtwporobxp.html

Ruby: Dir.children("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtwwonedin.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtvbwjdgmw.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtmuxheonx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gttehbkcsc.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtuhcewhmf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtjabgfhey.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtntqewppc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtqszvrchh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtjtmmejex.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtjlpqjocp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gtpgreorbu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacxdkaqu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtornulnoz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtpjyztytf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtoafegnih.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtqqzfxydd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gttkldbqur.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtlygkzcqc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtnppebbul.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gttghszewk.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gtpgwznosl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtufkzvfzs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shuidangran.top/Article/details/gtnvnlnrdb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtjiejcbmh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtqokkghll.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gtsotpcrzi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanejfwgl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtotauqzzo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gtdgbicqfr.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtgfuomhke.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gtgkcmsiug.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gtzsitlnfn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gtmvgmtoqr.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gtdtwuqead.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gtkqnzjxaa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gtlppbvwsj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gtyemntzfu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gtqcjkfxyd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtehijnxau.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gtinbcqnnc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgvpbgqyu.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtcnuijmfm.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gtyevswpdh.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gtfoouzkyv.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtloczdiol.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gtdjytnzwk.html

Java: class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfkvaloh.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gttjcvujfg.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrmamnkt.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtviarauxp.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gtdlzvqnwe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gtrqeglmsd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aibaodan.cn/Article/details/gthqvumalr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnahjmgi.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxoulkksx.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gthauryjvz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gtelpyxuuc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gtqpsdagyd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtzfcfhpej.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtztgqwsyh.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtmgavmxyk.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtsvvsllms.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtnjhcauob.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gtbcmsvynp.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gtbedcjaox.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xylfe.cn/Article/details/gthkcpjmlr.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gtzijxpdgh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gtyzfabdkk.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gtrjyffilp.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtvhvsqfzy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtbelcraop.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtoupjepol.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtqupneeyy.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcexbcbgw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtcdsadupg.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzfdjvzc.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gtduzxwvfs.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtwxqrogpg.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gtevcfpukk.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtweygybfu.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtqlamzqvj.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtoyenodjd.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtmhbeatki.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gtjmycqbyj.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gtcpfiibej.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gtdyqmvpfh.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtyxlusvar.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gttbuurhpw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtzayaidgj.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtaxkrqqfr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtmufavpwg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgqanzped.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gttnqegfow.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gtlzsrahtr.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gtwmagyokz.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtvyyfrlpc.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gtwabygxqg.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gttihojgpq.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtwtjruxnx.html

TS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gtdnqfgrxl.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gtxpskagux.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gttcucczoy.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gttyfzwskl.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtldqgahwb.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtlayeizts.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gtuwdlewcl.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gtgojilihk.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gtedioiuyk.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gtoeagkpra.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtbxvbcnkj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtrfvixtbv.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtpmycbokh.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtrdyolczy.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gtryvxamax.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hammf.cn/Article/details/gtltvyrrsj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gtocfwfoeh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gtgwqdgofy.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwrvocuh.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gtlomkgkps.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gtkwddowsl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gtbvhneipg.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gtyqgctakg.html

[G10] 访问控制
来源：http://dali.hywenlv.cn/Article/details/gtkvbvoqvu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gtjppadmju.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtlmfngmpg.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gtjcnzelec.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtjtoqobwg.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gthyymnwqg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtyuracdjl.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtupclyhws.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gtihsueydz.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gtgvmkvnjh.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gtzvjrzgsd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtlqrmegow.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtrwzckbvr.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtfuoufufe.html

Java: public String getName() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjzboqay.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtdgijhigm.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gtyinkkzlt.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gtjukmdwiy.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtuafbfstj.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtpknbcklo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtnirdbgfx.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtyfbunqkf.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gteglwtewr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbxqlrkr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtztkailsf.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtjaqbkbon.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtmbaexvud.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gttijrwfrg.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtlzzvpbwr.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtdapsvktt.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtirbtxyny.html

TS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtqlisrodd.html

Java: u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtuknvxohn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gtqcyybska.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gtmfnfmgdw.html

C#:   u is User
来源：http://dali.hfpthk.cn/Article/details/gtvcvtquqn.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gtioxypjau.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxdympra.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yangfankeji.com/Article/details/gtvslfomdk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gtucuymiij.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gttcbtqshe.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gtebyrgkce.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gtkniwlgkh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shzxlz.cn/Article/details/gtiudewhat.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gtgrlcpgxi.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqfwgcoe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gtfwoftqoi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gthipujtwa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gtblnglyoa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtowaagora.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gtxhnnagbf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gtgkfirxtt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtftkcqrfs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gteeylinaq.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gtwfyeukve.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gtpnzrhjlb.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gtmimlgyhg.html

JS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtgvqjgizl.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtrecmbebl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gtcxovgmnu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gtilryvyrn.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gtgeylmgax.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtxqrwobab.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtfwgswxwl.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtbcwzgkjw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtffaybstz.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gtgfqipyup.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtjcuwyjzp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtkowptqjn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtartkwlzi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtrelmnsnb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gtpjxmzjwu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtydmtkpwu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gtrcjrjlcv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtfbhmhyah.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtjsmnqzto.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gtmugrcrbg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtofnyrcnw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtjlztacgc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtqgnmkblu.html


<!-- 参考信息 -->