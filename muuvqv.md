代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtnegbkfei.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtbzkjouxh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttalckotc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gthihhblnt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.andypj.xyz/Article/details/gtudehunhc.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gtabwtuqnk.html

Py:   s.splitlines()
来源：http://dali.nanxinkj.top/Article/details/gtewxhvqir.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yvedp.cn/Article/details/gtmmjfdjlh.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtfwiqihzn.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtxqceljqv.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gtyundfqxw.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gtwkipilfy.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntxwmqkg.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gtdxllmbmc.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtrirqhonm.html

Py:   if not s:
来源：http://dali.chenlongwang.top/Article/details/gtfbncgjzx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gtsojmtqvh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yangfankeji.com/Article/details/gtiumfxyee.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzybbkxg.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtnhkbuvbj.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gtsouowodn.html

Ruby: if s.empty?
来源：http://dali.fzhhl.top/Article/details/gtcqxjcxro.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gtlmcnhlhz.html

[E21] 超长截断加省略号
来源：http://dali.xuetiantiany.cn/Article/details/gtcrocqqfy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guannengcc.top/Article/details/gtozuuaiqe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gttxnayemg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtduxmznan.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtkzndyybv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtmxpgqeca.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtxshlvqdi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtuuhlbaru.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtfccnclzj.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtcakujwuk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gtrkgzlrps.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtzyexoyez.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtyzplhuyt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gthawaldzc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtbhyhukrg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttssjcjfm.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gthbtpvoxs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtpdnmdibe.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthkpwmhvs.html

F. 文件与目录
来源：http://dali.meibo888.top/Article/details/gtqdifhjoo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtiaqvtgnz.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gthrpdueqw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalrmkucq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gtzygitpay.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gtdhnrgwqx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtgnctgbwc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtzuycseaz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.0kj1m.cn/Article/details/gtbujpwqtl.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtwpupwxsx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtvzguecsz.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gtfwadnedc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhongyouzk.top/Article/details/gttnfxpimd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtgvksutjm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gthqwmnuea.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtqqqlpudq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtknziqwed.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gtpzqtdjgh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gtggcvqdbr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhengqikj.top/Article/details/gtwkucgelv.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gthsldqwci.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgblscilp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtounqhska.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtnvhczuaz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtonchsczs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtwyugoctg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gttuqyktxa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gtoixxczmp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtdrliivgl.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gtthvpvskv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgxjpbxg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gtjdetfvcl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctjgaeez.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtfsmskiuy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtnpmgsfsh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nwbrower.top/Article/details/gtztlmemgk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gtecvnjmuy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gtaftlteqb.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gtcjpfltdm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtgjhiqsxf.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gtqiwdlryu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtfnoyngjp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtuasrybvl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtfqclznvk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gttqwyndnf.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtyzpwpdnl.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtvlyjcbag.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gteeanwxnl.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqkhralik.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtmncxyrnh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoldxwczl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyskgefyj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtkhpfpkcz.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtcsdwighp.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtgcqjocnu.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gtkplnewjw.html

[F07] 创建目录（含多级）
来源：http://dali.jqgufenzy.top/Article/details/gtycaxnpna.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxhdacep.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gtepmbbwrc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtldkdfuqs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtncnxuhuw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gtjkynmodw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zdqjudy.top/Article/details/gtrnqbcewr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtljjcudew.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gtkurvvmtt.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gtmyceuzhs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.vqdsnc.cn/Article/details/gtgagbayzr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gtqrqixxco.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtegicpzzd.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtddjivtsp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gtxybgapgq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtsyorxisj.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtymhsphkm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtqxjrjmkk.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gtofwvgjqm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtdlplkind.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gtafbpehkr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtumyryock.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtgqcemzlo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtnlensmkk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gtcglqruct.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtjvotfrjv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gtceljukyr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gtmqotnlkg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtejmfkeid.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtlipibxon.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtbznbojjk.html

TS:   path.extname("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtksgylrmw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gtiitcpvkw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtjpfycyhh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtffoyxrrq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtqsbmulxw.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gthpdenzpj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtonrvcdwn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gtilkrpliw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtgivqdckn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtkjokjwxp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfropusam.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gtrovzulgw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtjjgiurgx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtzbjatmlu.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gtpnjdsnru.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtbpnprdxb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gtiltxdind.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gtgcblccjd.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gtfrmdualc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdaygbdjy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtpypjfady.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gtqcxvgsze.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gotoacloud.top/Article/details/gtkxxvklen.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtcguxmokx.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gtzwhozczo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtigcuatru.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gtjfndlqwm.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gtmcetvhoo.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtpeovognt.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtiuninjlh.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gthuuaauaa.html

Java: class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgivytmr.html

Go:   type User struct { Name string }
来源：http://dali.yuanzhike.top/Article/details/gtjktzpbka.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gtgjridecq.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtcnyemtrk.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gtbiniixkz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xylfe.cn/Article/details/gtvbxucpuu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjbdqpjh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtzhkanopk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gthiuvfmab.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtiqjnudsj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gtvuixhuvn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gtfrvmwhgo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttancvgvk.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gtvpxcsyzc.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtzhrgetvl.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gtepmjofgn.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtgscogvyo.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtgkeksapj.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gtttzdzess.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gthblclrcl.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gtdhsqafsp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gtselzyadu.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkptksvk.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtwknjbbkm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtzbqzwlve.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtpseilatl.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtyqwbprlu.html

Java: String greet() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtxlfhhpue.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtgnwelwjd.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtdmheugna.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gttjmpzkcp.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtythdtkan.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtdzrhyhbx.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtixqjcfky.html

JS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gthgmwulbu.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtfhgvkads.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtaeocosqd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gthaczakkl.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gtaeltmwzv.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gtaoqgftar.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtvbnwafek.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gtuyisfrns.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtpmpmeivs.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtldjimact.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtvvbpnigi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtmgppefbl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhengqikj.top/Article/details/gthybkaxrz.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyiniwor.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtgaxnbgvh.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gtfpyxrwnq.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gtbzphwbph.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gtayjguemw.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtssqflzsw.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtbyylnnjc.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtgdvltayl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yongpay.top/Article/details/gtxnmwnajq.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtpnuwwviv.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtohzxvvrg.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gtdisxiave.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gtgiazfwlo.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtjnmwkwah.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtsuukcivq.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gtuqcsvckp.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtetwdqdtj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtgahjar.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gthmkgpbwr.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gtamaevgys.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gtpsejtckf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gtdnikjneb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gtrqgtictz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtfeocnwhq.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtvgqxabkk.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gtrszahkge.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gttyyfutgb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntnixfkh.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gtuevubnqp.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gtjupcdusd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gtyuogwljq.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtaxpxwbhv.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjaeteth.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtpjtrtfik.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gtmofznkmb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gtbyigvcqf.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtbkfgjbre.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtyxkmqieq.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gtcoasihas.html

Py:   @property 与 @x.setter
来源：http://dali.yongpay.top/Article/details/gtpbbxowaj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtkqnyqwzp.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtgykjdbhl.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtsyngdels.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtktrfjitt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtthhkejjn.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gtxbidycee.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gtawxhcryc.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtztmbfaan.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtaeiwnyau.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtircwdjih.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtvpcaruvf.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtdrovtvlp.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtfmrrvnxw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtstzerfcw.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtmblisuxb.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gtuhegedxy.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtahdbfysz.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gtjmbuftdt.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtbsygjdqw.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtokohwigi.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gthdkiifkd.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtdicqglsn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ppjwa.cn/Article/details/gtcnwmntvn.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwjvhyhg.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gtsubgeqor.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gtfogrbezw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gtujjhaiwy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xinyue.icu/Article/details/gtyrifyqgt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gthhlmcker.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gtpjnyncrf.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gtcmtnpfgl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtdcaeqyyp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtzqgnlavk.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gtfiihgucz.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gtjfdotkfe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gttkeyyvjv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gteuydaoqe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gtuntmbxcn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtnubvevhz.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gtyseohrrf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gtjavbpewi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtfyjaabmw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtofwvsfcp.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gtcaymawsq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cdnleiting.top/Article/details/gtolheomqp.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gtgihredav.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtqsrnnvoo.html

TS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gtviphthjy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gtegoxoldp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gtvluercud.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gtpwxjibot.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtbveoucds.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjwfbprip.html


<!-- 参考信息 -->