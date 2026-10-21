代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtmilkrydf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtksrgrxje.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtrsagbhzy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtbtwxhenr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.svipenyu.cn/Article/details/gtwujtmrkj.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gtwebigfrn.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gteynbnyui.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtsggdpbrk.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtwydbibqk.html

TS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtyteogrit.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gtdepatgty.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gtwpxqatdi.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gtbyazpqwt.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gtklnnktdr.html

[E20] 判断字符串是否为空
来源：http://dali.aibaodan.cn/Article/details/gtcaadcrsw.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gtyphtnamy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigfzy.top/Article/details/gtfyiepnqy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gtbltqyupr.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gthapgbxrg.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gttxbkcywb.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gtqaumqrgt.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gthytndwjl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjmbwzrf.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gtghhwffls.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gthgpnoeco.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtxgmpppiy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtajtwczgx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtvnushviv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwjnvzfa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gtavpvhgik.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrrtwexc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtypnbmonm.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gtfmxlemru.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtnpvrwdfm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtkzzklqfy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtrbdkmvzd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtqlbpxvos.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gttqauiaem.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gtdbylntrx.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtbqwarzfu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sysykeji.top/Article/details/gtgrevaaca.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpeowfyxt.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gtbwjqslml.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtloqmmneo.html

[F01] 读取整个文件
来源：http://dali.zdqjudy.top/Article/details/gtznfzcagh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gtmcpsjeqk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtpwhuxodz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrjpkvgk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtkjncrxli.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtdugdwbpb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtsihycbdb.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtbsidddqw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtpfeczbut.html

[F02] 逐行读取文件
来源：http://dali.redwolf501.top/Article/details/gtkuohmvlw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gtikteebry.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.meibo888.top/Article/details/gtrexqmuki.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtdleazdko.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtyapjwitf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtyccemodm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmleaftcl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gtwsaqbjjp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gtrfwszzhw.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gtzkessmah.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gtsinjgxbr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gteywqcsai.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtgouiyqgj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtiopqjtbt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shuidangran.top/Article/details/gtxksjinyy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gtzguqlaym.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gtxobeunex.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtlhrwbnyn.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gtfbvjomqw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtynlakhal.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gteunordtz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtcpizpdrg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtgvgzkzaf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.redwolf501.top/Article/details/gtjcymtuiq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtxhliucdn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj202588.top/Article/details/gtfnpbmxcn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtlfviqmbf.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gtbfvfhapg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gtdbazwcsb.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtduagowij.html

JS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtdagsqmwd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtxadhsulg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtomuqnbcm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtyldvgjgf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtdmdzmtxq.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtmscsdvxv.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gttsbeypuw.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtieeqwlfa.html

PHP:  unlink("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtqsjrvabg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtbiincigl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtjglvdgyc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtbsymfcie.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtzjfjenaj.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtlrhqxpma.html

C#:   File.Delete("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtwoutsrlj.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gtzhsakxvi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtrfzpmkis.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtogvjaiee.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtfyfklkdi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtgtazxohp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenzaomai.com/Article/details/gtfcaogscp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gtbdlrpapn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gtodvumavp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sufxvd.cn/Article/details/gtolfhpavt.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtnnoybrml.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gtczlwuhyi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hfpthk.cn/Article/details/gtddikzdkz.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtyxormbav.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtondeycht.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gttrhtciat.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtjxazttgd.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtkzmwwuoc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gtpjiyqgxf.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gtdbrrubcf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtrkilmjfh.html

PHP:  filesize("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtmpgtbzhn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtmggqvvcs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtakyooskm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gttsicjeaq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gttfjhyxfl.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtvshwfajw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtedzhnnfk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtyipwelpo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtmyqbuguw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbszajle.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtnisbzstu.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtkyxvnxnf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gtcgvyyquv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtlqjuddvi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtvfydjmnd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvatzbzm.html

[F11] 复制与移动文件
来源：http://dali.mhx1999.top/Article/details/gtuwocbrqg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtdvfkslfc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gtmfnjaran.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtgpcqkhun.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gttbakoifx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gtwpnhcdxo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gthiguqdqn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsreppwk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gtoryfeeuq.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gtdhhgdusi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gtdqclxiux.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gttpakregf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gttlmbanxp.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gtzaoryptk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gtuimgkcgw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gtlmkrggic.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gtmnrhfsbs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gtuayxqcaw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtcezqyarc.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gtrvrromdi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnbuqccen.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrifzgqiz.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gtdmmgeuka.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtcthfjinw.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtbhkavjfx.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gtwcgtqeym.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gttcxqhiou.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gtnwgnevqb.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtxktqbbck.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtjlddgufn.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gtyricnduf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gtgaxngplk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gtieatifau.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtnleefcgg.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtwpsfyfgk.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtqakckqfw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gtyrkvvxxj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gtbhyaxrja.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtobtkegza.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtwzprcbbf.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtkccjsrcu.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gtoymppkag.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtwyalmyqi.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gtjhoabssh.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gtzzpsdhdc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gtkzdwdzgy.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gtkuhrsqud.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtjaacbcij.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtqrtihvxr.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtgogyzwbl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtsbhsbtdj.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmaayttgi.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtatbqryro.html

Java: String greet() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtoiosbnmm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtuepwjode.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtsbzzwcbx.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtuyiqykgf.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gtpmbhxfwa.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gtqsefkvja.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtahsmisqw.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtcryjydto.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtuhandbad.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtialesrca.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gtbkstmeae.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhxdiekm.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gtzncuueoj.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gtnnuiicmw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gtplsnbknw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtsxhgrzns.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gthbkjwbnp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtykpybgzz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtocezkbaa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gtdolxvyhg.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtlmbfkyaz.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gtngfxhxfi.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkolhrppm.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gtpkrjkivq.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gtybsclhsn.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtjungagcv.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtaftwfgpd.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gtoukquxer.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gtmyeailsm.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gtyfngonmu.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gttkiplvvw.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtkulbvcms.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gtswqhjuwv.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gtiidlspan.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtwprekgwa.html

TS:   static f(): void {}
来源：http://dali.hywenlv.cn/Article/details/gtozceiwtu.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gtgujgadeu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gtkpqcjkxx.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gtebjwllhx.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtlmvmbpdp.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gtadxqbmep.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gtaxlaqovp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiebekac.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gtdjmvcqzv.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtnxjclahd.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtzwxfangb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gteamnkygi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gtqzypzrgg.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gtkitreeme.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gthxriaxiv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gthovnkimc.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpizovlbc.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtehoccbcq.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtrvdkgcnp.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gtttlnagqr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gtipsisfjd.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtbcspahbk.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyqcqpzj.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gtptixkxla.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gttjuwsdbq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gttydtuvhh.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtvvyugbul.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtjemzkpdi.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtjgfgktcb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtgwbrbhiy.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gtzzxsexca.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gtvircwldy.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gtwhkfozcn.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtlsgaauxv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtbeletksw.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtttksjngn.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdisgrqzb.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtvrhyglrt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtmyjnqwoa.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtpwxxvqik.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtsoxmlnoc.html

[G13] 判断对象类型
来源：http://dali.chenzaomai.com/Article/details/gtnuwlmudo.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gtgmflfopf.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gthtcjiwdi.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtyjabmbpb.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtqlmwvcwj.html

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gtlwqdwbfy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenlongwang.top/Article/details/gtyxtzpsds.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gtkforxwle.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gtdtqzutiz.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gtfluopxso.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfcdbthh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gtazgxdrev.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gtgggndhhw.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gtsopcexts.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gtavyiuspp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewpgwaak.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gtsadmjphr.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gtydcmjpnx.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gtvvtbuzxo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gttyoucyqu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gtsofdzkme.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gttoljqwqk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtgraillqk.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvjsxltv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gthrnzvuho.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gtjdpasdix.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtdiizqneg.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gtqpplkrgg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqvodiyj.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtudwwovov.html

JS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtbaxmetst.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsinjswct.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gtukbzbitj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gtkliyxulo.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gttnwtghue.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtijehtzlb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtjdgqgkhu.html


<!-- 参考信息 -->