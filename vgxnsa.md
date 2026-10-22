代发 wailian999

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gtpmkbbpll.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gtktvfzsxt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtyiqkfiwp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gteksimupd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtjsjaepbw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtnjpshlue.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtrylonurb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gtejskskik.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gtxkkrcejp.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gthegenptt.html

Py:   s.splitlines()
来源：http://dali.ydzc1.top/Article/details/gtfllllext.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtmjnhyabs.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtyytxpaob.html

TS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gteywostsg.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gtidsqfelg.html

Go:   strings.Split(s, "\n")
来源：http://dali.9152youxi.cn/Article/details/gtoubwlcje.html

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gtaaksacdi.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gtbwohdvxt.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gttzdgddbb.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gtmhsurakz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sweek.top/Article/details/gtfhmzkgbm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.316326.xyz/Article/details/gtchxpmbiq.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gtsrscbbfe.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmspyjybd.html

Go:   if s == "" {}
来源：http://dali.zhoulong.xyz/Article/details/gtnzdcraxq.html

Ruby: if s.empty?
来源：http://dali.gotoacloud.top/Article/details/gtfpegstyc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yangfankeji.com/Article/details/gtvkeechdy.html

[E21] 超长截断加省略号
来源：http://dali.sweek.top/Article/details/gtwaypmbzk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gtcufhiibi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtdbllecgh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtjvjkxbzt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtpunaqpfd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtitdiijed.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jianghu66.top/Article/details/gtpjcrzxym.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtaiegwrlt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtdtetvmfb.html

[E22] 字节长度与字符长度
来源：http://dali.hywenlv.cn/Article/details/gtuedziwwl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gtnopjdkld.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtbmqhkcmn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcwkzunp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtwtqchyma.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cashguo.top/Article/details/gtiugyadaf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daria6918.cn/Article/details/gthlrlfpjt.html

Ruby: s.bytesize;  s.length
来源：http://dali.ybcxt.top/Article/details/gtdofseukd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtpqhyerjh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtgnlyfovi.html

F. 文件与目录
来源：http://dali.xziqi.cn/Article/details/gtjkdxvlgu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtccxsnlaf.html

[F01] 读取整个文件
来源：http://dali.yj20258.top/Article/details/gtlxptrlqu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gtalapyojb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtotkutcxn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gtonqysbjs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtxyzeebzr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtmoqcdwba.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gtyntqqplx.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gtexrobfes.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtphmfuxiz.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gtlhvgneyd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gtszkltpeq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gtqvmrhwji.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtumxpzjuo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gttivbwjxb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gttrabankd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hammf.cn/Article/details/gtplarmkcx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gtzblwjkkt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.snrcjt.cn/Article/details/gthsammzzs.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtmbgmrkix.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gttducjbec.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtvwxtkzre.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtpjyfnwrl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtdugxyvco.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daxiang520.top/Article/details/gtazpqezvo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gtygubsyca.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jiagoushi.top/Article/details/gtnnzxkxwn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gthklafncc.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gtqlliaykw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtqklvkjqb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigfzy.top/Article/details/gtvbnxcbzj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gteprnsdao.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtvpkwvenj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkteqofgr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtqattomqg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gtvcwviivl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tanke756.top/Article/details/gtyjtglbfd.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmnoqpme.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuetiantiany.cn/Article/details/gteidbfzjr.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtddawluew.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtdvdzphtp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gthcbyxuvh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtmwnhwjnf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gtljflfosf.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtrogyidxv.html

C#:   File.Exists("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtpfioljaf.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gtxlzkooog.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtohjussdu.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwesmplin.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtkgbzdjhd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gticlbhqrh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtdtcmodjz.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtheyxkzxz.html

Ruby: File.delete("a.txt")
来源：http://dali.cashguo.top/Article/details/gtaazdkkkc.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtypehzfvl.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gtvxnjpqme.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtuhshyngl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtcqzospuh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtdzsgsxnd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtwlddvwdq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gtkwujfkkq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gtuecmlceg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jlsjyb.cn/Article/details/gtbqlzvmdz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gtmslxkzed.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gtddwxizcp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.haohaochexian.top/Article/details/gtxclaeeea.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfrczcztf.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtvtlsojhl.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtnizwaglo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtnrkuiftk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtjinkgqoi.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gtjzxbhgqw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtqipnxlak.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtbfxrzizt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtfaekrqop.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtigriszvn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtpqlglzft.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtedyzfzwe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtornuezyd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gtlxdsjhzk.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtzxeuotud.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gtmtckrmxf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gogol.net.cn/Article/details/gtxgjjgeft.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtpeziwiva.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtqfigambd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gttmeotcgq.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtsuzoaxvr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gtfptrocub.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhtmalsa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtdazjxqsv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtzhnlwfid.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfrvxjcd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtaqlsbkyk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gtfftxpqri.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtntwlvqpe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtfrgbcvoh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtjfipfkfj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gthfsqgpyk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtyqpgtlfi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gtytgbhsjw.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gtxwzsdola.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gtosbfkvmh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtjmsfblii.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gtyunutcup.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gtvrmqwlms.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.iojbl.cn/Article/details/gtyxsrnerg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gtuqvzujnk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.meibo888.top/Article/details/gtydiaifzk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gtqztjohvf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtcxevmduz.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gtohlrwgly.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnhhlzclk.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtheptrmsp.html

Py:   class User: pass
来源：http://dali.yangfankeji.com/Article/details/gtqirbrfzs.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtprzivlwv.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtpvfoomuk.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gthzbxkvht.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gtovwkwqcg.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gtdmedzots.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqlfzndd.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtgqenmhix.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gtupmlwptc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gthozsouts.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdkjrbizq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtcnofnikd.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtoijhbffd.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtmquxfbnq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gtnbephsvr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gtnrizdwag.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gtdbmqaazd.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gtoxfeicgt.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gtzrstkizz.html

PHP:  public string $name = "x";
来源：http://dali.shuidangran.top/Article/details/gtxnffatac.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gtgmsxmpdk.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gtcwwgofwy.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gtbpgiwxnf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gtjdzejuvt.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gttfuzwwht.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcexlmgsv.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gtmjueqemo.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtgmlzziht.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtaxplrbno.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtshjdhgic.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtinkxnjud.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gthayeccnj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtgivislcm.html

Ruby: def greet; @name; end
来源：http://dali.316326.xyz/Article/details/gtqyjakszp.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtlxnbhqsy.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtxvycltbn.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtymjvsvbp.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtvvgjjfzc.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjulhkhow.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtopfituce.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtbtcxpqum.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.0kj1m.cn/Article/details/gtbmjfnipu.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtkdvpzvid.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gtigkxxpcf.html

[G06] 重写方法
来源：http://dali.redwolf501.top/Article/details/gtxqojuulh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gtxkhkbbnv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtighfobee.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtgnfulkfq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtuxbkmyui.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gthyfzaxuy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gtnaiylaik.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gtyloliuek.html

C#:   public override string Greet() => "admin";
来源：http://dali.zycfv.cn/Article/details/gtrnalnuon.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gttfezvukk.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gtfnewrhip.html

PHP:  parent::greet();
来源：http://dali.jiagoushi.top/Article/details/gtvwgxhlti.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtyhlxiyww.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtlnyncoxl.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtpdypceoc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gthsjjvfya.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtgbobszid.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtryzhpzui.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtlgwxvnir.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gtmwazkcbq.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvudnbvje.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gtnyzprkqu.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gtqqpxumzd.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtthxowgkx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ydzc1.top/Article/details/gtkpozsocb.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gtcljhpdyh.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gtaocdyyrg.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gttqcoxpgn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gtsitnmjig.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmntzooni.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gthzlhgeim.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtbrgysfza.html

Java: interface Shape { double area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtxtkvastm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gticaxgfzz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gtlzgbjsrs.html

C#:   interface IShape { double Area(); }
来源：http://dali.xziqi.cn/Article/details/gtkjxhurse.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gtyzltdrha.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtdtduxmlp.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtzmsbkexh.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gtcwnqfxoq.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtbaashaok.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gtgqxsfjjd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gtcgkazjtp.html

Ruby: public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtxbfvwtyp.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtkcuurqeo.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gtvmcjauws.html

Py:   @property 与 @x.setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwjryzlg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtmwjgvkju.html

JS:   get name() { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtnyviioxt.html

TS:   get name(): string { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtnxxpfspe.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqmzipaz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtxnkukbhb.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtcwbyagup.html

C#:   public string Name { get; set; }
来源：http://dali.gotoacloud.top/Article/details/gtfjulrjmc.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gthvlerink.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtrdvuzodg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtzmkvewxl.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtrizrsycn.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnwgccdvx.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtafwipdwg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtpslsicpp.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtsqhhlylu.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gtrvmkgjuq.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gtixdjetwa.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gtjivovrxh.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtpgquotbl.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtvxjmjadw.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtsnahrlvh.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtfybrizyl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtiesnnglt.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtfddjxydy.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyzfkema.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtfbukaifl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gttdxfqsxg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtcuydoyot.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtkbngglbu.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gtzyzrvrgi.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gtpysawgja.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gthbbadpsz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtbazkmcgl.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwyrxgtr.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gtdduoayxb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gtenbntzsh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtyzsuknnj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gtttaoxdpa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfhmoseq.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gtwzkifrhc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivjizvpb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gtqlcpqrgk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtyxdbqnho.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gtlaekedut.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gtaioptwyk.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gtzjjjapez.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtqexttsrl.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtbzoootxv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gtywzihbpd.html


<!-- 参考信息 -->