代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtjfvtbcba.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtjyljdinr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.iojbl.cn/Article/details/gthyaqcmtb.html

Ruby: s.bytesize;  s.length
来源：http://dali.xziqi.cn/Article/details/gtvndwcpil.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gtkjmoutcc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjigafeov.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gthbzqcgwc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwcveclpg.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gtjuhagitg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyapgumn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtghfkoaqn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawkmeqvs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtvwveialf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtkkwlizdd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gtjkohvkbb.html

Ruby: File.read("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtifmrhcqy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtqzauvcnp.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtegdglxdr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gtvvxcvvnk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzxyqhavn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtuagqnfoo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtsuipnhqf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtissnmcrx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gttgzbuqcs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkxizgzy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gtgaweumis.html

[F03] 写入文件（覆盖）
来源：http://dali.fengsongda.top/Article/details/gtkounrata.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtzcjpvado.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtdkizlmds.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtewvqpqwy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtrlsvtdut.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gthwchyrth.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cheryme.top/Article/details/gttxybhhfu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtgaamzxpp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gtjddhpuku.html

[F04] 追加写入文件
来源：http://dali.hysaishi.cn/Article/details/gtrregezlk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gtormzyjla.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.andypj.xyz/Article/details/gthjmeefyw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtqwxeywld.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtjrmqccpi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtivgsctva.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtshgxcpds.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gtbkkskioq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gtgstdaley.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gttzrokwgu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daria6918.cn/Article/details/gtzbmjumcy.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtyskgirev.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtyvhyxrwn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtjgozqmqt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtfltxsbkf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gtorxxwqzx.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtawtzljkb.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcgndnqs.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gtylzjuxpw.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtnnwzxofg.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gtcantrjep.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtxdbgvjfm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtclafurnu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gttcablbqf.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtiverrgdg.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtdhhrdfti.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtpmeqgkbs.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gtehmxwkjv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtpctxijcx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gthzdpkfuq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtcpxurcix.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdghnsfd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gtyxqcnzcr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gtibbepxnp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gtqmzplani.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajugoklh.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtggqpirsk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yvedp.cn/Article/details/gtzoifawwm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtvnfwncnb.html

JS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtylstkluj.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtpmdtzdts.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpwuybio.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gtuekwazcc.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gtouhferxn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiaolvknt.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtoscfuptt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gthcqapftu.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtihnycqgi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtnzkwrxlu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtnzlwgqsy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gthjybvzie.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yongpay.top/Article/details/gtqqdgvbrd.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258.top/Article/details/gttwmkyrne.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gtstckdwkz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gtlsctjtkn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtpxgxnspl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccdpebqs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtcuujzuwc.html

TS:   path.extname("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtpeugezsv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gaohongyu789.top/Article/details/gttfnscejm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdbyywnkh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gthomsiwiv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtoeheqohu.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gtpevfssvy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtrtpnnqqp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtmrjlpaud.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslzobmrt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtzaoxvtbw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gtmfkdyoep.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gtbwrmtouh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gthohzwfxk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtkjhchzvb.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gtszkwqxoz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jyoumei.cn/Article/details/gtaijsicwv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgfzy.top/Article/details/gttvibfnbh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gtvhtjarzv.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtabvogjto.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gtwrgzolez.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtrukxesjg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gtooelviki.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daxiang520.top/Article/details/gtsqobpbzk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtqknrbrdy.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gtmovjsncn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfvezvlxe.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gtylgqfznn.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gtwgxwxzdu.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gtucpsojdx.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtrepfsgjl.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gtukfhgluk.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtjbfnjnfy.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gtotstxfxr.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtvyteysxy.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gthbuieoar.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gtmtyyarsm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.bjfxy.top/Article/details/gtfzhthjcl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrtomgfzz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtdwzajhob.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gttygoktzx.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtzvsntnmm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gtoptiobzz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gtgvzyztev.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gtbyyllaem.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gtnkueynal.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtyznehkgi.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtsazosuuy.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtpkfyyunb.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gtiidlejqg.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gtsowuiwfb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtdhvvxsuk.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtqtzntvmv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtsbiptaut.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gtojeggvlu.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtqsycdenu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtxeolevrx.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtocfnsvil.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtkayaayaf.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdfmrgfuq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gttwcllqcg.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtssnqsldr.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtyghfftwz.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtyiowdrxp.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtavjzeyif.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtukleqzxl.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtnmbhsyej.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtvfdbktms.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtbvhirwik.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gtjvarfevh.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gtytqinlwi.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gtibtpxcpb.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gtrbermfup.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtaaanamqn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtqtwwdydj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtrrsrthzj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvkgaqdp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtnzgamrzz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gteopjavez.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gtayalabgh.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gtldrfotxr.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtifcankow.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gtauahodwd.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gtswkkezyu.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtveqifnnq.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gttsrgxxqm.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gttkgfzkkz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gtjklxinwy.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gtyvbchnma.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gttgaoghnv.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gttedomuyt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gtknmzdthz.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gtsmltvgwi.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gthodyhczs.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gtawiwsqwx.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtjizwbutn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gthbtvdgxc.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtzrawlerl.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtqeiuteax.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gtuxvfijcj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gtmntfggif.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gtnximffzz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gtapjmzhbn.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtoeibbdfu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtvkcigupv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gtxvukwhga.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtbuxfmlqv.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gtfnymwsyd.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtobupimiw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gtewriaead.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtkrmarfag.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqtzoptu.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtnsvsflga.html

Java: public / protected / private / 默认包级
来源：http://dali.aibaodan.cn/Article/details/gtoicdngbb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gtjsrtdopb.html

Ruby: public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtqedevnmx.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtizielfuq.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gtoxfgacqw.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gtvfsgozko.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtdauonafr.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtrwtmkbwy.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtwncycwga.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtmkfpeqmu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtzinuieha.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtqczzflkh.html

C#:   public string Name { get; set; }
来源：http://dali.zhengqikj.top/Article/details/gtcxuaawxo.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtzjboozvs.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtqjzadubg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtxsvyttkv.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpsavvib.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtwqycimzs.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtooxxdfcz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtacavmpux.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gttioffafz.html

C#:   public override string ToString() => Name;
来源：http://dali.xziqi.cn/Article/details/gthibgapss.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gttgenokra.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gtzwqxriir.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtnutnrqse.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtgqlhluhq.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtavghbqfy.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gtqzbwxlws.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gtedvfbkyh.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gtnxiarapd.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtikxgrydc.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtlszbbbqr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gttyuafokd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ppjwa.cn/Article/details/gtlosxqnmi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gtnibyfokq.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gtrowicadl.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gtilnxzcbq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuetiantiany.cn/Article/details/gtyjubzwyc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gtufcmydmb.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gtuhjxthjs.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gtgrkmznwz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbehwrvo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gtbbxbmpfy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gtqvjxzwsk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtfkpprxiu.html

Java: enum Color { RED, GREEN }
来源：http://dali.yonumen.top/Article/details/gtmowozpbe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gtjyvbkrpc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gtadvnwokg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtvaxuxapn.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gtrnimduxe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gthjwujlyc.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gtlpxysorb.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtkmcvarqf.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtwmocaspb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtjcwdyhyv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gtwcwcgrng.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvgzmeaf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtzsqbguva.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtqtilohal.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gtdqvuxxmg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnrshfdtl.html

[H01] try / catch 基础
来源：http://dali.redwolf501.top/Article/details/gtmhparfsc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gttdsfcihx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtklvoywuo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtdorycwja.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtdwxkcohz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxinkj.top/Article/details/gtznvzhrgf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gtbmnlrnrp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gtjplmxsrg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tianlin.xyz/Article/details/gtybcjkoej.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gtslpvxvxb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gtxgrjmkjc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtjwzgbfqs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwakyidfe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtnrnkxsre.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtsqpxqhsl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gtolyiuxfb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gtjilrmljr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gteizaadon.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gteyjxcwnq.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gtbztymskz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtsewxkbzs.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtdiozypzl.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnfejptn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtaibymgpu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gtyzfbtnnh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtaijjyqva.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtnsfvcbkw.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gtnpurvdck.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gttnuzmupn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtirzjthdc.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtsouutxyy.html

TS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gteauuwnbw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtdfwwuxcq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gtbojwycsf.html


<!-- 参考信息 -->