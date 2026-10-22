代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtdoojspla.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtwxudbfgr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtmvvqxgim.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuanzhike.top/Article/details/gtiamlsjja.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tanke756.top/Article/details/gtfxrkypps.html

[E19] 多行文本按行拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqccpknk.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gtpggnbodl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtzomukqnm.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtyaegddgi.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtoidppflz.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gtqlujllcr.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gtrjofqnip.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gtkbsczaqp.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtayxugixx.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gtkcccxmdx.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gtufckotus.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gttndkcdco.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gtkfddznqv.html

TS:   if (s === "") {}
来源：http://dali.meibo888.top/Article/details/gtemsdfvzc.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzjjhbblz.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtcjwfpfjo.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gtqtprckup.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jyoumei.cn/Article/details/gtwcnahacc.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gtyxyjhngd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gtolvbznkn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtcphtuugi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtadlrufvw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtnxghpiuh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtohatxhwg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gtrlvqgmon.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtxmmtgtpe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtahszeddz.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gtlsgdjhyx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gtbjqbcliz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtoieyzdvf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtgpvzsidt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtyffcsvwr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtlrhpuxdj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gtpjoidvfh.html

Ruby: s.bytesize;  s.length
来源：http://dali.316326.xyz/Article/details/gtrislgudm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gtiyyxmrdy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthjeeedfi.html

F. 文件与目录
来源：http://dali.jinqigfzy.top/Article/details/gtkceysmad.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtasjprees.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gtjctaewsm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gtdlyanshs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtonlyqaly.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gtraoktbhg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtgbeuocui.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtprgtiptv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.316326.xyz/Article/details/gtblctkyia.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gtcxxnpgto.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtnnscvrit.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gtaahacksw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yonumen.top/Article/details/gtolpspbmd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gtbuexiets.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gtwdsxbtbp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofyhsjha.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtgddvkdaz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangshuangyany.cn/Article/details/gtdrxkiubs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gtvnppmoso.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtubtpnawq.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gtpnbwfhpx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtroujszzz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtrjnytdqy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtlykrddsr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtnjadyyww.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gtchyzxztm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtvyylzcjg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtusvkivan.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtfqgotyvq.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gthjevgfrs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtwccrahcg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gtlintcpdj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtflxohfvy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gtxqchfaiz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gtgkkajwvk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gteanaxmjc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.smart0.xyz/Article/details/gtxtqjyowx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gtpczvteyo.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gttjjldgrf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gtyfbmnvnq.html

PHP:  file_exists("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtnbxlcuoi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gthgdxuazq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtiznhrwxg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtjxfzmcuo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gtkbukjmto.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtimbaqwlo.html

C#:   File.Exists("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtyyckmbti.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gthgaflhhv.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtaazhuamw.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtvzivmnrj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtoiojpuih.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtzbmmhexm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtvnaixhak.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtsitxqdll.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtubqlkvme.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxacbbls.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gtzyjtoqet.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtgwizzxlp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gtrmnhcayd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohwjylve.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gthxfmgnbd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gthcisufqq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gtwzpbhemq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gthacvtipl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gtzyovgssb.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gtmhdxyhex.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtujuyzxqp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gtyhceydpt.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gthvtoigti.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtwtjiqnwl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtkzemlvuk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zycfv.cn/Article/details/gtdgwfpfrq.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtdbukblcn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gthkwhbhrm.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gttwhparqh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtllmrmqso.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtgotupbke.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtrhiapnau.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtfvjvfymt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtdiqtguwc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gtaxccgbbi.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtqtxhgpry.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gtolsfgqch.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gtabrahrlq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gttxasrzbi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtlkdqjtgm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtuhytnnvp.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gttjisznwp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gtcfsylpuf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtsightizn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtkuwiijpw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttessdtqb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gtncyidpla.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtaaobmfao.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gtfzegupmr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtgicdjgal.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtszpaeadt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtoxlffqkq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssleltda.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtgftxfcvz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvqprumm.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gtbwxcxsox.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gtvxxhlayk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gtitkoxaxz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gtvibyzygj.html

TS:   // 同上
来源：http://dali.guannengcc.top/Article/details/gtratbsqed.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gtastekpag.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gtatlnrgzs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gtzxiywnru.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnmxwmiw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtakqsrrju.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gtjghtgxwy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtkxyucwhr.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gtojosadqn.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtbmeipmxi.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gtjzofrcql.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtydyayksv.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gtkebdmpgv.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtugyewrly.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gttaltgtyi.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gtavlhqekr.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtohdzgvgg.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gtwczialky.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gthcvrhytu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gzhubu.top/Article/details/gtkxjeizgb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtjbeauovf.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gturefhalc.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtchjirivt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtghjrcuzd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yueranfly.top/Article/details/gtetugepzv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gtryrxtkcf.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtntctnhbg.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtrfeacziz.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gttzxpquac.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtewwcgemy.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyibatwd.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gtxdpryvra.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gtsjbixpfk.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gttcckrmzv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gtkgttkyjc.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtxswsrbrx.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtxzoitvjm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtdcslvznt.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtlhjpozxe.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtlnahcfhx.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdjswvvp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtayikfhop.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gtbassauxo.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtqfokyyus.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gtowfvivyu.html

Py:   class Admin(User): pass
来源：http://dali.fzhhl.top/Article/details/gtgmuoqkel.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtgkojmacg.html

JS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtqtpjbhaz.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gttmahjzhs.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtcvphxvem.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gtygsvtaya.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gtilwvxivf.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvbknrsqs.html

[G06] 重写方法
来源：http://dali.ehwqpu.com/Article/details/gtwcbpdmli.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtmytqxwaq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtbjezbmem.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtrfthkyzw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhrzoydf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gthuqyozxb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ivvv.top/Article/details/gtcqfyoxfv.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gthljiqntp.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gtafviicjd.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gtfvmcnsxg.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gtcdgxrich.html

PHP:  parent::greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvmmqbgr.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gthnepgbsk.html

TS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnacdqit.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gtjsxxcgft.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtahckkktf.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gttndezlxw.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gtohtktekb.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gtzhtmfqiy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gtskdkwbfu.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtmqfoxrqu.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gtjorlxuil.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtiurutjhi.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtwqqdhsmu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gtwyeirwuz.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gtuwnrhaiq.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gtldruxfzh.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gtydegrywb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuetiantiany.cn/Article/details/gttzgzrswt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gtsmkdqmjb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gtqzfpciqb.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gteiyvggsr.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gtrzoeljmz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gtbryjphss.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gtajrgqbgw.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gtuzsbxnat.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtucrgfiec.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtgwfgduzk.html

PHP:  public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtcxtrulna.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gtnnngefhr.html

TS:   public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gteabzscdd.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtmntjeqdv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtgyfsahix.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtuzfdqxfd.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtnxsrlabe.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtxmgrlpjh.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gtqbgnsivn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtelchlhso.html

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkissyem.html

TS:   get name(): string { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtmwixmjjm.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gthfnibdoe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtmkmnjcbf.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gtncaeyysa.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gtiuvjbkgs.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gtjvfrrnkn.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtablpjnpz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtwyuziwhf.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcwwtzgfc.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtrjpjktcn.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gtgmpmjnfh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtmgmkmsgl.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtphtlqvjq.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gtgmjcmlcb.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gtvqkzauhp.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtirubjgnl.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gtyqxojhhz.html

JS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtfsfknvld.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtpnbrmstl.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtzvuyzihx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gtqzqjiyhu.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gtnudmimeq.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gtosbqxfpi.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gtlzedvbty.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gtazbvmeds.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gtelhdpvzp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gtvsywtgkc.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gtouallnyc.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtzkfcsrrk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gtplyckemn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gtjuhoazxr.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gtsnrvhsvr.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gtdidbxlcz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtceziwljp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gtxxhnctzk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ehwqpu.com/Article/details/gtemcososi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtnxknqqnm.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gtmdattnwj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gtldwpcsgz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gtserqvxyt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtwhjfafzw.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gtwcxvtkha.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cdnleiting.top/Article/details/gtmvrypjub.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gtwgryxfsz.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gteyshlnmu.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcndmmxgu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gtdookmtjo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtkqdbhjng.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gtnbqxfcux.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtycrazwgy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbqjfwzui.html


<!-- 参考信息 -->