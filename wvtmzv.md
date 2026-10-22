代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gtrwfyuwxu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkerebua.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtywvylmsq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtvuawggmq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtieannbgz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gtrosfckpu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtozvrlxfa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtnsrokbaf.html

[E22] 字节长度与字符长度
来源：http://dali.jqgufenzy.top/Article/details/gtfxezofzi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.meibo888.top/Article/details/gtjidrybdl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspfzscyy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtgpniymle.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtauzpblav.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtxmvyvzhn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtjweauktp.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gtogpydlok.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gtxuroqxkj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtfvkbxmto.html

F. 文件与目录
来源：http://dali.dashuyun.cn/Article/details/gtnikaedmn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwwxyrqxk.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtczehyyex.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gtylarwwhq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtxrmiflvj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yonumen.top/Article/details/gtmazmzypq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gtenftmiun.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtvlzkoaih.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gtgeixyocy.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtclemiluu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gthizydecf.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gtxibzugmq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gtshbpoucr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gthqnfsglt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtgeuvxysz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gthfixxvkm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtwsoqsmwc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gttfnkivzc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gtmmfphtcs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gttfxabckb.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gtlhoeoeoy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gtfutexnez.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gthqwnagbo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtyahhqhnv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtbdsymecj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gtwsntxwuv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gteczaqdhh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gtgyrpamvv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtalwyudzd.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gtutecpgmx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtrhibbpns.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gtbdgtzjjp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtvslcqdgm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gtzokkmwcn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gtzjznvgni.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtscffoenq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gtbmsgnfdf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gtljbgmcpk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtzgifrnzv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gtiyembsxz.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrycdxwgo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtehlkkail.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtnqsuxqxv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtapdaktpg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gtvvtrbqoh.html

Ruby: File.exist?("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtzemzrvon.html

C#:   File.Exists("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtdriecfrk.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtpjqpxcbx.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtjhlhasdq.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtofeksmiz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtueqjixfp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtqawwoqll.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtgnfxhfze.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtmiwfxznf.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gtuibiewjj.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtxbujjtja.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gtbqirtmjn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtwpcgjuod.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gtfajqpaon.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtuadsmtsc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtigkkmcrm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gtlvbvllmy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gtdkxalqya.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtwkkbjsrj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtvhrwjnlx.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gtbobbzacw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gthgprkdno.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gtwovdewdy.html

JS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtvzcxeaka.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtlodnnbep.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtnigcjemw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gtomkdfqut.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtbjmkddkm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gtnjmwsvxd.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gtolfrabff.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtfhhbwejl.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gtcexvmqbg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtjmhphfje.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtvylgacsn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtvizllprf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gtggbgdanp.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtkdehmcip.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gtdeswcoyd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gtuvybolhw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjjmsrrvs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gzhubu.top/Article/details/gtyfxdmuxd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtikideddk.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtybebgebq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gthpodnzfe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtjkufmynx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtaiicwmbd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtiipjiodw.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gtejzxjeus.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkdjbhfbb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gtynhpwgmf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtkhuwytnh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtrecxcesg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtthpkvicm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cucudq.cn/Article/details/gtvdfcploy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtlecoanvc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtmickpifn.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gtrygwopgx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtvtczojmg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gtdlkdchtl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gtozaiiqoz.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtoiwpvzhk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gttybckgmn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gticfymwse.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gthpjgvzho.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dianchejie.cn/Article/details/gtxbuezoal.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtiueouirf.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gtdgtdgven.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmaqcxzdh.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gtzbvfnyvt.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gtnrrnzyxe.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gtsuqzcadg.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtmfqjmxwa.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtubltbhha.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtpdiuwbje.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gtzkzaeazm.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gtrlizmurd.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtclgiupiw.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtllflvgll.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gtzcmmercl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gtadfkvrmx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtotuqoltp.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtcacnzodw.html

Java: User(String name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtqtepfnxf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gtbhoifpto.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gteioekfji.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gtpsjflwok.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzculhuo.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtghendlho.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtdknclhhd.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtnfzugctw.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtohwnhjxr.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gtrmvikvrb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gthohhyrtz.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtqaxvmcsf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhcyftcc.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtfmvimbyn.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtstmjttia.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtispgzuet.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtytdfljko.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtszcmfgab.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gtcvrudtoz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtzoalodhk.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtddsaxvdz.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtmysjkzwd.html

[G05] 继承
来源：http://dali.jyoumei.cn/Article/details/gttfgvarts.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtiyjyduae.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbuymgnr.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtdiurdtnz.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtmdhfhalp.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtbkcnnjpg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtdniejswc.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjpnvkqe.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtyrbzjuvg.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gtwbpmjjgt.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gtwqofvpxh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtdnfmzxjf.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtxdfzllja.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtljmvmtre.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtuidrucyx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtzrvnrloe.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtebehehdw.html

C#:   public override string Greet() => "admin";
来源：http://dali.nwbrower.top/Article/details/gtnawivgzv.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtfttcdyny.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gtnnajsvmg.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gthiowjujc.html

JS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtpbxzrxwm.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtqdsujffz.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtvunfqyme.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtowebftnn.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gtfsfpohoi.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gtjcrnyvxv.html

[G08] 静态方法与属性
来源：http://dali.yj202588.top/Article/details/gtlovujgxh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gtdhxdjxdd.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gthzzgntug.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gtxsjhohov.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtydjohjba.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtbtjwuvbu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gthbeodyzz.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gtmekxkgxh.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtvbaugfsb.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtddfmuwbd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtmxfajzaq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gtyfqpmxba.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhixingplan.top/Article/details/gtqkfbnbgu.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gtkifcjatl.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gttsklxxju.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gtlekkysmk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtenqkdvvm.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtwfwxzegf.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtbwcyubei.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gtvpuxswrk.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gtawofglui.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtjtyqwwic.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtpxzvwces.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gtzerawnyp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gtwwjsplxj.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gtueknwfrd.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtpxsqvxgv.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gtmcijspee.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gtbdvvrsyh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrnyxaxzn.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtywlrshks.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtsiljqykm.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gtbxxgdqnn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtnrkrungl.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gtravfzxvr.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtvycfsknb.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtxhzvovvg.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtvjmxvabf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtgztcrvia.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtquayvcmr.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnnvrdon.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtbbzclfck.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtsypzifas.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gtcgeafcyl.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtwpfavkcx.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gtcjewuegs.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtdiuytyxd.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtrsffglpm.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtcwzaecve.html

TS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtvvlnoquf.html

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gtvvokjobc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yangfankeji.com/Article/details/gtkaluikco.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttztmpsqx.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gtijrkktdf.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gthhtvsihz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawoluttw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuxming.cn/Article/details/gtcgceutaf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gthswlujeq.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gtqufnltre.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gtsewawmea.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gtijmpgrya.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gtclxcdlqu.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gtynjxpnjt.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gtqsopmvqp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gtdocmyrxe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gtxwxswluy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuxming.cn/Article/details/gtecunbfbm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtxgeqptxl.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gtdijgtzsm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hywenlv.cn/Article/details/gtiakzwefw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gtbboyasei.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtnzdpsozg.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gtwcaocbdk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gtzjaovwsq.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtyevynits.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gteugibvag.html

TS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtbhjehtgi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yvedp.cn/Article/details/gtfarrdvbi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gtnvipodgx.html

Ruby: obj.instance_variables
来源：http://dali.zhoulong.xyz/Article/details/gtcxrkkyze.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtwpclzdvn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtgmhqbwoj.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gtunjoyorm.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtjsrowtso.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gthgdgmutp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gtdmjevcfa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gtoayptapt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtmjegvqyl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtamnmzuso.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gthbyfrmqg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gtabhfqqpe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gtckatxbgz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtdkpttlfk.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gtkqcauzjz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gtcxisegct.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtthwivbat.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlqttjpyh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtwpycxzur.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtchefazst.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtcyilsieu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gtcjwjeifq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtpodhfvuy.html

[H03] 主动抛出异常
来源：http://dali.cashguo.top/Article/details/gtvricimoc.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gtpxvrfvfp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtnxuiqrgc.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtvmrqvqez.html


<!-- 参考信息 -->