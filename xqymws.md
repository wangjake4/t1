代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gt2egbtyeks.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gt2mkogtybs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nsrskryl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2rppojpid.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfrvhcdq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cashguo.top/Article/details/gt2gqjyxezo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gt2cswpliag.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtjwnurq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gt2fzvvylrm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2qtksijac.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gt2lobtycdj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2iilkzpyl.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2rjvidnkl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gt2smabwfki.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2iijqznhn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gt2mwfxqony.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2nfgpixvy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2lndgokdx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gt2ntgjgngl.html

Ruby: File.read("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2crzbyfev.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2ymzmzveb.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gt2hdxsurre.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gt2gjnqbtyx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gt2rmtrokvy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2pvluwpfr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gt2jwaumbvr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjjswutb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gt2qyvjvelb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sysykeji.top/Article/details/gt2gvczvbgg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gt2pancajdt.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gt2sxkwdtlp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gt2vrfsdszv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2ivrwwfue.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2ujlgprpn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2fawolmtz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gt2lbtoeflz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gt2cxqvgljp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gt2ggfklkgh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2nbyrryie.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gt2norjlilx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gt2tbwdkcnq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gt2ujljrzxz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gt2lglgftxy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2yqzcovkq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gt2elnmlxck.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gt2tgatojjz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gt2dqyxoffj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gt2hptmruzy.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gt2abobrxxx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gt2jsjvomjt.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2royzktuo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2vlvevtbh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2gmmnkqld.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2waglmtlw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gt2eaowipep.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2vfldeeal.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2dsiunkxf.html

[F06] 删除文件
来源：http://dali.zdqjudy.top/Article/details/gt2hwrimnxo.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2nawpnten.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2japgswxu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2zkwgwics.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2wrqmppfl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2twfldrzw.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2berjnyyl.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2qbnxzvac.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2hvxbwkor.html

[F07] 创建目录（含多级）
来源：http://dali.shuidangran.top/Article/details/gt2hmbqfhqi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2gphyzrzg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shuidangran.top/Article/details/gt2nblfmtkh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gt2lkqzxfzu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gt2csrvmmpj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fljebarp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gt2cafdkkfi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gt2lllrpvol.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gt2rvavivxp.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gt2flxwfvwf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gt2wlmwpvyh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gt2ceeeyjdb.html

JS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gt2jrzrjgpk.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gt2qkvsmyea.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gt2nxiciiqt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2qukfuhhs.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gt2nvpktwmt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gt2tfqmgtgb.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gt2bijmsrdr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2agoyigwc.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2cuayybct.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gt2dlabboqn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gt2klpdwvrk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2nvxgphpj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gt2ndkaqdrz.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2mruqjaip.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gt2utovznuj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gt2weqmlyyd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhtskffx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2zoeikxsi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2vvaneels.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2jlfxroyp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gt2lrhxsvpu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2skalgdta.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2pwedtyqc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2cuidjgzk.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gt2bcdhavme.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2zyublhpp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2smrjvwvd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2symjetcx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2fjbjpdvw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gt2fhqeljxl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gt2vttbbqpp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2wujqbeyf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gt2rlucoqyp.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gt2rdksglua.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gt2evfyqlrs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gt2kzrgubag.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gt2soomadml.html

TS:   // 同上
来源：http://dali.shzxlz.cn/Article/details/gt2sezirqjl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gt2ovglihnc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gt2akhjgrtq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gt2mpyybaqn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yueranfly.top/Article/details/gt2oycopsug.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ggkkbili.html

G. 面向对象
来源：http://dali.sxryk.cn/Article/details/gt2chzjqics.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2grtmzubv.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gt2kkmxnlau.html

Py:   class User: pass
来源：http://dali.yuanzhike.top/Article/details/gt2npkutiwx.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2bgufbmmk.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2hkeahfib.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gt2eopmveyz.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2upknsgft.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gt2roseoptw.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gt2urgjjvdu.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gt2zbbhecmi.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gt2rojricta.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gt2qakfgaxd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gt2fwmvadjp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xzhrylnn.html

TS:   constructor(public name: string) {}
来源：http://dali.c1oappe.top/Article/details/gt2nvqahlek.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2bqassuqv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gt2qozfjcuz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nwbrower.top/Article/details/gt2ckqnjnin.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2cwrlhxyt.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gt2tacvisog.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gt2cddzcxsn.html

PHP:  public string $name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2lnsfpbus.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljecrwot.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2ueqgwcwb.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gt2nbrexzgu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gt2usgiekzl.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2ljldffkz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2bcfcswxg.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gt2yzlhmrzx.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2gmwzczli.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xaczkssm.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2lnaeuuvp.html

TS:   greet(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2fsmdikak.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2vybbjkck.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2tkplomyq.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2japexptv.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gt2rcrdgztb.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gt2ezbyvqdg.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gt2xfkqlmhc.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2sydvxvaw.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2zkqmqxzt.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ftrhvdzs.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2hhtdsjpt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gt2gzhxdmnf.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gt2ialwenpl.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2pweutrcr.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gt2cxzkckjs.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gt2fzguhtxe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2epcldhju.html

JS:   greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmwjhjnw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2uzdxowsx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2jrztjktk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gt2wpjrjixm.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gt2sspteifs.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gt2esrpocgy.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gt2cthffmxj.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vydaaorg.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gt2czrvirhp.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2pvyafjpx.html

TS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2rmewibkq.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2zedqqbue.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gt2crtisnpc.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gt2qbqbiwkj.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gt2mejuhzez.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgwgqemd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gt2ahdtclwn.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2vosmsije.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocswpqer.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gt2etmcqnwh.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gt2dyvpookf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gt2ggscuiwg.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbhqtdwd.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gt2cnjqahnp.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2budamqrq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuanzhike.top/Article/details/gt2jtvjvhmi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tianlin.xyz/Article/details/gt2nntysllm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gt2dinjzjbx.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gt2mvosxnub.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dywkngvp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivmmzjfo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2hibpnltg.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gt2vvwjtecw.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gt2theziwbo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gt2hbxcbqbh.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2maeshjlc.html

JS:   #private 字段；其余公开
来源：http://dali.zdqjudy.top/Article/details/gt2hkjkoruv.html

TS:   public / protected / private
来源：http://dali.sweek.top/Article/details/gt2bvgzpwvg.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gt2mvipjeon.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gt2zndyaset.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2bfocmffz.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gt2qxotvelg.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbqfbarq.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2zresukic.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fvqqcbjb.html

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fptkflna.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gt2asszchcq.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2cnxypxcp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2bekfsozj.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gt2zrxlvnly.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gt2pefmplao.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gt2zlzagsiq.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gt2wrlxyiky.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2oxhmemfr.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtgdryms.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2suoumqmw.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2yswsmsoz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2jsyjfkqi.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gt2plydhvev.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gt2mvrlfmyl.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gt2oyflsvla.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gt2nllataco.html

PHP:  $u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndglsowz.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awbpestb.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2pwprwhbn.html

Java: u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2ndflkpqv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gt2yctqsuod.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gt2imusfecy.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2luqfzbwg.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwgcsbxg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gt2eittmnrq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkmfmvwx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gt2mtynpxhz.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gt2ekdddwjc.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gt2bqlxvroy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gt2xwshwsrl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gt2glgmihmo.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gt2dvpmskvz.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gt2yprenwal.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gt2rmtwtamj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krjqbupw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqqxiqv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2kdcqtnpm.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gt2qahtptat.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gt2oqkjsgie.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gt2nlvergoa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2gbkmcwtm.html

[G16] 对象转数组 / 字典
来源：http://dali.vqdsnc.cn/Article/details/gt2utlfbsro.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gt2hawkkyhq.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gt2wrjzvgap.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2eciurejz.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2bigspaxp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zdqjudy.top/Article/details/gt2ssciuivk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gt2cdxqyeup.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gt2ekiukoey.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gt2yygusrww.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2xygdmywe.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gt2kizcubyh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2bwvyzovz.html

[H01] try / catch 基础
来源：http://dali.andypj.xyz/Article/details/gt2abdthfcs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gt2tnymxsqk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gt2dxpszpdc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2hqbmlmju.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gt2xbdvbwsm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gt2ffdjiuqr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gt2buudzhwr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2twvfdidu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tkgetezv.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gt2pnendpux.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gt2sijqpazp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2tymgtiwq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2paalkcyp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2bimcqbay.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2jxixusow.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbagieia.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gt2wcqawdwd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdqdzlud.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gt2tbmftihn.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gt2qmrcjrpj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2oetibnrx.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2yunvtcuy.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2jrtbxbuw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2uecspjbn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tanke756.top/Article/details/gt2fvparbbv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenjidiqi.icu/Article/details/gt2asppojeo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2llsaqbal.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gt2rztvncbw.html

Py:   class MyError(Exception): pass
来源：http://dali.ivvv.top/Article/details/gt2mnevmxzm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gt2edvoxjas.html


<!-- 参考信息 -->