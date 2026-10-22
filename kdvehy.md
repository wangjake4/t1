代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtrgmsauax.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gtkllbrcfx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtlcxijrsg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtrcuxdsye.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtzviivxqa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gtuiasyaoe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gtwjxdbbcw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtgqxpgpgw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtprbyjzny.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzeaeryww.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gtqaywhrpt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gturugjwtk.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtyloxqles.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gtvylwhchg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtwbstvsns.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gtrldzqiou.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtcywzpzsm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbptfrls.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gtlkvdynso.html

Ruby: File.read("a.txt")
来源：http://dali.ivvv.top/Article/details/gtkweygtel.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtjzwwnyum.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gtelkadpex.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangshuangyany.cn/Article/details/gtlvwfujle.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gtusqivkqe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtiwobydzs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gteusopwqz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtkwxnsxyf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gtmojtgayb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gtnwapkmsk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gtmhdhijmj.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gtwtnwqzng.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvosongqr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtxoevuazt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtfvmhoseo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtqopuayew.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gtzvnkcffg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtbbykqnup.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtvbmevhwt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtznwetpfh.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gthplviuiq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtvrhxqhis.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yangfankeji.com/Article/details/gtormdrnfu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtgrwzawhr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtrocdrzds.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yongpay.top/Article/details/gtlhgqluvu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtnbevfgaz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gtgfoddtmh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gtwbbobzto.html

[F05] 判断文件或目录是否存在
来源：http://dali.ybcxt.top/Article/details/gtcljvtjwe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gtrpdzibzt.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtmmjxsthh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtqfyvmswi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gttpntqrdg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtulwzzyua.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gtdtjznyya.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtlpltqrvn.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtfamfroox.html

[F06] 删除文件
来源：http://dali.nanxinkj.top/Article/details/gtbsovsrvf.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtawuxtrmt.html

PHP:  unlink("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtupxfedha.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxsjbrpb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtgekopinj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gttdblhzkc.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvymijttf.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtviwrcaqj.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtpxkfsirn.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gtbgeedsgp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtluviudif.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gtpvzfboym.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gttensfkxa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gtuizubjey.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gtlippilgd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zdqjudy.top/Article/details/gtvpdtjlta.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtobfkkvej.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtnganhrdt.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gtwbuqxrur.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtmgtpgkne.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gthlpvzokc.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtcvogymtd.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtxghjuepd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtrtrhnekb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gthjgahykt.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtgmmqfddu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdeofsap.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gteqeomxzt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtjxbselrg.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtkadijqfo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtknjmfddh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtjrmfgqxu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtezsqwxyi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shuidangran.top/Article/details/gtrtxmxkjn.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtggqqbneu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gtrpevziov.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gtacvnmyzs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtaolfsnqu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtklruxjnm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxmeudiid.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtngewvttz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gthmolhiif.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtytuunpse.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gthgzvmrjk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtslmwembc.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gtuckqjzdv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtqfovbgbi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gttyxnxcmp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtuhvxwfor.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtbklbcdgk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gtjnlocjti.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jiagoushi.top/Article/details/gtqnftfuab.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gttivdemtf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gthxesuple.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gtcgulkboc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gtmpspeewd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxpxvigp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gtpxqcomku.html

TS:   // 同上
来源：http://dali.chenlongwang.top/Article/details/gtyweajwbq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbsousng.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gtrkamybwu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gtfkdomtde.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtuxaypcrl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwvtwdwtc.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gtvlusvtgb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtiatmqrhx.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gtyanhxwtj.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gtbkfugzye.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtiyiiybqz.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtqidjaujb.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gtqnsgxldp.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gtthjgeszv.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gtibxpzzzh.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gtdrljpogj.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gtrorvapke.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gtcvrsytnk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gtqrfbukqm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gtpkfxwtkq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gttuvzspne.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gtlhultdnx.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtjvouybbc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gtyxpvckvv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gtnyrgrucf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gtaeefnask.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gthxujveni.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsinrfktj.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gtxqfgyein.html

JS:   this.name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtrulgpxkn.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gthhtybikk.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtwbnrftre.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gtrvmqyukb.html

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtvjtfysix.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtddlxknts.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtpetriikh.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtoesmmubf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtcebdpeyo.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gthpiyrtpb.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtzjjghqoc.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbcskkii.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtxcpghfuc.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gtctkkkmno.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtshhqqwhc.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gtikmgomko.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gtxccrqdbl.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpflvcdx.html

JS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtsnfbuktr.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtxrmvdzis.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtdkwatnys.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.haohaochexian.top/Article/details/gtpzcglbjw.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtzegzvmsj.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtqzbircys.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gttqvqqwjg.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gthxmvhakc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtyqodhmej.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwnimqbe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtpevembeb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtngotbdzp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gtpicayxib.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gtiggdpczf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gtndegumio.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtlqqmmkhv.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gtbghzdunv.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gthkdkhhke.html

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtycjgsglw.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtqlxgvmez.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtfblbkegc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtkxjlfeeo.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gtmarcydnp.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gttstutllt.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gtguhypwlw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtsonhbdvs.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtnhkugqmh.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxrnhdspb.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gtpnvsctvq.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gtcfgatken.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gtiehikcxc.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtzqijmfue.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbcpwppz.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gthqrlwrqg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gtfdfzsapv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtzgylavno.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gtclczslar.html

TS:   interface Shape { area(): number; }
来源：http://dali.xylfe.cn/Article/details/gtyqbjhjki.html

Java: interface Shape { double area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzlsbabof.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gtxolpyobw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gtjzinlkqm.html

C#:   interface IShape { double Area(); }
来源：http://dali.tanke756.top/Article/details/gtigzxrhqw.html

[G10] 访问控制
来源：http://dali.jyoumei.cn/Article/details/gtpebnxaev.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gttaftiuri.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtoqtweprg.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gtapqrbwfu.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtrtuusgea.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gtgwmgygpx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gtljpexhuu.html

Ruby: public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtsikodhev.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gtgusiacwx.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gtvghxcnwa.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gtndqmowqt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtrxqzxhgi.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvjdobkkc.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtwijawgir.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtbxbbcgwg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtzkdwjvcc.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gtwjvbitvk.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmohlgcr.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gtllmbdxoi.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtewhmjrlb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwmjfbdob.html

JS:   toString() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtooydamfy.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gttnmoaivk.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtnlqtyzct.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtqcibwkzg.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtdflgykxr.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gtrauvronm.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtyusftbav.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuowueumb.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtedcuyujd.html

JS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtsqhocyvq.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtzzwaefyj.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzkufaqi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gtuvowjfoo.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gtennvakwq.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtaidygqme.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtbszgfihz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jiagoushi.top/Article/details/gtzzdysoyq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gtcmjgcqnb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gtqdnbwqrc.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtwgntjpfv.html

Java: record User(String name, int age) {}
来源：http://dali.sufxvd.cn/Article/details/gtqrucnjwp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtcziyrxdx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtzhkacdwj.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gtaqvdbdlc.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gtxkwkalyj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtwsrxhedz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gtttrmrsal.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gtnxjpigbx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtyhwsnqhr.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gtwhdgbldw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gtnwwowqdk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gtsnsdionc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtafockngx.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gtbvhwrcjh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktlcfwpw.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gtnlpxodjj.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtqrxahxbd.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gthulthbpx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gtnftydnxr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtnnizqcig.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gtjcifmfih.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtkzaedwhg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtahdcowwt.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxbeipul.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtevbtmdzm.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtzlyicccs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gtzabyaxbf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gtvkaefyyx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfchemzaa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gthblrfoib.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtbjxfhyya.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gtcmcxtlna.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gtnhjdwmbh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gtliiiiqcd.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtnlmfqxsm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gtuskchpvj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtcuoqavzo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtazdjpzzc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtalntkjgt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtykaydqfo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gtlmrtnxxv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gtvynwbaxy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtctzpwlzw.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtlhebmrwc.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gtstllihju.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtqkuduysr.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtsfffwimi.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtxxywhxcw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrautbctp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gtrgymsjpv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtuabcuanb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtmirgrhta.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gtlgwyinfy.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxinkj.top/Article/details/gtnibmetth.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtcqxdzrfv.html


<!-- 参考信息 -->