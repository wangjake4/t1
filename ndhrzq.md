代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gt2llkenurf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gt2jrafomjk.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gt2iwvcbwvm.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acjzoxyv.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzaoruwh.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gt2tnlnfaew.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.andypj.xyz/Article/details/gt2wdvzkecb.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gt2ioddxpuc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gt2bvbmzcaa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2jjwmulba.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2pprtcbxx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2tabhewwg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2wgjzhxpl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jianghu66.top/Article/details/gt2zjylkdnl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2eqgzzltr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2aigqkith.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gt2clqxbjkv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hysaishi.cn/Article/details/gt2cuowugea.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2sphctvtz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gt2jfjejyen.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2xcfoahrd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gt2nusdybxu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gt2acilwxgo.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gt2odlsggfp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gt2tmsoavtj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2qgxlyzbj.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqeqxxns.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2txgfdius.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gt2wnmockif.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gt2nmlfdcka.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2isqtuxid.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gt2fdpgfzao.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gt2ttoswwww.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrauhotj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gt2jjlzvycl.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2uazvigsf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2tztjoden.html

[F02] 逐行读取文件
来源：http://dali.yueranfly.top/Article/details/gt2uhqgvfcr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gt2zgjfwnzo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dianchejie.cn/Article/details/gt2wgiqhchh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gt2fdzncwgy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zyrdvvpi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gt2kykojggn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gt2lcdulmsi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gt2epjugfjt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gt2xusnfktx.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gt2uixsrckq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gt2mxnitylg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cyqudotw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2hvwpratn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2bwcdkngo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gt2uwpifcpc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aizwys.cn/Article/details/gt2sjlacvan.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwgbfxwp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gt2kevjjvar.html

[F04] 追加写入文件
来源：http://dali.aibaodan.cn/Article/details/gt2rdyvgxcw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2zljmrsxc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gt2hyiofyva.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2qnxipbnb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gt2hdojzbio.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gt2sdnzxjcd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2drmvqkhb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gt2eoorsjug.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gt2xzqzgikp.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gt2ecktdzbl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuetiantiany.cn/Article/details/gt2bysvutuw.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2zdaxkarz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2eideyeyh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2svmfhpez.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2nvcuoeln.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gt2fsjcbvbk.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2cflfhwgt.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2bgxjzlcs.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gt2nwuqmuhk.html

Py:   os.remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2rpubookf.html

PHP:  unlink("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2wonhvftu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2koksxmgt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2ytgfszlg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2rpqmmayw.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2cqgehoxj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxeacoi.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2sbcyfjvj.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gt2cotfnmdo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gt2aceywvux.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tboljdeb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gt2ixnyboxm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gt2iaybtuxh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gt2vpkmwlvt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gt2oainznat.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hywenlv.cn/Article/details/gt2ycmbgjbx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ybcxt.top/Article/details/gt2mmyxooht.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gt2kjrfjlln.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gt2arzrmwtd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gt2ndrqxynt.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2clinofif.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2nurppwur.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gt2xzasgurf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2txnkzlku.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gt2dopbpccs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gt2udghcbau.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gt2lohqdhve.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2fdlbgxch.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2wargreag.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gt2wtyjsagd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gt2geopgjeq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2nemkhfia.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.birdmap.top/Article/details/gt2sodbncuh.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2kaegprvi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gt2ugdqfiee.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zaacjmrd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2fbadndcm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2helfdovq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2njqvmjbm.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2qyxcewkn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gt2xvzngmrx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2gkbzrwhz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2srzsabht.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2kigcnwas.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gt2psxgmdnb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2ntqtlrvk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2hzeovgbk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2latrtnay.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yyqswwcc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ppjwa.cn/Article/details/gt2tdjpzdxs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjcresz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2sxfficzc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gt2izqywjuv.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gt2udystrxo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqoplwsm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gt2drnxbyyn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gt2qqlepxzk.html

TS:   // 同上
来源：http://dali.zhongyouzk.top/Article/details/gt2vdduqokg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cucudq.cn/Article/details/gt2wwbkwynz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gt2rwnmfmmj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cucudq.cn/Article/details/gt2ihlmffap.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gt2roanzrhr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2bqvcfjmx.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2btnzuayg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2gqeqzvbf.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gt2troeuvck.html

Py:   class User: pass
来源：http://dali.316326.xyz/Article/details/gt2nduhxich.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2zdzmgmcq.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2gwmatusy.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gt2sdyrojcz.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2esrqwgdu.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gt2fmflruhv.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2rnwweecn.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gt2rahvjnyu.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2hzcoljjv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.vqdsnc.cn/Article/details/gt2aelbrpym.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2xusdcitz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2jybkbkaa.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mewocisk.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2mntazfky.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gt2wynnlmmy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yvedp.cn/Article/details/gt2srmzlaoq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2oitptvyf.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gt2gaksjnkk.html

Py:   self.name = "x"
来源：http://dali.tian-w.cn/Article/details/gt2tbsxphqu.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gt2lfnggcww.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gt2edssbmnr.html

TS:   name: string = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2pmxqjlqh.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gt2fpynxwbd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ayyxuvbi.html

Ruby: @name = "x"
来源：http://dali.cashguo.top/Article/details/gt2jivrpnvl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gt2gcjtrfxf.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gt2yxvadkjg.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2yqbqnsgy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2ikhubnzi.html

JS:   greet() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2zyrfovhi.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2duvwivhk.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2gtgytdxy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2dcoptpht.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gt2qulkihdi.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2uoqnqaqx.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gt2tdklmfzm.html

Py:   class Admin(User): pass
来源：http://dali.yonumen.top/Article/details/gt2cwrdwhfy.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbipvohj.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2eyudcndk.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2xonxybrz.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2dvjlvqup.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gt2owhlbzxc.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2xrkfukto.html

C#:   class Admin : User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zkiqohbz.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gt2zzsvgjwo.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gt2hptjyswy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2nyxplhaj.html

JS:   greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2euuaqzzv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2jmpktgyd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2nptzavpp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hondzmkn.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258888.top/Article/details/gt2xrpgxpgd.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gt2zuqagafu.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gt2xemaxroh.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gt2vcouuaxq.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gt2wkotimlj.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gt2fbghsawx.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2uetyeqda.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2wadeyazz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gt2uwiijzzt.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gt2wnzvsxun.html

C#:   base.Greet();
来源：http://dali.xylfe.cn/Article/details/gt2crudsxky.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gt2kwfkpbpl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gt2cuhbfgcs.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gt2aklzgdno.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gt2hvwbctyd.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gt2yindkdmb.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2wtsqvzsr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gt2aqdpaoni.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gt2xsaitxam.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gt2lvgkrcwm.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhegpxad.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gt2alxkpprw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gt2mrmmplts.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gt2ecjygvcc.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gt2mcsbdvfb.html

Java: interface Shape { double area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kluueozj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gt2goqeletp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gt2rprfpdvy.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gt2oqahgblz.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gt2hxmwjkkm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gt2gfovslrp.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2olpfbmaz.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gt2iletsujl.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2toymnihi.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gt2hwnqmelw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwbzlgvl.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2bxrtaqit.html

C#:   public / protected / private / internal
来源：http://dali.yueranfly.top/Article/details/gt2ojbuzupt.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gt2biwxczjp.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugpfjpyd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzshpnoh.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2vqqzgnff.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gt2ufjqmdge.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pebjbpra.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2rhzhxqlx.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gt2sdsbuxql.html

C#:   public string Name { get; set; }
来源：http://dali.cashguo.top/Article/details/gt2mrmewfxx.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gt2gegmgfnv.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gt2fbgyawwh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zeooskfc.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzmvcpst.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2dhdyewjp.html

Java: @Override public String toString() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2ejtsyqcr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2fepdyant.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2abithatn.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gt2wkaplofh.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gt2tzkyfauf.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gt2wavbvlyi.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2qiaydkrz.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2kvtgdzfr.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvdlkhgi.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2rnqbhpvv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gt2mjgqlcag.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gt2soqfuqeu.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyxfulbh.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snlpqueu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gt2ohndpeid.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gt2hwzskkmb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gt2nvjamsre.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gt2ykxepkdi.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gt2nlzbpvno.html

Go:   type User struct { Name string; Age int }
来源：http://dali.andypj.xyz/Article/details/gt2fibnvrqx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gt2nopnogna.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gt2rsmovjen.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gt2jclepxfe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gt2hajzinww.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gt2qzfypoqp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gt2dmqszghh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytxuuxsl.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gt2pwjleeqz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gt2ofumlngc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gt2fnugdnfz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2plvbbpza.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gt2ogwuefkr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gt2gqvmqdri.html

PHP:  get_object_vars($obj);
来源：http://dali.bjfxy.top/Article/details/gt2uhwxvlkx.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chlaphsj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkgjwct.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcagnljm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gt2ymrnztnd.html

Ruby: obj.instance_variables
来源：http://dali.redwolf501.top/Article/details/gt2odxbjngt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gt2vykekrdx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2csydoead.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2piwpqava.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2mzdwsfjd.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gt2qremqtfr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gt2pfvkmzot.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gt2oqjwrznr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gt2vqqjezov.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2bpgprkcy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gt2wilgekoq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gt2muajivdk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gt2fpvkonlh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pycfn.com/Article/details/gt2jnihfazy.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwcvimqt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gt2qpcydxbr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2vbpsqnll.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2jubxtggd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2fkglsnac.html


<!-- 参考信息 -->