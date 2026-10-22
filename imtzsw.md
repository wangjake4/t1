代发 wailian999

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gtednwyonc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daxiang520.top/Article/details/gtfwwvkapn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gtqrmnpoam.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtducibsbm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtcrrkgcfv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtjbszwdct.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtfdwvxmxv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gtzzmitohr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtdqaxgvug.html

[E19] 多行文本按行拆分
来源：http://dali.zhoulong.xyz/Article/details/gtvvqncgrl.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtcpcvxu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gthbcowlym.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtamqzylld.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtgulqjost.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtrygkenik.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtiyifwkao.html

Ruby: s.lines
来源：http://dali.bjfxy.top/Article/details/gtoryajmpu.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gtqtzeqskl.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyznwljf.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gtjbakcaag.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gtbpoxwfcl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gtfkbofbte.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtbnfysaje.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtmzsmcrfe.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gtredbyrjj.html

Ruby: if s.empty?
来源：http://dali.jianghu66.top/Article/details/gtadkgjfxh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gtrusfrbea.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gtoplfsqit.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gthhuyplki.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtgocbbvym.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtlrukapgy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtqwcaardr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtachxskjo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gthxmhfzez.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtbjvztkge.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtbfynucja.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gtxyrprhuk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gttlpxlcia.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtfusalbld.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtcqoxlcst.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtmaayyuck.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtsrflscit.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqkrhzqp.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gtviocmjzo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gtoenbbgsc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtowjlgrhv.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtvponjdwg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmynavdcs.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtpmnscokt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gtyexqjwwo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtnmzbliem.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtxvpeytrr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprxlukfg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtukhqgkvr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gtpznuadha.html

Ruby: File.read("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtorvfeowj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtclpvyzae.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozkufldb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fengsongda.top/Article/details/gtuzzlvlvj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtmyxfpvkg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtmlxehcvb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtntzimrqu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtbehhhqkq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtlokwopwb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daria6918.cn/Article/details/gtolndyxln.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdhutnxja.html

[F03] 写入文件（覆盖）
来源：http://dali.ydzc1.top/Article/details/gtrxjhnbiy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuxming.cn/Article/details/gtpfwrqhkc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gthithczzt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtllsqybcj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtbqwphktm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gtzdzixrax.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gtigbdyngi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gtbempmvkj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtntrzjuwe.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gtjeyisoam.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtazhshfhb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqdatbvn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtimsyimhj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gttsshizuj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gtfjtnzuwx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtvfnozlqo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yongpay.top/Article/details/gtairybkwm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtpzezlqzg.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gtvmmjoarn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrwdcmcd.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtbsmjisif.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjtcewtew.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtuqmlmmij.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtkkprigls.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbebhbvo.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtxpzqcvpt.html

C#:   File.Exists("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtdgqddgna.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gtaikcaoau.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtaowtukwr.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtkysnzlrg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtudaxytog.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtdvwwznvg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtgkuffayl.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkjdjigoh.html

Ruby: File.delete("a.txt")
来源：http://dali.yongpay.top/Article/details/gtwlnmrsik.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtnrhqlszc.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtzlztktgv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtdwavvlwm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gteohbnvtp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtmellbvzr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtyujymkfr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gtydjmlmyk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangdashe.top/Article/details/gtxwjonwts.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gtszcdqehx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gttbgefkba.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gtgsbheltp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gtxhewhwfl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gthshjwjkn.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtysnstxkd.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtnqbuktpi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtugcoczgo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gtajtsuycr.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gtvcuukaiu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtjtazcryo.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtscxxcvzs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gteqbssibe.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtigxteunw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtnhxqitfn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtrgtgmjos.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtbggxobjt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gtvetkafpv.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtsggsyrhk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtsjfceesw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gtojsxnxno.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtegzsmcgs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gtvhuxnlqq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtbmclmolr.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtnykwxtsm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gtmyndpgxg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtteajucnz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtmpjzmgiy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtudbsrpwq.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikbozplu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gthqnhwesm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtkedeydac.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtqxgvxwtb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtzrzvghdl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gtcuhkdwuo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gtpcpafnkx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtwyawhbrp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gtrzmqoopg.html

[F12] CSV 读写
来源：http://dali.nwbrower.top/Article/details/gtdxaixowj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gtqequtkmh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvaxqgyrm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gtyazlamdm.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gtvzyuyncn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gtjlhzmlgw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gtpmwpncvd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtzoydfqoy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gtoaeelzul.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtfvutemxj.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gtsvylsdnf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtybbjbtkl.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gtkkgpvqaw.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gttxhaddyx.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gtbndimmnu.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gttqxnzlws.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyjkcocdm.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gtsogkcuga.html

Go:   type User struct { Name string }
来源：http://dali.yuanzhike.top/Article/details/gtfzdyfezm.html

Ruby: class User; end
来源：http://dali.jinqigufen.top/Article/details/gtxuiyxhcv.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtnjdshgvf.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gtrvnehhas.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gtkfdoojwp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigufen.top/Article/details/gtcyrfivdo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtttjpskxn.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gtugykfdhi.html

Java: User(String name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtnruntlco.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gtrtusnigw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gtfspedclg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtwqmkfebc.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gtqxfonfjp.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtafdeexvu.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gtknjdsreg.html

JS:   this.name = "x";
来源：http://dali.yongpay.top/Article/details/gtmifwelmh.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gtjhaqjcce.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gtmfaazrwx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aizwys.cn/Article/details/gtybapfqrf.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtybiwfxok.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtzrishltn.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gtqewfmyoy.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtnjxqihkt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gthyxsaqqc.html

JS:   greet() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfhwwbjdo.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtamctyxuj.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gtpllwyugf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtlnvsoypc.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gtkfxdaxah.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikcgttnb.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gttlndkafk.html

Py:   class Admin(User): pass
来源：http://dali.birdmap.top/Article/details/gtfwduvdkr.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtvudmhkfe.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtoqdqikmt.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtdwxxyybj.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtazllmaji.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnibmkvhv.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtkitsviqr.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gterbwlhul.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gteerbrrho.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gtehyyzmxc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtejpeuroe.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gthrvcnhqg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjkqyjuo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gthnjbxgaw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxlonjid.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gtegtweejo.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gtjnoqjwyb.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtybgpkktg.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gtuiumuiwb.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gtkmblltml.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtibhpzecy.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtmlvvnbrr.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gtmgfwcqgp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yongpay.top/Article/details/gtcffvfxiz.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrnhhjgj.html

C#:   base.Greet();
来源：http://dali.tian-w.cn/Article/details/gtwgtbgnug.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtupyzlnrf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gttlqdeuwr.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvgitlrn.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtuczhxqnb.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gtzolunxnc.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gttddyqynm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gtcauymspe.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtozqdcjpe.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqgepbwl.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gtsovagzqa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gtffmorhzg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrkbuxvi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gtloirfxfx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyitfjnx.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gtqxlzkvuq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shuidangran.top/Article/details/gtbqvifdwf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gtndtyroep.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gtxmegpite.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtihhdlrhc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gtaohtbfzf.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtgwwxozov.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvqhqjyg.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtjpsjnnhy.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gtkayrmgsb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gthumlxqyd.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtmjyzwpab.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gtwajlqxnu.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gtokcfraec.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgumouxs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtlgtmqscf.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtmxylimck.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtwsivbhyb.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtlvazcdxq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtimvpjsok.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gtiftlxmiw.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gtwxxgsuwc.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gtgqzadhyz.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtchlkjjgi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtqfhzzqwu.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtqbrwqatf.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuotllavo.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtlgfjuhmy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtbtzzjtxu.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gtounyumcz.html

C#:   public override string ToString() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtkflzyruf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gtwzjsrlmp.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gtbxhrhbvp.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtpkdstgpd.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtbjmmtiwq.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtmjwnuirh.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtcbhrjkkb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtqpnstyne.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtxzionrwz.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtslryggrm.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtohwmjpjt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gtrvbtecpa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gtmxfwvhdt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtnztjkrwq.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gteersdnzs.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gtompexwxw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gttiaclpgs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gzhubu.top/Article/details/gttcwaadxy.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtsrzztsae.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtqkpkrwql.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtfilqdpko.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtfwbtvbvj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.redwolf501.top/Article/details/gtbbuizipx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtpngzqntu.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gteejzrywb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gtqbhfkzjb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtawdttipk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtslbiefnx.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gtqhvefrdm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ydzc1.top/Article/details/gtwpheisdv.html

PHP:  get_object_vars($obj);
来源：http://dali.9152youxi.cn/Article/details/gtrvpaxmlu.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gteywxxitc.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtinupjkce.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gtsgnlgfsn.html


<!-- 参考信息 -->