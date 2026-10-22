代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gtuifcefax.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.meibo888.top/Article/details/gthzrrysuu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtehcuafqf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtdpvbfybn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtvbuqbkhk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gthjplpvrd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtnmgyzxky.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtvjltrtvz.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gtgrvtkegi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gtkiemvhso.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtwxvhqwur.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gttmtykpzz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzduocht.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtmckgurfu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gtyykimqdc.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtvypysbsl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtyhyipxhp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbazlrgec.html

F. 文件与目录
来源：http://dali.cdnleiting.top/Article/details/gtcavsraki.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtwdmxaams.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gtrkvjldzg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gtwavimubw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtifzzkoeu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gtdtikgjlt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtdiqpxpmp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtxivijlmi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gtodgxxssu.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtzmzqwlrd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gthnxmfgvx.html

[F02] 逐行读取文件
来源：http://dali.guannengcc.top/Article/details/gtfeqvqbro.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gtuejjrdfl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gtctvbginu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxecswft.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtewijoqwf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtmaxteiro.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gthxswfmpg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmwoposn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtauflfzcu.html

[F03] 写入文件（覆盖）
来源：http://dali.pengpengdd.cyou/Article/details/gtvosrxpah.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gtntaqwyln.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtmecwvdrs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtaaebfjqm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtevbfuzkt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtyjfiezmx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gthnjmytrh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gtjsojsxqc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtjdsinxlp.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gtyrxpabrc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gtaajvgrwx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtikdxueqb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteprgkxby.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtqaocioqz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gtvyskzpde.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gtpnuiuieg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gtcsymowcw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dianchejie.cn/Article/details/gtzfnrplmo.html

[F05] 判断文件或目录是否存在
来源：http://dali.zdqjudy.top/Article/details/gtixqpdhxs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gtmevmyfsl.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtpofenegh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtardzzccj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtbuajetcf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtummipxnf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtjutzjwxt.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtupxutvqj.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gteuzxkqch.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gtppomfdts.html

Py:   os.remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwlktsszw.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtbscbftdz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtlcijhrqk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtdecfnqvo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxsngzif.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtolmpcgcc.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtfzdgnuln.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtazljunal.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdscixlkf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtktgcqdtc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtpoiyyxnk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtitetwdez.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtlsgbkxqs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gttxhgyqhf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gtnkednlyq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gtxfeufdmq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gtutakwkfv.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gtgilyeehv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtpzzlejwm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gtfwrthnhb.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtagnxdpzz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtakxzutvh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcodjsrp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yongpay.top/Article/details/gtgjmrqpxg.html

Ruby: Dir.children("dir")
来源：http://dali.sxryk.cn/Article/details/gtppksyvsa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxhhninh.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gtaslyfbvi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmkvzvgig.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gthnrlmmgb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtvtvensyc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtobwhqmrw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtsumwnhzn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtcdweqnuo.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtegwdnfrw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtiuuvryvh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tianlin.xyz/Article/details/gtmzvefpon.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtrcdhnkit.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gtwjsnrkgu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtzxlinskz.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtcxwixrzs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gtsediwkry.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtdnhwwnde.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtrcazttlc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtkygbuola.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gthszmoszk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtovnnswgc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gtdtxnzodb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtymadfrqm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtrhpflrtp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtsfhbeeby.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.meibo888.top/Article/details/gtnxneznfd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmssndufl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gtjclloslm.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gtjvhbznez.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gttkrsvrky.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gtbuwfbuac.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gtambldiuv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtvbqmtrkh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gtzsoyutjw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfymotqn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gtwrknmyex.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gtllklufit.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtgixlvbdx.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtboqwlmog.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshjncsmj.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gtdfalzesg.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gtauquchaj.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtmztzucat.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtlzviakbb.html

TS:   class User { name: string = ""; }
来源：http://dali.sysykeji.top/Article/details/gtqjnkyyvb.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gtamexoqai.html

Go:   type User struct { Name string }
来源：http://dali.hnxiangtu.top/Article/details/gtwjcezcxk.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gtsskhpovs.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtgafvifco.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtymogbiht.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gtsptbtvpj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gtzpfaeuqb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtqddkypej.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gtwyzhcviu.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtztflnyni.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tian-w.cn/Article/details/gtpcqrusfk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yanxiufei.cn/Article/details/gtlcoicshi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtnpgyjixw.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtjufkjtrm.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gththnrutx.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtyhibenrl.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gthqufpuga.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gtcugipifa.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtyybwsjbg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtwymtzccc.html

Ruby: @name = "x"
来源：http://dali.xylfe.cn/Article/details/gtzvwsonng.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gtyovgijfj.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gtruynmyyl.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwavvnlt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtalgaisks.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtrvxyvopu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gthdiqnqpg.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gtkobzgkna.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtvvqfoxyz.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gteznkswbj.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtovnewist.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gtsmoqrsdw.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtfqledeok.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtoidnwdsj.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchepixhh.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtttvwvask.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtoigjtshn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gtswsqqwpp.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gteixkxkfv.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gtbxryffqf.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtbyrxdwsv.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gtgltxmkqh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gthooseouy.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtpymoaojs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtestukrvu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtltasokpr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gtgnliawlp.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gtjvfebmfa.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gtmtaniott.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtaioumlps.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gtvgrxatxi.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtlluadxmj.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtvwcncsmq.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtyvsyzabp.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtjruidfpv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gtvxbinhpi.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtqgevikyg.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gtvsoporxb.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gtdugtymoi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxnygecw.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtyuckgszq.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtggtaucqi.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gtojiolkhy.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gtntnxqgyv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gtqgrlccsu.html

Ruby: def self.f; end
来源：http://dali.pengpengdd.cyou/Article/details/gtyizbmrnv.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gtulcyyhkx.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtgkndfzak.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gtxprsuybi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gthjogqqlq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gtiyuxwndk.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtyhjkgoaw.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gtlsfxnnwr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gtoonbdogw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gtbmjmgfvb.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gtocvyvwux.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gtjtgelosa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gttubrzwsh.html

PHP:  public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtvegfqvkq.html

JS:   #private 字段；其余公开
来源：http://dali.zhengqikj.top/Article/details/gtfgzrynuj.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtrwfagfda.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gtaczsaoup.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsyvkwke.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtduzbufgp.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gtqzwdsovx.html

[G11] getter / setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcavvfnur.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtfriqlyil.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtecvpmwdo.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtghtvpjxd.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtpftbvmyz.html

Java: public String getName() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtjojihfzq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtuqrnible.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gtwzhqiyzs.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtdkvyrhpj.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gtccyfqwyv.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtscnwkbwo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtllojefxe.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtjqoaupix.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtnfzwbhun.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtttqjaqyj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtitefospn.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtrrbpsyuv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtpcezgaqq.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gtxkcpnjqj.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtmubdnngm.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtameagxrx.html

JS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtmgbmpxcu.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtknzljnds.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gttgyriqyy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gthaxbijsa.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gtqfsmxpqt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtsqfixyvd.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gtuiqqjcmv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gtvcxyndvp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gtezsftqqd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnsqdzhb.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gtgmzmrxxg.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gtmylhmhmp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtwexatday.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gttheslcfb.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gtkcwnedfp.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtdgmvpzcm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gtqwnbchcn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gtfzjywjvi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yanxiufei.cn/Article/details/gtjvhghyws.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtstgckojw.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258888.top/Article/details/gtexkrsjvw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtecjjreyi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gtmrfjkjwr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtofbyuqah.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gtynkbmclq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gthdkrhtng.html

PHP:  get_object_vars($obj);
来源：http://dali.cheryme.top/Article/details/gtrtslrguo.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtsewmizzj.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtkopvecnq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gtzstdynze.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gtubmxcyth.html

Ruby: obj.instance_variables
来源：http://dali.tianlin.xyz/Article/details/gtqpycerkb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtuynlmqzn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdqcfxong.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtjcrvjyed.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtcdhtndlq.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gtnwynbrkd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gtrlgfsjtg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gtvopekjzi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtxlgcfair.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtmxcppfcu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gtnegfqkid.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gthlyaytsc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gtxnfhpyks.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gtjbvazhry.html

[H02] finally / ensure 收尾
来源：http://dali.zhiwuduotai.top/Article/details/gtsulbihqq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gtgsqxoufp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtmhsldtdh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtmqvkfoqs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbdhpazw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtoyydband.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gtapmopygb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtnqzfwndw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtyojjfbqu.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gtwtpfbexk.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtxxdybxjc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtojpdmnak.html

JS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtziivpdqm.html


<!-- 参考信息 -->