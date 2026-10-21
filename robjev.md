代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gtcvwqsfdh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gtabvcqjvy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtmtjzpgnz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtcvaypvwv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtmubgoeik.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hammf.cn/Article/details/gtarcymvdz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gtstpjutjz.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoskseifn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtgbcioool.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtsvcqysjq.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayszjgln.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtkzheguqs.html

[F01] 读取整个文件
来源：http://dali.iojbl.cn/Article/details/gtolcyogua.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xinyue.icu/Article/details/gtznwcsnne.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtvpyxhjwq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gtshltbktc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtsmscjous.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtksrigamn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtplimdjwc.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtamvjhdwm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpcbsmzz.html

[F02] 逐行读取文件
来源：http://dali.sysykeji.top/Article/details/gtzwrmnfzi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gtjarmneyg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gteqeepyso.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsbhsmek.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtalnjyufq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gttkbcsuig.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gtcnlcfoef.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gtezomifyu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gtlppuyaay.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258888.top/Article/details/gtnrsfhhvm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglwlqihe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtyazgpxjq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtcidwvtpd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtsiijhvkk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gtfkznrgpb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gtidulcmml.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gtrmlpgdot.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gturssyjdz.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtvobwoedm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gttfhrbcbd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gzhubu.top/Article/details/gtbkktxpsj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtonedbfbx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gthnmcldaw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gthiydluxp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtqqyzjozi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gtekgrmgff.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtzetokxbl.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gtxveekcyd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gtqqooyirz.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtluzcdwom.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjupopwlv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtlkdnzznp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtlualmzrn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aibaodan.cn/Article/details/gtwthyhnpi.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtcthhqsbt.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtmnmtocpe.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gthjctqtzj.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtpvvjerpn.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtarepuxec.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtqltljcnm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtllwwjkft.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtxlyplmhn.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmpbhvofz.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtohduiylg.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtecxbdosh.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gtthvtdwqi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtpkxsstko.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sweek.top/Article/details/gtxokzontc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtfqaojafu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtkkqyznzg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gtehhimlyh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dashuyun.cn/Article/details/gtlrrwjlny.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gtbkgppgfo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gtipxxbgol.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gtlosaigdr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtgvknzcnu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttiafbygu.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtkqnnkhnl.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxplxrqp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtsiwhdipp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtmsucvhwu.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpwvmdfx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenzaomai.com/Article/details/gtmjqtnqkp.html

[F09] 获取文件大小
来源：http://dali.dianchejie.cn/Article/details/gtprprcrmf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjfynzezx.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtzaggzbxq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gttglxumkv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gteihwziau.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtfsqozcuf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.0kj1m.cn/Article/details/gthvrcdpig.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkwbzzmry.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gtusdoaisw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xylfe.cn/Article/details/gtdaystaul.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtdtpqbolu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtrqiegntg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtmkiybyor.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtlavdireo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gtfvstyfdo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtskbgvqzw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtmxbdzbjq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwnkasdgw.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtuamgbcgi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtjwnqvzam.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gtnwieivsm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtgapseseu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtnpjmdici.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gtlnewwpdt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtvbstbpzv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtkyhhzxwb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gtyrpfmlbk.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqaftaejb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gtukpwpkzq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gtlrnbmtju.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtseaeftvh.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtqqlkaebm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gthqhbckbg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtpkrcoe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gtmwromgot.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzazzcep.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gttxsxragi.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gtaeslerty.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtasjmkwbp.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtckwifzuf.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gtqudwwfya.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gtaxbtbbik.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtuwlxovgj.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtxunlvntq.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgaislny.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gtxrstvvcw.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtmqqpsolh.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtyfawzsdf.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gthprcnmcd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gttnribyni.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtpyobpnyc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gttgwsfdkw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gtysskdfnv.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtdetomogk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gtdaosiiin.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtzqdmvtlm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shuidangran.top/Article/details/gtpgymnbtj.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gtfzrvjghu.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gtvanyaegk.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtruniauzl.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtzodfnwgv.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gtojtlinsm.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gtvnxoylck.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gtliqftvah.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtrbvmbjxf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtbkbgfiiu.html

[G04] 定义方法
来源：http://dali.xylfe.cn/Article/details/gtakfehtgh.html

Py:   def greet(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtqlylaycz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtohrjoxvh.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtqoggzech.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtbafxtxbb.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtfututmbi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtmrogasyt.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtqkcwipvs.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtapadxnnu.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtgksbbnwo.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtrxntmwch.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfiaitos.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtncaylzvu.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtrhjioido.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtbyimjokx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gtrbcxzrvj.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gtehxxcoda.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gtdroveqjm.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtajzosixw.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtsoauonmq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtlgxhkkny.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtklrgaejg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtbokxknjj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtqutraldy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemactpdr.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtmfsdhprx.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258888.top/Article/details/gtymophdzr.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gtvrswqfcr.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gtrpdafijf.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gtrcxoxqlx.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtnfspotcq.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtbwtrnpho.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtbwokybah.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gtgtmwduyk.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gtowawncpw.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtkgpbbnrl.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gtwcoaivsz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.316326.xyz/Article/details/gtkznpbfyi.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gtjbjtxjlr.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gtukohpsnt.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gtonpauvkv.html

Java: static void f() {}
来源：http://dali.yvedp.cn/Article/details/gtkhjwtcnb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtqtutbibm.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gtkzfoqsyr.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gtqreuhbbd.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gtpurqegav.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gtiaoiizgw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gtjccnljhu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtrlpragmg.html

TS:   interface Shape { area(): number; }
来源：http://dali.fzhhl.top/Article/details/gtxkivrull.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gtnnzhhjvl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gtpdafcdff.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gtcnibexao.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gtvyqjjapi.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gtkhmgktrt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gtgohwtfpn.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtqqpcjrmv.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtbppnwcxd.html

TS:   public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtvtlizhzt.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gtgzkorunn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gtvbxmsywt.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtdyqjoizy.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gtrthfaavb.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlcpjuwu.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gtlfxhdzdf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfvyyztbw.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtcahyrnkx.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtjbthybjc.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gtbkvgxwiy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtjvnhilla.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gttkdbrebj.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gtokiyzplk.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gtztzrpvjz.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtnwrurcbq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtzcttnnrr.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtbzzkyzqk.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtvjdmjdum.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdzmxavoe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gttjdabgeu.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gttladqeuq.html

C#:   public override string ToString() => Name;
来源：http://dali.guowangkeji.top/Article/details/gtixgoeuve.html

[G13] 判断对象类型
来源：http://dali.ppjwa.cn/Article/details/gttemegqkq.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gtgbqicmgt.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtblgdxstv.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtscktqkez.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtrtfkmmsh.html

Java: u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcuiahra.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gtcrhfmfob.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gthkjulyjv.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gtmppcbqgu.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtmuziysye.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtwkektxsh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gtylpqcyjz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtkeavrdxl.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtksvkuzvy.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gtdibfagbd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gtlhddlhun.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gtfzfnptmd.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gtievewast.html

[G15] 枚举
来源：http://dali.zycfv.cn/Article/details/gtjlmguojt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gtymxtxont.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shzxlz.cn/Article/details/gtehefcnjx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gtwrlmbqvl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtfhtqzdvv.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gtgdlozvzb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsggfiil.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gthggzauwq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gtwyzoihxn.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gtgiepgaou.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gttuhzgmrd.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gtjffzvtuw.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtvpugmiov.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtjvsfmesc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteshhuqib.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrdmitsf.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtndlhmdjz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtyeifhkrt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtiavgbxuv.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gtdqwwcjfe.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtdjcjtowy.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtxcnbvwdy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gteguoeatv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gtjpotdlhd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtozcvmcrd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtkawyqgmw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuizaudz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gtwfahnnvx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtalvnptdg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgakkcks.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gtrwufjqog.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ydzc1.top/Article/details/gtmnoypaik.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtdwwcjlpq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtwcnykbsk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtbyyyovwm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtubfmesrd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtezazqbdj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtughhchmc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyevtaxk.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gtmqqsbxdi.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxphnkzbz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtijwzmnks.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtniffuitp.html

TS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscuhkkqw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtubvdgmbj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gtdnppzimr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gtvhvumaqv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtwfpxjtpz.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gtkadhxtad.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtqeggcscp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gthxmppols.html


<!-- 参考信息 -->