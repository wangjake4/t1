代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtmvtpxwiq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthrsmplsj.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gtolbwacwl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthikddfae.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtalkjdypa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gthpurseth.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtygqsvcvw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gtkhmkkhsy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtdsxrvwdn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtvnrklqrn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gtnzpnbwtj.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtraisdubx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtyteonbyy.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gtdsrwskhy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtfsbatpqo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gtsajjzbif.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gteypnknvz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtmogbjgvi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gttedfbatn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gtfogugxeb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sweek.top/Article/details/gtglblgfci.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gthqnvmnvs.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gtafblwlaw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gttzraaloa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtlapvwtbu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtwaqqjdud.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtuwxuffod.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtaestlchj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gtddolrpwb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.redwolf501.top/Article/details/gtfbxrkgde.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtqwjgoflf.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtjlspjtfg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gtbzvlpwhm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gtlchkudke.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtxkaqjzhl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtvtqkxsgh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gtdhanwcmb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtnwvomsmn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj202588.top/Article/details/gtktuxypcd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gtcuzrqawx.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gtzbooinvh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxuanxn.top/Article/details/gtsqdkudts.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gttwzqfeat.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtwozdmubb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtjjwdawew.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtrvihmnza.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gtbjerfama.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzdjapod.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtirjyksqq.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gtntamjryt.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtahmxlcbk.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gtwcxerjrm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtausvjvqj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtnnjaabyd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtejmdzwmz.html

Go:   os.Remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtoawxanwu.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtawyoukbh.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gteidkkulk.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gtykcehkrd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gttktxnkph.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gtgwgsczzl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtvkojzcbz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtciesqqli.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gtopxucwol.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtlknxypdj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gttbqwppmq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.iojbl.cn/Article/details/gtezvksmsv.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gtnxtsugop.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtuelteatw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtthulducl.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtmypclojl.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtwsnxbvlh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtjwvysewn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gtwlumswxe.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gttmznnuef.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gtfhllxukv.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gtnubgnpho.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzgunbwm.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtacejgvcb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtaqbkpmmm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtotuvzruo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtxlhnllsp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtrhobdrxa.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtgdslujtd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gtrrazihgg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtyixfiddz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtfxeqkstl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gtbjgldycn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtfhmoybgq.html

TS:   path.extname("a.txt")
来源：http://dali.316326.xyz/Article/details/gtfmyzhuwi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gtlbmtedgw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtmrppkzif.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtixsdngqu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqkehxxuc.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtgyxrazvh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtryklmnpy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gtcspnlxpp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtidywmdlr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtnoevbjbw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtvlftdgfm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gttcykxkky.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtjtlmzpue.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gtckicojcw.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gthyydkpir.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gthdskmsng.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gtfeucwtny.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gtsaqhktfv.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtwrzxmllh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj202588.top/Article/details/gtetmjdiia.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shzxlz.cn/Article/details/gtzwkpuojh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yvedp.cn/Article/details/gtkqpsglhp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtsnqbiwbk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtghnvrxvt.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gtjxcdmutd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtzrcrxzil.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gthiujvcxk.html

Py:   class User: pass
来源：http://dali.birdmap.top/Article/details/gtqiyrshek.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtvdpejiia.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtmarutbhv.html

TS:   class User { name: string = ""; }
来源：http://dali.aibaodan.cn/Article/details/gtciecwzqr.html

Java: class User {}
来源：http://dali.gzhubu.top/Article/details/gtksaoakgh.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gtrfdqnynk.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gtxxbkpwlz.html

C#:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtpsquuigd.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtjmfdpite.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtgmkhfzet.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guowangkeji.top/Article/details/gtxmjlptuy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtaknadmsx.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfhlazrbc.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkkmwvffp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gtusrqnxqp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gtrwlfcmof.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtmtjedkdo.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gtirobghqp.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuyiaeeu.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gtgyryifos.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gtpxkcwdcr.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gtzzfckyai.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gthmuxnazj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gtsmqxvjmc.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotqehdnw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gttiehbixr.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtnfarrplc.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtwoolhdya.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtnqbwsyna.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtekvfrhoy.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtcbrbdmng.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtepchuodt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtdpptlwtf.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gthnkqerls.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtapzawtfh.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gtsycopojl.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gttcicubpw.html

PHP:  class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtrkefwaxf.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtqsfdjoac.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddnlpifz.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpvptijkd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gtvrzuogrq.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gtnwfawzrl.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gtdkuwzjsz.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gtzrgqpfjz.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtxzvulyrd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtnzahemyv.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgerhluob.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtwhhmawej.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtubgawdgn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gtgstfhree.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258.top/Article/details/gtvtmxvwdh.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gtzyizskew.html

[G07] 调用父类方法
来源：http://dali.zhiwuduotai.top/Article/details/gtoqleosbs.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtdpjlesfj.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtsitaoczx.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtgqriahgm.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtizzyanta.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtomcuxtnc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtxsnusyqn.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gtjxgfmjip.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gtszqnkhda.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gtrezyfyot.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbxfkewf.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtwstiviem.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtibaxpxem.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gtfjmgvszd.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtupprdadu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtcvlkpeib.html

Ruby: def self.f; end
来源：http://dali.iojbl.cn/Article/details/gtmtwlyabm.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gtatjewmzx.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdjrzzpz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cdnleiting.top/Article/details/gtebhhrwap.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtfdoqswuw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gtwqpmhlty.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcojrbxo.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtuqigbgeb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuwdzfgp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gteijpeevr.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtkspxhhps.html

[G10] 访问控制
来源：http://dali.316326.xyz/Article/details/gtephsnwkz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gtknmuytax.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtdewwzrof.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtlanqsahz.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtqrsihoag.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gtgzxupflz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gtxdxuzpmy.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkbaemwh.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gtdlwbkbgs.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gtbafyxcsj.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtfpkexhdq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbzjovilu.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtclrmwton.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtomypzoib.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtquvqjnwo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtiuuslwao.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtwyumlets.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzvmuaqk.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gtjgkqqvfo.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtpsotjbjn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtjuyvhgmf.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtnffuhssp.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtzhautjnp.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtykdeiyvh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtipiixzsd.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gttfakwyya.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtdzmpltgs.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gtvyecfhxp.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gtvezaeyej.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtfbqrygqi.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gttbbxrtpm.html

TS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtswulvwlh.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gtscsruxww.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gtqchgjxkj.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gtyaowwqfs.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gtuznczjks.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gtctfclvjk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gthjbdorpj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gtkwiytjqm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gtxbvuahmd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gtcpaiefkb.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gtmkqqxvmo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttogbikzo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gtnhzganaw.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gtyvknntmu.html

[G15] 枚举
来源：http://dali.zdqjudy.top/Article/details/gtdqcvjgfh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gtlwehzukj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gtlkmtmjec.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtiyqpsddk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtztuhmpzp.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gtrjrkojdr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dashuyun.cn/Article/details/gttvmqzjvv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gttzlkwxhp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtbkizacqj.html

[G16] 对象转数组 / 字典
来源：http://dali.sysykeji.top/Article/details/gtucuyfyvi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtokkclvrt.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gtfnhydqmr.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gteslpbycg.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzauayedr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtpemgtxqj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gtbmsqdfmv.html

Ruby: obj.instance_variables
来源：http://dali.xziqi.cn/Article/details/gttsilunms.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtjlxspbuj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtczfpruty.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtukdnrdqv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtwhmolpax.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gttixdvdhd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gtokchcldi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtikwusndn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gthgrduqoq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtbrydmquu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarzeegmw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcuzryvd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigufen.top/Article/details/gtnripgxow.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gtuijdnerj.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gtvedijyby.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gtluoefsrz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtluowhxpw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtwbipowea.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtplbocrzs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtogkbatny.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gttarejube.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtnegydjtk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtwsedndbr.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gthuhmmilv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukxqdzof.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtzcpwmuui.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtyitsxxrb.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtumqmyasz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtlrlkimdq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gtwpbpfyka.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gtpekeswkv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtscpfzbda.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gtsacfkctg.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gtcwbzcvho.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtgishpkdn.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtrevyyuie.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtglogykjt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtkfxidjqp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtueelwich.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gtlazycylo.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtalqadmle.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gtkfdnvvzs.html

Py:   except ValueError as e:
来源：http://dali.yj20258888.top/Article/details/gtdvcdclyp.html


<!-- 参考信息 -->