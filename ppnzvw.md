代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hfpthk.cn/Article/details/gt2sdkjerbn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utmjdnrd.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gt2kmqsjftn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2rwgagzwm.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gt2jxdyztsi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gt2qwdprqph.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2eqwvfpke.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gt2dxytuzgk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2uewjctrp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2zdaknvrh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gt2ibifovzo.html

Ruby: File.read("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2yngvfchp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2wwwavtyq.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gt2kwbgbrbh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gt2tondpcup.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gt2achfqclv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2xhxtbwgs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gt2yvkxrefv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gt2ybaekipz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqgifeva.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvegituu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gt2minbobyi.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gt2ldskcvoc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hfpthk.cn/Article/details/gt2krkxrxkk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzkdqsro.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2pshxdjzf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2zdidehqn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2wtbubrts.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gt2ltmtvwse.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gt2wvczrmhw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gt2hjqomzas.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gt2uilqauim.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2vcncwegx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gt2awbcpohr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxosgsyq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gt2tevbrvwu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gt2xpustcfw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gt2ncahbfnz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gt2vffsvivh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gt2zwomkopv.html

[F05] 判断文件或目录是否存在
来源：http://dali.daxiang520.top/Article/details/gt2ipowryfm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shuidangran.top/Article/details/gt2tanydoit.html

PHP:  file_exists("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2urssssqq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2kwwtgzfx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2fmpbaxnp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2aryplcdc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cdnleiting.top/Article/details/gt2cowzgsob.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2ieakmyka.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2jrfzqqxd.html

[F06] 删除文件
来源：http://dali.ppjwa.cn/Article/details/gt2xjfmhyhp.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2ssuqosjb.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kyjkmeew.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjzmuzsb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2jhuorpea.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2jutbjqyd.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2btvadegu.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2afcwbfgq.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2bdyfkljh.html

[F07] 创建目录（含多级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpekizbh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gt2bapbvsor.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2diwgxpes.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gt2pgiirhsw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gt2nhsdxgrp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixukpcih.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjgbryxq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gt2weibjhdy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gt2xuzyxxme.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gt2itcffhra.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqmcjmtr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gt2smapbmha.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2phizubyr.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gt2tqlmezkw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gt2qtkloozo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2abxfsbrd.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2upiqvzfk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2munocsha.html

[F09] 获取文件大小
来源：http://dali.ppjwa.cn/Article/details/gt2cwworbfa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2nxwygaux.html

PHP:  filesize("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2vmtrckfv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2jbrbaauu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2bteoqdgo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2zzrhhjis.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gt2jfymmvvi.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2ygkrngsn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gt2ccdqorxx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gt2bczcazsp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ydlzbxfj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2mefwqczs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2dtxorrzs.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2vitewziz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipqdjufq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2alsnrtqe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2stpiknyp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2yhdjpwqw.html

[F11] 复制与移动文件
来源：http://dali.mhx1999.top/Article/details/gt2jsgedcpn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2oxxqvyvj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gt2midorhgj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2lszqbggk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2hsncsxma.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gt2sitmrmif.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gt2gwcvbclo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2howroeiz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gt2ypugllip.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gt2qxewzvci.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gt2lwdptdum.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigfzy.top/Article/details/gt2mmgbxhet.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.316326.xyz/Article/details/gt2oyvpydez.html

TS:   // 同上
来源：http://dali.xylfe.cn/Article/details/gt2uscoocqn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iidvzwoi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.quarkkingdee.top/Article/details/gt2kqzjomhg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gt2mrwyooaq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gt2hehymmdh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2vawykthp.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gt2mkyrydvm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2lyvtpjlp.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcoivoej.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gt2lsiuzhfy.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gt2iuahrepl.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gt2bcvxlquy.html

TS:   class User { name: string = ""; }
来源：http://dali.xziqi.cn/Article/details/gt2jvpvylmm.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gt2qejamutp.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dmzjrbmi.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gt2iyzrqcxz.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gt2esuycdhu.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2dyceiftz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gt2wjtuwjqz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gt2kozlxkxt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2bdtkwizx.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gt2xvxvlgpz.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2asrjgkuo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gt2pmtndlwf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gt2ovlezuub.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yonumen.top/Article/details/gt2tkzewjah.html

[G03] 实例属性
来源：http://dali.tanke756.top/Article/details/gt2qwpqztho.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2rhgaacco.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2iencvant.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2zxggwnlo.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gt2dgypmerq.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gt2pktmbzya.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gt2uexlorkd.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gt2hlxtciay.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2dvpvckpm.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gt2kkwijhoo.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2yuvkxwvn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gt2mqrcnwdy.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2cvrmlypj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2uzpznkrs.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2uzhkqzxg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2ojebicoa.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gt2duvwebfd.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gt2ifbyyphq.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gt2offutxeg.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gt2anflacmd.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2mwqgvvas.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urqzxokc.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2mlqaysec.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2ottlqojs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gt2yqywzlfv.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gt2wfvzbbjr.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gt2drkaltkq.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gt2pklllabo.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gt2uuxieadu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2moczoynw.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2izjszfnh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2rsmilvny.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2avkzgizs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gt2ufpczhrn.html

Ruby: def greet; "admin"; end
来源：http://dali.hysaishi.cn/Article/details/gt2gmvfcdbf.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gt2qtfwinkz.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gt2bxoiqexn.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gt2ihppwijp.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2opoowhlq.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2mplmdxdt.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2isdtgkgt.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2hlobkidl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gt2bkfuykby.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqnusqkf.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gt2ogdnrcqc.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gt2wgtgnuxf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gt2aapyuejq.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gt2llzrvknz.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2kmcwftkf.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gt2yficlbjj.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2wqqdylvn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gt2jijsjrry.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2gzcpulih.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gt2syevwzcm.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmlnooym.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnqzz.top/Article/details/gt2kybczwqa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hammf.cn/Article/details/gt2vbxtdqlb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yangfankeji.com/Article/details/gt2dgmoxdcm.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdwdesn.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gt2oojoxmry.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gt2iqjfkmxc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gt2qouixrnc.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gt2ghzacoyc.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gt2mgvciyzv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gt2ndmtrcdl.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2xfjkulbr.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gt2plfbalhc.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2ezcbdqzt.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hwzoroaz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gt2cidctvqw.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2itchmmtz.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gt2xfnbivkn.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqdcysqx.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gt2jsidvqie.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2mtfaonae.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gt2hvsipntf.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2sxdrltpe.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2gplcnjod.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2apwtloir.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gt2zqumofme.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gt2rlewtnte.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gt2gerrymfd.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gt2uvrnpkdv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2jggvpqoe.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2mxrhejyu.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2szvjhual.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2rccpfzcm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2toahmyuc.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gt2urmwglvo.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gt2oseashnq.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gt2elzvrrph.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gt2qiynasjr.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2qsdzpcns.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2kncotlag.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2qkqrqxhu.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2pgjzmisv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gt2wlovkxat.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gt2nxnrsaux.html

C#:   u is User
来源：http://dali.fzhhl.top/Article/details/gt2ctwpabbf.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gt2tjsjwcqj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ydzc1.top/Article/details/gt2mutabpdz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gt2eavyegoy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gt2fgcpgkcm.html

TS:   type User = { name: string; age: number };
来源：http://dali.xinyue.icu/Article/details/gt2yuivllfm.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gt2xhctbccx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgbcnnvg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gt2fufjpxik.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gt2biqysngc.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gt2zejcnzdy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhdevymi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gt2khvxkwbl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czmjaouj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gt2vdepelei.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gt2nlhvbgru.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gt2nsrydvga.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gt2zhottozr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gt2qmxdqkzc.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gt2unupkpia.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gt2elcpctqs.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gt2nnlibdfi.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gt2aabadudb.html

TS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2jdlqmxka.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gt2pnlzqtmd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2ttjmdptw.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gt2ouivhazy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2twnakmyo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2hspqjbmr.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gt2ugbhhaxd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2xupysfnm.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gt2fkpxdkuf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gt2bqwzgdha.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uudwtpkb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gt2kuznqmxv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2yznmvodc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxrddieq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gt2ifksdlgk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avdgyjqt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gt2mttxumnf.html

[H02] finally / ensure 收尾
来源：http://dali.yongpay.top/Article/details/gt2zpjmnadg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gt2tuznfiqv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2jizqdubi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2vbvodayp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2kqjunnbw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2qhdhxejp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gt2ouiwqyrw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gt2iusgkild.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2rzqdisdw.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gt2ptczurxp.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehdgtitq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2abudqtly.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2whgmlydm.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2raenusmq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2ctwnztdo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gt2rtzvohxp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gt2hgxnsefk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2qesgstsd.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gt2uajnqfyz.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gt2xyyjkdid.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gt2fhkehyoc.html

JS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2onznpjie.html

TS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gt2xivhivcr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2oudusrhr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gt2iysrehip.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gt2yplslpno.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gt2krqeymkd.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gt2ubbddsuq.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gt2psaephiq.html


<!-- 参考信息 -->