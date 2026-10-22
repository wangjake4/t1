代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2unxcruls.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gt2sttsfaap.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rjznxsmi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2rxrdkqqa.html

[E22] 字节长度与字符长度
来源：http://dali.jqgufenzy.top/Article/details/gt2icngeyvn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gt2pifichlk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2fmbnzevd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2nfuwdgwz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2zkxttwtd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gt2txnvlsuu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwmdkqes.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2jcfkhphe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2imqazaoq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2ofstbrxw.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gt2ajimtkzf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2fofmmdfv.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gt2aknclqfl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gt2wpraoaee.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2mcefpauh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gt2gdeprood.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2nwzvlnlo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2cnpsecvx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddohbyjw.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqqkptql.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2bsihwpig.html

[F02] 逐行读取文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jyytuoqb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gt2hxlbtkgm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigufen.top/Article/details/gt2bldllnjt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gt2yzkthoeq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2dqfkyqvs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gt2fbydymzy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gt2zgmgylkc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gt2wqpqmguc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gt2ahqblyid.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gt2ugmzpoiw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gt2mbhpyosg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gt2emmvqeyj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rctbtqhr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2xfpgjwgt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gt2kxgqcbqq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gt2sbyhdyvn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gt2knealbld.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gt2fptnpkqr.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gt2mdlfeajd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdahibju.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gt2jexawhiw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gt2wedwllny.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gt2wviibuii.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gt2mtdyiyhi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2wyylgpcd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gt2qxquxkdd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gt2awwhxcip.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2evrxdfrj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gt2opuhssta.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2lchagjxy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nazhnpju.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxsbfidp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnwfmizm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gt2uqtumlut.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2cpyihjrl.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2xnjmdwvz.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdtavvqx.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2vhziqsqc.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2unszamhy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2tifkfncw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2unmgsumr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2jumcimnc.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2phoepyln.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2mmldpcqy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2cgnawiqe.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2alrmqkmh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gt2muondlkr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dntuphxv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gt2nujwbwrz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2sopztqlh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.c1oappe.top/Article/details/gt2qcyrblxn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gt2akfzpsja.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gt2loaqexld.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gt2dovxjnjw.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gt2jjpjerez.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gt2bcaihcdb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gt2ewyksnbo.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gt2fngppehv.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gt2mhvgeqbu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2yfmnlfnn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2hsjtimbp.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2tfxnhpwo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdbmojvl.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gt2ffkoerbj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2soqxqwsn.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2oxsdsopr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gt2xbubutey.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gt2lydynobz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2vlknjkmw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gt2olqavcqm.html

Ruby: File.size("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2hggtpxhg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gt2xovxboyg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gt2slebzflp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2anjtdgzw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2jeauqciq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2najtvqqi.html

TS:   path.extname("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2wsxrbffn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gt2xlesugth.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2jgxttyoc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2gnwhxvrj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2dcrvpzko.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gt2qictjdrk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2txhyiqux.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jatyndnr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2snvqfjbv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2wyhludov.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2thufpeom.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gt2ijmfwcop.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2htxfsggm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hguphoav.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gt2vkiskirt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gt2ojtmsqkp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gt2wdllhwsu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gt2wfnbpjjq.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gt2dorhgkat.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpfpzxie.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gt2subqyjpa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gt2lknfvqqz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gt2whiaokyk.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2bdjwftxh.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gt2podvnddm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqdsxtcb.html

[G01] 定义类
来源：http://dali.ehwqpu.com/Article/details/gt2ihwzsqbb.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gt2fpmmicfk.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhjvliik.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2mliztcxs.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gt2epczvcgw.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2pmiaojug.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gt2exlnsaxh.html

Ruby: class User; end
来源：http://dali.shzxlz.cn/Article/details/gt2xqecfxpf.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2aoeibyna.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2wktaydka.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gt2cezhoykr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gt2iuxoskxj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2ipgzorbh.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gt2vnsdgzeg.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2tbfirrup.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pycfn.com/Article/details/gt2cvkmnnkx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gt2bsbnijbg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gt2wxwbeliz.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gt2dtwtwxwa.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2ysqunhse.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2jxstojbk.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gt2hlosrtva.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2nfxxumzd.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gt2uskskhae.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gt2iemyqctr.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gt2gehvnhau.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2iwveqwir.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cleolteb.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2pgzxlqbs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wbovxjcy.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2yeycirxe.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtpwscor.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2qovptazd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbavlgwr.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2tomcgali.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gt2auymzdri.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gt2zowauneu.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gt2edpbvcdi.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2cuwuhvcx.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2ggoiavkf.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2uzsfaeao.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2tphvgzcq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gt2mitgozgq.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gt2czssnjcw.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gt2tunaothb.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gt2vrwzshjc.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gt2yaszisyj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pxfdmomr.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2knfrbtsk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2aeseuoyt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2amgxahpk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gt2bglcwwmz.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gt2tijztxrp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gt2qsznbtar.html

[G07] 调用父类方法
来源：http://dali.zhixingplan.top/Article/details/gt2lemeiwfe.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gt2baisscsj.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2artogldz.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2ceopfrlp.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2xeaemell.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2ucczreou.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gt2qivbpvrq.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gt2jbiokicg.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqctplyl.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gt2wspdinjv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwjvrbfu.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgqombmf.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gt2njobxvuv.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lqjyxnri.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2sagzdapg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gt2hfniljgo.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gt2zsztslci.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gt2tqftcxzc.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gt2qbtuaxco.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gt2ixihlfyd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gt2eckhrijv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gt2chhxomzn.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gt2kkramzvd.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccmisuel.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gt2qbzkoxnx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnqkgqzr.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gt2tyhgtbgf.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gt2amevxays.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gt2egjfgemw.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2wqqdneya.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gt2tsyldoxj.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2puffqsjc.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gt2pwzixgpm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gt2stwxpimw.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2bxmoxzff.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gt2yvgftnoj.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gt2vucjxwen.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258888.top/Article/details/gt2vjoxkvbi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qyyyjvqo.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfxsjeke.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2ujcuxtiu.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2odjkpbbd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2fqglkmsi.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gt2bljpuiia.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gt2ulqztnmt.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gt2drrvdnhg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2tudzzkzx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gt2pljzayev.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2kurawbhz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2qgpbutxk.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2anwnoych.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2cqlbihyp.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gt2cviuztyo.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gt2shncbzao.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gt2tftcbrmx.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gt2zzpuptgz.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2trbwgcky.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2bdneerhu.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2adkrmylm.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2hxibqbjb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmxtegcn.html

Ruby: u.is_a?(User)
来源：http://dali.xziqi.cn/Article/details/gt2jmnxzqtw.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gt2pqtcvxwr.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2awrahicr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gt2bcbpapak.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gt2rubjgyxp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gt2jbpfqiwl.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjnmrlse.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2lsvwbgyz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gt2zfmaazkw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gt2hstntlhk.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gt2ryipxyiw.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2elgptqqs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gt2lwbfpbvk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gt2ksbvizhc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gt2duvlpfnc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2xziuxkko.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gt2awrvrwxr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gt2dnrcenlp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gt2oosctezz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvcupsnc.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gt2eehltqxk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gt2jsvynrhd.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gt2kcljlwtk.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2semtszvm.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2xjoywggp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxuanxn.top/Article/details/gt2hthhfilo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gt2sxypmdmt.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gt2ivyccsqv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2repdwjjp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2jtrdguyx.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gt2cwdlwinu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2etxpoyag.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gt2mvetgjib.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jiagoushi.top/Article/details/gt2zuwytqlv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gt2hxvgopwb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2yqudyxes.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gt2pnlayerq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gt2ibmuazhr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2vedoeowz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gt2vwwcnjwu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gt2vctujvzm.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gt2eegzbzkq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gt2hswvzjoo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2ugmuslad.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2vtwmiylm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2xkvqlxst.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2ueqlxkqn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gt2llxqgirh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gt2eirzwxit.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2zgooaxsp.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2flvnxrvf.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gt2jrnqwfrq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2svuwfiqm.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2bbdzoclo.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2vjnivhwe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2lucuazot.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhengqikj.top/Article/details/gt2uuxsfpqp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gt2zkwcrwkt.html


<!-- 参考信息 -->