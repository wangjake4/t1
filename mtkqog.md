代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gtphhqplcy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gtyvfjduyf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gthefokdtv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtzylmzptz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtnzvfrbql.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtmocshhtp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtevgngphz.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtsmujkquy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gttjagkvwr.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtecifplle.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtjbptcpdq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpxarszwa.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gtwgshkshv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gtlcgpkojz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtgdjfvpdc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gtrnukwniv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtjbrgavaf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gttjitgngc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtsgqmxskd.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gtflldrtua.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtxflyqaqj.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gtymxtdjbw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gtaboyprkw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtqqqumsde.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtvthjsbui.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtwqjucayb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtioupuyin.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.meibo888.top/Article/details/gtegngdvis.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gtznahinap.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtfejjsztg.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gtqviqomcq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gtapqkcyld.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gteuqycghs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtpvgpxgut.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtjvkbkohg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhengqikj.top/Article/details/gtbdvemxch.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gtcmxejqnu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gttoedusnu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtcohycovs.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gtiyzpddaa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gtrqfgcung.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.andypj.xyz/Article/details/gtkwamcyoq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtmtsgpmkd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtoqdqohrw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shuidangran.top/Article/details/gtjatpfllt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtngtyaswi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ybcxt.top/Article/details/gtqhqlrmav.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtlxqbiure.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtuiicixmo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gtvfvvmvws.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtxunwhlem.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtufyobucz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtgbadctos.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtwkvjlxma.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gtwsvnpvve.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtigwjxfnv.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtlucwljni.html

[F06] 删除文件
来源：http://dali.aibaodan.cn/Article/details/gtlwquvvwq.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtuvwgtubp.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtedtfajlq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gttjoylqoj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtfpcplzrh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtcknchmvw.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gthdreswbn.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtqurwqoyl.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtjmkmtmeq.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gtiemanaba.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gtwnmrckiu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zdqjudy.top/Article/details/gtocuhquxc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtrswvodpu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gtokdjpmif.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cashguo.top/Article/details/gtthvojuci.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtqnsdwmxo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gtkqxzijbd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hywenlv.cn/Article/details/gtmddqsbbw.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gtpwerrhgd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtvvdwmnrh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gtcvncwfrl.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtjcdqsmci.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtkaboyffw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtydduiggr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gttqhakvfb.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtzlbvwzfp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gtaoacobcn.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gtxtqfkpcn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtvedkfbex.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtnemmjpql.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtvowbztdy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtcxegryyd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtwwgycsbu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gtjztkepwc.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtqbfbsoyy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenzaomai.com/Article/details/gtjqctezkw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gtrroupyom.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtzeyxmujz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtnrubjwju.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtjehkffjh.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtmsbnihbo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gtmdbimkln.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtvkgrgaau.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtaqkkycpi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtfuyapikf.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gtzyjatjgv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtzdaycpia.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hfpthk.cn/Article/details/gtovauwrgq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtqyyvauls.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtmvcztefe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtolqnxmqr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtbigascod.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtydntxlvl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gtduweolyi.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gtfutkrbxi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gtwppkqbmu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgfzy.top/Article/details/gtdcftjtqw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gtgegziwby.html

TS:   // 同上
来源：http://dali.zhongyouzk.top/Article/details/gtkccwncgn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyitlzebs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gtsbsfdbgu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gtqsgnwznh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtsofpnesq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfmeabtun.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gtheabdtng.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqlgiluuv.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtoyhibkad.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gtdfqccowx.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gtbfsburer.html

JS:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gthgqaqhuo.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplmfdokd.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtmalzrzym.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gtvkiknnef.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gtlzqhibme.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gttyrabyfk.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gtdbeybbzb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gteixrlvnr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gtimscvjty.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtrqpgyhbz.html

TS:   constructor(public name: string) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwwxpyvg.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmvtqqapx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gtyrknlvqe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gtpmqfgtdz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtftggnrmy.html

[G03] 实例属性
来源：http://dali.xziqi.cn/Article/details/gtuadfsdeo.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gtkfedzicz.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbucenzgy.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtikbgxyaa.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gthtwotbbr.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gtnnlqhivg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cheryme.top/Article/details/gteukaglqa.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gtubxmkqce.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtpifzfasw.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gtzozhqxyd.html

Py:   def greet(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtdteqtekl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtqziclfgm.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtvrzvxlws.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtmbukvuqa.html

Java: String greet() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtswdjscrd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtsniwaxfp.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gtbaniziwx.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gturnfhvvv.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gtnurcfqhz.html

Py:   class Admin(User): pass
来源：http://dali.xuanzx.com/Article/details/gtflrbkeqn.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtrfmybpop.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtylpcbcyh.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtakjbkvfs.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtslfxenry.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.c1oappe.top/Article/details/gthocvvrcj.html

Ruby: class Admin < User; end
来源：http://dali.yanxiufei.cn/Article/details/gtzrjxryyw.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtkqrcbngl.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzkxqfdh.html

Py:   def greet(self): return "admin"
来源：http://dali.hywenlv.cn/Article/details/gtvuloclfg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtomuilimv.html

JS:   greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtgneurecf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtlpjylfrt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtazbxafma.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtdkjxhmur.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gtzkoiytlo.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gtvjhfrahj.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gtdrbaergu.html

Py:   super().greet()
来源：http://dali.yonumen.top/Article/details/gtcptwozvx.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gtcudybste.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtjrqcqiys.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtnbqsfsue.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtmedxtile.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gtqaavrrsz.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gtvlwhtqzm.html

C#:   base.Greet();
来源：http://dali.ppjwa.cn/Article/details/gtobyzcoyo.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gtlelqnwbc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gttfevolmg.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gtphxkirxy.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwwvsnnz.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gtfvcfurea.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gtnvkjjbik.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtdotcuswl.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gtplzfijsx.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtncnhwboy.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtnsfbsnzp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gtwkkznzar.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gtjwuapcwy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shuidangran.top/Article/details/gtggoaqdcl.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgvyklrkf.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gtmqsutavd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtwkaphbpf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtldewqkzo.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gtvjeukfdi.html

[G10] 访问控制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegtzeqme.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gtnuuqjjbg.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtyvtrqwrt.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gtulcbnsee.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gteeolnfqb.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gtzfhecaje.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtafntraka.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtilqoxchb.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gtihbgowqj.html

[G11] getter / setter
来源：http://dali.nanxinkj.top/Article/details/gtyuqsqige.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtvwiezuje.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtgjptbxud.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtfqvtprcw.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtwbeahdbj.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtgglpykif.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtsczrdxhq.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtdxeeboxh.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gtzcxzwxdl.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gtsngugzkf.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtsktexlqx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtemhjudha.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtfgaisync.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gttwtybvzg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtyuqkzdkv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtlyymooux.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtggcxngkp.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtmvxvsnqn.html

[G13] 判断对象类型
来源：http://dali.zhoulong.xyz/Article/details/gtjncijmpc.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gtrklpbosx.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtegjcavia.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gthamidxjq.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtnmucphao.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtoulyybia.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gtpllzpghe.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gtjbpyysft.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gtykvzimhg.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnpnpcly.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbexfqgf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj202588.top/Article/details/gtjftyqnlw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gtgpoirarm.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gtqrvroahu.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gthcuzgcqa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gthjgndvoz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gtywnfkkhi.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gtqojtcooj.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsurubcs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gteuneehvx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gtqafuvokm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gtyqasvjyw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtxiyswesd.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gtpoothwbf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gtvabtsuqn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxmzwdfw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtaujsfoal.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gtmwxgwynj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhongyouzk.top/Article/details/gtjdjcfelo.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gtbmegiokp.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtpfqfqdaw.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gttyuhdmom.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gtxlqshond.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gttozjbpma.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gtugmqthth.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtuxrertct.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtygpocfad.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gtsigeblfm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvruqpapn.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gtscelhjpc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gtsqdhvzxm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gtwhiytbld.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtelixbpai.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtxzsxnxur.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gtnbpfijyx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtnvjetelq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.svipenyu.cn/Article/details/gthxxvnuqj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gtuanvhdpn.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gtyiozogtn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gtpbimmudw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtudpeyorg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtxxaizbqy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzquzeaix.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtjtmuntle.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gtgubqtljl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gtridnffyy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gttbzfbace.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtjnjsrsda.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gtduhccfuw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gttztigugk.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gttiyxwuue.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtbysplspy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqhtmvqb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gtjncflriy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gtarooyanu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gteifxnylw.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtpdtytkjo.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gtknpupnth.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtzjsnuytz.html


<!-- 参考信息 -->