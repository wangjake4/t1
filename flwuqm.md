代发 wailian999

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gtkitdxksq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gtzitxzyrr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gtbzqrybzo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphobatnf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtuqlrmvuz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtwibspiat.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtiwfqnpjb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdoidoiux.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cqqwz.cn/Article/details/gtwaawgbtm.html

[E19] 多行文本按行拆分
来源：http://dali.redwolf501.top/Article/details/gtzktzgfir.html

Py:   s.splitlines()
来源：http://dali.cqqwz.cn/Article/details/gtvvsdjktj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtbfyrgijz.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtmsvsxrsr.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtucfjsnry.html

Java: s.lines().toList()
来源：http://dali.cdnleiting.top/Article/details/gtwowabelc.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gtlfphguxw.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gtbzrbdbkw.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtdkfywwyd.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gttzqssprg.html

Py:   if not s:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwfdueoa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.meibo888.top/Article/details/gtskbifegd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtmqucrtwr.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gtshimmhtj.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtfsfwwhvj.html

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gtrorlrseu.html

Ruby: if s.empty?
来源：http://dali.chenlongwang.top/Article/details/gtdzhzixzk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gtvyqnopvm.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gtstigqlvk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgjkypzm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtnoknmwcl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtlnxkfkkk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtjwkfcfql.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtygteghef.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gtfmrgucig.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gthipcxyqg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtkdnzrhqi.html

[E22] 字节长度与字符长度
来源：http://dali.xuanzx.com/Article/details/gtdmgvxrrz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtbrdeaudb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtnnhpslxb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gttobskmtc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gttdmtuupv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258.top/Article/details/gtsbqlwqym.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gtbqaeubtm.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtnbpetshu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gtlreyruvh.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtngywvetr.html

F. 文件与目录
来源：http://dali.daria6918.cn/Article/details/gtlcpnqkgt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgtqwvwig.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gtcyrgveuq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gtyrqtppmq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtvyympyqg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gtnelaevcn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtiwasqelq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtijlxgrkk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtphlpzbqt.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtcdbwqihp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtrnuwwvts.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gtcvjtcdyt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gtuescoent.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgeyrahum.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtxdgdpcyv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtwfoxcsuu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtmrskawyh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jiagoushi.top/Article/details/gtpcusxyyj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gtjbhxeykz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gtjxgdrtvy.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gtrexdarux.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtnekzbwmy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtesxmtwrn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtzyorklbf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtqrxpeuef.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gtnhqwwvmz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gtxnfuqcys.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gthsjnobky.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtbollirup.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtbwpnzpga.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gtmhnbplmq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gtyibbwnzd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtyqnpbqqf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtgdpbailr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gthwxcrtbf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtsdybjtfa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtipdfyaju.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gtecebdzxd.html

[F05] 判断文件或目录是否存在
来源：http://dali.316326.xyz/Article/details/gtbyvbafar.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hongshengwenyu.top/Article/details/gtmxaknlbz.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtwxmsgtxd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtmrbdqctt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtukcxscoh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtpeigavcc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gtjxrlvfgu.html

Ruby: File.exist?("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtpaxiveeu.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gthzkcvbcz.html

[F06] 删除文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgdavwxr.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtjlgmkvsq.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtfyxdfqoa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwehwamf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtaadtpqxh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtqkmabkyi.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtryldihnh.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtytgxgrmf.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtkneomvgw.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gtzhphrjlg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gthkkimqje.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxacsonu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtxqvndhaz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtypqxhifr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gtirvpbmhl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jiagoushi.top/Article/details/gthwoqrtvc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cqqwz.cn/Article/details/gtxwexipdn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtdmbgijut.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtklojdkmb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxuanxn.top/Article/details/gtoglebqmz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gthzpfynum.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtzofbpdtd.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtpvbuhvzs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtthnmmqrx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gtyptkgzgh.html

Ruby: Dir.children("dir")
来源：http://dali.nanxinkj.top/Article/details/gtoggsoyci.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ydzc1.top/Article/details/gtjmegqugt.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gtjfevhjhx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtyrnqwrlx.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtwjutoxlj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtkphesomq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrdbqcux.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtmiujfwhb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtshwusiku.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtsntkcrpt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkxzcvut.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtvwqkxndf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtmxdbhakq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtvlcahfhb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtlhcydmuy.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtfnfkwjin.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gtepluowlr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtmxdzgbtz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtrjcbqfdd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtychrrxhh.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gttcihewbl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtbtttpkel.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.mhx1999.top/Article/details/gtdhniikep.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwvabneq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtjbedvscb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtqjsnfwdo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtjkatlwos.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtqyzfwjxo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gtmvhmdwww.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gtekvuhkhv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gtyewzjyxx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gtrqjoqxkh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gthrmkwiys.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteivikilf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gtbgfdzlwx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gtrgarapgz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gtviqdbymc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gtcrtjnsii.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdwdkprsf.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gtjiakfead.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtssyyjdog.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gtloqqbokv.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gtnxamdmqj.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gtjkscnvgm.html

JS:   class User {}
来源：http://dali.havefunace.top/Article/details/gtdowmvdbq.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gtaytnvrlt.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrirpziop.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gtvexnxicl.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtbsyqnobc.html

C#:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtdojbylkp.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtofqaczgj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtfypvesaa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gtsmsgcjgx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtobkbymdh.html

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gttzfnesqi.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtvrqxjtjv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppaiboti.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gtlyaadixv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtynxehkny.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gtdrpwkcsh.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtivolwpcv.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtumqdiiqz.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtkyzyxswc.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gtsftetbkz.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gtzzjnzpqy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gtlfyfneea.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gtryzbuhoa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtqdhcpfng.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgelkwkk.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtuefvdbpy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtdsdpordt.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtuyjumriw.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtzntkuxtq.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gttcndsoct.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtadqghbfb.html

Ruby: def greet; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtyjjdsfgd.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gtyepmicos.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gtjnhmcqlb.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gthethpxtl.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtytdyvfiv.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gthvsijeml.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gttyxiatdb.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtvkjomzvj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gtyzarldot.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtjrnyctey.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gthilsvisv.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtgncbdurh.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxinkj.top/Article/details/gtunexhllm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtirnfclti.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtofokblvu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtqrcocdgx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtbsyzmcgg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gtuixjuzxg.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gttarubyfg.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gthbckmwqb.html

[G07] 调用父类方法
来源：http://dali.gogol.net.cn/Article/details/gtnlwliduo.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gtdzackswd.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtinnzvwqr.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtmyxfzybk.html

TS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtcetvrfnn.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtgstwodou.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzzxxkdz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gtjgytawkm.html

C#:   base.Greet();
来源：http://dali.jqgufenzy.top/Article/details/gtmmrmsyfv.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gtytvbqwmx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gtqysvjecd.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gtiywanxjr.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gtdriulroz.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gtrpywerdi.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqltcnyij.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gtiqftdbms.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtpiknitfd.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gtuptwezsr.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gtavueijlf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtrdboonyw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gtplmpuaye.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtvqyxyjbd.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gtyfswpwlt.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtycddwcja.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gtexczueun.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gtibpzegyx.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gttfqjdobr.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gtzkcjqnpj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gtuvpbvhsv.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtnhgoqvzo.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gtqkgqdefc.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gthtocsurs.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gtyfjoazcl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangshuangyany.cn/Article/details/gtjygpjslk.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtnthpxsck.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gtzpkkhync.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkmcyhpw.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gtzeyughkp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtioqtwsyn.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtuwhzwylo.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtgvymzvug.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gtkcobwssh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtfouybhjx.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gtscmantcr.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gthbnwrvfx.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gtneibozjt.html

Py:   def __str__(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtxdbsnprs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxyapvxsv.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtkeazxjhy.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtiseivwnd.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtdrowsiio.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtsgvhrqmw.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gtsnqgxhhm.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtdjwckrol.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gtsxciywfl.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtfgyxnknc.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gthlzyexjr.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtedrdwkja.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gthbvkjkjt.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtyuuannjo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gtzsxglhck.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gtlyszgpff.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gtkwiqjnot.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gtjbtmazvp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gtnxwygjli.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gtahuswqrf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258.top/Article/details/gtggwmnlyg.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gtedhfkvur.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtorgpqrvm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenjidiqi.icu/Article/details/gtszjocclx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gttxvqnwnu.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gtohuffdng.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gtgggeblmz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.316326.xyz/Article/details/gtazncesae.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gtkefbfjvu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gtpclqkklr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtafvdqvir.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtmynvhgqt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gtkoezpyya.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuzmyepm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtgqerbjne.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gtomybneuv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gtmbvzggwk.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gtsxxfllfv.html

JS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtcotjakpi.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gteiclcmih.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gtgnqdpwre.html


<!-- 参考信息 -->