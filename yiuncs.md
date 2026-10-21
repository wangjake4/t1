代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtqifvjyjj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gtlrwlcjwn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtknimhywv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtimneqwep.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gtojwfhhpk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gtkuhcfpwg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtqmxqenlb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtvttrkgss.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtiadwniwk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.meibo888.top/Article/details/gtpknmhdvs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtntsrptjk.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtitjgwepa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.iojbl.cn/Article/details/gtbzlgwwir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtarfkcnxg.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gtkvkshzff.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqmdpxjt.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gtutnugzfn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sufxvd.cn/Article/details/gtwrkksxbi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtzkgkfppj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gtujbrofog.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gttpuijdyq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtucxsszhd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtkgbdbcgu.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtwgiayqrf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtrqkncagd.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gtxsoahlck.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtrtbwegrq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gtutvlpcoz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtngdzxbcc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtxfgyuwqn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtwdaomixo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.iojbl.cn/Article/details/gtiyhsxyyz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gthzxtcopc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gtpdtbpzbl.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gtmrbflnhj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gtevddpvrm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtaacbqphd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtpeamsmar.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtvfmdioxs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hywenlv.cn/Article/details/gtumzkhtja.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gttuczyqvh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.smart0.xyz/Article/details/gtkkrucwfs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtntgpglzs.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gtgbkhonlw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guannengcc.top/Article/details/gtdyclmgjm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxbkyijo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtchsesjev.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtbluvplzp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gtwqmvvzql.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gtmynkdqbf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gtzxgvqqye.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gtbwvyuhcb.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gtcwacspow.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcpbsuem.html

PHP:  file_exists("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtfzuqbzwg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtjuffupex.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtytsdmiyp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtdlstigdi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gtbzirwznr.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gtowagfrof.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtxtlvvmjr.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtgfamlhgy.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtjckxslzs.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtgydohkhd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtnnlvsbtb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtlvnndjdh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtmfjiwwgx.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtrguiybdw.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtjaptwwam.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtikymlehy.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gtlsyxetox.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtaprfxtgp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtymulmlwl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtqgqtbhvf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtkswdefai.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gttrjqadej.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gtjljxqwcm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dianchejie.cn/Article/details/gtrcucnlnb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gtheijuswl.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtcsevtals.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gtnjlysqbn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ivvv.top/Article/details/gtnzlkcyqj.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtircttymz.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtmtqxspny.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtinxngcin.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtyqkhojmu.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gtmlrvwctv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gtemoibkes.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gtwjrpxyza.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtxsllwlyg.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtmzhmwunz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtqrtojkgv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtmqmcbeay.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtplaeutuh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtofevcmxg.html

Ruby: File.size("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxapbgcqi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daria6918.cn/Article/details/gtnxpozutd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gtrmgxrjcn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtdzkowlvw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gttdovctpx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtmunklonr.html

TS:   path.extname("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtuqafrvmr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gtbkkwrbgf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtrvlsriid.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadbekrpe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtngwcwntt.html

[F11] 复制与移动文件
来源：http://dali.0kj1m.cn/Article/details/gtlowquaer.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxrpuvfy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gthqngbsxf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwzwotuw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtizdxwkpi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtcsunsgiz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tian-w.cn/Article/details/gtdprqoiqk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtzgnhxeqh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gthjysttxg.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gttigmxwbn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gtvmanmapu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gtxljjgwzm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gtxzwphurg.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gtekoisshr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtcqaghbau.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gttotenajq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gthsosyupf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtuokwrluv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtuvrbhwiu.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gtpjxbvvrp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtouuvufpg.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gtyyygqcpu.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gtjazgzuid.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gtrtedxbow.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtjtsjbhcq.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gtudnzjhtf.html

Java: class User {}
来源：http://dali.hysaishi.cn/Article/details/gtarpddwgv.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gthprbwtgi.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gtrernvdbb.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtxiwgobmp.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gtnrdwxvcb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtbmprvdqg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gttteytwvq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtqxlugigo.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gtgczmxawx.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtepyspybl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gtanqlqgll.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nwbrower.top/Article/details/gthburgsxv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gtbofsrtof.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtvwdsobue.html

Py:   self.name = "x"
来源：http://dali.havefunace.top/Article/details/gtgxedqhxo.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtdikkzfmn.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtqzbpasgg.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtjgvzhuwz.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gtsbrfrigy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gtohudrdnk.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gtxrvudcau.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtqzhifzba.html

[G04] 定义方法
来源：http://dali.nanxinkj.top/Article/details/gtuksnzuuu.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtjgmouzma.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gthzozzuey.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmdgpkzuk.html

TS:   greet(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtehfoeguh.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtofujrhgc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtdifrblpr.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gtikhpoecx.html

C#:   public string Greet() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddeutoph.html

[G05] 继承
来源：http://dali.yj20258.top/Article/details/gtfiejihqs.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtpbclpbkb.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtlkhykgau.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtfyaqeozd.html

TS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtdwkehifn.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gthhviauuv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gtialsmiyf.html

Ruby: class Admin < User; end
来源：http://dali.shuidangran.top/Article/details/gtwljybnfb.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gtykmdehmz.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtkjmqspsp.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gtmrptutdi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtzbcejrgv.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtroufhsam.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtmzjykndd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gthvnknfpb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gttfxnnqro.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gthdgqbrxl.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gtuhdqhdpt.html

[G07] 调用父类方法
来源：http://dali.sweek.top/Article/details/gtwugqbvvm.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtyxlabxlg.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtikhcoolw.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtdwzfuvtj.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtubmtjhrb.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtxdbedsmj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gtsxiexdgx.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtukzrnboh.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtbwrmhuiy.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjtugthu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gtcgqdrwkm.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gtubrzettj.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gtchuaxnfv.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gtsbmqqyvp.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtvwegqgge.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gtxdzhvjpx.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgsflrnn.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gtpfsyczvu.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gtxdupjmvi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gtfktvuyit.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gtqcukdnog.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gtzyawsmoj.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtgzgdzyik.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gtyniepseq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gtfstettbk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gtrtgygakn.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gtczprvfzu.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gteebotrdc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxuuzyng.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtgxahwzlw.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gtvyulvnqx.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtjrknquwd.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gtpscvveuj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gtyfwqozwd.html

Ruby: public / protected / private
来源：http://dali.pycfn.com/Article/details/gtnojimwcv.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gtexprizwx.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gtpoxmkhoa.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gttjejhkrf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtnvayshqm.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtyfufxrsk.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtthhsxnvw.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtrdjdnntj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtcruankka.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtlvmmzzlm.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtfeerdrqa.html

[G12] 对象转字符串
来源：http://dali.9152youxi.cn/Article/details/gtdajgklsx.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtidhjpnuo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtugfpxemn.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtdizjqdot.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtnkjtkvth.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvubaxihs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtvgfbxxzs.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtwubljfow.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtctpwends.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtcvjaqywn.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gtozqvdffk.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gtfvdhuhia.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtclrjsetr.html

TS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtwypefkhe.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtqtlwrgyr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gtjzgyxscp.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtoseshgoa.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gtkheptjwb.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gtqdwxmqiz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gtyruabokb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gtolffyrxn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekpvdotv.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gtpmomawnm.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkambcwtp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gtwkadjkec.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gtrzndobhp.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gtcsuryxap.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gtgnivevxk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gtcloibffg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtnewjtfhz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gtalcgxzhp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtahxavmtc.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gtkkyjhdef.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhxboapc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shangyingyoupin.top/Article/details/gtfqqykzuf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtaxadacfo.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyfpprbv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtfrznrfdp.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gtaybapvvh.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtwevjmikt.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gteoollltk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gtbrxwtzhj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gtqhpdymjm.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gtzwlovvjq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gthlyzebmn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtybbttthm.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gtwzkdpcvn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtneksvxve.html

[H01] try / catch 基础
来源：http://dali.jinqigufen.top/Article/details/gtyxecfpak.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gtakpmvork.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtftnicccf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtdseaiazf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtbowxzjeq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gtqirkjvad.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gtzsehfqnv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtkjzxuadx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gtanqcyrof.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gtrzlidqlg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gtzwexerrn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gttkqbihon.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtjcnkjejw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtjbosrcfx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtkkocnimg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutlnbyig.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.redwolf501.top/Article/details/gtfuivusjn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gticucbyki.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gtxbjtnzgz.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhougkuu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtzpcvhibq.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtywglotwk.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtdchnhdms.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtupxumvgm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gtpyfxhyxw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gtvyysgpsl.html


<!-- 参考信息 -->