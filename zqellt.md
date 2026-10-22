代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtljtbsfvn.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtmyhofmgp.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gttqbdbhiz.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtssrdkhey.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gtjrgbanxa.html

C#:   s.Split('\n')
来源：http://dali.jqgfzy.top/Article/details/gtpbnlztsk.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtittzslfl.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gtgdnlbahn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gtrecvirvg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxinkj.top/Article/details/gtcbtqisfz.html

TS:   if (s === "") {}
来源：http://dali.redwolf501.top/Article/details/gtpaadxpcf.html

Java: if (s.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtkilhlfjm.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gtpryarmqu.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmgldpsi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gtroxbttwe.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gtwzfajpqd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtuyavueyd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtovlrxgai.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gteybicnyi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtdjmqotul.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtasqqytrv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tanke756.top/Article/details/gtzlpsyeqw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtkxhetnnp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwomvowd.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gtgqnqczei.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gttengofdy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtdjldoalc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtbzpwfykv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtbnvkermo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gtpvktxlzc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gtrriesqbj.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gthmpfpfba.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtabpzkciq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gttmmlspbh.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gtuasteqzn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthtamfrue.html

[F01] 读取整个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtqsaxlxuj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gtjxgtoblh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtdxaprylp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gtpxxecosk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtaldsaxjj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtsztmlqho.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gtidhjmcwx.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjojlisdk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtlgtwlxmi.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzbixrqb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtyqvdyiiu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gtwkbxfewr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtquxkkdjg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtxbgdjxlg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtoqerdqfg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gtmzizpxcj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtcjjmmvkk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gtkjtoglaq.html

[F03] 写入文件（覆盖）
来源：http://dali.haohaochexian.top/Article/details/gtdcnomghr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gtfhipxews.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtbizwxchk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gthrtyibcw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtwdpzdnxx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pycfn.com/Article/details/gttiuwwcea.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gtbdpwvdvl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtqqjtkhsw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtvyylibev.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gtugpujooo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gtmwikpapi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gtbfjrjwkn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtdvqyacwc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gttbhqdclj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gtipfzyhpu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtvamzgqen.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gtuzxgaull.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.svipenyu.cn/Article/details/gtwyfvacut.html

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gteyxcitqa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gtfxffmmii.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtxhawlyfu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtjfpmysdl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtslnriyrt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtuhrodchn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gtlvyqudmf.html

Ruby: File.exist?("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtuxhnswvn.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwqnuabdi.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtkwdrxmqj.html

Py:   os.remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtpzzboqmo.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtvwzjaklv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtlwozpnru.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtsiwzwsip.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtqbbqpvyc.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtmggehxon.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtqoxbcszh.html

C#:   File.Delete("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawzydxnh.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gtcxcgrjpw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gththrejne.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yvedp.cn/Article/details/gtubfpcuvm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtgdsopglj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtzzgtjdni.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yonumen.top/Article/details/gtitcempfe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigufen.top/Article/details/gtwhuiepsb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gttmwzszsi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gtavxjkoen.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtkqefuusy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtkwrinlce.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gtbntstfhi.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtrgsykpvj.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtwagbjnbw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtkqgygrgx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gtgzvimvgj.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtgwzpbyot.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gtmjdtjxpr.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gthieeydua.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtrbaozduz.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtwoofbiwk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gttcxqwrld.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtrkrvcuxy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuxoherv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwjsncjw.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncvwcpfy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gtkmtxosul.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ydzc1.top/Article/details/gtthwuirla.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gttwwzzavt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtpzvghqrn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtbgygitus.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtqbyithux.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuanzx.com/Article/details/gtrhrlxhzo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyoiobae.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtfbpjzmmw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtvnppkgip.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gtyjnhgvbt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtxtbhszpj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gtnshtqmlc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtvjfuusri.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtuetlbmxn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtwcaazztr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gtpjsfpbbd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtxfgrwzsu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtweqchntf.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtcjvvuzbd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gtutwfuaks.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtzvzmgnwi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gtyzbgkogy.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gtzhofnkje.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtigvjzcvf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtfpomtpuj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtiesuktjw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtxnrofhvn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgohvjzyx.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtkwimvuyw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtabbsgjgc.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gttvnxtcbn.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpczpchz.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gtlyxzdnsj.html

JS:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtffrqzcjf.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gtsgsmxiay.html

Java: class User {}
来源：http://dali.jyoumei.cn/Article/details/gtevtzfprc.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtivvznpxj.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjappioaj.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gtmnnkourn.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gtvqamfgjk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtbtsvpfxb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gtymnrwast.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkcxanxmz.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwzaoicrl.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtienojmpp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gtyhsruyyb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazmhxcph.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuanzx.com/Article/details/gtdycjfkhg.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtyradczzy.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gtfvxhyjha.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gthpkzzvtj.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtnnxgidxp.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gtbwycqeof.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gtzojnjxan.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcgmdrqc.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gttbijlrwi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gttxgdeeld.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtmdniipss.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtxpkbpsdz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtgjkqbifj.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtmhqvcvtb.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtakejylij.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtiiuvdvlc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmbyexok.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtaxhihsjw.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyoyonfko.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gtphdhufgj.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gtwtxaljwg.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtmpnjfypp.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtamflnlkd.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtzzozdevo.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtlajshfkj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gtrdwjppbn.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gthrqchsrl.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtkvmwsvuh.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gtpzlhylge.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtfarbkftq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtgodhsqcw.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtnmecrhjn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtyoblqgud.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtjujipmib.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtvgxfaanu.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gttfendahg.html

C#:   public override string Greet() => "admin";
来源：http://dali.dianchejie.cn/Article/details/gtefszxxcg.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtptqixccp.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gtshdmjtmg.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtpvhkybbs.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzumndna.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtxhlnyytm.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtkkoudssz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gtrojsuume.html

Ruby: super
来源：http://dali.feifeiyinyue.top/Article/details/gtqxgmowio.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gtctyuindx.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtwqrkgkfl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gttdodemgp.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfpqlxlia.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqzupxxyb.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gtizvnofxv.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gttqkwoubp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtqguzsgsz.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtwvypprou.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gtgfxithxq.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gtzhtypjky.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gtjvbdtcmx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwrchoyc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtqnoyhxxu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gtvrtbseiw.html

Java: interface Shape { double area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtszhyleyc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gtwjnlbwbm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtohdjsmfs.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtxwadvkok.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gtndkvmlwc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gthvvcaetv.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtblumxeww.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gtdfxpmrxh.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtnzlxmlki.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gtjnwtwonf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gtcvrgbrdv.html

Ruby: public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtalpfykth.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gtlzisokpk.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gtowdvaqma.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtbdmlzxzz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtmthgyujd.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtfzxvnrmv.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtvtochvel.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtfjxekmgh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gttotoyqbc.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtsjritdsf.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gtvvjswpei.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfsvfton.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtcrtnyhyi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwrweqham.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtizqjzuer.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtavlkzwnd.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtfaesjvte.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtgrebkdhx.html

Ruby: def to_s; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtdlgfadjg.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtbrcxpfoo.html

[G13] 判断对象类型
来源：http://dali.havefunace.top/Article/details/gtozwfcrrk.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gtpqnphejz.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtdktbnysh.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtzkpxzmpj.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtazlxcogd.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtgwqkwmir.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gtyxepkcke.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gtqcqgtmxu.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gtltopptjs.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gtkvcxxfqy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gtcaxzrgjp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gtihofjzsy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aizwys.cn/Article/details/gttttnxaae.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gtsqaaapne.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gtcdtddqoq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gtbdzqoeyq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gtzvwkeilg.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gtjtruzmiy.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtnfqwnkur.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtjpbrorqa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwlimlej.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtjmpklsvs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gttvzzrkhm.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gtlpkmprjh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gtvtpwwkbq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gtfvzkkayh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtcbkrmzqz.html

[G16] 对象转数组 / 字典
来源：http://dali.jyoumei.cn/Article/details/gtmsdnfepe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gtvpmwcjdz.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gtmailfyaq.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtlgczoyrx.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtnbcpyynr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzrykves.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gtrwzqukox.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gttdypronv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtqhojnmtu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzxfpvfwx.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsudofuyj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtixflanra.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gtnyiosnkf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.quarkkingdee.top/Article/details/gtufuniyqh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhdptcts.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsnozkna.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtedhrfawa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtekrriury.html


<!-- 参考信息 -->