代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gtngygwqru.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttgrijfgn.html

F. 文件与目录
来源：http://dali.sysykeji.top/Article/details/gtsfkqiase.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrytksupw.html

[F01] 读取整个文件
来源：http://dali.sysykeji.top/Article/details/gtbdlxbsel.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gtgbrqltva.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtocaehhyn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gtqrtvymln.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtqsgyfwel.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtjykekppp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gtfmrqnbti.html

Ruby: File.read("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtcfyljauo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtlcitgknq.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gtmzzsxwxg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gtpeezenen.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gtzgsiehxa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtghfcfqzr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweljzbig.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gthcjnhdlf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.smart0.xyz/Article/details/gtzrlwujyz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtaolqovry.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gtraemfdsc.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gtndrbdyrt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gtlgcdwkhb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtsunpbjuz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtrknzbbwv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtmmypgsiq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangdashe.top/Article/details/gtjoxxtapt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gtkpwllhcg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gtmuxhpbpx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtbcarouyv.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gttkkhltti.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gtfngttlfy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gteoapfcau.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtywbdhrau.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtkmqqamhh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cashguo.top/Article/details/gtxjvrrwhq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtbrqmidwj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gtmfsqxcmm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gtwzxzkyug.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gtkgaybrey.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gtpvfinafp.html

PHP:  file_exists("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtslhyhjks.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtvjfkjsty.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtvsiajrfe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtiirazbtw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.snrcjt.cn/Article/details/gttvolfhpv.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gttdelfkpb.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtafmarkbo.html

[F06] 删除文件
来源：http://dali.sysykeji.top/Article/details/gtohyaxtqd.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtyulyqxcr.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtybwjiznu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtcikpjyjn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtfweeodgj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtfkwvmfez.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtzicwpjfo.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtrtumvlaz.html

C#:   File.Delete("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtofkmezyx.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gtuslzekpf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gttkvxngrs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gtwyyxopft.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtercwfawe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtpnvykamx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gtzrforthx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfekagwgo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gtrkzfbtnd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtayzhjhmg.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gtcrcwlugq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gtnapzrdyw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtfwiolzxz.html

JS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtqopaymdn.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtsspyavqr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwtrnlsg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gtgwxzifzr.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gtmddovyyv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gttuyrakab.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gtudtqjwdg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gtshutokob.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtdubpxyrd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtbqktiegc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtdxirktkk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtukxkdblj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gthhjlcetr.html

Ruby: File.size("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gttazncfgn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gtqhbwaava.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtaargftsg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtucoqpbpc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtmplughxl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtlzplchjx.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtyjkewvcx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gtslugbzjw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtiyqdaseg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtltahhuyh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtxsqxgefn.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gtcnneyqbr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtvlfmfmtx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sufxvd.cn/Article/details/gterczrwrw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtybpexttk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtkwmkjaud.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtbahojdxj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gtgyaajgjh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtyrfmvmyk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtacfgvuto.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gtwupsdegn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gtrqfioeld.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gtymyjnjqw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gttzpetfov.html

TS:   // 同上
来源：http://dali.daxiang520.top/Article/details/gtsaahhgga.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gtgpzrhwrf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gteocxyawn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gtfkmnuirj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gtdehovcgo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtoorrqulv.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gtorghvlbu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmpqugdsk.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gtqecsbgut.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gtqfjsbpep.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtokieeeyg.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtzalaojtz.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtijnbbnop.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtuuxnnnbp.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gtsbgusgwl.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gtpnffvwtt.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtpnrvoxtm.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gthlbitgtx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtqpkrwklj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gtwvdfgwck.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtnsoajuqr.html

TS:   constructor(public name: string) {}
来源：http://dali.chenzaomai.com/Article/details/gtesgdaywc.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtnfjzscny.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gtnmzhikuf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gtbxzchwai.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gttrmnnaun.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gtzsrxycss.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gtsiohrhee.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtcjhgdkri.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtsnbabtrj.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gtqrqklrnr.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gtjinvoyfn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtmpzznnjc.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtjqanberg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gtjxqrqjku.html

[G04] 定义方法
来源：http://dali.aizwys.cn/Article/details/gtoeykptsp.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtwdtszmpn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrcvkfhiq.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxpvmpang.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtsgrmkblt.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtyjgejuza.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogxxkoiq.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtecqtzegt.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gtuzjoenmw.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyaothmlo.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gtjrdxyzxx.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtdwegzlqv.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtwyjettcn.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtxukiauik.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtshaprejt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gtwtwyikmz.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gtkjrwanta.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gtfwpotxlq.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtghhwtvmy.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtfbrlwntt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtkrwcxvxp.html

JS:   greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtzpifwvlh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtknywbftm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtdhdkpzqr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gtmcrgaxge.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gtxgempjfe.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtlqcbqbzg.html

[G07] 调用父类方法
来源：http://dali.ydzc1.top/Article/details/gtdfuoglan.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gtlpvbkhqe.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gtrkgalyfb.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtvszomujb.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtztdusfak.html

Java: super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtysvajqod.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gtoipcdahy.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtfmfmhqzj.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gtwftvwhhk.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gtuotybfkq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtxflpuzkt.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gtzpvqswtm.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gtqthlegac.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gtjahdvnpq.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gtxuhqxiqc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gtjnsdwnma.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gtptxqdstf.html

C#:   public static void F() {}
来源：http://dali.zhongyouzk.top/Article/details/gthxjlxpgo.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtqyzimjzc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gtltiwvjpm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gtkkrxvwil.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gtdpuelpqe.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gttnjwpgyi.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gtvczmtrie.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtroxrwpoz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtuluuuqvj.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtqnkuddbs.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gttwplqzie.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gtqgaraege.html

PHP:  public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtqliwbklh.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gtxlizrtfk.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtrojorbzo.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gtpprwzpfn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfsukhlg.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtdjfgmwrc.html

C#:   public / protected / private / internal
来源：http://dali.jinqigfzy.top/Article/details/gtrubqptzg.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gthjmcbgst.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtwtqyumtp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxnzzfpi.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtfwnwddfl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyiujnmxp.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtktlwucmv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtuyzlthea.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnqjxilt.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gtqmgewpmj.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtmgwhayxs.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtpmophamb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtbmzvnvmh.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gthtxxfxhn.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gthmgfqvon.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtssqlkdfm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtimslnzqo.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtlaqcstpg.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtdbbuqkds.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gtgbqgoajt.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gtvwsfmzcj.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtfixjxhbp.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtxwwxwozh.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtopjuadxz.html

Java: u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtrohzerbe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gtdimiuvzx.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gtbqffbwqr.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gtyvfozsdf.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gtaqowfxxw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gtxvujyciy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtmuxwdpwo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gtrakmjkph.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gtnlvdtwwt.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtykxzslcf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gtyhguwhuy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gtfpwqzifk.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gtyyakyfhf.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gtqjagcjfy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtkibtdpzq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gtsbnxvmsh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gtaexfvklw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtpvovedmv.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gtmhgnjkql.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gtvophqwne.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gthfkmgrjz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtaulqduih.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtxmhetglp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gtiaymitau.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxinkj.top/Article/details/gtzjxigyoc.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtcefrcmjn.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtqixjyisx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gtzmeanwxu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gtjfytcxwc.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtoxevpozf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtjmvnhthm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjcveauiu.html

H. 异常与错误处理
来源：http://dali.yj20258888.top/Article/details/gtmzmjwjqz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtiixpykoc.html

[H01] try / catch 基础
来源：http://dali.hnqzz.top/Article/details/gthtoegwue.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gtiqjngmvu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gttnmvoyus.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtqsezzmfr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtxcthnijz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gtvgbexhzj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gtedahxwat.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hywenlv.cn/Article/details/gtqyddrund.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenlongwang.top/Article/details/gtemclfrhq.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gteyyxaycq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtpvdfellg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtwyyrrede.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gthvjbjmgf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gttdxcweko.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtzfaazjrf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gtxschwqfd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gtqblzbbxc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtfbxneslp.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gtrzodjpyk.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtrmvocmqg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gthrbnmqav.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtkdiwbujp.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtqrenirwk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtlthupmzi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gtvfbvjhjz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sufxvd.cn/Article/details/gtsexhwggv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtpvnumbge.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gttvdoebqy.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gtvrvifmwj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtlppwishu.html

JS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtpkanxznd.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtkkqhgsze.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gttnihwtrh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gtwpmuktfu.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gttbioumtv.html

C#:   class MyException : Exception {}
来源：http://dali.jlsjyb.cn/Article/details/gtplphprzx.html

[H05] 捕获特定类型
来源：http://dali.chenjidiqi.icu/Article/details/gtsjldzcwg.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gtpubhfrjg.html


<!-- 参考信息 -->