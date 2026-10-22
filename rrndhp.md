代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtdbrvdipr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtdvahyrlt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtabrjvauh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gtdfvmzftp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gtqzlskxok.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gtdgjonwlj.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gtegpzezad.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cucudq.cn/Article/details/gtwgnyrbzy.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtifuddkim.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtffkzmmnd.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gtunntmbql.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtvyazknuq.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gtudgdwibr.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gtipegkllm.html

[E20] 判断字符串是否为空
来源：http://dali.yangfankeji.com/Article/details/gtlalyxipc.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gtjmctksui.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gtrvgzswki.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gttmxprfbt.html

TS:   if (s === "") {}
来源：http://dali.meibo888.top/Article/details/gtrsjomgmp.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtnxcdzfyh.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gtiyafgqdi.html

Ruby: if s.empty?
来源：http://dali.meibo888.top/Article/details/gtcqglqwop.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtygoeolvd.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gtzzsxzile.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gttrllgzab.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtzpmkybsm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtylltgspi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtudytlmfl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtfhmgvmul.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gtfrowuqvx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtbggqusvc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtqhfvqytb.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtitddihpe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtdpdmyfak.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtnbuvfgog.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtnydofksq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtitfsqp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtsvwbntcx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gttkvflvfs.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtyvmgvvhs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtttzmrtwz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgjhshtia.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gtviobvgmf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdzwddzlc.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gtduhvldwy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtdqqijhzk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtkyqopybe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gtunnkfsmn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtswxrmqza.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtrmblnnzq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gtkejqschb.html

Ruby: File.read("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtehwpbpfd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtcvzyhpxp.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtapawcnny.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gtkygnpozu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaionfcyn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtsvgvritr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtxzchabpf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtthbkvfaw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gtgaspnodo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cqqwz.cn/Article/details/gtizvbygmh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gtardieuqy.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gtzsltezwj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gtiigqxhcn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtukfkzrrz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacsiubwn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtcsayevwt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtwprrrjwm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtumfawjuc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hammf.cn/Article/details/gtslnsezbw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtiovdxred.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gtxnqctfxj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gttizwzjgz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtroinmpfo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtfkswgduh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtokyqprco.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslwudtmo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeqwnecd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gtnoinpbye.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sysykeji.top/Article/details/gttmvlucej.html

[F05] 判断文件或目录是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfljzlmdg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztdofyyj.html

PHP:  file_exists("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtertzvahe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtlbvzkouj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtnfovsmna.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtuddcgodz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.snrcjt.cn/Article/details/gtyghydsgt.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtgngykuzz.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtugeszasr.html

[F06] 删除文件
来源：http://dali.xuetiantiany.cn/Article/details/gtbpdfkdol.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtikoxxmad.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtfdpfqblq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtoynvzrbl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtpblkbtaj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtkplnncut.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtcorhgkav.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gtadnqirol.html

C#:   File.Delete("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsrchthj.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gtmeosvald.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtelrtymyf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ehwqpu.com/Article/details/gtizdcszql.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtpvhibevx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtxcamhyxj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gtxjnkukuz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gtrxwhdmaq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gthizhgbbj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gtemqgaknh.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtwqdrcmbs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gtdigyypld.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gttuyqpxon.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtdaqhbcrs.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtacsmqysp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtkbuafbgd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhdjyejr.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtfobpdyyl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtmwhdhuib.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtfphvacvz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gtcvypevce.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gttkymjjyk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtkdcfthka.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtuhutiakw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtcwzphwlr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gtyngtzxdv.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtmhmzkuoi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gtuoqjfbri.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gtdzpffmdj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtpictsnfp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtnhdpsmtt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtzcxfcumx.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwuguwqi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gtyzwvrmek.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtelbpynrx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmogpztuw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtnnbbfjff.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gtexdfuavw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtivojirex.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cqqwz.cn/Article/details/gtfnsyzklk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtbzqexcxe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtxrayvcqh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gtrjyutrid.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gtmzhkevtd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtvnvpjstc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gtlmjowsbw.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gtdwbuhlxd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtfaglrdkg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtlcyaavbn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gtakipplxt.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtwctxffjl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gttsovctkl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenzaomai.com/Article/details/gtupuwwder.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aizwys.cn/Article/details/gteivhvgqd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtqivlkevl.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtuqzqnupw.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gtcdmztesq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnxkgxjus.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gtspmlmxqn.html

Py:   class User: pass
来源：http://dali.daxiang520.top/Article/details/gtgfmlrdzu.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gtddryiqdy.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtvhtusyik.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gtfrvhcure.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gtedzjzjom.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gtcsmmutjv.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gtkyfuzamu.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtcsvvufaw.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gtpjflxwyq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gtzawyadvr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtnngxmadq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gtavarqxmf.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gtxneyzcsu.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtxgjcgvsk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gtiyfeosgc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gtneweqhhw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gttsosvlip.html

[G03] 实例属性
来源：http://dali.shangyingyoupin.top/Article/details/gthwzecoht.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gtlgvfnhob.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtqssccpws.html

JS:   this.name = "x";
来源：http://dali.tianlin.xyz/Article/details/gtfgzvusna.html

TS:   name: string = "x";
来源：http://dali.yj20258.top/Article/details/gtbgwipjxo.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtzmlxjuar.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jyoumei.cn/Article/details/gtfgegeqvg.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gtsrkddyrt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtcpoeuhdm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gtwnmnupdx.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtwupoapep.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtsdotgxwy.html

JS:   greet() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gthgzedjqu.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtrxyvkkfz.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gtqaqtmqkz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtvxswiehv.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gtynjpwvwb.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtmnnmkmsi.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gtzndphozj.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtnvxndyuc.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtdilpnvyr.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtrhysgbxm.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtjhhypiyp.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtuyzhmnsf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gtlmailvln.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gtfuswvguc.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gticxnqhqq.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gtlvbafbax.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gttpplvedm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsuqznogn.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtomcoygrr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtczkkheke.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtpsrpbqut.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gtnfiptzqn.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gtpvexbmsk.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gtzjlyvpwc.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtdnqzyvbr.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gtjtpdifnr.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtkhdntpgc.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtxrqfqghl.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtdpljywto.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtbenageiy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gtqonkpciz.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtzuoywmle.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtntudgvye.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gtmcejekby.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtwjzpwlil.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gtswqbevtu.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gtbsvgvgid.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gttgsghnbt.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gtrdgcpvum.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.svipenyu.cn/Article/details/gtatxdorkn.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlthkywli.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gtvxsdzbtp.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtpnskzzkm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hfpthk.cn/Article/details/gtbkfyndda.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gtmugurxdr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zycfv.cn/Article/details/gtnvgmfpnl.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gtjuziiywk.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gttaehviwa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gtjaminelp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtdfzwtasz.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gtfxxmhlxq.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtvpetcbvj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtxuiotkog.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gttyplmkiy.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtannhbghp.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtfwphcjyv.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gtqtpsgczj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gtfjwemqub.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtnbrybhpk.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gtdjawpaow.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gtqinstzsc.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258888.top/Article/details/gtspxjfkrb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtntcgvhib.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtwiuxitvo.html

TS:   get name(): string { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtqnveoyzh.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gtazjeawdu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtwbxuyfaa.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gtjimforvi.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gtojgyfaky.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gtoltnhnie.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtthdqajsb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtrxasqjdj.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtfffexvqp.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gteeeblaft.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtkvdkfedl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gteobjraoa.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtvckfcofs.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopyvlswt.html

[G13] 判断对象类型
来源：http://dali.hongshengwenyu.top/Article/details/gtzajfyvxm.html

Py:   isinstance(u, User)
来源：http://dali.dashuyun.cn/Article/details/gtmshdfumj.html

PHP:  $u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtskbmcszh.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtbcajpgvo.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gthothvvdk.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtlcuifmkb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gtavhwkdlt.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gtzvsjosms.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfebbyqhr.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gtzxzloeoq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gtkhqobbwt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtqkndmieo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gtrphbyxjn.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gtnmunxwuh.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwlnxtukd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gtetregaqc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gtlkkbhenl.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gtgykazner.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gtgpyfmxzu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gtjyzqcjtv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtgxcpfaqb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gtjldlljtn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtdrmkuksj.html

Java: enum Color { RED, GREEN }
来源：http://dali.hysaishi.cn/Article/details/gtfhyuiylp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtrtmtnurz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gtwdzgrmsi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtxlxpswkb.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gtfslffxjs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gtvlqqvxbp.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtdwbpudzf.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtesvtkhdr.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtvklbiryi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gtrvohmfkq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gtikkudnlm.html

Ruby: obj.instance_variables
来源：http://dali.hongshengwenyu.top/Article/details/gtvjipmale.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtckafblox.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtbozjtvfa.html


<!-- 参考信息 -->