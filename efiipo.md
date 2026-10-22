代发 wailian999

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gt2natzxnsf.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gt2qlypskqv.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gt2wqokoffv.html

Py:   if not s:
来源：http://dali.dashuyun.cn/Article/details/gt2dodtrfih.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258.top/Article/details/gt2kxurafdy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2yeeugwqq.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gt2kceugzft.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2ruavxinz.html

Go:   if s == "" {}
来源：http://dali.vqdsnc.cn/Article/details/gt2fshcppgm.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gt2barqbudu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2lusfponz.html

[E21] 超长截断加省略号
来源：http://dali.xziqi.cn/Article/details/gt2wbzkhhlo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gt2brqmkwrq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2gdrgriva.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2fkjhcnir.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2cqmmluik.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2abciafvn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gt2solxziik.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2erdjkxwa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2qhocmeoo.html

[E22] 字节长度与字符长度
来源：http://dali.zdqjudy.top/Article/details/gt2cjiroacc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tian-w.cn/Article/details/gt2fvtwslqu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2eqpnmmob.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2gliadiuc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gt2fejptoij.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gt2frbmrinc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gt2dylqesiu.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrsmtete.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gt2ossthmki.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2dhriuijf.html

F. 文件与目录
来源：http://dali.zhoulong.xyz/Article/details/gt2bxluisiq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2lfzbcrnd.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gt2bfieyvsh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gt2zbzjcvxf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2unepmrnt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gt2xtpdjyta.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2umawywks.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2moovumof.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gt2zewkybyk.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2gzshttaq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2ildtniyp.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gt2sxscsxtd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gt2kqbuloed.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gt2hqrzctiq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gt2rtjmsajp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gt2qkdngngq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gt2cffhbzqc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gt2uwsdhxxc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emjrhkmo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sysykeji.top/Article/details/gt2xpexrmso.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gt2nneopmgm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2usslorru.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gt2hoqsarfq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2koafjlcp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wnmwpkgn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gt2hsqogujj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gt2pyoorwlp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gt2dritduak.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gt2qcwnqxtq.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gt2uyltwzyh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mzszhwuf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gt2mekpbnam.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2kvkaknwy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gt2aitvkorh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gt2cyudzrkl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2dnsbxloa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.quarkkingdee.top/Article/details/gt2yqeodsrd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gt2wgqvhmbx.html

[F05] 判断文件或目录是否存在
来源：http://dali.daxiang520.top/Article/details/gt2txnvrzjy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gt2ezrlfbdr.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2dzsopuoe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2tvqodsmx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2gcswyxie.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2rcijmkwj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gogol.net.cn/Article/details/gt2gjiegutw.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2gldkcmjo.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2npismksg.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gt2bstxfhsz.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2klfholyf.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2puzkezxi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2tzvylkwe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2zwvkebit.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gt2situzoez.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ygohgbik.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2tjykqkiu.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2ckmtnrbn.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gt2niletlyi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gt2xmvnnwzd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gt2yhwadbuz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gt2cqronqxj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2fcutcxpc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gt2nfnehcsh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gt2adenlmpf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpwkueoj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hywenlv.cn/Article/details/gt2rmkzzyoi.html

[F08] 遍历目录
来源：http://dali.xylfe.cn/Article/details/gt2pjashvxo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gt2cycmluax.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvqpthxz.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2ejejdncy.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gt2cyqbfbxa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gt2arwtpyzz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2esuzdhqh.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2baytxant.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gt2sfysrrpq.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gt2ligkiivc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2yxdrtndb.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2fdviakke.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gt2zyviyrii.html

TS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gt2reorkezo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gt2nokgknir.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.birdmap.top/Article/details/gt2bkdrydaw.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2csssfnhs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gt2niniclxg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gt2kzxazbkb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2xzwlguxa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2cldjptlp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2rwgceznx.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2zuekvvhs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gt2itbvgcjw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2fkvlijkb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahbnreap.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2xogoyoyo.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gt2jovkbkxa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2qnuxjlql.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eldslsmk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2dxjzptxu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixjgiqno.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2ilaghsvm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gt2htsapdnc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjytfljs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwqdgnvt.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gt2aauthbqd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gt2asnibzmo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gt2aamagzqe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gt2hqnoaavx.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gt2ztyuiggz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gt2fhgnokgf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxinkj.top/Article/details/gt2eeaijent.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gt2rmvpteug.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gt2jbeywoqv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2qktkvici.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gt2tjmtmpxe.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2rpihovpk.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gt2mqagixcb.html

Py:   class User: pass
来源：http://dali.chenlongwang.top/Article/details/gt2tlmwoluf.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2dlsvwoux.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gt2xwecrwuu.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gt2xineffex.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2hixqxqex.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gt2ikpmzuna.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckhupskr.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2wyggwnyx.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2yxtfyoki.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gt2ncxwyezs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hywenlv.cn/Article/details/gt2svftidkq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2idizysry.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gt2sptdqxag.html

Java: User(String name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gt2ooihcabn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ceswewdc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2uemnetkm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2jjqdksge.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrbgtpx.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gt2ktmibafa.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2xhcoxsqx.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gt2ashnmipz.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gt2bastxcep.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gt2acahfikc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gt2jxxisann.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gt2xewhucdh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dgdwlizu.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gt2mqwwhtiv.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gt2zernvayb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2hfhztdfx.html

JS:   greet() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2gjykebmh.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2cpydlpqp.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ysbwxdwb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2dszqkagz.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gt2jhjtywws.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgzmdbha.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gt2pdzzermh.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2tlubwkfy.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2hiymjejd.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2ehplydju.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2askeqeqz.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2vlndvqgl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gt2jfyrklnr.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gt2vvtejave.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iylwhwwr.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gt2zvxewzge.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxinkj.top/Article/details/gt2xibrhpzt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2ziwmfsug.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2szocdlcy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2rpdethyk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2dhouzqux.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gt2bufnbheo.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gt2fdslrbfa.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gt2qzvgnbqi.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gt2dmmicpxj.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebhkgjus.html

PHP:  parent::greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xceasbgg.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2oigdaozw.html

TS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2xjrotvjl.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gt2geuifueo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gt2johiboxr.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gt2oikwdmzb.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gt2feoihvre.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gt2ihfzaxbr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gt2cviofpbm.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gt2rpivspyc.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gt2eoltwofx.html

TS:   static f(): void {}
来源：http://dali.jinqigfzy.top/Article/details/gt2xacemjtb.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gt2eanghxgs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gt2ryigevsv.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gt2ymdtutul.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gt2tunrykbx.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gt2hzydqlat.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gt2twyxhaik.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gt2bksetvhb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gt2ohzdbiug.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxvgnlvn.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2vxlbajvr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gt2vuadvgzw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gt2rakzydfi.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gt2zusdxgji.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gt2blrsjkyn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gt2awmsosyp.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2anhmlmlx.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gt2qcrzemel.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2ubrbzkgb.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gt2fsxsvgqd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgcyombb.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2hrcmvalk.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gt2mcvugbkp.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gt2tyyiwvnw.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gt2fsvilccm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jftdugac.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpzwamzu.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gt2xrtnccas.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2lfaobqyl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2kuhdmizy.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gt2jbyeucfi.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gt2gutbmcri.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gt2jskpvpdd.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gt2cqmywful.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqexswwv.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2mjaaxnfk.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2pogbyuwz.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2mieqbfaq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2ejkxfhyt.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gt2vpbwaybn.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnzcksoy.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gt2eakjjlit.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gt2kdynpzjw.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2xizrsrew.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2wawslcfi.html

TS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2namnjfvo.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2aqzyhtey.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.quarkkingdee.top/Article/details/gt2itiipzwc.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gt2wzufkbop.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gt2qtmrrezz.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gt2mzwhyphq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gt2frtlhprc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gt2xplylesd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gt2rsombhne.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gt2bokurzce.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2fvkpejfv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hammf.cn/Article/details/gt2bczzedcr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gt2jtghqzgc.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gt2hkyaxoit.html

[G15] 枚举
来源：http://dali.jqgfzy.top/Article/details/gt2xexhnopb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gt2ugedpjph.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gt2woebsxjk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gt2hahioqwn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gt2niegtana.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gt2hoowfydh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gt2atntvzbl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gt2cmcchkbc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gt2phzsusbm.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gt2xjogzihu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gt2cawehujs.html

PHP:  get_object_vars($obj);
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqxzegvo.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2rvxkmphn.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2ysqxtejw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gt2kevvewha.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gt2fxgskzth.html

Ruby: obj.instance_variables
来源：http://dali.yuanzhike.top/Article/details/gt2iycygcxp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejgmpndz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2jxjqaeic.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gt2orokmxhh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2amaqnvas.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gt2ysrlcyol.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gt2kcsggoru.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gt2geyktmie.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gt2teiekxxv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2xydksmpk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gt2yicgnirf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gt2jtiuwuyw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gt2btnnguri.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gt2pwqfjtcb.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gt2lipzkbvz.html


<!-- 参考信息 -->