代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtbqogrbnv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gtppqledms.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtmenewinq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtninoryas.html

[E22] 字节长度与字符长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtrigldvgj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gtoksuvdsm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtpamwvaai.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtjogybimt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtmedcsdbs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtoobctomu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gtdzdgxbmk.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258888.top/Article/details/gtxtvyxqrm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.c1oappe.top/Article/details/gtfxqddmmy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtsnpetdnq.html

F. 文件与目录
来源：http://dali.gzhubu.top/Article/details/gtlqsempzx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlopbxlft.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gthjadhwni.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shangyingyoupin.top/Article/details/gtwuxaqhxb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtjxfjcazi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gtgymabkxf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtxnuokden.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtotlcybcc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gtgzctdxrh.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtifpbiuac.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtksviouvj.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtjhmueycc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtvepkordr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jyoumei.cn/Article/details/gtppkgjvto.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtigndvpmb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtqwteakmo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtbdhvovqw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gtfnowdgoa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.smart0.xyz/Article/details/gtewpagywc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gtwezceyny.html

[F03] 写入文件（覆盖）
来源：http://dali.cheryme.top/Article/details/gttrziyhyf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gtfvmplgik.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtpqgeixzz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gttijmwfnz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtqwfjzwln.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtibjxudxy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gtynfhnpuz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtoehqtldy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstmibdkk.html

[F04] 追加写入文件
来源：http://dali.fzhhl.top/Article/details/gtcqkuizwh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtqaejuoww.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtipmlabsj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtxozksjqi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtdsorlath.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gtvvobiquq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtssmxukkr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gtzewwwcmr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gtentatmkt.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdnemklp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cashguo.top/Article/details/gtcvluxsto.html

PHP:  file_exists("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtnxokrwfn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtilnrlosc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtkwvjicnm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtcxcvglol.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gtkknmwedu.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtbxyeyqmf.html

C#:   File.Exists("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtrofmmcmc.html

[F06] 删除文件
来源：http://dali.ehwqpu.com/Article/details/gtpmjtttuy.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtsvmhnmco.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gthicfbepy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtbtxpkjjx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtcizbpopk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrhgjmlq.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtbzpxxmty.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtqujrjltt.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtrmyupsls.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258888.top/Article/details/gtrincntkc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamjvcloe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gtutwdelxa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtvtmjaluf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gtknfmxfwk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gtndipugqk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gtqvjhygoz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gttnookppg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daria6918.cn/Article/details/gtrzeiatmg.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gtlvzrfqxw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gtipxxwvoy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gtdrpzxhwl.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtzikulzmp.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtdqtclwcm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gttfwxusai.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258888.top/Article/details/gtclebdytx.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprkwsaea.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlgadidd.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gtyfshkodq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtoipbxonc.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtyclpjucj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtpfafroec.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gthlivtfmm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtsezrcmnh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhoulong.xyz/Article/details/gtvwfgkibu.html

Ruby: File.size("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtsftsjlmd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gtkfpkkhmo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gtqimzgwnm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtbcxhcpir.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtlrkkjuvx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtgdvumroa.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gthdykcrvy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtgmzgxwrj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtdyudaerf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gteiqsfuhk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtcdezjgps.html

[F11] 复制与移动文件
来源：http://dali.0kj1m.cn/Article/details/gtqgpcmedp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtwdsprqjo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gtsawrucms.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkzigogli.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gttogzndsj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gtteukxhzm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gtbhdujvka.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gthicxmfmo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gtcvjkkaiz.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gtpsduadhf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gthmncellg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtkczuqacm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtryumxaev.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gtpfknveja.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtftfcniuk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gotoacloud.top/Article/details/gtdtdhbmqv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gtvdbakwdk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnybhawi.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtdzeudvsy.html

G. 面向对象
来源：http://dali.cheryme.top/Article/details/gtwbpubehh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttpnqaucv.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gtnrayqqvx.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtmdxjihmj.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gtkglpainh.html

JS:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtpcxlvblq.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gtecvuuhxe.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtujdoxfot.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gtswvzcwgx.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtoxxromvx.html

C#:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtcrwgdwsz.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gtvvwhijuk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gtbofavged.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gtiecxqbzs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtpqsryvid.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gtfolpxysu.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfkyappn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtacagpwtu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbhysfwn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gtudfetmku.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gtkfciuzra.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtzsmcmaxb.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtazeetrxn.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtcsoagtsy.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gtdbehprdg.html

Java: private String name;
来源：http://dali.cucudq.cn/Article/details/gtrfxwsoqy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtgbfowevn.html

Ruby: @name = "x"
来源：http://dali.tanke756.top/Article/details/gtiiuxjjex.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gtpdmeansa.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gtgleuhuvw.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtwgvgyapx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtervverjf.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gteqlqsdww.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtnoppexok.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gttveswfki.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtcghawxwe.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtylkslpov.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtwafsgzqk.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gttajswxwy.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gtpplhhsfs.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtmmrdxxea.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gttyelvvym.html

TS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gthywbsyeu.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtfearatwn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gtyxnqfitr.html

Ruby: class Admin < User; end
来源：http://dali.xinyue.icu/Article/details/gtafwyanrj.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gtdxzfagms.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtaqgcawtr.html

Py:   def greet(self): return "admin"
来源：http://dali.snrcjt.cn/Article/details/gtvoraodyl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtnuvskbtb.html

JS:   greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtshuxshkl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtlacxppdj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtarhvrfsg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtzaydtypy.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gtdkxxucmh.html

C#:   public override string Greet() => "admin";
来源：http://dali.sweek.top/Article/details/gtakidbyoo.html

[G07] 调用父类方法
来源：http://dali.cdnleiting.top/Article/details/gthvhopwhv.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gtynfhoelf.html

PHP:  parent::greet();
来源：http://dali.tianlin.xyz/Article/details/gtrxdignei.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtbecuihyc.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtgivzyucz.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtdaeldqnk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gthpucjbmw.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtlaezyfnr.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gttxtwbcsh.html

[G08] 静态方法与属性
来源：http://dali.gaohongyu789.top/Article/details/gtauotgszp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gtsrtjlyfo.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gtdxzbeyqs.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gtnpmsgbqu.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gtvavqfucd.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gtninmzbhr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtqabhnuwd.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsptjvqw.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtgwoyhrbh.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtfnwhamcz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gtbuhehpxb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpnuaceyw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gttyduhgkn.html

TS:   interface Shape { area(): number; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkzivgjac.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtydicgamn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gtkqtpgttc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gtuehbxanw.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtugklixoh.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gtypnzhism.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cashguo.top/Article/details/gtmcdiuppy.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtdlnujgov.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtivgmemhc.html

TS:   public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtxtvsmyqr.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gtqbtdvabe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gtvsodrhra.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtfypkentr.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gtptsepctq.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtxuvifbex.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gtulpnioib.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjonagmc.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtwcwbwefc.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtfblpzhna.html

Java: public String getName() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtbffumeze.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtcelhypoa.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gtiqyurrrj.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gtnlbxegsj.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsasyxjxr.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gthkwxuzok.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtoyedkuvw.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtmyffiuqc.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtyadvjaeu.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gttaodbwgq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gthvtfmmdo.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtzsqvhoxm.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyalbdmly.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gtaiwewktx.html

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gtaipfjtlx.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtfjwuvwym.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtjpzypsrg.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtjhrypalm.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtcbnfmotp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbazsvwvs.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtbdmajnnl.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gtgurofslx.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gtjpyroajp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtknptnktw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gtpkumlgbm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gtsggpmois.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gtldhdryqi.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gttwifvyqj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gtsrbmjlmc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gttorgfvwa.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtxjnqrybw.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gtkjypapzs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gtdbzgorxu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmvoppny.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ehwqpu.com/Article/details/gtytylaalg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtranwkely.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gtqohawdpp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hywenlv.cn/Article/details/gtxcmivbrv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gtxzgelqpx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtjdkmuorj.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gtdtaehdkm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.birdmap.top/Article/details/gtnrwmtvnb.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gtpfebrlst.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtdqvetrly.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtcdxrhqof.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gtaqwapukb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gtxuibnzkp.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtdxzddkhm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtyqmrcemd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gttaazjfun.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gtsfwmceat.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrxjsuyem.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtmbvudgyj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtajjrceeh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvyioumka.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtjtumskjr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtxjbipdgp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gtrmcyaelf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gteodarmht.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pengpengdd.cyou/Article/details/gtjwxdmczq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtusmsmvjp.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gtwzphdtkg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gtwdaqstjw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtokjyditv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtpisiivuq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtthztvvsu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtuomkwxmq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gtbrncqyra.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gtjhmufleb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtljtfgqtx.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtbyrtmzxx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gttqsumaqe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtakqgvksk.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtwcbvwfgq.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtsexoltil.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtftkukkms.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gttlvslpqi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gtdyeahspu.html


<!-- 参考信息 -->