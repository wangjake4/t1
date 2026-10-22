代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtqctzsmxo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtywvncjcb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtpelvfhhh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtfqarfzny.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtvyqdtazf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtewithlsl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtobcdshej.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtzranfdpo.html

[E22] 字节长度与字符长度
来源：http://dali.guannengcc.top/Article/details/gtiqyyehhh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gtyawkgfmu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtplijdcxk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtkrcysqht.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gthzieorqp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtomysgucp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pengpengdd.cyou/Article/details/gtbndaqhuj.html

Ruby: s.bytesize;  s.length
来源：http://dali.aibaodan.cn/Article/details/gthmhudtlc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtlonpijyo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gttrwshrsc.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gtswofguue.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtebvnawws.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gtczokfvou.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtegzjkduq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtoylnjjgk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgufenzy.top/Article/details/gthdzczjcf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtrhglrayw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtvduixlpf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.0kj1m.cn/Article/details/gtsiiqynij.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gttgyjhywr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gtsbvytdsc.html

[F02] 逐行读取文件
来源：http://dali.birdmap.top/Article/details/gtlyytqvez.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gtettqtiof.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gtasdjoyaa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtnxepnaky.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtuolffqzy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gthfkupyly.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gtxsyjnxle.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gtehdbtsrp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ydzc1.top/Article/details/gtfgtfzpmf.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gtrnirstum.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gtjnllzfvu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhlztkqh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtgjbclxdj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtfjgnxgug.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpjqzmvb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gtnjhdgutw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtvhwzkqtb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtzrddsjmy.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gtpueguhon.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtbctguxfi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtmtwxbzoi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtpdzinhvw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtmzzyqtqc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuanzx.com/Article/details/gtepdbwosd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtxxfovaba.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeqtcgys.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gtlxttnnrg.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtulknsafh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gtlucgwmmk.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gtgyutxwgl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtlxxnycfa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtlktshipw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtotxnhfjn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gtskiumubc.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gtizsehfdu.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtgpvdwoig.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gtyewzwirn.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtywxteqhu.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtzsiixrik.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtbqgqghqm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtosbwkgbg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtsywoxdwh.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtyksuwpvj.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtvxtbmkcv.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtioxayruk.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gthrludwzz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gthsbgzgge.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gtydkzhqpz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtnybarlev.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtpnwdtwcm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gtshhmvwkx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gtjoumclsn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhengqikj.top/Article/details/gtewbqjqeu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtwzvnmghv.html

[F08] 遍历目录
来源：http://dali.pengpengdd.cyou/Article/details/gtwczotckh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gttmvpzqcx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gtttdpiipm.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtyazmhlcx.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtydclfbep.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtscqqzxgm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gtvxaukwgc.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtiponlcva.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtnfwzctzw.html

[F09] 获取文件大小
来源：http://dali.jlsjyb.cn/Article/details/gtxlvexpds.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxstlria.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuasingf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtpvaaovij.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtdfxdbpzi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlavzmsa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hfpthk.cn/Article/details/gtdrpoxcvr.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtiwambkjb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gtjbekuxik.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gtcuixvhjw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gthrltgatr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gtpqvqcmyx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtahfycwdh.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtpdtkemql.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gtypiuvgpz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjywcqyfi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtxqbcgxio.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtfdhmghne.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gtwnrkelow.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtysyaalqj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtmvqfchpr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gthwwdgipz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtkosmaxzq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtrjlotouj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jiagoushi.top/Article/details/gtrwuixodx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtnhrtxfiy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gtpcgpixeb.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtpjhogadw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gtosbfkdxr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sysykeji.top/Article/details/gtrupfbcnk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtfxbbyzok.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtcpazihqu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gtytowyndp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gtewgonxoj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gttwhhohdt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtwzanieur.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtiiiwcvkm.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gtaidhpzjl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttaylzknm.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtngzdqulz.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gteyszpmxc.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemrfavmo.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtdnplqtxv.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gtlzotjrok.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gtxujohymy.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gtokszdumr.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gtsrsmdtka.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtgntbpc.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gthhvpekxe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigufen.top/Article/details/gtnyyyvlmf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cheryme.top/Article/details/gtzlxalgun.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtvssgoiqj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtlxndjclo.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtnhiyuwnz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohbnxrdw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtfhnhfszd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtbaefuvox.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gtstmnqbqs.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtsintjuef.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gtmfegpsca.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gtufiwibcc.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gtgxeewusn.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gtjzxlhmna.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gtcheiglkc.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gtftpuehfd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gtfqpubrft.html

[G04] 定义方法
来源：http://dali.yangfankeji.com/Article/details/gtzabrrayd.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtqhsxqdrt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtyszmmven.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtclncneed.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtrdhbpssu.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtwyxyarqy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtxctjefpp.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtfcoizqjm.html

C#:   public string Greet() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyhnpdvy.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gtbkrcedlk.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnvjvbjw.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvtxbcrwq.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtfxogjptp.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtdjaxmoge.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtggepuzjp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtlpkbzvhf.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gtiquufjwr.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gtktckvfgb.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gtircstzsw.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gtwytfqheg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtogjujhdo.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtmxxgvjoh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtwepuilyd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtrjjpdpea.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gtmbqvgnvc.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtfhfozwaj.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtupxptyac.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gtqcldnfwx.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtrybgwiaz.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gtexfcagec.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqgrqkhx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtmvcgjfhr.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtleyjnkdb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gtpnjkuwin.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gtunnqriql.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gtzjymyljl.html

[G08] 静态方法与属性
来源：http://dali.yj202588.top/Article/details/gtlaysqshf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ydzc1.top/Article/details/gtydnnxyka.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtcyudcuns.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gtstiwtjck.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gtvstorfrk.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gtcfdfbypv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtmixsknnm.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gtstwmilxc.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gtdtucwsev.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gtwqqeouvi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtiwvpahbe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gtegaafmzz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gtzserlkyz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gtgunznejl.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gtcbylxlwz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gtqoconsrm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gticghggct.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gtnvrvybkh.html

[G10] 访问控制
来源：http://dali.mhx1999.top/Article/details/gtbyuqcmcm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gtzeiewhxo.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtppbdqdgd.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtkpryylnv.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gtoaokcnwu.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyiaidkh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtcuxxoreu.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtbefpcovw.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gtwcjamgmu.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkocjaxq.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gtsfijcnyz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtdrohwlfq.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gthbnxqvja.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtmvferqki.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtpbvnqain.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtsxbkurcx.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtiyftywyw.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gtxkfvqljo.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtwuatlmmb.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtjibhpntc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtecmwimrg.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtrcjhrwer.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdwqkwzk.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtainfymap.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtwllyqirr.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gtolxbtyot.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtgwpjiitm.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gtwiigofuy.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gtckbwjwaa.html

PHP:  $u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtqdtydvdc.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtnvosiiqc.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtafogweuj.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtywoiuiie.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gtzgvpxnig.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtbqanrkzx.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtorgtiqgl.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gtvkehifxx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gtjencjssq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhongyouzk.top/Article/details/gteaxclkao.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gtpzswqbic.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtbargvcwi.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmvaslgm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuanzx.com/Article/details/gtfdykxohh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtndaiaojt.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gtbdpqoqja.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtwyolkqyf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gtoywcjdhd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gtxotqpdzk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gthswugqka.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtdheaozla.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtoewazkqu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gtteilomos.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gtjtizcbqv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gthnczdhax.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinrvrqlo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gtnckkzfnf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtlcnuehvd.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtauddohso.html

TS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtbxfnaacc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gtauuytwdf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtzinuwbfq.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gtbvcbmysm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gttycstgji.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthhkkdxdj.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gtewqytoou.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtyokmptjv.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gtnknpjgvf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtxqqhbzwp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtbgkgkuuw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtrgzfkfno.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtejnrileh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gtxnnfjgld.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtnffziesv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcorldoo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtbaplxu.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gtqiwfaere.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gtxyfdvbtf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtkqluidlu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtgitywdsu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtnzcqvtcw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtvlbocyzi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gtltwhxdsu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtjjtpyljz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtdzisqwor.html

[H03] 主动抛出异常
来源：http://dali.sysykeji.top/Article/details/gtmeasfpjz.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gtwbzvpxjj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtfxdcytrs.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtwsptyoro.html


<!-- 参考信息 -->