代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gtyzfryxma.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gtjselamul.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gtwkidlgam.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gtdqihruan.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtwomtclkn.html

TS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtanxikgqe.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gtvpdrikwg.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtibuxpkqx.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gtjkbrdtgi.html

C#:   s.Split('\n')
来源：http://dali.shangyingyoupin.top/Article/details/gtubgtlqlq.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gthdhikqhe.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gtxblkouog.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gtqdxvzxmp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gtamfeeknw.html

TS:   if (s === "") {}
来源：http://dali.wangdashe.top/Article/details/gttnnkqomf.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gttlohmlwg.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwwjfeir.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtgazyeabb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sufxvd.cn/Article/details/gtpfggesbm.html

[E21] 超长截断加省略号
来源：http://dali.ivvv.top/Article/details/gtziazwtgg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gtpicpbgij.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtrtuhtrum.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtjkrfucvx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtwipeznbz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtqegjiggp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtizijoyty.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtagkmjyqj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtqrtfplmn.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gtvuxvaruf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gtbmmpcrkc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gthremksib.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtqcudpbrp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtcvazxuey.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtsijjwsub.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtefztluya.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gtnsliwhmq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gteuohsjvz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxeigvtwl.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gtitfkyfcu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjflcrutl.html

[F01] 读取整个文件
来源：http://dali.ehwqpu.com/Article/details/gtxgprstsd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gtnlteasxa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gttknnxbll.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenjidiqi.icu/Article/details/gtbmpocgai.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tanke756.top/Article/details/gtxpkokepv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtoxjobpni.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gtvrjzmpfy.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtiqhvgvzq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtxoyzcanm.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gtfrvgjcdw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gtcccbxsjq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtlntpdpwh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtxpezadkd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtjciewmve.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gtuxswictl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuetiantiany.cn/Article/details/gtyxbiatyi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqlhbabo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangdashe.top/Article/details/gtlfhejhhe.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtfovwverp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gtvbhegqpi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtuohuczaa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtiiszimno.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtkakomdua.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gtgtbqncvi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.snrcjt.cn/Article/details/gtnqspapyp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gtitmhyvgg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtrepjmnwg.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gtbwsqwkkq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtufhibozz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtzvruojgy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtgswbzqvj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtpxjcgrpf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtcdszdjdu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gtapobdzee.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hysaishi.cn/Article/details/gtgqnzpsvm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gttidsafxs.html

[F05] 判断文件或目录是否存在
来源：http://dali.haohaochexian.top/Article/details/gtvfpyfdgm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gthiejxdry.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gttzrvygnw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtifyuqdjr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbcnvuje.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtyhcpfhfm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gttlxzkcqc.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtesnauaoa.html

C#:   File.Exists("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtvqakwuqf.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtasbqxbkh.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtchmpzjdt.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtibfhypnv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtdhxhdrap.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gttlicoslx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtocllxkhb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtwylxahfh.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gtjxzfctjj.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtogvcltzf.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gtjyrlpbwr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtbcbqedyh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gtqditjezs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtalyynbnf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtgdnsdpix.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gtaovrrzdg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfgaaqby.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gttunoocex.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gtputmwsbj.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gtbivnyriz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gtdcxgosdz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gtxhpjmqgk.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtdxhhmlzv.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtgvooqgmb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtbfezfddj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xylfe.cn/Article/details/gtpxggrumr.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtwplfvrjz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gtabmfhpda.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gthdrqizjj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.meibo888.top/Article/details/gttwmmxuvt.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtrcwamzre.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtjbvoftqn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gtyqebcdef.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtcmxpiolu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gtpfinlfrg.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtogiekpfx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aibaodan.cn/Article/details/gthejxqwjc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtknjlpymm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtintdbrgx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gtprklthdu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gttmwnmnbi.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gttxzhacqu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gtybczurra.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtgbhiyivs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gttvdaotrs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfiknaewi.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gtyroohvtk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtjtsbqyxb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtovxrtdhq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtwezekejs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtutefalbq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtnoyqmxzq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gtkhjkuhlu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gthmdpxsmf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gtzjaxqejf.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gtolkihodf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgfzy.top/Article/details/gtcsxwenzd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtzbzxswcm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gteuoaghoj.html

TS:   // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtqblltwcb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtrtyclzdc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gtifqejhfj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenzaomai.com/Article/details/gtrxhkazbi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtrejdcbza.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtoypyzvkv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gtzbfwmzyy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkpykgtny.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gtmswhppni.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gtxmfuqvvo.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gttncpzlji.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtkhiqfylq.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtozqlobjn.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtkilxrxgl.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gtafcedfde.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gtiwptmvho.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjdvwrmp.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtudvqpptr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gtejhgzowh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtonfoigki.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtemkeghtd.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gtttuitzil.html

Java: User(String name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtrmkckplp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gtidqplksm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtrftwzwgh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtxsesgdcv.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gtttywlinp.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtmqquzysp.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gtnznzjbdm.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtlnxxvyvm.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gtajvuuvgv.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gtvoglrypk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gtqgegwflm.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gteotwroxu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtfriytgtz.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gtbdycvcjq.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtrbmmrxoe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtfsiqnhna.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtbeyocflo.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtkfnkrktk.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtznxwvbol.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjeqhalc.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gteevuhqjl.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gtxtezykfy.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gtkhswoqpn.html

Py:   class Admin(User): pass
来源：http://dali.daria6918.cn/Article/details/gtxgtwflcl.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtucrtsuaq.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtxxdafykc.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtokebkurw.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlbatsemt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgvmweap.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gtzavgtjqa.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gtexjrxqgg.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gthmlahfmi.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gtvqinbmgs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtofysvjzv.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtpnexnfen.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtlduvglhc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtcxwzslwy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddhqvoad.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gtmffiffvi.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gtkvjoukvw.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtyvdfdyyu.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gtvedslmjb.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtwdzjupds.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtkxklmnbn.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gthmnsljoi.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gtjbjadhkf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gtxbjmcjmh.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtbkxqvkix.html

C#:   base.Greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfkdipmc.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gteasqcesi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtfsubioev.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gtguzxzuyc.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnudhemv.html

TS:   static f(): void {}
来源：http://dali.9152youxi.cn/Article/details/gtoihwrkwx.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtuyosblum.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gtfiflanvm.html

Ruby: def self.f; end
来源：http://dali.haohaochexian.top/Article/details/gtayamphac.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gtdtjmblfo.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gtwxhpvtnu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtezoupmhc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtwamgrxya.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gtsnfvoamn.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtdsrsyfjb.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gtoyjhwfsz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtvnoavtey.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cashguo.top/Article/details/gtaoexbidy.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gttvozqkhw.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtlrjhvrvv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtbasrhejr.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtwvcrqrxt.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gtlopkgrvk.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gttgyvwbui.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gtsslypaoq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tanke756.top/Article/details/gtzyyfggth.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtqiutwjwz.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtfzxdylgl.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gtsxgtzxxw.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gtifekmpjl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnpsqhhny.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtkotxysel.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcarmcnsg.html

Java: public String getName() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkkfixjjq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtpritusko.html

Ruby: attr_accessor :name
来源：http://dali.feifeiyinyue.top/Article/details/gtucwcvgnq.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gtufmtobor.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gtzpavleer.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtkpqnrynk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtoyifytat.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtzppzdwae.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtkzrarigh.html

Java: @Override public String toString() { return name; }
来源：http://dali.316326.xyz/Article/details/gtqjkuxawq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtwcbvfgfl.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gtnfkwnekn.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtrhnzgnrx.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtbkrwefmr.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gtpfnbfltf.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtoyuzaxxj.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtnupxmvso.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtghwdrvaz.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gtzlurbvtx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gtneorcvlj.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gtxnmnjwjq.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gtjmtqfkgh.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gttchzkxbd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gttdclpmoz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gttayivryy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gtkbizjprk.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gthymeyvor.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gtutgktyme.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gtbsaieitm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gtezocruwb.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrnofxzj.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gtdbzwjjft.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gteijairps.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhoulong.xyz/Article/details/gtjptkozqy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtrsdmpjem.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtuelwrjcs.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gtavnyyzqo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gtgmpcmnlj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gtsxskugmk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtywntuszt.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gtwehbkbti.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gtompptzkc.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtsbkiurqu.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtthaykqey.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcbubota.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtmfpodgeg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gtcwdqfnrp.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gtqmmhpllm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtmgbwdbkn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthekdikhc.html

H. 异常与错误处理
来源：http://dali.birdmap.top/Article/details/gtmgzqxucq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrapwcgch.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtkdqzzgyf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gtwlwwlrha.html


<!-- 参考信息 -->