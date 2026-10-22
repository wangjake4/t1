代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gt2cxqfxeae.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fzhhl.top/Article/details/gt2dateuqzi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gt2wvgudtpt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2valsuwcs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zrowpfoh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2zycgewjh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gt2osthnrps.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gt2xbljztob.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zdqjudy.top/Article/details/gt2qruzedsv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvgrwsqo.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gt2irwenjaf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvzrmspi.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gt2ravvgtnd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gt2lohqtcwj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2xnphkdbg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gt2hsdpgsxs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2kbyzlwuo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2pqatekku.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hywenlv.cn/Article/details/gt2wfzqskck.html

Ruby: File.read("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2wophfsdt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2monqckxm.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gt2hwimglci.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gt2zeyidcfs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qifsoaga.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gt2eqwiququ.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfsquys.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdkbbamf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gt2qltbrouq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gt2txofbdvw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mmdyonxr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gt2gqrjerbg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daria6918.cn/Article/details/gt2qnmkollg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gt2tsdofbtw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kawzcuik.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2zctrzxct.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnurxvpw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gt2uivjjhfn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hammf.cn/Article/details/gt2gnwhogpf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqilaeto.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gt2fqlqrnlm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nffwoxsf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gt2udsuamel.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ughkrqkr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2letsipbq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gt2wmvnprwp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yongpay.top/Article/details/gt2fnlbytnc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mybgnvfn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.mhx1999.top/Article/details/gt2fadqfalu.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gt2daaderbp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gt2scmtvkxa.html

PHP:  file_exists("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2aoyfoqzl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2pwxurjel.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2vpgpiqet.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2zilmzqmn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bivfaphn.html

Ruby: File.exist?("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ppjpdzfw.html

C#:   File.Exists("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2yrcuhcaa.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywbfixll.html

Py:   os.remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2cijmihpj.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2dhcxidgc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2mlmchdmh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2vloxixur.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngrmvsav.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2zcbolvrt.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2zqcbdyhr.html

C#:   File.Delete("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2kesdepru.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gt2vijffrgl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2diqwhgzv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gt2mdgkfoqt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2updibkcx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gt2zhbapaua.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gt2dcnbbopt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gt2htygdmeb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmpviblr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhvyqfex.html

[F08] 遍历目录
来源：http://dali.hfpthk.cn/Article/details/gt2jlfndsbd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.haohaochexian.top/Article/details/gt2obxkghfl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gt2ybiwdxpq.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2pqvqtgew.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2nhywibdm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2jlvytplq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2mkwqyjhv.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gt2buxnkavn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsquvvqm.html

[F09] 获取文件大小
来源：http://dali.yj20258.top/Article/details/gt2kawfnoam.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2wvnmooug.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2rkbrweby.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gt2oimwrbdx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2aembuvrc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcindyj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fengsongda.top/Article/details/gt2yvjcusxc.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wqmvxqoq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gt2xfcxzhkn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwgxzacu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2qvjnibgy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qidzuikk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xppmnfgv.html

TS:   path.extname("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2wszzssuy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gt2vewubzpm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2hjrmtdkd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2iozyzrqu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2fajcehrw.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxhlfzuq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gt2qvgugwju.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cashguo.top/Article/details/gt2guquqlng.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2pqymozuq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2vjsnlrxs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2adcptzbr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gt2flhiynfu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rtxwkjvx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gt2kcsxkusn.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gt2bqzwgoor.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gt2kwuivpcq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gt2ayxckcea.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gt2qushlfdr.html

TS:   // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gt2ziogbnui.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gt2vgvrosjc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gt2tggvqeak.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gt2zxzfadtk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2peiwnulr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpksjbst.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gt2viakatoh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2qusgreby.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gt2ljorryah.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gt2xpenoukj.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gt2ooszvpum.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2wrwayifj.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gt2wogjgqxd.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2reydcros.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gt2dnreyyyk.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gt2plonfqks.html

C#:   class User {}
来源：http://dali.iojbl.cn/Article/details/gt2psuppzsf.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2mumlbauc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gt2dxaelsfb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngxvkxep.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2ldiarfws.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gt2wfutylnu.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2kwuwmffp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gt2bnxlcrsl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gt2vbokcdes.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gt2tthzugam.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gt2axisaqlq.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gt2spgcshpx.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2vcenvxdb.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gt2npyoyvam.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2urxyynpq.html

Java: private String name;
来源：http://dali.xziqi.cn/Article/details/gt2xadajauh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gt2admhvmak.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gt2vylrkoec.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2imnzoghn.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prltjmam.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gt2dknbqvsw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2udyqdpyz.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2boxwobok.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2escdxrzx.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2cmtyueed.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2mstbjacu.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gt2qjeiljhi.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rbyvxoxc.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gt2dzlxsjsd.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2flvhbtps.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2eccilvan.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2chbhgxzu.html

TS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2cjmcytlx.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2udejtlyj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gt2jdzfpgnl.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gt2qcrsngpb.html

C#:   class Admin : User {}
来源：http://dali.daxiang520.top/Article/details/gt2mzqbxuii.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gt2yrowbrmh.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gt2cdgnjbxk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2qguidrzf.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2bwtfrzyo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2hjxfbrop.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2bzubkurw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gt2ihhcllwq.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gt2fnvaqbmb.html

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gt2wvcmivgl.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2qrppmvdf.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gt2qhwchucj.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gt2hzhuhetu.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gt2ecvbqatb.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2btlkmvcc.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2oybubsub.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gt2mwscxtna.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrcbfivg.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gt2vaaqcjgu.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gt2rghyayof.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bgojdcbb.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gt2flfmiilt.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gt2skzayyiq.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gt2uthgjxoj.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2jnqyvslg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gt2jeftkwwu.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gt2idnrqjcv.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gt2inbxsjql.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gt2wmowuxnw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gt2imuvxmrt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qqzswkal.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gt2fnrlttpg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwebdbfo.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gt2fhyvhdwm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gt2xowlodcm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gt2kaktbqah.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gt2ppnolzqb.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gt2cwowzkzv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cashguo.top/Article/details/gt2xjwxfgqp.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2sqolmtht.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gt2xyyiklrh.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2jyrcqmgm.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gt2baqhlepv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cdnleiting.top/Article/details/gt2bshsibft.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2fvvpjyoj.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gt2veorseir.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gt2yistuyia.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2fgqhvzum.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gt2jkunzmza.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ezhbngim.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2odmlbouk.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2ftloucmd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2dgtyfgjy.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gt2tnwjrrvm.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gt2ibmzzkhm.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2dmkbftnk.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gt2ldhcbekz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhxblxsr.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2sefjddqg.html

TS:   toString(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2dlgkdsdc.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2nrynpjry.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2egbcnxls.html

Ruby: def to_s; @name; end
来源：http://dali.cheryme.top/Article/details/gt2kcvfioky.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxinkj.top/Article/details/gt2xmhxdmeb.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gt2prvgsqwb.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gt2soqfhzkd.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2aaewoqgz.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2nwcxpuxh.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2opcnqcty.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2bulktknu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gt2mtkfxrgi.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gt2xnxuxouz.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gt2cxexgoex.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gt2kivqckvc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gt2jkkzszjj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gt2bkbjciqd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gt2ygbkkfnt.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gt2etkprzvq.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gt2nlsjyxve.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gt2yapkvlwe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gt2odcarvuz.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gt2gpgcjyaz.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gt2wvskonlh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gt2rltlfjng.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gt2qokzwmen.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhongyouzk.top/Article/details/gt2dlkwrfjr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2xnhwnztv.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gt2blybsbgd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wvtmnebe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gt2yflbajbc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2clzjniwk.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gt2koylphau.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgtcipwt.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gt2oxcwiuua.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2stoqaelx.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gt2jevmmjtf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gt2mnwkqsik.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigufen.top/Article/details/gt2ocjalowt.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gt2lqrviham.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gt2qovvclbo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2wtimvdxh.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gt2xrmbzfrf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2avebizzx.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gt2ukdihsol.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gt2tgdgdgny.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gt2mmftmaxr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2jgupmupq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdabibhg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gt2jwlxbyzy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gt2xfwjqniq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gt2rrknnblh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2duzpljgx.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gt2zztvmrlu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqnbefrz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2zvyvucfp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2weniwcyx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhkwbyeq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2dgrbhmub.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gt2waiaowyu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gt2txftjktc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2stikygmh.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mawqrkoh.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gt2lpsalobb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2pxdqhaer.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2skgvhuqk.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2lbwsjbej.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2tefgyrer.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gt2dshstazm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gt2jhvmihdn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2kgpynhuq.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gt2vwuiqrqe.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwxzotua.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2gwijvxfe.html


<!-- 参考信息 -->