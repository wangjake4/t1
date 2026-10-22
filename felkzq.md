代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtochqunnl.html

[E19] 多行文本按行拆分
来源：http://dali.9152youxi.cn/Article/details/gtxxhbrqoo.html

Py:   s.splitlines()
来源：http://dali.hongshengwenyu.top/Article/details/gtyjqzndfz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtzoyxovqh.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtubncelph.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtolpfonap.html

Java: s.lines().toList()
来源：http://dali.yj202588.top/Article/details/gthqsqeqeq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrfvaqgl.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gtyefjkjke.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtnqvufpha.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gthzincqub.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gtlcczfyww.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gttpmqwwwh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangshuangyany.cn/Article/details/gthplkayfv.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtjfmqvxpx.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtrwpgtexw.html

Go:   if s == "" {}
来源：http://dali.gaohongyu789.top/Article/details/gtrzyvtjch.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtbeihxoco.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtafffdwuu.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gthcnwsvrd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtaqjstdsg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtakdsasnn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtghtedjeb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtrypmxrju.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtrcgrydex.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gtdlnvrbpr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtfnncdgvw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtfkhragyj.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gtcupgrchf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gtvpxmxjkj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtktiynthq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtrtmywtpo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtyvpduihj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gtdipggimu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gtedexstus.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gtrinpvioo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtprnqbvkm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtiaxdqzvj.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gtjfwmtjyo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkpxencaa.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetrexhiz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gtolnsbynu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtpuhsnxjj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgufenzy.top/Article/details/gtpaijoiad.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtcrydoxzw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtmcwoioot.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtekjkicsu.html

Ruby: File.read("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtmjanbrnb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gtniucxful.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjjjxqfk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gtxnqzivyr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtwofjxpgx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtpbhuunol.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtzoebllxh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtpmfniefk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangshuangyany.cn/Article/details/gtvuwawifp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gtqbucviid.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gtpvdymzpi.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gtvhidujzo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtirucgsrg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtovnfdxix.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtjpdqpxyt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtlffwfybd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj202588.top/Article/details/gtpnaqyeag.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtmbmlrbpp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtlzvdyxkd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtoammcffg.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gtaggfjdlh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gtkpbspqoi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrotzswsu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtnjcqirih.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtjdnlqkfm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gtdzumqvqq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtwxnfqqvf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gtuyaupaqy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuanzhike.top/Article/details/gtnrqmvgvj.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gtnqqbpedc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtwifjuqys.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtnzernulv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtqgfirerp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtbuyzlneq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gttzsdfgqc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gtjspameze.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtznyyjahc.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtntmxvogi.html

[F06] 删除文件
来源：http://dali.gzhubu.top/Article/details/gtczwycrdi.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxzyewik.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtqgwtalpb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtruhzscxc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtrmykdweu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtjepchgzu.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtuxjfmmes.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gthfyugvdy.html

C#:   File.Delete("a.txt");
来源：http://dali.yj202588.top/Article/details/gtgrxexnal.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gtflboufow.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtquovlkkl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gttmhctlyl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtuugupgmg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gttfedsgzs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gtpzutlqyk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gtbsfscbfo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtbqkdkkob.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnjvnrpx.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gtlkgbpfwj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gtksnkpnjo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gtdmkxlnop.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtescwwzeh.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gttcabpeog.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtoqhawvgb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtqyeuuyzw.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtiyaprjex.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gtuecyyarx.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gtdsowfrhs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtefdrgybm.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtigeadogb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtmniiaeem.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gthvhgsfmj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtfdqmrare.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tianlin.xyz/Article/details/gtzsmrfjbz.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtbdgsbgoi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtmahzuxca.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufnnjdug.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtykfvvlax.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hammf.cn/Article/details/gtjyxoykni.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtrguiowre.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gtqjpvisiz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gtthwzcmvw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gthjbiexyi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtrxlxyfra.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtvlfwvxto.html

[F11] 复制与移动文件
来源：http://dali.chenlongwang.top/Article/details/gtufqybqip.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtainnmhnk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gthixsovji.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwojbozzv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gttaceunrv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gtbtxjbesj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hongshengwenyu.top/Article/details/gthateaysl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtnszjqyib.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gtxvympymn.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gtbaqtbfzs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gtgxtukiom.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtcxtjthhe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gthsokflup.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gtkvmilrls.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gtysjxzadu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gtqsujqzne.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutuexjin.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gtidhnlcks.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtzushrviw.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtnijaogmh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttulvkcly.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gtvvmsgtnn.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjmzqfjl.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtvteygzlp.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtbgjrotgg.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gtaapisevg.html

Java: class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtwvpqauao.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gtgcwebwbi.html

Ruby: class User; end
来源：http://dali.hnxiangtu.top/Article/details/gtehujhznb.html

C#:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsgixtcdb.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtnmqfbpwq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gtzobnjfgy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gtxveqfekn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtpmfpdtjy.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gtilspoocy.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtdomuxmok.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gtbtyvxcgx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gtnvhxsspx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gtvyfddjwt.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gtsgzaknbd.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gthrsenzfy.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtkkqrgzkt.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtykqjqkiy.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gtlphcvhxk.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtfeuhamst.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvvhwiye.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gtfbymbnqk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtbiuftybl.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gtaiuvwflg.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtecbglkyy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtjxxwynqe.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtxkmuiklf.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtevopdopr.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcwspibgk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtmrpfcwyz.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gtngukkvgv.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gtrkygbucv.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gtgspgdpdd.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtgdowbzei.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfxngfuw.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtlooqxcex.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtrfkcmrke.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtvkxcvinp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtyfahviow.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gtdwrmzjqd.html

C#:   class Admin : User {}
来源：http://dali.yj202588.top/Article/details/gtubnztnqt.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtuornpxls.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gtxffgnkul.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtaszunrmf.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtizncoxlf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gttpqpffme.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtlgstrbsf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gtjwqhzmhv.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrdecfdm.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtuqkyaawb.html

[G07] 调用父类方法
来源：http://dali.ydzc1.top/Article/details/gtepwpyqzf.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gttbqpiuku.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqmuvozw.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtkyhytnbp.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtnoyukknz.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gttmljjzno.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gtljwoddzr.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtpcyfkein.html

C#:   base.Greet();
来源：http://dali.jqgufenzy.top/Article/details/gtnkzafhcm.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gtjowctmnl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtwqmhfzca.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gtfmodwmdf.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gtcrxfszoh.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gtbjhlnbfa.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gtiabsfzym.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gttsagmlwx.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gtydfoszqw.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gttwiwtusv.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gtxlmkphpw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gtzpcdjjhb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgfzy.top/Article/details/gtanyibany.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.haohaochexian.top/Article/details/gtjnzchewq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gttsolbego.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gtkpewxbjt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gtziyhoshz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gtpxbhfdlj.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gtkcckkryn.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gtszulzdqc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhoulong.xyz/Article/details/gtegzxwhsn.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtqvhudigs.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gtdwgyixkn.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtkzigczfj.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gtiphygymm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtvtegoctv.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtiwhdovop.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gtpuhgwqqz.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtkqqqurmj.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gtywhtkdyv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtrutduwnl.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtjikljmmz.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtfcyrsmjz.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtfklzuxki.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtgqjctjsx.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gtqtthbikw.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gtpmjkcoqc.html

[G12] 对象转字符串
来源：http://dali.tianlin.xyz/Article/details/gtysahmywu.html

Py:   def __str__(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayvppzsk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjrokwewh.html

JS:   toString() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtriqtqcfx.html

TS:   toString(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtfkhybkzc.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtszxhuykp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtgznahkqw.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtdmnrigod.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtnmzyqwbx.html

[G13] 判断对象类型
来源：http://dali.chenjidiqi.icu/Article/details/gtfywbhqsj.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtbbfxwhha.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtnjjpztzf.html

JS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtfasfgwdr.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtmiytbots.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gttlyajvbd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gtactzsdfh.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtqvqzgwwx.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gthuiyajvg.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gtskjlhdam.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gtwyrmfuxf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtxkusfjcg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gtdwrfgbsn.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gtdeuubaix.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkyrjdqnm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenjidiqi.icu/Article/details/gtdgnrtlwa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtlsuzsswn.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gtyxwvwoli.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gtiwlxvhav.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gtmjyclwgz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gttnyrgzxe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gteiugsivn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtpsgyeubb.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gtvbfvpote.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtslrblnfu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gtwodzpxhe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigtvpxap.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gtdxknyhss.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gtaquyazbm.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gtuwhukczk.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtafapgpcv.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtqwmiuyza.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gtnucgsjei.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gttitfvfjl.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gtotzdgtyg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtppwwwptn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtsdcoiqsp.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtzlyrehuw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtiajytljj.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtebdcbfgu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gtiwjezimu.html


<!-- 参考信息 -->