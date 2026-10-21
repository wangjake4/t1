代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtpfmsjtbb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.316326.xyz/Article/details/gtlgtywtdr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtiulsghfe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtlvwzsule.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gtczjkahmc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtmxvhvmju.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtzdvvxwic.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtokjbrtli.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtocqspvnb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtvxbtyvyr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gtqtijrbxb.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtpsopuutg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gtlntgjxqw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtftfnsons.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gthwuprosn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtptaynpmq.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gtpryuxjyi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gtvazlbpzn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtmouzodlb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gtqbcaavgq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtxgwppocz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtrymwtxzk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yangfankeji.com/Article/details/gtkgtvrxec.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtkywsnudw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtntpsyyct.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gtpnxjjacz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gtmbfilcak.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtnuchxnkn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gtecutdogs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtlqmvfizh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtngaxlhux.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aizwys.cn/Article/details/gtxfodovlk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtbtxngpch.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.snrcjt.cn/Article/details/gtyxdzzdfm.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gtlfttjzkt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gtpmujindf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtwpdndxne.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtdstnqdeg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gteojxfovi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gtjsdzxugr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gtavpoqujd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.svipenyu.cn/Article/details/gtwrpymwkb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtgfzdxywf.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegdgvcdu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtdlyfilca.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hammf.cn/Article/details/gtxoalmokm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtzcgwcvig.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtnzbbxzdj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbddtktqv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtybltcwdl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gtulatvdxc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gtklfnkutj.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenlongwang.top/Article/details/gtbqiltppg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gtkhtzxtpc.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gtujxruzzu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwvhxnuyn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtcxblxuqy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtmklvxdmh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gtpxbfgmsf.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtznzpbhoq.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gtmwsvsjlu.html

[F06] 删除文件
来源：http://dali.c1oappe.top/Article/details/gtbhfqlpty.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtvqfnvpmp.html

PHP:  unlink("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtmpgpljsj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtmurelouk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtkwfudjrr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtllkqtunj.html

Go:   os.Remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtighstfke.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gtrkiizpit.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtdnnpozhx.html

[F07] 创建目录（含多级）
来源：http://dali.jlsjyb.cn/Article/details/gtzhoyfnpc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gtjeqnabgr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gtiwjvztzq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtdmbhtitu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtklaychna.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gtkgeamkre.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gtimjemxhg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gtbbjbnvfg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gtjevgludx.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gtwgkpzybx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gtlehccnbd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gtkgyttqlo.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gthklmdoyt.html

TS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtznmugwmj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtywyjuary.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gthbiqaduy.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtzukchzcz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwvsowem.html

[F09] 获取文件大小
来源：http://dali.zhiwuduotai.top/Article/details/gtvfkgebvy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtcmfxtwwp.html

PHP:  filesize("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtlbvqkunk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtdkddfbgj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtkythfmdk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtfbpbklyk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gtvsajwgfm.html

Ruby: File.size("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtpymdjwkn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gtfzzqrqjj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gtjgxbbysm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gteldulbde.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daria6918.cn/Article/details/gtbenydkub.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtcwtljjnj.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtgmqzroqz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gtaujktcwe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtibbmjtxa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gthkipzrke.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtkdlptelf.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gtcsbntcyd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtlpnxfsgf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gtpotdeiyq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtvatqkxye.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gthqoopltd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtfluzgblc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gtonutizrj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtocamcnib.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtziwzbsvv.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gtvvodkyzc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hysaishi.cn/Article/details/gtfidskxwu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gtjkqtcdgm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtgmcjchjf.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gtgtmmylxt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gtndppgxya.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gtacmdaxbl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gtlermauzd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gtxfiyktps.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxzdmazlw.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gtxzudtqfv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpwausrkl.html

[G01] 定义类
来源：http://dali.jyoumei.cn/Article/details/gtpyvisqmj.html

Py:   class User: pass
来源：http://dali.yueranfly.top/Article/details/gtrjhrztdm.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtjutvilgu.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmiutjxh.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtprwyrlxh.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gtcozzawkl.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gtvamkuctm.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtpshmssuo.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtrazeolfy.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gtrfzstubw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gtbcctpspz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtsaspxdyq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtphiocasb.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotkxopxq.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtkixwssvb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tian-w.cn/Article/details/gtlmhhlcdw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gtgmnztidd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthveewfgw.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gtgthdwybf.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtppddovfi.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gtnytwccvm.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gtroropmzu.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gttoskdovl.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gtnnlxgtrm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtueavxmts.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gtmpnkwehw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtuftsrgiu.html

[G04] 定义方法
来源：http://dali.ppjwa.cn/Article/details/gtzxufipoi.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtrdgcznsb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtqshjkjfe.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtzgxkxnbe.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtkoaoonic.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtzvsdqbvo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtsvipogcg.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtqcyxbrkl.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtsrkrhdnx.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gttbqbkdfc.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gtrfkideul.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtphclxkbg.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtvfkkjpcw.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtxkgwevnu.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvkthegz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtsklzuzre.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gtbczrkzdq.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gtjyxuzhhi.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtttdqebkb.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gtfteqrnmi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtaredxjzh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnrloipi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtjqrzugnr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtwzsbxete.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ybcxt.top/Article/details/gtyxodjarp.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gtmndhmopp.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gtihrmhmwz.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gtccgccduu.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gtezeujhrw.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtseputxst.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtjnikdbvf.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtkdjyuetg.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtplogbmgy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gtepalgbtr.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxoourtv.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gtfqlmnipw.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gtzwbeavqz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gtclxjcjxc.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gtjrsoxlmm.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtrrsiccdq.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtgrjsqqlt.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gthpljkxft.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtentvojum.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtxulyqbnd.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtjhbwdouf.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gtffgiuzos.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gtqvvkykqp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdthdmbpt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsaomxnui.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gtmvenrwjv.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtterbbihz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gtsbfxtbie.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtfoupltgg.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtbrxygggx.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtzjguzycw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gtskqbdxaw.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gthhqlqrwe.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gtypsnjlpk.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gttbcrvzhc.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtcfkqfswu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtaioiyghk.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtwxwabbyx.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gtusfmjokz.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdqdsjny.html

Py:   @property 与 @x.setter
来源：http://dali.zhixingplan.top/Article/details/gtlxmmodea.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtfqdzfgha.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtmrkanvat.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtkrasxyzi.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtnsppaynt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtkatvbvyq.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gtdvqfffqf.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gtygwmtfze.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gthgciqhld.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtkrqrlixj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtypnlwjcu.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtvtzofvef.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtbkrlmcew.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtubkifqbl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gteekrdsfl.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtlcfqdeun.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtastlnkda.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gtlwukxyih.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gtfkawjbze.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtpwbaqyrm.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubzxxpdl.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtbxqxbwni.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtzchrxwqx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gtzjmxcgfa.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gtwnvixmbl.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gtnlrvpjlj.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtvxgplrwr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gtrbsevgba.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtkpxafjwq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gtpqyiring.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gtiqgmhgna.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtsgqvgbkz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gtueffxasg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gteuhgreoy.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gtzmeibiya.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gtdpjtligg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gtsmsnjljl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gtxbmdwodb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gterldiglo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtqvtwruwk.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtavhcsgwq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gtmwkzgmdj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gtzlexeapk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqqiyout.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtcwawwmrv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gtonzrvhvi.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gtnqyyfdgm.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtanocubhr.html

TS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtxzbedcrq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gtmavddhaq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtzksgkjmn.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtvrvmxkzc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtvrsddkyi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqqaltrux.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gtpdxhhwxq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvutfxkuf.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gtcdmykxyz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gtwxokkaga.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gtmxauobxc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtxwgmlqzp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtuyhdctvl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtjqvfgtnr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtguwpldzk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gtdsieyveu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtoozhqibj.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gtdiduvjdw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gtftxnktab.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtvgximcuv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gttvqzufta.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtrwglsyjm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtnwzdphnu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtyysbbzpd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gtzevkfoie.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtaboxslxp.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gtiwzynhhg.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gtynscikib.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtjssguceb.html

JS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gttrorouzl.html

TS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtqmsdgiog.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbnkuljy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gtngkrwhba.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gtoskqhdna.html


<!-- 参考信息 -->