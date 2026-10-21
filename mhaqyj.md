代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gtbhmgueyq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yonumen.top/Article/details/gtjcrftkam.html

Ruby: s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gtlbbofjlf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gtgsdvbenc.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtjzbzuzaf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.mhx1999.top/Article/details/gtpsoprdut.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shzxlz.cn/Article/details/gtwjtpvfap.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtwubrnuls.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtadnpofbb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtcfzbvxmz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtlixjpqgf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gtprivairm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gtbmmytwid.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gttevlxlxa.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gthilwaiqr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtxjfwafjm.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtdrugrnqr.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtvaberlvg.html

Java: s.lines().toList()
来源：http://dali.havefunace.top/Article/details/gttqiouops.html

Go:   strings.Split(s, "\n")
来源：http://dali.9152youxi.cn/Article/details/gtjuknlyvv.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gttqkqlkdv.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gttktrbadk.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gtwzgfupxu.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gttzbwlona.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gtbzkrymjc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gtvbasptkj.html

TS:   if (s === "") {}
来源：http://dali.tian-w.cn/Article/details/gtunzyvgfs.html

Java: if (s.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtfloaefhi.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gtjkzqobsb.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gtuexpvidt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gthagxewfp.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gtoonudbbk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cucudq.cn/Article/details/gtqokhgmaf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gttlrlache.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtuhzkvhvg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtjenrntvq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtuzxafeyj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtzgysnbdf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtznzjbjng.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtrfrhhoac.html

[E22] 字节长度与字符长度
来源：http://dali.yangfankeji.com/Article/details/gtpzvgqamt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gtpyclqaum.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtsmkelliz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtflnxkvdp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtssxnyfem.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtobmieszd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtkioswjgp.html

Ruby: s.bytesize;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtjfflhmjz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gttaibhsgs.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvfvqiefy.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtxlaoadyi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtckudtyyg.html

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gtgbrcmrll.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gtvmlwfpbb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtcnkgaypl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkliyuhrw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtiyasvscx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtdzotvrcy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gtsbakxtdy.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtduscsfuy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtbfdmyxrn.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gtmnjkjcdh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gtfntrcugz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtbpvtcjwv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtyzhqejyo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtdnymglfe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtjupdkyjb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gtazjtjsbh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gtqfvwkgsv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.redwolf501.top/Article/details/gtofototzo.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gtbfqfgtbb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gtvdbqvmqx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtnvmisqbj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtwmmlferp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtpjejgceg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gtleuhkfzm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sxryk.cn/Article/details/gtwxcbikgx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgdeoprg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtkargjkmu.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gtvfdpnobp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtaeevncos.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gtprmwnnat.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gtepnfqcun.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtojduksce.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyihhskk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sxryk.cn/Article/details/gtfhjfwosq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuetiantiany.cn/Article/details/gtfiqidrsm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aizwys.cn/Article/details/gtzepivnma.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gtpucynyjf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gtahkkrlzl.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtfxjwkbpa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtuxdudlxw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtmmgpsszy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtntcwkzzi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gtbcgpukpw.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gthhzguhhg.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtmxofymuo.html

[F06] 删除文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbwmkfda.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtwqrhyadj.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuijfqiv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtdznwnfea.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtythzidgv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtfukbwksg.html

Go:   os.Remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gteaonlafl.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtpndrinpx.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtzpvjoeak.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gtxnpzzwwv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtklamoenk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gtahenyizo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtskwlowcd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtbypmymon.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gttnzsvsxb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jyoumei.cn/Article/details/gtnwbaaxar.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.feifeiyinyue.top/Article/details/gttxgmwlrb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtbynxfcky.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gtbcyzyloa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gtcmmnemyo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gtphaiupgb.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtjillfsnu.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtwsitvbke.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtijjgbfvn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gtzfyiqecy.html

Ruby: Dir.children("dir")
来源：http://dali.c1oappe.top/Article/details/gtzgecpxhw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gtjvhxcqbc.html

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gtoxsbzpvu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtrzszufef.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtgjalazzp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gtbuuinkof.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtkdpsleks.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtscwfsjxl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gtldsafkxm.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvpozdwg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gtqjtwnwml.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtporpwxlw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnygasmgp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpvtmhpz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtaagezmaz.html

TS:   path.extname("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcfzbfhh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gtrhjmhjkd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtfbwunloo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtjeaxvkyd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtuwnemirq.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbodwqxs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtdygszcjj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtofzslsoe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtnqyjttsg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhkqswcb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gtfclzgjyx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fzhhl.top/Article/details/gtbpxxnkth.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtbertkwig.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtoaczvptu.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gtfjryubnt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gthetdmmoh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gtncdfycwa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ydzc1.top/Article/details/gtbhumzxdh.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtnbrbxcmd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gthonutqhy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gtakcfxgnv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gtxqchdkru.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gtrcjgzclz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtlshzqrzr.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaatuzhpq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxweoiufi.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gttmkxyukq.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gtdbdbrrns.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gthiaohlqj.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtrlfhjzml.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gtwjfceyhg.html

Java: class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkesllkma.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gtqosgshmq.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gtlcxrpnqp.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwkvvvdp.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gtxgryrhlu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gthliudhtj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtwmusfoce.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtaoduacuw.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtaicwdeen.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpzxclgzr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gtatqmeinb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gtoytahagz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gtmduhorao.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gtustwgjit.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtyutnjrbg.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gtqzfqaakn.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtrxgrubyn.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtplqmiond.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gtrivjgjkb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtrecqtccq.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtqvxccycg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gtgfiqrguw.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtqcapmnpo.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtrwgsqtpw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtrcngcmok.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtdqpqarfg.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtcdzfnbzg.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtmnemeyku.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtiixketzg.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtjdauqnvk.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtyumkjhpe.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtpvtxrtuh.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gtirvvfsqn.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtkxfrgzss.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtveogjava.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtgglduaki.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcfkrshk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtutqqafre.html

Ruby: class Admin < User; end
来源：http://dali.0kj1m.cn/Article/details/gtsbzhdtmd.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gtfrpwcnib.html

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gtfmmlalam.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gtkynpluxg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtzbuooeqc.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtxnjhewdv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqawmulc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtqgjjhqej.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gtzhsvrfxg.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gtjbiwucaz.html

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gtrobngtrd.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gtvnfrmuue.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gtebkfykbp.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gttwrkfhxp.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtmjkwsrzg.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtmxysbqsk.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gtoporlohv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gtlfcgqjwr.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtmmzhqxne.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjyifqab.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gtorwkssdb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gtwfleotvj.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gtrjunjvaf.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgwolozax.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtgkvyzyez.html

Java: static void f() {}
来源：http://dali.guowangkeji.top/Article/details/gtfdixjirf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gtyxvfypkh.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtnknqjgpf.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gtmwzkljlf.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gtrxufekvk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gtwkrensto.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gttvqugrjt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtgwofpyac.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gtiexnwzdp.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gtuheoerdm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jlsjyb.cn/Article/details/gtkzawkede.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gtjfclwavs.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtzftglnux.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gtfenlvmmy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjpkumhn.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtsyphnant.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gtasdtxipg.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gtnajcdrie.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gtmwohfyht.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gtruvukire.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtqlnkxnkp.html

C#:   public / protected / private / internal
来源：http://dali.yueranfly.top/Article/details/gttkoxoumz.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gtxahtzksj.html

Py:   @property 与 @x.setter
来源：http://dali.quarkkingdee.top/Article/details/gtcougntzt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbzyffovp.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtfngbfpbs.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtovpnltyr.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gthfqmduak.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtrcphhbsk.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuhawizd.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gtwidgarli.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gtooiuhdkk.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gtaplrcsum.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtfpnijazz.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gthtmrgdhl.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtsdpjumrn.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gttkyrfsni.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtoylutuoq.html

Ruby: def to_s; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtdtecrbdb.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtddeccrnb.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gtjievwznd.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gtxgydfmac.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtbycntlqv.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpacqqvix.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gthwsvesyg.html

Java: u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtdfhohsyq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gtkytsilop.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gtlgrtzwio.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtblzahilz.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gtggejqdgk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtwttlcltt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtmtwtzbnc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fzhhl.top/Article/details/gtwovbpnmv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gtcvtwuomr.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtlbvbyzaj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gtykjjhvbv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gtuhsudyfk.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtanojzhlu.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gtaqckduei.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gtnuawwowy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gtxjfdxvlk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gtejmdwzwo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtaxaapera.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gttbhncmnu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtcsilkttb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykkhrocn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtscdeunsr.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gttbgejqes.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gtntwssybm.html


<!-- 参考信息 -->