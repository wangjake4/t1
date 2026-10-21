代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj202588.top/Article/details/gtyeorgnje.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gtvmgepjmi.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtqwykfagl.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwkzomvmz.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gtbshphwca.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtiniywjfw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gtyrxmxmin.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gtwfxavipl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhiwuduotai.top/Article/details/gtfpuxqdsb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwlyemnx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtmckuousc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtvbitgcvb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtobfamiqo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gthbxpntlk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtkorqfiry.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjylqmyoj.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtkwuywgbn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gtdrnomycx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtywopvypx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtsjvtukfu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtipsbuyed.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fengsongda.top/Article/details/gtiobmrkrz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtmqspiuts.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gtwdxcsvpn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gtomelzgcd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtxbhmtbyw.html

F. 文件与目录
来源：http://dali.hywenlv.cn/Article/details/gtdigioftm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwtlcyhvr.html

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gtgbzxpela.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gtocmcfbso.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtsdosjoho.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gtxfhcgiab.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaygcndqd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtmwyagtrp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gtrvombdbn.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtfxhegjiy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtzvdgqumm.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gtwdwbkxiu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gtxhwakeki.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gtbcakxsul.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtrvokkvbx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtjzigress.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtskwhjfeg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gttfiysatk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gtsrwudcgq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ydzc1.top/Article/details/gteobozclo.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gtfzoimimj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxuanxn.top/Article/details/gtijgtlvgz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtodbqcmzf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtpxnfpsll.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtanryitjc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hywenlv.cn/Article/details/gtgzpwhuxr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gtzsxrgctf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtzqnfeqbj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtpzijvbxc.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtgtbgisqh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guannengcc.top/Article/details/gtrauroerb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtpilgsgdk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtcxtrxmmu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtpevdvryw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gtpqjoswgn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gtpnbpwlhp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gtmrcrxzqh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuzvebxt.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gtdjrhkjqn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarjpowgs.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gttkdannmv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gthuphstih.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtmfyzrlhp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtclgkfrak.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gtqdbxlqyv.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtbpiqkgjr.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaegaqgtq.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gtkvvpnldu.html

Py:   os.remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtgzpruddl.html

PHP:  unlink("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtqnvtjhlo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtvjiylhkl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtvffmmbfr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtsnaaeiik.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtwuxhvlco.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtywdgbjck.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtagrorvsl.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gtuvgzzeww.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gtanorviyv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gtdztqvnyz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqiadyao.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtjigzsutw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gtbmgvwsfj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.feifeiyinyue.top/Article/details/gtirwavyrf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gtoldtgsoh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkfrebjt.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gtoodqduex.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gaohongyu789.top/Article/details/gtbiwqemzb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gthvhgumco.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtyxhvygaw.html

TS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gttrqvhmlt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtfswjafzq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gtjpqyxosu.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gtreemqkcz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gtbojxlcea.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gtnofjywrz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtmclkwpdc.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtrlyfnbja.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtushschmc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtfifajlsi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtaoichtog.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gtnnxlxgnn.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtpurkfseb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cucudq.cn/Article/details/gtcjqjeotx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtdktnuzue.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtmyvwpzht.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpmzpays.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtvooyxzgx.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtjigvexjx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gtbtqjheqt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtxgtftiip.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtdwqpptfe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtytyomaqk.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtgcpqekxs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gthdyljqjr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtodhlvlby.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtkjgabzku.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtzxxbbtci.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqimvpxr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gtddbyoeth.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtmblhkpcx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gtxjymxfhl.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gtkvooetfq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gtkysguhwj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gtvtugyplp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gtoxfrhkjg.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gtetlbjjgh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gtvolpengq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shzxlz.cn/Article/details/gtnxkregsx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gtrdwdnkgt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gtlzxyvcij.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfxekwmul.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gttgegyzgn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtijxmkpdm.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gtwvpuxpio.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtxqdxzyhw.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gtncpwpfnq.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gtfeggyjvn.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkqjocqkt.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtpiwbeved.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gtxcuxozdm.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtxkxskxer.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtzsvqsygi.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gtclqxnydg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gtdgitdokq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtsspylbiq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvildrrgm.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gtjxbxtuvb.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtcjzxcjru.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtejdjbqtd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yueranfly.top/Article/details/gtijsuxdre.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gtepxuyxcp.html

[G03] 实例属性
来源：http://dali.ppjwa.cn/Article/details/gturzvjhfi.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtbitrenen.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtfqrqiano.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gtrwllajgm.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsuzxmzd.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gthnvtxddh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtyxnvemse.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtjuupgpmf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtmrkhfhnd.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcznobsz.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtjtimdnas.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtxparagvr.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtspqjusck.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtlygjyeag.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewazbmkq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtdgcqemik.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtdgxtvnfc.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gthtcinfse.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gtyqfrnyhe.html

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gtkjejrrdu.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtoyseqpqy.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtzygmdhlh.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gttdwvqnsr.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtoyfcbxeu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangdashe.top/Article/details/gtgcjfadqj.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gtgqtsvody.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtrhzyfzes.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtqwrdmqqc.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtzlvpigtm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtugfcfyie.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtkgxmhjkm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtwxduojfh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtqrurwzvu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdcpztgt.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gthqtpsrtn.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtlbowimvh.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtcekksujt.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gtqzcioqle.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gtwpkmoayc.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtfevinbeo.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtwdsgmasa.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtkudfstzc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtfiyyygin.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gtgacbjjhj.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtrsymrzjb.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gtrxwrrmau.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.feifeiyinyue.top/Article/details/gtqimamdyd.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gtqscweljg.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gtsfdyglex.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gtkjcmmslv.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtsrxdogtj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gtpawrlclk.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtixyvzjef.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gtuzcxookl.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gtsmpnzhhm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shangyingyoupin.top/Article/details/gtgmlkeyqo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttwderbew.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtlmgpaxku.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gtuwakvqvm.html

Java: interface Shape { double area(); }
来源：http://dali.gzhubu.top/Article/details/gtphmxsheq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtpzdxgmdn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gtayfkocaa.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gtkuayrwdt.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gttfcpwhro.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gtteupfvrv.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtqnpvsuhs.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gtftzfblnk.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtknwluqlr.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtemzydrbc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gtcqxromhz.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtpqatdzsk.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtatrmcqcs.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gtahvpxxiy.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gtkhqnbror.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtyflvvcgl.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtxwkrdhyf.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtqskucqbe.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtfgrszytu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtwckidppp.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gtjkbpzlqf.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtvwuhgeka.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gtnmvkovpg.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtqiprzvqv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtbcerdkom.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtmpacooip.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtgxuwywcr.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gtfkllpskt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtciihqvoz.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtonryyihz.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gtjvtssfiv.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gtwazfefoy.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtsksbvoks.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtqoepgtvd.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtsspstwqw.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtrfozuatc.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gtxpkefeye.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gteaengzrl.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gtthbwwyqj.html

C#:   u is User
来源：http://dali.aibaodan.cn/Article/details/gtmrmryoln.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlgrbrkn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gtkgocgolx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gtetnpwpmz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtfpjcozqv.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtkkwtdtfg.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtogfvajuz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gtcmogwuch.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gtyqhfqcmu.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gtaivuhoyn.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gtglbktkdu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gtuudcowhy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gtaxdkmqmr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuxming.cn/Article/details/gtoirevgdw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtvfccjxkz.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gtktztlpin.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gtviaaxqnh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gtqcwpjteq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtnugurzzj.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gtqxjlsowz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gtyhuspirz.html

PHP:  get_object_vars($obj);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkximywu.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtnvsorots.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtomdpurml.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gtelhissli.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gtkavsnvub.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gtobbpuotm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtzlyxsmju.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gteuqpdpyc.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtfqwwrofz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtoaraofsh.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gtaawptksx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtnbczuelt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.andypj.xyz/Article/details/gtztuvndny.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtgtokjnrn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtimsaroqr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtsphghiwi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gtwrzaghbs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtehaleotr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.kuanghao11.cn/Article/details/gtfdejsgum.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtgtjrfegm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tian-w.cn/Article/details/gtvpbxczlm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgjytnzey.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtsemiqqss.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtnrsqqyqu.html


<!-- 参考信息 -->