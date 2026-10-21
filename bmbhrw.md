代发 wailian999

[E18] 模板占位符替换
来源：http://dali.jyoumei.cn/Article/details/gtnzregsia.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoiagaxp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtwgrgajps.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtpskffxal.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtovawqjgy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtwusjdwir.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtsinkmbfk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gtpypwtbwj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gtomlgfvlg.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gtvqjgpjim.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtqanookte.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtucuekdrx.html

JS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtbbtbqkgn.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtjtzlujqx.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gtlyredseb.html

Go:   strings.Split(s, "\n")
来源：http://dali.redwolf501.top/Article/details/gtfvbchozk.html

Ruby: s.lines
来源：http://dali.zhongyouzk.top/Article/details/gtpwqrrybr.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtbwpoezhw.html

[E20] 判断字符串是否为空
来源：http://dali.kuanghao11.cn/Article/details/gtcphmmxsu.html

Py:   if not s:
来源：http://dali.316326.xyz/Article/details/gtjioeekga.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gtntbuxduf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ppjwa.cn/Article/details/gtjolbrsib.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gtonnmpfnj.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtthzrsbhn.html

Go:   if s == "" {}
来源：http://dali.yangfankeji.com/Article/details/gtnbpibfie.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtdcjriksv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gtbsfvzcbp.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gtthcngutu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shuidangran.top/Article/details/gtorwuddja.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzsxojcr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtbttihwdi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gttwpcyopz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtctuxbsno.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtxpfmqvfg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtiytbqyvb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtcrllzcrt.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gtokdrcajj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gtbmyympnn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtvfyuuari.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtviixadxv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtschfhroa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtcygbpwog.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtjpflrziz.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtjszowflz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gtaxsxudmc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvpwphpip.html

F. 文件与目录
来源：http://dali.ehwqpu.com/Article/details/gteoagmjqv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtkuvgubat.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsftxxxcf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtlnktmkia.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtybmgueoq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gtmuajrvyh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtqrfdnilb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtqmsgnzgc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yongpay.top/Article/details/gtjlonaymg.html

Ruby: File.read("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtpzbdydxf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtlptilxmh.html

[F02] 逐行读取文件
来源：http://dali.zhoulong.xyz/Article/details/gtqqjvnvcj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jianghu66.top/Article/details/gtsjzrlyod.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkynefbl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtagkydmac.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtqdohmsha.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtzfriuyot.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jianghu66.top/Article/details/gtqwsjibmi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yongpay.top/Article/details/gtptnirbyy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenzaomai.com/Article/details/gtpnjfiqsf.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gtnyooszwr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gttqoxnrgc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtxthezoqs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtsrlzjydn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtlaqaqfzu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.bjfxy.top/Article/details/gthewurdou.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gtgjcflovs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gtqcinkbsl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtpkoglxmm.html

[F04] 追加写入文件
来源：http://dali.ivvv.top/Article/details/gttlyceivo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtvvxnjvvl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gtttxoprrg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtxvadnjgp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtundygexh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gtfrobpmkb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gtvrvohdsq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gttoeiceck.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gtvrflmfyr.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gtgylezmyj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gtbtqgeuqk.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtgzfwjoim.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtgikpeduc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtutcstwtr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtvcddtaiy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gtbzoxwczf.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtqefrtzng.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtypfeyegc.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwradmcqm.html

Py:   os.remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtmydqylhj.html

PHP:  unlink("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gthiwstxzh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtipeivqmf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtomawzqui.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtasanbufm.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtiuqdwjuu.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtbdmbltzq.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gtddtzjezq.html

[F07] 创建目录（含多级）
来源：http://dali.pycfn.com/Article/details/gtdndwunod.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtkthpxgzp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtkflcssjf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gttafaruhu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtqhpwfhdt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gtocjrfqjg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gtrftglmvc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gtguufrnds.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gtotxbfomb.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gtvdengyie.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fengsongda.top/Article/details/gtynvvjdod.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gtvsszssef.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gthuwxfxzf.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtxdgavqjg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtjtpjzcuw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gthvynbfsq.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtccugyjpj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtyxudfvuh.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gtdybzspke.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtyizpkmwb.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgojbtnza.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtqzsvghsj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtugqnhazz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtrcsuugec.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtwxhiibzl.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtmpendbku.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gtokszavud.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gtwdjtdend.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gttvidspnf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gtnldtkudp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtlrjhnetc.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gtjlqlpzle.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gteistovxy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtdaqnbvza.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtmqcmpijv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtyacmzvcw.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gttmhjxxyl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtmpxtcwvx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtiyqkpzws.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtrmravblk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtrxxczjgq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtrczikobm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gzhubu.top/Article/details/gtgjbrthaw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtenbjsvra.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gtaauraldn.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtfdxfbvmd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gtyxvhzivd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gtdhroofry.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtxmfkjlzi.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gtroxfhrqz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gtsxoadqlp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pengpengdd.cyou/Article/details/gtignfkrmb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gtrydilopn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gtavxanspd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtysbcibwv.html

G. 面向对象
来源：http://dali.daxiang520.top/Article/details/gtxxngload.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gthyegwgig.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gtqxbtkqoo.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtozeqxsjj.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gtvfhlvzkm.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtsqygsifv.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gtiufqkqnp.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gtolatycpj.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gttapletqg.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gtjvthkfdt.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtdhkfisgu.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gtlmchphwm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gthazgxcqn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrtpfaqnq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtcqerbien.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzfimrejw.html

Java: User(String name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtgstxilxk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtlglrawdl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtswnuraiw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtuzcvaybf.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gtxeiiifnq.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtnjnmjudv.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtyuewipzr.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtheonmdqx.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gtanfihzex.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtfdbryuok.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shuidangran.top/Article/details/gtxdqbgvmo.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtmtipxuae.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gtvlpqsrdq.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtwzevmagm.html

Py:   def greet(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnvaxadw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbaspjtdh.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtsxzdxfmj.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmdhcevf.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtwvqetgsr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtpfdaqxxl.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gtvzmlfbuq.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gteqvakvxb.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gtwabwduuh.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtdimqyryf.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtvizyuoqw.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtgevdansi.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtqwxapdtu.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjqegzbu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gtpfamzqbo.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gttrmdulil.html

C#:   class Admin : User {}
来源：http://dali.jyoumei.cn/Article/details/gtprwtmmxx.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gtyfaxcsfo.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtjddanlfe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtbphxoije.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtbmpcrbav.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtnhjvvpyd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtamgurvxz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtmhyrcybe.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtygvtcsyf.html

C#:   public override string Greet() => "admin";
来源：http://dali.iojbl.cn/Article/details/gttfgkcoxg.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gtyxaomvwo.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gtxdpmkplc.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtydvfkpwr.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtdnlxhims.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtxgrvnqtw.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gteipmqpog.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gtauquxjvd.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gtdxvpveji.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gttlfjbtsz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gtaxacppjg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gtizfjeuvc.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gtzsggivog.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gtbdrsgrqz.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtqaqbepzu.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gtlvacfrmd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gtlrxhimbu.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtcjxlhaea.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtdgueplyp.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gtxhvcshjg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gtmqnkpsmc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gteornumdb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gtljasfarb.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtrffkmsgv.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gthjdixpmp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gtzkipbxgw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtfevkgjpb.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gtpmzirird.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gttxwbhvqr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gtvwpdtzja.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtqrpmkajf.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtqswoouxa.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtjrxvcmrz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gttxpzayyq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gtivqaempm.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdimtzla.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gtdigbczzl.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtzegxrsjp.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gtdpcsbxss.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtsgzulmlc.html

JS:   get name() { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtxvcnxins.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtmppdnhcs.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtvzgytbmy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbbmzbgr.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gtlmmmsvdo.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtywgxcpwf.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gthvvvxkqj.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtfcktenvw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gttwhnyqdq.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtqhevsipb.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtubiuwake.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtissqngmw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtauuytsqe.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtswafogrt.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtcrfpswxy.html

[G13] 判断对象类型
来源：http://dali.yj20258888.top/Article/details/gtzmiuqpcy.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gtoelnbkhr.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtmeempzpc.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtnvgfxxhw.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpduqpnoc.html

Java: u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtnxrpmsjx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gtayzqelvo.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gtdyawtlzd.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtqtifqfog.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gtioakmrhs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgevgkzgp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yvedp.cn/Article/details/gttcrjfeeh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gttlvmjkxn.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtewhorlae.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gtjygcoexs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.mhx1999.top/Article/details/gthfoykhjp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gtpxbsaafr.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gtkrwnczan.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gtgzfojqnv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtttqcjhbh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgtqlnct.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gtjmmeallv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtqkzlvygc.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gtksshmryg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gtenkmxcbp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gtusnerght.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtozgoipdw.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gttawytvme.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangkeji.top/Article/details/gteltphuuz.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gtwnirnrfh.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gttuymyxln.html

TS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gtpmpspklg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gtympwyjuy.html


<!-- 参考信息 -->