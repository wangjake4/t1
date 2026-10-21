代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtrkchgriv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtqnvodtda.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtdzepkfiw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnxiangtu.top/Article/details/gtwhiborkx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gtxuxsyirr.html

[E19] 多行文本按行拆分
来源：http://dali.guowangkeji.top/Article/details/gtejdvfbhc.html

Py:   s.splitlines()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyppzngei.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtaqbdrmvi.html

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtnglneizv.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtpmvksnwa.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gttmyfzxjh.html

Go:   strings.Split(s, "\n")
来源：http://dali.cheryme.top/Article/details/gtlltaqqyh.html

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gtgaduefwh.html

C#:   s.Split('\n')
来源：http://dali.xylfe.cn/Article/details/gtmabjclqh.html

[E20] 判断字符串是否为空
来源：http://dali.wangdashe.top/Article/details/gtmkkyxmmt.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gtcobfwlsi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.feifeiyinyue.top/Article/details/gtojjukseu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgboshcw.html

TS:   if (s === "") {}
来源：http://dali.fzhhl.top/Article/details/gtkejlffeo.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtyllggwrn.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gttykbbbnp.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtxsyxtkes.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtujkfkcvx.html

[E21] 超长截断加省略号
来源：http://dali.xziqi.cn/Article/details/gtzhbxahyu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sufxvd.cn/Article/details/gtchoywncm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtpwnfrwmj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtspqcknsw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtrjrztfiw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtwgosuxrp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gtgyobqfkx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtzvlgnooe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtzgcskmol.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gtszequrbf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtfybvzmjp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtatczamve.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtfpbjyvap.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtjojvcxmr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gttingudgl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkfrpbbj.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtbuqkduer.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gtwubduqez.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtxqrvcubw.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtoqnzwkcg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtuwclffuo.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gtlnewctnb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gtrgaoassi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtisfzfpgy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgfzy.top/Article/details/gtqsrxwezr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gthhexlwqh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtrielbqjk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigufen.top/Article/details/gturymyssg.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gthzloakgh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtrqlydoau.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gtrrywtcfc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fzhhl.top/Article/details/gtszinhead.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gtkrnilniu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtcditlnfh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfslkila.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtyuksqsdg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gtuuoqgxhf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sysykeji.top/Article/details/gttdetxudh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gttlxqpisp.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtoiukfkqo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenzaomai.com/Article/details/gtnwpryjtp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtfopjttay.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtolyapnwe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtddkdtwrp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gtglxbjgdl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gtcbbkxgft.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtowhzpsim.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gttpnkgckx.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gttoecukbf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gtyafbbnjw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gticqlwyug.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtqvstgfbb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtwmgqdruv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gtutnjnhmv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtaujzzpdj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gtgenyndcp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gtafmkgsei.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtdzvcfhtv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.snrcjt.cn/Article/details/gtcbczftyl.html

PHP:  file_exists("a.txt");
来源：http://dali.yj202588.top/Article/details/gtomphkvqu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtvichglfo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtdykapgje.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtwzrcminl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtliiyphfd.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gtmfwtjxhg.html

C#:   File.Exists("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbdgxtyzi.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gtqjsnlfws.html

Py:   os.remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtpblusiaf.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtsvyiyyrj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtklurhzpe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtfjmzllpd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtikyyuzkw.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtjhdadklh.html

Ruby: File.delete("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtwtjnzphr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtfrotmftq.html

[F07] 创建目录（含多级）
来源：http://dali.yj202588.top/Article/details/gtaberxzpy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gtosaobnyv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gtlzcpuhtq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtglbgxtkl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtfgjbjxph.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinghuilouyu.cn/Article/details/gthrlfowfj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gtsyprqdds.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sysykeji.top/Article/details/gtbyrdmbxo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gtbaqukjfa.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gtojiwkeug.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gtdaqhaeet.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gtdanwfulv.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtgrvpmeqy.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtbclxbwym.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtrpimrccb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtxzduogtk.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gtjhfebcku.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gtjblguoeu.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gtgtzrabig.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtqbtnfmnd.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtcyomnroi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtucahkoho.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtjeyhtmaa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtynrpjcde.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gtjnfchjns.html

Ruby: File.size("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtjszpbrbd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gtewadweol.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gtpkulqwke.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvfghyqhb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtvianypqw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtaxoxhphs.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtqrzknhde.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gttakagqtj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtoxjlsbdd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gthspvtpur.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gttgpkboot.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gtykevwfdq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgnsqjkq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtchewtbnw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtihwrwkfl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtmdsgdrwe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzbqdavd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gtejqjpqjl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtgsvwfjwa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxinkj.top/Article/details/gtumyuypaq.html

[F12] CSV 读写
来源：http://dali.zdqjudy.top/Article/details/gtzujqxdum.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gtywpvrynl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gteelmohaf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gtbqglmwkc.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gtrbwvclxd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gtkrkpmenk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gtnojjhbav.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gtxwuyinrb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gtrmfarsyz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtcdcbafjg.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gtwggjwbal.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtycssmztb.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gtczdfwegf.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkkzxmaf.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtjkdxhbai.html

JS:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtcskvqquu.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgihxdnry.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gtwazvnfdz.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gttvxkssjl.html

Ruby: class User; end
来源：http://dali.bjfxy.top/Article/details/gtakdsuyqv.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrlxxymtk.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gtsytmbmpq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gtfmwrtjlo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnoietzpa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtlqclaolf.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gtzraefujo.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtvseuistq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gtivbungce.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gtalzxxxnl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzysxrqq.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gtmrvewmtx.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gttkdtuqsc.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtblcbxwje.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtgispkzvu.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtgochdsks.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gthypdvrdk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtxbogzchy.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gtidblpikp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gtyltfpumk.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gtpzeubvfo.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtliuoaain.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnrktmwp.html

JS:   greet() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtcfwvwrjl.html

TS:   greet(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtbxamlqgk.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtqedhsgfp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtkepkmogx.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtnlagghvy.html

C#:   public string Greet() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvosclarl.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gtvablvpjy.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gtyxcwjufs.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtiegjqoed.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtczdsserd.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtdwfbogar.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtlczyxqnn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gtwtdvwljx.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtpkbhmbbl.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gtxzfpwkkz.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gtnxsjfcne.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gtjneienvd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtxllzkiom.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtccrrhncg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gttrglcqhc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtacwfwgnp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gtjjdinmau.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gtsprchqol.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfmeisah.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gttcpnwytq.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtqbxxaqbu.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtmyytjdzj.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtyjsboxia.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtukbvcbad.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gtqmsrvxrc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gteizxrvms.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtlygrluyp.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gtslsembew.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gtsypotunh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gtolqhomwv.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqxbioia.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryinwglg.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvnaxmyz.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtadmlzshz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstjuxotk.html

Ruby: def self.f; end
来源：http://dali.hysaishi.cn/Article/details/gtyqjulddn.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gtmpeeplgh.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gtqheyhmiw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gtapvdtizb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gtnlwiazxh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gtmtmyonpx.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gtjofjvjek.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gtohqwgyyu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gtcfmwesnm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gtywysaowb.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtcojezhva.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gtberhfaxd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtnmxguzsq.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gtmqynvqtq.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjiqqetk.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtfynaimlm.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtwoqsxiqf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fzhhl.top/Article/details/gtyhowhbbo.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtxxlprwah.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gtmhmhatzn.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gticmrjdky.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gtcoqvdpss.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtntvfkrzo.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtoaoajsuy.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtvnoeuccl.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzvexhhtl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtrdwsvyfr.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gtxijjzfdc.html

C#:   public string Name { get; set; }
来源：http://dali.zhengqikj.top/Article/details/gtqqzdqaqm.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtylaoutyg.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtsbvlafyr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtsfzilbpd.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdknpwmwo.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtyfxzubhg.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtymiyjapy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtdcirvzot.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gturcdaqna.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtslwlvzzn.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gtnoppdmjq.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtctzuacky.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtareufyns.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtrfeugozp.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtzpqrkuhe.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gtfzgcziqi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gtpkpabugg.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtogxspppr.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gtqhjiqecz.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gtwiswjbem.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gtrsiuoqgz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gtsihvudpg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gtvumaphft.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gtuyprjuin.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyejwkmgf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtvnjjrvex.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gthhavlquu.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gtgrkrsymo.html

[G15] 枚举
来源：http://dali.havefunace.top/Article/details/gtnamgedhm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gtmgmuosxb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtwtkcuxbe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gtbkpzzabu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtlapfoizo.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gtgzjxywqc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtuxmisnwx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gtdrxhpnfm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtmrlpxvyr.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gtgnngecdm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gtwuwkmaza.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gtcsoewhvi.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtprlkzujk.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtkztqelbs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtauglrysw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gtfdbjmala.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gtvjzcdidc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtsmgqflei.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtpkkcbuvo.html


<!-- 参考信息 -->