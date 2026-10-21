代发 wailian999

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gtjmwdwaia.html

Ruby: if s.empty?
来源：http://dali.iojbl.cn/Article/details/gtxbabbrng.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gtzahccxet.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gttlhfmcke.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gtfwuflolh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtlbevfnnj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gttasarezu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtsnfwoybv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtvzxmvmqv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gteaavqjjl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtukgkbewa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtclroeuzv.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtvhhmpqiy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hywenlv.cn/Article/details/gtucwldesk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtyqjcmykk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtwkzxzkcm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtmygghabm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtkcbvyjkz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gtehbgdogb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gtnchyifro.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gtccjvpotd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvbvjzykm.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gtfdmjrhfr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtkewlbuxg.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtvjzvndoy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gtcufrxmmy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtsimyofcj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gtgybjftfn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtiwblorew.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfisphuhh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtmeymohqt.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtmymibyxr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gtekdapitw.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gtvmbncqbl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtotypefug.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtgwwpcyvh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtdxunoitw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtflfosxmf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtheynsetf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuanzx.com/Article/details/gtahallhiu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gtgbvuargz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yongpay.top/Article/details/gtcsxsalrb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gtlkymxtrt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gtxpycjggd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtzypquhbe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtemgrokqi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gthnakitfp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gtuzznlqmy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gtqjnzeaig.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjrtuxji.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gtffpetvrr.html

[F04] 追加写入文件
来源：http://dali.jqgfzy.top/Article/details/gttwikhayq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gtikhmokpp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ivvv.top/Article/details/gtvijndijg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdysbfzpb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtqxlhbsna.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtavwrcrzq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtfndfelpn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gttirniecm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gtdprhjqmb.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gtklqohdrc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gtxutxbxbf.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcetibrqo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtgzymvtgt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtjkghzbdx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtqcryktyj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gtkonmpdcy.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtywrcfugc.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtxekaxdsn.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gtqjvepvfy.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtzcpvsiuv.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtjulieyot.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtpwwaedyn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gteisckqbe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvrenkhu.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtisosjokq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtlxtuogyv.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gtxbtksqwj.html

[F07] 创建目录（含多级）
来源：http://dali.yangfankeji.com/Article/details/gtajarfcwv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtoyctrbzw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gogol.net.cn/Article/details/gtbizukvkd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtxsulvjru.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtvidqvxtk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gtfmtdodsu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtletckvbp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtjofibneh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtadptjkic.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gtlfmryhks.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gthhlngzjj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtubulsujh.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtudydouom.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtvuovdqfb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtdqktfstv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gttpomuqhw.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtqvjhmeth.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gttxlbzzqz.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gtglsnjkhf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gttdispyhv.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gtjohsbtwe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtuytnsw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtwudkalpn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtclzvvkva.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gtrnzbhokk.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtmdzoukhs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gtfmqufajx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenjidiqi.icu/Article/details/gttnxkbqrq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtcekeluaf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozsacxgd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtjsgexdho.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtfavghotz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gthbtjpchs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtnjntzoau.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtfungcpur.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtopybapty.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gtpxodmpze.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtpbqlpivq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gtwmfbimeq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtkvlpxhrz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gttartckvc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gtuyuxcbvu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gtbfvbtnqn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtoslwuzsd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gtqpdtqarn.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtrlpphdji.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gttdtetqtb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gtvnqsmmoi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gtanorlviv.html

TS:   // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtqelznmvm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtkxmtlolc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gtrbxkbzme.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gtqbrlbvei.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gteneeilub.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtgynezjgy.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gthfjjoevp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtgxzjcbzz.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gtddchgthj.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gtbuvtjytl.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gthtjoltkl.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtdlmkvdaw.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gtfjtkykil.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gtpaqtbfgv.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gtzxvddfbl.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtupgvechk.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtktfadklm.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gthmykkmiz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gtcltjdwkd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtfavytlwa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtzcsidzbo.html

TS:   constructor(public name: string) {}
来源：http://dali.hammf.cn/Article/details/gttvecfpub.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtofqigwwv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gttwvstamu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gtrszujhab.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gtcnltifob.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gtxmysezkf.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtcnulkyez.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtkivnaray.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gtiypkrkcb.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gtflyecbbm.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtjzlsfhiu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gtlritadjq.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gtnkgkevxu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gtqoldsbce.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gtnaanexrg.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gthirwfqhx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtatdrdtmk.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtoanyhroa.html

TS:   greet(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtmjxkflig.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gtdskyhntg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtugqptptf.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtnwivxklq.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gtgoideczs.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gtxbedukec.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gtcusiesfm.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkdlwocw.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtheyhehjq.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gthylwkrac.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gttulcpgss.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gtmhihfpss.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gtmrzpgzvo.html

C#:   class Admin : User {}
来源：http://dali.kuanghao11.cn/Article/details/gtwzyypsnn.html

[G06] 重写方法
来源：http://dali.hnxiangtu.top/Article/details/gtrpsazpvv.html

Py:   def greet(self): return "admin"
来源：http://dali.meibo888.top/Article/details/gtodwgerhr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtzikrrrqh.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtddghhvfe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtrhruzgho.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtqgkdbuap.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daria6918.cn/Article/details/gtftlmcmjp.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gthtkbwemc.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gteeqmtheq.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gttgkppsgv.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtwkjlqgrz.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gtbrqoiwil.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gttnfudapy.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtwofrgcvm.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtdqhfzsyn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gtprpbzfdr.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gtokstrxmy.html

C#:   base.Greet();
来源：http://dali.xylfe.cn/Article/details/gtpfocccjq.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gtdgmqitfn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gtnlnpijtt.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtnblqqxyr.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtgdrsmpra.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gtjqyqmfrz.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gthhqvjmen.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gtyvzxruah.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gtkygbewzd.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtjgnydezy.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gtmqblfisz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hammf.cn/Article/details/gtmbpdrdbg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gtkbvktxyb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsylfxxey.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtjkzvnfmk.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtnvakully.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gttkzxptxb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gtnvzjfeyd.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtrpmegvqo.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtevdxfqjv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gtfbvomhbi.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtiddcqrqu.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gtrcuntbjj.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtucvfzuir.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gtgqipuwhe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gtmmshgtoz.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtesgmwyyc.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gtoyqzkrjt.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gtbltxrbks.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gtuhcfmurs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtavmrtoxz.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gttafcjkgh.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtegcgxqxf.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtldkzvdcx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtozuspgtp.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gtdnnzwhnv.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcaskwalp.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gtgdgkkrno.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtfgjtwrhk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtvujrdnrl.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtrsypmvkg.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtinrbywgn.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtampljdfj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtcspdexxj.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gtgetdfpzn.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtfsdppsbb.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gtixqqfzlw.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gtlarsemzo.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gthsdizpda.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtwrpnxowv.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtfmdomnyo.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtnqqadbdi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gtipugymib.html

Ruby: u.is_a?(User)
来源：http://dali.mhx1999.top/Article/details/gtsnistbcb.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gtxlqxkpin.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gtmormepgv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gtuoczoxpv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtrvhqgymt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gtqewbqela.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtelftuovv.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnmcwrjvq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyytclpsn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gtwxacpfit.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gtlnctpsot.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gtbxkziixy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavappqjx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyslbmxuo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gttszjpwpz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtelfpefpo.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gtguukhjal.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gtcobhphjt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtdfzcprcm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtcaomvpxb.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gtcmzdzbua.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gtdbcczutz.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtrtynjikt.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtjkrrwwkn.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gttuhattmn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtggniogwu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufzaissy.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gtumxqwpem.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtzunwnotx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgofnvaqj.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gtbdubtssz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjrchyfgf.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gtcxtzijnl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtstoyoaau.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gtoigrdtgh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtnrccxezi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtytljzpta.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjcxolhd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gthsflqxbw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gtcdbogvan.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gtefbfivjv.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gtuolcvoik.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gtcpuajwnz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtnlffkfll.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtxsboygcd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtdnmrabhl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtqedzrfll.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gtrplqwrzn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gtroiccqyf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtewedqnfq.html


<!-- 参考信息 -->