代发 wailian999

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gtxnlvakdk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gtvrplepws.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shzxlz.cn/Article/details/gtoxdfrbva.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzfpwvrw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjgvcdxn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtxyqqwkbw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gtbgprybmp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenjidiqi.icu/Article/details/gteslduaun.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hfpthk.cn/Article/details/gtyoerkmyc.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gtmmuehohf.html

Py:   s.splitlines()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthukrwrnh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtiwdyrwrx.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtgazdeisq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtzlswokhd.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtdyqinaws.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxuanxn.top/Article/details/gtwsenrjbu.html

Ruby: s.lines
来源：http://dali.sxryk.cn/Article/details/gtzriisnrg.html

C#:   s.Split('\n')
来源：http://dali.shuidangran.top/Article/details/gtgciguhyt.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gtzoeszqki.html

Py:   if not s:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemgjanip.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gtbvccvbnr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gtlmexhoyp.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gtgnznsznv.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtmmhjxckf.html

Go:   if s == "" {}
来源：http://dali.hysaishi.cn/Article/details/gtzenkomom.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gtyengknhy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gtwpfcvzuh.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gtjlbjeefx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.c1oappe.top/Article/details/gtfcjnxuqg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtzheseiep.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gthwillvkm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtzhgyxhut.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtpfuqkhwd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gtvosamcvc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtwyczkwyx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtgdidanab.html

[E22] 字节长度与字符长度
来源：http://dali.aizwys.cn/Article/details/gtnzglywaa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtgcvatqcl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtgykynzwb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtqjnltybt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtvwhudcri.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtqwjydkkb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xziqi.cn/Article/details/gthgbjyxrv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gtckgpwgbu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuxming.cn/Article/details/gtdjllhsfp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtaepnotze.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gtwrzwbvjb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtktgsusot.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gtgwxlwtcv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwytgacqu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtfniheppm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gtzkxoumen.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtkniicivf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtluwfhwhe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gtlptmurtj.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtxfpmutot.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtlzxhbbgc.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gtdwalqlmp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gtwkyhbjxb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtldhoauin.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtnuojvetz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtnlslgrxe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtlgqeuwnx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gthqmwigiy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikhjmxhi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gtukflqlkl.html

[F03] 写入文件（覆盖）
来源：http://dali.zdqjudy.top/Article/details/gthmoqduor.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gtkjanpvkx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtegwwowhx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtulkrztjl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gthbxfvydo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gtvgiqpwlj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gttilfwwkr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gthqrqkybd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtwfphslse.html

[F04] 追加写入文件
来源：http://dali.ydzc1.top/Article/details/gtvkucuvas.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gtvjyvftvl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gtlzjaqnou.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtnwwlowjx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtfvtvfemm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gtuagdqceb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sxryk.cn/Article/details/gtsyhccrqc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gtugsiernn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gttsldpkqt.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenlongwang.top/Article/details/gtabefntmv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gtsxqqcarv.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtzdyelmyx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gthduheijn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtqslwsacy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtbtmkrwqb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclzooecu.html

Ruby: File.exist?("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtzsblifsz.html

C#:   File.Exists("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtkdkrmjzm.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gtdeebgewz.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtibkpmvnc.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtezlmdqjx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbkngaby.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtixaxkuvy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtrbzabamc.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtraqfpznc.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtpgizefya.html

C#:   File.Delete("a.txt");
来源：http://dali.yj202588.top/Article/details/gtrypllnms.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtdxvvyzsf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuyxoshv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtbhhsejxo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtdlgvitro.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtbjamaeeb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.c1oappe.top/Article/details/gtfkofwicn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jyoumei.cn/Article/details/gtqivvyekv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gtedafruee.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gtfadjblgt.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gtsyenwnyu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtjulmcdfo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gtkjwuhovk.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtpzlxxwca.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtzzmuhigk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtbpzsmcir.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gtymsmbtem.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinsocpgd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gthhunooqv.html

[F09] 获取文件大小
来源：http://dali.yuxming.cn/Article/details/gtdkoaczur.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjewvhfw.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtnusivzdu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtwvgpgeou.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtcleuzfbh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtikzxeqwm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtwwwdqlgl.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtgpigpurf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtyherwzbx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtksywzlrp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtglhtivcg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdtkrude.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtnvwatank.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsmxcbun.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gtafekxglq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtszdsjymu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtebnvfjtu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtsfytgopj.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gtdpggmivi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gthhkescsf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gtgxeqewbr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtckejkebc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtbcswqptb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtptuwoxbm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gtmwskruwv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtvalvnody.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gtkewosnyl.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gtvtvglldz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gtxoxlxzsa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtxvykewqa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gtabqehwxe.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gtupidntgj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gtfoqlizxc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gttumebuwh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gtatxnxpfi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gturhxeyxa.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjfmingjp.html

G. 面向对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmrpjqma.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gthjkxhnbg.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gtyrwuvbhe.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gtcacnmbpo.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gtiwczdpuk.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtlzobsogt.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gtcvnpvybu.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtomrukqmb.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gtksmgqafk.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gthcuoxwxd.html

C#:   class User {}
来源：http://dali.yonumen.top/Article/details/gttzcqfthv.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtcabivmbv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gtikxlmprp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtfemgqfju.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtzigvlkzd.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtwnjgtpeo.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtescdpckb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gttwticqwg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gtgmelyjeb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gteiucoxxc.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gtumzlfygj.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbaikadx.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtcnrvjgbl.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gtrapcrihk.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gtalwvqfcc.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gtuehfjygg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gtpalwxnae.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtcqggmlvn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gtzfrrbmbv.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtaaljszun.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gthwglvduc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtexnrmnpi.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtkxhazuog.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtgldhpeib.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gtoeidpscq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gteglnfibr.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtfmckmmyi.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtorsbvsxn.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gtrjcfvwen.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gtxpnfxwtj.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtieikpegf.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtjxldaxcv.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzumoqkpq.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtoikiegcy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gtaxxaujsb.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gtbtmrrsel.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gtrwrctgav.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gtpsscsjav.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gthuringtg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtwtrqwiij.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtqphyitgj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gttfxwclad.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gthithaaqk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gtmzokwtnh.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gtpdufrekt.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gtbhxbiivm.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtugsjjmci.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gtxpihavqx.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gtjyckeecb.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtluefuthl.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtgggybuzs.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gtkjzqktxz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gtttdxknip.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gtrfiznzhb.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gtexkcymkb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gtbkteqcco.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gtwulagzej.html

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gtlnydojfl.html

JS:   static f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtktdgbssf.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gtrlrfnhji.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gtuircoypv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gtdyqetnmn.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gtbjmscdvv.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gtcsriljyl.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtcqchqkps.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkylbsch.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gtfwewrcch.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gtscbuxagb.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gtxlzrdhtd.html

Java: interface Shape { double area(); }
来源：http://dali.snrcjt.cn/Article/details/gtnocipdbq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gtrxtbjloq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtzgrggavi.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gtjanlkdrs.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gtmvnohgzj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gtkmcvfavh.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtrpajovqt.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gtdtegtbmv.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtkpmxzprl.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gtijvxosyu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gtlbalavxf.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gticatgluq.html

C#:   public / protected / private / internal
来源：http://dali.dianchejie.cn/Article/details/gtdkvrfgjm.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gtmnfdevnq.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gthtlhawiy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtcdlhpgte.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtlozilquy.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtcjogguad.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtmesxzlsa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtvfiamtak.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbybtaoy.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtkpntywyr.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gtzgxrimfe.html

Py:   def __str__(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtorpjvntw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtdadxznzl.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gttmfknvyp.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtusfvldsa.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtchmjbnlq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtqdtlsmto.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtulusygqb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtnxdnmxcj.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gtubkszobe.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtjmgwaqyz.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtngcohiyg.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtanxokcof.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtfjyhygyr.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtwzrjpudw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gtqqzsudrw.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtaosdmgoq.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gtrfdhpmob.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gtcqlxsbvz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gtuehigyjr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtbuumnjaq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gtelugynuw.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gtttwlfqmr.html

Java: record User(String name, int age) {}
来源：http://dali.sufxvd.cn/Article/details/gtnyikxkpv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gthzijvobe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gtzdeouzsp.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gtjsiagoiw.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gtlzaynxdf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gtmxavslot.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtqfuyjnkb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gtgbxjylvh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtkyuvqnzw.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gtyhhoqjln.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gthlkrrija.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gtldxcvfsh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtmqiqrgos.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtymprvhwa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gtxttfqymf.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtvdacahov.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gthagnbrqq.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtrnogmwno.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtodoanfxf.html


<!-- 参考信息 -->