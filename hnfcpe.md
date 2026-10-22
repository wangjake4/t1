代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gt2gasutjcn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2vlpawlws.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gt2oooatovp.html

Ruby: s.bytesize;  s.length
来源：http://dali.yongpay.top/Article/details/gt2xhoftcxw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgsbawpe.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2wriffqcu.html

F. 文件与目录
来源：http://dali.tian-w.cn/Article/details/gt2lsdjfpqy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2bzudposu.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gt2grplnlvu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gt2bbkksfuu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2lymualqs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gt2nchzllkv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gt2sdbnedvq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2nhwtrzqc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gt2njixursf.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2mjldxbyn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2taducpny.html

[F02] 逐行读取文件
来源：http://dali.9152youxi.cn/Article/details/gt2rqztxipo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.bjfxy.top/Article/details/gt2pcwrmmyv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gt2xrkgpftw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gt2vsmvmnxd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gt2iulzsygp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtwtlpnu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gt2ocpgwdue.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aibaodan.cn/Article/details/gt2ngddudwt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gt2tlndbxdy.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gt2fkxclvtu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gt2gmdhvhrp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gt2khrmhdkh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlupnnov.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2vhcmtyrc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.smart0.xyz/Article/details/gt2jgifjbgy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcuvpkly.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gt2olfufivb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gt2sqpvuhcv.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gt2davalpdm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2ykperdvo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guowangkeji.top/Article/details/gt2qfzftguy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gt2ezsmctnp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2ksfrwtua.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gt2akcoecoz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2htqpvmhr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gt2xphathko.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zskrjbnp.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2nkqvllbx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gt2mzzqsvbw.html

PHP:  file_exists("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2cddwnsoc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2obzwftgz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ynrnktgt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2sydvpdai.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gt2vtkldfbk.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2beyyhdza.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2gctaggll.html

[F06] 删除文件
来源：http://dali.zhengqikj.top/Article/details/gt2eejgtphh.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2gpneizsb.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2ngifeidb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2hvzycinw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2gezyqqhn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2ulkfiuap.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2imjvpeku.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2vfqvtvwf.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2edlgsbem.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gt2ffetznqg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gt2hzgwxryb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2rkyvacqo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gt2zkgyianq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gt2sxilwfyr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gt2cohjknmz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gogol.net.cn/Article/details/gt2pkvxsgql.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gt2bobvbonu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gt2vvwizoef.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gt2qgfjqnit.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gt2medsayrd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gt2scqjouro.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2gdhzbpuo.html

TS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gt2rnqbztly.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gt2gshjcdai.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2fhpwummh.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gt2bwjmyogo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gt2txjbvllh.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gt2jfhmquwu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2cvfueyse.html

PHP:  filesize("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2vfswbzul.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gt2zhprjjpl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gt2nzpvqwam.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmobocsd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gt2mwtljohf.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2ssqrztjy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gt2sbqpndnj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gt2btyveeqr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2rodkkwwr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2fwhbvtvu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2hdypbbdx.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2jykmkjsy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gt2nzyfdqay.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2vfmcprki.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2bohzxyls.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2shiduyuz.html

[F11] 复制与移动文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2xuwyyjjj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2warchicl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2ptntjfwe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2hnudgmrg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhowptty.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gt2fnoudkhi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gt2uqxtddio.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2omskluwr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gt2cgcxurgw.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gt2jepyjrwm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gt2cstqmurg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ubydyiqy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gt2oaumagud.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvbisbhd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gt2jvapdhsw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gt2oaecymtv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gt2nxsagmrb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gt2fbebxlpg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2wymailqv.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gt2zpfqwgih.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2nkmaszgh.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gt2rvdgacca.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gt2tzycchvi.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2emxobmtj.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2vazjnkbo.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gt2kevnojsi.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ouregdwd.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gt2ywtcwyjg.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gt2tispbcab.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjtguavd.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gt2rvpaakhf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ruqllkdz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gt2zeudxdwy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2yqkeuijt.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kddaiivf.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2xkhuhcte.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gt2wzykwwcb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gt2emtyviwv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gt2orrvitrf.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gt2gshzctvp.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gt2tzigdxga.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2zkbjvwkg.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2lledvjne.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2iuvmwqia.html

Java: private String name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nxleyrqg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gt2wtlsohfi.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gt2ysgvnrtb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgfkvrpj.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gt2wqoseybz.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2crwfiwtp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2tgmwcwfk.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vllijruk.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wwbgdbhu.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2xlqklsoc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2rzilspao.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gt2yrlkjxpw.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gt2xtbnphzf.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gt2uggpacvk.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gt2bckzxdos.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2ujzeqrkv.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2wuytrnyi.html

TS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2sopjywdt.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2coumqyaa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gt2jqdztiai.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2boyoweyy.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gt2fndjkffj.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cnpkuchr.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gt2gzkpwbgh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfkzfqdq.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxkjjtnn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2nqvldfap.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2qcfncxwp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gt2esofimih.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gt2fbxqehym.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gt2ucdzgxpk.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gt2tdkykfrm.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gt2purhrlaq.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gt2dsmmyfic.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gt2cpqnchrz.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2nithvqme.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxfnmwct.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gt2xvavjtfk.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gt2idqsymfu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wcoxqkxe.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gt2zbvkidfs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gt2vymahqkw.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gt2epqcjxzs.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2exjwzizo.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gt2xgtskzcu.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2fyskhfqg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gt2jghbofro.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gt2ntkufjbt.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gt2vxrppeaz.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gt2aawargmu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hfpthk.cn/Article/details/gt2tjnrombw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gt2eltlactr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.haohaochexian.top/Article/details/gt2ysllfosg.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gt2trypjyld.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2slnefrff.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gt2qhrzpzkp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxinkj.top/Article/details/gt2yemxdbiu.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gt2uwnyefkt.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gt2faartqqs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gt2bibyqgds.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2wukxcjli.html

JS:   #private 字段；其余公开
来源：http://dali.cdnleiting.top/Article/details/gt2xievqnqf.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2xfaylnom.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gt2drnfdvqs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cqqwz.cn/Article/details/gt2wugfcsku.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2dlytoxqk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rgehnoep.html

[G11] getter / setter
来源：http://dali.meibo888.top/Article/details/gt2ykgckvbt.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gt2cvvfjaeg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2ucwmyowt.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gt2ehkhpqcu.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xfnlajtx.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgybkjyt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2pittstuu.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gt2bmsxozmp.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gt2wbrtupxy.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gt2sdarrsss.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gt2nskaeukx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gt2hvuhtkue.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2isdtfxss.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2dralguvi.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2hlxxtnlx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2chlnvsdt.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gt2paprnqup.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2elqvnqvf.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gt2prdwdfgn.html

Py:   isinstance(u, User)
来源：http://dali.mhx1999.top/Article/details/gt2rpjicxxn.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2ymuigrsd.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2xizimcdk.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2hmthmoma.html

Java: u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvyanfoe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gt2gvzzjmao.html

Ruby: u.is_a?(User)
来源：http://dali.yongpay.top/Article/details/gt2pgsjevwb.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gt2whfsbusl.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gt2vggexuon.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.mhx1999.top/Article/details/gt2iemdgvwz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzyzzqwd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gt2vrdrdrba.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gt2ymponxdg.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gt2ekmzfqlh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gt2bopnmuoh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gt2nyrymybn.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gt2srglrbeo.html

[G15] 枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2gnodxlrs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gt2brzhnnrz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gt2meeiifgl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gt2rpyhjcxv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2amfazytw.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gt2nwvvwkeh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gt2sbxdhkfm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gt2elwhivbl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2mvynodsu.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gt2vxrzwyij.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gt2qkslevcd.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfacedar.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gt2gyfgjusf.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2espjirov.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gt2qmqzpntt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gt2souctjkj.html

Ruby: obj.instance_variables
来源：http://dali.havefunace.top/Article/details/gt2huptgnky.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gt2yuguvstw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2fmghbsff.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gt2wuwrsnqa.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jhmkerhp.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gt2qeqhbqvu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jiagoushi.top/Article/details/gt2pvuwxbnb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gt2amozvjet.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gt2dpoxpjib.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uszfdufi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gt2dmldqfxl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gt2hffjjfip.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gt2heexczug.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.svipenyu.cn/Article/details/gt2ramhqtnx.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gt2nkcrejld.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gt2sdogfzfd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2yfwbpvpj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2rgopkwqb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2ubpnpnju.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2hfqgkogb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gt2oxmxckqn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.redwolf501.top/Article/details/gt2xiziinei.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2kzuuimas.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gt2iaxgtqcx.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gt2idsyqsqy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2qfimiezy.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2pinpatte.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2rjjecolq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2kuztthxi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rftqrwnl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guannengcc.top/Article/details/gt2tbeczfvk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2ghrvwqnq.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gt2vmhyjatn.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2svnkaxfo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtimsizo.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gt2xbvpyfkz.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gt2asbwbhxf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gt2lflgkgjt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gt2jzwcgkqm.html


<!-- 参考信息 -->