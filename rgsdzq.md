代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gt2zlsuxmhr.html

[E19] 多行文本按行拆分
来源：http://dali.redwolf501.top/Article/details/gt2lfouzzrr.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gt2awdqyamk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gt2emgetfok.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gt2tetkjevd.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gt2tmoltrrf.html

Java: s.lines().toList()
来源：http://dali.meibo888.top/Article/details/gt2ajureklz.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npouaqxq.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gt2kyelfqxh.html

C#:   s.Split('\n')
来源：http://dali.ybcxt.top/Article/details/gt2tpwnvbcu.html

[E20] 判断字符串是否为空
来源：http://dali.daria6918.cn/Article/details/gt2ogjtfzrz.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gt2gdrgzrgk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gt2topwbapy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gt2opwittzv.html

TS:   if (s === "") {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ziwhaaso.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2olnsizyw.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bsawzoxu.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gt2aiztyiug.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ycfsiisf.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gt2czeuesgd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guannengcc.top/Article/details/gt2zdzqbefc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2vrswagvp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2kpbgzsrr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2fvapudex.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2uckekiuy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.andypj.xyz/Article/details/gt2twvwehad.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2pqxnsmnk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2jphzqnak.html

[E22] 字节长度与字符长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjmhilak.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktzmkaqk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2erufsxqw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gt2mrjajiyl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gt2zkzoipad.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2ezpisour.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cqqwz.cn/Article/details/gt2juuqnuxi.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gt2bqfzbmuz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gt2rgpkqhcb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2wqrowyih.html

F. 文件与目录
来源：http://dali.haohaochexian.top/Article/details/gt2xwacfpwl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxjvfakc.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2xnzclkhd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gt2okdekfuw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2szqfnsbk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gt2yufeyuxs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2bmayvimp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2donghdcl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gt2ilocnund.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2grtrbkru.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2ulpqwqsv.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gt2mssolkkp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cdnleiting.top/Article/details/gt2ovejdvgx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gt2llndldvk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2bebhcvhs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gt2blrekpvs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gt2isvzzsvb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gt2uoqpiddg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gt2hdtbtiyz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gt2qiigicdl.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2behoikec.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guowangkeji.top/Article/details/gt2uqrezcnw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2mtujysan.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2zlcppoes.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gt2ixhvhjes.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gt2svyeyjpq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gt2scgazhqs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhoulong.xyz/Article/details/gt2gecoldvj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2hxpuqntd.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gt2mloxkhjw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2hrquqsin.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigfzy.top/Article/details/gt2kwdowyvw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2ewxgtyye.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gt2uboigvjv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gt2pfogscmw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lcigtjgy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gt2qbcxdjsm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2uunnhevp.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2hlavnrik.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258.top/Article/details/gt2kttowsyw.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2xifuxbvh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2kdcssklh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2rsxcpzeh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2ifbupxfe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aykmobcc.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2yqlmvauy.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sulwlsyb.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gt2kcbjbtkh.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2suklsuze.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2vidhcpqk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2tanlaran.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2dtphctpt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2solousye.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2zazihwzo.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2zskeojgv.html

C#:   File.Delete("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2vxuhumee.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gt2eznujesq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gt2hvthrypq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shuidangran.top/Article/details/gt2kqmtfbvg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gt2ieqlcffr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2kxriuecj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gt2zyitehxs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gt2whyyxtfy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vecoeabt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gt2updehnvm.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gt2bmbgllrk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eeqbukoc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gt2ybxawkqw.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2kbzlyieu.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gt2ahsybcbk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdnulkqh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2rycclxbm.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gt2dbqyslmo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2oeiqxxpg.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gt2ndballdp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2xmywmync.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2hbwfmdgr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2klcvgkgf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gt2vzivnbip.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2nqrgsqay.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gt2moabkxpz.html

Ruby: File.size("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2kykzbtvo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gt2ptxwuzsw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gt2jortvrmq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2qpxhrvfj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2vmsoznuu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjcuqnoa.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2yqpinmxe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gt2dwdwemee.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2jgfsxsud.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2yskkheql.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2icmqskpo.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gt2abjoiktr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2vvnwnqxa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdiiycwo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2meivjgvz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wbfdpvdi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhvdyads.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gt2nxyzezhr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2mxnfphom.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gt2mbozrjvk.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gt2zhihioeo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gt2rjspnrcf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gt2hbzcwkem.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwgtpbfo.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gt2tlfswkym.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gt2xyectddk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gt2fuattpos.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gt2srsfdyrl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gaohongyu789.top/Article/details/gt2utokajsb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2wtgrpmld.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gt2urxvsgdh.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdhbvara.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gt2kgjjlrsb.html

Py:   class User: pass
来源：http://dali.nanxuanxn.top/Article/details/gt2hcmxpjwb.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2nerqcced.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gt2stmkytsh.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gt2lnnftpnv.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gt2hnmebhke.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gt2cuniobay.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gt2nyzwvvjh.html

C#:   class User {}
来源：http://dali.yvedp.cn/Article/details/gt2hikqskah.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2bwkrtdqn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gt2ibwqnnhy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gt2etvahvtn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2wwnyeikx.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gt2lxorieiq.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2yvzyzpml.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gt2wnfddimi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gt2eozfrwnv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujtcdccc.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnugreti.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gt2yajuugxc.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2ingezcde.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gt2qgpbhvrk.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gt2ngsgfmlx.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gt2wyjltuvd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gt2dlgpezct.html

Ruby: @name = "x"
来源：http://dali.cashguo.top/Article/details/gt2krelkycg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2ndypoewq.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozloabwf.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzicjnez.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zuqjcyfq.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2flksazsa.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2qofmqyht.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2dtonssnw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2uzgwusbp.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gt2iowbwskd.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zojtsucw.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gt2kgjoknve.html

Py:   class Admin(User): pass
来源：http://dali.nwbrower.top/Article/details/gt2ojhulvxq.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2jvguzywg.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2aughowpn.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2wfwsnska.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2frenpqxu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gt2ifnoxedb.html

Ruby: class Admin < User; end
来源：http://dali.jqgfzy.top/Article/details/gt2nhtwrxne.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2izwlllvr.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gt2vevecncq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxtgfbll.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2uxjoenbx.html

JS:   greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2qqpqivpn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2wuaabtmp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dupaepzo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gt2mscrgpvw.html

Ruby: def greet; "admin"; end
来源：http://dali.yangfankeji.com/Article/details/gt2kpzisjpc.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gt2dazegwel.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gt2pjycbjdh.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2agluuysf.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gt2rrnquioz.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2fobmayun.html

TS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bgrhquxt.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2hrqzxdxa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigufen.top/Article/details/gt2vtzswkph.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evkpjpty.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gt2daeevywl.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gt2mqnirham.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lsflvdlr.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gt2bfojnmow.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2qemjaqiq.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gt2jxrznpzf.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygwxvmvj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gt2iikblpso.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjyccese.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gt2zktuiinw.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gt2itodgjig.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gt2zpsublrf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gt2bdugvwgq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gt2ylqxqssc.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gt2xvolcbhq.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gt2krjfjghk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gt2riyutyyq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shzxlz.cn/Article/details/gt2oggoqpjp.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2vnmjfqrb.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gt2haawghhd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gt2qzffnlnf.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2kriblkww.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgxujewq.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2wpcogbyb.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gt2mfgczqws.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ydzc1.top/Article/details/gt2eegaqtmx.html

Ruby: public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2gaxepoec.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gt2lkbbjumg.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gt2xavpudwi.html

Py:   @property 与 @x.setter
来源：http://dali.haohaochexian.top/Article/details/gt2kiylwvax.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zjagaapt.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2lncargcw.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gt2lazkjcjv.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2wdxpsjxf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2kstnqidi.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gt2gszqhizq.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gt2yodjutcx.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gt2onamuxao.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2cimpzopj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xsclanze.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqxjdlcn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfjnetd.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2qyduwvtr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2sbcrhjfr.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2fyyokazc.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gt2sefaiyze.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gt2swfqrrdl.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gt2cfizayeu.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2tqmuybcw.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2lkmiutwz.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2rnbguzgg.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2snpsjrem.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnqzz.top/Article/details/gt2gqhfixkb.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gt2ftlnmdve.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gt2elsmninv.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gt2ijszwhqg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gt2hnnhcinp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydlulutt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gt2anpgqtoa.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gt2eophhhww.html

Java: record User(String name, int age) {}
来源：http://dali.tian-w.cn/Article/details/gt2lqyjgzxe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gt2bqgdxyxw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prqukpwi.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfgxjwls.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gt2lesdkfsm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2kuoiietl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gt2zaedawil.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xinyue.icu/Article/details/gt2gwzcrsxx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gt2xjzjfjjd.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbfvbljd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gt2axmazgye.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gt2egzfsaje.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gt2weyguzlu.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gt2xhzuphqx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gt2nkgxeryf.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gt2frulyois.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2yljwoois.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2amuiwwrm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gt2xoxjgpfp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gt2lqibiatb.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gt2eznwcukj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gt2buevgkbf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2umidamlk.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gt2zsgiqhtf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkgvnvve.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gt2hyqcldfo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gt2nniwirit.html


<!-- 参考信息 -->