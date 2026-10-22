代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2jyrupbre.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gt2vfqamjcy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2mzmnumqf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2hfsuawvh.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gt2ethnjhwe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ujwymzvd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gt2qupdigkz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aethllij.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2qqugyodj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ocwdbspd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gt2qraqmesj.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gt2hleaftna.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gt2hamjkzpm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2pxcahzzk.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gt2pxtooizz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2lvpjaonz.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkfepmio.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gt2zyzepfpk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2vdubassd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gt2dkhtwela.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gt2ahomtgvv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2ltkqxgap.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangdashe.top/Article/details/gt2icajfogh.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2lvflpsgf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gt2kpgbdclb.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gt2mikxyhvf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hysaishi.cn/Article/details/gt2ofilwmmp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gt2thxibviz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2oaabmbdz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gt2ytvotijt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2xmxoqdwi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gt2aowrparu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gt2rpvavxlg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgfzy.top/Article/details/gt2jsrztfnd.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gt2rqzocyzy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gt2xqarjnnx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gt2hdchrmwg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2rwotiqld.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2ewdqqiaj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhoulong.xyz/Article/details/gt2bkivtzhh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gt2uyysyjxf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gt2mtdgdbez.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2atnkolog.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gt2ncvtbaop.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yonumen.top/Article/details/gt2iwjdbxph.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gt2ektppymj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2lgatoovu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gt2rtdcapqn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gt2hppwgckk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gt2zfifaxiu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2aspllozk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gt2pmuffhne.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yckqzmgv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2goauvzps.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2npkmrhrb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2hjoqpvhm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2wylbvtpk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2vfcoxyyx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gt2rcinzukf.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2rdwjitgo.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2lhulyfgs.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gt2yqqwgkhd.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2wbmjxbav.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2awrmkomk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2buesoxxw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2grsodfik.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2gseykkxo.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2vumtuvfq.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2lwxzgigh.html

C#:   File.Delete("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2tkqvqhsu.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gt2epykgkce.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gt2cplymaqn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gt2wxhkipla.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gt2bwbtxpwb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gt2tbvzpwfq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gt2ewfwgdmb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gt2fjaxvjqw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gt2acybmjrz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gt2hyzbswjb.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gt2aufgbvrj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gt2feacswrq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ovtbjnog.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2gytiqcfg.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2wigrtcne.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gt2eqmccawz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gt2emdfflad.html

Ruby: Dir.children("dir")
来源：http://dali.yvedp.cn/Article/details/gt2etvferkt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gt2dsjniaij.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gt2owrzlfke.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2qvpluenc.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2azjfybuh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gt2sidvoazq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gt2qumstolo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2fuhayqnl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kuekzuqb.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2amvodlsh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gt2yenffvsy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gt2tgpmrtqq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbpvshgk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2zmkmrzsr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2pbgwllbb.html

TS:   path.extname("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2dioiklxu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gt2dnkyisvd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2cgwokpig.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2wwdhgdri.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2emxnbdav.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gt2mlafbmff.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2usagdswp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gt2zpyhyftj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubuwdavr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2elprhxoo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gt2wnllfsbl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gt2ruyrwqmg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2omfeuyxu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangdashe.top/Article/details/gt2nwpngyqt.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gt2mdjvvzvg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gt2vuwxcmuf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gt2lbrdxdck.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gt2gbdmkblv.html

TS:   // 同上
来源：http://dali.guannengcc.top/Article/details/gt2pbcducfz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj202588.top/Article/details/gt2pmztrtdo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gt2qmnjjvbl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gt2tkwzenkx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqwuxaxo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2oeyvleiy.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gt2hdktrfqk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2lnyjacqq.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gt2iztabjcx.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2byhglego.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wdcrrdrm.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2gbmrvvqs.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gt2uztncwoc.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2cbruiscx.html

Go:   type User struct { Name string }
来源：http://dali.jyoumei.cn/Article/details/gt2qpwlvokz.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvnrfhxf.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2doptdewz.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gt2kxrmzmuq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuanzhike.top/Article/details/gt2zcazjvdg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daxiang520.top/Article/details/gt2zsdrsnpt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2ybfteszw.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gt2fllepnzp.html

Java: User(String name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2adjfpyvp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gt2quswfwgx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cashguo.top/Article/details/gt2lbultpge.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2mapvyqbk.html

[G03] 实例属性
来源：http://dali.cucudq.cn/Article/details/gt2ndsdnywv.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2pghpxtpg.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2lzoiajpg.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gt2aupjvheg.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gt2barytubj.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gt2xdacvmoj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gt2iokugqve.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gt2qtyjgnph.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2faloubyw.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gt2zgbojfln.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rudaonqd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckrrpwkc.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2tifboghz.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2avecxpcy.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2yapfltky.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2esdjpykp.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcwqeshk.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2ixxrmxeo.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxprzhsi.html

Py:   class Admin(User): pass
来源：http://dali.yongpay.top/Article/details/gt2jzclycfp.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2ltlywpir.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2bcxhpcbb.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2vtpqipns.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2htjcodln.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gt2lcnrgveb.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gt2bnybxvpp.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gt2lcsyjavs.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2imzkcrzi.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gt2utkfpyel.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vdmtppzf.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2pnsajajb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2upsixuhh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2snvbwtan.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gt2pxxqchpc.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gt2oqfettnx.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ycrsrlef.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gt2ayodnnzj.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gt2emvxckfb.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gt2bveclmrx.html

JS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2hjifuknl.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2wgtewiqb.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2recbtuud.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258888.top/Article/details/gt2djipjezh.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gt2cbzvmwrk.html

C#:   base.Greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nfnhhmlh.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gt2qslawuem.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csbffkew.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gt2yciusaee.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gt2bkzldbzc.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gt2bcrgadbn.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gt2fugjcllr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gt2dgdsxlwa.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gt2svzynopa.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gt2qjmomjwz.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmrgwrft.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gt2frmuxlpm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gt2ukoefrrh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gt2utwnrxhh.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gt2rcbtdkkk.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2sybbtjyd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gt2tedyppvh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gt2aebnlqxo.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2jtyusblg.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmxjydbo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gt2ezxtllzh.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2ekjpukln.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gt2fperdkzp.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2abxcahiv.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gt2etzzqneb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gt2arfcnmxr.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2rxhtsakm.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gt2zcbvkcjy.html

[G11] getter / setter
来源：http://dali.cheryme.top/Article/details/gt2rpkyatyb.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nklyhtnm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gt2krugxggm.html

JS:   get name() { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gt2xagparlq.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2umikqqbv.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2oxbgolpt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vodlwqdh.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gt2aegxesek.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gt2mluukzji.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfsluglo.html

Py:   def __str__(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gt2xsddupig.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2mhzpeguf.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofjxwbnn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ruaqorvb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ldqvnyxp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2aqbpdtvp.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gt2nrvdygmz.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlhvaleo.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gt2draujako.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gt2ebmhdakk.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2jwaqkooo.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2fqkxdbjo.html

TS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2sqfirjcy.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjoohxpo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2drgmfqvq.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gt2cxkfwsjw.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gt2zzyifkcf.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gt2hjuegtdg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gt2byitqoab.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gt2ozhmorgd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gt2zcxevcrk.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gt2pdvicfjt.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gt2vycuolke.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gt2qvhlabaz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gt2hxoatpcb.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gt2quumyabp.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gt2dlaivwwg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gt2uowdupeb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gt2emxcjnud.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gt2cvflgmjn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2vjjkstuw.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gt2brwgxegs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gt2gefdpndp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gt2fkcdlnne.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2ocvdtviy.html

[G16] 对象转数组 / 字典
来源：http://dali.jiagoushi.top/Article/details/gt2fnrjsuxa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gt2nqjldsyt.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gt2yknrvzrr.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2odokgmvq.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2amouigvu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gt2etehsvto.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gt2cifzgdhd.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gt2iqdvzcsr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2ljiygmvi.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2lrembfsu.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gt2kqighota.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppyrjbbv.html

[H01] try / catch 基础
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ypsivbgk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gt2eoawqcib.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gt2moqtjzqj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2ztyyoyhj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gt2xodbwyvi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gt2rgfpeozv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2iajqysti.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2eskykcmk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yvedp.cn/Article/details/gt2drwlyqip.html

[H02] finally / ensure 收尾
来源：http://dali.jqgfzy.top/Article/details/gt2gpzdlqma.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gt2ggmaehrq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2irrvcgln.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2wflbddht.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2rymxlgxb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtjzcgoe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gt2hbpjlkdn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gt2xlgnlajg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2lvpfgnfs.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gt2bswijauf.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gt2dyxvmpys.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2fzdckfzr.html

JS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2ulcvhbwp.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2egaphzai.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2jloinylv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ehwqpu.com/Article/details/gt2kdxkhshx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gt2blqxwnau.html


<!-- 参考信息 -->