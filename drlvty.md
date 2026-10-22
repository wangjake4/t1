代发 wailian999

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtwsvfekkp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtbnincvyb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtaonmcogi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtoiwkuthe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtsgvqafvf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucxwmwcv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtibhxwrui.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gtuoylayot.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gtdtvhyoxl.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gtnidcvfaw.html

Py:   s.splitlines()
来源：http://dali.hongshengwenyu.top/Article/details/gtggvgtlru.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258.top/Article/details/gtxsynpkaz.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtpupsckyt.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtnkuanbgy.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gtliinbcin.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtjjnjdlhc.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gtzbdxhtit.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gtdcfdgcgu.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gtrulwnomc.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gtoxobbsbv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gtneezlvan.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhongyouzk.top/Article/details/gtjripvyci.html

TS:   if (s === "") {}
来源：http://dali.yonumen.top/Article/details/gtsqobuqih.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtktbtktqz.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gtylbbpkxr.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gtururzffy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gtzquykhvy.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gtmwuhobwe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gtxgnnxcdv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtdugstanc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtohrbfldu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gthnsznncg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtclcdqvjg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gtqikodcpz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtrfgxlpxp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtzoxgbsem.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gtinedjxtb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gtmuzssjnl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtqcijxemu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtfomifovd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gtdtdbwttt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtrpbgtlom.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmmjojcu.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gttozwhhjm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtvmqdwknv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqbneliek.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gtqqllxfny.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttgiibmag.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gthqiagoiu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gtgotwvtdc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowfmfuim.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gtupekfema.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtfchqsxye.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtgmdnuotl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gtohtongaq.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtuhmokgan.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtaqdlrack.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gtaqxhgjsr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gtqtdrnbfg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gotoacloud.top/Article/details/gtbezthlst.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlqltcvg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtersqgcht.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtkkzeukuo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gtkwfjykko.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gthrukwqgk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gtmefxpzqc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gtanpedpiq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gttkvjqswn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtelthijey.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtftmjasic.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtutvvxqoe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtwwujycaa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gtjvtpesbz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gtyimxocvc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtqpeeidzz.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gtnjxxlcxp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gtqwxrpocl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gttfyftnfx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtbewvnioy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtbxzttitp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gtldecgunx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtzrrtpbdt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aizwys.cn/Article/details/gtqipwesvl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.9152youxi.cn/Article/details/gtsklrwdec.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gtnupkuesm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtezbovfkh.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gthwtaoxgk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtfkobtqxo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtoatptdom.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtlutazmfq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gtfrvbvuum.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gthcagwmlb.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtrszdhooa.html

[F06] 删除文件
来源：http://dali.zdqjudy.top/Article/details/gtlmzogalo.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxhtzepz.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtvssgelyc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gthzwjyupe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtzwmrfbny.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtsvjigput.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtnjlswstu.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtjafkgcki.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtsitjwppx.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gtfpagegcs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gtdltlnhtf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gthvdyijne.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtcytzdasa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gttzyyqdvk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gtcxbczuyd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gtyumtpnpz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gtrbujnaoi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gtgdzhlotw.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gtckiowtwc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gtthoduuug.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gtbfeslkkk.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtuphmckxc.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtnanpucsr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdduiogs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shuidangran.top/Article/details/gtgoaaghsa.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvbhtewd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtaksepusm.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gthgfmpuji.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtfhzuxyeb.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtmoigkyif.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gthnumpdak.html

TS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtghzkxagu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtmvgjiqol.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gtstraikmx.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gthjzfyrhk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtsroicsbs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuanzhike.top/Article/details/gtlqhbotfi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnbzzrjc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gteswodxwi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtxmngabdq.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtaktgxtct.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.mhx1999.top/Article/details/gtmlugwaph.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtkcxxcctc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtaoofirtt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtwluquslj.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtblioveds.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtdhufzldz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gtwbddaqaz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtejkshjyb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtdmccgayt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtayqilomw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtfhbapqaq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtrascbcgs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtdslbzgkb.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gtdtfwdvlf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gtdvizdnyo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gtpoecqcuc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gttxdogugo.html

TS:   // 同上
来源：http://dali.c1oappe.top/Article/details/gtkqpuwmvg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gthnvgbcos.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtnakckprh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gtvtakhmez.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgufenzy.top/Article/details/gtakvbxnvr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtastosvzy.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gthwxrvulj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtcqyrvvhi.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtrzpuqsox.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtohifgdxb.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtyjhaomss.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gtvhnbuusd.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gtyxsgvjsx.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gtypgyfffw.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gttpkromir.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gtdkatvixd.html

C#:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtzdtdusze.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gtmxhvqlcz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.meibo888.top/Article/details/gtfiqtmmvm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtjkusfzgh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtudwfsbww.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gtcfvzfcpk.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtvmzvyrby.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gtftyfwznx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gthrjbnikm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgoxjivvr.html

[G03] 实例属性
来源：http://dali.dashuyun.cn/Article/details/gtrgpkxude.html

Py:   self.name = "x"
来源：http://dali.pycfn.com/Article/details/gthgarnchy.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtdxhaoyyn.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gtgcdpplib.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gtwxednril.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gtorqkivdy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gtuifvpuna.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtyhcefrnj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtakqjygrn.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtnbekfevg.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gtdhpnttcm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gttsyqrnhn.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtxdrysjty.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gttavdryam.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtwgetdqnf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtdgezzukm.html

Ruby: def greet; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtwmdtsizs.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtgjigfaiw.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gtgybhozmn.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gtefbtscfs.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtckkrhoka.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtegveddbw.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtwstszwmy.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtritxjgmu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gtakzukfbd.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gtrbouvrqz.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gturwjkysv.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gtppbrsqtj.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gtzpugadmb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtcmphkkci.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtrjvufnsw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtcwzhliie.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtvwvdejak.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.c1oappe.top/Article/details/gtzewkeckm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtjrqaoiyf.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtlndtxmvy.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gtblebgllc.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtcmnaxlqt.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gtmwqbyllt.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtznxxslyr.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtqpucacpe.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtbvdajnda.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gtjkcbfsst.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gtrxsvyinx.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gtzqyljugq.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gtyvocyson.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtedvgxmdn.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtrsxnqour.html

JS:   static f() {}
来源：http://dali.shzxlz.cn/Article/details/gtwmmrtcfh.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gtkojbxvpg.html

Java: static void f() {}
来源：http://dali.xylfe.cn/Article/details/gtszswyzoy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gtjvtdfnby.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gthwdrnarr.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmhfxyit.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gtwmofvnep.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.svipenyu.cn/Article/details/gtqfzbhgqg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgufenzy.top/Article/details/gtwfbylwmi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gttybqwsya.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtxfhiljze.html

Java: interface Shape { double area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmzjbscc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gtdobmrdru.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgfzy.top/Article/details/gtlfzbfxzu.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtehsmyuqi.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gteetacswc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gtuuoreufc.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gthncodspw.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gttvbfubke.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtoiicblom.html

Java: public / protected / private / 默认包级
来源：http://dali.dianchejie.cn/Article/details/gtkapjecrs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gtyhmzkomw.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtdbxqkpxn.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gtbvwkoxzy.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gtweefrzjy.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gttbbhvhks.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gthjngursr.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtyrhjcjmn.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtzcgblyry.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtvcktddvc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtlkcytqbq.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtlttoeekl.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzpqihfe.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtlbpjqbuw.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtjjojulti.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtyllxrl.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtynagfwal.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtoymqyzbi.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtkjsnidlc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkktoevmn.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtfkuvlarb.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtpzopoxrm.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtwhhmvvrt.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gttmfnvqhs.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtjzkdvvyu.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtwohlyhie.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtikqxqumh.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtvegwglqp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gtqhxyucil.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtsueluyuw.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtxmddhvrp.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gthqkldbcv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gtbpcmlxfm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gtyegjwasj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfcgblyx.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtyyrccghi.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gtrcctoznn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtlrmzxjru.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtbggtfbtr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gtykmxiikn.html

[G15] 枚举
来源：http://dali.yuanzhike.top/Article/details/gtxdbdyphy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtljibjkli.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gthoiyehvd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtfdpaqbob.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtcragpkxr.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxsfwlpp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.vqdsnc.cn/Article/details/gtpomssikb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtjitygymz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtclikrvix.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtblhxjehu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gtnbbkeuvy.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gtydscocby.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtniurnujv.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtypewkdrg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtqmwtqscl.html


<!-- 参考信息 -->