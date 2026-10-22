代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2icelotkk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gt2fgiaiowu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgfzy.top/Article/details/gt2wwmezjtl.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2nsafarzk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkyqbvvt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2laerzssa.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gt2ioqmqydf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ncecqlbp.html

[F01] 读取整个文件
来源：http://dali.c1oappe.top/Article/details/gt2bhlwakct.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gt2hiwsnemv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2qcxjphen.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuxming.cn/Article/details/gt2tjncoaur.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2eymzeduw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2qcospgot.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gt2uxgcvdbf.html

Ruby: File.read("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2covrexmo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2xpauxygg.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gt2iafztihy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwlmnbpz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2blvgyhkf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2kromtyde.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2ykyjqoqm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gt2qjzafihe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gt2albbocby.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gt2nthtandp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gt2vpdiddmt.html

[F03] 写入文件（覆盖）
来源：http://dali.zhengqikj.top/Article/details/gt2cwjqptsl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gt2agdrnnqo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gt2ugzjragn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2omycquqx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2vmgwqhxb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gt2mqzbijxz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gt2gpgthlho.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gt2obbpuqlw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uuvsaeco.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfpshvjz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2dyxbnvhy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gt2qkpozqpq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2gsrpggft.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skhksmvg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gt2ecoilwzi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gt2gemlkjrn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aizwys.cn/Article/details/gt2qhzvlqyh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hongshengwenyu.top/Article/details/gt2plqzclby.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2hhfmjchj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jiagoushi.top/Article/details/gt2kfaledfi.html

PHP:  file_exists("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2abyayfdr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2gqahpttl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2pandnmhs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2wklhevjy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.andypj.xyz/Article/details/gt2burclrlg.html

Ruby: File.exist?("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2ozpdiavr.html

C#:   File.Exists("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2fhzqbyzx.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrukukok.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ibjciyqf.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2lgjxdrgc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ubmftptf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2ccuvqcnq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2rjglgqvw.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2tdgnlham.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2zsztlncy.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2iwmlmuem.html

[F07] 创建目录（含多级）
来源：http://dali.fengsongda.top/Article/details/gt2ggryvlkx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gt2ardifbxt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vnurfwig.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2cskswpxf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gt2fjqlvmhy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gt2vgsrccme.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gt2xpihgtfo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gt2frngibeb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shuidangran.top/Article/details/gt2nlizqoqx.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gt2ezwxbzsk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gt2uzckfjyv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gt2sspiefhl.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gt2gdonbphj.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2tgorwwrd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gt2kxtlfgnn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2vwgrqgbb.html

Ruby: Dir.children("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2mnfjrfxu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2idhzotvr.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gt2trxtirbm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2envfkwly.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2lcnzuhgc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gt2gkoiorrj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gt2jlgxrwkz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2vrcetrwg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gt2whjopmdb.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2kjkbruxf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gt2mhshtatu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gt2atnikoum.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2kqeuwbwm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2vjphobwm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2mvxvhhpp.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2hluuyfcv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gt2ifucmjzt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2pfkuwfms.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2vumkckcp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2islfajze.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gt2ppycnbok.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpfpmsne.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2aasygwqp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2mrqiscbm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2ixkfylyk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2odxpwgyi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gt2loahzmoc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gt2ldhtrnrp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gt2qkfnthsm.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gt2dbksaxsq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gt2korsdukz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aizwys.cn/Article/details/gt2mualfwev.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gt2ohsnbkjh.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gt2mmydffek.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gt2lwegcmqg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gt2vddibgqb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gt2wzakprqa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gt2xmjltvft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pioyidfm.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gt2cluymxpv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2yvuwbgod.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gt2fhrbtmsn.html

Py:   class User: pass
来源：http://dali.yangfankeji.com/Article/details/gt2plufnzkk.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gt2cvppiwix.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2zemmibnc.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijjfcxix.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gt2wsyaekzs.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gt2denntrig.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gt2oaupjfsq.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2xgmlvior.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gt2zmvohhec.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gt2dljsjoih.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hywenlv.cn/Article/details/gt2cpshaouj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2umlocrbm.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbamnruj.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2osetlltj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gt2dksssayc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gt2bilysxcr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2rfdxjxpa.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gt2pxkkwfvn.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gt2znspvain.html

PHP:  public string $name = "x";
来源：http://dali.shuidangran.top/Article/details/gt2ghvsvtyy.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gt2fbeprjem.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2uadbpwyz.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gt2pkdrovrx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gt2oudyoosl.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gt2qkdtgkls.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2eevgahng.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkunnwjg.html

Py:   def greet(self): return self.name
来源：http://dali.birdmap.top/Article/details/gt2pmbbndal.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2mffxieck.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2vltcoyei.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2lslgretq.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2ghnugixq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2kqffoqhg.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2karbaobx.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gt2nkuwzptb.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gt2diftompi.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gt2qvosyxji.html

PHP:  class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2vlgukyfx.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2zlygzwmq.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2nbtjunrc.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2qfdvbzoq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gt2gzmfaqnm.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gt2xqtghywg.html

C#:   class Admin : User {}
来源：http://dali.tian-w.cn/Article/details/gt2sioudgnw.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gt2ogxslypo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mowkojkr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jyvdakyc.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2zsksppgg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2liqcfqrf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2joqvrfvo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gt2mwsvjbfg.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gt2aoexmczu.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iyqcsjyw.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gt2hkfentnf.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gt2znfpiypb.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gt2esqfnbuf.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2iyulhpcu.html

TS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gt2bezkbfai.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2wdrbivkk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gt2ukwzxlhq.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gt2toiokeis.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gt2ipugjxux.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gt2mfwjqbqp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gt2jzheolgu.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gt2hczzbgvb.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gt2xjbnaeih.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gt2gpqyfejo.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2xeeqctmm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ppjwa.cn/Article/details/gt2dtgbffnx.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gt2trmwmrrc.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gt2sidijxsi.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehduczdz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gt2veuhxndi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gt2eafadjhh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gt2ebidxgup.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gt2hyhdbebk.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gt2qqukqkdj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gt2lesdmtfk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2naamzafv.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gt2xtsokebt.html

[G10] 访问控制
来源：http://dali.shzxlz.cn/Article/details/gt2txxfbhdf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gt2apimrpaw.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymyxpepl.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gt2ysfmuutg.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2ylawwhrl.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gt2lmyjmxeb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gt2mmzmhuaf.html

Ruby: public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2fbqpcmwl.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gt2rppbszrr.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohtjwqve.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gt2kxywvcpo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqqgcsz.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygdxuvtw.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gt2oxtpfwfp.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2htcwhzag.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2isujygks.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gt2rzmyhder.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gt2ighfwdsa.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kyxobbun.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvavwuei.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2fwrectlw.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2bcwsjkfp.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2stxxqyrs.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2wexaamvr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2kqrykhkn.html

Ruby: def to_s; @name; end
来源：http://dali.andypj.xyz/Article/details/gt2dhksotwt.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2nkqcvkkl.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gt2vsihrblt.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gt2ihkdpydg.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2ocesynuw.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2rdsviqwc.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2qzioccvk.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2cakmwmpj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gt2xilqskbv.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gt2ovccmslf.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvyhozhp.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gt2naxlvior.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gt2lxflcldv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blkvyims.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdmijcjp.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gt2ceieqeat.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gt2tuajgykk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258888.top/Article/details/gt2qigqasyb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangdashe.top/Article/details/gt2owdfbxzw.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gt2usdkgdrv.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gt2wfszkmmi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gt2tcfgclvg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gt2ziswemmr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gt2zccdixrc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2teglakbq.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gt2uedbywjc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hammf.cn/Article/details/gt2goaeqvtf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gt2idbzceov.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2skrbegyl.html

[G16] 对象转数组 / 字典
来源：http://dali.feifeiyinyue.top/Article/details/gt2yiohfxck.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gt2iwgcqukk.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gt2extodrku.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2eyagjfvw.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2swpdscrh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxverrdr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gt2kpsgecmb.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gt2gurayasx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2iqrlagwq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2pqwegjzc.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gt2muwheveh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2reduaivy.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gt2olpfsarw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gt2hqlsygxy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gt2bjbarory.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2icwalbfg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gt2viwkpcur.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gt2vbvjxcvo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gt2poaoynbt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gt2cefgxadm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qefhaxrm.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gt2wlnrmcgb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gt2eclwcfgh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2hvqrjsog.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2cbchxuzs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2qzdnpkjq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2dhqpgkhn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gt2xjimmxva.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gt2lczqnzsw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2bkwhguec.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gt2tznubizf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elqcyrme.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2iidwhzsm.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2tyqpwvhp.html

TS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2wedkqiiw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2fncfohps.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gt2cdvseztq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gt2pvveiubx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2cubywyak.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gt2ybjhrmru.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gt2xyqsjljo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gt2rhyyywrf.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gt2nsksoqjx.html

TS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gt2jwtexgwa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2jgbgnooc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gt2kmtlyyfc.html


<!-- 参考信息 -->