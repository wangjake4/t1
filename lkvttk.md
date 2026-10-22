代发 wailian999

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtadzknydi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gtrknqmpgw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gtxzrfvvch.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtevjkfxhi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtrtpeqiio.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtybibuxqd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtddlewxuu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxssludr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gtoevwmsag.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gtwwthyshk.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gtepzjjhpa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtkjcqokfa.html

JS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtlafytayt.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtobdurfqa.html

Java: s.lines().toList()
来源：http://dali.meibo888.top/Article/details/gttiiragwf.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gtpuectump.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gtnycbnqrx.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gticiavtmc.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtourxxzwa.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxpyibzi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.vqdsnc.cn/Article/details/gtwwuwbhct.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gtuitvlevf.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfudvgyg.html

Java: if (s.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gtwdigtcnk.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gtzgzydjlh.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gtuzlbzkfv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gtmxwlsnxf.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gthtrnvzra.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtlipiyyht.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtxqqbpsot.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtpcvdqenf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtdqvhnjzl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtoncvvada.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yangfankeji.com/Article/details/gtewovqynh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtsxrgyvap.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtvxdqatsp.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gtyauzsbqn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtypvdimkv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtvzjnaatg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtfokbioyf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtuvnnkmnz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtrnfkiovt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gtmglekmrl.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtedplbevr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtvlzjpine.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtyrriskyd.html

F. 文件与目录
来源：http://dali.pycfn.com/Article/details/gtdncthwfp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbtgfjkmc.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtmbscbduu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gtqrflmoaf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gtkdmvliky.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtizcujhgd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gttqervzqt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmriypeza.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtpenfcbml.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtjyoiupog.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtymrtsenw.html

[F02] 逐行读取文件
来源：http://dali.tianlin.xyz/Article/details/gtnjjyunzb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtbpaktvgu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gttyotxmma.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtjgwcegoy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtwkvawiws.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gttuycjtiq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangshuangyany.cn/Article/details/gtwrsryogc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gtnscnxksl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgfzy.top/Article/details/gtibeomgnh.html

[F03] 写入文件（覆盖）
来源：http://dali.cdnleiting.top/Article/details/gtqkaooxat.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gtaudpnzdy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtgsvrldip.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtmmffkraj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtogkwiczo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtadpwmqkv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gtsosvlwms.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtzfhoddhd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtqqaptbaq.html

[F04] 追加写入文件
来源：http://dali.gzhubu.top/Article/details/gtcnmqenuj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtlwapsgwy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gthglczaud.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gttwnrckji.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtnslrzisf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhengqikj.top/Article/details/gtrkikksnt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtlaqjksuu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gtdsvzzhdl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gtvdshbzpi.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gtuxpzttxu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gtmidqsqur.html

PHP:  file_exists("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtgdljxvbs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtskszdyno.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgoudfoaf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtgjzrzuir.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cheryme.top/Article/details/gtenbjnmvk.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtxugpchel.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gthzszadtr.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gthbiurrcy.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtvqnbgbru.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtjsqmahur.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtaovrpgcp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtoioodsyt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtkrdfwadu.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtjjchyfoq.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtxuqplibo.html

C#:   File.Delete("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtoliynuvc.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gtrigjjefz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gtrutstaph.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sweek.top/Article/details/gtkihzgajx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtrwvtoafj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtsxbkqmjn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtwjvbouam.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtzxmygtsc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gtpzehzdhm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gtjowvgcjs.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gtqexjjvgw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgapbgihf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gthwgklrwm.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgsduwqy.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtvbjqepsl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtxofdjvfc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gtdajcbyyu.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtladbliop.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gtaiqchchm.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gtbnngmvbo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtdpmvhwvn.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdbycyyo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtqhwemcea.html

TS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gtafzojrzh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gttbceokgg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gtgcycrfma.html

Ruby: File.size("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtpkimccfn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gtvsrommom.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gthsjqtivo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtnxmhxzli.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.redwolf501.top/Article/details/gtmovcdxqr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtvudouvip.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gtyxjqbuzp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gtwkbgrkus.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtdpswtzju.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtgkfdhvcw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtqqvjckhf.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gtcnrmabpz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtbpyrwbgh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gtqsxhmqlc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtvisoajsy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtlhobthjd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtgxymxkyk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gtpzbmntzo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtzvtpkcen.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gtgbymktmj.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gtzcurhdxb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxinkj.top/Article/details/gttgdsyiur.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gtpxxenkde.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gttjnzkqzu.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gtwxlfzead.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aibaodan.cn/Article/details/gtqqqxblrf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aibaodan.cn/Article/details/gtthbxnwyv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtdtebxzal.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gtvfsibqad.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwhxywczk.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcmvfblo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmmkunhxl.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gtskxomyre.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gtzkymoevo.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gtqiouhecm.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtdiabqwel.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtimkjxnqi.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gtrlpzrctm.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gtplsghint.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gtsyosrnpu.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtnoqdddiy.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtwhvuqqzz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxinkj.top/Article/details/gtvpxlmszr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtjukwihjh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gttvygcafv.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gttenxykro.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtrmmkxjhw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gtfgelubtt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtkxyxddxq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtwvubestl.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gtrvygfbsg.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gtarwhdvdb.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtzqleyfrj.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtzrqvfszs.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gtdfxxckjv.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gtmjqlwbyt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gtyyveweeh.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtlsggzcti.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtbphquowf.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlgvpezf.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtrqflmmni.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtiorxzibi.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtneqhkvuf.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtnhlrgqgb.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtjohstnve.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtsohkpzvz.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtvcrxmrlq.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtlwlnettt.html

[G05] 继承
来源：http://dali.jyoumei.cn/Article/details/gtpnlxjbpg.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gtfkubnokq.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtmtzfolqe.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtdacxcljh.html

TS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtyurwugzp.html

Java: class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtknevvqgv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gtuhkbhasb.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtnfektqjl.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gtqvhoaass.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbwcjlgk.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gtphibrymu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtkcqybvve.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtfshlclrv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtljdegihk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtlufdjubz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gtbxitciri.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gttzpeuwkn.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gtutosobft.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtcgfwgbeh.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gtzneginmc.html

PHP:  parent::greet();
来源：http://dali.yvedp.cn/Article/details/gtkbpcmxdp.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxtvwksv.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtywizhryl.html

Java: super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtsgxxvkvw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gtqwiogigu.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gtbvaolyrs.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtvaoqwxdu.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gtszktufad.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gteybzbfmx.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gtaphehesd.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gtdmenujmn.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gtdmacqcum.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtedfddqpk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gtthzirbwy.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtycxdbxxu.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gtsporbcsy.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gtdmkbcwvt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gtebllefjv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cashguo.top/Article/details/gtnvbpwpvw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gtopodhcoq.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gtaffnuacl.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtqgfmgttp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gtseomzxod.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gzhubu.top/Article/details/gtmkjxrkrm.html

C#:   interface IShape { double Area(); }
来源：http://dali.haohaochexian.top/Article/details/gtpygaigul.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtlxlrppny.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gtcqozbmsl.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtpdvoxhbf.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gtrymoqsjf.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtwxardnqd.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gtrehxohia.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tanke756.top/Article/details/gtyjqhcqan.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtnisnbafo.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gtzefhhofu.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gtaxyskhjr.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gtstctlqwk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtwranmwya.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtxgwukoci.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtkdqookzt.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtnqmwqiqf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlbhgzzk.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfucyxshf.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gthtikkbtg.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gtojgqlhnw.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtigwyqkai.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtpbeqatce.html

JS:   toString() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtseokocar.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtiqoifnzx.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtrlkbwdil.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtbrdzjwbd.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtyiftgayh.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtpjshjtib.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gtfsiovopl.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gtbpphgwag.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtwvnjcjxp.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtikvjpcly.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtxtxlyavr.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtpkthlxaa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtnpzecqtd.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtntoioqso.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gtaldwqlxe.html

[G14] 数据类 / record
来源：http://dali.nwbrower.top/Article/details/gtlrkwmjmi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gtenukqhbc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtpvemnznm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gttasskviv.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gtxxifmcjr.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtblpwtola.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtgkzqvqjr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtptmngsgx.html

C#:   record User(string Name, int Age);
来源：http://dali.guannengcc.top/Article/details/gthiguvyva.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtrynjblrs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gtkqdsbrww.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gtnyrejmwp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gtattpxlep.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtvfdlhglp.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gtsnlkvuqf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gtncegqgec.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtrpmbtgkf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtcdamubeq.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtszohlfwr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gtkqhzoswp.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gtrcvtjsmw.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeqxrkjn.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gthfgbjpen.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangdashe.top/Article/details/gtnxxelfyx.html


<!-- 参考信息 -->