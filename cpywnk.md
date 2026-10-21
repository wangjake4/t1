代发 wailian999

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gtueesafzb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttekvrkpb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gtwufjnpvh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtsqyohilw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtjfmpiknb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtkgzswvbk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtbyqfybvc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtovomwull.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gtfyhbiaef.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gtjxhxxpgy.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gtaguwyiin.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gtgwvualbf.html

JS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtfrkdodvi.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gtosotmwss.html

Java: s.lines().toList()
来源：http://dali.guowangkeji.top/Article/details/gtouhwqhpl.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gtakhtzfqj.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gtcymeswox.html

C#:   s.Split('\n')
来源：http://dali.pycfn.com/Article/details/gtojvojiat.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gtfvcotlbg.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gtdvazycwm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gtyvhwmibe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtteelfzsg.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gtzdurslbr.html

Java: if (s.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtspfriujn.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gtfgdksseo.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gtegvwnbjv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtlvdvjnsj.html

[E21] 超长截断加省略号
来源：http://dali.birdmap.top/Article/details/gtoargjwir.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnovikjg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtbryervew.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtpdumbphz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gttfgqmfym.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisbmnkiu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gtxzhkbhmc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtpwabgwho.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtjuebakla.html

[E22] 字节长度与字符长度
来源：http://dali.quarkkingdee.top/Article/details/gtpbopntzr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtsgowtzpk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtmeeyfurr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtbnxobhod.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtqksxkeko.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtbzfsxciy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gtypjyeirn.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtzypuqbdx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtabanxkls.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbpseruka.html

F. 文件与目录
来源：http://dali.ivvv.top/Article/details/gtzlnxyzzz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtrkwixbnj.html

[F01] 读取整个文件
来源：http://dali.meibo888.top/Article/details/gthnwcllaz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gtujdvjfys.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtieuuquwi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gtljoldjme.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtcwbcwcaw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtayjksufz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.snrcjt.cn/Article/details/gtfknunoho.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gtactqwvnl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gthesazrqn.html

[F02] 逐行读取文件
来源：http://dali.chenjidiqi.icu/Article/details/gtfbhsmjqa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gtdmeqhtro.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgiurrkoe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtdxrwqhds.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtwgvcfccc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtzjrqmhzk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dashuyun.cn/Article/details/gtnxodzryz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gtwyimtxyg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtzxwrwiek.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gttmjnvmwv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sufxvd.cn/Article/details/gtiwptwmzo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtbgferxir.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtmqlsorsg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtmgvilxbd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gtbuqbsimm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gthegxwzxy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtqgafonfd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gtmcirnllm.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gtmsbhqonz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtvglckyuo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtgeplkgkk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtpebgigks.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtwhyvmlmz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dianchejie.cn/Article/details/gtjzcnfbns.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gtrootzokl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gtrzsjcuij.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gtfxoqcrze.html

[F05] 判断文件或目录是否存在
来源：http://dali.cdnleiting.top/Article/details/gtdcvzhdqw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gtfszypoxo.html

PHP:  file_exists("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtszowlwyc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtfytygkln.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtvlgymqbp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtxcpcrvki.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gtqyiteycf.html

Ruby: File.exist?("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtkphlkbxm.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtlbvupvwk.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gtkdylmpoy.html

Py:   os.remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtoyehifrk.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtvgjyxnhv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtfkfpmmhl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtomocootr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtiumwvtri.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtniyjsdwj.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gtvslbqigp.html

C#:   File.Delete("a.txt");
来源：http://dali.havefunace.top/Article/details/gteswaghkm.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gtqpvlnsak.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtbqcpzjmh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gtceiprgnu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gthmnybxoy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtzfudpixa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gtxzyqrkme.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gtkcvgynua.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gzhubu.top/Article/details/gtsqasrrnw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtsvjwovjg.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gthndeftkl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gtfkrvzqtc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtqanrllfd.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtmpylrrpm.html

TS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gtoonrykdr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtrycmtffx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gtlzqavzpf.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gtyhgtzbns.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gtxmcksmhs.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gtrkcgxrrk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtsnfawnmx.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtxdyrktib.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtfswjudau.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtrhmtnfxi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtlbkzogye.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gttfjlgowg.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtaffsqgen.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gtbcnbzdzp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuxming.cn/Article/details/gtazmqgzxk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprnlljsd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpmhktnv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtktkenexz.html

TS:   path.extname("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtzvinotpj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhoulong.xyz/Article/details/gtosqhmoxg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gthqghczpg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtwcajnpyj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtrpvjhxwj.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gtveoojjdk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtmszcckrs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuflvzcrw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtfaabkwyp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtpnbcfyzj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtgdkgcfrn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gtgcdzljjl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkxvjtfe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtxbregbgf.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtgchihrtj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgfzy.top/Article/details/gtvctwpfoq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gtxrowylhz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gtcmrhaoob.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gtltfboclf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gtebyquljp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gtgkbdmqcg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aibaodan.cn/Article/details/gtdflswhaa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtckvgtggy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtsnoqwrnv.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gtklyzekgu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdkyjmwoz.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gthzpepxxf.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gtbhosudpg.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gtbrqdnkwl.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gtbszicyzm.html

TS:   class User { name: string = ""; }
来源：http://dali.yueranfly.top/Article/details/gtspukvfau.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gtrgxevsrk.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gtjgcqaboa.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gtjlmeyyfg.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtfnozsveh.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtmlyhijfi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gtjiyfonci.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjtstvlrn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gtiqzadnjb.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gtfsrxjfsu.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtvyugpgrb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gtgihedlpx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gttbwhmyln.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtnnidrclw.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gtlhufkdxb.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gtwfwjavsb.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtnqkcppwi.html

JS:   this.name = "x";
来源：http://dali.andypj.xyz/Article/details/gtdovajnhn.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtwbzvokzq.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gtdyfqpscl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shuidangran.top/Article/details/gtldnfnldz.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtrbpqpytv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtwpklrdkr.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gtbvftnodv.html

Py:   def greet(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtyecsawjl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmmrxdxg.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtulqunwgz.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtoxumptwv.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtxxvlxiua.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtgcsvbwty.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtpfbayahc.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtcdkfqkdn.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtoemrayjj.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gtghqdddbs.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtaqimrskc.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtqujmbzlr.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtcejkvdze.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtwkhdqucc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtoilbndve.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gteqldonrd.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gtmrepadng.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtvkiyqmai.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtkpkcrthr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtudnwttbk.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkpfrviep.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtlvmzilio.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtbhtkpgqz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtogqdrndt.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gtcvlyktjn.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gtswgebgqw.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gtaueekbpl.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gtuydrwkjh.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtpuxdyzbu.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtxnwdimeq.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gttiplgthk.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtcigeiabn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gtgjkfhnxd.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gtrbzvznez.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtgitwvcxb.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gtrradwcjb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gtxqopehvg.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gtmvvjybzv.html

JS:   static f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtayyqcxky.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gtfgcddvcb.html

Java: static void f() {}
来源：http://dali.sufxvd.cn/Article/details/gthpcklxqe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gtdvaytkju.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtaxcoekzu.html

C#:   public static void F() {}
来源：http://dali.sweek.top/Article/details/gtkltjwlma.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdgkufks.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xinyue.icu/Article/details/gtttswsjec.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gtagehuwfm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtoiopgaie.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtrlhtwhlt.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrgggzlxe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gtnohrndnx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gtzdmmaimq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtsrsawrrf.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gtnnmlompa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gtdnrsgcyf.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gthatxwxdj.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gtndagaoym.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtvdvkzsfi.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gtftfowyjj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gtksgxuhjq.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtwjqxxwnm.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gtweoslmnx.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtdsuftdoy.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gtqbqsnrsx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtyqzymjfc.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtwrxbdnci.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtsezkeekm.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtzzecursd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtclcyhhoa.html

Ruby: attr_accessor :name
来源：http://dali.xuanzx.com/Article/details/gtglbsjqxg.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gtbjjrlyhn.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtpqlakhog.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtztcovtap.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtfjpokyhb.html

JS:   toString() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtwpaphdkl.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtkdoxwqpj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtkqaegjwz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtltmouynl.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gthaeoagxn.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqvboqkv.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtfpfqgnrd.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gttfcvcjwn.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtrckksfqz.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtrnbxedya.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtgrnvnmme.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtjvmcxovl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guannengcc.top/Article/details/gtwcvrualo.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gtjtbtbioi.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduyxmohw.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtalorjdfe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtylqmgtpy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gtphkvrpob.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtaseeqjfo.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtqhfxrcol.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gtsfidmlbr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtejsskcgj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtzkavzydr.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcmtxjpx.html

[G15] 枚举
来源：http://dali.jqgfzy.top/Article/details/gthtyjksan.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gtpuhtqfwx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gtocvjgpoc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gtzkabutey.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtkmdvuuhm.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gtalnmdemy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gtnvywqkyh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tianlin.xyz/Article/details/gtxnbylvec.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gttfuksbta.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gtnffcjlhj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gttnrciynd.html

PHP:  get_object_vars($obj);
来源：http://dali.bjfxy.top/Article/details/gtualvzawe.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtfmjkglca.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpiriebmu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gtdpkmtlxa.html


<!-- 参考信息 -->