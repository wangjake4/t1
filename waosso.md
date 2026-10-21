代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtefqlnegh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gtwqfjhloh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtlchpyujg.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjoqesjv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtbrxerqvf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtveyaixit.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gtovwtmdkj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtryocnfdx.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzdveaaz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cqqwz.cn/Article/details/gtwbjwktei.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtyacawwfx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaspgjutd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtzmjwoxqo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtitcjfegs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gtgpmrjbmg.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtzzoopicw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtxquphdea.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtxfjfhapl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdvndqhg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gtomspfmpy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtacdmshge.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtpepbjddv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtowtdwqzq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ydzc1.top/Article/details/gtshoveomr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gtyfhkirjt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtgzzlwmib.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gthrliypgt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gtudckkndk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtqmspwvkp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gthvzfhihr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtrnxrfdjg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gttfrmzcaj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gthznxhlrk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gogol.net.cn/Article/details/gtymseoqfg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtkiylljep.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdzejysy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtthglwhjy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtdjpscmiw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtozqaegbc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtdqajodhf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gtczvmctwi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shuidangran.top/Article/details/gtislbygza.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gtbpalpncd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtatmxivjj.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxouvgee.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gtlqipigey.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtoydxqeeq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtyepquljr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtajupwlub.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtlvnbakeh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.quarkkingdee.top/Article/details/gtqfcjyavw.html

Ruby: File.exist?("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtmxdtflqv.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gtveezwfqk.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gtfkotmgrf.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsdcbguw.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtxefkcznz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gthctqyfht.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gttjgzohdq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtjyagysul.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvkbwjrf.html

Ruby: File.delete("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtovfeaumu.html

C#:   File.Delete("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvykutcb.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelnhpliq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gtmrsaqnpj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gtreuaytkr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtnurtydrs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtwrloiulr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gtxtmoumxu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gtmimancce.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gtqxgpnexj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tian-w.cn/Article/details/gtaztrykdu.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtkhdhscul.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gttykanqjb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxriespfv.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoeevrjql.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtiiydkhqi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gttgtrjakk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gtgpfgzfsy.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtmylqftdo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gtygrewdnf.html

[F09] 获取文件大小
来源：http://dali.sysykeji.top/Article/details/gtnzcjacan.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtnqyenktz.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtnjibqdvn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabrjsccg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtztarxfnp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtwrtvjeib.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvrsjney.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtbszgxacx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gthzwozxbt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gtsraigfhd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtwwdvgapp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtyjymbzfv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gteufmpllm.html

TS:   path.extname("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtahlezwju.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtkdhtrfuk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtrhhflmij.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtqgofnvke.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvlqlrbqb.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtnltaqruk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtkjadzomx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gtfrqwpiwx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtclyqzfap.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtonxeudxu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtzglktlpi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.9152youxi.cn/Article/details/gtjbnofpmv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtjitplaqb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.kuanghao11.cn/Article/details/gtsqnkegeb.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gtiugszbmv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.316326.xyz/Article/details/gtsfvsvjqp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gtlgpedsjf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gtzpjvrbnl.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtgtkciaee.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gtdlyydkbh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gtpcxmauss.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtihjytjcy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gtwdbaaivr.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrssobwyo.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gthoscahdf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtiicukusr.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gtqoabfhlk.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gtoficlvso.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gtsddwtzfi.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtldhbeedh.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtiuwlddgu.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjomplcax.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gtkcssfich.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtrjeabfvq.html

C#:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtrbstcaut.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtxwdqcict.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gtcppgnqoz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtbofctabk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtlicxyzrs.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtnqucuyrx.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gthauwsvmj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258.top/Article/details/gtjorqanel.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gthanywbif.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtpqsjzfbj.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtknbrhbqx.html

Py:   self.name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtxcevviai.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtrpkrqkvx.html

JS:   this.name = "x";
来源：http://dali.yongpay.top/Article/details/gtxcxggphw.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gtzigivtjs.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gtkvrpnynl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtfafobrqm.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gttdiymicn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gtwnlopdic.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtivnlxykl.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtnxmxnfxv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtatjqckse.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtpwzdiyjo.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtymiurrip.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtgtychqoo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtdyzcahsg.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gtrpttvuhm.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gtjizaqhcs.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtlujbcyqy.html

Py:   class Admin(User): pass
来源：http://dali.nwbrower.top/Article/details/gtnkkvpgoe.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gttpunmdse.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtvndjompv.html

TS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtfqmtyrmg.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtdhenvxzl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedbsfdbx.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtiedtdqnw.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtqfvdgdmj.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gtfnhpouyj.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gtaiblzcfn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtnkcsmgdg.html

JS:   greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtkarmcmdi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtaglfcxru.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtthrymlle.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtwvpxwjtp.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gtbttnnued.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gttqrvgpet.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtfgvdsbqy.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gtonkhbezr.html

PHP:  parent::greet();
来源：http://dali.tian-w.cn/Article/details/gtddtlvhof.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtmgxgoyge.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmlxhbcr.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtlfhszyty.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gtfansmqmu.html

Ruby: super
来源：http://dali.ydzc1.top/Article/details/gtqyqqepbu.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gtdyfpwjvm.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gtpuzijttg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gtxkahbqpc.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gtmqkqkiue.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gtujxujnjy.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gtjkljycma.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gtcxhqmlwg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtcrokfdny.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gtdhcuzlfi.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gtextxzifp.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtqiidqypl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuetiantiany.cn/Article/details/gtqhxifylh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtnovcjjxq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gtueechqda.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gtzwdybpvm.html

Java: interface Shape { double area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdnoppjqp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gtelamwery.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gtewsswxjy.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gttwdzcbnh.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtsgxiamuo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gtwlcguytz.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtlyrqqvjc.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gtmxlvuesx.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtryrmplqi.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gtshcnczgo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gtuafdgpfu.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtlwmgxtff.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gttvkjjarx.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gtwakrifjx.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtamgbzqku.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtrcdrrwbu.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtqvlmdhnb.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtjsybcnzi.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbtxkrdoe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtckanrsyy.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gtibwwstky.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtzpoenhze.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gtnwdryjrd.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtiibbzlkb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtkzdrfqlj.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtcstkobkn.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtrxcptxfl.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtlsfqdyyr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtjbfpaycy.html

Ruby: def to_s; @name; end
来源：http://dali.cashguo.top/Article/details/gtpbxefevu.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gtgvwqwgfd.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtdyvjxvyz.html

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gthyjichtt.html

PHP:  $u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtscrizwod.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzdriqbi.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtvtqlhkcl.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtynmvramy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gtiemnoxfb.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtjykuqsiz.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gtxmjpxgjq.html

[G14] 数据类 / record
来源：http://dali.jinqigufen.top/Article/details/gtbzejuaoj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtesmwglye.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gtlrlopwxq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gtetcpwkuu.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gtunozjowg.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtdcmokdzu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gtvoddbirk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gtoxlqutrq.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtzhbvxvyx.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtqabvasxh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gtwugsndkj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gtojypxlpt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtcnkrfbpi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitvlwuam.html

Java: enum Color { RED, GREEN }
来源：http://dali.jianghu66.top/Article/details/gtindmqtrs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gtmhpysxnh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gtuczogzzz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtpvzaenai.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtpotueyhc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gtjpkjecer.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gtipthmbpp.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtyoanosip.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtrglkieaj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gtglzotlyi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gtcvbtagpr.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gtejraifqo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtscgdptcb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtqcstxnju.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkuasecsa.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqaljzthy.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtvaeivcqi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gtpqkootjy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtsjbdhakd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtdsmgcmqm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtiixiutst.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hysaishi.cn/Article/details/gttihobcir.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtjckzkkbh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gtiseyeicj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gthwaxmxee.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gtrxoujdcy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gtjpcfjeev.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtucmstvgp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtysaxlzfr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gttdygyxro.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdawrodi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gtsedawcmt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gtfkatkyma.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtvoomhxzs.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gtwkcslgye.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gtjymhhiyl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtadxeaymq.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtokymikrr.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtralzkytb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtrmxhpgve.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtihgoxrhw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dashuyun.cn/Article/details/gtypravxqj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gteiekogwm.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gtyuyjjeon.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtuafgrsnp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gttwmawrec.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdotrjjzv.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtfbwjuhyq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtrmylezkz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gtkfsygwin.html


<!-- 参考信息 -->