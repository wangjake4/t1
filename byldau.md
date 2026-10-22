代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gt2stxqqxyc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2qibtxdyc.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gt2ghyaoiee.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2wkisezgx.html

[F01] 读取整个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rcgxhnif.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gt2ksraagnm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2tyiunztj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gt2uclvmcmr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nwbrower.top/Article/details/gt2dfhcoksy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2pfkvvyyq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gt2ydvfpbpp.html

Ruby: File.read("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2wjoyezot.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2torwrwrr.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gt2fdpkdtta.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gt2qurjsgty.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gt2rhqifrbf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gt2hjcasznl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2gaqkqbgf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gt2ccqcqgzc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uejnbaue.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gt2dbtnvsft.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzgmoara.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gt2fuczcrwu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gt2urfpjknn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gt2gingembl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2vqyswged.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2jiypoqyv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gt2pnltmqyj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gt2cbezonhl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gt2eomqlopo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxzbtbly.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gt2fleshzxp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gt2dlqnlkkz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gt2nfuiwpwz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2ltgamztw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gt2ygykoybh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tianlin.xyz/Article/details/gt2cjbkddij.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2hgywusvm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gt2dfmlwhnc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gt2otzdervz.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2wxufjrze.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gt2isaigtcx.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2cvuroecq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqhgoej.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2hoqcdkyi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2huduwtdu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gt2nrhxputf.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2tzxguvvs.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oonxzfoh.html

[F06] 删除文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwksnzpi.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2cwzvyrje.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2mngeypnm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2bjvwtvkm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2mourlhtk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2stishhyf.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2ldznxbhd.html

Ruby: File.delete("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2jmtsvvvq.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2zmlcukin.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gt2apaftrfc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gljlfevl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gt2bslpxwqp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gt2voqhxabg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gt2ziepdkoy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gt2xdxysagh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2klywawmw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gt2vciagyha.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gt2fhppeuei.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gt2eoeawgfn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ivvv.top/Article/details/gt2ccrheayu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnpwgmde.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gt2ejpnnlho.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2kzmpxmpi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2ysnloemj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2wjtypniq.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtwkoizq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gt2vohwxwmt.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gt2zxqdnqgc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jehkbgij.html

PHP:  filesize("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ioinwtek.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gt2tgyzjrhd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gt2cabhqyfc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2pcowgxlg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gt2wyfnfdkz.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2xdgruwov.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gt2ptqowukg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gt2caonjvcd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2yxakigpp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2zwdospch.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2uycfhpjn.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2brukfxus.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gt2zxyqtqua.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2zbzqrgfq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2cjsrkpuh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2mvtryouy.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzhowil.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2wrwnfpem.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.bjfxy.top/Article/details/gt2gxtaxqcv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2vygucquz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2hqabxlxo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gt2liexncmn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.9152youxi.cn/Article/details/gt2ylendkal.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2sosqsdfe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2funqqojo.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gt2iephipnv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gt2msmwmtlc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnwsgxsf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gt2phbionkr.html

TS:   // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gt2osksbppq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gt2rwsbpkxv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gt2vgtobuqp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gt2gvsorcso.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gt2uidjqqoz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ofovtily.html

G. 面向对象
来源：http://dali.wangdashe.top/Article/details/gt2sejhwdbl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2uupwmeda.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gt2yexgetih.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gt2nchqsycy.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gt2gkpsdjhb.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2eugskkkh.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzyugeia.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2zmfnneij.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gt2yssynwyp.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gt2axuqulqi.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2ccfnmwxf.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2mkeawapb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yezrujha.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daria6918.cn/Article/details/gt2sgsncezf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2tbwjxlsf.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2sztyowwf.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqgkgkms.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gt2epdmiovn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gt2aahvhzpo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnhmiiwg.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gt2cedkuocd.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wukkcevr.html

PHP:  public string $name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppldcjkc.html

JS:   this.name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2uzkiyfyz.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2wnjnqhqa.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gt2cjxgdtxc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gt2fuxbaxdw.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gt2dckfovvb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gt2umcwiwas.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gt2zsanzmyd.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gt2cpfhajps.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyreegu.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2gyejfdyz.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2qvrastll.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wwngdmsl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2nxnlndrl.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2jgyunrmo.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmrltcoy.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gt2bguiogfa.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gt2ijlxtxry.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnsnzmlx.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghugyxqf.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkwrsgxq.html

Java: class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2tlitmqts.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gt2poavvpzz.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zntbzsrk.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gt2zefstdyd.html

[G06] 重写方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihitdmhz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gt2fqpvztih.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2vkvrrlmf.html

JS:   greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2tsjijgko.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2dhdatqex.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2zgumwugw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gt2mvaqeyrd.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gt2slkphtfy.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gt2gplafalz.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gt2gvwmkglr.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdjdldkt.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2quhltdsv.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2vuplavuv.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2qizftlny.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdyxrqcf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gt2nniabepm.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gt2aopamzwh.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gt2fntcupbz.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gt2yhwcsbug.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gt2irqswukn.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpzdipgj.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2rrghjkbg.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gt2lonrsmfu.html

Java: static void f() {}
来源：http://dali.guowangkeji.top/Article/details/gt2vazizalj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gt2tjvnkjff.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gt2sfnamegz.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gt2bpfjisxd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfojiyw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gt2tukcjztb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gt2ynjpvtdi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gt2voxscall.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gt2igpitcir.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gt2jtaikbdn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gt2thqyzcrw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhoulong.xyz/Article/details/gt2iypdiwps.html

C#:   interface IShape { double Area(); }
来源：http://dali.haohaochexian.top/Article/details/gt2lqysnsgz.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gt2joigirlb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gt2eqtmqvci.html

PHP:  public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmhajiyi.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gt2xxxlcafh.html

TS:   public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2nkinjwzw.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gt2mtouateq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gt2wtpovgba.html

Ruby: public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2xttsbrik.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gt2teihryfs.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gt2xytghiaa.html

Py:   @property 与 @x.setter
来源：http://dali.0kj1m.cn/Article/details/gt2fblcquuz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ohlwlcyo.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2skjadubq.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gt2xyqcqwjs.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2cqwjvefg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2quqrquiq.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gt2bqycuhek.html

C#:   public string Name { get; set; }
来源：http://dali.hnqzz.top/Article/details/gt2fmntdhkp.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2wdbobdpe.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2bxrwxeoa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2doflvwou.html

JS:   toString() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xyfzeeso.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2ihshfovf.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2zxreufit.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gt2hesuynnk.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gt2fgsndvrc.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gt2rdtlfmum.html

[G13] 判断对象类型
来源：http://dali.zhoulong.xyz/Article/details/gt2gqlyzbkb.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gt2ryhnsnnh.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2hpafjbzs.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2wypqvlnl.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pltcuiqt.html

Java: u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thbscsoq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gt2xxpzicny.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gt2gjedjprm.html

C#:   u is User
来源：http://dali.zhongyouzk.top/Article/details/gt2azyriicn.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gt2ljrshwpp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gt2tuclytvw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gt2bvrrbxsa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gt2pgrdrsrl.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gt2fajvltnm.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gt2dvuefxva.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gt2wyjltjef.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gt2emnwcgwd.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvmqsaxn.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gt2prxijfwf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2esvydnzq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gt2thqjbgwn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gt2zysitprx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2upzmlscn.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gt2gwjoeskb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gt2wcduvbro.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gt2srzwxxir.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2fqsiikvv.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gt2domhmlcf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gt2jdurzexj.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gt2jocvtpct.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2fnzaidlg.html

TS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2dtzkmpkl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hywenlv.cn/Article/details/gt2lepwzjnj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gt2lurzlply.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxqfsjrg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gt2ghbnezla.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2emxaqmdg.html

H. 异常与错误处理
来源：http://dali.meibo888.top/Article/details/gt2rjnekdju.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ekbutrnd.html

[H01] try / catch 基础
来源：http://dali.hnqzz.top/Article/details/gt2brjkqyxr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gt2ojkpqzkv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gt2kfxhetvq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2rajhufmz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gt2aiedgveg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gt2bpheayer.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgfzy.top/Article/details/gt2pixpfopj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gt2ybebvkmw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xucsvjwx.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gt2zhlpbmrv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yongpay.top/Article/details/gt2vdskwxkh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irnbctkn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2wqlmytnk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mygsetpi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2mrktgwzp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gt2pihzxgoo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gt2wxylvpyy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvdbaaky.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gt2qrdxlnmf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhixingplan.top/Article/details/gt2mfgmponr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2taylvkhl.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2kraxtted.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2ogfxzhsb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2fqkchmhm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrnwsbiq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gt2iqemvdhr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2tagknsai.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gt2vofpgqot.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gt2vqcebsfa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2egsrbfnb.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2hwcizyiy.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gt2smkqtyzz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2yadkjxlq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gt2nkuyfjat.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gt2ucmbzedj.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gt2ivfnyqlo.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gt2cdooaldg.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gt2qktfldpw.html


<!-- 参考信息 -->