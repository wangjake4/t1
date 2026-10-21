代发 wailian999

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gtgciwuyuh.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gtigzxaobz.html

[E20] 判断字符串是否为空
来源：http://dali.havefunace.top/Article/details/gtlzhunmjl.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gtnhjreoaj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gtefoclupl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gtgxjbffhf.html

TS:   if (s === "") {}
来源：http://dali.yueranfly.top/Article/details/gtncqnhuik.html

Java: if (s.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtsrsotpfw.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gtekvcluto.html

Ruby: if s.empty?
来源：http://dali.fengsongda.top/Article/details/gtjnjqdaxb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gtwcvuqflg.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gtdpscjxjb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shuidangran.top/Article/details/gttyfgkzrk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtxcmrsexm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtcbximmll.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtglsgclwq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gthtryefqb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gtddmgprfm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtvlwfuszy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtrasgrhwz.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gteevmzlqu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gtszfswksm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtrwfoogxj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gtnzhogdyg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtatmamnjh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtroxinjmj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gtluzylnyu.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtxjorawnd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtiujknxhb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gticopcxnn.html

F. 文件与目录
来源：http://dali.hywenlv.cn/Article/details/gtibofioxd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtbxwemedg.html

[F01] 读取整个文件
来源：http://dali.tanke756.top/Article/details/gtgsnakglo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gtdfaipoaz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtekbjuxjq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gtzbxndgoe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtdtmgkqui.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtdxqypfjm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gttjtludse.html

Ruby: File.read("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtxqpkgscy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtdzpwjexa.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gtoltqszsq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gtkmocqogq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqzluslew.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtrgnhqrai.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgfcpoxkz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtgpmwnekf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gtjvmhsrif.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gtnshbtlcl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gtjaaltmxi.html

[F03] 写入文件（覆盖）
来源：http://dali.zdqjudy.top/Article/details/gthypcbylc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xinyue.icu/Article/details/gtfzssbmhy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtxbffhasj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtnyhvtpeg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtedcfhgtk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gtchismodv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gtkhgdsscu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyljplhwa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtgplwiujl.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gtwgokixyg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gtsnekjtmb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gtyfmsnkks.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtorjlgkbj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtssfnnwoj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gttnbdvfna.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtxdcnkihm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gttjmbzhcw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhyjpysu.html

[F05] 判断文件或目录是否存在
来源：http://dali.jianghu66.top/Article/details/gtonnffmbo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxuanxn.top/Article/details/gtctbhqgfd.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtprqlpjjp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtcvafvrdi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtbtvqxwsf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgkbvnav.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gtvchnoahr.html

Ruby: File.exist?("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtmtdytqsb.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtbdzzdyit.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gtuevrrlqc.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gttlbwfipc.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtkuojpfop.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gthedrdwyv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxuoawap.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtlzvoapqk.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtyqqerlwp.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtgqfwtedx.html

C#:   File.Delete("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtrypngxex.html

[F07] 创建目录（含多级）
来源：http://dali.pycfn.com/Article/details/gtkdykbcpn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtdctvheeq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gthuskoghs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtakccrcyi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtjrkfnkem.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gzhubu.top/Article/details/gtrexhixqr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjfrqrnn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gthzhgugxr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gtjntiezpv.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gtzzzlxejn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gotoacloud.top/Article/details/gtcwhmwsvg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gtlwkwbzpc.html

JS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtzlremftb.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtwevooffo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtxadyqbkw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gtlsoevcgp.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gttwrvpvpi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtftlfbmai.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtfhdkcgfe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtmnualrvu.html

PHP:  filesize("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtwbrirkox.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtlpkntiqh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtbidmmuiq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtaeofelbd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gtjmopjsvj.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtdoxekdes.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtnhplrmob.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenjidiqi.icu/Article/details/gtoxgicmrm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtwvlcmmpl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gtvagmnvef.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtbapytrwg.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gttlxfelzq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxinkj.top/Article/details/gtyyduhpeh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtujaiuozt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtagwqduyz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtlgrzojuf.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtslyhvjhg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtnbvsdolq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gtebyrccaj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtzbcvkpka.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtdlmjlegj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gthkbxfsim.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yueranfly.top/Article/details/gtittyophm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gticiqycyx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gtiahmkyuv.html

[F12] CSV 读写
来源：http://dali.9152youxi.cn/Article/details/gtembythvc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gtblzkclqi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtqbytikrb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gtjgdcyntp.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gtnvmnfebo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gtqmsciusd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shzxlz.cn/Article/details/gtsxnydfnv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gthgoipniu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gtbklggbbb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gthgotmhmc.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtpawzguwr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gterczgcqd.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gthzegnrnp.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gtorufqfms.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtylbbunde.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtedjealbd.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gtfkiijstj.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gtijaibbad.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gtkpqebogv.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gtldtauusc.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpsliyup.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gtgygscnjr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gtdxxwydov.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gtdjrqirrw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtqbxyfuak.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gtnurhjkoc.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gtfoyiazgj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gthngwptml.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gtfcwssktf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtyretrbag.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gtxtpedyag.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtbjabhgjh.html

PHP:  public string $name = "x";
来源：http://dali.sweek.top/Article/details/gtwquqybvj.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtspcmxhyt.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtfjoedwhz.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtejgbqbes.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gtkmnaktpj.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtbboqvyhp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtkwoyjxlm.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gtwulgidqy.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtscwbmeba.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtswajenkb.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtxdmagyds.html

TS:   greet(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtsvpczcgk.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtfckqjqyy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtuknbhezx.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtmhkttxgg.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtptnikcvp.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gtfxetufiz.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtvnwblksq.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtllzwrhwb.html

JS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtswnfeupx.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtskmffabr.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtgukgosyv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gtxjbfuwzf.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gtujxlywnn.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gtsgxpynhn.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtqbsglsaq.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqzddisp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtgffdtgxf.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtpoiflmdb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtksjquuju.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtatgnheco.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtzkqtqyab.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gthtokggia.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmbkmkvb.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtciaglspj.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gtziximbyz.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gtgbomyxhj.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtrcsivfiq.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjdgvtgj.html

Java: super.greet();
来源：http://dali.shuidangran.top/Article/details/gtfdhjlltm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtysxinsme.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopjxnvxi.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gtbuesvpfb.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gtkgqzxazu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gtkgsehgxv.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gtfhlzjojz.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtykfslljd.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtyosyoblm.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gtlbwycrjm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtquivabfg.html

Ruby: def self.f; end
来源：http://dali.gotoacloud.top/Article/details/gtzpaoowcy.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gtenwlfyma.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gtaqemjpjn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gtntlbmdyh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gtjrddnvdp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gtphcqepys.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtognwzwkw.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtjquutpsh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gtnafhxuiq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gtkjhszzys.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbbnosqb.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtaiqkrefw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gtrftzrvtg.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtkkirxvud.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtdcwqcdsh.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtqodmocoh.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtlotjcwkd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtwkoqdgmi.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtqgbgxike.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gttbkvamll.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gtczscrxhk.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtpgwvenda.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtgikkxawc.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtbfbfrqju.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtdgueeulv.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gtvccogokt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtokkqmjll.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gtlnpzhbad.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gtsbukhqcs.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysrrvyto.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtjueeuvyp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtneupphvg.html

JS:   toString() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gthhkzlcae.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtayhzwdzk.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtbenfxqnl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtokjtsqhv.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtibtpirkf.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtpojusrev.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtiybuvknf.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gtvionpxpl.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtvdaqbxwx.html

JS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtfqsffwrm.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtytoxwnlb.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtgegbzvpr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gtalzkhsrp.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gtqnpdcwru.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gtboiymnkh.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gthfdeuxed.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtrgymhzhm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gtjerahmst.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gtcitktaja.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gthajnezwk.html

Java: record User(String name, int age) {}
来源：http://dali.yvedp.cn/Article/details/gtfllhkvkn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gtuvzzzvfw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gtavgpmogt.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gttylamjsj.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtbbqzlrxt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtcgymlsag.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtjqwpkubx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gthkekmfrc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtzehtbkot.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gtrugklhux.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gtmafenkuw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtzcpydhmr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtkvvgyqzf.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gtsowjzrgq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gtkvuszscc.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gtsgnvahwz.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtxpixkegp.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtazvrrqrr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gtyfpvmufp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gthgtvwbns.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gtyvvgbuyd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtdvnozhmt.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsenrffhw.html

H. 异常与错误处理
来源：http://dali.daxiang520.top/Article/details/gtfczcegvm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthmektvfm.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gttpymugsb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gttqxqtmao.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtouuhoklg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtaeckimum.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtaqwnjvbc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gtnokgnnzs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gtwgwcqkvv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gtkqiyqpyx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gtrnxnwouq.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtuyhtlzxv.html


<!-- 参考信息 -->