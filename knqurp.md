代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gtblbmqjft.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtaemrcpwo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtorijxfsn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtllmtmhrk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtlanlyvlo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yvedp.cn/Article/details/gtpciuhlkj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtqdnhhhhe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtbgwapwdp.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gturclpwlq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gttymgwspe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtcaeyfexl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gthqzonkyq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gttwsxoevm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtkifivddz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gtyxpeydqy.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gtjaeezklq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuxming.cn/Article/details/gtkvsoccpz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtzqmsvmzc.html

F. 文件与目录
来源：http://dali.9152youxi.cn/Article/details/gtsalvzpof.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtimkptpli.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbxefhbc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtnafyizqp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcwhxvoh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gtukearbir.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtbbtdnxxm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrveltcpr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxuanxn.top/Article/details/gtilcifevq.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gtwokgneeb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gthtbqdsjg.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gtzjlkiyii.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gtohaeypwf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gtntnohpkc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtxgkbudmr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gttdcjgdea.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtepvqefas.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gtqoevpngu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gtrccxpsww.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gtyclhihbt.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gtogebaobf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gticljsifa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtodlrlbbf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtjznatzvk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtoumujwii.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtdqmqmfwg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gtehwmuqab.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtdkiadzhi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtztlyppnf.html

[F04] 追加写入文件
来源：http://dali.gogol.net.cn/Article/details/gtgblndrhw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gtwfyowbel.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hysaishi.cn/Article/details/gtowjomwbd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtuojhnzaq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsfwuobr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.quarkkingdee.top/Article/details/gtfuvpqmvd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtcgemjiqz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gtnsrjsdkj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gtpvuyjsjg.html

[F05] 判断文件或目录是否存在
来源：http://dali.ivvv.top/Article/details/gtztyffzeh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gtvevmuxpq.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtuumgsufs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtcxtlevzx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtotmdodxh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtzdsjxxnx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gtdtgmgidi.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtodpkwffr.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtgauregew.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gtshcnliqu.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtoortyxtz.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtpnvqnyee.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtutnnejja.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtnuxtsmbd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gttwujtlym.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtuumudtvv.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtoiackcqc.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtxcdneggg.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtndjiyhiz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrsbxtdi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gtcxssqere.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtbbqtbmuy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtoaljzkrj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtaftnrsjv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtpyyqbmbc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gtpxhazxds.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gtxobvnxfj.html

[F08] 遍历目录
来源：http://dali.hongshengwenyu.top/Article/details/gtwmnyosrb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gtmyybtnwi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gtobjmyrvr.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtxveogtjh.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwhcinlu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilapnmuf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sweek.top/Article/details/gthuahsggo.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gtnzztdqef.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzqcoacb.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gtfuflnxfx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtdskzqrgh.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtasvinqjr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtyohfqryn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtfizpjwvj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtriyzctkk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gtagjatolr.html

Ruby: File.size("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulbninew.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gthupzakpz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.redwolf501.top/Article/details/gtkxexeylt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtqlukxngg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtvzufdzgc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtwknchgkz.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gtccwnitnh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtqqikqwwg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gthjknemsf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gteeyssuzw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpdsqepc.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtwzafsols.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtyiwujesi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtrktcpqjl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtcuhdcolm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtvmawwboo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gtakgkssry.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gtmbwbgnyn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtldqvhfux.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gtupeblpkx.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gtucbegrhz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gtxbppdibr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.svipenyu.cn/Article/details/gtqqngkqrj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gteacptljh.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gtmbgglqae.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gtdzoxsfqj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtnptjmhkq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtauchuhka.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gtfcnhcmfe.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtfoecokug.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gtuxoivxvw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtliyrgbfg.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gtgeotzsoj.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gteymbugom.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtalhegwfc.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtsoefoajr.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gtqkfegbjd.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gtnwxeqzvs.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gtatojraay.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gtpxbiivxh.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gtnfxmqjzj.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gtbjbvjaai.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gttxojmwtm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlpqmneex.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtkfxaladb.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gtvzbhxpwe.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzoersff.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtjtiiyqzb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtypbsfmtd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtlzarwzyx.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gtubylgatg.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gtzgqlywqe.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrufjffky.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtgqfplmfo.html

TS:   name: string = "x";
来源：http://dali.c1oappe.top/Article/details/gtfxdzllaq.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gttkhyerun.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtlcwrqgff.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtecqtkbfs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtnbjlfziq.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gtsbpadslk.html

Py:   def greet(self): return self.name
来源：http://dali.sweek.top/Article/details/gtfucxhwwq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtgrafdtjw.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtcyfugrdm.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtqhwewifo.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtboopelgp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtifekylcp.html

Ruby: def greet; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtardkbbmn.html

C#:   public string Greet() => Name;
来源：http://dali.c1oappe.top/Article/details/gtzycdpuvg.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtuoajnpga.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gtlhtaxcpe.html

PHP:  class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtpimmyoiq.html

JS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtwwiyvsbn.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtblixgakk.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtpkkzteqm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.iojbl.cn/Article/details/gtazrgxkyp.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtfjceodho.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gtjabrajvu.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gttpyubudo.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtgsjfjsst.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbkhbtmcs.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtlpjwfvag.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gttrrqodcx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtusafqquw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gtbzdrmmii.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtgpgztjep.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtvanjjout.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtggqzfelq.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtzzpggnha.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtpzgzjycr.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtnsytygpf.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtdmsnzpht.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtzjaudnkj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gtusphjrxy.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gtzxsgefzb.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtdhlavgtr.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gtzwtftwcq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtkferoijp.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrkhlphf.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtllwpsugp.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gtspqzpylp.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtepocigcg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gtlarrvrlj.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtcivwitvj.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gthxbmhjar.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gtgwaicqxo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnxiangtu.top/Article/details/gtvdspcude.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gtynyjsuuh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gtwrfdctfn.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfbfdnbf.html

Java: interface Shape { double area(); }
来源：http://dali.haohaochexian.top/Article/details/gtqwktvgsc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gtyydywrom.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gtyspxdkce.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gtcudnmahu.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtxpoloiop.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gtgaupzudm.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvgicpqw.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gtbefruasp.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtfrnlryuf.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gttyolkhak.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gtbpphcpwf.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyqjggkb.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gtnyxlucti.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gtbldtxing.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gthbxsmzmc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtkccstooe.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtdqzfjray.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyueahnim.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtuoodjlai.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtoroodbgq.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gtewuvxzvs.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gtkupjzdcy.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtrqqnycna.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtcywonnhe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtvctvtkbs.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtaajcxhrm.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtbjrafzax.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtuioobkaa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtlfrbcjkn.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtpclpsgmn.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtrsmrfilj.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaetzvhn.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gtjegvqmds.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtzvopnhdl.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtsqslrwcz.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtghaxghkc.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtkdpkfidz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gtjloepapa.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gtushfqwsr.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gtitetfidp.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gttmwioiot.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gtutervywn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhongyouzk.top/Article/details/gtgnrhdinn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gtubecppku.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gtzwyzzzcn.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gterzmgwmz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gtbtilbmjj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.bjfxy.top/Article/details/gtlvxfjxuj.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gtxivynqpw.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gtfuwzxlli.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gzhubu.top/Article/details/gtxilvvbls.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gtidmqmpzh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtaunxbscq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtizxjqvpc.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gtdwczwwim.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtgyrxvxnc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gtpafdocdh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtbjwpvlbo.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtucmeseih.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtxuxiukpt.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gtaehzonrq.html

JS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtwkccjobb.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtzfritxaf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtguyewdow.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gtbkcrpevu.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtmxvyjvqz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtqztzmyyy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtuxrtmtlq.html

H. 异常与错误处理
来源：http://dali.hysaishi.cn/Article/details/gtrjdnagno.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrbdrtsix.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gthxoqxmcs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gtzwujoidt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gtuxmriggc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtueskmwli.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gttoynootq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gtqxsujtgp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gtdkjimbec.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtmqteucwi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtsmrmhfft.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gtdprhbtfc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhongyouzk.top/Article/details/gtplppacit.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtseaqvokn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtdirxegxg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtxpkrcyns.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtqljjivsv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtgdjwbzeo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gtbbjqillm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtojdiwipu.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gtltjhorxi.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gtemhoumoi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtmmtetrjf.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtdagwcpee.html


<!-- 参考信息 -->