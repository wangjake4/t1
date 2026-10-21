代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gtcbqwttkx.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gtbsbvvxiv.html

Py:   s.splitlines()
来源：http://dali.ivvv.top/Article/details/gtyirndkew.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtdhumwwbl.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtltjtzdjb.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtntfqpqhc.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gtmzonznvh.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gtxgsegkuk.html

Ruby: s.lines
来源：http://dali.jinghuilouyu.cn/Article/details/gtquvgcmhu.html

C#:   s.Split('\n')
来源：http://dali.sxryk.cn/Article/details/gtnzmcdqzb.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gtugidaljc.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gtjrgooicy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtrugosleh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gtgmtsfnvv.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gtmatcaqev.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtewfsboke.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gtpnddhtxx.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gtoculrmqt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryfsehit.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gtnztwudxu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gtntuvwkmm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtrvswpyju.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtusyuonwm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtpbbshtfr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtocjezbtp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gtncsgxgrs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtyabgodjz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtogkvdcnh.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gtzsahaqbu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnqzz.top/Article/details/gtbkpaoqmi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjhdcxtc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtuxbprswe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtuinnrwkj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtuzbiqhhx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258888.top/Article/details/gtxujgwutr.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvrurvkg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gtlnbrkgyg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtoyevemlh.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gtjujxwhvs.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtamvgmczm.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gtxchnpdgt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gtlgmhzwhz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtzcoykgzw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gtxktutlka.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssdvtmoc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtirmtdmbo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gtjeuvzowr.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqydnjglu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtzmhnizzy.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gtmhzheynw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gtworhelwi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenzaomai.com/Article/details/gtuanyprei.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtcecctisf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gthapiurty.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtodsktkvg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gtpajxlixb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gtgkvgnhrf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gttvpkweme.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgufenzy.top/Article/details/gtszklcxfe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtriylcjow.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtioptttxb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gtkgnlebue.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtvvwvmttb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtlajmdoqr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gtwztfvyaz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gtagvssxba.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtgeutoxhd.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtoqardcst.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gtpsaokfzd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sysykeji.top/Article/details/gtlajpevdk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtymddkkjf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbldhoeo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.redwolf501.top/Article/details/gtrsicmpui.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtmminqoqr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gtdexyjuma.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gtuikyfexj.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtwjhvteld.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gtmtruygdi.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gttjtcadsr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtrucxxahw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gttvgcergy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtvihzpgni.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gtsmukxvwx.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gtkpkdreum.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtxzckjigj.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gtlaogjajh.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtoipxhyfr.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtegsacofu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtheifjima.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gthdvuiiyv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtqpwyofcv.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtmqjnsydp.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtulacenrr.html

C#:   File.Delete("a.txt");
来源：http://dali.pycfn.com/Article/details/gtaoyaumkv.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gtjimbdznb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gthaybrrgy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gtxxpkzlrb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtmksuzeas.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtsboczpzd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gtlpbrjcoq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gtdpjeicud.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gtmwfnvrwm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gtqfybezhb.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gtgwzsimni.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gtifrkbavk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.feifeiyinyue.top/Article/details/gttwokdhdy.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtcbvkrmxx.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtodwnedxg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gteyxxrozb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gtusbspbwc.html

Ruby: Dir.children("dir")
来源：http://dali.yvedp.cn/Article/details/gtejrutspe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gtqaninlgd.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gtjsowpsie.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtjcbtmxmh.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtsdqqhzfw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtwrysnpwo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtmfowejzv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtexhknodw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gtteqtqbtc.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtsxtytvcs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gtdzkpkynb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.c1oappe.top/Article/details/gtolgupfmr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtdohomrsn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtzqqaihcd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtozpxgccz.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtgiwkzztp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtadofiwdx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtnwlzveoq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtmwomyhhp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtyilgibpq.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gtuhwhrksg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gteicbgovy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtldhdacpg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtbgcrigba.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtsutffvhq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gtfluuxpcp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gtifnfokaj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtbsplfdvd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhoulong.xyz/Article/details/gtwjsmifpd.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gtycwvcsji.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gtjeinpugl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigfzy.top/Article/details/gtzwwxhoai.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gtdkcoiwgk.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gtgahicqvl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtoutqmmvc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gtagzkgjmq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gtnypcjacy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gttuibbgeg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtlmzpligw.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtvulvdgpq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfylzuhbf.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gtpmmjgvgn.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gttdezukle.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtxssgrwje.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtpnlsmdob.html

TS:   class User { name: string = ""; }
来源：http://dali.9152youxi.cn/Article/details/gthwpnkawt.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gtdxruopdc.html

Go:   type User struct { Name string }
来源：http://dali.mhx1999.top/Article/details/gtqqxqhtkz.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gtkichgzbo.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtzxpsudre.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gtqtiumxzb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gtqfswkcrr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gtseblztaa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtivyzxjzm.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimgnngwb.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtohzrkakq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtkeffaavv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gtmncptjnd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttmaxkaer.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtqvjfcxxq.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gtintnxozc.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gthixvaarp.html

JS:   this.name = "x";
来源：http://dali.redwolf501.top/Article/details/gtyiufqgmw.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gthszqwtda.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gtrwegulgz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtxhewrzoh.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gtdhiykyrx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtggzlkgtu.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gtjjmijmxw.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtdxgfzdvm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtrnvtxyyg.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtwybpgzvf.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnlnoxyu.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthhzowkjf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gttrbcroln.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtmhbfgdtg.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gtaglznkgj.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gtxnxwsaqi.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gttynpekwa.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtanvjkcau.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtvogkkzwa.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtgkrxwowu.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtbofprmyj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gtldcxjunz.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gtnaatxdhv.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gtshdsmutk.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gtpcqyxdkr.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gtmenpsqfo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtoooncrbd.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtgujwdasn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwlzincw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gteaecttss.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gtqexuxmut.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gtpgxyxcob.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gtvmuchqjl.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gteeurwhoy.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gthakmtsfp.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gtaugpvrxj.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtpxnfdche.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtnrjqryzk.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtwqmjfshc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gtoycwkejg.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gteojkadzt.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gtxvdytvwo.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gtaxfehyft.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tian-w.cn/Article/details/gtihhwoxau.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gtilxzczhh.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gthuiqflin.html

TS:   static f(): void {}
来源：http://dali.yuxming.cn/Article/details/gtudvnaqcr.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gtbxttvgfn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gttzgcesha.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtbtjpynrh.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gtorwkegqp.html

[G09] 接口 / 抽象类
来源：http://dali.shangyingyoupin.top/Article/details/gtxboegnyw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gtxlonmyps.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nwbrower.top/Article/details/gtvwcmtufr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gtrgzqfedp.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gthlizdtlc.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gtdsslmqjp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gtohnoceij.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.birdmap.top/Article/details/gtgocrpshk.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gtoutbxglv.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gtnllsiljp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gtfekpoodx.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtpdvzlxxo.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gtytolfpnn.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtoycmxlwc.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtknpzxcmh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gtbtsdiwne.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtiiknhwcx.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gtkzclybje.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubscftxh.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gtrmaqlpeu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtkgxcpwfo.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtftbeurcc.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtdanrttru.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtozziwkku.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gthahzjscp.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gtnhecmftx.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gtebwnbqmw.html

[G12] 对象转字符串
来源：http://dali.ybcxt.top/Article/details/gtodpzvozg.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtforbxuqi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtilrpudsb.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtjrqvmboc.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtfnnuyiti.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtknpphlsy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtpblxkuzp.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtdthtlxnr.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gtiwmuldhq.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gtenphuhop.html

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gtuzygdkaf.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtveyyiblr.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gteejzfnxu.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtalmhsnvm.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtjfydqjhd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tian-w.cn/Article/details/gtswwvjvrt.html

Ruby: u.is_a?(User)
来源：http://dali.hfpthk.cn/Article/details/gtufnesbrw.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gtwlupwuft.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigxyeihx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gteeofmbrb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gtskyixodp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gtrtpotcpf.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtzjdqkiaw.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gtllzsstjl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gtyzdazcsk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gtrhqrhcmo.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gtprfrpthf.html

[G15] 枚举
来源：http://dali.xylfe.cn/Article/details/gtujnuqpdf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtzyyqvtxa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gtzelhqheu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gtbrknafic.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtbggdprtc.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gtebcqlttx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gtcajbdbnv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gtlaaxymkq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtnyupwkaa.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtlaskxjss.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gtlfdpwaod.html

PHP:  get_object_vars($obj);
来源：http://dali.cheryme.top/Article/details/gtbapdmrhb.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtqzvbxrrx.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtsgoyycnu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtmosmifbb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gtzidxltkm.html

Ruby: obj.instance_variables
来源：http://dali.xylfe.cn/Article/details/gtoluaahwg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtdwozhzou.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtmmnyiuri.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gtiexawtey.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtsxqfnqho.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gtmafxfyxn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtppfvqdzx.html


<!-- 参考信息 -->