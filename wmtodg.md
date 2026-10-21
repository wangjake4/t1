代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtppeojdwx.html

[E19] 多行文本按行拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnhjujie.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gtirlhuktu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteihgfuss.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtflobggrn.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtqjdoztmr.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gtujzgelga.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gtyadiupxz.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gthsmzsvec.html

C#:   s.Split('\n')
来源：http://dali.shuidangran.top/Article/details/gtvsvohjka.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflmtvenn.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxklvtkz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gotoacloud.top/Article/details/gtefgevrmt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ydzc1.top/Article/details/gttqhgqfeh.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gtrdcdfmoc.html

Java: if (s.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtzuzbtpsl.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gtgbygqucb.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gtwgjolmco.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtuatidujk.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvubsnrqp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gtarczqflj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtjlwpjujb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtwgwnyvnk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtocqmhogb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtqwpxnbee.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtjawnrshu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtxjkiwyir.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtdunuuhlb.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gtpsjqdkwh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gtbmrkiyuc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtgjmmsroh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtgsxxcrbb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpyuttef.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtdrvjivic.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gtvhugyfyr.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gtbhxqdlaw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gtrojxgxjn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwuobuxey.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gtssvxdhrq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtclhhrpyy.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gtzfgyeiaq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.haohaochexian.top/Article/details/gtxpqrpizj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtvvaaunvb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gtmvcbrbij.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqipgmuq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtfaaylugb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtrrjthdzt.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gttfuydjnr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gthfkjxasu.html

[F02] 逐行读取文件
来源：http://dali.jiagoushi.top/Article/details/gthasorfsg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gtfzzepkqt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtnndpoadk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtquorfbgg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvxnseoji.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtenxltvvb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gttjalpzvm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gtxgtwmwty.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gttmqyabaf.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gtdartzkxs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gtcammgmzi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtzgxnvbks.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtpbruhelv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtmcsmuxea.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gthllerxxc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gtqfpyyshr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.svipenyu.cn/Article/details/gtjdckqbct.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtawlkcaxf.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gtvanurwio.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtqwgioumc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gtpfztifcr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtabtqszqu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtsyxnwndv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gtewnrsipt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gtxlgwhbyt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xinyue.icu/Article/details/gtnzgcksdo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gthbgfnlbm.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzswvpbc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gtivdgleer.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtgryttfme.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtajahmmct.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtmpmwjuqm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtlngwqsdd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gttydazcuy.html

Ruby: File.exist?("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtxdckaqwu.html

C#:   File.Exists("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtkicvxncq.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gtsnncfbnq.html

Py:   os.remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtzwkutgvr.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtbluwkplc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtwzbsrgoh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtkzpzylzz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtdikufsdv.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtsuwtuxbo.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtsokrlhxv.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gthkkjiiti.html

[F07] 创建目录（含多级）
来源：http://dali.jqgufenzy.top/Article/details/gtuahjrshv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtkwaffvux.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gtyssowlbu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtunvnxoda.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtyofiqrtg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gtlqmqiboa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gtuprtikhr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gtfcvzjjnj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtnvarbwxm.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gthpljkrpc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gthmnntypg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcrzekscl.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gtkdjxnmcn.html

TS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtstqofgki.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtldslfcvr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gtyarkkppd.html

Ruby: Dir.children("dir")
来源：http://dali.jyoumei.cn/Article/details/gtmjyqdxxq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gtqlbamajj.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gtlcijgviu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtgqnjlzek.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtkmrfukvb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtydcbhgpb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtzcgvnvia.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtedsskfsr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gtdxskhnqv.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtggmzrebz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gtzhltwuki.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtbzkbqlvx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtwnfkcesr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtbyoamjzf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gthbzzmfgh.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gtsjidrnck.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gtbmnaiwww.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtewcctcwf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtbltzokae.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtegldfasg.html

[F11] 复制与移动文件
来源：http://dali.hysaishi.cn/Article/details/gtmhzwgymy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtzuswjkla.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtvdsofntw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtnjquhhzd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtlzdpyyzo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtazkkupog.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gtvfsojfat.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtmrwqymhk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gtyimowqka.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxnueqyb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gteennpiin.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gtreydlcdp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gtcfyijqxp.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gtqgcyryqq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmnzpyyq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gttjrpfbtx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzyyfsfh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sufxvd.cn/Article/details/gtfnritjfj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgvglmwno.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gtnmcdmlfb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtflbjfhgp.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gtzqwbijzi.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gttuvyaokf.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gtpenxbaul.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtdarlmzka.html

TS:   class User { name: string = ""; }
来源：http://dali.316326.xyz/Article/details/gtqcracsas.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczcqpfij.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaoynltja.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gtzhfipwcd.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtxidpjwsg.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtvorlbptp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gtyyaxcung.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gtpklhyasi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gthpotfuwr.html

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gtvkvohhmi.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtvueqcqyo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnqzz.top/Article/details/gtqdmtislm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gtqfcrxmgf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxprfhycv.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljpowfoz.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gtnqsotmbz.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtvkbuymmp.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gthogrzwju.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gtplccysvl.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtxxovizok.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gthemjnddl.html

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtlakmxnpi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gtirvevxlu.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gtkuvjjiol.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtziygpqfq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtqahilkmm.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtxnyxnsau.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtmshbxzbg.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtdjojmaiu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtbltftvmm.html

Ruby: def greet; @name; end
来源：http://dali.xinyue.icu/Article/details/gtzqepzgtt.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtfdegdtrd.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gtsqrjkzma.html

Py:   class Admin(User): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssxwvscm.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtshtfnhgx.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gttizgvats.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtygopgwut.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gthuqanblp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gtoutvkhia.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtyedwlifl.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gtzdhfbdgw.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gtrdomrfiy.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gtkkfxbncs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gthxdqcuge.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtrssiwfus.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtfzlbhqas.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtvbhubrki.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvllorfbe.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gtcrawjrzm.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtzgqvchht.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtdoxlgtah.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gtmhjelipe.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gtvhtiupre.html

JS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtksqnkuyx.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtjhqxmcgf.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gtvzsjneby.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtzddlawxf.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gtnseppbtf.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gtpibvyvns.html

[G08] 静态方法与属性
来源：http://dali.wangshuangyany.cn/Article/details/gtwwiqafwg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gtggidmjqt.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtldbowoje.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchtsfata.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gteeloviyn.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gtmpgfgbao.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtrehvumsx.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gtabpiflbz.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gtukbgrjus.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gtqqjfwdrg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gtehvrnhzv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gtitzjbigq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gtyyrgtbfo.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtymxwodzf.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwntkgwyi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gtwgjaften.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zycfv.cn/Article/details/gtcvsevitp.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtarbgcent.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gtsqjptyke.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gthqnunuma.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtdttbihxp.html

JS:   #private 字段；其余公开
来源：http://dali.dianchejie.cn/Article/details/gtqfztqhxh.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtmtnbalke.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gtwmotsopr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gtokhmmnjl.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gthcolamnz.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gtyhiktxds.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfncgeshm.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtvwshccwl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtglupjkgz.html

JS:   get name() { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtswojgklo.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gthaegmbbo.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtrvyosspw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtybeirade.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gtnpbawcyw.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gtuvsmunnu.html

[G12] 对象转字符串
来源：http://dali.meibo888.top/Article/details/gtztzvflyi.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtgqbzvqpp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtairumrkk.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfoyxieu.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtyqqxscpn.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gttlkcblfy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtqztlvpsx.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtrrvjsmia.html

C#:   public override string ToString() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtyibgpoqf.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gttpkjousp.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtbvsinopu.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtcwfwzipt.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtzazmzztk.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gttftsaqxa.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gthrsytuvm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gtghulyefg.html

Ruby: u.is_a?(User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwfhxtqw.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gtedesxfoa.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gtffzmgldm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxuanxn.top/Article/details/gtpnrydksb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guannengcc.top/Article/details/gtaylvcrib.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gttgbhinhl.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqejbqil.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gtrozbdbix.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenjidiqi.icu/Article/details/gtyqqwvvrd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gtvkjtnthf.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gtaanvlirl.html

[G15] 枚举
来源：http://dali.zhoulong.xyz/Article/details/gtkllnbeqw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gtcapvotgu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gtyzplvjen.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gtpfdprpdz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtcwsaleou.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gtagigkncc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gteinsptuk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gtnuwqtkif.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtrcfxpovl.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gtmpcnsxpe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzstalnq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpizthadj.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtcsizfwuc.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtvvmiqksk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gtyinytlsx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtlorxbojs.html

Ruby: obj.instance_variables
来源：http://dali.hongshengwenyu.top/Article/details/gtzjnnehbv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gthdpfgzre.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtycyxxuko.html

H. 异常与错误处理
来源：http://dali.yongpay.top/Article/details/gtxgpvddts.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmuqjolyj.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gtxucvnlfb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtdnudrdku.html


<!-- 参考信息 -->