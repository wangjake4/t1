代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtmwcuxcyd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtzsvtnmgo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtiznjmzgh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtnefrxzwj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jianghu66.top/Article/details/gtjkkhelvm.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gtcxgggxug.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gtpewcxgbd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gtytmijycy.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtwrtdkvpx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtcpunsnhp.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gtulvzbned.html

Go:   strings.Split(s, "\n")
来源：http://dali.dianchejie.cn/Article/details/gtpmslbwcn.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gtpdtktssa.html

C#:   s.Split('\n')
来源：http://dali.guowangkeji.top/Article/details/gthspwcqin.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gtkndfzjcf.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gtzbrpgsux.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gtobzehmol.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.haohaochexian.top/Article/details/gtokmvwgsv.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gtbyenipwo.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtnrhlpxjg.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gttbtzrxff.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gtrfonzbbp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gtpbmdmtkg.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gtwfhbadud.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gterjjsdlj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtefkbrnpl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtzkkuwcdb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtsixiivsn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtdugmdosw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yongpay.top/Article/details/gtnclyckua.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtqvpqqwxz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gteinsitah.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gtpcjuoicj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cucudq.cn/Article/details/gtitqzwccd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtqifeeptd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtuodfrgty.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenfmyndm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gtdiehnjfh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gtpjaxcfao.html

Ruby: s.bytesize;  s.length
来源：http://dali.yueranfly.top/Article/details/gtvdhcfdeo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtfnvokmhe.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwrgwhrok.html

F. 文件与目录
来源：http://dali.xziqi.cn/Article/details/gtkbfjinpb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvhbamrqx.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtizcfnxvl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gtekjadmeg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtzebbctof.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gtxvhdmxue.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtmdzuhtss.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtebshsxhx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gtxxtgrdyf.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtzqyjukle.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gtodmdylke.html

[F02] 逐行读取文件
来源：http://dali.yvedp.cn/Article/details/gtqaqtaelg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aizwys.cn/Article/details/gtvmjkgqru.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtzdkrcyct.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtjkqnbuji.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedlimtyc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtpkumrctj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtystcnzil.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtypjanrcn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gtrecqjjct.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gtrzufbioa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daria6918.cn/Article/details/gtdoqlehfd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gthfuolbgb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gthkymfndd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtoqggeuvd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ybcxt.top/Article/details/gtufhnfwsp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.vqdsnc.cn/Article/details/gtmpjebshb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gtnckpngql.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtwatfmimi.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtsbflqaze.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gtfhjczpkr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gtrqrlljwo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gteftkvzuo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtrqunxyno.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gtkpszorda.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtgliolrqr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gtpuqpvyac.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigufen.top/Article/details/gtiiunzibt.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtlfxllcrn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtjdedonld.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtzwpvuulz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtnuwbwkxa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtmtmssgmr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtcorpcveh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gtchrwyhan.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gtyvbxkepa.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtljhnscmy.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gtitghrzyd.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtlqanmzou.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtsrxuijld.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtzvfcirwo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtjczvyzvs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtctjzpczo.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtsxyjlksj.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdrgprgl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtnkcdeygb.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gtrbmmwbma.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtypcvhbzk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtesfduenj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtikgdhkuh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtklqcfxyr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtyjqpqyab.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gtcltrobek.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gtelbwyxzr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gtpsxkgqlk.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gtbgogynmx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gtcmhcaqlb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hysaishi.cn/Article/details/gtvvtveoem.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtthnlmojh.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtzleqbvri.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gttxqdwism.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.redwolf501.top/Article/details/gtbjqbdkjj.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtqwibdmfr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gtlpnpleis.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gtmdrokygh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtpxvjoysu.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtpkbgjexi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtsnmzisph.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtcodungca.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtggdfvdye.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiobmzfek.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtrfgufvjv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gtmtlwvede.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gtrbbfizvh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtwthukhka.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtlqfwalno.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtsxxzbsmm.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtfgwybtzb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gtwnhfbcgr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtfbmmwucp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtbztoahia.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtpwjqcqgh.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gtrqrbcpic.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtptztzebt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cashguo.top/Article/details/gthxiuwply.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtugzubdeq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtpfkrcise.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtndolwhxg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gtxwgxlwzo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtwnclxmqt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gtnnspucqg.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gtsynkavvo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtqtphahdg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gtexhodskf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhixingplan.top/Article/details/gthpjwicdo.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gtyhvkoczo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gtooaeognj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yonumen.top/Article/details/gtwbemdmis.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gtgfaoqrcb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtostkuamb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtdkcgrofg.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gtcjjfqbte.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlbsafzct.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gttsaglftx.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gtbhqrpizf.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtihexlotb.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtfpglfgti.html

TS:   class User { name: string = ""; }
来源：http://dali.bjfxy.top/Article/details/gteglgrlhm.html

Java: class User {}
来源：http://dali.yvedp.cn/Article/details/gtibscfadj.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtiddqlusr.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gtsebmfodg.html

C#:   class User {}
来源：http://dali.tanke756.top/Article/details/gtvjiyebfh.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtpxqgfitp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gtcpurmcwi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gthabeksut.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtmdxqgaiy.html

TS:   constructor(public name: string) {}
来源：http://dali.chenzaomai.com/Article/details/gtclixpmdq.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtkcqayseh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcchagwlp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gtqvfoshug.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gtwnsgzxlj.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gtkotbbxos.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gtbonitota.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtfodamtyx.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtqydqooxi.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gtfntbqspw.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gtexayqtph.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.birdmap.top/Article/details/gtkpuxdkrs.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtkbajjclj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtowopuurg.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gtataijpzq.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtravgmvoa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtcafbcrnj.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtaixmiaqv.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtdarecxqf.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtxnymrqlc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtikiukwko.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gtalrnvogx.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gtxcopjspl.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gtfiuckocu.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gtlsrmctwd.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtyhmgjxke.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtigvfmtah.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtctcbykpe.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtehfoginl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gtxhxgxtrb.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gtbnieirfc.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gtopdzqemd.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gtssvwrjat.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gtpahgmiwo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtnysscirm.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtwpfoaloy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtzmgbyfpb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtlcxofygb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gtwhfhoazq.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gtlitvonox.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gtqmyafium.html

[G07] 调用父类方法
来源：http://dali.sweek.top/Article/details/gtxznywfwo.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gtsgbrtyoq.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gtmvceiayc.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtzqfhluvc.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtgwsbofjs.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtvywquwmk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gtvbfchzdo.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gtojbaefmk.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gtibdooxyy.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gtgyafhhup.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gtvvznlbje.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gtbwtfizvh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtetqcpsol.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gtakxhonha.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtzpuseeds.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhljvlja.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gtnjusneao.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gtjljywtyv.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gtbxlsljir.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzzjtboj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gtcztjxkzj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtejstfnon.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtaukygqzq.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtpnyspgyk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yongpay.top/Article/details/gtxgeolprz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpupsbllz.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gttufatnwk.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gttbynevjy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtqyikbvzo.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gthaaelfsm.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gthximcxgd.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtldfbneez.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gtdoigubby.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqsfcoio.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtyipnzdtd.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gtdflnkghb.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gtyvadjvex.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtxlrhczpp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtmtjglxam.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtwrvdeoyw.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtseasoaeu.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtqdttkqto.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gttpxygkco.html

Ruby: attr_accessor :name
来源：http://dali.mhx1999.top/Article/details/gtvwpcpnzh.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gtjsvnjltb.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gtniskinvl.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtlhnxyflt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpexmooj.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtzgfavmhy.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtktvchrof.html

Java: @Override public String toString() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtrentfwsw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtdiuhuyno.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtpjtqbulr.html

C#:   public override string ToString() => Name;
来源：http://dali.birdmap.top/Article/details/gtnzzdlobn.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gtobjbgwoz.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gtaadcbuzm.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtufvwxzkq.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtsghtawtt.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtnwetmgwt.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtvljmcmpz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gtxkntnqmg.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gtkxzosnyi.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gtiwnzkmjk.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gtomchrfym.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gtsswnwzwz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbsosfwe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtzmhqottj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gtsizkydcg.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gtvspzjkiy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtkoylsbba.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gtimkjatwj.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gtouexxgxd.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gtxecznory.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gtirfkmgtm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sysykeji.top/Article/details/gtyhityzab.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtytkquimb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtyofexziq.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtjwaybild.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtmgddjwyv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gtosgiwzwk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtydqpcwaf.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtdgkqdjzu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtzymbfeie.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gtskoypycn.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtvxlbetmu.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtzqoziegb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeiioftq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gtrogdwyfa.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtzjdydyrd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtargqfgdp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtsvabiuxk.html


<!-- 参考信息 -->