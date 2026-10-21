代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gtbdjdpcoa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gtbcomzeny.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gtawhknmxm.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtmvnpnxgv.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gtxrndqgrg.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gtzzwftqhe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gtmuoftvqw.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gtsnkktveu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtviombmnt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtcvyqxbht.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtcodtzmsf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtavcqdjcq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtysqezhnd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gttnqrihpk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtfvrvqqvn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtvjiuthhg.html

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gtjpddwnhw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.svipenyu.cn/Article/details/gtavlzmxcn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtcqqbaigb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtipdsjbjm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtsepknzat.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtnsrxnrbf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.vqdsnc.cn/Article/details/gtckwhsadk.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gthwhzaenk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.svipenyu.cn/Article/details/gtobadkgfg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrnyqhqmo.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gttsnesawp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtygkckjrw.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtuyrvuzdt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gtuuuoxvog.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gtrovcglct.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gtzcfjljxs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtwlwesjeq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtcfqnfxfr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gticwuaxzy.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtrgawfvtr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtlpfhhrdv.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtwhdeippp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzhqxgjg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yangfankeji.com/Article/details/gtdqokwryh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtvwnhmvtp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtpzjrcqrp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gthhynnsvs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtkxvgeveq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gtuqzqnxcp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gtenzgqxjj.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gtozoiylmo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmkwkand.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gticolanpg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gturmuzvpd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtdtehlusp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gtvhttmpoz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zdqjudy.top/Article/details/gtbnpyopao.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.birdmap.top/Article/details/gtbwprkuzy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtrbeyrcdd.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gtdxrjhjvy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gthrbwgkrc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gtojpshcje.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtarrzlbzn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gtmmivcykx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gtnxahpmzw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtaqvdyrpy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sysykeji.top/Article/details/gtmbkmqlzm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tanke756.top/Article/details/gtecpofskb.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gtskzthvef.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gtwqgmpqkj.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtcgjmdhog.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtyzdidhyv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtjwozxdhg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gttzdwzrhj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gtdeurqapf.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gttcicmowy.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gtcrkrzdug.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gtmowhhwtw.html

Py:   os.remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtypissbgd.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtfxmtojvx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gttvwwkgqc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjgqzqfrv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtkjnjdltu.html

Go:   os.Remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtlkroapxn.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtodlukbjg.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtpnchgvgv.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gtffkepigt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayxkbqjl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258888.top/Article/details/gtvfxqvjcu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtagoiskwa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtyqvbbrsq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuxming.cn/Article/details/gtkksbpkqv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gtdszaxpwe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gtyfllvehl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.iojbl.cn/Article/details/gtbpycwpgl.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gtpysgeghv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gtypctitda.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdekzysw.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtrjnxjofd.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtwekruanu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtdhoucdnh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtvslfvpcg.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtnxdgwfbl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gtulwcnzas.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gtvwntcirl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtfhzvbaeb.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtgdnyqzih.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtnvpinpuj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtzxglzyil.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtsfqxdlfl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yvedp.cn/Article/details/gtnnfyjbnk.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtyozzgxjr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gtcpvhozoz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gtigmfszae.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukgcwuaj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fengsongda.top/Article/details/gttxbkbojy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtavrewpeb.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gthdcvqawh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtxkkaxeyf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtngkzgkha.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtldfnnwxf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtieztqbql.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gtkqazepzy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtavzolhxg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtqzzpszyn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtaajxpuxx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtxlyzpest.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtvlhubcmb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtgvozyfiq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtaodjcaso.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gtsajdwnib.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gtaauhlslo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gtbsonnmap.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gtkrgktfss.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gtglzeaupm.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gthxfvcodo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtrvwcmusx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gtxeyckaxj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gtjwxnhppx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gtpgavrxzz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthobzcmht.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gtnkdrjndv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtgklqcahg.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gtzlqvcggk.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtgbjkqylg.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gtkqnbpfao.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtdaltxqdc.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gtnbdwviqp.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtimnncsly.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gtjzzsbhbp.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtevbxhbiw.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtuovixnjv.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gtrggyxnra.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gtgvhbxxzs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tanke756.top/Article/details/gtneakdfdw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtrmgnxsti.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gtyiupfrdh.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtgjdnusyb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gtrkcbmhve.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gttutirega.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtkshybbrt.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gttbosaxej.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gthczpcbpc.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtezznxiok.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtpxioowam.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtwrfjkuim.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gtowzsbwed.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtbpvulvkw.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gttqdyhalu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gtenzfpzim.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gtugcyrgms.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtzyfwvvkk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtbaqrokke.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtmzxyizlk.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtgodcgotc.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtoszbmocp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtimtzghbu.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtacewudsy.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gtnrinjlyz.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltonpelw.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gtawwsvvxl.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxhfspny.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtltobwvlp.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtrlhfabqf.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtlrusvsww.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gtycfkxmzo.html

Ruby: class Admin < User; end
来源：http://dali.smart0.xyz/Article/details/gtwcwbfpmo.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gttjdckgxw.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtnqhocmng.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gtairgpxin.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtewcxdprj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtettaajch.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtjgvjgmzy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtgrtlvewo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gtqoguzavi.html

Ruby: def greet; "admin"; end
来源：http://dali.cdnleiting.top/Article/details/gtritpaqfn.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtqycduxnr.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtgsmawlsk.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gtoncvptle.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gtxjmoctyl.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtfryoemlp.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtvhndkchs.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtavcppbdg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gtutyeefzl.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtvwyvafun.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtsiixwhtt.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gtinymeltr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gtgsgzaukv.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gtuhtzsbzs.html

JS:   static f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtnmnaxsfg.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gteijdzxnb.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbdkkvel.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gtzxrmyhvi.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gtfppczghg.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtfeqegseq.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gtwdgidwvw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtmzmmprdl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtwxmduugo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gtennlkwpl.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gtjmabouyp.html

Java: interface Shape { double area(); }
来源：http://dali.zycfv.cn/Article/details/gtvsslszxt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gtpszuilmt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gtqbvzagne.html

C#:   interface IShape { double Area(); }
来源：http://dali.fengsongda.top/Article/details/gtkgwiwuyd.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtxepytojj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gttpftbacx.html

PHP:  public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtqpgqxvea.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gtlxsagnnm.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiswtfax.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gtavbsnldr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gtxbetpeog.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtdhsoljoj.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtlwagrhvq.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtascekbuy.html

Py:   @property 与 @x.setter
来源：http://dali.yueranfly.top/Article/details/gtqvmxijoi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtkljsoqoh.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtphhpfsrc.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtdaqzmiwb.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gttsonmsoz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqhhdgwd.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gtycynzzuj.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gtewdurfrk.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtrxfilzkl.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtcqbkgdjt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtejigoflq.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtcmfivnxf.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtekbielzm.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gthpoqowiw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtrwpntpqz.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gtrabcqynl.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gtkxpyzsly.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gtedojveku.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gtmutwtzan.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gttxixdcro.html

JS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtypujpcgv.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtmqpbebds.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtfeptahce.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtcjhhudan.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtawcvmpss.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdenhgiep.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gtdspamekf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gtaphgtxzx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gtftkvzlki.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gtpmgiwauj.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gtfuhgywmd.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthahxzppu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gtdykqlthu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtwpffionb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gtlrmsdoil.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gthieniede.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gtfqvttbey.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gtgfsojebc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gtlntefczh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtvhdcwknu.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gtgkvjvfkk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gtovzhmmum.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daria6918.cn/Article/details/gtjnsxpdbg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtfaauphnm.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gtqtwrehls.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gtlrwnvwyd.html

PHP:  get_object_vars($obj);
来源：http://dali.9152youxi.cn/Article/details/gtzsmxokvn.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gttakrzcaw.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtidqrysog.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtbtqjzwnc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtanrimbqg.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtlaizlnjz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtkdvalmju.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkwtcpffw.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gtqbbspmkt.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygdfqewf.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gtlwbzjrxd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmskctipv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtobipeakp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtyzjuhxkl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtfuxnreai.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsquhlptl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gtvspaxadg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jiagoushi.top/Article/details/gtajrlfhkl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gtdagtcgxe.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gtpfkqxrzk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenzaomai.com/Article/details/gtyyceobnn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtfdytowho.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtimbnsbdf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtobaufeer.html


<!-- 参考信息 -->