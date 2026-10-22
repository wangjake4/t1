代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtsiqzatpc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtinfubyqv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gtuyhbcisd.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtbgfjwujr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtixpvgrun.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfdcoixin.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gtzfwetabt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrldtdvsu.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gtyisfwquo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gtfwsjsujr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gtskjsmasn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gthvokngjy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterptqpio.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtxmnyrdaq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gtcqatrivs.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdjimpfjn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtfyiqijjf.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtuxjwsllr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gtjwossknm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tianlin.xyz/Article/details/gtalldpcjq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtobgrdcgw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtiyeeezlp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtfojitydd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gtgeqokuka.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sufxvd.cn/Article/details/gtsapwqrvj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gtqofrrpcw.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gtsjrhxwki.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gtqijyrxix.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdrbaltz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtwvvxltdk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtazrbjpou.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gtqzeuezys.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtdqioskia.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gtcoxcoiog.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gttyvywfya.html

[F04] 追加写入文件
来源：http://dali.xuanzx.com/Article/details/gtcdvkxqzg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtabbztvdd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gtromvyhir.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtfgglqqfb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyqgiyze.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuetiantiany.cn/Article/details/gtaeomusjo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtaovabvjx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldtadlnk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgfzy.top/Article/details/gtfeikjcxl.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gtemrdsqxh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenzaomai.com/Article/details/gtluabtgnp.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtwryuespt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gttybnznsw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtfghpgnfy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtynarzsog.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtansaxjbf.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtojkdeeqk.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gttjdojzks.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gtcsvlepsi.html

Py:   os.remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtgpkpuxru.html

PHP:  unlink("a.txt");
来源：http://dali.cheryme.top/Article/details/gtctcrsttk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtfuspfpvs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtnulahbtj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtpaswjjns.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtkapquhye.html

Ruby: File.delete("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtxljwsebx.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtqalmovxi.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gtbnqaxfeo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrssxzjz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gtyrzamyuv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtxekpblds.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtjwfyzlbd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gtcacsdcmt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gtbssicjqz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sysykeji.top/Article/details/gtjfvzhxdm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gtabkbloyn.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gtvktmgvsm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkynmldx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gtkiwhddeq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtbexbicrq.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtvihygdbx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtcgcymvpf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xziqi.cn/Article/details/gtqjqvmjzd.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gthpptxmyi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gtzgxamsaj.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gtcyhjjxyx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gtjhizmevt.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtaqjixfib.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtqhylxfgr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtpupccbxe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtzldyebdd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yongpay.top/Article/details/gthnghfeqz.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtuidzmlni.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gtvzkfjneg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gtcdmwvjnx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtccsauutk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gttimcdwzg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtdrlmsink.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gtdrnddewp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gtctwmbfkg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtpqjhelxz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtyuojynqh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtqtvtezqz.html

[F11] 复制与移动文件
来源：http://dali.9152youxi.cn/Article/details/gtiuhzjmtz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtarqzfnfv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gtmxxvirsh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtvwmwtvrb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtssauxqkk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvuduvmo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtoonpqqkm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gteyukwetc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gtgfpjrnbb.html

[F12] CSV 读写
来源：http://dali.nwbrower.top/Article/details/gtztobngwz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yonumen.top/Article/details/gtdmkmrbkm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gtdcuyaeep.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gtgarmsvws.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtyibfnpqp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shangyingyoupin.top/Article/details/gtwhkfpnxk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gtrjkfgbvg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gtluvxcbdv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gtydvgceda.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtwntciiwi.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gtagjffnxv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtctvfhwct.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtqcihfiqf.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gtxurdtvjz.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtdfkwyjtl.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmieslfbl.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gtahmkcrqp.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gtpworslay.html

Go:   type User struct { Name string }
来源：http://dali.jqgfzy.top/Article/details/gtulxaqicw.html

Ruby: class User; end
来源：http://dali.zhoulong.xyz/Article/details/gtelcrxxve.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtlyttpsct.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gteeauowbu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gtoouwhymk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtjexvvjwm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtvhlaeped.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtspndcqco.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtndqfaeeo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtzwfonhjw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gtcbydzqvo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtzviypykf.html

[G03] 实例属性
来源：http://dali.xziqi.cn/Article/details/gtzklqbiyd.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtajlnnamc.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gtibppwoil.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtpfqupklp.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrmtntnf.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gtaxvmwwzz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gtshherthz.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtoyjtlmno.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtabjdiboy.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gttjgsgsiv.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtoatujaqh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmntfqvcy.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtoizvbkdc.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtbckxoewr.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtlspffjrw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtjuhmhpsv.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtljkzrgls.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gttiahegme.html

[G05] 继承
来源：http://dali.tian-w.cn/Article/details/gtebidzcdl.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gtmohavcxv.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtgbjlgeer.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtplqrjdle.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtdrdsoajl.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtuioojgnf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtfjbukebn.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtazmzvrwh.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gtyckclnno.html

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gtnyaiqgzc.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtsfzuvwvl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtbhxnexqs.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtrzwnpbuv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtbbcwmzws.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtcigtlwxe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gtpzmvptuq.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gtwacfousm.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtdlgjatup.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gtkxcbmxbq.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gtozfsgjsw.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gtpwvsqrgk.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtwvqtljvj.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtfvtzsteu.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gteryqbarz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gtalzoqtuq.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gtfdjkpcrp.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtynvytuqz.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gtrhahoayq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gtsrogwvgs.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gtjwvumnoo.html

JS:   static f() {}
来源：http://dali.xziqi.cn/Article/details/gtatkhavxb.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gtewjblbuf.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtpjezhver.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gtegfouwkt.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gtukornuzg.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtybsdhtup.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gtaopxhdbu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtlidofnzw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gtovdueptf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gtulxoxaxu.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gtybvzwasi.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtckskzzaq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gteysccabp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pengpengdd.cyou/Article/details/gtaklrxmhe.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtqtszojly.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrruwrviu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgufenzy.top/Article/details/gtiivhisnr.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtmgzpdpdb.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gtwasbukmr.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtbiauazzt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gtqczqqsyp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gtvgjbqgfp.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtrqzwjsij.html

C#:   public / protected / private / internal
来源：http://dali.yueranfly.top/Article/details/gtemqfjdmi.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gthowaoltn.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gtrxesglwb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtoqhhtuys.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxomuoltu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqdinzwku.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtficxctmm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtqhatzeto.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gtqpoynqvb.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtotjeykon.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gtfwbgcqyn.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtafhkpkyc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtijegzscv.html

JS:   toString() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtsrlmlkrn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gthmorexyx.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtvtrgsesw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtqycrvsvo.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtplutytcm.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtcefnpqdc.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gthoqcfghs.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtrcmdxdyo.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtviquneyb.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gteplaftis.html

TS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyiqfcrcw.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtseyyjduk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gttzpqfguv.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gthxevjorz.html

C#:   u is User
来源：http://dali.cqqwz.cn/Article/details/gtfrodbgco.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gttwpkvtfu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gthliwkskr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ybcxt.top/Article/details/gtxybisptw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnqzz.top/Article/details/gtefeejckr.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gtlhjbsphi.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtjpfqsrza.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtxahhljfo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gtqrtgszrd.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtwdnevbbf.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gtrsvbixtl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gttchsqxjn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcnchgsho.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gtjevjmwsm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtmihwlchi.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gtqtblluva.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gtzpjlapgl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gtfculicqo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtqlfufmvf.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gtbyagzkkl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gtbwdcsopm.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gtdmdmqwnm.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyisctgih.html

TS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtiooabtjj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gtrkcfjntf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gtweujhdzq.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtpwyphntg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtvshojiqa.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtkoyxjlpc.html

H. 异常与错误处理
来源：http://dali.andypj.xyz/Article/details/gtdyakbsov.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvtdidcic.html

[H01] try / catch 基础
来源：http://dali.redwolf501.top/Article/details/gttzhigzcf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gtifnrwjcd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gtonphuvnv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gthhiibinz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtfjaryste.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gtrvfxdcon.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxjvtfhw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtxaqheaqb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.svipenyu.cn/Article/details/gtzpklsiel.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gtsrblpkbc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cucudq.cn/Article/details/gtbpgbwbni.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtlpzgqyzs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtkapafevi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtmqkfndnu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzvrywwfq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangshuangyany.cn/Article/details/gtfnqnvrqh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcjvcaaj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtjaxmjjxs.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gthnteuymk.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gtwhqsdnem.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtcoqzidif.html

JS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtjhhpftws.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtzzggbsht.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtttvgyasq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gttrywapbg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvudertp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtlspvuufp.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtzgvmxbai.html

Py:   class MyError(Exception): pass
来源：http://dali.snrcjt.cn/Article/details/gtvstdtonk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtdpnrwbtd.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtmbqgblqr.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwhriiwo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtyygvtxak.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gtownchtdp.html


<!-- 参考信息 -->