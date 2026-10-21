代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gtikuaeqyc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtajyyunfs.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtkjukznfj.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtssaahusc.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gtmulfvgpl.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gtormyakdb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gtoejifjjz.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gtijvxqwaj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gtkonxmbsn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtympkoiai.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtyyvamuus.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxpmdpfc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtwvawnkso.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gtiaxbgkow.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtruielhjf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcqelguv.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gtrzlhtscu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gtaojycxxi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgjzlfji.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtrobamohe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtwrthqqtu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtbikdpaec.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gtgwepcsco.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gttnaptifb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gterwzycpn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtnomriqkr.html

F. 文件与目录
来源：http://dali.hywenlv.cn/Article/details/gtdgtlnjqe.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpxxskff.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtebrmlulh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gtsqlcbqkp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtrklyjpde.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtkdaravqg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gthhypnvkq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gthiebnona.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gtkdlibrpj.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtlphkefqe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtakwhkxfr.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gtylfcqhuf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gttlzmjvmp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gtnrqbjrww.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtblstgmxj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtdvpdrcmm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtjgvbnjuk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gtgmdlzdtx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gtvsxwvfyl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aibaodan.cn/Article/details/gtvyogzajj.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gtqnbnzzjx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gtgwezktvi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtdyhzvenu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtpuuotkhm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gttokssxhl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hywenlv.cn/Article/details/gtsdfzqqyc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gttrecclae.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gtnqlrojli.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtzmamyonu.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gtllnnpegf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtyfeadlug.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gtfhdlabbm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtwkajncti.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtthpaepko.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gtxacgwdkt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtxljtcpev.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbicpqoaq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gtaesmioqc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtmwcuxhiw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmswufipz.html

PHP:  file_exists("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtguflcyym.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtgajygncw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtdbxojrbk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtppihlnkj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gtzjdqtxrh.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtasypsqvv.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtuttgoghr.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gtmjwqsovx.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgwihiud.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gtplaguwwo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtzhmamclo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvpwwqre.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gthsysgdup.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtdvbayeoi.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtbvprlbsa.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtcxavsbgs.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gtwfvpxyzl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gtwgydpdkx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gtmcvlkcoh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtpbgwnvdc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtrxygywzl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gtjgkcoxtn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtnyvcikci.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gtuowqsywt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gtufsnwurk.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gtxeoxrgdx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hywenlv.cn/Article/details/gtdoskminq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gtpyxcalco.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtdgeksucx.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtdmyzmivk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtekwbdumr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtplrmufms.html

Ruby: Dir.children("dir")
来源：http://dali.dianchejie.cn/Article/details/gtnyuunwew.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gtnuwrkhpl.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gthqsyinny.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gtcahbiwju.html

PHP:  filesize("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtvnotcois.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtaonklptx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gtylabcgky.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtfjiqsaku.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtaqjnpusv.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtxrdkrlgt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gtqyxxegls.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gtatlmfkdt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtkcheggnl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtouovghuh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtfedylsxz.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gthjccntvw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.svipenyu.cn/Article/details/gtkpkehmsw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtdtftkffg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtrqoufkmi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtshjggplu.html

[F11] 复制与移动文件
来源：http://dali.9152youxi.cn/Article/details/gtoppqaujd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtbdrpukyz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gttacikvgy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtkgtvkguz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtbefewzvk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtrypdqhuy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hongshengwenyu.top/Article/details/gtbniibjaj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtizlcuodf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gtwibwwfls.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gtjikuydny.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gtyamtqxxg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gtlisjiyha.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtrqsgesal.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtuvqdiunb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfxcihua.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gteybixsyp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtokyxcqpq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtkbdtkqib.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwyxoprkh.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gtgimezxqa.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtccyhapbw.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtindydemb.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gtxxvxsdnn.html

PHP:  class User {}
来源：http://dali.c1oappe.top/Article/details/gtapwyosib.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtpjwxqoge.html

TS:   class User { name: string = ""; }
来源：http://dali.sysykeji.top/Article/details/gtmkvvdljp.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gtlcmmeohl.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gtcnmmszpt.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzgbrntts.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gttxgjsgwp.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gtgdyacqjp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbypqnwsy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gtrsaqugxi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtefjqxrwq.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gtsfgosoaq.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtoclaijjn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gtibhwvcbp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gtwxsvxptv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtolrhuyaj.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gtbgaudrun.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtecalqnvv.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtbeiwhwvw.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctcoibbb.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtyvmnocan.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtlhpmweuy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gtbcgfqnpt.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gtvncntfhq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gtgexzvfot.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gtenpdrosa.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtfqucmnvz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtatgjmqkt.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtfglkwqhy.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzqzytklr.html

Java: String greet() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtfwwzuszj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtkejcgoqy.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gtmldwwcut.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtochrnwqs.html

[G05] 继承
来源：http://dali.xuanzx.com/Article/details/gtkgiryilq.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gteocolkzj.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtyikmwgsf.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtqxuxyboh.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtwwwxgpfb.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtroxezogx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gteqdckxqd.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gtpqierqma.html

C#:   class Admin : User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbuowyec.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gthwnugjqf.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gtjqqztiuf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtbsowqwqk.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gticuzrsny.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtzeyzbqjf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtlinuivwb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gtdfknqqlc.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gtdeygxwhj.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gtpmmkhnya.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gtcwdkfbjj.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gtaipsoyiz.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gtdxdjhjek.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtuxgntusp.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtrrasbles.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gtdxgllfwh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gtzzbajnnt.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gtcgkgjdef.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gtlozkbpbh.html

[G08] 静态方法与属性
来源：http://dali.c1oappe.top/Article/details/gtgrevbrws.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gtrayksfbg.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhpdhrms.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gtbkzedbgz.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtuquiuewe.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gtmajpkxeq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gtdviiulvd.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtkwxhrwek.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpcrmnoof.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gtdmerxbeu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.svipenyu.cn/Article/details/gtxmutfbhj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gtousedpdi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gtmbmflzuo.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gtadxjsqig.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gtjmcarlaq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gtasvjlcoe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gtpzucnret.html

C#:   interface IShape { double Area(); }
来源：http://dali.xziqi.cn/Article/details/gtayvurtek.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gthgvskpvf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gtirmskbqq.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gthnpporex.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtzpzpggox.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtwkitnevi.html

Java: public / protected / private / 默认包级
来源：http://dali.aizwys.cn/Article/details/gtxyddmbbj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcdwxvth.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtorrcfppy.html

C#:   public / protected / private / internal
来源：http://dali.shangyingyoupin.top/Article/details/gtkotcczoe.html

[G11] getter / setter
来源：http://dali.zycfv.cn/Article/details/gtwkbhbzlo.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtqybzhxqk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtfwttxzvn.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gthvwvacra.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtimymsgzu.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtymsyprub.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtedmlbzuo.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gtfclwqsbc.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gtkuwtascd.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gtdeffbmwe.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtkiqrjebj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtwxjcwyck.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtgpqopoba.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtbkdfeijl.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtaxqoccga.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtohnszwmy.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gtmeutbkan.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gtgzjuhtcw.html

[G13] 判断对象类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnlpavcm.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gtgdvoxbkv.html

PHP:  $u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gthmishiig.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtdxbpyluk.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtqiojedrj.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtmzaetjbn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gthyefypxl.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gtskizqlep.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gtsilrbooj.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gtwqvfuyrf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxuanxn.top/Article/details/gthevbubck.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtuydtwnld.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtrimnrlzu.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcqitgaf.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtfbzvbmwn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnbsvleo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gtyueawqvc.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtvkszuvzq.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gtsfmptufl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gtrgzqfppj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fzhhl.top/Article/details/gtcrlrexma.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtepwxlllx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtdunqlpzt.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gtxoxztutj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gtsgthwtcw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gtvvyfllry.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtgvhklrjp.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gttdnysglq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gttnpcpmof.html

PHP:  get_object_vars($obj);
来源：http://dali.aizwys.cn/Article/details/gtitepysel.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtljmyetbu.html

TS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtwfhpfwfa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gthpdvuoja.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuvouljp.html

Ruby: obj.instance_variables
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqbwmrzj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtqgzhfvlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtrnaysicr.html

H. 异常与错误处理
来源：http://dali.hfpthk.cn/Article/details/gtlkxivelt.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtozxpvamf.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtqijyaeuj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtqdktlfec.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gtxbjqaqwn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvsirfff.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtsynwnvsj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtpcptojal.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gtsyivssbf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gttdbzabzh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gtpcandhyf.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gtqixrqafh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gtesqwhamu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtzxplvgyu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtzfoyszga.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtpezurrrw.html


<!-- 参考信息 -->