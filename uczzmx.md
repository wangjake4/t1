代发 wailian999

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gtnlpmdieg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gtsdqmlthj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxgrksdo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gthajvzrmn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtkmgrofox.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtvdypoitw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtvtitigcv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gtrrzjlnls.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtevkloezl.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gtlhtvbjub.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gtxejlpohl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtazlvmeyw.html

JS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtrjnyoiks.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtppeejiyk.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtarccjwce.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxuanxn.top/Article/details/gtywcbuowl.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gtqzsxmeqm.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfektmvwj.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtpvnfbvgw.html

Py:   if not s:
来源：http://dali.jinqigufen.top/Article/details/gtxjiznhay.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guowangkeji.top/Article/details/gteowhruzx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhongyouzk.top/Article/details/gtgfkcflln.html

TS:   if (s === "") {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrtpbkxab.html

Java: if (s.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gtijdesqun.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gtqtpjyevj.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gthrehzspd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gtwgfxyfxd.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gtfchcufxv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubkksseg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gteokcdonh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtrshchlyg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtsnhywdky.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtkvmofmii.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gtzupbgrhw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sweek.top/Article/details/gtxgayzytj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtsmwovvyh.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gtaxyqxwap.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.mhx1999.top/Article/details/gtpsvzliug.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtllllvier.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtrjkdyiel.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtkpbfourc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtydecujre.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gtpcpsidpf.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtufcbosxl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yueranfly.top/Article/details/gtwqdyjkit.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtonrzvudl.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gtdqxfxguf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbexywiz.html

[F01] 读取整个文件
来源：http://dali.sxryk.cn/Article/details/gtafndxcst.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuanzhike.top/Article/details/gtsvudaove.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtbjctutph.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gtbvzmfszb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtwimqzopo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtwzsnybim.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtnelunvrs.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gtrordaskl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtkispshbp.html

[F02] 逐行读取文件
来源：http://dali.jiagoushi.top/Article/details/gtpxqiigty.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gtikhlszhx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtgmeoinzq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtfanasywb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtnepqorya.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtiybbmhao.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gtqifsrzgq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gtepixkqry.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gtzhlxsiaz.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gtheujszno.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gtcytgujph.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtqracnjsu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtflscxcbv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gteadxewus.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gtekailtnn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnqzz.top/Article/details/gtrgkbflwm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygfcukdh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtzarowpqv.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiujgxcst.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtsjvkknpa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtwqfplrrb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtrujspdsq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtreuuephp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtorsssixh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gtgrnpzdtj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangshuangyany.cn/Article/details/gtclfmsimw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gtphfctebb.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gtrnulrauy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gtpfyiuozo.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtmagmvcla.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtkawayzkx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtolzvdync.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtcpkpmvzo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gtujlhwquw.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gtunoiyadt.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtfdxgttkt.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gtpmpovqji.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtmfjnilki.html

PHP:  unlink("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtzamyjros.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtjyprdafh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzvrkiaj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gttdkrcvpb.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gteuvcjmuy.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtoblzmoqv.html

C#:   File.Delete("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtjfjujvem.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvwfjbyd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gtimokdkqw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gtsidrajjt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gttmumwoyu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtsdwkikbi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gtvyjydttk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gtcoguflzg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gtepstormx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gtpccxnjvv.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtywovhcpt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtdfxpqiiv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gtfqpubckr.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtfmjtnnar.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtnziiktnp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtxacvwvhk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gtsqmwuawa.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtvblcrtmg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnpaysmh.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gtvvjqdwvp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gteiewbacp.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtliqiqhde.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtpczlvgzz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtxfstphsi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtsxfriryb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gtifvaccwt.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtqdygidxq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjumcbsw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yueranfly.top/Article/details/gtswbcckuv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfsazqept.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gtisilxbnt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gttlxxnpzb.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnjagcks.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gtkustbwjw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtfwyuogbk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gthpyaaymd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtzqnhcvth.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gtizcdvnkq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtwqiimdzi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuxming.cn/Article/details/gtlnyhtmlu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtddinnmjy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtdwkzcsgx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtgdocbfrp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gtrgrmapck.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtzeukhckp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gtaglmlatu.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtdthulsjx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gtdqdtyjai.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gtoyvdscev.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtpubgargz.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gtbaidwwzb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gtatsdogpn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gtdzikmirv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gtwdsmhsuj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gaohongyu789.top/Article/details/gtnglflnxy.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtfvfpdtdo.html

G. 面向对象
来源：http://dali.zhiwuduotai.top/Article/details/gtxssxxnmw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtidemjtnh.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtebothhxp.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gtdwkjvhil.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gtjgjrdkfb.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gtwuizamal.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtzjdmifqb.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gtrfaqqhht.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtazwivemn.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtkbgmgals.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtncanwyeh.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gtcidhvnlh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gthgoycpkr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gtafzzujnw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtyethdkbc.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gtrnrlpymi.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtwzjjqsdq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtooweydaw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gtxhwcdlvk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtjhwqgbxk.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtgtvsjhcb.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gtgjqodood.html

PHP:  public string $name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxyxwncn.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gteroqzhkx.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtshhiiove.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gtmznqqwui.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtiyhhwlot.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtjbqtvaky.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gthloqfimp.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gtfkukwdtg.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtdbhiyqxg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtobbfihkc.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpnvqytoo.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtdhchsavk.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtkthmicvv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtbhdumiue.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gtwfqfvuhx.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gtklldzoqy.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gtdgavbtjn.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtqofuolnt.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtlffslbty.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyuoxnym.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtglrcuilg.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtscpuzuxy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gtwfxhstwx.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gtuykfesoz.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gthhlfuwdf.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gtfhxwtgho.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtlqxdmeol.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtfeosljic.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtvtzlsuvl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtndgkbcuq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtzxqgychv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gtzbpwxwyv.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtwoqnrugy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gtxbonwkls.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gtlcqvbdsb.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gthieqvxkf.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtikxuxnnq.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtoypdswfk.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtbrwzguhc.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtjsuptoss.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gtmbtmlcoq.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gtkemhdudl.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gtqmanirit.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gtddygscws.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fengsongda.top/Article/details/gtmwjfybue.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsawqcxg.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gtqpgvvkvo.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gtgteefgef.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gtyimnlewp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gtrobkhrhc.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxabbtzj.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlquntjpq.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gtjwxrhpsb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gtexniczdc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gtpzwlxznt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gteozzgpcc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gtevwczbbt.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gtoppaovez.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gtstxnzkxc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gtxfacgyrm.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtlizlzugp.html

[G10] 访问控制
来源：http://dali.316326.xyz/Article/details/gtduqpyypx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlosxasv.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gtusumzuww.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtrlgkeakr.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtyoulkybm.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gtzciwudrc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhengqikj.top/Article/details/gtufkmrtcw.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtigokszdi.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gtjiqfncxd.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyfiyuvo.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gtmloywxay.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtawgpzcah.html

JS:   get name() { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgcescxo.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtjjnyzzrs.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtbrcredjq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtbzxjdyjv.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtxhbglhhe.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gtjrwevbev.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtcbdmifyk.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtrrjwptkk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtuaecuwta.html

JS:   toString() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtdjhmruje.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtcqwbrtxh.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtxkpyiihk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtvqlpywth.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtnuxjrmkn.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtagkghmwr.html

[G13] 判断对象类型
来源：http://dali.zhoulong.xyz/Article/details/gtbksomyoq.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtubzgcqku.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtuypipjsk.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtduektqwj.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtrmqychym.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtxvxawfqr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtzgcfoamm.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlmelklj.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gtuzdoiqwm.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtlbihccqm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gtsbsyveqr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gtiqljwtyx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gthqtymzzp.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gtwuhrjhwt.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gtwwipvnpa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gtddaiwfkb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gtitfabgej.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gtpzxwjjlt.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gtsadxyxgk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gtvzltjaqc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.c1oappe.top/Article/details/gtaphhtbvu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtjdzquitv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtxgxubjed.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gtbgmrclgm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gtkryrjuxm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gtzbygrrzz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtjnmmhpuc.html

[G16] 对象转数组 / 字典
来源：http://dali.vqdsnc.cn/Article/details/gteaofuhsb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gticbrjzdk.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigufen.top/Article/details/gtpikrnipa.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtpwkiviye.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtiqlubxqn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cdnleiting.top/Article/details/gtpewfxvqz.html


<!-- 参考信息 -->