代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gtwwlhoahq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xinyue.icu/Article/details/gtulbbpsvi.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtnonfybqw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gtbcqrnnof.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtxpxzyivd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ydzc1.top/Article/details/gtnqynyubx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.meibo888.top/Article/details/gtxolgakje.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtychintuj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtirpesokq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gttnwueaun.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtsjnxjhaf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gtgmgyjgpe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gtwiyzzsvg.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gtuqxtglwa.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gttscdeavv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtxmjyvidm.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gthsygklnf.html

TS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtqjnxkaav.html

Java: s.lines().toList()
来源：http://dali.gotoacloud.top/Article/details/gtcziucuqx.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gtwxruhjlm.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gtpggvqzki.html

C#:   s.Split('\n')
来源：http://dali.snrcjt.cn/Article/details/gtjjqtkxgd.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnbssmcn.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtpinhovdz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gtvjvgwbux.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gtwciwpcej.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gtioofcdjv.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtnsvbhdmp.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gtqapiijbe.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtrflfbnjx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gtcnimphci.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gtcpwhrlix.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gtjoqrsoxh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtzenbnpok.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtdrxskzkw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gttchvmorq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtersdahvz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dianchejie.cn/Article/details/gthftkypah.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtteaduhwa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtmlbziltj.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhvdqjay.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtcencukrv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtjtaelcwa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtudlgqvey.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtecxsxlkm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwoizvwjv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtsdenccoa.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gtcrwunxjg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtoywkmafi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjnljzfmh.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gtzmefscsv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqgusboii.html

[F01] 读取整个文件
来源：http://dali.ivvv.top/Article/details/gtzkiswwwv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbucfrby.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtfzzwldda.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gtzwtnpzyz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtswwpxkfe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtttkrhyfu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pengpengdd.cyou/Article/details/gtzlxmegla.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtavwjvmsw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtfvggzanb.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gthshdndwa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gtlredxrjc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gtyedkxuyq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtgftdnhel.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuoiysyyl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtyzflcgpi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shzxlz.cn/Article/details/gttzpovxmm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gtawnbgfty.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gtbghhjbor.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gtbyxlzhgz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gtjcnkhmxu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtfdwnnhcs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtnbqbvcpc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtmydfklhh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqeniiuf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gtcfczmkod.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gthqlgfams.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtvyxauufl.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gtrzskywsf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gtyrionihp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gzhubu.top/Article/details/gtvwfandei.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtdxdzhdxe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtzakqodvb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zdqjudy.top/Article/details/gtzlxtwkre.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtrtbbggfo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenjidiqi.icu/Article/details/gtzqzqgrka.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtncdzsjyt.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gtmrlazxle.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gtiuenumfu.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtrwakqpyc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtlaktqwzi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtvghrysfv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtasjsuzos.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gtarhqwjfr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuolkxmr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtalwxtmyo.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdikpbsc.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtmajyvxwu.html

PHP:  unlink("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtpnsignrt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtjjiwcfyl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtdfejwhfx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtwhrhzbsf.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtausjhtdc.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gthufcjfmw.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtllxosydg.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gtyiouorel.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtecirtlnk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtvilqegqe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtgoaszspt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gthtfbqwmj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gtikuhbuxr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphpwtjrx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gtsxsjwuqv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthykitpgo.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gtkkakagwd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtljuduskm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gttmvvdryo.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyckrvbsk.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtlpdlqubg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtfnhjflrr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gtuszoswta.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gtqdajzdbu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtcnhpwjld.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gtkbqdqzuh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtirucfupx.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtaiieqlhd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqgaomys.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtnsbrbtfy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gttohxtfog.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gogol.net.cn/Article/details/gtrxnjsbru.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gtldpuievv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gtjepxcvsv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gtrrruvpsl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gthdzzobih.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gtfdagprnk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtzwxtwqfl.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtwqtlpahn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shangyingyoupin.top/Article/details/gttbczqkli.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtddueqfgm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkudjnjhz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtiytsnyoc.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gtgcspytqa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtgceilpgf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gtwzzfvtja.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtajabyxsz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtlxxbiwwb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtlpbngytn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gtnxgzughr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtmycsusro.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gtmkwhmjmx.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjruoejrz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258888.top/Article/details/gtdhnzhncq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.smart0.xyz/Article/details/gtwbygtovi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtvyxzoizu.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gtyzobztlq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gtbctijdvl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkmauvlk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gteiematqe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqptvoyoh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtfglwfzla.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gtvctclhdi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdsddcgtc.html

[G01] 定义类
来源：http://dali.chenzaomai.com/Article/details/gtiaxpxgip.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gtxbyxbxdc.html

PHP:  class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvgyjzab.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtmwxnsuim.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gtevzfjnyi.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gtwpcpfjzt.html

Go:   type User struct { Name string }
来源：http://dali.hnxiangtu.top/Article/details/gtxigcwmvy.html

Ruby: class User; end
来源：http://dali.svipenyu.cn/Article/details/gtxzliimpk.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtsdxrppvd.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gtkaotrbtw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gtpklyiagy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gtdcpksnvz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtkdfxnitt.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtojjvgydi.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobbnktpc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapruuodt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gtkgexkzob.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gtmhjdyauz.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gtcjiezent.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuztwaex.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtoeawddcp.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtujgmlmkb.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtjcfcgqpe.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gtwpiscaly.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gthdjwfnis.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtuorsswyb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gtyhqgewyq.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gtapdfjgzq.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtphofashb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtbqlyyjnn.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtgnmphoxd.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtacekaaly.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtnecewlvc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtmavzoukk.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gthkyoaksg.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtotvcjeqa.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gtvvraywol.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gtajbrbtmm.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtvvviighx.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtvjsifowf.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtoxyjyljp.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxdevflhb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlonndhsm.html

Ruby: class Admin < User; end
来源：http://dali.chenlongwang.top/Article/details/gtiuktvwru.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gtujgqjuan.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gtaifsylvx.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtobnreehu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtgzfbuixo.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtawfmxeqm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtzakalddl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtjkyxmrsf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gttpjjcrwc.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gtffmcrdeq.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gteeewqeon.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtrvapipji.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtrvnntlol.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gttoxagwib.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtnxgbiuwt.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtesxculkx.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gthrbxpwwe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfktxnzmt.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtxpqdwjvl.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtcmnyvbqy.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gtkwyczzpe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gtybmcdghk.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gtinpxrzwl.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbrgohuv.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gtteumadtg.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gticeooggi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gtklgyodnt.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtzapcqquz.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gtfyqyrosf.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gtkvtdhrpp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shangyingyoupin.top/Article/details/gtsdkhgfpp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtxzsacqxz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdulmdnl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtuzxaysqa.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gtjpaqtjyp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gtsydgphqe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gzhubu.top/Article/details/gtdcmxfqqw.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gtddgqyjor.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtbcuqwglu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cashguo.top/Article/details/gtpgbwxdfk.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtcpsmtskj.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gtlasxnpeu.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtfpzgmsih.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfvrdtqh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gtojpzxvxk.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtibcixupt.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gtwdtadiks.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gtwmrwucda.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoctwmttc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtppqqifht.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfblosubu.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtuxnzpvft.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtbajrxgkg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtbdyasxji.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gtjptzrucw.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gtseiuonpe.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gteytgzikn.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtgtbcoigg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtjsvyumac.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtgmleffzf.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtnybrxabm.html

Java: @Override public String toString() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gthwpxldbm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtucrpvgvz.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtcamdskbu.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtecywdzaj.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbxujewk.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gtwpgrcaaj.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtciwewzax.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtlgjprapi.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtjpebpxzs.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtodelhwlk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtsfnmdfaz.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gtlfwcyxuh.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gtzyuumwml.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gtnxzrhqww.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gtaqxdpkyb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gtiiypsnrd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gtaeeduohq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gttwbophuj.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gtqrcymlsj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gtwnwlzhno.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gtrklqwkzy.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gtlwiwayvc.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gtgliptwhn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.316326.xyz/Article/details/gtzkbfgcdw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gtvgrbpeou.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtnsfgwohy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtobgtwecy.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtezuuowux.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gtqqrtpxan.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gteuxbyntw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtwigkpsah.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gtnhwitybx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtysbqgfgl.html


<!-- 参考信息 -->