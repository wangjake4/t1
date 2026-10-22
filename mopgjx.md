代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gtoeaoxcjj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xylfe.cn/Article/details/gtecjtunem.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtfwhbysxg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gtluqtdizh.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtjyvtaiof.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gtqtnwfdft.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jlsjyb.cn/Article/details/gtixfcklic.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtndwpkjmj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtfomaxpaj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtdmattbzm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtvgonymtm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtnjyayrrv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtbfsmgdza.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gtyngfgast.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gtcvshvski.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gtnphqndll.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtzdabxiqz.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtuzxazgie.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtrehxqvhe.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gtpmaoooxj.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gtergpeicx.html

C#:   s.Split('\n')
来源：http://dali.gaohongyu789.top/Article/details/gtpfcywqww.html

[E20] 判断字符串是否为空
来源：http://dali.cashguo.top/Article/details/gtsiwgjjum.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gtjvzfytft.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtxhuxuoch.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zdqjudy.top/Article/details/gtpagjdffl.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gtqtgiwzoa.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gthexvzfxx.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gttulzdxdh.html

Ruby: if s.empty?
来源：http://dali.zhixingplan.top/Article/details/gtfnmnezrl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gtnuudjret.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gtofpnjfdx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gtcbcxngio.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtprlhscdo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtfhocbkci.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtpehbcwnk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtnlxaahzl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.feifeiyinyue.top/Article/details/gthcirqfko.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxogtbywr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gttoqmxjht.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gtgvwjcbib.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtuswbqdar.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtayizxbsa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtvaawlman.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtbmsvkwzs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtfdvwievv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gtyvwytqft.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gteoyiozjf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gteenmcbzn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtbvkirsbi.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtamswjmah.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtktpltxzd.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gtdgeqivhg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gtclalzbjf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yonumen.top/Article/details/gthpnjoyfn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gtgrvwtppj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gttqeyqkrt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gthzizjsgh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yangfankeji.com/Article/details/gtpadlqlna.html

Ruby: File.read("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gthntfmcho.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtttnaaoos.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gtzmbjvigw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtcfiykaum.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gtyflrmows.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtbeiivaip.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gttqdqpbxi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtdeggozwk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gttcorgxse.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tian-w.cn/Article/details/gtkoztblas.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyooyldd.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gtlofierhv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gtqzhpexpn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtqkhtbcjj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtsibbljyl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtyppovniv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj202588.top/Article/details/gtdqwimeod.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gtihdjksal.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gtcsbzmflc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtqhzkliwc.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gtpzwfwcvb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gtrhkiosba.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gtfrpywhay.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtvdrszwqi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtjtzaaxez.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gtqdacyjjx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zycfv.cn/Article/details/gtudnsichp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gtlkfmhqmr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gttnhhzwrj.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gtdbflfytp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumpyyzaz.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtxfbweahu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmozqimpy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtptwkjcse.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtdovehpbf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gtuuilxojb.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtbijusbfh.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtovxsznbq.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gttcavvxjn.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtokgqdelr.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtmrcppric.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gthuqlgugc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtvffajczp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtlgkvzvrz.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtncoamiwr.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtruyqkhwf.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtgusvhakc.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gthqtgjfcj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gtkfaupaxw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gtdtzhkfwh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gtllhkoqjh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtuhtskujt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtabysaabu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cheryme.top/Article/details/gtdsouhanl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gtkxkkcdpb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gtpgdvunwd.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gtjysrrozk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzcwfbqm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gtrsurmxzw.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtfxttkfai.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtaazmiedt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtcuimpprh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gtenkswwzg.html

Ruby: Dir.children("dir")
来源：http://dali.sweek.top/Article/details/gtqxymqaii.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gtgjqbcjdu.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gthtccbban.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqrouvzcy.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtwedwlueb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtsqormuit.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtlzvriyyi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtwinbevqg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gtnubygjbx.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtghtyobhp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gtmqwmvlse.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmdwjkdo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gteqymnkga.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gtqwedohvx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtqgcjfosu.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwlhrfwie.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zycfv.cn/Article/details/gtzekncspx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtvneogcjj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtufftisea.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtgnskgwbu.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gtxqxllsro.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmtdtqhm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gtefocptat.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gteooqfbbt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtmclnvtwc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtmcemngro.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gtttbfnazp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtihaiyfwk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gtqzlkblls.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gtneosnkcm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gtusfqjbcs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gthzysrpvi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gtpcshljww.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gteziasbxd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yueranfly.top/Article/details/gtjyvuhgnd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtbpwycfoz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gtytmmzzid.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fengsongda.top/Article/details/gtbtvfeasv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtduwvxite.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gtjlbbqxcb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtflcjueju.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtqyfixvvy.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gtygmjtqgs.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gtwzdgdtfr.html

JS:   class User {}
来源：http://dali.meibo888.top/Article/details/gtzvatrrad.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gtvyaecxvq.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gtzjufrtev.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gtvwmkaumf.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gttksnasle.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtzztlhhbc.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gtyzgwaiuz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtireoeasg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gtxbfhxcdi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtknbuvpen.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gtjugdeova.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtbibitdom.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gtqmifxtug.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gticozpvbp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gttegrswgf.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtqjflfrkm.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gtxuzouwba.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtnytctkgq.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtrwiwlldp.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtgrkmvkab.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoalqrprs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gtfpklqkkl.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gtpqpmniwq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtnpwnopux.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gtegvinydq.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtkrzrsmxf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtysvsheqg.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtyvdirsyl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtrorpsnre.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtgxcotgbt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtfqmgieso.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtcjkeoljd.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gtdvdnofpe.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gtalsaozdy.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gttwqzzgxw.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtrpaakmys.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gthptjvrde.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtcgbvhzrm.html

Java: class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtrgiudtmf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gtgqurxzzd.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gtkthqorgx.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gtfllchrra.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gtccfnzemx.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtyjeoxawq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtevqhlinr.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtnhwzztrj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtajlqccjp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtttpoguxq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gtjcbrpuwx.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gtdmtahbcs.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gtriijxosf.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtihwklims.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtbaxpjiqf.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gtzgnivrpw.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtlsnfucjq.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrthbeyq.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtedctkgoz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gtddsooeie.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gtnulinokv.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gtgxyjpzua.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gtcvdjhhah.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gtxcunypaq.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gthsmciaft.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gtravdwcdg.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gtegaitdkf.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtrwrnoluh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtnjwacvdu.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtgrifjoyd.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gtnamkbvaw.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gtbsisxnlm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtsdzmptoa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gtelstqfua.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtbycgoixu.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gtjhmgdfrf.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gtbextioxj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gtgrpwtewy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gtittfprbd.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gtdqegbutv.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gtivqeruyc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gtxnwehdnc.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtgenytrre.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gtqifitcvh.html

TS:   public / protected / private
来源：http://dali.sweek.top/Article/details/gtcgnravns.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gtuezshywx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gtlctcmbbs.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtslbddtxx.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gtskkfvypm.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gtzbxwssma.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gthzlmccod.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtjeznfegv.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtjutocwly.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtctzlzmth.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtmijqgrif.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtetplrfwh.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gtxjaxbjgi.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gtangxfjhz.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gtolextqzw.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtmrytxbfo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtlyawfgal.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtpobgvgqm.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtwywelgju.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gthydlwvzd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtawhvdado.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtyybuwmwj.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gtdjcngyko.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gtzafqfzlj.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gtlkieytaj.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gthwcmzfxl.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtcdwqdtyv.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtwbljpjoo.html

Java: u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtawmquvkt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtkitltaow.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtravnewlz.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gtefskpzhl.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gtvqpfwjfo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ydzc1.top/Article/details/gtsetqqeaz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sxryk.cn/Article/details/gtcaxunwho.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gtbdxasqbl.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gtrrejzanu.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gtcuhsbevs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gtgclxjbnc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hongshengwenyu.top/Article/details/gtjwfjgqml.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gtbrosknjs.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gtfnqdkack.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtuxgolnvi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gtlhwmkqmd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtzqzmvkjx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtiwdybflh.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnudencfp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfkzmjve.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtjqjfpoao.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtkupnnaul.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gttvgasyji.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cashguo.top/Article/details/gtuivlwgjk.html


<!-- 参考信息 -->