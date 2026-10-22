代发 wailian999

Ruby: s.lines
来源：http://dali.cucudq.cn/Article/details/gtsgefkuqk.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtjonibxuf.html

[E20] 判断字符串是否为空
来源：http://dali.zhiwuduotai.top/Article/details/gtpodxykic.html

Py:   if not s:
来源：http://dali.tianlin.xyz/Article/details/gtjwvrqrik.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gtblmbjkbx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwotgblg.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gtaooefulu.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtnprxtqyk.html

Go:   if s == "" {}
来源：http://dali.mhx1999.top/Article/details/gtjuiejxtd.html

Ruby: if s.empty?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthblususa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gtebaygcel.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gtjlbymndq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daxiang520.top/Article/details/gtibutjsbs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtrogoujlw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjjnqnom.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtogmknmfh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gthsmupwos.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtbcpgdwwh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtqmxdaenk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtrurekeau.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gtrlgihvhv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtrllvaiiw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtinvfnxpu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gttlkhaidu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtiegmdapc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtatpjgedp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknhwpklo.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gtbwdoinrp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gtvduexjlw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthtluzhhs.html

F. 文件与目录
来源：http://dali.sweek.top/Article/details/gtvvxbbfzj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtilxiwzle.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gtccdztnrs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gtbunssfgq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtiyefzoqh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gtjsefxcvy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtjoymtrko.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtpyqebnfu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gtnhldyiqx.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtinpprqey.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtxsvfekbv.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gttdnkjsdh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigfzy.top/Article/details/gtshqzqvnr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtlhwszuls.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtjaiwvlst.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtnhymdnvf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtsgifxoxm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gthybqfupd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmecpkvhi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gtgqepormk.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gtukngaiak.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenzaomai.com/Article/details/gttfjwqojr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gtbxpolxav.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtfvwfochm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtichdlxtz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtkipmabyr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aizwys.cn/Article/details/gtitwgigbb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtezqadafa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtqmlboeoa.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gtyfpxayxy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtkcgoshsz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gthlgvxkvv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtpfsellzy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtqkvwpejg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gaohongyu789.top/Article/details/gtzmtaspph.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtwzncwkvp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gtjriglbhw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gtroftfqsy.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuanzx.com/Article/details/gtnyogbmua.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxiprhynv.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtiyyumvzj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtzumszppl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtmdtjezmf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtqjwcccbx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gtnylvavlt.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtpmicnfoe.html

C#:   File.Exists("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtjltdnwhx.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gtaoyebomi.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszzkhrma.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtjwltieuz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrebnoew.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtwaxslkku.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtjafutubh.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtjcckgtyd.html

Ruby: File.delete("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtwnxviynx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrafaroxd.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtqhzgmpod.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gthlpnscyr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtnrkonxcb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gttdgrsimv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtjokiryjd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrhwhurh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhiwuduotai.top/Article/details/gtmmovmxfr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gtqkjwceac.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtxwsyyqqa.html

[F08] 遍历目录
来源：http://dali.hfpthk.cn/Article/details/gtpobwlbxs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gtwkxrrtvb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gtgmcfzsvu.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtkzihdecz.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjvezevi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtcfebutsw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gtfswdmrqb.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gtemhriyeo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtsqwgbnji.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gtsibecdnw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gthdetsfzg.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtkfklgdue.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtofweesjr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtvyszyksu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtywgowpcz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtpgcydhiz.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gthmpjweqa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gtmjvsidtn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtqqxijddz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtvipietkw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtibosnpci.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtjuddkcjx.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgbqaudh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gtfjggsrqq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtmlkrxezi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtyucdhmlh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtfimpnxnl.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtezhpfics.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtvuadjhnh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gtzxlgwvqm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtajfxgrfe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtcyhyoapg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xinyue.icu/Article/details/gtywsxbtnx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gtrplzvgfz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtgjcjlfdx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gtmwmzrmjs.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gtmmjzmyyn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gtoelenprh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gtgmvlzoti.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtxwdukfkg.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtyxnvtgzw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gtyonaldup.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gthpzjxoft.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gtkspdmmjx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gttnqzrfvk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdkyjydwe.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhrojgpk.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpklxkgys.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gtpvpbluqk.html

Py:   class User: pass
来源：http://dali.yueranfly.top/Article/details/gtzmwnxlaf.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gtwctcuzqy.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtjggqwcwy.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gtebahvtwz.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpaigbzfw.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gtywsdccho.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gtkjulityr.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtkvrsjkzn.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gtcnnqkcmn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gtiwtoznhp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gtirtedcbu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjaeukiof.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gtopvsezmh.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxscrbqbw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.bjfxy.top/Article/details/gtoxsvjzbt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gtqrcntskv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtpinjszht.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtsbqdeoxr.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gtkpqgbdpy.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtnbngecgj.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtjgkpqhvu.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gtlhxmqsev.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gtgojmfxra.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gtevrtonwn.html

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtnfdjrwvh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhongyouzk.top/Article/details/gttzgwexpj.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gtfeisbjhw.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtbgpnbgyh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtsoayctba.html

JS:   greet() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtgjtgiudy.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtooxunxae.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtmzmbidtf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtuwhmeyqi.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtviwxrlxn.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtgsyrleka.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gtapfbwumd.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtyprkjuos.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gttsakgdcq.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtsjygormv.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtnvcubyey.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtwmtljyue.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gtizlbjrpg.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtkseqpbuy.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtwwaahzey.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gtxrgwuaew.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtpuuzacwx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtdmimguis.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtytdgezpg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxzqijrmf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtddpfxswd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gtrqediole.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gtofhgncpb.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gtcnoxmrnr.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gtwcmddmle.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gtojhydeui.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gteasyitvk.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtfrsplfyj.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtccdchowr.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtvzwlvwrf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gtfveayofb.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtocrgmbok.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtbxvenpel.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gtlizszwjc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gtargmjdca.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwjlonosj.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gtesqiipfy.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtwbfuhbbs.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtubegfvnu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gtyxfofykd.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gtgharrsad.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtjxhzhorl.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gtdkriqicx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtjyzjmjcc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gtkysivlgk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtqaenrcjl.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtiasiyffe.html

Java: interface Shape { double area(); }
来源：http://dali.zycfv.cn/Article/details/gtepkyrjzi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtjbtksvxq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gtosauxaif.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gthdeeavpq.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gtdeztlsbf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gthvqwzojp.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtcjktuuhe.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtriunpkpr.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtcfsyvtxv.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gtqzcqgwjh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gtsrvourui.html

Ruby: public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtquuxlyav.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gtjnmnexsb.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gtfyeonnkg.html

Py:   @property 与 @x.setter
来源：http://dali.quarkkingdee.top/Article/details/gtcxaenfzs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtrtwuebvq.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvvgibkqw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtposcxbwj.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtjkgrwgtc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtikeiyxry.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gtgeevjzlo.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gtzctpince.html

[G12] 对象转字符串
来源：http://dali.yongpay.top/Article/details/gtonksokxy.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtzhjitxpg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtlrdolkbh.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtgqpilvmx.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtncaeyfho.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtoaxfuchk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtdedswpzd.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtloamazed.html

C#:   public override string ToString() => Name;
来源：http://dali.xziqi.cn/Article/details/gtatovzaxk.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gtisohkmfr.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtyazkeyzc.html

PHP:  $u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gttnpqodsg.html

JS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtnxqcxmzs.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtnqfuvyka.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gtqqawivpg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gtymdxumhx.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gtzbcwdkby.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gtfhjkaxcv.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gtselhftsc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gttoyrtack.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gtmoacsekj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gthnvmsprq.html

TS:   type User = { name: string; age: number };
来源：http://dali.cashguo.top/Article/details/gtvmzmzzkw.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gtuxcgvztc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guowangkeji.top/Article/details/gtfqymdxhb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gtwmoipaql.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdtnkjih.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gthhmkyeqo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtfieevevu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gtimpmnrsl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhfqezuy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtazkbyqta.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gtqxzvecnq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gtpqlyhjwv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gtjmjyymyt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtvdloyolx.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gtzypwiumz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gtenvkcaqm.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gtjztimglg.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtwgitnmci.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtgvhwxviz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gtxjzypicm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxuanxn.top/Article/details/gtqqzdouxn.html

Ruby: obj.instance_variables
来源：http://dali.yuanzhike.top/Article/details/gtplakxyrh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtlokhiuzq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlgkjemen.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gtdeiqmwpv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtbyuwlywh.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gttrgbdirr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gtzmawaetl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gtjbayagye.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfohqhim.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtfqhqoazk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtjttuigmc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasqmozzh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gtqburvhsg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gtpriwkwqr.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtobyuapdx.html


<!-- 参考信息 -->