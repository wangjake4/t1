代发 wailian999

Go:   if s == "" {}
来源：http://dali.jyoumei.cn/Article/details/gtgvxilscm.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gtyrkeviil.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hywenlv.cn/Article/details/gtlxhojjri.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gtdgdvmcwz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gtdukomgph.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtxpzjorii.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtsteqznom.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gttvwubzuk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtztrfxgtj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gthbqiklfd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtiqegxldq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtsbkxcbxk.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gteqwtabql.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybxqqdrh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtiuphprwi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtngtzakfa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtopczdzfy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gtezjwlmlc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtbbdkwnko.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtlazwpwkx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtcpzjjlqy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmjnrippt.html

F. 文件与目录
来源：http://dali.daria6918.cn/Article/details/gtfhofvate.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttyjuhbbo.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gtyplodeag.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gtidiuyjrq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtzzermmzx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gtatnaneac.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtgnpljyjk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwknnofo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gtgmunnnsb.html

Ruby: File.read("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtomvbrcil.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtbpvtcene.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gttdbkvbpr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yvedp.cn/Article/details/gtqwdubuka.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtdkwmpahs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gtcqzyufjx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtixmpnlkn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtngsodvfn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gtaysjbtbd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gtaykgbvzx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gtovkpovij.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gtpwmvloyh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomzdxmhp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtgkmhmuhu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtzdwjiapt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtjvcpjmwn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtuxmihucs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gtmtifcusn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhoulong.xyz/Article/details/gttmayqxzj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbwqntxc.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gtjdxdxvos.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezloaswn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gtlhnphjfr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtgmkokiwi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtxsymqsxw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gtdzzntggg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtdgmzytta.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gteecjnwbs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtxqtwrxbk.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gtkoxnshox.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gtwlrtunpf.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtpgrcepft.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtqejeuscb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtpxubqonz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtaueemcwl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gtbrpntwzj.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gtejmtzbnm.html

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtayvdwamu.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gtsjoriorm.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtxjwmamnp.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtxmpbitxl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gthtnuzoxu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtbedlttvv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gteqzccicn.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmmlskaa.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtvkgigkhe.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtyemkyqba.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gtyfenadmc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.vqdsnc.cn/Article/details/gtsbkabwnz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gtufydmvky.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtrzwcppsl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtvmatfhyz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gtjzonkpxc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gtfswytgsz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gtdbiciula.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtvevbqdem.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gtqknkxbmo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gtqpjzgpud.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gtjmurzgks.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtvqxrnyxn.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gttjebdwoa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtdergmrjd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gtoiaawceq.html

Ruby: Dir.children("dir")
来源：http://dali.tianlin.xyz/Article/details/gtcgyauoul.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtgyaceklr.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gtksfatbuj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gttndvodwg.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtlsyzvsae.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtusobookk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtlvvojizs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsughucsp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gtuonpirzj.html

Ruby: File.size("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtoqhdgkpw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gtphdqzyzc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ehwqpu.com/Article/details/gtkyneeuic.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtmdhvzxqm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtzglaoeyp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtartuqsrp.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gthoiwiosf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gtaxopglbw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtijozqggg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtlusbdhwu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxcwfuqws.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gtgyvxqipj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtlkogyogk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtfnpnbbit.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtbnbsdlel.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtaqujgqzr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtthviuith.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gtinrlsuzj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gthyjnawgw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ppjwa.cn/Article/details/gtlkwothqb.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gtmscyhchu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gtkspksbpl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gtwhktgckf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtslfkczpl.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtkmovdzmo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gtbemsmpjo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gtyhruurev.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258888.top/Article/details/gtnbvbkklp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gtgdedlzhd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtozdrduez.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvtrhclj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtahcsrztt.html

[G01] 定义类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenbkcpih.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gtbhtzbbwr.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gtrkasranr.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtjdfljjxp.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzdmhvyol.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtwqucbsyl.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gtjujdtlpo.html

Ruby: class User; end
来源：http://dali.yueranfly.top/Article/details/gtemgexeyn.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gtvzsqykdj.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtwqgiulgu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gtnwflxrdm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cqqwz.cn/Article/details/gtasbuesaf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtubxuqdms.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzujdnszt.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtibfzrskq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gtypskzypk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gtlbaqyrbw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtgjbuqjoj.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gtyqzbcsny.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtelajkkgm.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gtxeyitaot.html

JS:   this.name = "x";
来源：http://dali.yongpay.top/Article/details/gtuofboupt.html

TS:   name: string = "x";
来源：http://dali.cucudq.cn/Article/details/gtfasfbmpz.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gtrukupapb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtfmqllpjb.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gtergzrgmi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gtbtvsykpj.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gtwlfjkdxb.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtlgcmujqg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtcfqlmubu.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtuzxymecg.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtxfurtuzf.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtbntjbseo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtrpofxuqo.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gtcuzvarol.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gtdgwmwemp.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gtiaecgfer.html

Py:   class Admin(User): pass
来源：http://dali.zhoulong.xyz/Article/details/gtjkjrpjuq.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtxoghkysp.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoabfsqbv.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtfzswwenk.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtrdmtfvsb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gtkltegjjg.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtnxalzbru.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gtsvrvmzne.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gtefxjyedc.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangtech.top/Article/details/gthjgdyrfv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtzyuoloqf.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzevgzscx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtebdmrbwa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtupeyphea.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gtaqbiwhws.html

Ruby: def greet; "admin"; end
来源：http://dali.tianlin.xyz/Article/details/gtisgxuhfe.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gthxrmuegx.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtfjpnnbzf.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtjrtazvdx.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gtiiodfngo.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtlkklmgxr.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtwqzuotzp.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtkcziaohk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gtsgbwfffb.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gtnberpcwp.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtecswbsmt.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfglqlhr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gtwzcofcck.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gtawfyxlyx.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtogmpnree.html

TS:   static f(): void {}
来源：http://dali.yueranfly.top/Article/details/gttvxmzpzp.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaveelic.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gtubhzlawo.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtbptygete.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gtmnjddilp.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtoxbengsw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gtgtsmwmgl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtgheretrl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtaibhtytr.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpzfabjrt.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gtjgxmhirm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gtpgxphyaw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cashguo.top/Article/details/gtcrstfkba.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gtayavlivw.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gtyhsxepyi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shzxlz.cn/Article/details/gtjygilwni.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtcgfllcob.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gtyjhogqpd.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtbrjumdov.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gttohyvhgg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gtbpjyczgv.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtjmxivmdo.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtevzuzwaa.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gtwmujjfyz.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gtwbudcqel.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkbhauxw.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtnoswejsv.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtapkvpmkm.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtojohqkcv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtgzplmhac.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gtjtryhuam.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gtzhcbixtz.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtntcgblze.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtererzjwu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwacplkhi.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtfykmbigu.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtbojpprme.html

Java: @Override public String toString() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtsedaefcd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtfqrozjzn.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtamcpxcwx.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gttdpivejg.html

[G13] 判断对象类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtifuccmoh.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtfytfwgaf.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtoxepwcsi.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtnflgbsni.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtkpprbmys.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtfpjddxvc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtgpxvfkrt.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtbesuazwh.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gtwghkjaga.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gtglygcsdr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gtjvibwtge.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtvvwzaxxs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gtqzofiato.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gtuikrulsl.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gtwjvkxpum.html

Go:   type User struct { Name string; Age int }
来源：http://dali.0kj1m.cn/Article/details/gtwmnckwkt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtznwsqfhb.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gttgboqavd.html

[G15] 枚举
来源：http://dali.zhixingplan.top/Article/details/gttojizdhc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtbcwjdmjs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gtufyaucsk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtqlwhoheq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtigfvkgej.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gtbxjmtwnu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtonihdkyc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gtmtheekep.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmyzxnxb.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gtlscapyzv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtbtbdozje.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gtfnfwozaj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtqyhaxqzw.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtqywipvjd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gtjuswnfyr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gtkvmeqfbw.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gtdqoisilv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtrczkiymc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttcdzxxlk.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstqqqnop.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtghlyinod.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gtglceoevs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gtwyuvskpp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gtyqmatqyq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtfoizaomk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtciwphkub.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gogol.net.cn/Article/details/gtgosnvvri.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsboqanu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gtsgzestxo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gtvpxrtbks.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtmflhlmbo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gtzudmgznu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtffgetnwk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtbgpxyxyf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtxmwbgbsx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtmkpqjuoc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gtpcorbeck.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtrrunutqp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtflzzvybp.html


<!-- 参考信息 -->