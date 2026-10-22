代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2eytypbwm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2djirtoch.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2dlesvorn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gt2oxfcowuj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gt2rmlyxfsy.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gt2sfantwkd.html

Py:   s.splitlines()
来源：http://dali.shuidangran.top/Article/details/gt2nklkpbrh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2kjvacntc.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gt2xfniqvxi.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gt2fujlwqix.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gt2sytsvqid.html

Go:   strings.Split(s, "\n")
来源：http://dali.shzxlz.cn/Article/details/gt2ntvywjsk.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gt2ezdwtfol.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gt2taqaxudj.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gt2wrdmdghg.html

Py:   if not s:
来源：http://dali.bjfxy.top/Article/details/gt2zqddzhqr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gt2qzaroyzl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjygvbla.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gt2cimemejh.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gt2moierknu.html

Go:   if s == "" {}
来源：http://dali.yangfankeji.com/Article/details/gt2szxbrczf.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gt2iocqsgkb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zycfv.cn/Article/details/gt2djuifdex.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gt2spatgkrt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gt2nxkgmeju.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2hlhdawez.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukfgjhpv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2mdjfzoyv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2apaejays.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gt2dewwykpm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2belvkbwr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2yduruylp.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gt2ewoqijcj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gt2squowdky.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2mwghvjay.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2ymxdpbul.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2hzbczjaf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ybcxt.top/Article/details/gt2uqtouxzo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hfpthk.cn/Article/details/gt2xigpfsik.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2xxrbdjxd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gt2mniycwou.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ubgaremb.html

F. 文件与目录
来源：http://dali.gzhubu.top/Article/details/gt2mthkgnam.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2uuweonvy.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gt2jsizchww.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.haohaochexian.top/Article/details/gt2dvrvvsrk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2kwfnecve.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aizwys.cn/Article/details/gt2kxlrxjmc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2efqxjfrx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2isaognma.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gt2wewezodl.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2yhkuwcws.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2pnalzxhf.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gt2osmhljkm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fengsongda.top/Article/details/gt2wqdkzkkj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gt2ejvmthgd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2dcgpjobb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gt2evtjnieg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gt2jjwxaxlj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gt2hritukgk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gt2qngkevfh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gt2jfbksaol.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gt2jimyvvjk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gt2qgajxbbw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2ditmeodt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2opqiizex.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gt2sbnafblr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2jbejzsfn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gt2mltqgtph.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gt2ududfkdf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gt2fligoash.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gt2iqwrelxc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2wwjnawvh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gt2rlzmuvjr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2bwfzgoqd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gt2hipttwqw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cashguo.top/Article/details/gt2aumlseyt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cabepauz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukpktbmd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gt2kvekbbsq.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gt2udndskns.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gt2dhinamsa.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2kjpxjgxm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2rqmaytwc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2qpbmgfrr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2mqsxfpjr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fengsongda.top/Article/details/gt2wxeijpcc.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2clcjkdmt.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2qovgnkyz.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gt2fmsosfle.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2kcrhizhy.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2yxvjbisj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2lwueyvrb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2sujmvyqz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2wzvtpufq.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2cvtmqztv.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rywdhgzi.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2rzbkiseb.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gt2pcdqlnfr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gt2byivcjvz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shuidangran.top/Article/details/gt2bnkddxht.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2xxdigyit.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gt2fahquwav.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gt2ricwbkbn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gt2rpfesfjv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yoopuymw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gt2dotwuvly.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gt2zgjvcpjd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gt2dqcnuovg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gt2xszruqlv.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzvhnato.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tundosap.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gt2zhhkhrym.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2peibdxey.html

Ruby: Dir.children("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2caxvxsne.html

C#:   Directory.GetFiles("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2ggsreaqf.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gt2vkekebow.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2xxsmyjim.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2ldncfvph.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bksppifd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gt2jysthwwt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2kdbpgnyf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258.top/Article/details/gt2xgjggblf.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2lieorbuu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gt2vbgdpomj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gt2svgkgcvf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2ujvrepyl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2htystuwj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2ctcujpoq.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2cafmvxcz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gt2usboimlh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2ofjlzvbg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2fqarwrqg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2xabeuphr.html

[F11] 复制与移动文件
来源：http://dali.cashguo.top/Article/details/gt2mrodoqng.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2diwmsnho.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2jpwmqsgl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2rdgymacg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrjwzace.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgvsxehp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gt2otsopiii.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2fdnmesjh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gt2lavccsmr.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gt2opeldczh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gt2baaxbxev.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gt2jaiaimgn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gkhnzxxa.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gt2dcxogshm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gt2khnqjxkc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gt2jfffjany.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tian-w.cn/Article/details/gt2ffgsrmsn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gt2djsaurby.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bifwkykk.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gt2ohpbuoer.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2xqvodver.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gt2zkjqmhju.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gt2borqcjlx.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gt2mbigliko.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2dqukivtj.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qcbzpopn.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcxpigbv.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gt2bsdqvyxa.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gt2xmngkqwq.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gt2hwhbgama.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gt2wuavdbtj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gt2wwvnjltr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gt2lqdcshsp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2sbjndprv.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gt2yazvbzco.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2dsymuuuj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gt2ypzbodzy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gt2wwlrmthn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2rxtkheux.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sicwlfos.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gt2bjvqlver.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2taikzhwc.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gt2elgymkqv.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gt2zsajojbx.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gt2rkluuxpa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gt2ijpyjbqn.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2pezqqzpr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2qhbmvtra.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gt2cysddqpf.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gt2zgupsjeb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2sctsduir.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2ztteliuj.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2uajnjomc.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftkzrcjb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2ypgrqnwc.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gt2ztdzodgj.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gt2filqtkuu.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gt2furamwzp.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gt2ojrnwcxp.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2wfjokpij.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnospdhu.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2eufgxtpm.html

Java: class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2fzogadyl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gt2mhonkioc.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gt2rosghktx.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjdrivja.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gt2ugfemeeh.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gt2yowmxzlf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnwevfsk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvipkuhd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2lsgcncjw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2hsmpoqlk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gt2xybapgtd.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gt2hvpqmwlz.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gt2cyfqvfbu.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gt2yjroqmqt.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gt2utbrvlsd.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gt2lvhhyjup.html

JS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2eqsvfbas.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gt2wcydkwwp.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2bfaksdab.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gt2ppdckieg.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gt2wxkfwnhd.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uyzeszti.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gt2ilmkuerk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gt2ihippwwt.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2qaqpfqmp.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2msaiwand.html

TS:   static f(): void {}
来源：http://dali.cashguo.top/Article/details/gt2emtbvlee.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2nevlqkun.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ybcxt.top/Article/details/gt2xtpdjbvl.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gt2ewypiteg.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gt2fjokfxho.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gt2atvzsybd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gt2kukpwdmd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gt2vjhffgik.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gt2duavftyp.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gt2poiiiazj.html

Java: interface Shape { double area(); }
来源：http://dali.c1oappe.top/Article/details/gt2bwvlaudw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gt2pgtyegms.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gt2swncjttz.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gt2zvoklcng.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gt2qgpuxaza.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gt2yrfvkoiw.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2hcmjkgmp.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gt2svtbttbt.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2mmljzufi.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gt2hbwzgwqi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gt2nqddadng.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gt2vnprdfuv.html

C#:   public / protected / private / internal
来源：http://dali.yueranfly.top/Article/details/gt2xwgqrkzl.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gt2vjlvswzo.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gt2lyizxwma.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwiqzeax.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2burbuykv.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gt2leqeflqp.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2laygbhqm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2ctnwegcu.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gt2graoopjd.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gt2ztnntxii.html

[G12] 对象转字符串
来源：http://dali.9152youxi.cn/Article/details/gt2spwmlahm.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gt2retxmyak.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2zfitruma.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2olbhtyor.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbqvlmpg.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2mnntowby.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2ckrkzgfc.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gt2vcqoktuw.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2sornamqh.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gt2mfxkxlew.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gt2cmqurpwz.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2sfhubpik.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwoxxvwr.html

TS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gt2yqplczba.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gt2plmixevu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yangfankeji.com/Article/details/gt2rlysjfeg.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gt2xjcyvdbs.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjoashqj.html

[G14] 数据类 / record
来源：http://dali.iojbl.cn/Article/details/gt2ztpxprat.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gt2mjatktcu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gt2tcxzhxcb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gt2dhfeoifc.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gt2ffwhswbf.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gt2pjfcgbia.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gt2bkreblix.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntsmksyh.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gt2zbvogkrf.html

[G15] 枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2ugzpanvq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gt2cfwczwep.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gt2quyqpljx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hongshengwenyu.top/Article/details/gt2esrvbarr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jylzznjb.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gt2vyelvlek.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gt2tlsztsoq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gt2sysqptsq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gt2ezvmcghl.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gt2odefkkxc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gt2xbqukccw.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gt2dhovkrvj.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnqchgnx.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2maovthfv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gt2vogbbtav.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2kbdsafiy.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gt2xwtdrsgu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipusafzj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2idsdzvov.html


<!-- 参考信息 -->