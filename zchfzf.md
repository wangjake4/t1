代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yongpay.top/Article/details/gtczmvlxmv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gtiijmdaew.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gtncrpolno.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cheryme.top/Article/details/gtkowqascm.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gtxmncutiz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gtfjujgfpr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jiagoushi.top/Article/details/gtpmuwmdxh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtnjxkrlsa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtmfcqvnpc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtswyzvnaw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.316326.xyz/Article/details/gtowsfaicu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gtxvotdhez.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gtlmqzzxfq.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gtvxfvnjky.html

Py:   s.splitlines()
来源：http://dali.yuxming.cn/Article/details/gtpjdxvulw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gtdsgvuaxw.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gthjvkucnc.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gttvtzoekd.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gtyselofjf.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxuanxn.top/Article/details/gtxhnqgsbz.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzozbjgfi.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gtztyeaqzo.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gtaogsntqz.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gtguybpeji.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gthjjrgump.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxinkj.top/Article/details/gtatbxmrxk.html

TS:   if (s === "") {}
来源：http://dali.sufxvd.cn/Article/details/gtbqslyzll.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtmojefukv.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gtbaaubdqp.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gtbujtgcae.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gtdeegktyn.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gtsmcoqhdy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gthznoucze.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtyjkuxxfj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtkldimlju.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gttqlgrnli.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtdpijxdcd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gtkekfhqvs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gthxgdnszv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtgqanworu.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gtbwaavfxj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtzecehtgy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtbfjbgywa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtntfpwfer.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtodlxbqvj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlutqcvds.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gtoqrmbxoj.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtcjsxjgny.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtnzyeayhi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtbpiddnee.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtullvzpyk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwfvwxrya.html

[F01] 读取整个文件
来源：http://dali.ivvv.top/Article/details/gtvstymuwv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gtuecoiwgg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtnndyhbey.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cdnleiting.top/Article/details/gttwknjqxw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtcbklfjwx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtmmstmawn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gtkdcbxcnl.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtgyexwfhk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtkwkuhihd.html

[F02] 逐行读取文件
来源：http://dali.vqdsnc.cn/Article/details/gtgdkogwox.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gtmotmwqoq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gttylfgidc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtqitzglet.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtmcqovcgf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtvidwykmm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gtluzwebga.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gtvfncsbtp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtyfjlgsat.html

[F03] 写入文件（覆盖）
来源：http://dali.guowangkeji.top/Article/details/gttvjknjss.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuxming.cn/Article/details/gttjhrsxgo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtxveoeiiw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtryekmnjc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtidwcxmpn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtkxzdilue.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtcijqsngx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gtincwbaat.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtxogvlgsw.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gtokivqgeo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gogol.net.cn/Article/details/gttziujiks.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtiwayqvpy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymoqnobt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkizdkymy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gtdjgtgcye.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gthghmyybp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gtvliuurcw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gthmafogcm.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gtjgxiygfa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cashguo.top/Article/details/gteneuwvga.html

PHP:  file_exists("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtrudixbyw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gttnwdkjnx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtmatdzrzm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofvyyskp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gtnkqmtndp.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtosramrrj.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtzjaznhlv.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gtstjnghad.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtmxsoajdv.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtplwceamq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtsfchrezf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtrcqnaopx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtxwpduoke.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtcplhbgqe.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtjaggntbv.html

C#:   File.Delete("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtojjrtbbf.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gtbqhnmjmv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtwhrzuoay.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gtcwzzgweh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtpniuogde.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtipxllbhn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gthkjiyxaa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnqzz.top/Article/details/gtsyjpgeyz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gtvikkmiza.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gtaijhqfdj.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gtnnuartcp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwcjrrjf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gtqvfpprmv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gttkbwsavz.html

TS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtsukebfgx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtlamktsje.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gtbawinhjh.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gtuaialcky.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gtdfqpcjwb.html

[F09] 获取文件大小
来源：http://dali.wangshuangyany.cn/Article/details/gtcnybhdxw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumrxhsuh.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtqynncrtr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtkfzqgogi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gthfcooyms.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtrdxtoamr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gtxcghqfef.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtwatpkkqa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aizwys.cn/Article/details/gtstotlogp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gtqcumnwau.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtqpfybpdi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtrahtwqpq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtozmqobpx.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gtzlsvcqlz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gtkxrsxtwu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtajzzdust.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtwxacwkkh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtkspiqtex.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gtqgutwvun.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtmcixmvzh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gtleztgzzn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtytzwakna.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtkglpodyr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gteatomuyv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gtjolztzeb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtfyqnqjnv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gttugjttzl.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gtvuhiarza.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gtkhmtqvfi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.iojbl.cn/Article/details/gtswmtxhew.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtlcvhkvsj.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gtlvrcqwid.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gtiwirbudc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gtmefnkxhp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gtkuctbvnc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtjykyxpae.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtzatigxfd.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtykdduytf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpwxnhciz.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtdubzajmd.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtasqkyytp.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtpiywzsdp.html

JS:   class User {}
来源：http://dali.xinyue.icu/Article/details/gtkjbkwgaf.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gtnpgmebnh.html

Java: class User {}
来源：http://dali.aibaodan.cn/Article/details/gtnfttuxrj.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gtqdbtdaru.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gtabsmwqyj.html

C#:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfuyhqnpv.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gtbhjkvhii.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcqsvtbw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gtvzgqjskw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtrhvomvmh.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gtmygzgizs.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtzdtovvfm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gtabsrownr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gttbzjcfxn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlyivmta.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gtbnyfvsms.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gtqkqukedy.html

PHP:  public string $name = "x";
来源：http://dali.jianghu66.top/Article/details/gtzukhgduj.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtxgmwjbio.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gtvqjqaqzf.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gtxwaekfyz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gtxmdvemtc.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gthhtyghdg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gtdxdpggtq.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gtrodwmptg.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtrujnjhkp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtoasuiqub.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtynneljir.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtpltlnjss.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdkophtth.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfutfmeet.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmaipwik.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtlcfqehhd.html

[G05] 继承
来源：http://dali.fengsongda.top/Article/details/gtgokilfzd.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtxmhbldfz.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtfnmanvxj.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gthpmqislo.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtkygpdzqd.html

Java: class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtkiecdaci.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gtdecfcjay.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtfizkqvtr.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtsoeuavkz.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gthxumflas.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtbapjucwt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtmbvxgfqs.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqhcfphan.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtbbhkvskc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtoiikiqws.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gtjuzvrxum.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gtmfnjyrjj.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gttxgymcmh.html

[G07] 调用父类方法
来源：http://dali.cucudq.cn/Article/details/gtfepettxb.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gteddeqzmk.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gtuicrlbtg.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtgailjkck.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtmtcsnszq.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtdgkmtvzy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtmzbvhzae.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gttlluimoj.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gtbthquaun.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gtxvjmicyc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gthnazmjji.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gticzuvgsm.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gtgdmqqukj.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gtkcyxrfkj.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqffbtdu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvxfkjwt.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtexmqjpuj.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gtycdtsrpe.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtygqundtf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gtjhncffxr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gtmviylfkc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gthppbwgio.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gttpmkwquv.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gtgukfqpjh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtexpguqqh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gttzgqojxb.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtfbfirroa.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gttthvxhwy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gtbxhzucft.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrhcxbqf.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtgiaenoai.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gttkllhmsr.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gtibnehumd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gtfuspejax.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtygywpibn.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gtfrcjbrxr.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gtjteqmbxf.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjliqqfsx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtkxipxngu.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtukwhcekk.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtdobayhpl.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gtmmyjjmit.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnepefqq.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gtnuzpbwns.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gtaeehnrnh.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gthncocoaq.html

Py:   def __str__(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtbhlswucg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlbpconpk.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtylcooldb.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtsfgifklh.html

Java: @Override public String toString() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtmypkksgv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtxnuuxjtb.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtixqcpkou.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtgptfifou.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gttesozdfb.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gtafhrkhls.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gttvaebiwg.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtlclirnii.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gttjigffdy.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtzgzkmjjd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtgmtxucsj.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gtlotrmwoh.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gtxbfjvfpl.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsbqrxha.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gtiplpnqtp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gtymkjnjsl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fzhhl.top/Article/details/gthaueqxht.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gtthcwbzzl.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvklohadr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gtafworanr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gtihfcslpp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gtuduttqgs.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmbntxow.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gtexhzmbry.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gtabfqdrty.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhongyouzk.top/Article/details/gtpwjiigsk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtehaqwesw.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gtikgxavho.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gtdjxpsffa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gtfevyzcsx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtfygttzil.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gtkbyzqewv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtfpnhsoqm.html


<!-- 参考信息 -->