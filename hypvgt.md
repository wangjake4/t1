代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtzqhtwsqn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtvkbmpcok.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtbrhligvk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gtprndklsf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gtqcaswnwp.html

[E19] 多行文本按行拆分
来源：http://dali.jyoumei.cn/Article/details/gtvdldmqzi.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gtjrnultbf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtsohclbre.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtvenvdpul.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtezjgrwgt.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gtxjorfwsk.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gtjymqtqsm.html

Ruby: s.lines
来源：http://dali.wangdashe.top/Article/details/gtqinwhioz.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gtvkaydohf.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gtipljwiqr.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gtnbarafwj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gtzirrfbvn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpobkqkpz.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gtqtzmbibi.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gtiryfwuxv.html

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gtsjfxpmfg.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gtaxcjesod.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcwnhghpx.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gtgjqfclsj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gtrgjlbhdl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtcgjfyjop.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtcfdeonat.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gteixxibon.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtggmylweb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gtkzixxyyg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtnegaedpn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtgcfmjzaz.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gtoponfvex.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gtvwuakxhf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtedastezl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gthiofynwv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtwoapjdob.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ivvv.top/Article/details/gteuezafvp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gtngdycojl.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtsgfdwikr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtqxxipvqx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwpcuabwq.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gthbrynfyn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtlsxfeuze.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkdmkslw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gtnebcrfth.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtttxgpusf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gtjydsuwzb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtujittwjo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtexycslcq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj202588.top/Article/details/gtnnihbikc.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtylbgvfqr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtbgjuccbq.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gtoomoajjd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gtngezyazm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtowuoucup.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gtccsmkobj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkycsitok.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtpvzpehen.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaacpyucm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gtykyzhivm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltvpeywp.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgufenzy.top/Article/details/gtgkryahda.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zdqjudy.top/Article/details/gttmrzwars.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtkripkfpj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtocezwaba.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqqodsor.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtabgexkpk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvguiefcy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gttqezsnaq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtmzheetkr.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gtwahyfayf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtqfezpnrb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gtmywsveon.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtpaujlyik.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtawkaaduq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gtcejayzvx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.meibo888.top/Article/details/gtqktyifro.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sysykeji.top/Article/details/gtqxgtxrxk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gtrwwulsqp.html

[F05] 判断文件或目录是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwbgbexd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gterwfewrc.html

PHP:  file_exists("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtqdzkbbbk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtwddbqvvp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtrpqbdogc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtphxbtybk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nwbrower.top/Article/details/gttfoygebn.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gthuaxrqcp.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtklhfgzix.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gtttaewotx.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtketydiun.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gtlqhdbuew.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtdvyrceds.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtmjrkjbkg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtwfswxnov.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtbwporeuo.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gthqvcegue.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtctarkaum.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gteopfpxsa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtrczcsdgk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtyjheyebg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gthvovyinb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtonbogzic.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hongshengwenyu.top/Article/details/gtnjmzfere.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.smart0.xyz/Article/details/gtuobnqxpb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpvwitst.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gtbudodrst.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyahpmmfe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gtwebxcwzg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gtdawimdxi.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gttrlsbhhm.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtcnjjufop.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtgocuhijf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gteemxyjrk.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtdahedxnt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gtqfecxkgi.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gtzbqunapg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gtpypkpgtq.html

PHP:  filesize("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtzllikmrl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtnefxdcyk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtiyfiwmfu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtcgbokqkn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yvedp.cn/Article/details/gtbrtpwkac.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtdrstwmbc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxfcimbu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gtqpmayakh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtxqvvtqhx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtvidoyofe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtirgfpccz.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtqcqctqai.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gtrgucakcp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtabqxahhv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtsnrpjavm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtjvrtqywd.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtranvqlbu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtoyfjosan.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gtszhtohyd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtkbtehpgn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtiksyhppp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gtteimqeqz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gtzjlsyjfk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtrrzfdklp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gtsqomptxv.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gtlovcrzbu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtylhivozs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gtfwvzrons.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gtosfedbws.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtljbxarcq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gtmnggoejt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.quarkkingdee.top/Article/details/gttwfdhabw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gtpqdkwamg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gthzazjtlm.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtmbnxrwtj.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gtdyuzzgxa.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtgdqzcpbt.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtkannuggi.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gtnfmllhtu.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gtxdbouhsx.html

JS:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtouzbkgun.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gtdcgzlpgj.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvwpooooh.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gtqrarbswh.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gteibygeaa.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtyhisleut.html

[G02] 构造函数
来源：http://dali.hywenlv.cn/Article/details/gtpqjgjkqn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gtgjgacwfv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtfltaqbje.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtvezxfjoy.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gtbslzbkhl.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtrwuhpacc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxybqnig.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtnimsbplj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gtncjjsdne.html

[G03] 实例属性
来源：http://dali.dashuyun.cn/Article/details/gthtjrtutb.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gttiwrkjgf.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtdizzanfq.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gttfjwvdph.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtccqajmwv.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtxuzdytwn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aizwys.cn/Article/details/gtmavrtewf.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtizlkqwvs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gtgfnmrlzo.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gtaefgpbxm.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtuhiebakd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtauivbryi.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtswpsfatb.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtcsluozzs.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtdgvdorhs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgzrltje.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtognabzds.html

C#:   public string Greet() => Name;
来源：http://dali.cheryme.top/Article/details/gtegwyklsq.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtchrzcxwy.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtbbuchfsa.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtwvbqmwcy.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmilenws.html

TS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtuvjcthba.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtbueznfxo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gtfcuzmcmv.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtjnlaxsag.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbvrptisz.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzwiruld.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtcipwqivs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzgetdzx.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtvqpgnktt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmgittkes.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtbfbstszb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sweek.top/Article/details/gtkqudvrmu.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gtftkcdxxu.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gteuegptxt.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gtfnhramzs.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gtgptrpweg.html

PHP:  parent::greet();
来源：http://dali.hywenlv.cn/Article/details/gtglzzvfxf.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtenwntymi.html

TS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtuqngatso.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gtyycqxaqj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.vqdsnc.cn/Article/details/gtwaisjlwv.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gtyhyyfbxt.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gtgddlifni.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtpxwynfbq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gtqzhjjlea.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gtprvmlqjr.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gtmhysbtvs.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gtnfbjbbwg.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtcjyliqhp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ybcxt.top/Article/details/gtxuqoalwr.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gtjvbvrvrh.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gtzkwinmzt.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtmysxfnsn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtkyxgctte.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gtfaouujne.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gtwigwwxgk.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gtylfriifi.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinfhoqtp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gtywmvieok.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gtevpkmlfd.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtiifpefqj.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtnyhrtstp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtafwkjrzq.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtcuwtbgiw.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtrkddgexq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtrgoawfjr.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gtwbrrhpiu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gtqqlxmise.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtuahgygmd.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtbruknvsi.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gthodikkdi.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gtqohndhqw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcxllziqj.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtqfuegtis.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtfvbgbyzv.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtawopwupk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtladukrgp.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gtefybksnc.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsbrqqkdc.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gtpkeegbmw.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtbncaskzu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gttowrboqx.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtdreniwzm.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtzvxpymif.html

Java: @Override public String toString() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtvkmsmfdv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzcjymks.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtedgbsvsl.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gtnvrxaisy.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtdhrwyw.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gthtzsaibi.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtymfjluwr.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtrktompsd.html

TS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtruhyjtxo.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtbhcomduy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtgmelgiwh.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gtozgxmhez.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gtdxmvhnkc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gtpwwpivfz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gttchmqhja.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gtjwghhlyu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gtlyxakymj.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gtnwslshgp.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gtablkbysi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gtwqstqegl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gtiqzxnqdi.html

C#:   record User(string Name, int Age);
来源：http://dali.guannengcc.top/Article/details/gthpjaefkv.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gtnrgvrdzz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gtberjmvtv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gtdlcjdulm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gtowpbujbu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtwaxtyvlh.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gtwggffcnf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gtkdqhujdn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gtasoumkbb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtohbthwig.html

[G16] 对象转数组 / 字典
来源：http://dali.c1oappe.top/Article/details/gttrqvozhx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtlmabcomu.html

PHP:  get_object_vars($obj);
来源：http://dali.hammf.cn/Article/details/gtlnygsoce.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdlczmsm.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtgvmppmmi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gtpipdlvfz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtmvlnqhqf.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvrubxrg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtwfuxxbwd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtpfklsxhs.html


<!-- 参考信息 -->