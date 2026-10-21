代发 wailian999

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gtqwfufrjt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jianghu66.top/Article/details/gtdwknvdln.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtgfpernss.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtuxjpavoj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtywxgglhv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtcijqrnby.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtucygveeo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gtqvkzrejy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dianchejie.cn/Article/details/gtlhoxdbvx.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gtrzercasu.html

Py:   s.splitlines()
来源：http://dali.sufxvd.cn/Article/details/gtdhlmwgnm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtjprzknhi.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlukzxbss.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gttnfgpifg.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtzlcduxfq.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gtxnljyucn.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gtfzvewkwp.html

C#:   s.Split('\n')
来源：http://dali.sxryk.cn/Article/details/gthqibcsin.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibzlxmoz.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gtekrjjpjz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gtdpczwocn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gtenoaabct.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gtolodmbnl.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnwkmdmpg.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gtvcwjlobf.html

Ruby: if s.empty?
来源：http://dali.snrcjt.cn/Article/details/gtteqvuxmj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtzndtuojf.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gtjtgnepjo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gtmabdoata.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gteqxxkuuu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtcqartwur.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gthllwhtet.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtzvjwnelo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtxttxwmue.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtszgidwle.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtfolajhca.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gthtgjyjnt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.andypj.xyz/Article/details/gtoggtopgy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtqjbvrqeu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtsfkdiqck.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtosmtuspt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gtgnauxvoa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgfzy.top/Article/details/gtlfumoczp.html

Ruby: s.bytesize;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtjwmgusge.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtigyjejqi.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gthidqqrnj.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gtfelksbgb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtaqgmuerk.html

[F01] 读取整个文件
来源：http://dali.ybcxt.top/Article/details/gtaqbkfnja.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtngyflihg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtaekagcuu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gtptczjufr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtwnzghnlk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtspaqnhog.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtvxbilgpr.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gtdsqqupvg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvtptuik.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtdtlrnejh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.c1oappe.top/Article/details/gtqlridvpd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gtiavwyqgt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtarzawcmd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtpkfjmpxi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtuuiqajlq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gtegbhotjg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjghyqiz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gtjnsogdse.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtnvjhcnkv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gtzlnyurfi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtoulminde.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtvbuygzyu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtucrwydqj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gtqjubpowx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gtrnphezzw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gtyrgpxqvi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gttwnweikd.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gtsizhfiro.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gttcajstfu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqfssdpo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtafbhzfws.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtokftfowr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtaeojipfo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gtmojubrzg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gtiaxpxrun.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gtgbvuakaq.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtmiknpqqc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shuidangran.top/Article/details/gtdonpxquk.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gtribjvdnt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gttfvgytdf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtcjaqgfpq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtvgrkzvdr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hammf.cn/Article/details/gtrvhnqymf.html

Ruby: File.exist?("a.txt")
来源：http://dali.cashguo.top/Article/details/gtomcbjzfi.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtkvtdjqof.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gtqxfjouky.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtdpwtpzza.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgphmvno.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtgredmmzo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtvwfmxifa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtqshmiyno.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtmgwpqcya.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtqyffxkqw.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtlgsknklf.html

[F07] 创建目录（含多级）
来源：http://dali.jqgufenzy.top/Article/details/gtvzgjmowd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtpxuqxmbl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtqvfqypjn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtcskteycg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtykpfbyoe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gtohmumfci.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangshuangyany.cn/Article/details/gtfkpfipik.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sysykeji.top/Article/details/gtjduvstca.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gtncklnlaw.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxtfgwwe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gtzqshtbts.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gtsscjhena.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtrjceierc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjobmdhm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtkkkbxwuw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gtbdvbvgat.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gtgpxfjmal.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gtlacqgfpv.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gthwpgpenw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtptojybpb.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsuquylm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtnomfccem.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtktloqmbe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffhziwjc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gthwstihbj.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtcbpbhess.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gtljswfngp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gtrrbgiyml.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtllgsxvqn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtuapgxuly.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtloqldras.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtgxnjtrxa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hywenlv.cn/Article/details/gtxahqpbjn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtmkblfimi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtensimdci.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtgneivouy.html

[F11] 复制与移动文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gteadntuaz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtbphlgxpw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtlrgempfq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gthwvrxrec.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtbxrdnuuo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtklzhmtsa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gtqiywyves.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfmwrjpjd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtvnmkkmhd.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtoohexwbg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gtdafxwucf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gtavbsagfl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gtoczlerlt.html

TS:   // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gtpniqlogh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgfzy.top/Article/details/gtrtosnmds.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gtwowdymif.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.haohaochexian.top/Article/details/gtoxkzfxwv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gtycarwgmw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtjiquwlkp.html

G. 面向对象
来源：http://dali.zhixingplan.top/Article/details/gtwgwftbre.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttxogqwgd.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gtkevflrue.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtiagffpjg.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gthgejvcrb.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtueohkenu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gtqldkznvl.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gtzteyzmtw.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gtdcmchufq.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtmfcqwlsb.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtlmchmzfm.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gtvoyhrfgf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gtirzwxorb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtxncyhqlq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtupkjfkxf.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gtxmlwlhcy.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdqflkrhb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtjrtuhhsa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkokjaig.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gtsdswmsla.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gtvtjpwypy.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gtceacdlqz.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtpinlakjw.html

JS:   this.name = "x";
来源：http://dali.yj20258888.top/Article/details/gtgafpuabh.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gtanvjxjpz.html

Java: private String name;
来源：http://dali.zdqjudy.top/Article/details/gtgjnfrlbc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtifwbbfga.html

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtwesuwsqb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gtvyxgxtgu.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyssjfmnr.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtoeefvgpv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtilkatdcb.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtonohpjrq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtxsacttzt.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtxoodaoui.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtajhskeqd.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtaljaqytb.html

C#:   public string Greet() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtbsewkxed.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gttjrdzbsl.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gtbvewhsmt.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtgamvyvat.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gthjozshri.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtltljepxc.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtkhiuplra.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gtuztxigvt.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gtcqjsjdgr.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gtjmlmzawb.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtykzpwrge.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gtochtbjie.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhaskqzo.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtjmweiwax.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbkndesyl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtctrvaxhr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gtdfqwiftw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gtbiowgvao.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gtbmxsjxki.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtcwgzyugo.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gtcrrwlzyc.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtiwbdqdcs.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gteasecvua.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtefkoswdp.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtcazwviex.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gtnghqccvj.html

Ruby: super
来源：http://dali.gotoacloud.top/Article/details/gtdtkqtssw.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtmosupqaf.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gtohupcpaw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gtdsipzeqz.html

PHP:  public static function f() {}
来源：http://dali.ydzc1.top/Article/details/gtvdfliaox.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gtxpwqulmi.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gthxtyzrzw.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtaqbqeoij.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gtjuqvpknk.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmmhfymb.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gtygoudlyw.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gtdheiqfvx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gtkuoeeuet.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nwbrower.top/Article/details/gtqmfcedfc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gttzuwlpzn.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gtuhvbmlrz.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtpjbvczuu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhcgtyxd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gtlbysgsxq.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gtjsliyzkf.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gtgjrzojoe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtigozwevp.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtuiouwval.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gtswxzezhz.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtabvpnwpr.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gtzamtxccp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hammf.cn/Article/details/gtmtguzeys.html

Ruby: public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtuvjvtvfr.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gtldopylbg.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gtpgbavewo.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gtgtsfavpf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtbbyklmwl.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtkkrxxslh.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtmiuaismn.html

Java: public String getName() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtzfyhivok.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtjoayiysl.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gtaucvlyae.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtvctcvlzf.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtriclixzk.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtblgnhlzq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtjoceqbbt.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtntxgaics.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gteqsgyooo.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gttzgrctqx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtwcfkiazz.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtejqgeayb.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtktlftcll.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gtumbquogk.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gtpwtyphtj.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtcjhluute.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtajcxajro.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtgsjcfpmw.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtdcmmovww.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gtsuyfanjx.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gtcwinypsk.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gtqinkxhlx.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gtqujdvqow.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtujaxeuxn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtnejvviob.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjmmxqnb.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gtiwlaxund.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gttbozqeee.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gtpnrzfuux.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gtmufaktpe.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gtbfqcvplm.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gtenuzyaer.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtlwljbqzg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gtlnpnytya.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gtumobqpkc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtzfgwnpab.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gttoiytgna.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtadtitstx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gtjctvzrkc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyiqcxtd.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gtbqdpgojx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gtwhgnphpp.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gtolzomfrg.html

JS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtqmfzkjhx.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtribrcuux.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gtghdzohfu.html


<!-- 参考信息 -->