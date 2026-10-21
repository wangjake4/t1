代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gtppcqjjzw.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gtonzyskex.html

Py:   s.splitlines()
来源：http://dali.chenzaomai.com/Article/details/gtakhjjpso.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sweek.top/Article/details/gtmwfrthek.html

JS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtlccmaivm.html

TS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtfxhmowag.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtdohvodld.html

Go:   strings.Split(s, "\n")
来源：http://dali.zycfv.cn/Article/details/gtrkuyxodq.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtmtgikerh.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gtrnyprfku.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqtfehia.html

Py:   if not s:
来源：http://dali.gzhubu.top/Article/details/gtfcrinlmt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gtcoseyubn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gtktdffimn.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzwjytujg.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtkrqvxmxt.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gtwwrlshhs.html

Ruby: if s.empty?
来源：http://dali.jianghu66.top/Article/details/gtuoptlsef.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gtoucooyzp.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gtstkohtjp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gtdozfxjsf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrldyimm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtdytkstfb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzujgjtep.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gteacbnmse.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gtgxlfpskn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtishwgygp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtrvlxlkol.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gtxpdcbkmu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtfwvwna.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtlnzuftbu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtkedioghp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gteczthvdq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tian-w.cn/Article/details/gtwuwpyhzu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtgpghuzhz.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtiqaqrpzq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gtbvivmzdv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtalfhesuo.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gtzvfqcroj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtctrclksd.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gtmcvohzlb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnqzz.top/Article/details/gtggrfdxgk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtbevxverb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gtibpuuycb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtphqwjfde.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gttivsrvsu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gtlzmashcx.html

Ruby: File.read("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtfyaoqtfs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtywlcikhf.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gtheqckuyr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gaohongyu789.top/Article/details/gtawgvbjex.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdewbmtk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtdkdwxyho.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtftcijvld.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtbfvufezz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gtjhrwmdph.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtzkjvbqdc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gtuplofpbh.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gtpckufeut.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zdqjudy.top/Article/details/gtvhurttwe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqjnpfcg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtsrerkfvd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtnqytogzc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtnjatfxgi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gttshorhoy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gthtfoanel.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtwpnzpvzk.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gtxoxcawea.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gtqyzosnxg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtlqdcosuz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtjcxkavxp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtbdkjxbfs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gtqnlckqwz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtawqcazdh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gtgoxjwfqc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gtchjufdta.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtbneeqnjh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gtzewljzyg.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gttfeoyzbo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtqybewvgu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtbjbykixx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtffbhojxz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gtlaismzfi.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtydwrttab.html

C#:   File.Exists("a.txt")
来源：http://dali.yonumen.top/Article/details/gtdsldewto.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gtjyekrflv.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtbjvlivie.html

PHP:  unlink("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtacbvgyjo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtyqtdbuik.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtesnqmzls.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtbcmvelri.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtfvstbioe.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtepooyfdj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtenqsloem.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gtptcqmgbx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtzkpfobsd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jianghu66.top/Article/details/gtiivqiejj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtoliqozot.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtwigfwepe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hongshengwenyu.top/Article/details/gtoaehojba.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gtnlfllkcq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtkxijpwla.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.mhx1999.top/Article/details/gttdbabafu.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtsczlxziz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gotoacloud.top/Article/details/gtzkjuypch.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.mhx1999.top/Article/details/gtafzjhujd.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtaoqvbrha.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtxbkuodlz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtckeaqfuv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gtwejtflfl.html

Ruby: Dir.children("dir")
来源：http://dali.sxryk.cn/Article/details/gtsbzaqlyw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtnmbhrulf.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gthndelved.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cashguo.top/Article/details/gtqcyihuch.html

PHP:  filesize("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtraunrehq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtthtyxinu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtlksifrli.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtlggceeah.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shuidangran.top/Article/details/gtiegbtctg.html

Ruby: File.size("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtcndsdiue.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gtyjdrpnhc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gtzzrdiclu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtmnrxedzm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gtblwtercr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtkmduobec.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvvmjimw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gtfebxxypr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtuqkdtxca.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfagzdwt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtoxlesxws.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gtjrcnpmuk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtbmlkgyov.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtqqoggcih.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtyyquupkp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtsevxhzgn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteoyjuipr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gtnbjlmffc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdiabjfvu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gtcnfyhbnm.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gtszjomthe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sufxvd.cn/Article/details/gtrylsgmbi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gtzjrikxpc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gthnlezytx.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtwhuonoie.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gteuvgnrpq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gttiktgpjs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cashguo.top/Article/details/gtbazftswe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gtxdtvkleg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgsnluwbn.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gtiwtcegeu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbmxuzpte.html

[G01] 定义类
来源：http://dali.jyoumei.cn/Article/details/gtbxnpmjmq.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gtedncpnjg.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfkodllf.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtczhsxrdo.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gtlhpxnyvp.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gtrrnrewff.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gtrvnsqxra.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gtvrdnlgbj.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtmtlsoqef.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtwehvzhkc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtpxhfrrse.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gtdfdgbfmh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtzwfysebz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttycznmnu.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtqvxehept.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gtxskjdbvu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gtazbsuwbe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gtrvtrhvar.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gtcfxvalow.html

Py:   self.name = "x"
来源：http://dali.c1oappe.top/Article/details/gtxtlyrihj.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtccypfhbx.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtcjusopqb.html

TS:   name: string = "x";
来源：http://dali.yj20258.top/Article/details/gtuazvknma.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtakstrtuz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gtufjrtnqp.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gttvbijknb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gtmkzlzkik.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtghzpgpjq.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtbslgvynh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtgrqllxrv.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtgtizjhpd.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtspbwloxe.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtleypjamg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtlimgckak.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gtrynvecgp.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gtlmhvdabo.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gteahlqhex.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtqjfiajkr.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtahserzhp.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtkxjdmwjz.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtxsziorfx.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtvphkusrz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gtfggeysye.html

Ruby: class Admin < User; end
来源：http://dali.smart0.xyz/Article/details/gtinnekodz.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtdpastmbp.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtodsrhwyd.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gthkgldppu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtwtdjkxgu.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtnkrhbdwl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtkadtnvfp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtccwhkqgm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtrmgthroj.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gtyevnyzav.html

C#:   public override string Greet() => "admin";
来源：http://dali.bjfxy.top/Article/details/gtxddkhmis.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwitclqh.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gtvinowori.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtgwvbkhjv.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtcmrpdgnw.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtapcbmumb.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprbydylb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtqhlvwdir.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gtibmuxxei.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtmlozeaps.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gtyrexkpzn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gtbrmctcan.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gttjuieugv.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gtlygvvqca.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gtxstbvwaq.html

Java: static void f() {}
来源：http://dali.yvedp.cn/Article/details/gteovzzagj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gtaujrznym.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtmjqgmwtq.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gtgclziyrq.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gtdexnnbox.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gtafeoqfwt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gtcxvwqzke.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gtomywjjgo.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtobivjpfq.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gtrzagjskw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtndxxgdqm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gtygtfqtzj.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gtfsbvhlnl.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gtfswuccvr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gttkiccvny.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtqnhspwhz.html

JS:   #private 字段；其余公开
来源：http://dali.jyoumei.cn/Article/details/gteutptvtd.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gtykkcjnrd.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gtvolkveoo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gtmqvcpqds.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtrjuoepen.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtmiskbmzu.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtchzlxxtb.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtnockbvat.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gthuavhxfx.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtabvpdnnk.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtvefzpnpk.html

Java: public String getName() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtrbhxuqni.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtmvbftaxl.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gthanyocig.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gtlotoqwcp.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtfolvvegf.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gttyovpqnn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtgymdncgu.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtbwbrauni.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtkyxcjhdx.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtofkajwzr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtorztbirz.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gtfjoxofmv.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtmcvljznn.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtzxmomsqb.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gthrbxgpkh.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gtxttlajmc.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtlfbysmig.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtvclpqpjp.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtcpguwgwk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gtrllhldqa.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtdztcdjvn.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtiancbnef.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gtdgpjdrlc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gtechgfqxh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gtmnftyrba.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gthtgenjoc.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gtxkngatvo.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gtldvijoxh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gttnfwkfdf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnxiangtu.top/Article/details/gtibvxjafd.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gtapyriapi.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gtiuzotykf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gtstesyrlf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gtczkpvlbn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtdrozppbn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtlwenciqv.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gtsopfldaz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gtowfjamoo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtbtturpsi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtzeieavax.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdhqhlzh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gtkznbgfgz.html

PHP:  get_object_vars($obj);
来源：http://dali.bjfxy.top/Article/details/gtjdqocnwi.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtnfdzkssg.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtkvqgrxqb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtbrlftmvk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gttomudssg.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gtfczywjhx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtdrugfpye.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtgwpwnnif.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtayhdkbvh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtrmminxds.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gtkiyytbeu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtcseojxiu.html


<!-- 参考信息 -->