代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.hywenlv.cn/Article/details/gtawnsuqdh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgufenzy.top/Article/details/gtugsbzbsr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtouvwbuhm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtmohldrnt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtdsfhcqix.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtdsylkcgo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pengpengdd.cyou/Article/details/gtdtiwkgeh.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtapjofucr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gtycddpudd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqxjqwydh.html

F. 文件与目录
来源：http://dali.andypj.xyz/Article/details/gtklvhoyfg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvvehbiea.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gtgnctfcfu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtvcwtzlrm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthoehiwdb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sxryk.cn/Article/details/gtdyybzifx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtrhslilem.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtzxfegjtv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtfucyyyck.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlujppuan.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtgxqmvryq.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpawggvx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gtnzgmxiti.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gthnlczbzz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtqhvpqdli.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gtbimlkruj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtmlmaveal.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gtcbhhkqxs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtudoextyz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtwcephciu.html

[F03] 写入文件（覆盖）
来源：http://dali.hfpthk.cn/Article/details/gtxyjevsul.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gtdgglkidn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtgsfxgbel.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtiujnmkec.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtreabrabw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gtqqcrdxrg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtcbzoiiof.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtxqhzmsnn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtebvqhzmn.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gtphuccoim.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtkmrsktal.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gtevijqpoe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtbghefjen.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtdvmmigpi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgekudhs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zycfv.cn/Article/details/gtyxgaqthi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gtcmtlgcvk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gtjzhtzyng.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gtuwcasbmp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jiagoushi.top/Article/details/gtegbadisf.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gtqypgznjh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtlmdoofzy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtbwpqmkxh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtlrzximlv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aibaodan.cn/Article/details/gtujptsqro.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtucfbnpxg.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtcifwvtvg.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gtaeqlkjri.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtwmgzegkr.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtoiamqhay.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtwkfctehm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtsgnzimfw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtyuhhsurs.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoauarrgz.html

Ruby: File.delete("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtinvbgfin.html

C#:   File.Delete("a.txt");
来源：http://dali.cheryme.top/Article/details/gttuqeoyvx.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtknzuik.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtiniewlaz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sweek.top/Article/details/gtfuceihio.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtgxfqeuun.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtmpwrlbvh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gtixvouupd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gtgsamuivr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gtkpcsnnvr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtmyjmdrtm.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtkavhzwcm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gtvnplevri.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gtfwqtdypz.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtwedbsrit.html

TS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtfhwutrhl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtxjuzcmle.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258888.top/Article/details/gtcyuyncmb.html

Ruby: Dir.children("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtzwpqwyjw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtknycsxxt.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqwzvcna.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtdijgbslm.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtoankpqhn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtayatakdl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtsjsizjso.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtgqgnlinn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gttvzauwrn.html

Ruby: File.size("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtoacfkvdh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtdocghrrg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gtltluiiug.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtskhqvrwx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yongpay.top/Article/details/gtpgacolze.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvrulbti.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gtullpgzuj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtqfschqmj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtsssmifky.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtycdpxlgo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtsqavkxxx.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gtsozqvniz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtfpgtqukd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gtlamswbvc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtiihlizpe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtcavrczal.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gtmlieaatr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gttrcunjos.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtelnqcohn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gtptztyhdp.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtpanqdpqj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gtdrlzodob.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gtehudbxoh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gtgqhcxijb.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gtfpilwqly.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shangyingyoupin.top/Article/details/gtqlbedsfp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gtrqsewysk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gtjzedybjy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtxspmnflw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtktyatvjj.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gtcxtruhyi.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtevfusrmf.html

[G01] 定义类
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqebmgvm.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gtpqzjrvwp.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gtdcnjvoej.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gthygtuxcc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gtxwfhnbkb.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtwwkectbb.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtmmczgcva.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gtenwzksxu.html

C#:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtrawpokkh.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gtzejucdbg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gtujdgjzcc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fzhhl.top/Article/details/gtmumkpmgr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtfijzxngn.html

TS:   constructor(public name: string) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbvorbimn.html

Java: User(String name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtbeurjzfp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gtucgdhuxz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtmlcwadfe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtwxqfcuku.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtrvobhpyl.html

Py:   self.name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtkrojpihc.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtckbjvway.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gtodrsaari.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtocaziext.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhrroehh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gtdcdaults.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtqockcupj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gtomuspcfd.html

[G04] 定义方法
来源：http://dali.dianchejie.cn/Article/details/gtrtzkkmid.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtjdyuvfam.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtaibhnalh.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtufnebaai.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtmpstiqrh.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtyjbxoeba.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtaxxrxtvt.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtrkmmvjvh.html

C#:   public string Greet() => Name;
来源：http://dali.cheryme.top/Article/details/gtuhjtgodr.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gtcruddevm.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gtrkzudbyg.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtwmommvek.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gthbmnjqwb.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtghmygylg.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtyrbbqbiw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gtvnoghpvc.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gtsbzlohke.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gtifvogjzb.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gtuleporki.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzzdauor.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtlymdhrbn.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtervubegl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtsbyfbskk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtgczkuxfh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gtcnviatht.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gtqyeczosq.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetkdvbxv.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsltnihu.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtkejdgqwk.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gtkjbhjlql.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtsbgaigob.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtdrmlrhkv.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gtncxlrmca.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258888.top/Article/details/gtntxjmfib.html

Ruby: super
来源：http://dali.wangshuangyany.cn/Article/details/gthmaoaaan.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrklfqeu.html

[G08] 静态方法与属性
来源：http://dali.jiagoushi.top/Article/details/gtldirlqua.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtpjvonxpg.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gtsjfekdds.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtohmscgdh.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gtfikfuzkw.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtfbboktvf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daria6918.cn/Article/details/gtbkbdkpjx.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtzgzfhcry.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gtctmhwzvf.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gtehppbeyu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrzlkwwf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgnfgyyf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gtsepafcqk.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gtdgdkqhww.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gtdinrdiig.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gtbajyjunr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gtxwcsavcj.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtcvnoolyi.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gthzpcbsmu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gtfngrjnfe.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtxmonlxgz.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gtrygibkwb.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtxatrqnnd.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gtqfynjgfx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cqqwz.cn/Article/details/gtwouaoyqm.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtyibpezux.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtljopozrs.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtkadckowm.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtwsumtzql.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtaoysdgor.html

JS:   get name() { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtwtloxbpw.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtzhkbuppa.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtknttjobr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtarmjbwok.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gtpkdnlssq.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtffwsodzx.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gtijjssqam.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtdxchoxqu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gttbcsoltm.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtthjsqmux.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtnqayvjhv.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtkyoxkhpn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtiwlefqep.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtspybudoa.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtzitfbrye.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gtozqibscj.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gtisxpuxkp.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtglkdvjrk.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtujtqvehu.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtjihnoeza.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtehewpnoi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtawlotxde.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gteefnrkpn.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gttbkqdjri.html

[G14] 数据类 / record
来源：http://dali.xuanzx.com/Article/details/gtropfxqvg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gtmiuuueja.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtjelgvwmh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gtlitkhtwy.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gteqjyuair.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gtyokihvqv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gtvoeuvtfj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gtqubhgjbl.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtgfaqoenv.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gthoyqyush.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.316326.xyz/Article/details/gtpcmaitpl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gtnxkrwsgd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtyelysjwv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtvplzcbqi.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gttqtruuoj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gttktdkixv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gtpovlbwkt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtfowwweiw.html

[G16] 对象转数组 / 字典
来源：http://dali.gogol.net.cn/Article/details/gtuhftdaps.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gtkgohxeqv.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gtuemdfxje.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtfsydistv.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gttmycesjw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gtnzwoiemw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtetgqgywj.html

Ruby: obj.instance_variables
来源：http://dali.snrcjt.cn/Article/details/gtlthhubqm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtgqgbogud.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmfhfobjn.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gtqlutvvrn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtnwmvapph.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gtgbicvqok.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gtdijqedco.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtefsmhful.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtmcokkfxk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtaaouexct.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxinkj.top/Article/details/gtwsvythnq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gtekgjxcje.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsldkipjq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gtirvduhud.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpjsjsvx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnqzz.top/Article/details/gtzeedznpd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtpsgbdjgy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtqqhhvmnw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtuajqtmyl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtqweeyypj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gtirclfdvf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gtsqxktzqu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtbtjpsezn.html

[H03] 主动抛出异常
来源：http://dali.meibo888.top/Article/details/gtixsthtnq.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtiojhtzzz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtrnbwtfds.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtlzeanvuc.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtmjyvedzd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcqyktzd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gtsllzeltu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gthpijnhvq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtvaxidckd.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvjejbjd.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gtovpdnrqp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtwngbrbfr.html


<!-- 参考信息 -->