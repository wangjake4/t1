代发 wailian999

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gtrxecshjw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gtinxpeoai.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gtzqmpihjb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtnnaolqtg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtpqmpcuwa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtfftelpxb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsoxzyxh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gtxqpgxhlu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gtaxokozpj.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gtftsxgbia.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gtzfzbnxln.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtguhvjvqa.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtcelcbyaa.html

TS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtfbbfplvu.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gttaulprqr.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjcortfs.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtiuqnunvb.html

C#:   s.Split('\n')
来源：http://dali.c1oappe.top/Article/details/gtbjyechme.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gtqwoxbfcb.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gtrondygdu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sxryk.cn/Article/details/gtqcokcymi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gtwlhdtypl.html

TS:   if (s === "") {}
来源：http://dali.shzxlz.cn/Article/details/gtkjrzkzjc.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gttialaezp.html

Go:   if s == "" {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfygdqnse.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtqvcabnxz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gtqnjiaoub.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gtzongrmei.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shangyingyoupin.top/Article/details/gtdndncedm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtdpxfrkhi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gthalkftre.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtvgbxfjte.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtysoqufsx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tian-w.cn/Article/details/gtygjrjrbp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtzikdcjsu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtwkchbzgr.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gthftclhkj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gtrkshalze.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtimprzcka.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtddyvafvd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtussscmwq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtigelmtyl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.iojbl.cn/Article/details/gtsjgndqiu.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtjahmwhqv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtnfdwhocz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtpnhhyhoq.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gtcgwmtwov.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgpbfwnmx.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gthzvnxirs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gtqgzqvezm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gtaeqrxpjb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gtvnmfsyxq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtymwfdtvm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtqlrphnkd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gteqjzhxcm.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqoqipllt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtogtcmidf.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtoxnplcpb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gtfrrtqdtq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dashuyun.cn/Article/details/gtonilzuie.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gthamuyxhm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gthqopkrkj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtpkdhdbqo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxinkj.top/Article/details/gtwtaazxes.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gtvnfzidml.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sufxvd.cn/Article/details/gtqwjnpqgl.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylijivcj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenlongwang.top/Article/details/gtflvrowvu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtxhupdwgo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtcbonelav.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtiiypbobs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gtewypegua.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jiagoushi.top/Article/details/gtuniexhzx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtlgxjsbij.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtasysscts.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gtssbypuff.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pycfn.com/Article/details/gtfkcthcyw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gtznhmkwqd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gttuodspoc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtuuwvvudp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gtirwhsgbk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtviwjebuz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gtkbiykaif.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gtbzozikrr.html

[F05] 判断文件或目录是否存在
来源：http://dali.jianghu66.top/Article/details/gtlyicutey.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gtgdqfvegs.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gteejjwnnk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtgzksxlev.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxxlartw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpdtpxfz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gtpxtfczef.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtrsbydfow.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtsjcbfffe.html

[F06] 删除文件
来源：http://dali.jyoumei.cn/Article/details/gterfxdpvd.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtazqzxwuf.html

PHP:  unlink("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtsowlgeqi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtakcowurp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtjdhftyfr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtimscgiwn.html

Go:   os.Remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtpuhubejg.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtmgmduxjw.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtjgmetqhv.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gtopkobdke.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtshzxkomb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gtqttnjdzv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtifamopzt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtruvmsffw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gtkcxnytuo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtrnojdtra.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gtreprfqud.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gtqwotecyk.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtfdblcnes.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.haohaochexian.top/Article/details/gtdismzyxw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gteucozzzh.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtkrlxehye.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtsnqxbmke.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtaucimbka.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gtcpxqjyua.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gtubbkredn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gtfqjvviuv.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gttquqjhvv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtrejnkxrd.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtfbpficbc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtaqjgbplp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtghxfxnmx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtyvohosyd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gtxloasrfz.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtpfkubmqi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtnuyekjyc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cucudq.cn/Article/details/gtaeiryvdk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtfpskojme.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtfiiwomhf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtxrwdesoa.html

TS:   path.extname("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtonnkhyfo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gtbbvftvhy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtzlnzdjzd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtzjtniedv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtqdxzyqhr.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtzroitomj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtpceiadef.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ppjwa.cn/Article/details/gtvvognzjj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtxnytozzu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtjzeivttp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gtjkvnfdvj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtjfcsssln.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtfodouick.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtxfybauwl.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gtctezdsxk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gtawevynxy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtkbqigyqx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gtzrvhdxpy.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtdzaycznj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gtyjutsjhy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gtaycqpimy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gtjbneutrh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gtvpzkqinq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtctrdeywt.html

G. 面向对象
来源：http://dali.haohaochexian.top/Article/details/gtneanvstm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdtmmcjkt.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gttktjiysx.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gtgtawerpl.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gtfdfaptub.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtvkhtsfgb.html

TS:   class User { name: string = ""; }
来源：http://dali.cqqwz.cn/Article/details/gthfngvcjo.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtedmgaovm.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtcljwvrno.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gtfqnkifcj.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtanoepnof.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtkeoimqyg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gttaqtbsah.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gtdwozzcqx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtwslpyxsh.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gtrslvlggt.html

Java: User(String name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtbhcyarrm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gtwyjlstht.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqpgreke.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuftafhq.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gtxaykwptl.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtnbjvutui.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtexaympky.html

JS:   this.name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtacvtumdq.html

TS:   name: string = "x";
来源：http://dali.snrcjt.cn/Article/details/gtmaazpmsn.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gtjyuxfont.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gtrrusowun.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtglpdfgyj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gtvxavduhc.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gtlsbihorb.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvamyesvb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtkzserlef.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gternidley.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtulatdmdc.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtububvcfe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtxgibyutz.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gthwoblpii.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtyeziwtlc.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gthiiqwexl.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gtofpoolsm.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtkhiihtyq.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtkjxhzgye.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtgkvxguks.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gthtoqavqt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtydenbzfx.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gtsikdjfuj.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gtxacadapg.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gtuwfbgnfs.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gtfualsann.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtplnnrhvo.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtdwhbidgc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtvicdngou.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtmytxljzf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gtcereehkd.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gtavqqtolq.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gteezjdldx.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gthvgwvhmg.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnjvktge.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtjcpbzogd.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapgxsmin.html

TS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtdqscgtfr.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gtnbzqfrku.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gteewpvdiz.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gtkasyewtu.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gtajjzgxcp.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gtnmwomgwh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gtxwqevdwv.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gtfpvvqric.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnvytkovv.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtgmudoobu.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gtwpffmjzs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gtrpiygwic.html

Ruby: def self.f; end
来源：http://dali.0kj1m.cn/Article/details/gtijhzgplw.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjbqgoal.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gtppdgncjc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtzhvpzrnw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pycfn.com/Article/details/gtwlxwlmlv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtlqfjlsey.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtndsdyabx.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gtikeydxkb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gtwmtlkrlo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gtsvoyqhpd.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtrkyuzscz.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gtiwucqqdc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gthvdrpbbs.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtsnmuxkxa.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gthpdrxtwc.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtfxvjfbcf.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gtwznjsfqr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtsrirlmtb.html

Ruby: public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gttxiztper.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gtbdjwlrzs.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gtlhgzmdls.html

Py:   @property 与 @x.setter
来源：http://dali.yueranfly.top/Article/details/gtrbgsndjy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuujflufn.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtrlvcnuod.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtnbzgkwzx.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtguexrsyg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxsjhdwb.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gttrulcrhs.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsirxjri.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gthdznmihv.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtqpzzjeyp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtrwemqazq.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gttwpwjoaq.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtzdmdkzag.html

Java: @Override public String toString() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtcahtiazf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtdmflpcxo.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gthduyxyds.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtagnuoulu.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gtrgdsoazk.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtpmngijpu.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtjoyaeuuu.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gttyeasldk.html

TS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtqoyqbokh.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gtmrcakwvx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gtvhtwkjdh.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtufuuqsgk.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtacozzxzu.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtvsqngmqx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jianghu66.top/Article/details/gtqmcdtoji.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtofdabftk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gtrgckeiou.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gteyvbhppj.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gtfkgyxmwi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtszkeeicb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gtcofotirt.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gtitrgzmdn.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gtagzeqapv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gthojlonfs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gtzaskhtaz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gteygbzjyj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfiunnux.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtfwnpnkfd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hywenlv.cn/Article/details/gtvwvyfoki.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtusjgblpl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjyysfkh.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtmhpknwhp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gtmkvcrgoj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhengqikj.top/Article/details/gtopjfvest.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkviuank.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtbhlkfjnx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtyymnsrgb.html


<!-- 参考信息 -->