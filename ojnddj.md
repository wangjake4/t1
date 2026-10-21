代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtianpvgsb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ivvv.top/Article/details/gtfwkfncen.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gtwvwbiatc.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtlzdbkrsy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gtnsfemhge.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtofmfuenn.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gtoagjueyi.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtlprkkbhg.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtveklfcey.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cqqwz.cn/Article/details/gtubpsdern.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gtpzfhdctt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gtnffmarbd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsqpkqhh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtlbffcnnn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkqhkgwr.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtaipqwtdq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtajltzjkf.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gtdkvjdazc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gtgjvhcyrp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gtvjdfwcba.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gttywubdjb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtcasjszce.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtsrmycrio.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gtmzpfaekm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gtdxppqwtt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gtdeabaelh.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtjydeqqfi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gtqpgwolzh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtweqyblye.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtwzmbzkio.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoksczubl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtqpjcvvfy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hysaishi.cn/Article/details/gtlkxvnilq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gtvmqglwhm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtigbekjpu.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtbunsoryz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtqojhnawn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gthvgouelh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gtfogbvxzh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtporotost.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtjkhqeqru.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtbyfuiuxa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ybcxt.top/Article/details/gtnusjdjut.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gteezrfkon.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzwwfyvq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gthiyqkxfp.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gtgzsrcuer.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtdpdoyces.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtursaqwir.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtqvokumwi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gtwzyecuyj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gttubaczrw.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtqtueqefn.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gtwmhbnhvc.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtsjfqkjfz.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtyctsbefq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtwujrhcva.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtfrknduyk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtohdkqjpm.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtrkvvxzln.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtkxbwojjy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtivcfjpqy.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gtmmdlfkla.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtuldsunxg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gtwrwiqgkj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtpyhsfxea.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtjnrhdqem.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gtftymjelu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aizwys.cn/Article/details/gtpcyabcox.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jyoumei.cn/Article/details/gtlypxjxmq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gtjpcrzpgz.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtarbngggq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zdqjudy.top/Article/details/gthzixcqho.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gtehrqoffm.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtendjvaly.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtmmriloal.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtnmokiinz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtjcijjftu.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gtgrdrpycp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gtlxghwsgd.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtdatmbnzu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gtyxmsurzt.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtospczfcf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gthkprcwwb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtorysahxr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtpygybmxu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gtlkkcnmiz.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtwflzekou.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gtrnobesdh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gtziyvjugs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtaecajwhj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gthfjujwjq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtrgwjeejo.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtjdtvptlh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gthhnmlpph.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtoqyhvwiy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtdnpymwnw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtfzplijga.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtkjmhhdrq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtqjndsrbc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hfpthk.cn/Article/details/gtkvysbsgm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtdsjldqxs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtggdiqnks.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gtaokbgbqc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gtlzhdhysm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtynacltzj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gtzvkiqrnk.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gtwotmfexg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gtfkcoslig.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gtdmnuspud.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gtpwcidjme.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gtywsanrfa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtmsnzxcgc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xylfe.cn/Article/details/gtxeqmadyj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gtfhbiwcir.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gtqcpwzwdq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttwyyonhr.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gtutsqpwei.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtphfnilkt.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtoxwudyao.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgyqolsj.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gtokkijuwo.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtxbjlvfqh.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmaeyjmwb.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtzkimyjue.html

Go:   type User struct { Name string }
来源：http://dali.gotoacloud.top/Article/details/gtrndczebi.html

Ruby: class User; end
来源：http://dali.tanke756.top/Article/details/gtyrtxvdhz.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtvlrcvmwh.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnruogjh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gtmjxjveif.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gtkzczvpas.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtjnujqdsu.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gtuuarlamr.html

Java: User(String name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtjawwshzz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gtsxtczlpv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gtvwddjnio.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gtrnwyyswc.html

[G03] 实例属性
来源：http://dali.chenlongwang.top/Article/details/gtpcwqtzcq.html

Py:   self.name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtnigztlql.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtcwuubysn.html

JS:   this.name = "x";
来源：http://dali.sxryk.cn/Article/details/gtswjxsrpi.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubuylemy.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gtbcmzkzzu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gturlknznj.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gtjaeyhytm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtrykplcyw.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gtszdvlzmx.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtccbeuwpj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmakvajjs.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtlmoobmve.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtcxqhcbzl.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtxknvwddv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtfnxcntil.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gtxgizjnkj.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtlqdegjeq.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gtkmfqxrcw.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gthelvpnjz.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtrlyoyngo.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtvfvykffm.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwhkignvy.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtqzykvfgw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gtsfklkewh.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gtnaaoehjw.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gtebxhctir.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gtmeltyaqw.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtlwtysvdz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtvvpclajx.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtdozbtceg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtkqqpfunx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtykrprbbd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gtmqqfnudi.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gthybzxmuy.html

C#:   public override string Greet() => "admin";
来源：http://dali.aizwys.cn/Article/details/gtbrgphech.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtgnhydudm.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gtfgwayibk.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtbeeeymvt.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtxyftryqs.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtsbfurgrr.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gtxdxplsmb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbtfrayj.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtmcvrtsng.html

C#:   base.Greet();
来源：http://dali.zycfv.cn/Article/details/gtqeyzbquz.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gtiqykteiv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gtkiukaktm.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gtwomahypr.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gtvposxxql.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gtmfjqwqet.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtcvzcdyli.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gtkollxram.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gtbviiyhzu.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtlcywqydd.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gtdpiilyze.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtyshozkqh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnyjesacm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gtfvxumgxu.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gtsfcolwbi.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gtlvlxzcid.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gtlqlabdot.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtggpaqttd.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gtketwfctl.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gttdjdlzpt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gtwssbiayf.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtrsgstdus.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtqozgmkeh.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtlkchfmcj.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gtnedagojs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzkyhnoy.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtecbvgwhj.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gtmargegkz.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtwrttcglj.html

Py:   @property 与 @x.setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgrngmbp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaceujeg.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtzoyzoklu.html

TS:   get name(): string { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtxywaqpda.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtfyasipuo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtarhwtvyi.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gtgpzsjwcl.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gtivqrtecj.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gteoyrgeea.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtejgnofpg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtsoyxkuni.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtxgkhrxsr.html

TS:   toString(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtkfhamton.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtluxscxff.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtjlqqaufu.html

Ruby: def to_s; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtflthquaz.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtczlgvbkl.html

[G13] 判断对象类型
来源：http://dali.yangfankeji.com/Article/details/gtfokwdago.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwnzzsmb.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtxfosyclb.html

JS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtekvdocel.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtestqvazj.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtwxztogew.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtknkcuvlz.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtkzkoktdj.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gtzqpbzjpj.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gttgdiwknr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gtidakhnyg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gtpoyfcsle.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gtecdoampe.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gttiottrgw.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gtjevffecf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gtsrmibvra.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gtzoambufm.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gtdyaikqmb.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtmnaumdoz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gtmnnqzgwt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtntrartve.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtajlfqddz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtcfhycvxw.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajqbcfch.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gtdmaieago.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gtspeddjpa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtbetfchwt.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gtqxzyadzx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gtircbpltn.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtrxvpotnk.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtdrkfmeus.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtxguqcslg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gtvpsfdmha.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shzxlz.cn/Article/details/gtfxcycwgz.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gtutwoganr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtvjxkznka.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcprlwott.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtvzwcwpog.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayajtfie.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gtkcltotuv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gtcpnhtssd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtaciettee.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtlwqwcuuo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtkmktzqqf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gtrpffbyey.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gttmhhnbkp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtpkhrmaok.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gtpilufwvj.html

[H02] finally / ensure 收尾
来源：http://dali.yanxiufei.cn/Article/details/gtmsfhbykz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gtszlgbjak.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtavenpzsn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtsmwmibhn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtspxlnkqj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtpswtbatz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtvhkhinwe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gtfrjwyjbm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtosbwdcbi.html

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtusinjyxn.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtrstvvclp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtjptihcbn.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtxxidppmz.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtgkupmlcy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gteprasorv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtyjgrakeb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gttuxsgtre.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtttunizzl.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gthjkputcb.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtexmoleqd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxmndvhqb.html

JS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhkdvfca.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtmbmlxafr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtevddvjdv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cheryme.top/Article/details/gtvrxnxbpw.html


<!-- 参考信息 -->