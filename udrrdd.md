代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvgemygq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtjuzaorzx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtgwvxraie.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gtniaciptx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cheryme.top/Article/details/gtopyplmxk.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtxypuefga.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gtvjvuxjoo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtwqavetuw.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtofrmdwpt.html

TS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtfdhfcpgi.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtptucepak.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gtwfeaqola.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkukrdaa.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gtgofkiznm.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gtltgziepk.html

Py:   if not s:
来源：http://dali.aizwys.cn/Article/details/gtxrvdfvnr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtysbgrffi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gtdvqckcru.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gtigheffms.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtiptdjxmd.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gtsrqejkzi.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gtrqydjncb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gtmvdvhagq.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gtgqtcsgkq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ppjwa.cn/Article/details/gtgrhjmmax.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtraxunsdh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtressajhp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtiwgleopg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtpyyewnjs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuxming.cn/Article/details/gtvnzwedpy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtltoezovc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtdmbicmns.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gtotcjraon.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gtvpflahqp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtjbypvneo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtnforbvbh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtuzenztju.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gtjtoyjsux.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gtybixxeby.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gtxjumlkcq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhengqikj.top/Article/details/gtfqrzncpc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtobndcrvb.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gtnymayatb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtecofnszi.html

[F01] 读取整个文件
来源：http://dali.xuanzx.com/Article/details/gtzkqjfxwv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrbhdpat.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtjogxqazv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gtmvyonyrx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtaiugosfq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtnlwoegdg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtmofjwkdb.html

Ruby: File.read("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtuufllhbf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gttuqximuv.html

[F02] 逐行读取文件
来源：http://dali.zhengqikj.top/Article/details/gtyzvfcxpz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvnriaod.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gtyvyfkffn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtofcezazd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtywdksydf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gttnvksfuk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtmsnvbctr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtukxgkvrf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpolcjyjy.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gtjhwwslvd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gtsqcnzwqm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtfqczrpbt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtulgcbbxg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtfxmhhdyg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtygouwqkd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gtvzbyezsq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ybcxt.top/Article/details/gtlcsqibkd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtebjsluwm.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtendjqzfa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gtqdtrgshc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolpsopbm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtkwzikjzz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtlqxwyyeo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddyiiggh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gthchndqrl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gtvwnkjhga.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gtouirpceg.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtiiogpwer.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gtwmyixujj.html

PHP:  file_exists("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtqbrzuzqm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtafglissn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtipltrfhw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gthufaclbo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gtwjdqwwcl.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtumoyfirg.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gttegqercp.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gtonmwkszw.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gthmfmwhft.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtwwmfhosh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtoyklqkqr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtyaaowvew.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtfwmtpugj.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gthzrqhkwl.html

Ruby: File.delete("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtlaqwepsw.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtwqjgtiqk.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gtutiicdew.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gtgbtkamod.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gtpfnnsdwg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtfccldlwd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtcnjgesps.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhixingplan.top/Article/details/gtanzsetpd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gtooocbehq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gtwrgdmxye.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gtyvfvmihm.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gtymhvtdwn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gtvmcduhps.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgufenzy.top/Article/details/gtsldbiioj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvspgchb.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtgqudwhqi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtbbvjxwvt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gtkzoyohiw.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gtbbefhnvj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gtajjhhjkd.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gtbupdgxme.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvnngkgp.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtniygxagq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gtugcpmbrf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtmtbrxkhl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtygtkctsp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gtwgrnjeju.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtyqagajcf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gtyorfjcba.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtetwnfsdr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwpdouewl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gtxbkqyuai.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtwjhwcxcq.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gtooywwmxc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gtyepuedol.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtjsfomzgw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtoxhikncj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtbpwlhvkw.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gtfyycnyir.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrqdinsj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gtuoxlzqje.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzzzaynlp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtxzphymec.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtxaqxocbl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gtqltxnyrh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtupmrlled.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.kuanghao11.cn/Article/details/gtrtowvhly.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gtedpmscvu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gtenutnmnj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.vqdsnc.cn/Article/details/gtptkfwxdx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gtckpmkcva.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtekeusjlc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gtmnasqvbo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gtmhygizhk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtqdurhmgn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gtixiebjjs.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjdhilhn.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gtrrcqypcj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtishtlgqu.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtnlpnfrgg.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtziyultcw.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtwhcvchiz.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gtlkmymmee.html

TS:   class User { name: string = ""; }
来源：http://dali.bjfxy.top/Article/details/gtvyxqrhrr.html

Java: class User {}
来源：http://dali.aibaodan.cn/Article/details/gtucijfyxh.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gtsqcjerlf.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtxwkgmows.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gtojdkfjke.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gtiazqguvj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gtskdtqyrl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtwwheefll.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtwxfpjljn.html

TS:   constructor(public name: string) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsgelhym.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtoytuxjrd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtoyuekruh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gtnyleuxis.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gtdpdmocjh.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcnyxghq.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtrifezwrg.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gtqperruhu.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gtitwucsdk.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gtjzrezbti.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gthqvmxkvg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gtgbeevxxu.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtimjrtutt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtqmebbapk.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gtkyzbquwn.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtmbfqjrcv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtfobcsvrs.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtidhakake.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtgcddiaup.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtedjhqkuv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtaaupfhoa.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gtlboaydcy.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gtztejazke.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtasjrkdny.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gthgmzpydb.html

PHP:  class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtopxweyzr.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtdmqpxukp.html

TS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtnlwwwhwu.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtqrzlhtcp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtaixvffzu.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gtnuxcdeej.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gtqbhuhdgv.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gtpwnvjuha.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gttjmczmsr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtjvdcjeds.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtjlnvvmrq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmazuqexs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtukaacaee.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gtipyjctje.html

Ruby: def greet; "admin"; end
来源：http://dali.iojbl.cn/Article/details/gtvyjugctk.html

C#:   public override string Greet() => "admin";
来源：http://dali.daria6918.cn/Article/details/gtpwpvrkwl.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtlnmydhce.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gtojjeeqag.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gtlqqphnen.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtqkhfrzth.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtmfasjwfa.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjecltcqy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gtaamgxanw.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtipdgzyje.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gthepjuwja.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gtzahnuidl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gtxtfbvmkb.html

PHP:  public static function f() {}
来源：http://dali.gogol.net.cn/Article/details/gtephxetzo.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gtojlhdbpy.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gtkajusopw.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtlhbnhjzg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gtwyycbyuh.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gtuajbfzsk.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gttcfmuwll.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtdqwllbeo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gtakxwnbfd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gtyeifglxi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gtexsrmcqd.html

TS:   interface Shape { area(): number; }
来源：http://dali.xziqi.cn/Article/details/gtlobcmxae.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsonmach.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtwhmcqgpx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtociisrqf.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtemfwlkyo.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gtvbxeacqt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gtfppxmnov.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtxdcbsmdk.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gtujhxxyyn.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysdyviyw.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqqklqiz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gtapfrxiqz.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtcvvesmxz.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gteespjhhz.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gtzutycupe.html

Py:   @property 与 @x.setter
来源：http://dali.sysykeji.top/Article/details/gtqffzesma.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtbtdrtocc.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtliyhofkj.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtokootaro.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtmsvfxycb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtwtoaacia.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtgtasizbf.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gtonkjrlve.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtuesmrdyc.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtoazknylk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gthmsblhmj.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtuhsygvhd.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtmejumbap.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtjlstnuih.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtarpyimuo.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gtxfmrefwt.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gteonqimtj.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtrgrqktpb.html

Py:   isinstance(u, User)
来源：http://dali.yueranfly.top/Article/details/gtocvuvtfa.html

PHP:  $u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtmvpcqkvu.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtjaoqdznf.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtjgqrszns.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulzkpxvj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtbynjohpg.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gtgadkicbv.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtlrbqhoeq.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtyeeijezb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gtnwmlmiwg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sxryk.cn/Article/details/gtmkayswpy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gtkhuevunl.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gthrpcrntl.html

Java: record User(String name, int age) {}
来源：http://dali.yuxming.cn/Article/details/gtehedlaeu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jianghu66.top/Article/details/gtvensevzz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gtxigejkou.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtwllgliph.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gtxytqctuy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtouissaww.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gtpoxcnnay.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gtehlgbtrc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtqxjlirwg.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gtoxdsonla.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fengsongda.top/Article/details/gtjwamzvlb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gtqnonkewy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtfyyrvmoj.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gtkbtfqter.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gtebmuaano.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gtgsqsxvgi.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtckjygxdj.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtndyvsiby.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cdnleiting.top/Article/details/gtignwxqna.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gtkxntejmq.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gtktrswhsj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gttjhzunlj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkevjoegb.html


<!-- 参考信息 -->