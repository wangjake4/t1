代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sysykeji.top/Article/details/gt2wztynudh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2umqlmjpv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2iltmvyfx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2plpwjmiz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2sqrtruei.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ybcxt.top/Article/details/gt2ilazxvpq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2xbawnyhg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2bwunyayj.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2awkjztsh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2tavebtlj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2zbsowbsf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2shhjoqkm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcoqwdbu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fengsongda.top/Article/details/gt2kfqbgwxx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gt2irkglnls.html

Ruby: s.bytesize;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2thwvevua.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gt2fflvzfkv.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hwdyzgyh.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vbzivtiz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ujstdmjr.html

[F01] 读取整个文件
来源：http://dali.meibo888.top/Article/details/gt2xmdyirwy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gt2acuzudhl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2wmhdxvvy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gt2mznzsyev.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsbschq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxyxnjvw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gt2myobvyvp.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2qokhntfp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2tptoxwxm.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gt2acpqncqa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gt2abpvkimj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenzaomai.com/Article/details/gt2hvctgizc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2kszojilt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2kjiygpbk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gt2vffbdphj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gt2imnusvgv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gt2tfsutzon.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gt2gvljhyet.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gt2pqymjubi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gt2nbabtnxc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gt2xzeqvcxx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gt2xfhoxqjr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2xoxdnywv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2mcjmasbb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gt2snflhvfi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gt2ntnoxskr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2avwcggrh.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gt2yeykzadw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2xtrvqdeq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gt2aovavtfu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gt2getwupsw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2myuhsjgl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gt2ecldsmqu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2xebnbssh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2eweuknxv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gt2gvkffdyi.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gt2mlzegbxd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.9152youxi.cn/Article/details/gt2lmsuiliu.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2mrklwdsn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcckbhcs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2izwvsefa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2blluokvm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gogol.net.cn/Article/details/gt2eopvsomj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2ntdpdojo.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2wrishzys.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gt2pmboubyb.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysawvups.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2gosxfcff.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2jsfjkmop.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxlndqcn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2kjgyihzv.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2wsjzrcjb.html

Ruby: File.delete("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csjetqid.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2wpdbyoss.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gt2byjzshud.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2povgapfy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ppjwa.cn/Article/details/gt2zsriyhxq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gt2iqhqleet.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gt2mhlufdnh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gt2mgjcripr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sxryk.cn/Article/details/gt2ntzttywr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gt2mmqhwghj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gt2ojhoeica.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gt2pohyhnla.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gt2kkxlrhjr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gt2rdlnaewq.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gt2ozfbqytl.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2hfxroilf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqzzdzpc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangdashe.top/Article/details/gt2axjxekhe.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2sxqscsuy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2djgzndrx.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gt2mdkdzplh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2wlmxtzoz.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2vjnhqqzx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gt2eynpfkww.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gt2xddpizvc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gt2tjechect.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gt2hmdrzypd.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2snbbjlfq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gt2kymoilvd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gt2duepdoph.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2cfqimife.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gt2pwbprhws.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2uhyaiiez.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2eivfozau.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxegggri.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2hadrllgr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2dplnflif.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2wggphicb.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txjyeryo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqowkxcj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hammf.cn/Article/details/gt2deapegkh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2ahvatuuj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2qqfmysyk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gt2rwjcgyrv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gt2nlfagamv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2hsfwpzbd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gt2evretpho.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gt2jigwbogj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gt2usfqjofz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gt2rwinupoo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gt2wbouozdp.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gt2qjimfoxr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gt2wgbylols.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gt2weaksmuy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yvedp.cn/Article/details/gt2shhyetex.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehslfqln.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2kdvllhnm.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gt2thszdqmg.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2kbozfbua.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gt2ffrssndu.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akaozvzk.html

PHP:  class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkgbyyxi.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2dahmodyq.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gt2ljkqdnpq.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gt2hdvwxyqe.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gt2jzzpjaan.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gt2zscatbkt.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2binqndoz.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gt2eiqfzrdh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gt2auwrcswb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gt2tmwyimed.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2fwomjfqr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsklteoo.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2kwlbahgj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gt2iqamtacq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gt2srpxdxzk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2lynkzsyn.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gt2qpzztonr.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gt2oepqaghn.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2yvrxlizg.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2knjriyvp.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2ssexewsl.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gt2firoreas.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guannengcc.top/Article/details/gt2dhdqzlhr.html

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgajmkay.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2izchywkn.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gt2pvubnsad.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gt2yftyjyub.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2jlnbrckr.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2upnxxppv.html

TS:   greet(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2xewcvrst.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2yeljcgqq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2yikufqhw.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gt2ieloleqh.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2uiapjbre.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gt2ywrbdktr.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gt2bxpslpnn.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2ylpmzyeb.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2gvdwlmro.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2qfrkigzv.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2tvfzabef.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gt2tdwrjzvx.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gt2aheusdxc.html

C#:   class Admin : User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2zqnfbzmi.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gt2vcpboztb.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gt2vwvybrvw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2cjyqklnz.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2rzufoaiw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2knbxrpmx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2vhhfdliz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjaglynm.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gt2xfgeuiem.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gt2fxcvxtjj.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gt2zhuibogq.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gt2fzjywhno.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gt2rjwivmzf.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2qymbchyj.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2oujktsuy.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gt2odukjsbw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gt2ytmndnzd.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awyvwpod.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2niwuqbtp.html

[G08] 静态方法与属性
来源：http://dali.c1oappe.top/Article/details/gt2ibvehgtt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zycfv.cn/Article/details/gt2ddgmejua.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gt2shogdzrx.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msnszkjn.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oyyvzcnf.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gt2kpjodlza.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gt2bpmsiqnw.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gt2hkuyxaok.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gt2kxzlgvrg.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzwupbql.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gt2fuwvvmwp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2feyicbrc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gt2lkwguvuf.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gt2crjmkoyl.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gt2oooxhvld.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gt2ylhhszvv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gt2homitznv.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gt2iidfkcij.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gt2flqxpndg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gt2kkwydnyo.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2rguoauui.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gt2gckioaze.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gt2rlagqgbr.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gt2obugmncy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hysaishi.cn/Article/details/gt2eryqozti.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxssxwug.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gt2riapxrrd.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gt2fevvhlux.html

Py:   @property 与 @x.setter
来源：http://dali.zhixingplan.top/Article/details/gt2ovqlptoc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2onyfqkaw.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ubeoietu.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xjegzics.html

Java: public String getName() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbejjfru.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2ckcaedyw.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gt2aiwkxjzk.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gt2ejsuagvv.html

[G12] 对象转字符串
来源：http://dali.aizwys.cn/Article/details/gt2zpkjzwim.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gt2seubiptx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvsidzvi.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2btqvbxfm.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2fbqxlten.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2bfxzdccl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2oqhqgcxt.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gt2zezkxbyp.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gt2tjvqbvpy.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gt2tecuhibk.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gt2zdnzldoz.html

PHP:  $u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2wsjhkymm.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2qaxlrocg.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2armaeurt.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2kghzddpt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tian-w.cn/Article/details/gt2qjrcsypy.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gt2lwkulcwv.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gt2yolyhmko.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gt2mclagkze.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gt2mfhlwzwn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.birdmap.top/Article/details/gt2cjmkqbsf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gt2skrrqwxp.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gt2lwoamuau.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gt2zbvuovnw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gt2rskdbszj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gt2idxeizcl.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gt2wgvqauoo.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gt2emblgvzp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gt2ynhenevg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gt2sbxfwuyk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.iojbl.cn/Article/details/gt2jdnduutp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gt2gdupxcgw.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gt2xmyxzfcb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gt2wpfjvmhf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hfpthk.cn/Article/details/gt2ztcujzmk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gt2zywuxztz.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gt2ztjejsrg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gt2impdtttj.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gt2nxocdmib.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2cilqolhz.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2lqghglxv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gt2qxablfoq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gt2tbagezlh.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlwgompn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gt2rywtrmkk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2egkmqnel.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gt2obpkjlxt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2hiiffrou.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gt2enzhphqv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gt2hkyaunwi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnqzz.top/Article/details/gt2zuactylt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gt2dyelpxtf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gt2srhfxvmw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gt2otyrvwgz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gcioyvba.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nawjupmn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gt2rpkrkodi.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gt2rxcdrmce.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gt2owxivaar.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2hxoweqhq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2llclculc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2tqwcgics.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2mxqqbnzo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxinkj.top/Article/details/gt2unxhykyb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gt2oywmbwco.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2vrbxfejh.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gt2sbjymajv.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gt2irbjrpap.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2qyowiptj.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfjftiza.html


<!-- 参考信息 -->