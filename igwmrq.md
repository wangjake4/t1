代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aeclicxa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xinyue.icu/Article/details/gt2jmairybg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2xhuimsem.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2jvutioeu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gt2afgkbzsq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gt2sxjdxsgf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gt2tvcbbrmc.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nazujtkv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gt2bcfjlarj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2wfkrvjqh.html

F. 文件与目录
来源：http://dali.ivvv.top/Article/details/gt2ayspfjud.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2eqrfjvcg.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjtzblec.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dianchejie.cn/Article/details/gt2tusjsaod.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2pkvxsmem.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gt2pjmqqgfo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2evmxrpjt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2fqqfycwi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gt2lysnpfvc.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2orjmrczx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2wlljradf.html

[F02] 逐行读取文件
来源：http://dali.daria6918.cn/Article/details/gt2oouqcnis.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gt2hnnvpqqu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gt2zynibbrh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yycgtaiz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2lbvbylal.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2svcobupw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gt2vhbqlgat.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gt2grwwzktx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gt2cohgpyvp.html

[F03] 写入文件（覆盖）
来源：http://dali.zhengqikj.top/Article/details/gt2isikxhts.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zdqjudy.top/Article/details/gt2bwecnyew.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gt2knsdlmxv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2nblvcsjd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2hgzimehk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gt2xtvjoepz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gt2wpxcgimn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gt2cqunutlr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2npdmyply.html

[F04] 追加写入文件
来源：http://dali.sxryk.cn/Article/details/gt2gjjlihih.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddtttexs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gt2fnpzhxfb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2zbiisntt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2itgdatnh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gt2zigwpqrx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2nqyzzpaz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zycfv.cn/Article/details/gt2khdgtpzf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akwgffbd.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2zevfthxt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gt2kzyuoogg.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2pblugorj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2ccsfrnev.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2gxdahsaz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2ucufbmqe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gt2wryyfkhj.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2ztdtyczh.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ecjvhmhq.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gt2wcgtoboa.html

Py:   os.remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2cptofqfo.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2bpdxqwsc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2wjczokfi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2hfapkumy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2fsbaqwlr.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ryvbnfdc.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2zsxufeew.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2yfnwusis.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gt2vzhwtbxq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xszttwqg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gt2xjpbkxfe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2trhrrmag.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gt2qwbfjyba.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gt2qcegpled.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cheryme.top/Article/details/gt2vzebpbvx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gt2fchbbljb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwnbqoee.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gt2njevngko.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yriaxwfe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gt2jkonbgzq.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gt2finlykix.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2ersbjjiq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gt2duawplxo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2rcidziqx.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gt2ngawmiqd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2oumrehll.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kaypzvcq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ttkmdoge.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2lmxdkhba.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gt2wlztdsai.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gt2ynxxflyw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2lozoueig.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gt2tilqkbio.html

Ruby: File.size("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2hquukdgr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cheryme.top/Article/details/gt2dfzqvkkr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhixingplan.top/Article/details/gt2tmzxoxnf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2ghiotsry.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2uwrscahp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2bmduhivz.html

TS:   path.extname("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2gujobkoi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tianlin.xyz/Article/details/gt2tjaalcql.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2cgwezkqt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2abtxwqiz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2iueczsip.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gt2ctkagrpx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2vcrguqlb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gt2joxxiacp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2tybotrpl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qfesobdh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gt2utxafidq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gt2pjzkfxto.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2ngxtlwns.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gt2doztjlle.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gt2sjutrihk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gt2gdpemmkx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fzhhl.top/Article/details/gt2cijatcwx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gt2gbsuaohs.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gt2xkvvhlno.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gt2mabficts.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gt2krqimxch.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfqvavc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daxiang520.top/Article/details/gt2xeknrevh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ayewkisu.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gt2xivcuebl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2tfoynyce.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fljyudtb.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gt2phunzffc.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gt2jgwwfbti.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2lnnorxjd.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqshieqp.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gt2jajpjbeb.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gt2xkcbrqqa.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gt2rdhwszrs.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gt2pdrvyfji.html

[G02] 构造函数
来源：http://dali.jinqigufen.top/Article/details/gt2eqrntspl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zdqjudy.top/Article/details/gt2lvvficyc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gt2nxsgeuaf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2xpwgesuu.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gt2bceeazzw.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2lcrdidmt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gt2kitdlgjg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqvuisj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmghpbbn.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gt2ejeedcuq.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gt2aqawhvkl.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2rwjjfmcv.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2rbhdsvka.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gt2aykfuyfs.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gt2krhoqeno.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gt2bevqjqyz.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gt2vzxttvvq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2ebhhkoyk.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gt2ziztigka.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gt2zkzqxmsm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2gramvluq.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2agdtxyfu.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mjgdjqou.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2ntkstbfi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2skhrkthd.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gt2snozoull.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2qregzdqm.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijekainw.html

Py:   class Admin(User): pass
来源：http://dali.xuanzx.com/Article/details/gt2kxqeplzv.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2vrnpnwui.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2mktutmwf.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2oevapnue.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2gkxntdte.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmcnjdtm.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2qysejtfe.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gt2tzmyhlot.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gt2ildorjwr.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gt2koukicat.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxoaatyt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ognrhesv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uknofghl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2ssccimin.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gt2ynlychzg.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gt2rgtzjexx.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tebeybou.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gt2gyekoijd.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gt2whfoobfe.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gt2klullwuo.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2paklcwcw.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gt2ixsrpktx.html

Java: super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2qvvxlbwo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gt2gtfbjvym.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gt2bffauwta.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gt2udgtyzss.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gt2amlxxyew.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gt2rcgapzra.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gt2jetsgjty.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oskyzmiy.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gt2bpknaewu.html

Java: static void f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dsuapfso.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ydzc1.top/Article/details/gt2qpyixcht.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gt2bfuchpwr.html

C#:   public static void F() {}
来源：http://dali.yueranfly.top/Article/details/gt2zwwtayfz.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gt2polyopsz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gt2cvxnnmxz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gt2jretdxrj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gt2qirhgjuj.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gt2iwjhpbwo.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gt2jysokeyt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gt2bybzibon.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gt2egvsxjki.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgltscqt.html

[G10] 访问控制
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrwpqioo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gt2zbiiqhmq.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2zcrwxmxs.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gt2dohdowdi.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2bkbbobrr.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gt2ulblsmlm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ydzc1.top/Article/details/gt2qyndoffl.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2rjbcknug.html

C#:   public / protected / private / internal
来源：http://dali.hywenlv.cn/Article/details/gt2lmyblfjf.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gt2zwpfgmbg.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgscoumc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2xjruboao.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dyyblpvd.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pkcwpsqi.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2tlvaigut.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2blkcilgb.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gt2xhhbcxxe.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gt2wqoxcdkt.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gt2enhvaetf.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gt2iijpkaxc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2ytbpyhqh.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2jlrhsbff.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ohbpduqf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2oeuyexoh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2hmrfvkho.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gt2rsrqswzn.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gt2pvhxbznk.html

[G13] 判断对象类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgvwwitf.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gubznvit.html

PHP:  $u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2jiskuhbl.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2ffbzjwgi.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2geokldwd.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2zmhrlcjz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gsfdieja.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gt2mzsyzcrm.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gt2xoogyfpu.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gt2emoqzpcr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gt2jjrmxkub.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gt2mozyojlg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gt2aphlybgd.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gt2txkvefty.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gt2gkofupre.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gt2ftlyvtwv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnbyasai.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gt2ahxqwcdj.html

[G15] 枚举
来源：http://dali.sufxvd.cn/Article/details/gt2jrempeqc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gt2hrxfavlm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gt2dtptckgu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gt2qaidobjm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2rwfltcwb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gt2wocjgfse.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zghzvyus.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gt2dpikgvjl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gt2tcrybzni.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gt2zchghokk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gt2qrxazuzl.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gt2omkpbgfg.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2fbpafoxh.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gt2qiffywgo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gt2ayiqdbzw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gt2zqhdlikk.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gt2miysaniq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gt2kpbtbwfh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2dsrbbsbr.html

H. 异常与错误处理
来源：http://dali.hfpthk.cn/Article/details/gt2aczcyhwl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2muxpmnpz.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gt2gjxvjpcn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gt2zgrzprbm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gt2jrtsthtj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2vpbggwzt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gt2ckdmegcf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gt2jqxsgdda.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gt2kmaowtif.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdasqpgs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gt2toeubbah.html

[H02] finally / ensure 收尾
来源：http://dali.jyoumei.cn/Article/details/gt2zkjgfaio.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gt2tzjabqsz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmyvtugp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2bvfvobfd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2lmpdfvvi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2qivladts.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gt2xwqhxhzz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gt2pzjmpxhe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2zueqdiei.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtvtuowk.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gt2euasicdi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2melpbqnw.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2akhzqkuy.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2fjqawrct.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2zfyyxcpa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sweek.top/Article/details/gt2njstkjks.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gt2saohwisi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2znayznuw.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2jwrohuyg.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2uoglnmto.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gt2guipjiuz.html


<!-- 参考信息 -->