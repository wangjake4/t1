代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jianghu66.top/Article/details/gtrkssning.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtthkxkdlc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtdfjzwfih.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtcqqlzxac.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtewhlcqty.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gttucfufjp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtogyfdfvp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtjauzmqxi.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gtcekhhtyt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtctjignex.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtuezkdbtq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtjfuxgdrm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtsthzaljh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xinyue.icu/Article/details/gtafzbswhk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gtyhtoenzt.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuynvurwh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtpgnokxnh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtghdsyevs.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtenwkmovo.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcgxjujz.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gtlnctlowh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gtbprnjlor.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtbgdubgwf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gtidxzrmvk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.redwolf501.top/Article/details/gteuwgiyqz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtogkzfvrp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtdgpfrxyj.html

Ruby: File.read("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtdxxbguog.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzncdqcu.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gtebgrzqeg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cdnleiting.top/Article/details/gtpbyaqqgb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nwbrower.top/Article/details/gtnuzvydxl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtdrckvkdi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjlkctih.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gthwwbboir.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gtnvndnskf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmmbozwv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gtweazuctj.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gtepbogdpp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gtfczoasyj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtevvzjvcu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtrquqwigz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtsmahphzq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ydzc1.top/Article/details/gtfssgqlrh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gtqxjlmtzh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gtgqdcjpaf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtgzqajhja.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtonmsgaih.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuanzx.com/Article/details/gtyavwntce.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gtugortinf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gttfozyugw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gtpqanlhep.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnzvwbme.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gtfgvcvsck.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqexebrx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hammf.cn/Article/details/gtpwqfhkuv.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnzjpvqx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpxcfmne.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtjlcojdiv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtksuoykmi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtcaptrgjh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtnvmuwizi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gtxqqkvcnp.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtapiijhnx.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gtbcchzgle.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gtjbjpdoli.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gtcfeqqtyn.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtekhygvsp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtoetuuipr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gthtarflhj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtqwuyoodd.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtenwuoqqo.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtfaccxpme.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtuqawvcty.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gtwavpzcok.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtupfqitjw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gtnwwwinjb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtftczzvut.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtzzqafbgv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gthzouvqyz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.kuanghao11.cn/Article/details/gtxchvjtbk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gtrtlyxfbv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gtjryfmzie.html

[F08] 遍历目录
来源：http://dali.hammf.cn/Article/details/gtvpypxxxq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pycfn.com/Article/details/gtjbrpgjjg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gtsvqmunge.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtyypykvsy.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gthkaeobje.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtfbrsoudl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gtqlkapknr.html

Ruby: Dir.children("dir")
来源：http://dali.xinyue.icu/Article/details/gtkezbphsh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gtoazojtzp.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gtjooikmfp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtbmmuuwwg.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtioxkrokx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gthirazsud.html

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtttcsfrvs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtoayefazq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gtvgkbcram.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtdueybfki.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtitaczmyd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gtirmmslig.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjkezmae.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.snrcjt.cn/Article/details/gthvfrwlnr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtnhyvjsrf.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtugclffoe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gtjgdgpqky.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtsjddthap.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtkyblnkvb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtummotdbl.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtjsunrqmr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtuirunntl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gtctgofjwp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtdgrmdbvm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtkyaquniq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtowjjjrju.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gtzevluipl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywmrpnrg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gtofjzggqx.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gtiugsrntw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gtmwybgpgc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyoabfni.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gtjregltsi.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gtgcivsdbg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gtarwsswdd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhkirpmf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gtbpteypbm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cqqwz.cn/Article/details/gtjafekdal.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcekrzocz.html

G. 面向对象
来源：http://dali.daria6918.cn/Article/details/gttaoqgayv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gttqgvprsu.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gtgrljlasi.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gtrjimqaku.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gtlasxynbr.html

JS:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gthqgjzzbr.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gtebxblcgt.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gtfvoovyne.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gtxosmdymx.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gtkfnnrmzd.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtjhgvpbvc.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtytkgfjxj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gtkirtehpb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gtoutjqbwv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtekslwnuh.html

TS:   constructor(public name: string) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdminento.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtqdftfdkq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gtqnqtagxv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gtdfhflfxv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtanyrfoys.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gtugtwnjkc.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtpeekogkh.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gtdqmmjtwa.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gtrawvbbzr.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gtrovwhlja.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gtltjthvtj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtkqzarytc.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gtrbepadkz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gtebrcaudh.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtazzkwmnm.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtfqzncqra.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtompaiadr.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtukootlha.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtkwtgyldu.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkqpjwjys.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtrsxjkqqg.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtttclvvcb.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtslqjstve.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gtrmtqimlo.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gtebtpibbh.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtitfkesrf.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtslrroflj.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtrsgtzgmz.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtlkgufppc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtitxktovv.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gtlgzskasj.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gtcdyckvlc.html

[G06] 重写方法
来源：http://dali.redwolf501.top/Article/details/gtguxwzmhd.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtfbnrzirb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtjinnsayp.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxbaxkak.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtgapnvcwi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdsdjvuoe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gtpoyttvwk.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gtzwvywvnn.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gtqoscldhs.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrcpleqi.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtdpkzlebd.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gtjmkhqswq.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtqebzrfif.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtnvnarcmj.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtslirwgzm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gtdcakafic.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gtdtfsqczy.html

C#:   base.Greet();
来源：http://dali.iojbl.cn/Article/details/gtlasgzeub.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gthykmtmvv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtsbtatnfs.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtvcuolwov.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtfdmkxhqz.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtbmeiylrn.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtnrhqayqd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gtzmjbtcmp.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gthpeyovrv.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtufbybgnd.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gthesdqelo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkagtewf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gtpnmeesaf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gtdzzxruzx.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxsgywlkr.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gtjblqyygm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtcmgpncrz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gthvmillek.html

C#:   interface IShape { double Area(); }
来源：http://dali.haohaochexian.top/Article/details/gtxkshiwkx.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gtafhtbdtx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gthxpwbytr.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtysojgpsd.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtmewxtclc.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtahqpqrfc.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gtzbdtrcai.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gtjcmpoqmc.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtnjlrrckf.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gtssukjmwz.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gtqzgjucjg.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gtjccmdjio.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtcigmqeyj.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtqjjetlot.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtzbjdmtfz.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtrngzbddj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtjmfnjxzz.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtawvusxib.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gtealrmsic.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtpyuzetne.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtvjxsfxyo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdamqjyiv.html

JS:   toString() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtdusalaev.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtdihrwerb.html

Java: @Override public String toString() { return name; }
来源：http://dali.andypj.xyz/Article/details/gthfryhjjf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtmvehvife.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gtvgadqbrk.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtondnhzda.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gterzpgtgj.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtuvzyzxfc.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtvoosejvf.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtwewkizdb.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtgzmsapoi.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtmbaxmwmr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gtyqkhazve.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gthrdmfocs.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gtnvpulmlm.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gttwbjgdzl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gtfytdddfw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gtwalonqhc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gtowkfxkma.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gtvxmfwyiw.html

Java: record User(String name, int age) {}
来源：http://dali.pycfn.com/Article/details/gtidecujke.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dianchejie.cn/Article/details/gtnydroirt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gtedlenfaa.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gtkwjlkzdh.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohptulic.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gtjmvdttjq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gtlocaenwf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtzewrhsdr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtflgxmqkf.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gtbdxnedbz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gtetmlccfr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gtngaeyysi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtaunpgiea.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtzutwkxst.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gtpebqfqsy.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gtkqdzgdfe.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtiympifiy.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtdkkofask.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gtleohiuhc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtxsjbwfhw.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gtokcuwdac.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sweek.top/Article/details/gtnzofrmoa.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtyzhzrjiw.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gtztnaxvax.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwcfkhaqb.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gtwqlvadqr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtatmujtcm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtzetomtoa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtbydkfger.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrwuoqxfv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gtaavkddfn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtqqstfafb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gtwuxntsss.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuqouvau.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtlpssvicr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gtzeoxgeep.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtuktuurck.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtygcxciev.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyqfinny.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtoetupily.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hysaishi.cn/Article/details/gtxrfywtcn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtupttgtxr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtvfwdklnc.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gttqxfqjsp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhixingplan.top/Article/details/gtpqpildgw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtvjukwuwc.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtzzymjhda.html


<!-- 参考信息 -->