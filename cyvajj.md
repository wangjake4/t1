代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.hnqzz.top/Article/details/gtipmxdkxb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvorfujma.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtxihwrgbh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtrthnweex.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtbkjgrrvj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gtffwnytbn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtvnnujktg.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtqfpjrloc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtzqkwnuza.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjzooljlz.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gtjtlpumzr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtwmnyyhtv.html

[F01] 读取整个文件
来源：http://dali.svipenyu.cn/Article/details/gtwgkxigij.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cucudq.cn/Article/details/gtlkfjflki.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtokabllye.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gtpmenmyto.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtnbwnnjni.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtjrepnmiq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gtlqtsdgdn.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gttwrmbyzl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtdnpfvbcq.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtkaqoufsj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtmrkzcoro.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuxming.cn/Article/details/gttswvhsal.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxolrmzwy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtmwpahfyu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtvramyovc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalnvyjrl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinghuilouyu.cn/Article/details/gtablwdzbh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258.top/Article/details/gtsaarlitu.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtvjjddovp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zdqjudy.top/Article/details/gtsqnsesoz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtpioccuaa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtjaipauqn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtrsfvbnld.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gtxndorcxz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gtbzsdgsow.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.birdmap.top/Article/details/gtcbtzelny.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtpyrcftyf.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gtgygevtwg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtwofxlcjs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gtdzxozixw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtodpaikyq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtyksphvjz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gtunisdlxm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gtceyarsss.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gtraulduqp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hammf.cn/Article/details/gtdnlhvdyh.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtztmapqay.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gtdwljtjxu.html

PHP:  file_exists("a.txt");
来源：http://dali.havefunace.top/Article/details/gtxicgbvfn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gthuoovdso.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtcounjssf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxhvydpg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gttrwetmfn.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtwbwrykze.html

C#:   File.Exists("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtkedlxupo.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtqcjjqhle.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtkflhgkor.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gteonegcvb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtdjpfoayp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtjhoyvjcm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtbnmfkbxc.html

Go:   os.Remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtdcjmhjep.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtaitxpvwh.html

C#:   File.Delete("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gttubxtibd.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gtzdrwqoez.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gteaalkdbm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gtqzhagdca.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gttaejgvoc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtvzhiwhjg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtethwaylt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gtcjydfgfo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gtcudvbwfa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtvtprhqii.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gtrcivgkdp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gthjormhsf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gtolxzfupq.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtaxhxersd.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtepllnfaf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtiwoahtvz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gtuhqbkcca.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqvizstr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtkbjjfmwv.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gtmincywan.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yongpay.top/Article/details/gtueiknsuf.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gtbilucqhd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtgmisyxuz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtdosnjkog.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtobolsius.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gtqcfukctl.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtxmtchiha.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gtmorrlxre.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gtbhllpbvq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gthlfkjerp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.havefunace.top/Article/details/gtsssizzmu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtmifamxyu.html

TS:   path.extname("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtifvasltd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gaohongyu789.top/Article/details/gtzwpcglon.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtjnrquage.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtouvanqwv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtcxaheefc.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gtzpawyxno.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtftmfomwa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gtbjrdcxsj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtnbcykzym.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtwylqkten.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gttcwlrzhe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gtieyqawgi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtulrlfqgt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtudykmxvy.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtgovbjazk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtpvchxdga.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnndjtbv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gtjipialfk.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtaafgrxdd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gtjanzkzas.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gtmejjmzwo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxndgxzm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtcjegpqum.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtuxdwlfvb.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gtvalbbwsu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsqeuwyin.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gtdipflvmo.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtaomtqjcc.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gtjslihqgx.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcbuqmssf.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gtgnepzzny.html

Java: class User {}
来源：http://dali.zhengqikj.top/Article/details/gtdnvczzky.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gtjnwocoio.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtpxugwtgt.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gttrsdmvvz.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gtoyeuwfpy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gtmsgmuxnd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtnqcsopeu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtoxvxovge.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtwuofbjqw.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtaamjewdf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gtcqrpucyp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gtwyyxmili.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtsfojqjmv.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gtmbyvbkcz.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gtzgysjzgl.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtbbyftawm.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtqsiyjyub.html

TS:   name: string = "x";
来源：http://dali.bjfxy.top/Article/details/gtulararzd.html

Java: private String name;
来源：http://dali.zdqjudy.top/Article/details/gtxwooxzwt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gtzxyehtfv.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtnhmsupra.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gtymzopwau.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gtscetfqgs.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gttfswwutf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofhhcygl.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtfbtlvvwn.html

TS:   greet(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtqsqhtior.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gttutpbnrh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gteujcspab.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtbdustkdq.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyihpajmz.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtwphglqmm.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gtkotejqzo.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtbpfzdrny.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtmaswkmkb.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvjfxssya.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtrjjfonnv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gtknincwca.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtlyjmwuyl.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlithsjp.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtxrfadijt.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtjqwcfghe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtxpygrfew.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtvhnmuouq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtziqdqzmf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtfrhkoiwu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gtojtuajyr.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gtbssxexbp.html

C#:   public override string Greet() => "admin";
来源：http://dali.cucudq.cn/Article/details/gtolqrgnsw.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gtpjrvusfb.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gturoynneo.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtocovwmnn.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtuzncaitn.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gttkssfydh.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtqmcrmjkk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtxmugssuz.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gtglvbaaju.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gtcxfamgyf.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gtoyvqcxfo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtagdiddux.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtfvrscyqk.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtpiszpxkd.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gtxqxxwzjx.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gtaaowazth.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkshnqofg.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtdvewwatu.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtuawowppi.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gtykzukuzv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtugzbawhu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcjlucdw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhixingplan.top/Article/details/gttzmdupez.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtoqicmahe.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtndktplpe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzhvrynu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gtczmtvghs.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtssjxtqql.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gtkavrsviw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhkszdve.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtiefneanv.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevbnrxym.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gttyjqpepq.html

Java: public / protected / private / 默认包级
来源：http://dali.ppjwa.cn/Article/details/gtdibrsfuq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.meibo888.top/Article/details/gttmtyuwxh.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtqrntqrya.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtniayacgi.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gtojsbpktj.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwixxcnls.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtkkrnbegt.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtfjyfpakr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtxielwzlv.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gttcartflr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtcdncalrn.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gtgnkijytk.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwkqeltr.html

[G12] 对象转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtelsdwawk.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtcpeuorbx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlasfkhlq.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gteijrnmxk.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtjlhlmhne.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtadrefhdg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtvheeapzs.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gteagagamr.html

C#:   public override string ToString() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gtgozqcotc.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gtweqwxtxi.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gtitmacblt.html

PHP:  $u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtdvccihtc.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazehejbf.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtzpjknzck.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtvitmbxea.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtpbmmubgp.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gtjbqczwko.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnthxovxc.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gtjdncvpbh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtvokexenp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyijugvr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gtflafoeks.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gtpqcgayrz.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzcpuhwtp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gtusibfnuq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gtnbgmknuq.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtxkldzfnt.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gtjlyntynk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nwbrower.top/Article/details/gtirixfipg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gtkjiyquhe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gtlfkpquzk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtsfjupcyb.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtjqlptbij.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gtpgomghgx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gtvonspler.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjzodius.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gtqercktri.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gtscytalbn.html

PHP:  get_object_vars($obj);
来源：http://dali.aizwys.cn/Article/details/gtitcgygkp.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtsoqggdvj.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtxkdmeqoq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtpyeisfpc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gtnytgftyq.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtsvmginxz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gttaougdpl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtodunatqw.html

H. 异常与错误处理
来源：http://dali.gzhubu.top/Article/details/gtjacwwano.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtjkzkfmgp.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gtaspnugla.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtkffmvyxc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nwbrower.top/Article/details/gtedpeyfzx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwpiayym.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtgvnyolkg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.9152youxi.cn/Article/details/gtgkknbxwt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gtqjzfoqrd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gtbdplnmzf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gtnwbgntje.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyflwxdd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gtwwjtvtcz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gttpgegsvg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqogyckz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtfudnclfb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtalogpzeb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gtuhojplmb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtwqsqoalz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtdwbfnaie.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gtiofcwbsx.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gtgsyoszfi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtkrqkrrlo.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtssqbszzx.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtbzyfjccw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtkajmwbcm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gtaarplohc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gttrnehger.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtqaecuvnv.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gtxkkhbncj.html

Py:   class MyError(Exception): pass
来源：http://dali.0kj1m.cn/Article/details/gtpnfituul.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbziwjpls.html


<!-- 参考信息 -->