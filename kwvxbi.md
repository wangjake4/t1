代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gtprzktvyw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gthalxxxqx.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gtylgdvhcn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fzhhl.top/Article/details/gttgjsrkdb.html

[E18] 模板占位符替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtoagkyeyu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gtxdikpquk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shzxlz.cn/Article/details/gtmpuiubmf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtrmcvemvy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtzbvrvsyp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtandhljjr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtcfktruyz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhixingplan.top/Article/details/gtfqcifhub.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tian-w.cn/Article/details/gtnftgxcdv.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtnwqfloiz.html

Py:   s.splitlines()
来源：http://dali.tanke756.top/Article/details/gtprhdtnjv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtgwjrvzja.html

JS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gtljgoxamt.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtvjclsnwd.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gtrfhoiacm.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gtjbutmrkh.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gtrlzgvkvr.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gtxwcrcwrq.html

[E20] 判断字符串是否为空
来源：http://dali.yonumen.top/Article/details/gtpmszoqgs.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gtknzmxutb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.snrcjt.cn/Article/details/gtipakkrgy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gtocdknans.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gttfopetlb.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtzuvchurn.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gtxuxjukls.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gthephxphx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xylfe.cn/Article/details/gtnwlsmjuu.html

[E21] 超长截断加省略号
来源：http://dali.jlsjyb.cn/Article/details/gtpmsufanx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.feifeiyinyue.top/Article/details/gtikepilpr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtpafimixl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtberzgvge.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtoekbqcus.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtscypelpl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sweek.top/Article/details/gtcsaifpki.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtbhypxrkf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtyewuykms.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gtjtclletc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ppjwa.cn/Article/details/gtxwltidyb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtffcyyakw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtezzrzokt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gttxlxighm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtkuofghyr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gtbkclxamw.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gtfjmxyece.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gtwljfgrec.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtglwyfiqs.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtgalizxlg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvaihjfmo.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtjihbjqra.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jianghu66.top/Article/details/gtcrlhxfjv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cashguo.top/Article/details/gtkrigrjfq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtfhassqba.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sweek.top/Article/details/gtuoofqjtd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gttfpuhzyt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tianlin.xyz/Article/details/gtfpteguzl.html

Ruby: File.read("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtuzdjhldr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtijmpuejz.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gtqwlatwuc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gtthflucak.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gteldspxgv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtojxkwrtf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtfxtwcbvx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtfwrtmtxx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gtqjavbiov.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gtzucauvub.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtyloxaicr.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gtmrtsqwsc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gtddaqiuhh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtwydfkbbf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtqbgsuely.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gthdikypvn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtuphxbsxy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gtrrshdjek.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aizwys.cn/Article/details/gtswubixmz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtodjtncly.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gtfruklagi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gtldydzpcg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fengsongda.top/Article/details/gthltyzqrn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtltfjgorv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtxtlnykys.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxuanxn.top/Article/details/gtlxsmcquw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtvumakoqi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gtayzdzpgs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.mhx1999.top/Article/details/gtmtafbqoq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtafemktco.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuxming.cn/Article/details/gtipjqdsfq.html

PHP:  file_exists("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtjbktkgae.html

JS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtouxvkhsq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtrkeypjmb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtckpvhgas.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gttrzctuac.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtfpunqpol.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtseanidnd.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gtcedgvkir.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtuvvavpdi.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtynokjzzf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtrhgswohb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtyolzqbwo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtwuobexxu.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjqysngy.html

Ruby: File.delete("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtdjsusovx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtkrhsccws.html

[F07] 创建目录（含多级）
来源：http://dali.zhoulong.xyz/Article/details/gtnvwexnnn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gttpkiclfc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtzudnlexo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gttesspzrt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtgrgritef.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtgpmorefu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gtfokamlam.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gaohongyu789.top/Article/details/gtotsxkmzq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gtdnfwlspj.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gtarxjvikp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtkgnncz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtgrhpqqxb.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtwgtwkpsd.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtxostvxgx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtxlestijf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gtyrzlqmoc.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gtfvihrgdo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gtxbmcooip.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmezgbpj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtahuwoxdz.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gthmrsrxse.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtxuofuqnl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtatgcttfi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gthheejuil.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gteevjyycl.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtskqyorbh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtxfkkaxig.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gtqotjbnpz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtphfmhtlq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtfxlaczze.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtbyulqyie.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtjwnoeuww.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hfpthk.cn/Article/details/gtkaullnuk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtipyyqsjl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtdvjpuwvq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtrfyetqyw.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gtcxrevxoq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtancchikc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtjjnxbwgd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gttitjltqf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtnzuhoeam.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtyqllbpvs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gthxxershd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtnoluwogm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtovohzauj.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gtrellmftg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gtrkgfwhix.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gtcjvcwfrx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtsgzxjwgl.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gtgxhaxwpn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jyoumei.cn/Article/details/gttowenhzu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aibaodan.cn/Article/details/gtgbmqgvbc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gtgxfbssfk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gthyolwvon.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqokquwyx.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gtarcbwwcn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrjeprzxs.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gtkrlfjkqx.html

Py:   class User: pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpspmvjmi.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gtpfjswjqo.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkoowomfu.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gtjqaueqvh.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gtmkdrkfxs.html

Go:   type User struct { Name string }
来源：http://dali.mhx1999.top/Article/details/gtgredracx.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gtwhzkgamn.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtrbtwvobf.html

[G02] 构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtwcclqjdm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gtrstyksgp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hammf.cn/Article/details/gteuchetmw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvycvucbq.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtnlfhexkr.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtihrhbhdh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gtwlnbxupb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gtcvyhonqm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gtzmnukugn.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gtrcwemrkv.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtnhimonvx.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtrbibekom.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gtarifgqhr.html

TS:   name: string = "x";
来源：http://dali.ehwqpu.com/Article/details/gtjydoyuob.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gtdukzrdlx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gtiqdiudap.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gtfhhrnllm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocjlpzjt.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gtqdwyfjut.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtekmtboht.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtrduoioez.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtrjcvigxx.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtryqmjhme.html

Java: String greet() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtqryontka.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtmeyjtacb.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtiquqvdrm.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gthtpmoldt.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gtwbbbunmy.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gtejqnrmmo.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gttvkrptrd.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtljjsensb.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtmzejmiqf.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtsmwijoxe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gtcelshjft.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtqowwigzd.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtogvoubby.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gtkkvdbmdz.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gtymnlremy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtzazxaeua.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gttwpzblpv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtxlzzpjjh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtotednzfn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gtbqsprjlh.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gtgdyholdr.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigfzy.top/Article/details/gtjigytyqg.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gtjpmypnld.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gtssgmfbov.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gtxeikyvrm.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtqvguhnhf.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtdussroas.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtgftlwcpr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtpihwlkkq.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gttqgyesng.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtttwlszvu.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtojabdziy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gtpijxigol.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gthehcwhwn.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gtxvkdderb.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gtgnhhtyoo.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gtllobufnt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtyeicowqi.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gtngihujlf.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gtxhppopja.html

[G09] 接口 / 抽象类
来源：http://dali.daria6918.cn/Article/details/gtwoqzvfws.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gtvwnjtfac.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gtboyefuqh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gtwcvbgatm.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gtvvmsiuah.html

Java: interface Shape { double area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljmuskdo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtfmcdhdcv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gtcgvwztpq.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtmeqhmxas.html

[G10] 访问控制
来源：http://dali.ppjwa.cn/Article/details/gtxehscgij.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258.top/Article/details/gtirnhhxnj.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtprlhufvy.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gtleayntst.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gtbtcpxnll.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gtcianqczn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gtviabwipt.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtyvcosdgm.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gtqtaxrzbf.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gtklfqioty.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gttbiissuv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtvtzueari.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtprmyqkkb.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtihyluvoh.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gttwutevhe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtbatacfrd.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtbzpvejql.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gtttyxgkhj.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfvzkrby.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtqbytknzo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtuvmcsdnz.html

JS:   toString() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtbhwfmhsh.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtjyuvolcm.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtqdadmdko.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gteyttqyof.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyubhamir.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtdybsubav.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gtwbwnusrt.html

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gtusldsnbq.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtftxsiucb.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtiyrwmvik.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtootgppyq.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtegjdatnt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtmsrpdvhq.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtpsfxhpqu.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtulrelrpi.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gtjrjnjxsi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gthmrtltar.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhongyouzk.top/Article/details/gtldzziqxb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtlcleanoh.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gtglyijlqa.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gtpyedawgj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gtrgqxlizi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtvordcvph.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gtlzfxbvki.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gteyqyttrf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gtwxjjgbdm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gtbiygqnrj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gtmxurcucl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtlmwgksld.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gtommdipix.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gtzgxwncou.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtdmtqjvkk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtwppzppwi.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtzfslbjkf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtvukqrdit.html


<!-- 参考信息 -->