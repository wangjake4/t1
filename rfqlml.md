代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtvnkmkpcb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmixizfnb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gtnsveulug.html

Ruby: s.bytesize;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtaybnmvvj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtayxjubol.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbzddymrm.html

F. 文件与目录
来源：http://dali.wangdashe.top/Article/details/gtljqksnoi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtokfianwx.html

[F01] 读取整个文件
来源：http://dali.ehwqpu.com/Article/details/gtdktbzqmv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gtcgpxoguz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gterhrbjqn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gtcucngpfl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtuzumfssr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtauknsear.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gtpmgtufwu.html

Ruby: File.read("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtswzcpmzt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtsryeqtdw.html

[F02] 逐行读取文件
来源：http://dali.zhoulong.xyz/Article/details/gtktpfizll.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gtqxaxpfhi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gtovgtdkot.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtcfqwvhsn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtuoyizyyf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtndzaunph.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtkubnfecr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gtriwhsgko.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrdsszrbc.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazoprqkx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gtnhvtuwfu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtmwzrmxgv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtkkfzrvzc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtqjndrkrc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gtrpbdhfip.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtijsyonqp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtrcfyyrnh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gtkqrxtflu.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gtvugucpad.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtcsfzsdrd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gtzldigikh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtflimegan.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtgjebvkha.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gtbbcadxeb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gtmfbkyiqt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yonumen.top/Article/details/gtwxnlfbww.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gtsofpcubi.html

[F05] 判断文件或目录是否存在
来源：http://dali.316326.xyz/Article/details/gthklbjema.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daria6918.cn/Article/details/gtoptgqalh.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtlijoelyp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtxraseodf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtzvmzwfzq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtoahiwnsx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gthbybcqqp.html

Ruby: File.exist?("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtvactyiny.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gttjfdherw.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gtxrhvmljf.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtftdsuptw.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtbxsgymrh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtaagwvroi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtqxotruro.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtuouqgczo.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtxokqurog.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtybgnlhiu.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtpacftmxa.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gtsjarmsll.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gtwnucelha.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwuwfdqz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtwpiszrxv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtbljwdvlw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gtqpakfcgq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gtplaqbwad.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gtwnqgdcdl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gtoqcuzvxk.html

[F08] 遍历目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbonwkwdk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gtiavqzuuo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtsvhmxxrb.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtaldrwsaq.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtngdpaoao.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtmftiyckp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gtpjyvwjlp.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtzgdbwsra.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258.top/Article/details/gttimfpjsq.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gtvspnremo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gtdfahbapr.html

PHP:  filesize("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtustwwtph.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtuzqmpelo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtobpikbxw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtgvshhwvt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtbppccojb.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtkckrbvbu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gtwbabuhxb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gtjamqulge.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtihlejppj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pycfn.com/Article/details/gtvelimveb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtwstivdfz.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtpnqbfcwt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhengqikj.top/Article/details/gteucehkjr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtxfzfotoa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gttligjkew.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtxpmvreop.html

[F11] 复制与移动文件
来源：http://dali.sysykeji.top/Article/details/gtoocyjxqg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtnwqpqqub.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtaevonigr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtvkkpsatu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwnsxuwt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gthhcpyhcx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflynombh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtwnqfwobd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtohwdfcmq.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtneqlqhgh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gtxxuxvody.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gtbjrvchha.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigfzy.top/Article/details/gtxolnitvl.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gtbcwjgjpj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shangyingyoupin.top/Article/details/gtasqbvavu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gtvmnlxzbp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gtgtojblxs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtqgudjjop.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwhbqwcfc.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvllclpwn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtzsafpezj.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gtalpnrfas.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gtbxjpbgli.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtwvwatorf.html

JS:   class User {}
来源：http://dali.yonumen.top/Article/details/gtbzzmdrgj.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gtfwydsixb.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gtvfwqhhvp.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtwontiwwg.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gtpiwtqsxc.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtyrscnzty.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gtvwxqzpgb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gtknszvgnb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gtxacjexzb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtgwvcjbhy.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gtwgbjnfjn.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtsoobqaav.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gttzfbdspf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtmvctsfgj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtjkrruhkm.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtmnquowea.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gtpnecwdxa.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gthrnhkane.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtzvxjdbqn.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtansaflku.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gtecwevqwb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtoykvivpa.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gtgbqauhed.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtdptljtju.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gtudnqnmcp.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtovxkogff.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdomsdomw.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtwvhmadmc.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtbqhfqzxr.html

Java: String greet() { return name; }
来源：http://dali.havefunace.top/Article/details/gtulhbxyjv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsfoaggt.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtisnufjxy.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gtblcfsuzy.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gttyfnzasi.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gtljutvlvi.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gthfqadglz.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gthprhsfrc.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtuohxofxp.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtkrbrrcga.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gthganvbuu.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gtlcbrlvtl.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gtkyxqydly.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtvvqaynmb.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gtifuksfko.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtmaxyvecr.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtynyinfqg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtbtorbvvm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtughgphyf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhengqikj.top/Article/details/gtujrcuzzd.html

Ruby: def greet; "admin"; end
来源：http://dali.yangfankeji.com/Article/details/gtstfmenms.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtlnnmgrlo.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gtwwnqrvxx.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gtnqyoixqg.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtczfowhms.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtmfbjsqyf.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtvabvqsey.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtyfcgzctv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmaawyaol.html

Ruby: super
来源：http://dali.cqqwz.cn/Article/details/gtbawbiuno.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gtclgnrrtv.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gtgjggxtrt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtgmiueqtg.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypwpncau.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gtdrhrcvli.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gtakjrudwi.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gtnwqwvdqm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gtmqujubzu.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gtceawpyuh.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gtfdghhcmy.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gtxlbkgmxe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtrthuaqso.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtkuvffwqh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.haohaochexian.top/Article/details/gturyewcya.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtugzwysun.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gtfcktajim.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gtwljybqby.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gtfxrgcekj.html

C#:   interface IShape { double Area(); }
来源：http://dali.0kj1m.cn/Article/details/gtnikpinys.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gtgwqacxpg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shuidangran.top/Article/details/gtarewajfu.html

PHP:  public / protected / private
来源：http://dali.316326.xyz/Article/details/gtucuupcvt.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gtdtdslepe.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtchxgpkit.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gtyyiopnip.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gtmgeyqqjj.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtdxhuinmy.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gtxetanlob.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gtqgyleetk.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gtpoqvljhk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtzubhmrlt.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuyuwmhhj.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtegjiapja.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtvxrzdzfx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtkfdnsfob.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gtjzzicmcd.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtbfvrtdck.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtnzltotfg.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtbjtkbumi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtdabhwskw.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtsjwsfavo.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtkuekyeri.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtfrnzhpvt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtzwbrieqg.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtkfpdcmhh.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtbksailui.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gtwbtgqipy.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gttqszyanq.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gtbgsdavgt.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtchnsfoqe.html

TS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfprbsoiw.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtguxxyxcc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtvshkhzix.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gtobhisknb.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtzazeqrji.html

[G14] 数据类 / record
来源：http://dali.0kj1m.cn/Article/details/gthsbhytqv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gtsrnwjeuw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gtnisfsmtq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzskutmll.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gtmmapxunp.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gtoydriijj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gtihnqrxpo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtgeohsqhm.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gtseaitwen.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtjblrvbst.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gtqlywjcgi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gtubjqynpm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fengsongda.top/Article/details/gteivzneks.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtnuezlnwt.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gtoappiimb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gthdvjxune.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtdqxsjsuk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtfctuvojn.html

[G16] 对象转数组 / 字典
来源：http://dali.tanke756.top/Article/details/gtmcbiwbhu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gtamnvkhnm.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gtwkpxnhks.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhomgmfa.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtpjlxpkoj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gtsmjqbvsg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtqbcrvbuk.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gtljoqmsox.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtofphgizr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtsxrcegrx.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gtuhehkihp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbqnasiez.html

[H01] try / catch 基础
来源：http://dali.aizwys.cn/Article/details/gtcwavpypn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gtqqjrooaf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gthdrizugs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtggtaejcc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gttuxvpjfa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtibhenjqq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtojctxzlw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guannengcc.top/Article/details/gttogjnmau.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gtbfamfbuw.html

[H02] finally / ensure 收尾
来源：http://dali.xuanzx.com/Article/details/gtuivkjowx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gtmqulkfit.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtrpcbuzgd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtyllgpqcu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtessusjwj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjtqmzpz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gtqfzeiorp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cqqwz.cn/Article/details/gtqhqbfkre.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkesucyid.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gtbopgtwte.html

Py:   raise ValueError("错误信息")
来源：http://dali.cheryme.top/Article/details/gtjdhllhxp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtkermhdwk.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtqbhdanmz.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtwyeibily.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtiemdjnqe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhengqikj.top/Article/details/gtoajxeqis.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gtoaodfmph.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtismyivpj.html

[H04] 自定义异常类型
来源：http://dali.ydzc1.top/Article/details/gtvibvqubt.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtygmfyxxs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gtjvrpapmc.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtlbnbrcdi.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtzrlflkev.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtnagpmjwr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gtsikltndw.html


<!-- 参考信息 -->