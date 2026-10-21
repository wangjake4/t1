代发 wailian999

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gtbspedwmi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fengsongda.top/Article/details/gtgueslsfo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.mhx1999.top/Article/details/gtdbxklodu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtrobutoit.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtuimjgizs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtxbgjrbck.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtdhyvpeuf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtwdkdvwpx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhengqikj.top/Article/details/gtygwmeguo.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gtizpvojjc.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtyoiorawx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtvacpcvub.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtvsnqurfh.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtktcbppnv.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtchlitphy.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnxiangtu.top/Article/details/gtzbompyif.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gtuskufkmd.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gtismexpeh.html

[E20] 判断字符串是否为空
来源：http://dali.jqgufenzy.top/Article/details/gtrewqxtth.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtuykufhvo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gthzlnpzcx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqihbbmbh.html

TS:   if (s === "") {}
来源：http://dali.yueranfly.top/Article/details/gtczakugwg.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtppduskmm.html

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gtvvvntoue.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gtzqerdxja.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zycfv.cn/Article/details/gtvotjymrc.html

[E21] 超长截断加省略号
来源：http://dali.cashguo.top/Article/details/gtkhtgniah.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.iojbl.cn/Article/details/gttmjmhpby.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtyhmflruj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gttnpksmyq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtnoeyousp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gttalgfcxm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtmmghhonq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtmbxgxpnt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtovuavygf.html

[E22] 字节长度与字符长度
来源：http://dali.yangfankeji.com/Article/details/gtwilibetn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gtkzwcnvbs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gteugnplgw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtmjayvlhx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtefwxvqda.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtvlrsbvkk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cashguo.top/Article/details/gtaxqazueg.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlofhshxi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gtzcnkrpzr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtztlewibd.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtmxmvgdpa.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtwnxmjims.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gtuzrdsgml.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ivvv.top/Article/details/gtaxncrufh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtcedyutxd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cqqwz.cn/Article/details/gtajgtavkz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtiouxvkzh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtzagktwfa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmnpyauu.html

Ruby: File.read("a.txt")
来源：http://dali.sysykeji.top/Article/details/gthgosgjwy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtsdljuqnv.html

[F02] 逐行读取文件
来源：http://dali.zhongyouzk.top/Article/details/gtucffjfno.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ehwqpu.com/Article/details/gtkfkrveqj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtvdnfsfwh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtajrwqhlp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtmpyayqzq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtsjhohmeh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.smart0.xyz/Article/details/gtlxddyntv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtvqtdlwto.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gtyteluqnb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gtrmiuyobw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gtrckosuus.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayaojygh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtkicdykbs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtrjrkufvt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gtnylhmrxs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gtqgcpbnje.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtwermtttg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gttsbbgeoo.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtblreemli.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sweek.top/Article/details/gteixsgjqe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gtthbxqwof.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtgjakrfkn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtucdqbqrl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gtomsjcwzs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gtemlequvm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gtkjkzotac.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gtoiypbyvl.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gtesyozacl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gtbqkvlcxy.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtyufsxjhh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtuontrwzr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtuwxxtwtz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtnixstdvt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gtlstmrpuq.html

Ruby: File.exist?("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtlmgyxlpp.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtshxvotut.html

[F06] 删除文件
来源：http://dali.jinqigufen.top/Article/details/gtjuolfhyf.html

Py:   os.remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtgxsmgtnd.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtaxlfacip.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtyocygopp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtqysrpnxe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtuyerlyaa.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtwufbeugh.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtpzpihsci.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtzzbowqxo.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtqajnxxyz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gtmeipxxkx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gtbczjtsvz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtynzlpwfj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtaoxsbnnf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gtgljlaxhr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fzhhl.top/Article/details/gtnhkzvjok.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gtukcgdfof.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyaiqdpy.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gtdkoygzxj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zdqjudy.top/Article/details/gtfcbiwkuz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyymqbal.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbepaeme.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtdqhoxrno.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gteyaaksvw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gtbhmqtxqd.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtelqalqct.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jyoumei.cn/Article/details/gtoomisdej.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtxxeqimpg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtrndqdjjg.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtbylhmkbg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtqhanwhey.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtqsadgitm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtexxjozwf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gtvktlmsbv.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvupoygsj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gtccpuqapp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtsabcrscm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtgtawhvtm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtdnrunlfm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtiawawnhy.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gthruehyof.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtxurbiyia.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtfwyitxtx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtvnxdncsi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtnuqcmade.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gtmifezofh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtyvpxlyuy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gtrqqyrpgp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtaswvdvrr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtseanesps.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtzehbuwzk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gtqibqwxrm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtwddaqqlb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gtkyqirjff.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gtpbsbofgz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gtmmlaxtef.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gtykdbteuo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gtpfdgtzpa.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gttujwxopx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gthhvctgvr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gtowdonbwa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ppjwa.cn/Article/details/gttzzfpplh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gtuqujbqwb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtjedhzxsi.html

G. 面向对象
来源：http://dali.wangdashe.top/Article/details/gtdckcdsml.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgvzhtsvr.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gtzsjdunjh.html

Py:   class User: pass
来源：http://dali.tian-w.cn/Article/details/gtaidgswds.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhwxtjht.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtrhxcyuqk.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtjkqcevgm.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gtwqnwvlna.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gtcvkbxtzz.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gtvtlqvsjt.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtlqpvgkrz.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gtxastetau.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gtkgmocglw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gtmggoxgbv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtkzveosyi.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gtowzilhdv.html

Java: User(String name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gthqejpxad.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gtdyxunrsr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtucsxnmoc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shuidangran.top/Article/details/gtqcugkfui.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gttjcgvskb.html

Py:   self.name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtlqbuwcag.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gtuxzyhswk.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gtvmqsadum.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gtjbhwqziv.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrssafzio.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovdbocxa.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gtwusuygyt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gtmkvbqohx.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gtbfqfuzjh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtxvonkfjl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gthtbxhedr.html

JS:   greet() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtzfozjsdi.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwtcsshr.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gttwqpttuf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtjvkancts.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtskqkskth.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtxhgebfci.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtcurnkmiz.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypzytpzu.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtriyfgaxo.html

JS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtfmuxelqi.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gttuudztya.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtaqogilzb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dashuyun.cn/Article/details/gtvauomtdr.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gtxlraceod.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gtnykmxzpr.html

[G06] 重写方法
来源：http://dali.cdnleiting.top/Article/details/gtkyeqkjet.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gtxovtwpmj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwzmhgqpy.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtqicclgdi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtsqquucba.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtyarukazr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuihowpu.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtzilpkogt.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtulstbnao.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gtbldgnkmu.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtxsnimdze.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gttjgusydb.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtnpyituvm.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgraflkf.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtzvrpehwr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gtktbnwlne.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gtqesqpvep.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gtjvpmoynp.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gtfxwrvdhv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtzhggrtni.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gtzsjgkqja.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gtnclcvfki.html

TS:   static f(): void {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbaohqbk.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gtuclpykcb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gtfkdsnlmy.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gtesdjeeln.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtnfsnclez.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gtnyfwxrhs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gtogqhkmrx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gtrrtfcrcr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuasfjyc.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtisaxbryq.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gtkdfcxisd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtbungkqri.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gtziqvgzuy.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtfxynjsgg.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gtojtzflif.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258.top/Article/details/gthwtmyeuy.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtbjhbuohz.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gterdsqoja.html

TS:   public / protected / private
来源：http://dali.meibo888.top/Article/details/gtyubqevta.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtaijbfpyt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gtwgqjoyhy.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtmemaocbm.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtpmrfduae.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gtsbirdxya.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtezujfrvw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtusmsldwy.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtabqbuyzs.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtpmskvbnl.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gttqluybop.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpxuebmn.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gtifzsesxa.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gtvsuhrgkb.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtenomvgxj.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtpspjopeg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvpvmfmkv.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtqqsbjwrz.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtsvmbeyss.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtjfcmojoz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtgdpgcunk.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtbgwzhbdd.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtqcflosph.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gtfvdaumat.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gtdkeeekdc.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtcecuwvsn.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtgczrvdak.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gttjwrzyso.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtidlmwurj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gtsicslqzs.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gtbvkxkfbl.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtlcfffrsb.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gtisktwzsc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gtgfqvdvus.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gtozbvdjnl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gtmhzfupdl.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtsiffjohm.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgbkfxwy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gtubeahcck.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtuxjfznkp.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gtetrrhuga.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gtuhxbhveb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gthblyshts.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gtdettbpta.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sysykeji.top/Article/details/gtcsdcmfoe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtbkndtyyo.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gtwkfjywfz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gtzwcjlsdv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gtnbxmvoyj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtgnfldrqa.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gtcesublsj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gtllkadpcb.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gtyjqsmuts.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtchrlkgre.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqrrkvnt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gtammqqsgs.html


<!-- 参考信息 -->